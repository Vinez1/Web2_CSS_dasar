## CSS Dasar

<br>

**Nama     : Fery Affandi** <br>
**Kelas    : TI.20.A.1**  <br>
**NIM      : 312010018** <br>

<br>

## Tugas

Mendapatkan tugas dari dosen Pemrograman Web pada pertemuan ke-2 ,yaitu:

![foto tugas](foto/foto1.png)
<p align="center"> Gambar 2.1 Tugas.

# Langkah-langkah praktikum

**1. Membuat dokumen HTML**

Buatlah dokumen HTML seperti dibawah ini.

        <!DOCTYPE html>
        <html lang="en">
        <head>
            <meta charset="UTF-8">
            <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>CSS Dasar</title>
    </head>
    <body>
        <header>
            <h1>CSS Internal dan <i>Inline CSS</i></h1>
        </header>
        <nav>
            <a href="lab2_css_dasar.html">CSS Dasar</a>
            <a href="lab2_css_eksternal.html">CSS Eksternal</a>
            <a href="lab1_tag_dasar.html">HTML Dasar</a>
        </nav>
        <!-- CSS ID Selector -->
        <div id="intro">
            <h1>Hello World</h1>
            <p>Kami sedang belajar HTML dan CSS dasar, pada mata kuliah
            <b>Pemrograman Web</b> di 
            <i>Universitas Pelita Bangsa</i>. 
            Pelajaran pertama yang kami dapat
            adalah membuat tampilan web sederhana dalam 
            rangka mengenal tag-tag dasar HTML
            dan CSS.</p>
            <!-- CSS Class Selector -->
            <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
        </div>
    </body>"
    </html>
 dan hasil di text editornya akan seperti ini.

 ![nomor1](foto/nomor1.png)
 <p align="center"> Gambar 2.2 Tampilan text editor.

<br>
Selanjutnya buka file HTML pada browser.

![tampilan web](foto/tampilan_web.png)
<p align="center"> Gambar 2.3 Tampilan Web HTML.

<br>

**2. Mendeklarasikan CSS internal.**

Kemudian tambahkan deklarasi CSS internal seperti berikut pada bagian head dokumen.

    <head>
        <title>CSS Dasar</title>
        <style>
            body {
                font-family:'Open Sans', sans-serif;
            }
            header {
                min-height: 80px;
                border-bottom:1px solid #77CCEF;
            }
            h1 {
                font-size: 24px;
                color: #0F189F;
                text-align: center;
                padding: 20px 10px;
            }
            h1 i {
                color:#6d6a6b;
            }
        </style>
    </head>


Selanjutnya simpan perubahan yang ada, dan lakukan 
refresh pada browser untuk . Menambahkan Inline CSS melihat hasilnya.

![hasil nomor 2](foto/hasil_nomor2.png)
<p align="center">Gambar 2.4 Penambahan CSS pada HTML.

<br>

**3. Menambahkan Inline CSS**

Kemudian tambahkan deklarasi inline CSS pada tag    `<p>` seperti berikut.

    <p style="text-align: center; color: #ccd8e4;">

contoh codingannya.
![coding no 3](foto/coding_no3.png)
<p align="center"> Gambar 2.5 codingan di text editor.

Simpan kembali dan refresh kembali browser untuk melihat perubahannya.

![inline css](foto/nomor3.png)
<p align="center">Gambar 2.6 Penambahan Inline CSS.

<br>

**4. Membuat CSS Eksternal**

Membuat file baru dengan nama <b>style_eksternal.css</b> lalu buatlah deklarasi CSS berikut.

![css eksternal](foto/nav_css%20.png)
<p align="center">Gambar 2.7 penambahan CSS

<br>
kemudian menambahkan tag `<link>` untuk menuju link css 
yang sudah dibuat pada bagian tag `<head>`.

![link css](foto/css%20eksternal.png)
<p align="center">Gambar 2.8 link CSS

<br>
Selanjutnya di simpan lalu di refresh pada browser untuk melihat perubahannya.

![hasil web](foto/hasil_nomor4.png)
<p align="center">Gambar 2.9 Tampilan Eksternal CSS

<br>

**5. Penambahan CSS Selector**

Selanjutnya menambahkan CSS Selector menggunakan ID dan Class Selector.
Pada file <b>style_eksternal.css</b>, tambahkan kode berikut.

![coding no5](foto/coding_no5.png)
<p align="center">Gambar 2.10 Codingan CSS ID dan Class Selector

<br>
Kemudian simpan kembali dan refresh pada browser untuk melihat perubahannya.

![CSS ID dan Class Selector](foto/hasil_nomor5.png)
<p align="center">Gambar 2.10 Tampilan CSS ID dan Class Selector
