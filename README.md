# Laporan Analisis Sintaks HTML: Profil Mahasiswa

1. Informasi Umum
Judul Halaman: Profil Mahasiswa
Nama Mahasiswa: Yudha Eka P
NIM: 312310362
Program Studi: Teknik Informatika

Tujuan Dokumen: Menampilkan halaman profil pribadi/mahasiswa sederhana yang berisi data diri, foto profil, tautan navigasi, keahlian, dan target pembelajaran.

2. Struktur Dokumen & Penjelasan Tag (Elemen per Elemen)
Berikut adalah rincian setiap baris dan elemen tag HTML yang digunakan dalam dokumen tersebut:
A. Deklarasi Dokumen dan Bagian Kepala (<head>)

<img width="293" height="16" alt="Screenshot 2026-09-24 153254" src="https://github.com/user-attachments/assets/eda10207-7d80-450a-ab37-f8d98e0c7ab1" />

Penjelasan: Deklarasi tipe dokumen yang memberi tahu peramban (browser) bahwa dokumen ini menggunakan standar HTML5 terbaru.

<img width="136" height="22" alt="Screenshot 2026-09-24 153349" src="https://github.com/user-attachments/assets/3a9ab716-caf9-436c-8e35-083648c73e41" />

Penjelasan: Elemen akar (root element) yang membungkus seluruh isi halaman HTML.

<img width="121" height="21" alt="Screenshot 2026-09-24 153354" src="https://github.com/user-attachments/assets/72febc3c-bd53-4bed-8df7-5a2839b2f440" />

Penjelasan: Bagian kepala dokumen yang memuat metadata halaman (informasi yang tidak ditampilkan secara langsung di badan halaman web).

<img width="459" height="21" alt="Screenshot 2026-09-24 160607" src="https://github.com/user-attachments/assets/3a501af2-f062-4938-825f-ef2649c494c8" />

Penjelasan: Menentukan judul halaman yang akan muncul pada tab atau jendela browser (dalam hal ini tertulis "Profil Mahasiswa").

B. Bagian Tubuh Dokumen (<body>)
Bagian <body> memuat seluruh konten yang dapat dilihat oleh pengguna di dalam browser.

# 1. Navigasi (<nav> & <a>)
HTML
<nav>
 <a href="index.html">Beranda</a>
 <a href="halaman2.html">Halaman 2</a>
</nav>
<hr>
<nav>: Digunakan untuk mengelompokkan tautan navigasi utama situs web.

<a href="index.html">Beranda</a>: Tautan hiperteks (anchor) menuju halaman utama (index.html).

<a href="halaman2.html">Halaman 2</a>: Tautan hiperteks menuju halaman kedua (halaman2.html).

<hr>: Garis horizontal (horizontal rule) yang berfungsi sebagai pemisah visual antara menu navigasi dan konten utama.

# 2. Judul Utama (<h1>) & Gambar (<img>)

HTML
<h1>Profil Mahasiswa</h1>
<img src="WhatsApp Image 2026-09-24 at 15.22.27.jpeg" width="200" alt="Foto profil mahasiswa">
<h1>: Menampilkan judul utama halaman dengan ukuran teks terbesar, yaitu "Profil Mahasiswa".

<img>: Menampilkan gambar/foto profil.

src="WhatsApp Image 2026-09-24 at 15.22.27.jpeg": Menentukan lokasi atau nama file gambar sumber.

width="200": Mengatur lebar gambar sebesar 200 piksel.

alt="Foto profil mahasiswa": Teks alternatif yang akan muncul jika gambar gagal dimuat oleh browser (juga berguna untuk aksesibilitas pembaca layar).

# 3. Data Diri (<h2> & <p>)

HTML
<h2>Data Diri</h2>
<p>Nama: Yudha Eka P</p>
<p>Program Studi: Teknik Informatika</p>
<p>NIM: 312310362</p>
<p>Saya sedang mempelajari dasar-dasar pengembangan aplikasi web menggunakan HTML.</p>
<h2>: Judul sub-bagian dengan ukuran tingkat kedua untuk menandai awal bagian "Data Diri".

<p>: Paragraf teks untuk merinci informasi data diri:

Paragraf 1: Nama mahasiswa (Yudha Eka P).

Paragraf 2: Program studi (Teknik Informatika).

Paragraf 3: Nomor Induk Mahasiswa / NIM (312310362).

Paragraf 4: Deskripsi singkat mengenai kegiatan saat ini ("Saya sedang mempelajari dasar-dasar pengembangan aplikasi web menggunakan HTML").

# 4. Keahlian (<h2> & <ul> / <li>)

HTML
<h2>Keahlian</h2>
<ul>
<li>HTML</li>
<li>CSS</li>
<li>JavaScript</li>
</ul>
<h2>: Judul sub-bagian untuk bagian "Keahlian".

<ul> (Unordered List): Membuat daftar item yang tidak berurutan (ditandai dengan bentuk titik/bullet).

<li> (List Item): Anggota/butir dari daftar keahlian, yang terdiri dari:

HTML

CSS

JavaScript

# 5. Target Belajar (<h2> & <ol> / <li>)

HTML
<h2>Target Belajar</h2>
<ol>
<li>Menguasai HTML</li>
<li>Menguasai CSS</li>
<li>Menguasai JavaScript</li>
</ol>
<h2>: Judul sub-bagian untuk bagian "Target Belajar".

<ol> (Ordered List): Membuat daftar item yang berurutan atau bernomor (1, 2, 3, dst.).

<li> (List Item): Anggota/butir dari target belajar yang berurutan:

Menguasai HTML

Menguasai CSS

Menguasai JavaScript

# 3. Kesimpulan
Sintaks HTML di atas sudah ditulis dengan struktur dasar yang baik dan sesuai untuk halaman web pengenalan profil pribadi (static web page). Dokumen ini memanfaatkan elemen-elemen semantik standar HTML5 seperti <nav> untuk navigasi, <h1> & <h2> untuk hierarki judul, <p> untuk teks paragraf, serta <ul> dan <ol> untuk pengorganisasian daftar data keahlian dan target.
