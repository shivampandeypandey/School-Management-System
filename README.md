## School Management System(SMS) in Laravel
-------------------------------------------

This Project is a simple role and permission based school management system using Laravel 5.8.

### Installation
----------------
01. `git clone https://github.com/shivampandeypandey/School-Management-System.git
02. `cd laravel-school-management-system`
03. `composer install`
04. `npm install`
05. `cp .env.example .env` or `copy .env.example .env`
06. `php artisan key:generate`

**  `Review .env file for the the App and Database Configurations`

07. `Create Database in the server whose configurations you have set in .env file`
08. `php artisan migrate`
10. `php artisan db:seed`
10. `php artisan serve`

### Extra Packages and Dependencies
-----------------------------------
01. `spatie/laravel-permission`

### Resources & Reference File
------------------------------
01. `Sample Database File` => `sms1.sql`
02. `Web Portal & Project Snapshots` => `Projects_Screenshots.rar`

### Testing & Credentials
-------------------------
The application can be tested using below credentials which are seeded in the database :

-   Admin   -> email = admin@demo.com, password = 12345678      & Role: Admin
-   Teacher -> email = teacher@demo.com, password = 12345678    & Role: Teacher
-   Parent  -> email = parent@demo.com, password = 12345678     & Role: Parent
-   Student -> email = student@demo.com, password = 12345678    & Role: Student
