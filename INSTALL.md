## Shell
```shell script
git clone git@github.com:authanram/laravel-websockets.git laravel-websockets
cd laravel-websockets
composer install
php artisan key:generate
npm install && npm run dev
```

## `.env`
```dotenv
# db
DB_DATABASE=dev--laravel-websockets
DB_USERNAME=dev
DB_PASSWORD=dev

# pusher (equals counterpart)
PUSHER_APP_ID=dev
PUSHER_APP_KEY=dev
PUSHER_APP_SECRET=dev
PUSHER_APP_CLUSTER=mt1
``` 

## Migrations
```shell script
php artisan migrate
```

## Serve
```shell script
php artisan websockets:serve
```

## Dashboard
http://laravel-websockets.localhost (can/will vary)

## Docs
- https://beyondco.de/docs/laravel-websockets/getting-started/installation
- https://laravel.com/docs/8.x/broadcasting#installing-laravel-echo
