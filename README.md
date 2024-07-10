#PHP 8.1 version
#DB Name: - Herody
#Project Name:-  Herody
#Local Check:- http://127.0.0.1:8000


Flow: 
1. install laravel project
   composer create-project laravel/laravel herody
2. update composer
   composer update
3. create table using migration and update user table for unique
   php artisan migrate
   php artisan make:migration add_unique_users_table --table=users
4. Use to intall Boostrap and npm for design
   composer require laravel/ui
   
   php artisan ui bootstrap

   https://www.codewithharry.com/blogpost/solving-npm-not-recognized-error-windows/ -- node install
   
   npm install && npm run dev
5. create laravel registration and login using form validation and insert into db
6. use login and do login
7. once login,it will redirect to home screen,with authentication


