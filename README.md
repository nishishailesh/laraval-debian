# laravel-debian
Basic Steps to make laravel working in linux\
Tested in Debian 11

    apt install composer npm
    composer create-project laravel/laravel
    pico /etc/apache2/conf-enabled/. add alias line
    service apache2 restart
    chown www-data:www-data storage -R
    To start bootstrap
        composer require laravel/ui
        php artisan ui bootstrap
        php artisan ui bootstrap --auth
        npm install
        npm run dev
        Run above command again if error

    in head add following lines
    <link rel="stylesheet" href="css/app.css">
    <script src="js/app.js"></script>


