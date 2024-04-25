
# Galery

## Tentang Website


## Fitur

Untuk Fitur masih minim:
- sign up
- log in
- log out
- add poto
- add album
- add comment
- delete comment
- dll

## Tampilan Website



## ERD, Relasi dan UML Use Case

- ERD
![ERD](https://github.com/adriansyahpurdi88/ujikom-purdit/assets/167829340/9f9cb7af-b908-4d22-90cb-3f14e45c0032)


- Relasi
 ![ERD1](https://github.com/adriansyahpurdi88/ujikom-purdit/assets/167829340/ce91aa09-02ca-4d65-a2f6-49848579c3cf)


- UML
![use Case1](https://github.com/adriansyahpurdi88/ujikom-purdit/assets/167829340/44931ee7-7bdf-4673-9247-282c5116682a)



## Prasyaratan

- PHP 8.2.8 & Web Server (Apache, Lighttpd, atau Nginx)
- Database (MariaDB dengan v11.0.3 atau PostgreSQL)
- Web Browser (Firefox, Safari, Opera, dll)

## Instalasi
1. Clone Repository
```
```

2. Install Composer
```
composer install
```
atau
```
composer update
```

3. Ganti .Env.example menjadi 
```
.env
```

4. Setting database di .env
```
DB_PORT=3306
DB_DATABASE=laravel
DB_USERNAME=root
DB_PASSWORD=
```

5. Generate key
```
php artisan key:generate
```

6. Jalankan migrate dan seeder
```
php artisan migrate --seed
```

7. Buat Storage Link
```
php artisan storage:link
```

8. jangan lupa menginstall NPM
```
npm install
```
lalu jalankan
```
npm run dev
```

8. Jalankan Serve
```
php artisan serve
```
