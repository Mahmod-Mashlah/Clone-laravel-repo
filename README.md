// 1 : run the command :


git clone (url like : https://github.com/yourusername/your-laravel-project.git)

    or download it as zip file .
    
// 2

open the project in vscode
    or use terminal command : cd (your-laravel-project)

// 3 run the command :  
    
    composer install

// 4 run the command :

    cp .env.example .env

    ( copy .env.example and paste it as .env ) 

// 5 database configuration [ also create a database on phpMyAdmin ]:

    DB_DATABASE=(db-name)
    DB_USERNAME=(root)
    DB_PASSWORD=(paswword)

// 6 run the command :

    php artisan key:generate

// 7 run the command :

    php artisan migrate:fresh --seed

// 8 run the command :

    php artisan serve

