# Canny_EdgeDetection
Deteksi tepi adalah teknik analisis gambar yang penting ketika seseorang tertarik untuk mengenali objek dengan garis besarnya, dan juga dianggap sebagai langkah penting dalam memulihkan informasi dari gambar.

Algoritma Canny edge detector dinamai penemunya, John F. Canny, yang menemukan algoritma pada tahun 1986. Canny Detektor tepi biasanya mengambil gambar skala abu-abu sebagai input dan menghasilkan gambar yang menunjukkan lokasi diskontinuitas intensitas sebagai output (yaitu tepi) .
Hal pertama yang dilakukan oleh Canny edge detector adalah menggunakan Gaussian convolution untuk menghaluskan gambar input dan menghilangkan noise. Operator turunan pertama kemudian diterapkan pada gambar yang dihaluskan untuk menyoroti daerah-daerah gambar dengan turunan spasial pertama yang tinggi.

Algoritma kemudian menemukan besarnya gradien dan arah dengan menghitung turunan-x dan turunan-y, terutama karena mengetahui arah gradien sebenarnya memungkinkan kita untuk menemukan arah tepian.

Algoritme kemudian melakukan apa yang disebut penindasan non-maksimal, di mana ia melacak di sepanjang puncak yang naik dari tepi, dan menetapkan piksel-piksel yang tidak di atas bubungan ke nol, akhirnya menghasilkan garis tipis pada hasilnya.
