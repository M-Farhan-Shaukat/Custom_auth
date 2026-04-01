##clone repository 
git clone https://github.com/M-Farhan-Shaukat/Custom_auth.git
## copy .env.example to .env
## composer install
    versions PHP 8.2 >
    laravel 12
create Data base update credentials in .env file 

run php artisan migrate 
run php artisan db:seed

run php artisan serve

redirect Admin Role
http://127.0.0.1:8000/admin/login
email: admin@gmail.com
password : Temp123!

redirect User Role
http://127.0.0.1:8000/login
email: user@gmail.com
password : Temp123!
