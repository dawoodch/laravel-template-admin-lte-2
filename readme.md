

## Step to install bootstap UI:AUTH

- composer require laravel/ui
- php artisan ui bootstrap
- php artisan ui bootstrap --auth
    OR  - php artisan ui bootstrap
        - php artisan ui:auth
- npm install && npm run dev

## Step to install laravellte

- reference https://github.com/jeroennoten/Laravel-AdminLTE
- composer require jeroennoten/laravel-adminlte
- php artisan adminlte:install
- php artisan vendor:publish --provider="JeroenNoten\LaravelAdminLte\ServiceProvider" --tag=views
- 