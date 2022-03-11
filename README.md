# Lab1web

Memahami dasar - dasar HTMl 

## langkah - langkah 

1. membuka text editor 
2. membuat file html `Lab1_tag_dasar.html`
3. membuat sturktur html
      <!DOCTYPE html>
      <html lang="en">
      <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Document</title>
      </head>
      <body>
    
      </body>
      </html>
4. merubah title `Tag HTML Dasar`
5. membuat paragraf menggunakan tag `<p></p>`
6. mengatur atribut paragraf menggunakan atribut `align`

    atribut align="right" -> mengatur paragraf di posisi kana
    atribut align="center" -> mengatur paragraf di posisi tengah
    atribut align="left" -> mengatur paragraf di posisi kiri

7. membuat judul menggunakan tag `h1 dan h2`

    Heading merupakan sebuah judul yang biasanya digunakan pada sebuah halaman artikel pada web.
    Atau terkadang dibeberapa bagian dari halaman web.
    Judul atau heading pada dokumen HTML dapat dibuat dengan menggunakan tag <h1> sampai <h6>.
    Tag <h1> merupakan judul pada lever pertama, kemudian level berikutnya atau sub judul pada tag
    <h2> dan seterusnya sampai tag <h6>.

    <h1>Heading 1</h1>
    <h2>Heading 2</h2>
    <h3>Heading 3</h3>
    <h4>Heading 4</h4>
    <h5>Heading 5</h5>
    <h6>Heading 6</h6>

8. membuat navigasi menggunakan tag `nav` dan untuk hiperlink mengunakan tag `a`

    <nav>
      <a href="lab1_tag_dasar.html">Dasar HTML</a>
      <a href="lab1_halaman2.html">Halaman 2</a>
      <a href="https://www.google.co.id/">Halaman Web Eksternal Google</a>
    </nav>

tag `hr` berfungsi untuk membuat garis 

### contoh pormat texs

    <p>Teks <b>ini dicetak tebal</b></p>
    <p>Teks <i>ini dicetak miring</i></p>
    <p>Dan ini adalah <sub>subscript</sub> dan <sup>superscript</sup></p>


### menambahkan gambar pada dokumen

menambahkan gambar di HTML kita menggunakan tag `img` 

    <img src="..." alt="..." title="...">

contoh 

    <img src="img/Universitas-Pelita-Bangsa.png" alt="UPB" title="Logo Universitas Pelita Bangsa">