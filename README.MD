# PRAKTIKUM 11 - PEMROGRAMAN WEB (PHP Framework)
~~~
Subkhan Fadilah 
311910410
TI.19.A.2
~~~
## LAPORAN PRAKTIKUM
Persiapan
Mengaktifkan beberapa ekstensi php, diantaranya:
- php-json ekstension untuk bekerja dengan JSON;
- php-mysqlnd native driver untuk MySQL;
- php-xml ekstension untuk bekerja dengan XML;
- php-intl ekstensi untuk membuat aplikasi multibahasa;
- libcurl (opsional), jika ingin pakai Curl
![1](https://user-images.githubusercontent.com/56526583/122104213-a583b380-ce41-11eb-9c76-517f8c14321f.png)
Hapus tanda ; (titik koma) pada bagian extension yang akan diaktifkan
![2](https://user-images.githubusercontent.com/56526583/122104287-ba604700-ce41-11eb-9eb8-91735d674f1d.png)
## Instalasi CodeIgniter 4
- Codeigniter dapat didownload dari website https://codeigniter.com/download
- Extrak file zip Codeigniter ke direktori htdocs/lab11_php_ci
- Ubah nama direktory framework-4.x.xx menjadi ci4.
- Buka browser dengan alamat http://localhost/lab11_php_ci/ci4/public/
# Praktikum 12 - Pemrograman Web (Framework Lanjutan - CRUD)
~~~
Subkhan Fadilah
311910410
TI.19.A.2
~~~
# laporan praktikum
# Persiapan
Pastikan MySQL server sudah berjalan dan buat sebuah database
# Langkah 1 - Konfigurasi Database
Membuat konfigurasi hubungan ke database server dengan menggunakan file ```.env```
# Langkah 2 - Membuat Model
Buat file baru pada direktori /app/Models dengan nama ArtikelModel.php
# Langkah 3 - Membuat Controller
Buat Controller baru dengan nama Artikel.php pada direktori /app/Controllers
# Langkah 4 - Membuat View
Buat direktori baru dengan nama artikel pada direktori /app/Views, kemudian buat file baru dengan nama index.php
# Langkah 5 - Membuat Tampilan Detail Artikel
Tampilan pada saat judul berita di klik maka akan diarahkan ke halaman yang berbeda. Tambahkan sebuah fungsi baru pada Controller Artikel (/app/Controllers/Artikel.php) dengan nama view()
# Pertanyaan dan Tugas
Selesaikan programnya sesuai Langkah-langkah yang ada. Anda boleh melakukan improvisasi
# Jawab
Saya telah menyelesaikan program diatas agar dapat berjalan dengan semestinya. Seperti membuat file admin_header.php dan admin_footer.php serta CSSnya
# Praktikum 13 - Pemrograman Web (Framework Lanjutan - Modul Login)
~~~
subkhan fadilah
311910410
TI.19.A.2
~~~
# laporan praktikum
# persiapan
Pastikan MySQL server sudah berjalan dan buat sebuah tabel 
# Langkah 1 - Membuat Model User
Buat file baru pada direktori app/Models dengan nama UserModel.php untuk memproses data login.
# Langkah 2 - Membuat Controller User
Buat Controller baru dengan nama User.php pada direktori app/Controllers. Kemudian tambahkan method index()untuk menampilkan daftar user, dan method login() untuk proses login.
# Langkah 3 - Membuat View Login
Buat direktori baru dengan nama user pada direktori app/views, kemudian buat file baru dengan nama login.php.
# Langkah 4 - Membuat Database Seeder
Untuk keperluan ujicoba modul login, kita perlu memasukkan data user dan password ke dalam database. Untuk itu buat database seeder untuk tabel user. Buka CLI, kemudian tulis perintah berikut: ```php spark make:seeder UserSeeder```
