# laravel livewire practice

## install Laravel
```
```

## install livewire
```
composer require livewire/livewire
```

### env setting for sqlite3
```
#DB_CONNECTION=mysql
#DB_HOST=127.0.0.1
#DB_PORT=3306
#DB_DATABASE=livewire
#DB_USERNAME=root
#DB_PASSWORD=

DB_CONNECTION=sqlite
```


## generate a new Livewire component
```
php artisan make:livewire counter
```

## install sqllite
```
touch database/database.sqlite
```

## migration
```
php artisan migrate
```
