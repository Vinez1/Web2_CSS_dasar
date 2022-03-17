## CSS Dasar

**Nama     : Fery Affandi** <br>
**Kelas    : TI.20.A.1**  <br>
**NIM      : 312010018** <br>

## Tugas

Mendapatkan tugas dari dosen Pemrograman Web pada pertemuan ke-2 ,yaitu:

![foto tugas](foto/foto1.png)

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
            <p>Kami sedang belajar HTML dan CSS dasar, pada mata kuliah <b>PemrogramanWeb</b> di <i>Universitas Pelita Bangsa</i>. Pelajaran pertama yang kami dapat
    adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar HTML
    dan CSS.</p>
            <!-- CSS Class Selector -->
            <a class="button btn-primary" href="#intro">Informasi selengkapnya.</a>
        </div>
    </body>"
    </html>


Selanjutnya buka file HTML pada browser.

![tampilan web](foto/tampilan_web.png)
<p align="center"> Gambar 2.1 Tampilan Web HTML.
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
refresh pada browser untuk melihat hasilnya.

![hasil nomor 2](foto/hasil_nomor2.png)
<p align="center">Gambar2.1 Penambahan CSS pada HTML.
