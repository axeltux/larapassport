# Creacion de API REST con Laravel 5.8 y Passport

## Instalar el paquete: 

composer require laravel/passport

// config/app.php

'providers' =>[
 Laravel\Passport\PassportServiceProvider::class,
 ],
 
 // app/providers/AppServiceProvider.php
 
 use Illuminate\Support\Facades\Schema;
 
 public function boot() { 
    Schema::defaultStringLength(191); 
 }

## Ejecutar:
php artisan migrate
php artisan passport:install
