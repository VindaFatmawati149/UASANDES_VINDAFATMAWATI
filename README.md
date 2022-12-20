<p align="center">
<img src="https://raw.githubusercontent.com/jhonarendra/prognet8/master/public/images/logo.png" />
<img src="https://raw.githubusercontent.com/jhonarendra/prognet8/master/public/images/logo-text.png" />
</p>
<p align="center">Website restoran dengan framework Laravel 5.6</p>

## Installation

Laravel 5.6 menggunakan PHP versi 7.0. Jadi kalau belum update dulu. Lalu pastikan sudah menginstal composer.

1. Clone repository, dengan perintah git clone seperti ini

```
git clone https://github.com/VindaFatmawati149/UASANDES_VINDAFATMAWATI.git
```

2. Pada cmd, pindah ke folder prognet8 contohnya

```
cd c:/xampp/htdocs/website-restoran-laravel
```

lalu instal composer

```
composer install
```

3. Edit pengaturan database di file `.env`, juga masukkan perintah ini untuk mengisi `APP_KEY`

```
php artisan key:generate
```

4. Migrasi tabelnya ke database dengan perintah

```
php artisan migrate
```

Lalu masukkan perintah berikut untuk insert beberapa data ke database

```
php artisan db:seed
```

5. Siap dijalankan...

<p align="center">Apabila memerlukan database sqldump, file bernama prognet8.sql</p>

## Contributing

1. Jika sudah di clone, pull dulu repository ini dengan perintah berikut, supaya dapat editan terbaru

```
git pull origin master
```

2. Edit projek sesuai keinginan
3. Kalau sudah diedit, push kembali seperti perintah berikut

```
git add .
```

```
git commit -m "pesan"
```

```
git push origin master
```
