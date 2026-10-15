# VyanTravel - Web Pemesanan Paket Wisata

Aplikasi web informasi dan reservasi paket wisata berbasis PHP native dengan arsitektur MVC sederhana. Proyek dikembangkan sebagai tugas UAS Praktikum Pemrograman Web Lanjut (PWL).

## Anggota Pengembang
- Muhammad Sultan Hafidz (A12.2024.07163)
- Dimas Arya Pratama (A12.2024.07180)
- Muhammad Rafael Rasya N (A12.2024.07153)
- Muhammad Rafly Setyo Handika (A12.2024.07183)

## Fitur Utama
- **Katalog Paket Wisata**: Informasi destinasi, fasilitas, durasi perjalanan, dan harga.
- **Sistem Pemesanan (Booking)**: Alur order tiket wisata oleh pelanggan dengan konfirmasi jadwal.
- **Manajemen Admin**: Pengelolaan paket (CRUD), validasi status pemesanan, dan dashboard kontrol.
- **Role-Based Access Control**: Pemisahan hak akses antara Pelanggan dan Administrator.

## Teknologi
- PHP (PDO Connection)
- MySQL / MariaDB
- Arsitektur MVC
- Bootstrap & Custom CSS

## Panduan Instalasi
1. Pindahkan folder ke direktori server web (misal: htdocs/vyantravel-tour-booking).
2. Buat database baru di MySQL dan import berkas database/vyantravel_db.sql.
3. Buka browser dan akses melalui entry point publik:
   `
   http://localhost/vyantravel-tour-booking/public/
   `
"@
        gitignore = @"
.vscode/
.idea/
*.log
Thumbs.db
.DS_Store
