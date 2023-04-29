# LOAN MANAGEMENT SYSTEM
1. install node which will install npm too
2. install php
3. install composer
4. install laravel globally
* composer global require laravel/installer
* then the message appears...
* Changing directory to C:\Users\USER\AppData\Roaming\Composer\vendor\bin
5. create laravel project using
* laravel new project-name
6. composer require laravel/ui --dev
    <i>Note: Laravel UI Composer package is a new first-party package that extracts the UI portion of a Laravel project ( frontend scaffolding typically provided with previous releases of Laravel ) into a separate laravel/ui package. The separate package enables the Laravel team to update, develop and version UI scaffolding package separately from the primary framework and the main Laravel codebase.</i>

7.   php artisan ui bootstrap --auth 
* || php artisan ui vue --auth 
* || php artisan ui react --auth
* || php artisan ui bootstrap
* || then run [npm install && npm run dev] to compile your fresh  scaffolding.
* <i>login and register links will appear on home page</i>
8. create mysql db
9. php artisan migrate
10. Happy coding

