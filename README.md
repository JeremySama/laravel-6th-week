# HOW TO SETUP THIS PROJECT

-   `Use your github account to fork this repository or download as zip`
-   `Run composer install or run composer install --ignore-platform-req=ext-gd if you have problems installing composer`
-   `Change the env.example to env but if you have an existing env you can skip this part`
-   `Create the environment and fill it with the needed data, such as the database and mailtrap, for example`
-   `Run php artisan key:generate`
-   `Run php artisan serve`
-   `Run php artisan optimize: <-(shortcut) or php artisan optimize:clear to reset everything in Laravel`
-   `To execute the project accurately, always use php artisan optimize: or php artisan optimize:clear and run php artisan serve after`
-   `To ensure that your routes are functioning properly, run php artisan route:list`
