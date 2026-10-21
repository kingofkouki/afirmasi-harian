30 Hari Afirmasi Diri (PWA)
Aplikasi web interaktif dan ringan (Progressive Web App) yang dirancang sebagai panduan harian selama 30 hari untuk membangun kepercayaan diri, karier, manajemen keuangan, kesehatan, keluarga, dan spiritualitas. Aplikasi ini dirancang agar terasa personal, menjaga privasi, dan bisa digunakan sebagai panduan latihan journaling atau menulis indah.

✨ Fitur Utama
📱 PWA Ready (Bisa Diinstal & Offline): Dapat diinstal langsung ke layar utama (Home Screen) HP Android/iOS dan Desktop layaknya aplikasi native. Berjalan 100% offline setelah instalasi berkat Service Worker.

🌐 Dwibahasa (Bilingual): Seluruh afirmasi dan tindakan nyata tersedia dalam Bahasa Indonesia dan Bahasa Inggris, sangat berguna untuk meningkatkan kemampuan bahasa (reading & speaking).

✍️ Gaya Tulisan Tangan (Menulis Indah): Tersedia berbagai pilihan font kaligrafi (Caveat, Dancing Script, Kalam, Indie Flower) untuk memfasilitasi pengguna yang ingin menyalin afirmasi ke buku catatan fisik dengan gaya tulisan estetik.

🌗 Mode Gelap & Terang (Dark/Light Mode): Tampilan responsif dan memanjakan mata yang dapat diubah sesuai preferensi pencahayaan.

🎉 Gamifikasi Progres: Efek confetti yang memuaskan setiap kali pengguna menandai afirmasi harian sebagai "selesai", meningkatkan motivasi dan retensi pengguna.

💾 100% Privasi (Local Storage): Tidak memerlukan pendaftaran akun atau server database. Seluruh progres 30 hari disimpan secara aman di dalam Local Storage browser perangkat Anda.

🖨️ Fitur Ekspor & Cetak: Tersedia tombol aksi cepat untuk menyalin teks ke clipboard atau mencetaknya (termasuk menyimpan sebagai PDF) dengan format cetak yang sudah dioptimalkan (tanpa elemen navigasi).

🛠️ Teknologi yang Digunakan
Frontend: HTML5, CSS3 (Variabel CSS, Flexbox/Grid, Animasi Transisi), Vanilla JavaScript (ES6).

PWA: manifest.json dan sw.js (Service Worker API).

Tipografi: Google Fonts.

Library Eksternal: Canvas Confetti (untuk efek perayaan).

Tanpa Framework: Sepenuhnya dibangun tanpa dependensi berat seperti React, Vue, atau Bootstrap untuk memastikan ukuran file sangat kecil dan performa pemuatan seketika (instant load).

🚀 Cara Menjalankan & Instalasi
1. Penggunaan Lokal (Tanpa Instalasi PWA)
Unduh atau clone repositori ini.

Buka file index.html langsung menggunakan browser apa saja (Chrome, Firefox, Safari).

2. Instalasi PWA (Web Hosting)
Agar aplikasi dapat memunculkan tombol "Install" (Add to Home Screen) di perangkat seluler:

Pastikan seluruh file (index.html, manifest.json, sw.js, icon-192.png, icon-512.png) berada di satu folder utama.

Unggah repository ini ke layanan hosting statis gratis yang menggunakan protokol HTTPS, seperti GitHub Pages, Vercel, atau Netlify.

Akses tautan publik dari layanan hosting tersebut menggunakan Google Chrome atau Safari di perangkat pintar.

├── index.html       # File struktur utama, gaya UI, logika JS, dan data afirmasi
├── manifest.json    # Konfigurasi identitas PWA (nama aplikasi, warna tema)
├── sw.js            # Service worker untuk mekanisme caching dan mode offline
├── icon-192.png     # Aset ikon aplikasi ukuran kecil
└── icon-512.png     # Aset ikon aplikasi ukuran besar (Splash screen)

Akan muncul prompt atau tombol "Install App" di bagian bawah layar. Klik untuk menginstal.

📁 Struktur File
