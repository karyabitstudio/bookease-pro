# BookEase Pro

**Sistem Booking & Reservasi Online** — Demo portfolio oleh [KaryaBit Studio](https://karyabit-studio.vercel.app)

Website demo lengkap untuk sistem booking/reservasi bisnis jasa (salon, klinik, studio, rental, gym, spa, dll).

---

## Fitur

### Sisi Pelanggan
- **Booking online** 4 langkah: pilih layanan → staf → tanggal/jam → konfirmasi
- **Cek status booking** (pakai kode atau nomor WhatsApp)
- **Booking Saya** — riwayat booking berdasarkan nomor WhatsApp
- Notifikasi sukses + kode booking

### Sisi Admin
- **Dashboard** — statistik hari ini, booking terbaru, layanan terlaris
- **Kelola Booking** — filter status, ubah status (Konfirmasi / Selesai / Batal)
- **Modal Detail Booking** — info lengkap + aksi cepat
- **Layanan** — daftar layanan, harga, durasi
- **Staf** — profil, jadwal, status aktif/cuti
- **Laporan** — performa staf & layanan
- **Pengaturan** — info bisnis, notifikasi, pembayaran

### Teknis (Demo)
- Data booking tersimpan di **localStorage** browser
- Booking baru dari demo langsung muncul di Admin & Cek Booking
- Fully responsive (HP, tablet, desktop)
- UI modern dengan Tailwind CSS

---

## Struktur File

```
bookease-pro/
├── index.html          # Landing page (fitur, harga, CTA)
├── booking.html        # Form booking interaktif
├── cek-booking.html    # Cek status booking
├── booking-saya.html   # Riwayat booking pelanggan
├── admin.html          # Admin panel (6 modul)
└── README.md           # Dokumentasi ini
```

---

## Cara Menjalankan

1. Download / clone folder `bookease-pro`
2. Buka `index.html` di browser
3. Atau jalankan local server:

```bash
# Python
python -m http.server 8080

# Node (npx)
npx serve .
```

Lalu buka: `http://localhost:8080`

---

## Alur Demo yang Disarankan

1. Buka **Booking** → buat booking baru (isi nama + nomor WA)
2. Catat **kode booking** yang muncul
3. Buka **Cek Booking** → masukkan kode → status muncul
4. Buka **Booking Saya** → masukkan nomor WA yang sama → riwayat muncul
5. Buka **Admin** → tab Booking → booking baru ada di daftar
6. Klik **Detail** → modal info lengkap
7. Ubah status (Konfirmasi / Selesai / Batal)

---

## Tech Stack (Demo Frontend)

| Item | Teknologi |
|------|-----------|
| HTML | Semantic HTML5 |
| CSS | Tailwind CSS (CDN) |
| JS | Vanilla JavaScript |
| Icons | Font Awesome 6 |
| Font | Inter (Google Fonts) |
| Storage | localStorage (browser) |

> **Catatan:** Ini adalah demo frontend. Versi production biasanya dibangun dengan **Laravel + Filament PHP** (backend + admin panel).

---

## Paket Harga (Referensi Portfolio)

| Paket | Estimasi | Fitur Utama |
|-------|----------|-------------|
| Basic | Rp 3,5jt | Booking + Admin + Email |
| Standard | Rp 5,5jt | + WhatsApp + Reminder + Laporan |
| Premium | Rp 8jt+ | + Midtrans + Multi cabang + Custom |

---

## Cocok Untuk

Salon & Barbershop · Klinik & Dokter · Studio Foto · Rental · Gym · Spa · Klinik Gigi · Pet Grooming · Lapangan Olahraga · Konsultan · Makeup Artist · Homestay/Villa

---

## Credits

**BookEase Pro** — Portfolio project by **KaryaBit Studio**  
Website: [karyabit-studio.vercel.app](https://karyabit-studio.vercel.app)

© 2026 KaryaBit Studio
