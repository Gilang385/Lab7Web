# Lab7Web
## Persiapan Lingkungan Praktikum:
- Install XAMPP sebagai server lokal untuk menjalankan PHP dan Apache. Unduh dari situs XAMPP dan ekstrak di lokasi yang Anda pilih (misalnya, d:\xampp).
- Jalankan XAMPP melalui XAMPP Control Panel, pastikan Apache dan MySQL aktif.
- Uji server dengan membuka `http://localhost` di browser. Jika halaman XAMPP tampil, server telah berfungsi dengan baik.

## Buat Direktori Project:
- Buat folder baru bernama `lab7_php_dasar` di dalam folder `htdocs` (misalnya, `d:\xampp\htdocs\lab7_php_dasar`).
- Akses folder tersebut di browser dengan URL: `http://localhost/lab7_php_dasar/`.

## Kode PHP Dasar:
- Buat file `php_dasar`.php di dalam folder `lab7_php_dasar`.
Salin kode berikut untuk menampilkan teks "Hello World":
php
``` php
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>PHP Dasar</title>
</head>
<body>
    <h1>Belajar PHP Dasar</h1>
    <?php
        echo "Hello World";
    ?>
</body>
</html>
``` 
- Akses hasilnya di http://localhost/lab7_php_dasar/php_dasar.php.
