Debugging HTML

Daftar Kesalahan

1. Menggunakan Markdown sebagai Heading
   Kode salah:
   text
   Selamat Datang di Toko Kami

Masalah:
Menggunakan sintaks Markdown, bukan tag HTML.

Perbaikan:
html

<h1>Selamat Datang di Toko Kami</h1>

2.  Heading Produk Unggulan
    Kode salah:
    text
    Produk Unggulan

Masalah:
Menggunakan Markdown dan langsung memakai heading level 4.

Perbaikan:
html

<h2>Produk Unggulan</h2>

3. Kalimat Terpotong
   Kode salah:
   text
   Kami menjual berbagai produk berkua

Masalah:
Kalimat tidak lengkap.

Perbaikan:
html

<p>Kami menjual berbagai produk berkualitas.</p>

4.  Bold Menggunakan Markdown
    Kode salah:
    text
    Diskon spesial bulan ini!

Masalah:
Menggunakan sintaks Markdown.

Perbaikan:
html
<strong>Diskon spesial bulan ini!</strong>

5.  Heading Tentang Kami
    Kode salah:
    text
    Tentang Kami

Masalah:
Masih menggunakan Markdown.

Perbaikan:
html

<h2>Tentang Kami</h2>

6.  Penulisan Tahun
    Kode salah:
    text
    2015

Masalah:
Menggunakan sintaks Markdown.

Perbaikan:
html
<em>2015</em>

7.  Link Email Kosong
    Kode salah:
    html
    <a href="mailto:">kontak kami</a>

Masalah:
Alamat email tidak diisi.

Perbaikan:
html
<a href="mailto:kontak@tokokami.com">kontak@tokokami.com</a>

8.  Struktur HTML Tidak Lengkap
    Masalah:
    Tidak terdapat <!DOCTYPE html>, <html>, <head>, dan <body>.

Perbaikan:
Menambahkan struktur HTML lengkap.

Kode HTML Hasil Perbaikan

html

<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Toko Kami</title>
</head>
<body>

<h1>Selamat Datang di Toko Kami</h1>

<h2>Produk Unggulan</h2>
<p>Kami menjual berbagai produk berkualitas.</p>

<p><strong>Diskon spesial bulan ini!</strong></p>

<h2>Tentang Kami</h2>
<p>Kami sudah berdiri sejak <em>2015</em> dan melayani ribuan pelanggan.</p>

<p>
<a href="https://www.instagram.com/tokokami">Instagram Kami</a>
</p>

<p>
Hubungi kami di
<a href="tel:+62812345678">+62 812-3456-78</a>
atau email
<a href="mailto:kontak@tokokami.com">kontak@tokokami.com</a>.
</p>

</body>
</html>
