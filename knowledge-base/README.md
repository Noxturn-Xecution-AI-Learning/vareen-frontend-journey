#  Knowledge Base — Frontend

---

##  HTML Dasar

###  Pengertian

HTML (HyperText Markup Language) adalah bahasa yang digunakan untuk menyusun struktur halaman web.

---

###  Struktur Dasar HTML

```html
<!DOCTYPE html>
<html>
<head>
    <title>Judul</title>
</head>
<body>
    <h1>Hello World</h1>
</body>
</html>
```

---

###  Penjelasan

* `<!DOCTYPE html>` → memberi tahu browser bahwa ini HTML5
* `<html>` → root dari seluruh dokumen
* `<head>` → berisi metadata (tidak tampil di halaman)
* `<body>` → isi yang ditampilkan ke user

---

###  Contoh Penggunaan

```html
<h1>Judul</h1>
<p>Paragraf</p>
<a href="#">Link</a>
```

---

###  Kesalahan Umum

* Menggunakan `<div>` untuk semua hal
* Tidak menggunakan struktur `<head>` dengan benar
* Meletakkan konten di luar `<body>`

---

###  Insight Teknis

HTML hanya bertugas sebagai **struktur**, bukan tampilan.
Styling seharusnya dilakukan menggunakan CSS.

---
