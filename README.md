

# Laravel Starter
**Laravel Starter** is a Laravel 7.x based simple starter project. It can be used to build all type of applications. Most of the commonly needed features like Authentication, Application Backend, Backup, Logviewer are available here. It is modular, so you can use this project as a base and build your own modules. You can use the same module in any of the Laravel starter based projects. New features and functionalities are being added on a regular basis.

Please let me know your feedback and comments.


# Demo
Check the following demo project. It is just a straight installation of the project without any modification.

Demo URL: http://laravel.nasirkhn.com

```
User: super@admin.com
Pass: secret

User: user@user.com
Pass: secret

```

# Custom Commands

We have created a number of custom commands for the project. The commands are listed below with a brief about the use of it.

## Clear All Cache

`composer clear-all`

this is a shortcut command clear all cache including config, route and more

## Code Style Fix

`composer fix-cs`

apply the code style fix by this command.


# Features

The `Laravel Starter` comes with a number of features which are the most common in almost all the applications. It is a template project which means it is intended to build in a way that it can be used for other projects.

It is a modular application, and a number of modules are installed by default. It will be helpful to use it as a base for the future applications.

* Admin feature and public views are completely separated as `Backend` and `Frontend` namespace.
* Major feature are developed as `Modules`. Module like Posts, Comments, Tags are separated from the core features like User, Role, Permission


## Core Features

* User Authentication
* Social Login
  * Google
  * Facebook
  * Github
  * Build in a way adding more is much easy now
* User Profile with Avatar
  * Separate User Profile table
* Role-Permissions for Users
* Dynamic Menu System
* Language Switcher
* Localization enable across the porject
* Backend Theme
  * Bootstrap 4, CoreUI
  * Fontawesome 5
* Frontend Theme
  * Bootstrap 4, Now UI Kit
  * Fontawesome 5
* Article Module
  * Posts
  * Categories
  * Tags
  * Comments
  * wysiwyg editor
  * File browser
* Application Settings
* External Libraries
  * Bootstrap 4
  * Fontawesome 5
  * CoreUI
  * Now UI Kit
  * Datatables
  * Select2
  * Date Time Picker
* Backup (Source, Files, Database as Zip)
* Log Viewer
* Newsletter
* Notification
  * Dashboard and details view
* RSS Feed


# User Guide

## Installation

Follow the steps mentioned below to install and run the project.

1. Clone or download the repository
2. Go to the project directory and run `composer install`
3. Create `.env` file by copying the `.env.example`. You may use the command to do that `cp .env.example .env`
4. Update the database name and credentials in `.env` file
5. Run the command `php artisan migrate --seed`
6. Link storage directory: `php artisan storage:link`
7. You may create a virtualhost entry to access the application or run `php artisan serve` from the project root and visit `http://127.0.0.1:8000`

*After creating the new permissions use the following commands to update cashed permissions.*

`php artisan cache:forget spatie.permission.cache`


## Icons
FontAwesome & CoreUI Icons, two different font icon library is installed for the Backend theme and only FontAwesome for the Frontend. For both of the cases we used the free version. You may install the pro version separately for your own project.

* **FontAwesome** - https://fontawesome.com/icons?d=gallery&m=free
* **CoreUI Icons** - https://icons.coreui.io/icons/


# Screenshots

__Home Page__

![Laravel Starter Home](https://user-images.githubusercontent.com/396987/67085331-74606500-f1c0-11e9-8187-99fe49134075.png)

__Login Page__

![Laravel Starter Login](https://user-images.githubusercontent.com/396987/67085329-74606500-f1c0-11e9-8669-3638e30cb449.png)

__Backend Dashboard__

![Backend Dashboard](https://user-images.githubusercontent.com/396987/88489727-f3889200-cfb7-11ea-819f-dc9a52bc8d82.jpg)

---

![List-Posts-Laravel-Starter](https://user-images.githubusercontent.com/396987/88519250-a0dcc380-d013-11ea-9dc5-9d731af611f1.jpg)

---

![Edit-Posts-Laravel-Starter](https://user-images.githubusercontent.com/396987/88519360-d1bcf880-d013-11ea-9f6c-b5d33912057f.jpg)

