## Run Locally

### 1. Clone repo

```
$ git clone git@github.com/kamilkahar90/test-laravelapp.git
$ cd test-laravelapp
```

### 2. Setup Environment

-   Download XAMPP/WAMP, Composer, Node.js

```
$ composer global require laravel/installer

```

### 3. Install Dependencies

```
$ composer install
$ npm install
$ npm run dev
```

### 4. Generate database

-   Create database name : test_laravelapp

```
$ php artisan migrate
```

### 5. Run Project

```
$ php artisan serve
```
