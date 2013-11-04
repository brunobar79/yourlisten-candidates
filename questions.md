## Personal details

Name: Krešimir Franin

Country: Croatia

Hourly Rate: 12-13$

Timezone: CET (GMT+1)

Skype Id: metgale
 
## Availability

Are you able to work from 3PM to 7PM (GMT -2) ? In case you aren't, what's your availability?

Yes I am.
 
## Tech Skills

Assing yourself a score in the following technologies:
 

Object Oriented Programming (OOP) - 6

Git -  6

PHP 5 - 6

CakePHP framework - 7

MySQL -  3

Javascript - 4

jQuery -  5

HTML - 6

CSS - 6


## Questions About OOP:

- How do you declare a function or method that you want to be accessed without instantiate the class?
public static function Class{}

- How do you create a child class of BaseClass ?
Class Child extends BaseClass{}

 
## Questions about GIT:

- If you accidentally add the wrong files to be commited using git add, how do you unstage them?

Well, I checked it now. Never really used it. Git reset HEAD path/filename

- If you want to switch to another branch, what command you need to execute?

Checked it now too. Git checkout branch_name

## Questions about PHP 5:

- Please write a conditional block of code that check if the variable $var exists, is not null and it's a number.

<?php if(isset($var) && isnumeric($var)){} ?>

- Write a function that adds a line to a log file the current date and time with this format: "[2013-09-23 00:3 0:15] - Status OK"

CakeLog::write('OK', date('Y-m-d H:i: s'));

## Questions about CakePHP

- Which is the default path where you set up the configuration for the database?
app/config/database.php

- How you can get the value of a session variable with key "foo" using CakePHP ?
$this->Session->read('foo');

## Questions about MySQL

- Write a single query to retrieve the information from 2 tables that are related( users and users_data) where the primary key on users is ID and the foreign key on users_data is USER_ID.

Well, after reading the question I realised that I have rated myself too high for MySQL. I have low MySQL skills obviously since all my work with database is mostly trough ORM and phpmyadmin clicking.

- Write a single query to retrieve all the queries that are currently running on the server .

Same applies as for the question before this one.

## Questions about Javascript

- How do access to the alt attribute of the following image element using javascript? <img src='http://example.com/image.jpg' id='some_img' alt='lol' />

getElementbyID().getAttribute()

- What is the protocol name behind ajax?
Umm...not sure what I'm asked. Asynchronous JavaScript and XML?


## Questions about jQuery

- Write a piece of javascript code using jQuery that make the el ement with id "someElement" to appear on the screen using a fade in effect after the DOM is loaded.

$(document ).ready(function() {
 $('.someElement').fadeIn();
});

- How do you remove an element from the DOM using jQuery?
$('.elementClass').remove();
 
## Questions about HTML

- Which is the doctype syntax for HTML5?
<!DOCTYPE html>

- Which is the attribute and value required on forms to allow file uploads?
 input type= "file"

## Questions about CSS

- Which is the css property and its value to force to hide the scroll on any DOM element with fixed height when its content exceed its own height?
Overflow:hidden;
- If you have to div elements next to each other with the property float:left, which CSS property do you need to add to the next element in order to get both of them to fill the same height on page and make the next one not a floating one?
clear:both?
## Questions about Linux / Unix based OS

- Which protocol(s) you could use to connect to a server SHELL remotely?

SSH

- Write a command to look for the word "ads" on all files with .ctp extension in the same directory
I used to know this, would have to remind myself about basic linux shell commands.
