# Undangan-Pernikahan

# 💍 The Wedding of Abdullah & Intan

Sebuah website undangan pernikahan digital (Web Invitation) yang responsif, estetis, dan interaktif. Proyek ini dibangun menggunakan HTML, CSS, dan Bootstrap 5, dirancang untuk memberikan pengalaman undangan online yang elegan kepada tamu.

## 🌟 Fitur Utama

* **Responsive Design:** Tampilan yang menyesuaikan otomatis di perangkat Mobile, Tablet, dan Desktop.
* **Hero & Lock Screen:** Halaman pembuka dengan tombol "Buka Undangan" untuk mengaktifkan scroll dan musik.
* **Background Music:** Pemutar musik otomatis (autoplay) dengan tombol kontrol play/pause.
* **Countdown Timer:** Hitung mundur waktu acara secara *real-time* menuju tanggal resepsi.
* **Love Story Timeline:** Visualisasi perjalanan cinta pasangan dalam bentuk garis waktu.
* **Interactive Gallery:** Galeri foto dengan fitur *lightbox* (popup zoom) dan efek hover.
* **Personalisasi Tamu (URL Parameter):** Menampilkan nama tamu secara otomatis di halaman pembuka.
* **Peta Lokasi:** Integrasi Google Maps untuk memudahkan tamu menemukan lokasi.
* **RSVP Form:** Formulir konfirmasi kehadiran dengan simulasi loading dan notifikasi.
* **Animasi Scroll:** Efek visual halus saat halaman digulir (menggunakan AOS).

## 🛠️ Teknologi yang Digunakan

* **Frontend:** HTML5, CSS3, JavaScript (ES6)
* **Framework:** [Bootstrap v5.3](https://getbootstrap.com/)
* **Icons:** [Bootstrap Icons](https://icons.getbootstrap.com/)
* **Fonts:** Google Fonts (Cinzel & Poppins)
* **Libraries:**
    * [AOS (Animate On Scroll)](https://michalsnik.github.io/aos/)
    * [SimplyCountdown.js](https://github.com/VincentLoy/simplyCountdown.js)
    * [BS5 Lightbox](https://trvswgnr.github.io/bs5-lightbox/)

## 📂 Struktur Folder

Pastikan susunan folder dan file aset kamu seperti berikut agar semua gambar dan musik berjalan dengan benar:

```text
wedding-invitation/
│
├── index.html                # File utama (Main Code)
├── README.md                 # Dokumentasi Proyek
├── audio/
│   └── wedding-song.mp3      # File musik latar
│
└── image/
    ├── bg-prewed.jpg         # Background halaman depan
    ├── foto depan/           # Foto profil mempelai
    │   ├── foto-abdul.jpg
    │   └── foto-intan.jpg
    ├── foto/                 # Foto untuk timeline story
    │   ├── foto-sekolah.jpg
    │   ├── berdua-2.jpg
    │   └── foto-berdua.jpeg
    └── galerry/              # Foto untuk bagian galeri
        ├── karikatur 1.jpeg
        ├── karikatur 2.jpeg
        └── karikatur 3.jpeg

🚀 Cara Penggunaan
1. Menjalankan Website
Cukup buka file index.html menggunakan browser modern (Chrome, Edge, Firefox, atau Safari).

2. Fitur Sebar Undangan (Nama Tamu)
Kamu bisa membuat link khusus untuk setiap tamu agar nama mereka muncul di halaman depan. Tambahkan parameter ?n= (nama) dan ?p= (panggilan) di akhir URL.

Format URL:

index.html?p=Panggilan&n=Nama Tamu

Contoh: Jika ingin mengundang Bapak Jokowi, gunakan link:

[yourwebsite.com/index.html?p=Bapak&n=Jokowi](https://yourwebsite.com/index.html?p=Bapak&n=Jokowi)
Hasil Tampilan:

Kepada Bapak Jokowi,

📝 Catatan Pengembang
RSVP: Saat ini fitur RSVP menggunakan JavaScript murni untuk simulasi (menampilkan alert sukses). Untuk penggunaan nyata, disarankan menghubungkannya ke Google Sheets (via Google Apps Script) atau Backend Database.

Musik: Beberapa browser memblokir autoplay audio secara default. Oleh karena itu, musik baru akan berputar setelah tombol "Lihat Undangan" diklik oleh user.

👤 Author
Abdullah Irfan Budiono
Mahasiswa Teknik Informatika, Universitas Pamulang.
