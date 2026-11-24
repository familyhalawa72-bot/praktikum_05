Praktikum Pertemuan 5 - Database Inventori Laboratorium
Nama  : Ingat Family Halawa
NIM   : 25110038
Kelas : TK A PAGI
Server database : MariaDB/MySQL versi 10.4.32-MariaDB
phpMyAdmin      : versi utf8mb4_unicode_ci
Nama database   : db_inventori_lab 

Cara memulihkan database:
1. Jalankan Apache dan MySQL di XAMPP.
2. Buka localhost/phpmyadmin, buat database dengan collation utf8mb4_unicode_ci.
3. Pilih database tersebut > tab Import > pilih skema_inventori_lab.sql > Import.

Isi: 5 tabel (kategori, barang, pengguna, peminjaman, detail_peminjaman), 4 foreign key, 3 check constraint.