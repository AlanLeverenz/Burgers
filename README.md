# Burgers

## What the app does

    This app lists a menu of burgers stored in a MySQL database. The user has the options of devouring burgers on the menu, or adding a new burger to the menu, with toppings.

## How to run the app

    Go to the "Burgers" Heroku deployment webpage (https://git.heroku.com/vast-mesa-58378.git). The interface is a simple listing of burgers on the left side. In the middle are buttons to devour the named burger.

    Burger on the menu:
    https://github.com/alanleverenz/Burgers/blob/master/public/images/burger-to-eat.png

    After clicking on the "Eat It ... " button, the burger is removed from menu of burgers and moved to the right side in a Readonly state.

    Devoured burger:
    https://github.com/alanleverenz/Burgers/blob/master/public/images/burger-devoured.png

    To add a burger to the menu, use the entry form at the bottom of the page. Click the Submit button to add the entered burger and its toppings.

    Add burger form:
    https://github.com/alanleverenz/Burgers/blob/master/public/images/add-salmon-burger.png

## Technologies

#### NPM Modules

    This app uses NodeJS and the following NPM modules:
    * body-parser
    * express
    * express-handlebars
    * method-override
    * mysql

#### Author

    Alan Leverenz

JAWSDB INFO

Connection String:
mysql://biu9e7wv25a0mfgv:d9oatblv6stuy43l@q68u8b2buodpme2n.cbetxkdyhwsb.us-east-1.rds.amazonaws.com:3306/n5q97jqdo4j814xe

Host: q68u8b2buodpme2n.cbetxkdyhwsb.us-east-1.rds.amazonaws.com

Username: biu9e7wv25a0mfgv

Password: d9oatblv6stuy43l

Port: 3306

Database: n5q97jqdo4j814xe


