# Modul Odoo Room Booking

Modul ini digunakan untuk mengelola pemesanan ruangan di Odoo, termasuk pengelolaan ruangan dan pemesanan.

## Fitur

1. **Master Ruangan**:
   - Nama Ruangan (Mandatory)
   - Tipe Ruangan (Mandatory)
   - Lokasi Ruangan (Mandatory)
   - Foto Ruangan (Mandatory)
   - Kapasitas Ruangan (Mandatory)
   - Keterangan

2. **Pemesanan Ruangan**:
   - Nomor Pemesanan (Mandatory)
   - Ruangan (Mandatory)
   - Nama Pemesanan (Mandatory)
   - Tanggal Pemesanan (Mandatory)
   - Status Pemesanan (Default Draft)
   - Catatan Pemesanan

3. **Views**:
   - Tampilan Master Ruangan dalam bentuk Grid / List
   - Tampilan Pemesanan Ruangan
   - Button untuk memproses pemesanan

4. **Validation**:
   - Validasi untuk pemesanan ruangan yang sama pada tanggal yang sama
   - Validasi untuk nama pemesanan yang sama
   - Validasi untuk nama ruangan yang sama
   - Perlindungan terhadap SQL Injection

5. **API**:
   - API untuk tracking status pemesanan

## Instalasi

1. Salin folder `room_booking` ke dalam direktori `addons` Odoo Anda.
2. Aktifkan modul melalui antarmuka Odoo.
3. Konfigurasi akses pengguna sesuai kebutuhan.

## Penggunaan

- **Master Ruangan**: Tambahkan, edit, atau hapus ruangan dari menu Ruangan.
- **Pemesanan Ruangan**: Buat pemesanan baru dan proses status pemesanan melalui menu Pemesanan.

