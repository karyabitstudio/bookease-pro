# BookEase Pro

Sistem booking dan reservasi online untuk bisnis jasa. Pelanggan dapat memilih layanan, staf, tanggal, dan waktu secara mandiri, sementara pemilik bisnis dapat memantau serta mengelola booking melalui panel admin.

**Demo:** [https://bookease-pro-eight.vercel.app/](https://bookease-pro-eight.vercel.app/)

## Latar Belakang

Pemesanan layanan yang dikelola lewat telepon atau chat sering membutuhkan komunikasi bolak-balik. Pelanggan perlu menanyakan jadwal yang tersedia, sedangkan staf harus mencatat detail booking dan memastikan jadwal tidak bertabrakan. Informasi layanan, status pesanan, dan riwayat pelanggan juga bisa tersebar di berbagai tempat.

BookEase Pro menyatukan alur tersebut dalam satu website. Pelanggan bisa mengisi booking secara online, memeriksa status, dan melihat riwayatnya. Admin dapat melihat booking yang masuk serta memperbarui statusnya.

- **Pemesanan lebih praktis.** Pelanggan memilih layanan, staf, tanggal, dan jam melalui alur booking.
- **Status mudah diperiksa.** Pelanggan dapat mencari booking menggunakan kode booking atau nomor WhatsApp.
- **Riwayat tersimpan.** Halaman Booking Saya menampilkan booking berdasarkan nomor WhatsApp.
- **Administrasi terpusat.** Admin dapat melihat detail booking dan mengelola status pesanan.
- **Tampilan responsif.** Halaman dirancang untuk digunakan melalui ponsel, tablet, maupun desktop.

## Fitur

### Pelanggan

- Form booking online empat langkah: pilih layanan, staf, tanggal dan jam, lalu konfirmasi
- Notifikasi berhasil beserta kode booking
- Cek status booking menggunakan kode atau nomor WhatsApp
- Lihat riwayat booking berdasarkan nomor WhatsApp
- Lihat detail layanan, jadwal, staf, harga, dan status booking

### Admin

- Dashboard statistik dan booking terbaru
- Daftar booking dengan filter status
- Ubah status booking menjadi dikonfirmasi, selesai, atau dibatalkan
- Lihat detail booking pelanggan
- Kelola informasi layanan dan staf melalui modul demo
- Lihat ringkasan laporan dan pengaturan bisnis pada panel admin

## Cara Kerja Demo

1. Buka halaman [Booking](https://bookease-pro-eight.vercel.app/booking.html) dan isi data pemesanan.
2. Catat kode booking yang ditampilkan setelah konfirmasi.
3. Buka halaman [Cek Booking](https://bookease-pro-eight.vercel.app/cek-booking.html) untuk mencari status dengan kode atau nomor WhatsApp.
4. Buka halaman [Booking Saya](https://bookease-pro-eight.vercel.app/booking-saya.html) dan masukkan nomor WhatsApp yang digunakan.
5. Buka [Admin Demo](https://bookease-pro-eight.vercel.app/admin.html) untuk melihat dan mengelola booking.

## Teknologi

- HTML5
- Tailwind CSS melalui CDN
- JavaScript tanpa framework
- Font Awesome 6 untuk ikon
- Inter dari Google Fonts
- `localStorage` browser untuk data booking demo

> Ini adalah demo frontend. Data booking disimpan pada browser yang digunakan dan tidak tersinkronisasi ke perangkat atau browser lain. Integrasi backend, notifikasi WhatsApp, dan pembayaran online memerlukan layanan tambahan untuk penggunaan produksi.

## Struktur File

```text
bookease-pro/
├── index.html          # Landing page
├── booking.html        # Form booking
├── cek-booking.html    # Pencarian status booking
├── booking-saya.html   # Riwayat booking pelanggan
├── admin.html          # Panel admin demo
├── styles.css          # Gaya tambahan
└── README.md           # Dokumentasi proyek
```

## Menjalankan Secara Lokal

Karena proyek ini berupa website statis, tidak perlu memasang dependensi terlebih dahulu. Clone repository, lalu buka `index.html` di browser.

Untuk menjalankan melalui server lokal, buka terminal di folder proyek dan jalankan salah satu perintah berikut:

```bash
# Python
python -m http.server 8080
```

```bash
# Node.js
npx serve .
```

Kemudian buka [http://localhost:8080](http://localhost:8080).

## Cocok Untuk

Salon dan barbershop, klinik, studio foto, rental, gym, spa, klinik gigi, pet grooming, lapangan olahraga, konsultan, makeup artist, serta homestay atau villa.

## Kredit

**BookEase Pro** — demo sistem booking online untuk bisnis jasa.

© 2026 KaryaBit Studio
