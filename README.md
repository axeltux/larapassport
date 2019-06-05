# Creacion de API REST con Laravel 5.8 y Passport

## Instalar el paquete: 

composer require laravel/passport

// config/app.php

'providers' =>[<br>
    Laravel\Passport\PassportServiceProvider::class,<br>
 ],
 
 // app/providers/AppServiceProvider.php
 
 use Illuminate\Support\Facades\Schema;
 
 public function boot() { 
    Schema::defaultStringLength(191); 
 }

## Ejecutar:
php artisan migrate<br>
php artisan passport:install
