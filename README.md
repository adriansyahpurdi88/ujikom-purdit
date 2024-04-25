
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
![login](https://github.com/adriansyahpurdi88/ujikom-purdit/assets/167829340/7a827dd9-9be8-4d55-aac7-da30c447db27)

![register](https://github.com/adriansyahpurdi88/ujikom-purdit/assets/167829340/a82373f5-1651-4c95-ae4f-f311f1996645)

![home](https://github.com/adriansyahpurdi88/ujikom-purdit/assets/167829340/fc8daff5-8953-4318-bfa5-8b6edf4ab6ef)

![buat album](https://github.com/adriansyahpurdi88/ujikom-purdit/assets/167829340/f84547dd-1960-4620-8b07-3242c25b60dd)

![upload foto](https://github.com/adriansyahpurdi88/ujikom-purdit/assets/167829340/0b21d08e-7a78-4322-8b08-facc57dc7b34)

![foto](https://github.com/adriansyahpurdi88/ujikom-purdit/assets/167829340/5bd165e7-a373-4288-a508-9e5671c4ba5b)



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
