## Running Laravel image gallery API and React.js project

#### Install Packages

```
composer install
```

#### Copy .env file

```
cp .env.example .env
```

#### Set Database Detail

```
DB_CONNECTION=mysql
DB_HOST=127.0.0.1
DB_PORT=3306
DB_DATABASE=
DB_USERNAME=
DB_PASSWORD=
```

### Migrate database using the following command
```
php artisan migrate
```

#### Start Laravel Project

```
php artisan serve
```
