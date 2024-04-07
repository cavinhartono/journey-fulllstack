### HyperText Markup Language (HTML)

HTML adalah format yang digunakan dalam pembuatan dokumen pada web browser. Markup Language yang dimaksud adalah mengandung tag tertentu untuk menentukan tampilan teks dan tingkat kepentingan dalam suatu dokumen. Tag adalah markup teks ASCII menjadi file HTML, setiap tag ditandai dengan (`<tag></tag>`) atau tanda kurung runcing. Tag tersebut memberikan fungsi bahwa yang ditulis di antara kedua tag dari dokumen HTML.

Element HTML terdiri dari dua bagian:

A. `<Head>`: Kepala dokumen dari HTML yang berfungsi sebagai memberikan informasi pada dokumen HTML

B. `<Body>`: Tubuh dari HTML yang berfungsi sebagai menentukan isi yang ditampilkan pada web browser.

#### Struktur dasar dari HTML adalah:

```html
<!-- Bertujuan sebagai tanda awal pada dokumen HTML -->
<html>
  <head>
    <!-- Informasi judul, link, script, meta, style dan lain-lain -->
    <title>Judul halaman yang akan muncul pada caption browser</title>
  </head>
  <body>
    <!-- Isi dari dokumen, terdiri dari gambar, warna teks, tabel, background dan lain-lain -->
  </body>
</html>
<!-- Bertujuan sebagai tanda akhir pada dokumen HTML -->
```

#### Tag-tag dasar

1.  Heading dan Paragraph <br>
    Heading digunakan untuk judul atau subjudul dari suatu dokumen HTML dan Paragraph untuk membuat paragraf atau suatu kalimat.

    Contoh untuk membuat Heading:

    ```HTML
    <body>
      <h1>Hello, World</h1>
      <h2>Hello, World</h2>
      <h3>Hello, World</h3>
      <h4>Hello, World</h4>
      <h5>Hello, World</h5>
      <h6>Hello, World</h6>
    </body>
    ```

    Output pada Heading:

    <h1>Hello, World</h1>
    <h2>Hello, World</h2>
    <h3>Hello, World</h3>
    <h4>Hello, World</h4>
    <h5>Hello, World</h5>
    <h6>Hello, World</h6>

    ```html
    <body>
      <p>
        Demikian pula, tidak adakah orang yang mencintai atau mengejar atau
        ingin mengalami penderitaan, bukan semata-mata karena penderitaan itu
        sendiri, tetapi karena sesekali terjadi keadaan di mana susah-payah dan
        penderitaan dapat memberikan kepadanya kesenangan yang besar.
      </p>
    </body>
    ```

    Output:

    <p>
    Demikian pula, tidak adakah orang yang mencintai atau mengejar atau ingin mengalami penderitaan, bukan semata-mata karena penderitaan itu sendiri, tetapi karena sesekali terjadi keadaan di mana susah-payah dan penderitaan dapat memberikan kepadanya kesenangan yang besar.
    </p>

    Format Karakter:

    A. Logical format

    `<cite>`: Menandai suatu kutipan

    `<code>`: Menampilkan source code

    `<em>`: Menandai suatu teks yang ditekankan oleh penulis

    `<samp>`: Menandai suatu teks yang dimaksudkan sebagai contoh

    `<strong>`: Menandai bagian yang terpenting dari suatu teks

    `<dfn>`: Menandai sebuah subdefinisi dari daftar definisi

    B. Physical format

    `<b>` : Menampilkan huruf tebal

    `<i>` : Menampilkan huruf miring

    `<u>` : Menampilkan garis bawah pada teks

    `<tt>` : Menampilkan huruf mesin ketik

    `<strike>` : Menampilkan garis horisontal pada bagian tengah huruf

    `<big>` : Menampilkan ukuran huruf yang lebih besar

    `<small>` : Menampilkan ukuran huruf yang lebih kecil

    `<sub>` : Menampilkan subscript

    `<sup>` : Menampilkan superscript

2.  Grouping Element
    `<div>` dan `<span>` digunakan untuk mengelompokkan elemen-elemen HTML. `<span>` bersifat inline, sedangkan `<div>` bersifat block pada konten HTML.

3.  List
    List Item digunakan untuk membuat daftar atau mengelompokkan kata, ada 2 macam list yaitu Ordered dan Unordered List.

    A. Ordered List (Numbering)

    ```html
    <!-- type="a|A|1|i|I" -->
    <ol type="a">
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
    </ol>
    ```

    Output:
    <ol type="A">
      <li>Apa itu HTML?</li>
      <li>Bagaimana Sejarah HTML?</li>
      <li>Dasar Tag pada HTML</li>
    </ol>

    B. Unordered List (Bullet)

    ```html
    <h1>Dasar Tag pada HTML</h1>
    <ul>
      <li>Heading and Paragraph</li>
      <li>Grouping Element</li>
      <li>List Item</li>
    </ul>
    ```

    Output:

    <h1>Dasar Tag pada HTML</h1>
    <!-- type="disc|square|circle" dan defaultnya adalah disc -->
    <ul type="square">
      <li>Heading and Paragraph</li>
      <li>Grouping Element</li>
      <li>List Item</li>
    </ul>

4.  Hyperlink
    `<a>` digunakan untuk membuat link website yang berbeda atau dokumen html

    ```html
    <!-- Link website -->
    <a href="https://www.facebook.com">Facebook</a>
    <!-- Link antar dokumen HTML -->
    <a href="Login.html">Login</a>
    ```

5.  Table
    `<table>` digunakan untuk menampilkan informasi dengan berbentuk yang mudah dibaca.
    Tag table bagian penting, yaitu:

    `<caption>` : Membentuk judul tabel

    `<th>` : Meletakkan judul tabel di bagian paling atas dan kiri dari suatu tabel. Tabel header akan dicetak dalam huruf tebal.

    `<tr>` : Membentuk baris pada suatu tabel

    `<td>` : Sebagai tempat menulis data atau informasi dalam tabel

    Source Code untuk membuat table

    ```html
    <table>
      <caption>
        Judul Tabel
      </caption>
      <thead>
        <tr>
          <th>Baris</th>
          <th>Kolom</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Baris 1 dan Kolom 1</td>
          <td>Baris 1 dan Kolom 2</td>
        </tr>
        <tr>
          <td>Baris 2 dan Kolom 1</td>
          <td>Baris 2 dan Kolom 2</td>
        </tr>
      </tbody>
    </table>
    ```

    > Output:

    <table>
      <caption>
        Judul Tabel
      </caption>
      <thead>
        <tr>
          <th>Baris</th>
          <th>Kolom</th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>Baris 1 dan Kolom 1</td>
          <td>Baris 1 dan Kolom 2</td>
        </tr>
        <tr>
          <td>Baris 2 dan Kolom 1</td>
          <td>Baris 2 dan Kolom 2</td>
        </tr>
      </tbody>
    </table>

6.  Audio, Image and Video

    Source code untuk menampilkan gambar:

    ```html
    <img src="link" alt="jika ingin menggunakan internet" />
    <img src="namaFolder/namafile.jpg|png|webp" alt="local" />
    ```

    Output:
