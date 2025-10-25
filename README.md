# 🌐 Portofolio Muhammad Rizq Maulana

Ini adalah proyek portofolio pribadi yang dibuat menggunakan **HTML dan CSS**.  
Tujuannya untuk memperkenalkan diri, menampilkan kemampuan, serta menjadi latihan publikasi di **GitHub Pages**.

---


---

## 💡 Penjelasan Kode

### 🧱 1. HTML — Struktur Halaman

#### a. Bagian `<head>`
Berisi informasi penting untuk browser:
- `<!DOCTYPE html>` → Menentukan dokumen HTML5.  
- `<meta charset="UTF-8">` → Mendukung karakter internasional.  
- `<meta name="viewport">` → Agar web responsif di HP & PC.  
- `<title>` → Judul tab browser.  
- `<link rel="stylesheet" href="style.css">` → Menghubungkan file HTML ke CSS.

#### b. Bagian `<header class="container">`
Tempat bagian utama portofolio:
- Menampilkan **nama, profesi, dan sekolah**.
- Memuat **gambar logo** dan **foto profil**.
- Menggunakan layout **Flexbox** (teks di kiri, gambar di kanan).

#### c. Bagian `<section class="skills">`
Menampilkan daftar kemampuan yang dimiliki:
- Menggunakan elemen `<ul>` dan `<li>` untuk daftar.
- Masing-masing item menjelaskan keahlian seperti HTML, CSS, JavaScript dasar, dan GitHub Pages.

---

### 🎨 2. CSS — Desain & Tampilan

#### a. `body`
Mengatur gaya dasar halaman:
- Font: Arial  
- Warna latar: abu muda `#f0f0f5`  
- Warna teks: abu tua `#333`

#### b. `.container`
Mengatur tata letak utama header:
- `display: flex;` → Menyusun teks dan gambar sejajar.
- `justify-content: space-between;` → Memberi jarak antar sisi.
- `align-items: center;` → Sejajar vertikal.
- Warna latar: biru `#4b6cb7`, teks putih.

#### c. `.text`
Lebar setengah halaman (`width: 50%`), berisi teks perkenalan.

#### d. `.logo`
- Ukuran 100px, sudut melengkung (`border-radius: 10px`).
- Diberi jarak bawah agar tidak menempel dengan teks.

#### e. `h1, h2, h3`
- Mengatur ukuran dan jarak antar judul.
- `h1` untuk nama utama, `h2` untuk profesi, `h3` untuk sekolah.

#### f. `p`
Paragraf penjelasan dengan:
- `font-size: 16px;`
- `line-height: 1.6;`
- Warna abu muda agar kontras dengan latar biru.

#### g. `.image` dan `.side-img`
Menampilkan gambar profil di kanan:
- Gambar bulat (`border-radius: 50%`).
- Efek bayangan halus (`box-shadow`).
- Garis putih (`border: 4px solid white`).

#### h. `.skills`
Bagian daftar kemampuan:
- Latar putih dan teks rata tengah.
- Tiap kemampuan dibuat kotak biru lembut dengan `border-radius: 8px`.

#### i. `@media (max-width: 768px)`
Aturan **responsif** untuk tampilan HP:
- Mengubah arah Flexbox jadi kolom (atas–bawah).
- Teks dan gambar ditengah.
- Gambar profil diperkecil.

---

## 📱 Responsif Design

Tampilan otomatis menyesuaikan ukuran layar:
- **PC/Desktop:** Teks di kiri, gambar di kanan.
- **HP:** Teks di atas, gambar di bawah, semua rata tengah.

---

## 🚀 Teknologi yang Digunakan

- **HTML5** — Struktur halaman web  
- **CSS3 (Flexbox + Media Query)** — Desain dan tata letak responsif  
- **GitHub Pages** — Untuk menampilkan portofolio online  

---

## ✨ Preview
Halaman ini menampilkan:
- Foto dan perkenalan diri
- Daftar kemampuan
- Tampilan modern dengan warna biru dan abu muda

---

## 🧑‍💻 Tentang Saya
**Muhammad Rizq Maulana**  
Pelajar SMK Muhammadiyah 3 Tangerang Selatan  
Tertarik di bidang pengembangan web, desain UI/UX, dan teknologi digital.

---

## ⚙️ Cara Melihat di GitHub Pages
1. Upload file `index.html` dan `style.css` ke repository GitHub.  
2. Buka menu **Settings → Pages**.  
3. Aktifkan GitHub Pages dari branch `main` atau `master`.  
4. Web portofolio akan bisa diakses melalui tautan GitHub Pages kamu.

---

## 📸 Screenshot (Opsional)
Kamu bisa menambahkan gambar pratinjau halaman di sini:


---

##
