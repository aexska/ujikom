
##  Konsep Dari Web Yang Saya Buat

Website yang saya buat ini merupakan sebuah Aplikasi kasir yang simple

## Fitur Yang Tersedia

-   Dashboard
    -   Jumlah Pembelian
    -   Penghasilan
    -   Penghasilan Harian
    -   Jumlah Pembeli
-   Authentication
    -   Register
    -   Login

    -   User
        -   Pengguna yang dapat dikelola 
        -   Produk yang dapat dikelola
        -   Menambah,mengedit dan menghapus Produk
        -   Melihat data penjualan
        -   Menjual Produk
        -   Membeli Produk
        -   Membatalkan Pembelian Produk
        -   Membuat Daftar Pembeli
        -   Generate Laporan (EXCEL, PDF)
        -   Login
        -   Logout

## Akun Default Untuk Pengujian

    -   Email : admin@gmail.com
    -   Password : admin123

## ERD & Relasi antar tabel

![ERD](https://github.com/user-attachments/assets/9f5ca369-f168-4217-aed2-2f861beea596)

## UML Diagram Use Case

![UML](https://github.com/user-attachments/assets/479e9da1-a248-470c-8261-79769aa4e409)

## Teknologi Yang Digunakan

-   <a href="https://laravel.com/">Laravel 11</a>
-   <a href="https://getbootstrap.com/">Boostrap 5</a>

## Persyaratan Untuk Melakukan Instalasi

-   PHP 8.2.0 & Web Server (Apache)
-   Database (MariaDB)
-   Web Browser (Chrome, atau firefox)

## Instalasi 

1. Clone Repositori

```bash
git clone 
composer install
cp .env.example .env
```

2. Konfigurasi Database pada file `.env`

```conf
APP_DEBUG=true
DB_DATABASE=database-anda
DB_USERNAME=nama-pengguna-anda
DB_PASSWORD=kata-sandi-anda
```

3. Melakukan Migrasi dan menyambungkan storage

```bash
php artisan key:generate
php artisan storage:link
php artisan migrate --seed
```

4. Mulai Situs Web

```bash
php artisan serve
```


