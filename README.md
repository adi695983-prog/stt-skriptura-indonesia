# 📚 Sistem Informasi Perpustakaan STT SKRIPTURA INDONESIA

Aplikasi web sederhana untuk mengelola perpustakaan (buku, anggota, peminjaman, pengembalian, laporan).  
Dibangun dengan **PHP + SQLite**, tanpa framework, sehingga ringan & mudah dipasang di hosting manapun.

## ✨ Fitur
- Login pengguna (Admin / Staff)
- Manajemen Buku (CRUD, stok, lokasi)
- Manajemen Anggota (CRUD)
- Peminjaman & Pengembalian (stok otomatis)
- Denda otomatis (default Rp1.000/hari)
- Laporan pinjaman aktif, terlambat, dan riwayat
- Database SQLite (tanpa MySQL)
- Tampilan simpel, dark mode, responsif

## 🚀 Instalasi
1. Clone repo:
   ```bash
   git clone https://github.com/sttskripturaperpustakaan/stt-skriptura-perpustakaan.git
   cd stt-skriptura-perpustakaan
   ```

2. Pindahkan folder ini ke web server kamu (mis. `htdocs/` atau root hosting).

3. Pastikan folder `app/` bisa ditulis oleh PHP (chmod 775 atau 777 jika perlu).

4. Akses melalui browser:
   ```
   http://localhost/stt-skriptura-perpustakaan/public/
   ```

5. Login dengan akun default:
   - **Username**: `admin`
   - **Password**: `admin123`  

   Segera ganti password di menu **Pengguna**.

## 📂 Struktur Direktori
```
public/   -> file aplikasi (UI + halaman utama)
app/      -> config, database, helper, schema
assets/   -> CSS dan resource lainnya
```

## 📝 Lisensi
MIT License – silakan gunakan, modifikasi, dan distribusikan.
