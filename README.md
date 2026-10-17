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

![Kode HTML Dasar Box Element](/images/img-1.png)
![Tampilan HTML Dasar Box Element](/images/img-2.png)

### 2. Menambahkan Elemen Div
- Menambahkan elemen `div` (`div1`, `div2`, `div3`) di dalam tag `<section>` pada `lab4_box.html`.

![Kode Elemen Div](/images/img-3.png)
![Tampilan Elemen Div](/images/img-4.png)

### 3. Mengatur Float Element dengan CSS
- Menambahkan style CSS pada `<head>` untuk membuat float element (`float: left; padding: 10px;`) serta memberikan warna latar pada masing-masing div.

![Kode CSS Float Element](/images/img-5.png)
![Tampilan Float Element](/images/img-6.png)

### 4. Mengatur Clearfix Element
- Menambahkan elemen `div4` di bawah `div3`.
- Menambahkan properti `clear: left;` dan `float: none;` pada kelas `.div4` untuk mengatur posisi elemen setelah elemen *float*.

![Kode Tambahan Div 4](/images/img-7.png)
![Kode CSS Clearfix](/images/img-8.png)
![Tampilan Clearfix Element](/images/img-9.png)

---

### 5. Membuat Layout Web Sederhana
- Membuat folder baru `lab4_layout`, lalu membuat file `home.html` dan file CSS `style.css`[cite: 1].
- Menyusun kerangka layout menggunakan tag *Semantic HTML* (`<header>`, `<nav>`, `<section id="hero">`, `<section id="wrapper">`, `<aside id="sidebar">`, dan `<footer>`).

![Kode Struktur HTML Layout](/images/img-10.png)
![Kode Kerangka Semantics](/images/img-11.png)
![Tampilan Awal Kerangka Layout](/images/img-12.png)

### 6. Styling Dasar dan Navigasi Layout
- Menambahkan *CSS Reset*, pengaguran font Google Fonts, style kontainer, header, serta styling navigasi (`nav`, `nav a`, `nav a.active`, `nav a:hover`) pada `style.css`.

![Kode CSS Reset & Header](/images/img-13.png)
![Tampilan Style Header](/images/img-14.png)
![Kode CSS Navigasi](/images/img-15.png)
![Tampilan Navigasi](/images/img-16.png)

### 7. Membangun Hero Panel
- Menambahkan struktur HTML untuk *Hero Panel* dan mengatur tampilannya dengan CSS.

![Kode HTML Hero Panel](/images/img-17.png)
![Kode CSS Hero Panel](/images/img-18.png)
![Tampilan Hero Panel](/images/img-19.png)

### 8. Membangun Area Main Content & Sidebar Widget
- Mengatur tata letak *Main Content* dan *Sidebar* berdampingan menggunakan `float: left`.
- Menambahkan elemen widget (link dan teks) di dalam area `<aside id="sidebar">`.

![Kode CSS Main & Sidebar](/images/img-20.png)
![Kode HTML Sidebar Widget](/images/img-21.png)
![Tampilan Main Content & Sidebar](/images/img-22.png)

### 9. Styling Footer Layout
- Menambahkan style CSS pada `footer` menggunakan `clear: both;`.

![Kode CSS Footer](/images/img-23.png)
![Tampilan Footer Layout](/images/img-24.png)

### 10. Menambahkan Elemen Box & Artikel pada Main Content
- Menambahkan grid box fitur berderet 3 kolom pada area main.
- Menambahkan konten artikel berita/fitur dengan gambar (*floating image*).

![Kode HTML Grid Box](/images/img-25.png)
![Kode CSS Grid Box](/images/img-26.png)
![Tampilan Grid Box Features](/images/img-27.png)
![Kode HTML Artikel Content](/images/img-28.png)
![Kode CSS Artikel Content](/images/img-29.png)
![Tampilan Artikel Content](/images/img-30.png)

---

## Jawaban dan Tugas

### 1. Layout Menu About
Menambahkan halaman/seksi khusus untuk menu **About** (`about.html` / seksi `#about`) yang memuat profil perancang web, daftar keahlian/skills utama, serta galeri portofolio proyek.

![Kode HTML Layout About](/images/img-31.png)
![Tampilan Layout About](/images/img-32.png)

### 2. Layout Menu Contact Us
Menambahkan halaman/seksi khusus untuk menu **Contact** (`kontak.html` / seksi `#contact`) yang memuat formulir isian interaktif lengkap dengan input Nama Lengkap, Alamat Email, Subjek Pesan, serta Pesan.

![Kode HTML Layout Contact](/images/img-33.png)
![Tampilan Layout Contact Us](/images/img-34.png)