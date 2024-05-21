# Project Management

<p align="center">
    <a href="https://laravel.com"><img alt="Laravel v9.x" src="https://img.shields.io/badge/Laravel-v9.x-FF2D20?style=for-the-badge&logo=laravel"></a>
    <a href="https://laravel-livewire.com"><img alt="Livewire v2.x" src="https://img.shields.io/badge/Livewire-v2.x-FB70A9?style=for-the-badge"></a>
    <a href="https://filamentphp.com/"><img alt="Filament v2.x" src="https://img.shields.io/badge/Filament-v2.x-e9b228?style=for-the-badge"></a>
    <a href="https://php.net"><img alt="PHP 8.0" src="https://img.shields.io/badge/PHP-8.0-777BB4?style=for-the-badge&logo=php"></a>
    <br/>
</p>

# Description

A task tracking system to streamline operations and enhance productivity.

# Setup Process

## Dependencies

To install the backend dependencies, run the following command:
```
composer install
```
To install the backend dependencies, run the following command:
```
composer install
```
## Configuration

Copy .env.example file to .env file then configure any necessary elements such as db_database, etc. <br>
<br>
After configuring the elements, execute the command to generate the application key:
```
php artisan key:generate
```

## Database

1. Create a database on the same server. <br>
2. Run database migrations:
```
php artisan migrate
```

3. Run database seeder:
```
php artisan db:seed
```

## Assets

- Generate assets for production: 
```
npm run build
```
- Generate assets for development: 
```
npm run dev
```
or
```
vite
```

## Access

Finally, to access the platform, execute the code:
```
php artisan serve
```



