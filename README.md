# Konsep Web
Web untuk menyimpan data data lagu untuk Radio

# Fitur Web
- Autentifikasi, Register, Login, Logout
- Halaman Dashboard
- Halaman Song (index untuk list lagu
- Halaman Profile

# Multi User
## Admin
- Dapat menambahkan list
- Dapat melakukan edit pada list
- Dapat melakukan update pada list
- Dapat menghapus data pada list

## User
- Dapat melihat data pada list
- Dapat melihat detail sebuah data

# Akun Default Untuk Pengujian
## Admin
- email: admin@example.com
- password: 12345

## User
- email: user@example.com
- password: 12345

**Admin** dan **User** dapat Login di URL `/login`. URL tersebut juga bisa di akses dari `welcome.blade.php` di pojok kiri atas
**User** dapat menambahkan akun baru melalui URL `/register`. Akun yang di buat di halaman ini akan selalu menjadi User, karena Akun **Admin** hanya ada satu

# Teknologi yang Digunakan
- [Laravel 10](https://laravel.com/)
- [Bootstrap 5.3](https://getbootstrap.com/)

# Persyaratan Instalasi
- PHP 8.1.6 atau lebih
- Web Browser
- 


