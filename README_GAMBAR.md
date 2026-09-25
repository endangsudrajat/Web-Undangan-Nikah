# 🌸 Panduan Mengganti Gambar & Kustomisasi Undangan

Website undangan pernikahan ini dirancang dengan struktur file yang rapi sehingga Anda dapat mengganti semua gambar dan teks dengan sangat mudah.

---

## 📁 Daftar Gambar di Folder `assets/images/`

Cukup siapkan foto Anda dan simpan ke folder `assets/images/` dengan **nama file yang sama**:

| Nama File | Keterangan & Rekomendasi Ukuran |
| :--- | :--- |
| `couple-cover.jpg` | **Foto Sampul Depan (Cover Pembuka)** - Rasio 3:4 atau Portrait (contoh: 800 x 1060 px) |
| `couple-hero.jpg` | **Foto Utama Banner Setelah Dibuka** - Rasio 3:4 atau Portrait (contoh: 800 x 1100 px) |
| `groom.jpg` | **Foto Pengantin Pria** - Rasio 1:1 / Persegi (contoh: 600 x 600 px) |
| `bride.jpg` | **Foto Pengantin Wanita** - Rasio 1:1 / Persegi (contoh: 600 x 600 px) |
| `story-1.jpg` | **Foto Kisah Cinta 1 (Awal Bertemu)** - Rasio 4:3 (contoh: 600 x 450 px) |
| `story-2.jpg` | **Foto Kisah Cinta 2 (Menjalin Kasih)** - Rasio 4:3 (contoh: 600 x 450 px) |
| `story-3.jpg` | **Foto Kisah Cinta 3 (Lamaran)** - Rasio 4:3 (contoh: 600 x 450 px) |
| `gallery-1.jpg` s/d `gallery-6.jpg` | **Galeri Prewedding 1 s/d 6** - Rasio Portrait / Persegi (contoh: 700 x 850 px) |
| `qris.jpg` | **Barcode QRIS / Amplop Digital** - Gambar QRIS dari M-Banking/E-Wallet |

> 💡 **Tips Format File:** Format yang didukung adalah `.jpg`, `.jpeg`, `.png`, atau `.webp`. Jika ekstensi foto Anda `.png`, Anda bisa mengubah ekstensi di `index.html` (misal dari `groom.jpg` menjadi `groom.png`).

---

## 🎵 Mengganti Musik Latar (Lagu Pernikahan)

File musik tersimpan di folder `assets/music/`:
- Ganti file `assets/music/wedding-song.mp3` dengan lagu pilihan Anda (format `.mp3`).
- Anda juga dapat mengganti tautan audio di `index.html` pada bagian tag `<audio id="bgMusic">`.

---

## ✏️ Mengubah Data Teks di `index.html`

Buka file [index.html](file:///home/mage/Web%20Undangan/index.html) menggunakan text editor:

1. **Nama Mempelai & Orang Tua:**
   - Cari kata `Romeo Montague` dan ganti dengan nama pengantin pria.
   - Cari kata `Juliet Capulet` dan ganti dengan nama pengantin wanita.
   - Ubah nama orang tua di bagian `<p class="profile-parents">`.

2. **Tanggal & Lokasi Acara:**
   - Ubah tanggal di bagian `<section id="event">`.
   - Ubah tautan Google Maps pada tombol `<a href="https://maps.google.com/?q=..." class="btn-map">`.

3. **Nomor Rekening / Amplop Digital:**
   - Cari bagian `<section id="gift">`.
   - Ubah nama Bank, Nomor Rekening, dan Nama Pemilik Rekening.
   - Pastikan juga memperbarui atribut `data-copy="..."` pada tombol salin agar nomor rekening yang disalin sesuai.

4. **Countdown Timer:**
   - Buka file [js/main.js](file:///home/mage/Web%20Undangan/js/main.js)
   - Cari baris `const targetDate = new Date('2026-04-17T09:00:00+07:00').getTime();`
   - Ganti `2026-04-17T09:00:00` dengan tanggal & waktu pernikahan Anda.

---

## 💌 Cara Membuat Link Undangan dengan Nama Tamu Khusus

Website ini otomatis membaca parameter `?to=Nama+Tamu` dari link:
- `https://username.github.io/undangan/?to=Bapak+Budi+dan+Keluarga`
- `https://username.github.io/undangan/?to=Sahabatku+Annisa`
- `https://username.github.io/undangan/?to=Dr.+Ahmad+Fauzi,+Sp.A`

Spasi dapat ditulis dengan tanda tambah `+` atau `%20`.
