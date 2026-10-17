# Web1Lab4: Laporan Praktikum 4 - CSS Layout

Repositori ini berisi hasil pengerjaan Praktikum 4 mata kuliah Pemrograman Web mengenai pembuatan tata letak halaman web (*CSS Layout*) menggunakan konsep *Box Model*, *Float*, *Clearfix*, struktur *Semantic HTML*, serta pembuatan tata letak responsif untuk halaman utama, menu About, dan menu Contact Us[cite: 1].

## Data Mahasiswa
- **Nama:** Nurfaiz Pradibto Nugroho
- **NIM:** 312510172
- **Program Studi / Semester:** Teknik Informatika / 3
- **Kelas:** I253C
- **Mata Kuliah:** Pemrograman Web
- **Dosen Pengampu:** Agung Nugroho, S.Kom., M.Kom.
- **Hari / Tanggal:** Sabtu, 17 Oktober 2026 (Pertemuan 5 - Online)
- **Instansi:** Universitas Pelita Bangsa

---

## Langkah-langkah Praktikum

Berikut adalah alur pengerjaan Praktikum 4 beserta rincian struktur kode dan tampilannya:

### 1. Persiapan dan Pembuatan Box Element
- Mempersiapkan text editor (Visual Studio Code).
- Membuat folder kerja baru bernama `Lab4Web`.
- Membuat file `lab4_box.html` dan menambahkan struktur dasar HTML.

![Kode HTML Dasar Box Element](/Lab4Web/images/img-1.jpg)
![Tampilan HTML Dasar Box Element](/Lab4Web/images/img-2.jpg)

### 2. Menambahkan Elemen Div
- Menambahkan elemen `div` (`div1`, `div2`, `div3`) di dalam tag `<section>` pada `lab4_box.html`.

![Kode Elemen Div](/Lab4Web/images/img-3.jpg)
![Tampilan Elemen Div](/Lab4Web/images/img-4.jpg)

### 3. Mengatur Float Element dengan CSS
- Menambahkan style CSS pada `<head>` untuk membuat float element (`float: left; padding: 10px;`) serta memberikan warna latar pada masing-masing div.

![Kode CSS Float Element](/Lab4Web/images/img-5.jpg)
![Tampilan Float Element](/Lab4Web/images/img-6.jpg)

### 4. Mengatur Clearfix Element
- Menambahkan elemen `div4` di bawah `div3`.
- Menambahkan properti `clear: left;` dan `float: none;` pada kelas `.div4` untuk mengatur posisi elemen setelah elemen *float*.

![Kode Tambahan Div 4](/Lab4Web/images/img-7.jpg)
![Kode CSS Clearfix](/Lab4Web/images/img-8.jpg)
![Tampilan Clearfix Element](/Lab4Web/images/img-9.jpg)

---

### 5. Membuat Layout Web Sederhana
- Membuat folder baru `lab4_layout`, lalu membuat file `home.html` dan file CSS `style.css`[cite: 1].
- Menyusun kerangka layout menggunakan tag *Semantic HTML* (`<header>`, `<nav>`, `<section id="hero">`, `<section id="wrapper">`, `<aside id="sidebar">`, dan `<footer>`).

![Kode Struktur HTML Layout](/Lab4Web/images/img-10.jpg)
![Kode Kerangka Semantics](/Lab4Web/images/img-11.jpg)
![Tampilan Awal Kerangka Layout](/Lab4Web/images/img-12.jpg)

### 6. Styling Dasar dan Navigasi Layout
- Menambahkan *CSS Reset*, pengaguran font Google Fonts, style kontainer, header, serta styling navigasi (`nav`, `nav a`, `nav a.active`, `nav a:hover`) pada `style.css`.

![Kode CSS Reset & Header](/Lab4Web/images/img-13.jpg)
![Tampilan Style Header](/Lab4Web/images/img-14.jpg)
![Kode CSS Navigasi](/Lab4Web/images/img-15.jpg)
![Tampilan Navigasi](/Lab4Web/images/img-16.jpg)

### 7. Membangun Hero Panel
- Menambahkan struktur HTML untuk *Hero Panel* dan mengatur tampilannya dengan CSS.

![Kode HTML Hero Panel](/Lab4Web/images/img-17.jpg)
![Kode CSS Hero Panel](/Lab4Web/images/img-18.jpg)
![Tampilan Hero Panel](/Lab4Web/images/img-19.jpg)

### 8. Membangun Area Main Content & Sidebar Widget
- Mengatur tata letak *Main Content* dan *Sidebar* berdampingan menggunakan `float: left`.
- Menambahkan elemen widget (link dan teks) di dalam area `<aside id="sidebar">`.

![Kode CSS Main & Sidebar](/Lab4Web/images/img-20.jpg)
![Kode HTML Sidebar Widget](/Lab4Web/images/img-21.jpg)
![Tampilan Main Content & Sidebar](/Lab4Web/images/img-22.jpg)

### 9. Styling Footer Layout
- Menambahkan style CSS pada `footer` menggunakan `clear: both;`.

![Kode CSS Footer](/Lab4Web/images/img-23.jpg)
![Tampilan Footer Layout](/Lab4Web/images/img-24.jpg)

### 10. Menambahkan Elemen Box & Artikel pada Main Content
- Menambahkan grid box fitur berderet 3 kolom pada area main.
- Menambahkan konten artikel berita/fitur dengan gambar (*floating image*).

![Kode HTML Grid Box](/Lab4Web/images/img-25.jpg)
![Kode CSS Grid Box](/Lab4Web/images/img-26.jpg)
![Tampilan Grid Box Features](/Lab4Web/images/img-27.jpg)
![Kode HTML Artikel Content](/Lab4Web/images/img-28.jpg)
![Kode CSS Artikel Content](/Lab4Web/images/img-29.jpg)
![Tampilan Artikel Content](/Lab4Web/images/img-30.jpg)

---

## Jawaban dan Tugas

### 1. Layout Menu About
Menambahkan halaman/seksi khusus untuk menu **About** (`about.html` / seksi `#about`) yang memuat profil perancang web, daftar keahlian/skills utama, serta galeri portofolio proyek.

![Kode HTML Layout About](/Lab4Web/images/img-31.jpg)
![Tampilan Layout About](/Lab4Web/images/img-33.jpg)

### 2. Layout Menu Contact Us
Menambahkan halaman/seksi khusus untuk menu **Contact** (`kontak.html` / seksi `#contact`) yang memuat formulir isian interaktif lengkap dengan input Nama Lengkap, Alamat Email, Subjek Pesan, serta Pesan.

![Kode HTML Layout Contact](/Lab4Web/images/img-32.jpg)
![Tampilan Layout Contact Us](/Lab4Web/images/img-34.jpg)