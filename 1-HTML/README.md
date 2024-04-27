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
    Setiap tag HTML memiliki satu atau lebih atribut, atribut ini untuk menyimpan informasi tersebut.

    Source code untuk menampilkan gambar:

    ```html
    <img src="link" alt="jika ingin menggunakan internet" />
    <img src="namaFolder/namafile.jpg|png|webp" alt="Local" />
    ```

    Output:
    <iframe src="./projects/images.html" frameborder="0"></iframe>

7.  Semantic HTML
    Semantic HTML adalah mengelompokkan suatu element HTML dengan lebih jelas dan memiliki arti. Beberapa element berperilaku seperti konten kepala, pokok, samping, dan kaki.

    `<header>`: Pembuka konten dalam sebuah element, biasanya `<header>` bisa digunakan menampilkan navigasi utama.

    Source code untuk membuat navigasi utama:

    ```html
    <header>
      <h1>Github</h1>
      <ul>
        <li>
          <a>Home</a>
        </li>
        <li>
          <a>About</a>
        </li>
        <li>
          <a>Contacts</a>
        </li>
      </ul>
    </header>
    ```

    `<footer>`: Catatan kaki pada sebuah element, biasanya `<footer>` dijadikan sebuah informasi hak cipta.

    Source code untuk menampilkan informasi hak cipta:

    ```html
    <footer>
      <h5>&copy; Copyright 2024 by Github</h5>
    </footer>
    ```

    `<section>`: Sebuah elemen yang memiliki kesamaan konten dan sebuah heading di dalamnya dapat dikelompokkan dengan menggunakan elemen tersebut.

    Selain itu, bisa digunakan pada element `<header>` dan `<footer>` untuk element `<section>`. `<header>` digunakan untuk menampung judul dan penulis dan `<footer>` digunakan untuk menampung link untuk membagikan artikel di sosial media. Tetapi juga tidak boleh ditulis bertumpuk atau nested.

    Source code untuk membuat artikel:

    ```html
    <section>
      <header>
        <h1>Judul Artikel</h1>
        <h2>Oleh: Media Internet</h2>
      </header>
      <p>
        <!-- Sebuah paragraf -->
      </p>
      <footer>
        <p>Bagikan artikel ini melalui</p>
        <ul>
          <li>
            <a>Twitter</a>
          </li>
          <li>
            <a>Facebook</a>
          </li>
          <li>
            <a>Instagram</a>
          </li>
        </ul>
      </footer>
    </section>
    ```

    `<nav>`: Sebuah elemen untuk menampung sebuah navigasi yang sifatnya penting, contohnya navigasi utama pada sebuah website

    Source code untuk menampilkan navigasi utama:

    ```html
    <nav>
      <ul>
        <li><a href="#sejarah">Sejarah</a></li>
        <li><a href="#geografis">Geografis</a></li>
        <li><a href="#wisata">Wisata</a></li>
      </ul>
    </nav>
    ```

    `<main>`: Sebuah element untuk menampung/mewadahi konten utama yang dominan dalam `<body>`. Konten `<main>` terdapat dari section, atau konten apa pun di dalam elemen `<main>`, selama ia termasuk konten utama yang dimiliki oleh website.

    Source code untuk struktur:

    ```html
    <body>
      <header>
        <!-- Konten pembuka -->
      </header>
      <main>
        <!-- Konten utama -->
      </main>
      <footer>
        <!-- Konten catatan kaki -->
      </footer>
    </body>
    ```

8.  Iframe
    Iframe adalah

    Source code untuk menampilkan profil Github dengan Iframe:

    ```html
    <iframe></iframe>
    ```

9.  Forms and Input Control Elements

    `<select>`: Element tersebut digunakan untuk membuat dropdown list dan juga digunakan pada sebuah form untuk mengumpulkan input dari pengguna.

    Source code untuk membuat dropdown list dengan 4 pilihan:

    ```html
    <p>Negara:</p>
    <select name="world">
      <option value="indonesia">Indonesia</option>
      <option value="malaysia">Malaysia</option>
      <option value="england">Inggris</option>
      <option value="italy">Italia</option>
    </select>
    ```

    `<textarea>`: Element digunakan untuk mewakili kontrol pengeditan teks multi-baris. Biasanya digunakan untuk membuat berita atau deskripsi.

    Source code untuk membuat input deskripsi:

    ```html
    <p>Jelaskan tentang pribadi Anda:</p>
    <textarea name="about"></textarea>
    ```

    `<input>`: Element yang penting dari form HTML. Atribut `type` dari elemen input dapat berupa yang mendefinsikan informasi masing-masing.

    Semua tipe `<input>` pada HTML:

    <table>
      <thead>
        <tr>
          <th>Type</th>
          <th></th>
        </tr>
      </thead>
      <tbody>
        <tr>
          <td>text</td>
          <td>Teks satu baris</td>
        </tr>
        <tr>
          <td>number</td>
          <td>Memasukan angka</td>
        </tr>
        <tr>
          <td>tel</td>
          <td>Memasukan nomor telepon</td>
        </tr>
        <tr>
          <td>email</td>
          <td>Memasukan alamat email</td>
        </tr>
        <tr>
          <td>password</td>
          <td>Password satu baris</td>
        </tr>
        <tr>
          <td>radio</td>
          <td>Memilih satu opsi</td>
        </tr>
        <tr>
          <td>checkbox</td>
          <td>Memilih beberapa opsi yang lebih dari satu</td>
        </tr>
        <tr>
          <td>file</td>
          <td>Memilih file dari penyimpanan perangkat</td>
        </tr>
      </tbody>
    </table>

    Source code untuk membuat halaman login:

    ```html
    <form>
      <input type="text" placeholder="Username" />
      <input type="password" placeholder="Password" />
      <input type="submit" value="Lanjut" />
    </form>
    ```

10. Classes and IDs
    HTML Classes dan IDs merupakan panggilan untuk melakukan pengelompokan. Untuk melakukan sebuah element harus diletakkan diberikan sebuah property yaitu `class=""` digunakan untuk CSS atau `id=""` digunakan untuk JavaScript dan hanya satu dalam suatu halaman, tidak boleh sama dengan element lain.

    Source code untuk penggunaan tag `<div>` dan property `class`:

    ```html
    <div class="box" id="active">
      <h1>Hello, World</h1>
    </div>
    ```

11. Label
    Label digunakan untuk mendefinsikan label untuk beberapa element lainnya, seperti `<input>`, `<textarea>` dan `select`. Label dapat ditekan untuk fokus pada element yang ditunjuk. Penggunaan element untuk meningkatkan aksesibilltas situs web. Jika element label digunakan dengan benar, maka pengguna akan mendapatkan informasi yang lebih baik tentang element yang ditunjuk.

    Source code untuk penggunaan label pada `<input>`:

    ```html
    <label for="email">Email:</label>
    <input id="email" />
    <label for="password">Password:</label>
    <input id="password" />
    <!-- Penggunaan attribute `for` = `id` yang akan menghubungkan element -->
    ```

Final Projects: Struktur
