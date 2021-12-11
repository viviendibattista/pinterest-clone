## Pinterest clone

I coded this Pinterest clone app to learn Symfony using Twig, Bootstrap, webpack encore, etc ...
This app allows you to : 

- Register / create an account
- Log in 
- Create a Pin
- Edit / Delete a Pin
- ...

## How the run the app

After cloning the project run and edit the .env file to connect your db run :
```
$ composer install
$ npm install
$ php bin/console doctrine:migrations:migrate
```

The app was developped with PHP 7.4, Apache 2.4 and MySQL 7.4
:) 