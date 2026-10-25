# Tiket Konser (Laravel + Breeze + Bootstrap 5)

Berkas di folder ini adalah lapisan aplikasi. Salin ke atas project Laravel baru (struktur bawaan tetap utuh).

    composer create-project laravel/laravel tiket-konser
    cd tiket-konser
    composer require laravel/breeze --dev
    php artisan breeze:install blade
    # salin isi folder ini ke root project (timpa routes/web.php & DatabaseSeeder.php)
    php artisan storage:link
    php artisan migrate --seed
    npm install && npm run build   # untuk halaman login/register Breeze
    php artisan serve

Login demo: admin@example.com / password
