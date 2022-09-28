# SIG_Peta-Kampung-Halaman

*Tutorial membuat peta menggunakan QGIS

1.  Download aplikasi QGIS terlebih dahulu. 
2.  Download dan ekstrak data Natural Earth Quick Start Kit. Lalu klik browser dan pilih file Natural_Earth_quick_start_for_QGIS_v3. Untuk membukanya klik dua kali pada file tersebut (*Gambar 1).
3.  Tunggu sampai petanya muncul (*Gambar 2).
4.  Gunakan tools pan dan zoom controls pada map navigation toolbar dan zoom pulau sumatera. Jika proyeksi yang kita inginkan sudah sesuai. Klik pada bagian project lalu pilih New Print Layout (*Gambar 3).
5.  Selanjutnya kita diminta untuk memasukkan judul untuk projek kita. Jika udah mengisi judulnya lalu klik OK (*Gambar 4).
6.  Pada bagian Print Layout klik tombol zoom full untuk menampilkan keseluruhan layout (*Gambar 5).
7.  Selanjutnya kita menambahkan peta yang kita lihat pada kanva QGIS. Klik Add Item + Add Map (*Gambar 6).
8.  Setelah add map aktif, tahan tombol kiri pada mouse lalu seret persegi panjang dimana ingin menyisipkan peta (*Gambar 7).
9.  Kemabali pada jendela utama QGIS. Matikan grup layer aktifkan yang z7 / 1:4m (*Gambar 8).
10. Selanjutnya kita menambahkan insert peta. Ganti ke jendela Print Layout. Klik Add Item + Add map. Lalu seret persegi panjang pada tempat yang ingin menambahkan insert peta. Sekarang ada 2 objek peta. Pastikan memilih peta yang benar (*Gambar 9).
11. Pilih objek map 2 yang baru dtambahkan. Selanjutnya pilih tab Item Properties. Gulir ke bawah sampai menemukan frame lalu centang frame tersebut. Disini kita dapat mengubah waena dan ketebalan dari batas bingkai sehingga mudah dibedakan dengan latar belakang peta (*Gambar 10).
12. Salah satu fitur yang dapat digunakan dapat secara otomatis menyorot area dari peta utama yang mewakili sisipan. Pilih map 1 lalu klik Item properties cari Overviews. Lalu klik Add a new overview (*Gambar 11).
13. Pilih peta 2 sebagai bingkai. Ini akan memberitahu Print Layout untuk menyorot objek Map 1 dengan luas peta yang ditampilkan objek 2 (*Gambar 12). 
13. Lanjut pilih map 1 pada panel Item lalu klik Item propeeties cari Grids lalu klik Add a new grid lalu klik Modify grids.
14. Pada bagian grids cari Appearance pada CRS kita ganti menjadi CRS:4326 - WGS84 (*Gambar 13).
15. Scroll ke bawah lalu klik Draw Coordinates. Lalu pilih format dengan custom (*Gambar 14).
16. Masukkan ekspresi berikut untuk membuat string yang mengambil nomor grid dan menambahkan simbol derjat pada peta concat(to_string(@grid_number), '°    ') (*Gambar 15).
17. Selanjutnya kita menambahkan bingkai Recatangle untuk membuat elemen peta seperti arah mata angin, skala dan label. Klik Add Items + Add Shape + Add Rectangle (*Gambar 16).
18. Kita dapat mengatur rectangle agar sesuai dengan latar belakang peta (*Gambar 17).
19. Kita juga dapat menambahkan gambar arah mata angin. Klik Add Item + Add Picture (*Gambar 18).
20. pada bagian Item properties pilih gambar yang akan digunakan (*Gambar 19).
21. Sekarang kita tambahkan skala. Klik Add Item + Add Scale Bar (*Gambar 20).
22. Selanjutnya membuat label pada peta. Klik Add Item + Add label (*Gambar 21).

