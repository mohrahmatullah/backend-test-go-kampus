# Requirements
```
	PHP 8.1.0
	Laravel 9.0
	Mysql 5.7.36
```


# Installation

1. Clone this repo

```
git clone https://github.com/mohrahmatullah/backend-test-go-kampus.git
```


2. Setup

```
$ cd backend-test-go-kampus
$ composer install
$ php artisan key:generate
$ copy .env.example .env

put database credentials in .env file
```

3. Migrate and insert records

```
$ php artisan migrate:fresh --seed
```

4. Storage Link

```
$ php artisan storage:link
```

5. For frontend/mobile

```
$ php artisan passport:install
```

```
Export File Insomnia
- Insomnia/insomnia..

```

6. login
```
email = admin@admin.com
password = password

```