# laravel-lang-id
Terjemahan dalam Bahasa Indonesia untuk pesan validasi, autentikasi, pagination, dan password <br />

Versi laravel yang digunakan: 11.42.1

1. Buat folder `lang` atau bisa dengan
```
php artisan lang:publish
```
2. Download folder `id` di repository ini
3. Pindahkan `id` ke `lang`
4. Untuk mengubah bahasa, bisa dengan mengedit langung file `config/app.php`
```
'locale' => 'id'
```
atau edit di .env
```
APP_LOCALE=id
```
kemudian edit di `config/app.php`
```
'locale' => env('APP_LOCALE', 'id')
```

