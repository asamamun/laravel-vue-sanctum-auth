# laravel-vue-demo

Todo app with Authentication using REST API + Laravel Sanctum.

Read more about the project in details from this article https://blog.logrocket.com/create-single-page-app-laravel-and-vue/

## Setup 
- Make sure you have PHP8 & MySQL installed on your machine.
- Copy `.env.example` to `.env` and change the Database information to that of yours.
- Open your terminal/cmd, then run `composer install` to install all PHP related packages, then `npm install` for JS related packages.
- Run `php artisan migrate`(this create the tables required by the app in your DB) and `php artisan db:seed`(this insert dummy data into the table created.)
- Then run `npm run dev`(this compiles & builds our js), open another terminal/cmd then run `php artisan serve`(This starts laravel server to run the app)
- Finally, goto the browser and enter the address on your laravel server or type: http://localhost:8000
