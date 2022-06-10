

<!-- ![](Assets/) -->


## Install PHP

Download dan Extract file untuk instalasi PHP

File dapat di download di sini https://www.php.net/downloads.php

<img src="https://github.com/bryanpratama/Pemrograman-Integratif/blob/main/instalasi-laravel/Assets/web_php.png" width="" height="350">

Copy di lokasi `C:\Program Files` Pada file `php.ini development` copy dan ubah menjadi `php.ini` buka dengan text editor dan ubah beberapa line seperti di bawah, lalu simpan

![](Assets/change-php.ini1.png)
<img src="https://github.com/bryanpratama/Pemrograman-Integratif/blob/main/instalasi-laravel/Assets/change-php.ini2.png" width="" height="350">


Buka `Edit The System Environment Variables` klik Environment Variables

<img src="https://github.com/bryanpratama/Pemrograman-Integratif/blob/main/instalasi-laravel/Assets/env.png" width="" height="350">

Pilih variabel path untuk menambahkan alamat dari file php, kemudian pilih ok.

Pada `System variables` pilih `Path` tambahkan alamat dari file PHP, kemudian ok

<img src="https://github.com/bryanpratama/Pemrograman-Integratif/blob/main/instalasi-laravel/Assets/sys-path.png" width="" height="350">

Buka Terminal dan gunakan `php –v` untuk mengecek sudah terinstall atau belum

<!-- <img src="https://github.com/bryanpratama/Pemrograman-Integratif/blob/main/instalasi-laravel/Assets/php-v.png" width="" height="350"> -->
![](Assets/php-v.png)

## Install Composer

Download dan Install Composer https://getcomposer.org/download/

<!-- Revisi disini -->

<img src="https://github.com/bryanpratama/Pemrograman-Integratif/blob/main/instalasi-laravel/Assets/download-composer.png" width="" height="350">

<!-- Revisi disini -->

Buka Terminal dan gunakan `composer` untuk mengecek sudah terinstall atau belum

<img src="https://github.com/bryanpratama/Pemrograman-Integratif/blob/main/instalasi-laravel/Assets/instal-composer.png" width="" height="350">

## INSTALL LARAVEL VIA COMPOSER

Bikin file baru kemudian gunakan `composer create-project laravel/laravel` untuk create project, pada akhir code tambahkan nama file ex:`composer create-project laravel/laravel test`

<img src="https://github.com/bryanpratama/Pemrograman-Integratif/blob/main/instalasi-laravel/Assets/create-project.png" width="" height="350">

Buka file dengan menggunakan code editor, disini saya menggunakan vs code

<!-- <img src="https://github.com/bryanpratama/Pemrograman-Integratif/blob/main/instalasi-laravel/Assets/open_file_test.png" width="" height="350"> -->
![](Assets/open_file_test.png)

Pada terminal gunakan `php artisan serve` untuk menjalankan, kemudian CTRL+click untuk membuka link

<img src="https://github.com/bryanpratama/Pemrograman-Integratif/blob/main/instalasi-laravel/Assets/deploy_laravel.png" width="" height="350">

Laravel siap digunakan

<img src="https://github.com/bryanpratama/Pemrograman-Integratif/blob/main/instalasi-laravel/Assets/local_laravel.png" width="" height="350">








