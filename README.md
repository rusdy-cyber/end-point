<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## End Point

end point/api yang di rancang menggunakan framework laravel 9

`versi`
- laravel 9

## alokasi
`masukkan file ke htdocs di dalam file xampp`



## instalasi
- buat database di xampp atau lainnya
- masukkan nama db ke env
- jalnkan
```
php artisan migrate
php artisan db:seed --class=LoginSeeder
```
- jika laravel eror key
```
buat file laravel baru ambil file vendor dan ganti ke file vendor project ini
```
## setting post man
`unduh post man`

login menggunakan gmail
```
https://www.postman.com/downloads/
```
#### salin link
```
http://127.0.0.1/[nama file di htdocs]/public/api
```
masuk ke post man dan pilih method post masukkan link di atas
