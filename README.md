# LOAN MANAGEMENT SYSTEM
1. install node which will install npm too
2. install php
3. install composer
4. install laravel globally
* composer global require laravel/installer
* then the message appears...
* Changing directory to C:\Users\USER\AppData\Roaming\Composer\vendor\bin

5. Create laravel project:
<b>Step 1: Install Laravel</b>
Open terminal and run the following command to install a fresh Laravel project:
* composer create-project laravel/laravel project-name

Or, if you have installed the Laravel Installer as a global composer dependency, then run the following command:
* laravel new project-name

<b>Step 2: Install Laravel UI</b>
While Laravel does not dictate which JavaScript or CSS pre-processors you use, it does provide a basic starting point using Bootstrap, React, and Vue that will be helpful for many applications. By default, Laravel uses NPM to install both of these frontend packages.
* composer require laravel/ui

<b>Step 3: Install React or Install React with Auth</b>
Once the Laravel/UI package has been installed, you may install the frontend scaffolding using the UI Artisan command:
* php artisan ui react

Or, if you would like to install login and registration of particular javascript frameworks or libraries, you need to run the following command:
* php artisan ui react --auth
* || php artisan ui vue --auth 
* || php artisan ui bootstrap --auth

<b>Step 4: Install the required package dependency</b>
To install react package dependency in your project, run the below command into your terminal.
* npm install
and
* npm run dev

<b>Step 5: Test in localhost</b>

8. create mysql db
9. php artisan migrate
10. Happy coding

# ****** Happy coding ******
