This API was built using *Laravel Sail*, Laravel's default Docker development enviroment.

## Setup
**1.** Clone the repository locally.

**2.** Run following command inside the main repo folder
>composer install
    
**3.** Create your .env file and run the command
>php artisan key:generate
    
**4.** Run following command to run the .yml file. _It might take a while on the first run, so I suggest you grab a cup of coffee._
>docker-compose up


If everything went as expected you should be able to access the project in your browser at http://localhost
    
