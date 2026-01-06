# lab9web

Ahmad Ibnu Abdillah <br>
TI.24.A.5 <br>

# Kode
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Header</title>
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
</body>
</html>
```
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Footer</title>
</head>
<body>
    <div>
        <footer>
<p>&copy; 2021, Informatika, Universitas Pelita Bangsa</p>
</footer>
    </div>
</body>
</html>
```
```
<?php
include("koneksi.php");
$sql = 'SELECT * FROM data';
$result = mysqli_query($conn, $sql);
?>
<!DOCTYPE html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Home</title>
</head>
<body>
    <?php require('header.php'); ?>
<div class="content">
<h2>Ini Halaman Home</h2>
<p>Ini adalah bagian content dari halaman.</p>
</div>
<?php require('footer.php'); ?>
</body>
</html>
```
![img](https://github.com/AhmadIbnuAbdillah/img9/blob/e4cf11decd2b277d865c6f16402371094ae39476/Screenshot%202026-01-06%20193015.png)
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About</title>
</head>
<body>
    <?php require('header.php'); ?>
<div class="content">
<h2>Ini Halaman About</h2>
<p>Ini adalah bagian content dari halaman.</p>
</div>
<?php require('footer.php'); ?>
</body>
</html>
```
![img](https://github.com/AhmadIbnuAbdillah/img9/blob/e4cf11decd2b277d865c6f16402371094ae39476/Screenshot%202026-01-06%20193025.png)
