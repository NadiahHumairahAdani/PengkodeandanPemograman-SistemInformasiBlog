## PengkodeanDanPemrgogaman-Sistem-Informasi-Blog
Source Code Aplikasi Pengiriman Blog sederhana berbasis Website dengan PHP & MYSQL

## Tugas Pengkodean dan Pemrograman
Nama : Nadiah Humairah Adani

NIM : 12030122140279

- Web Pos Sistem Informasi Blog dari (https://github.com/codewithdary/laravel-8-complete-blog)

## Tampilan Sistem Lama
- Dashboard
![image](https://github.com/NadiahHumairahAdani/PengkodeandanPemograman-SistemInformasiBlog/blob/main/DASHBOARD%20LAMA.png)
- Home
![image](https://github.com/NadiahHumairahAdani/PengkodeandanPemograman-SistemInformasiBlog/blob/main/HOME%20LAMA.png)
- Home
![image](https://github.com/NadiahHumairahAdani/PengkodeandanPemograman-SistemInformasiBlog/blob/main/HOME%20LAMA.png)
- Create Post
![image](https://github.com/NadiahHumairahAdani/PengkodeandanPemograman-SistemInformasiBlog/blob/main/CREATE%20BLOG%20LAMA.png)

## Tampilan Sistem Baru
- Dashboard

- Home

- Home

- Home

- Create Post

## Laravel 8 Complete Blog

This repository is linked to [this youtube video](https://www.youtube.com/watch?v=HKJDLXsTr8A&t=4710s) where I show you how to create a complete blog in Laravel 8 using best practices.

•	Author: Code With Dary <br>
•	Twitter: [@codewithdary](https://twitter.com/codewithdary) <br>
•	Instagram: [@codewithdary](https://www.instagram.com/codewithdary/) <br>

## Requirements
•	PHP 7.3 or higher <br>
•	Node 12.13.0 or higher <br>

## Usage <br>
Setting up your development environment on your local machine: <br>
```
git clone git@github.com:codewithdary/laravel-8-complete-blog.git
cd laravel-8-complete-blog
cp .env.example .env
composer install
php artisan key:generate
php artisan cache:clear && php artisan config:clear
php artisan serve
```

## Before starting <br>
Create a database <br>
```
mysql
create database laravelblog;
exit;
```

Setup your database credentials in the .env file <br>
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravelblog
DB_USERNAME={USERNAME}
DB_PASSWORD={PASSWORD}
```

Migrate the tables
```
php artisan migrate
```

## Contributing
Do not hesitate to contribute to the project by adapting or adding features ! Bug reports or pull requests are welcome.
