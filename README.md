# Portfolio Website - Mochammad Rezky Ramadhan

## Tampilan Section
1. Home (Hero Section)
   - Foto profile
   - Nama dan deskripsi
   - Tombol Instagram & LinkedIn
<p align="center">
  <img src="https://github.com/user-attachments/assets/258ea39b-8ed8-4488-9515-c26dd15a00d3" width="600"/>
</p>

2. About Me
   - Deskripsi diri
   - Skills dengan progress bar
   - Pengalaman organisasi dan project
<p align="center">
  <img src="https://github.com/user-attachments/assets/f898cc2e-b74e-4c3a-a777-07f767db03a6" width="600"/>
</p>

3. Certificates
   - 1 Sertifikat dalam bentuk card layout grid
<p align="center">
  <img src="https://github.com/user-attachments/assets/158c4c64-3a93-47ec-9b2a-8a66b4dbf48c" width="600"/>
</p>

## Penjelasan Code Setiap Section/Fitur

### 1. Navbar (`index.html`)
- Menggunakan komponen Bootstrap `navbar`.
- Berisi nama pemilik portfolio dan menu navigasi:
  - `Home`
  - `About Me`
  - `Certificates`
- Setiap menu menggunakan anchor link ke section dengan `id` terkait (`#home`, `#about`, `#certificates`).
- Class `fixed-top` membuat navbar tetap berada di atas saat halaman di-scroll.

### 2. Hero Section (`index.html`)
- Section utama perkenalan diri.
- Menampilkan:
  - Foto profil
  - Nama lengkap
  - Role/tujuan karier
  - Deskripsi singkat
- Terdapat tombol sosial media:
  - Instagram
  - LinkedIn
- Tombol sosial media sudah diberi ikon menggunakan Bootstrap Icons.

### 3. About Me Section (`index.html`)
- Berisi deskripsi singkat latar belakang dan minat.
- Dibagi menjadi dua kolom:
  - Kolom kiri: `Skills` (dengan progress bar)
  - Kolom kanan: `Experience` (daftar pengalaman/proyek)

### 4. Skills Feature (`index.html`)
- Setiap skill menggunakan komponen Bootstrap `progress`.
- Persentase kemampuan ditampilkan lewat:
  - lebar bar (`style="width: ...%"`)
  - teks persentase di dalam progress bar
- Skill saat ini:
  - Python & Java
  - SOC Analyst
  - Web Penetration

### 5. Experience Feature (`index.html`)
- Berupa daftar (`<ul><li>`) pengalaman dan proyek.
- Isi pengalaman saat ini meliputi:
  - Organisasi
  - Proyek Python
  - Proyek Java (EnergiSense)
  - Rencana belajar Blue Team SOC Analyst
  - Pembelajaran Flutter/Dart dan HTML/CSS

### 6. Certificates Section (`index.html`)
- Menampilkan kartu sertifikat menggunakan Bootstrap `card`.
- Komponen card terdiri dari:
  - Gambar sertifikat
  - Judul sertifikat
  - Deskripsi singkat

### 7. Footer (`index.html`)
- Bagian penutup halaman.
- Memuat copyright dan identitas pemilik portfolio.

## Penjelasan CSS (`style.css`)

### 1. Global Style
- `body`:
  - Mengatur font utama menggunakan `Segoe UI`.
  - Mengaktifkan `scroll-behavior: smooth` agar perpindahan antar section lebih halus.

### 2. Hero Style
- `.hero`:
  - Tinggi full layar (`height: 100vh`).
  - Background gradien biru.
  - Padding atas untuk menyesuaikan navbar fixed.

### 3. Profile Image Style
- `.profile-img`:
  - Ukuran gambar profil dibuat konsisten.
  - `border-radius: 50%` membuat foto menjadi lingkaran.
  - Border putih untuk mempertegas foto.

### 4. Section Spacing
- `section`:
  - Memberi `padding-top` agar konten tidak tertutup navbar fixed saat navigasi anchor.

### 5. Certificate Image Style
- `.card img`:
  - Tinggi gambar card diseragamkan.
  - `object-fit: cover` agar gambar tetap proporsional.

## Teknologi yang Digunakan
- HTML
- CSS
- Bootstrap 5
