# 💍 Website Undangan Pernikahan Online (Tema Arctic Rose)

Website undangan pernikahan digital eksklusif dan interaktif dengan nuansa elegan **Arctic Rose (Kadio Style)**. Dibuat menggunakan HTML5, CSS3, dan Vanilla JavaScript murni, siap di-host secara gratis di **GitHub Pages**.

---

## ✨ Fitur-Fitur Utama

- 💌 **Sampul Pembuka (Cover Gate)** dengan auto-detect nama tamu dari parameter URL (`?to=Nama+Tamu`).
- 🎵 **Pemutar Musik Latar (Background Music)** dengan tombol piringan berputar (Play/Pause otomatis saat buka undangan).
- 🌸 **Efek Kelopak Bunga Melayang (Falling Rose Petals)** berbasis HTML5 Canvas yang ringan dan anggun.
- ⏳ **Live Countdown Timer** hitung mundur real-time menuju hari H + Tombol Add to Google Calendar.
- 👰🤵 **Profil Mempelai Pria & Wanita** lengkap dengan nama orang tua, gelar, dan tombol Instagram.
- 📅 **Rangkaian Acara (Akad & Resepsi)** terintegrasi dengan Google Maps dan YouTube Live Streaming.
- 📖 **Kisah Cinta (Love Story Timeline)** perjalanan cinta dari awal perjumpaan hingga pelaminan.
- 🖼️ **Galeri Prewedding dengan Lightbox Popup** (bisa di-zoom dan digeser).
- 🎁 **Amplop Digital (Transfer Bank & QRIS & Kirim Kado)** dengan fitur 1-Klik Salin No. Rekening & Alamat.
- ✍️ **Buku Tamu & RSVP Interaktif** dengan penyimpanan lokal (`localStorage`), ucapan langsung tampil seketika.
- 📱 **QR Code Check-in Tamu** untuk keperluan registrasi di meja resepsi.
- 🧭 **Floating Bottom Navigation Bar** untuk kemudahan berpindah section.
- 📱 **100% Responsif & Mobile-Friendly** di semua perangkat (iPhone, Android, Tablet, Laptop).

---

## 🚀 Cara Upload ke GitHub Pages (Langkah demi Langkah)

### Langkah 1: Buat Repository Baru di GitHub
1. Buka [github.com](https://github.com) dan login ke akun Anda.
2. Klik tombol **New Repository** (atau tanda **+** di pojok kanan atas).
3. Beri nama repository, misalnya: `undangan-pernikahan` atau `wedding-romeo-juliet`.
4. Pilih **Public**, lalu klik **Create repository**.

### Langkah 2: Upload File Website
**Cara A: Melalui Browser (Paling Mudah & Cepat):**
1. Di halaman repository GitHub Anda yang baru dibuat, klik **Upload an existing file** atau **Add file > Upload files**.
2. Tarik (*drag and drop*) seluruh folder dan file dari proyek ini:
   - `index.html`
   - Folder `css/`
   - Folder `js/`
   - Folder `assets/` (beserta isinya)
3. Tunggu hingga semua file selesai terunggah, lalu klik **Commit changes**.

**Cara B: Menggunakan Git Command Line:**
```bash
git init
git add .
git commit -m "Initial commit wedding invitation Arctic Rose"
git branch -M main
git remote add origin https://github.com/USERNAME-ANDA/NAMA-REPO-ANDA.git
git push -u origin main
```

### Langkah 3: Mengaktifkan GitHub Pages
1. Di repository GitHub Anda, klik menu **Settings** (di tab atas).
2. Di bilah samping kiri, pilih menu **Pages**.
3. Pada bagian **Build and deployment > Source**, pilih **Deploy from a branch**.
4. Pada bagian **Branch**, pilih branch **`main`** (atau `master`) dan folder **`/ (root)`**, lalu klik **Save**.
5. Tunggu sekitar 1–2 menit hingga muncul tautan website Anda, contohnya:
   ```
   https://USERNAME-ANDA.github.io/NAMA-REPO-ANDA/
   ```

---

## 💌 Cara Membagikan Undangan ke Tamu

Cukup tambahkan `?to=Nama+Tamu` di akhir link website Anda:

- **Contoh untuk Keluarga:**
  `https://USERNAME.github.io/undangan/?to=Keluarga+Besar+Bpk+Hadi`
- **Contoh untuk Teman/Sahabat:**
  `https://USERNAME.github.io/undangan/?to=Ananda+Putri,+S.Kom`
- **Contoh dengan Pasangan:**
  `https://USERNAME.github.io/undangan/?to=Budi+%26+Partner`

---

## 📂 Struktur Direktori Proyek

```
Web Undangan/
├── index.html                  # Halaman utama website
├── css/
│   └── style.css               # Desain, animasi, dan warna tema Arctic Rose
├── js/
│   └── main.js                 # Logika JavaScript interaktif
├── assets/
│   ├── images/
│   │   ├── groom.jpg           # Foto Pengantin Pria
│   │   ├── bride.jpg           # Foto Pengantin Wanita
│   │   ├── couple-hero.jpg     # Foto Sampul Utama
│   │   ├── couple-cover.jpg    # Foto Cover Depan
│   │   ├── story-1.jpg         # Foto Kisah 1
│   │   ├── story-2.jpg         # Foto Kisah 2
│   │   ├── story-3.jpg         # Foto Kisah 3
│   │   ├── gallery-1.jpg..6.jpg# Foto Galeri Prewedding
│   │   ├── qris.jpg            # Barcode QRIS Pembayaran
│   │   └── florals/            # Ornamen floral SVG elegan
│   └── music/
│       └── wedding-song.mp3    # Lagu latar pernikahan
├── README_GAMBAR.md            # Panduan kustomisasi foto & teks
└── README.md                   # Panduan ini
```

---

*Selamat berbahagia dan semoga acara pernikahan berjalan dengan lancar dan penuh berkah!* 💐
