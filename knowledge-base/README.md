# Knowledge Base — Frontend (HTML Dasar)

Dokumen ini berisi hasil pembelajaran berdasarkan Pomodoro yang telah dikerjakan. Fokus saat ini adalah HTML dasar.

---

## Pomodoro 1 — Setup dan Struktur Dasar HTML

### Tujuan

Memahami bagaimana file HTML dibuat dan dijalankan di browser.

### Hasil Pembelajaran

* File HTML dibuat dengan ekstensi `.html`
* Browser dapat langsung membaca file HTML tanpa compile
* Struktur dasar HTML terdiri dari:

  * `<!DOCTYPE html>`
  * `<html>`
  * `<head>`
  * `<body>`

### Penjelasan

`<!DOCTYPE html>` digunakan untuk memberi tahu browser bahwa dokumen menggunakan HTML5.

Tag `<html>` adalah root utama.

Bagian `<head>` berisi metadata seperti title, sedangkan `<body>` berisi konten yang ditampilkan.

### Contoh Kode

```html
<!DOCTYPE html>
<html>
<head>
    <title>TESSSSSSSSSS</title>
</head>
<body>
    
</body>
</html>
```

### Catatan

/////

---

## Pomodoro 2 — Head dan Text Element

### Tujuan

Memahami penggunaan elemen teks dasar dan title halaman.

### Hasil Pembelajaran

* Tag `<title>` muncul di tab browser
* Tag `<h1>` digunakan untuk judul utama
* Tag `<p>` digunakan untuk paragraf

### Penjelasan

Elemen heading (`h1`–`h6`) digunakan untuk struktur hierarki konten.

Paragraf digunakan untuk teks biasa.

### Contoh Kode

```html
<!DOCTYPE html>
<html>
<head>
    <title>Page 1</title>
</head>
<body>
    <h1>Hello Wordllll</h1>
    <h2>Kicau Mania</h2>
    <p>Kicau, kicau, kicau mania (hm)
Kicau, kicau, kicau mania (hm)
Kicau, kicau, kicau mania (hm)
Kicau, kicau, kicau mania (hm)</p>
</body>
</html>
```

### Catatan

penggunaan heading dan paragraf.

---

## Pomodoro 3 — Link dan Image

### Tujuan

Menambahkan navigasi dan media ke dalam halaman.

### Hasil Pembelajaran

* Tag `<a>` digunakan untuk membuat link
* Tag `<img>` digunakan untuk menampilkan gambar
* Atribut `href` dan `src` wajib digunakan

### Penjelasan

Link memungkinkan berpindah halaman atau membuka URL lain.

Gambar membutuhkan path yang benar agar bisa tampil.

Atribut `alt` penting untuk deskripsi gambar.

### Contoh Kode

```html
<!DOCTYPE html>
<html>
<head>
    <title>Link dan Gambar</title>
</head>
<body>
    <h1>Contoh Link dan Gambar</h1>

    <p>Klik link:</p>
    <a href="https://youtu.be/RQTIEKUkQU8?si=ykHtwA1wwWYlKLj-">YouTube</a>

    <p>Gambar:</p>
    <img src="https://cdn2.cdnstep.com/f0Mibc4O6VLFW4lC0wO6/cover.thumb256.webp" alt="Kicau">
</body>
</html>
```

### Catatan

perbedaan path relatif dan absolut.

---

## Pomodoro 4 — Semantic HTML Dasar

### Tujuan

Menggunakan struktur HTML yang lebih bermakna.

### Hasil Pembelajaran

* Menggunakan `<header>` untuk bagian atas
* Menggunakan `<main>` untuk konten utama
* Menggunakan `<footer>` untuk bagian bawah

### Penjelasan

Semantic HTML membantu:

* struktur lebih jelas
* memudahkan pembacaan kode
* meningkatkan aksesibilitas

### Contoh Kode

```html
<!DOCTYPE html>
<html>
<head>
    <title>Kicau Mania</title>
</head>
<body>

    <header>
        <h1>Adalahh</h1>
    </header>

    <main>
        <h2>ADALAHHH</h2>
        <p>ISI KICAU</p>
    </main>

    <footer>
        <p>Copyright 2045</p>
    </footer>

</body>
</html>
```

### Catatan

bagi konten ke dalam struktur semantic yang pas.

---
