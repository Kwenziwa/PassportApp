# PassportApp
Starter Admin Laravel
# ![Laravel Example App](https://laravel.com/img/logotype.min.svg)


# Getting started

## Installation

Please check the official laravel installation guide for server requirements before you start. [Official Documentation](https://laravel.com/docs/5.4/installation#installation)


Clone the repository

    git clone https://github.com/Kwenziwa/PassportApp.git

Switch to the repo folder

    cd PassportApp

Install all the dependencies using composer

    composer install
    
Install all the dependencies using composer

    npm install

Copy the example env file and make the required configuration changes in the .env file

    cp .env.example .env

Generate a new application key

    php artisan key:generate


Run the database migrations (**Set the database connection in .env before migrating**)

    php artisan migrate

Start the local development server

    php artisan serve

You can now access the server at http://localhost:8000

**TL;DR command list**

    git clone git@github.com:gothinkster/laravel-realworld-example-app.git
    cd laravel-realworld-example-app
    composer install
    npm install
    cp .env.example .env
    php artisan key:generate
   
    
**Make sure you set the correct database connection information before running the migrations** [Environment variables](#environment-variables)

    php artisan migrate
    php artisan serve
