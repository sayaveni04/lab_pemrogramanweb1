# Lab1web

## Membuat Paragraf
```
<!-- Ini adalah paragraf pertama -->
  <p>Kami sedang belajar HTML dasar, pada matakuliah Pemrograman
  Web di Prodi Teknik Informatika Universitas Pelita Bangsa. Pelajaran pertama
  yang kami dapat adalah membuat tampilan web sederhana dalam rangka mengenal
  tag-tag dasar HTML.</p>
<!-- Ini adalah paragraf kedua -->
  <p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
  mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan
  tag dasar html.</p>

```

![Screenshot (185)](https://github.com/sayaveni04/lab_pemrogramanweb1/assets/115862597/cc592603-6a1e-41be-ac92-2ba0b8dc8fd0)


## Menambahkan Judul
```
<!-- judul paragraf pertama -->
<h1>Belajar Dasar HTML</h1>

    <!-- Ini adalah paragraf pertama -->
    <p>Kami sedang belajar <mark>HTML dasar</mark>, pada matakuliah <b>Pemrograman Web</b> di Prodi
    <i>Teknik Informatika</i> <u>Universitas Pelita Bangsa</u>. Pelajaran pertama yang kami dapat
    adalah membuat tampilan web sederhana dalam rangka mengenal tag-tag dasar
    HTML.</p>

<!-- judul paragraf kedua -->
<h2>Paragraf pada HTML</h2>

    <!-- Ini adalah paragraf kedua -->
    <p>Ini merupakan sebuah paragraf yang terdiri dari beberapa kalimat yang saling
    mendukung sehingga menjadi satu kesatuan. Paragraf dibuat dengan menggunakan
    tag dasar html.</p>
```

![Screenshot (186)](https://github.com/sayaveni04/lab_pemrogramanweb1/assets/115862597/b1c5c84d-3e9f-41db-ae93-d65ab63b07c9)


## Menyisipkan Gambar
```
<!-- sub judul paragraf -->
<h3>Menambahkan Gambar</h3>

<!-- menambahkan gambar pada dokumen -->
<img src="LOGO_UPB_NEW-1.png" width="300" title="Logo Univeritas Pelita Bangsa">
```

![Screenshot (187)](https://github.com/sayaveni04/lab_pemrogramanweb1/assets/115862597/d266c85d-7691-4f54-a8cb-19d89b3cfdd6)

## Menambahkan Hyperlink
```
<!-- menambahkan link navigasi -->
<nav>
    <a href="lab1_tag_dasar.html">Dasar HTML</a>
    <a href="lab1_halaman2.html">Halaman 2</a>
    <a href="http://www.google.com">Halaman Web Eksternal Google</a>
    </nav>
    <hr>
```

![Screenshot (190)](https://github.com/sayaveni04/lab_pemrogramanweb1/assets/115862597/885488fc-2608-42ed-9e53-1230776c20eb)


## Halaman 2

![Screenshot (189)](https://github.com/sayaveni04/lab_pemrogramanweb1/assets/115862597/8d16711c-9a54-4543-ae61-999f48e91a6d)


# Latihan Soal
```
1. Lakukan perubahan pada kode sesuai dengan keinginan anda, amati perubahannya adakah
   error ketika terjadi kesalahan penulisan tag?
2. Apa perbedaan dari tag <p> dengan tag <br>, berikan penjelasannya!
3. Apa perbedaan atribut title dan alt pada tag <img>, berikan penjelasannya!
4. Untuk mengatur ukuran gambar, digunakan atribut width dan height. Agar tampilan gambar
   proporsional sebaiknya kedua atribut tersebut diisi semua atau tidak? Berikan penjelasannya!
5. Pada link tambahkan atribut target dengan nilai atribut bervariasi ( _blank, _self, _top,
   _parent ), apa yang terjadi pada masing-masing nilai antribut tersebut?
```
# Jawaban
2. Tag ```<p>``` pada html diperuntukan untuk membuat paragraf sedangkan tag ```<br>``` pada html diperuntkan untuk membuat line break pada halaman html.
3. Atribute ```<alt>``` pada tag ```<img>``` berfungsi sebagai pemberi deskripsi singkat sedang atribute ```<title>``` memberikan informasi tambahan kepada user tentang       gambar.
4. Tidak, mengisi salah satunya saja sudah cukup

   jika anda ingin mengisi keduanya maka itu akan mengatur gambar secaara presisi dan gambar yang ditampilkan akan persis dan tidak mengubah proporsinya

   jika anda mengisi salah satunya maka akan mempertahankan proporsi gambar aslinya dan hanya mengubah ukuran gambar sesuai atribut yang diisi.
5. _blank
   Efek: Tautan akan membuka halaman yang terkait dalam jendela atau tab browser baru.
   
   _self
   Efek: Tautan akan membuka halaman yang terkait di jendela atau tab yang sama di mana tautan tersebut berada.
   
   _top
   Efek: Tautan akan membuka halaman yang terkait di jendela atau tab baru, menggantikan seluruh halaman web saat ini jika ada beberapa frame atau iframe.
