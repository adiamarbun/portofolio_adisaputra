# Portfolio - Adisaputra Marbun

Repositori ini berisi kode sumber untuk situs web portfolio pribadi **Adisaputra Marbun**. Portfolio ini dirancang secara profesional dengan tema teknologi gelap (*dark tech theme*) yang modern, responsif, dan interaktif.

## 🌟 Fitur Utama
- **Desain Responsif:** Tampilan yang optimal di semua ukuran perangkat (Desktop, Tablet, Mobile).
- **Dark Tech Theme:** Skema warna gelap yang estetis dengan aksen gradasi modern untuk memikat pengunjung.
- **AOS (Animate On Scroll):** Animasi halus saat menggulir halaman.
- **Typed.js:** Efek teks mengetik dinamis pada bagian perkenalan hero section.
- **Vite Build System:** Menggunakan Vite untuk proses pengembangan yang cepat dan efisien.

## 🛠️ Tech Stack & Alat
- **Bahasa & Library:** HTML5, CSS3 (Vanilla), JavaScript (ES6+), Typed.js, AOS.
- **Alat Pengembangan:** Vite, Node.js, Git & GitHub.
- **Desain & Aset:** Figma, Canva, Adobe Illustrator.

## 📂 Struktur Folder
```text
portfolio-hcj/
├── dist/                   # File hasil kompilasi produksi (diabaikan oleh git)
├── portfolio-hcj/          # Folder berisi aset-aset warisan (legacy) dan catatan
│   ├── assets/             # Folder aset gambar, ikon, logo
│   └── catatan.txt
├── src/                    # Folder kode sumber utama
│   ├── css/                # File stylesheet (style.css)
│   └── js/                 # File JavaScript utama (script.js)
├── index.html              # Template HTML utama
├── package.json            # Konfigurasi package Node.js & Vite
├── README.md               # Dokumentasi proyek (file ini)
└── vite.config.js          # (Opsional jika ada) Konfigurasi Vite
```

## 🚀 Proyek Terpilih yang Ditampilkan
1. **LeafCheck:** Aplikasi klasifikasi penyakit daun tanaman berbasis Deep Learning (TensorFlow).
2. **Website Company (BengkelGO):** Website profil perusahaan profesional untuk bengkel otomotif.
3. **Website Course (BengkelGO Cashier):** Template dashboard kasir dan manajemen kursus online.
4. **TBotics Education:** Portal pembelajaran interaktif STEAM & robotika lengkap dengan navigasi alur belajar (*learning path*) dan sistem manajemen challenge/event.

## 💻 Cara Menjalankan Secara Lokal

### Prasyarat
Pastikan Anda sudah menginstal [Node.js](https://nodejs.org/) di perangkat Anda.

### Langkah-langkah
1. **Clone Repositori:**
   ```bash
   git clone https://github.com/adiamarbun/portofolio_adisaputra.git
   ```
2. **Masuk ke Direktori Proyek:**
   ```bash
   cd portofolio_adisaputra
   ```
3. **Instal Dependensi:**
   ```bash
   npm install
   ```
4. **Jalankan Server Pengembangan (Dev Server):**
   ```bash
   npm run dev
   ```
   Buka peramban (browser) Anda dan akses alamat `http://localhost:5173`.
5. **Build untuk Produksi:**
   ```bash
   npm run build
   ```
   File hasil kompilasi yang siap dideploy akan dibuat di folder `dist/`.

---
Dibuat oleh [Adisaputra Marbun](https://github.com/adiamarbun). Hak Cipta dilindungi undang-undang.
