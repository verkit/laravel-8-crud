# Laravel 8 CRUD
Tahapan instalasi

1. install dependency
```composer install```

2. salin file .env
``` cp .env.example .env```

3. Generate key
``` php artisan key:gen ```

4. Buka file .env dan ubah konfigurasi databasenya
```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=secret
```

5. Jalankan migrasi database
```php artisan migrate```

6. Jalankan laravelnya
```php artisan serve```

7. Buka 
```localhost:8000```
