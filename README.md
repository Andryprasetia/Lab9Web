# Pemograman Web
~~~
Nama  : Andry Prasetia P
NIM   : 311910284
Kelas : TI19C1
~~~
# Langkah Pertama
Buat Buat folder baru dengan nama lab9_php_modular pada docroot webserver (htdocs)

# Langkah kedua 
Buat file baru dengan nama header.php
~~~
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Contoh Modularisasi</title>
<link href="style.css" rel="stylesheet" type="text/stylesheet"
media="screen" />
</head>
<body>
<div class="container">
<header>
<h1>Modularisasi Menggunakan Require</h1>
</header>
<nav>
<a href="home.php">Home</a>
<a href="about.php">Tentang</a>
<a href="kontak.php">Kontak</a>
</nav>
~~~
![Screenshot (163)](https://user-images.githubusercontent.com/81818989/121795370-3720d480-cc3a-11eb-8e37-edc7aedd314a.png)

# Langkah Ketiga
Buat file baru dengan nama footer.php
~~~
<footer>
<p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
</footer>
</div>
</body>
</html>
~~~
![Screenshot (164)](https://user-images.githubusercontent.com/81818989/121795380-4dc72b80-cc3a-11eb-9a97-792ac1f15090.png)

# Langkah keempat
Buat file baru dengan nama home.php
~~~
<?php require('header.php'); ?>
<div class="content">
<h2>Ini Halaman Home</h2>
<p>Ini adalah bagian content dari halaman.</p>
</div>
<?php require('footer.php'); ?>
~~~
![Screenshot (165)](https://user-images.githubusercontent.com/81818989/121795394-7bac7000-cc3a-11eb-9972-bd0fdb50c867.png)


# Langkah kelima
Buat file baru dengan nama about.php
~~~
<?php require('header.php'); ?>
<div class="content">
<h2>Ini Halaman About</h2>
<p>Ini adalah bagian content dari halaman.</p>
</div>
<?php require('footer.php'); ?>
~~~
![Screenshot (166)](https://user-images.githubusercontent.com/81818989/121795402-8cf57c80-cc3a-11eb-9555-4c3cb7885545.png)
