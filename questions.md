## Personal details

Name: Oldemar

Country: Brazil (Born) USA (Actual living)

Hourly Rate: $40.00

Timezone: Eastern Time Zone (Florida)

Skype Id: oldemar_jr

## Availability

Are you able to work from 3PM to 7PM (GMT -2) ? In case you aren't, what's your availability?

Yes, but 5pm to 9pm, would be better
 
## Tech Skills

Assing yourself a score in the following technologies:


Object Oriented Programming (OOP) - 7

Git - 8

PHP 5 - 8

CakePHP framework - 9

MySQL -  9

Javascript - 7

jQuery -  8

HTML - 9

CSS - 9

## Questions About OOP:

- How do you declare a function or method that you want to be accessed without instantiate the class?
- Just creating an abstract class
- 

- How do you create a child class of BaseClass ?
class child exends BaseClass
 
## Questions about GIT:

- If you accidentally add the wrong files to be commited using git add, how do you unstage them?
- 
git reset (file_name)

- If you want to switch to another branch, what command you need to execute?
- 
git checkout (branch_name)

 
## Questions about PHP 5:

- Please write a conditional block of code that check if the variable $var exists, is not null and it's a number.
- if (isset($var) && !is_null($var) && is_numeric($var))
- { 
    do something;
- }
- else
- {
    do other thing;
- }

- Write a function that adds a line to a log file the current date and time with this format: "[2013-09-23 00:3 0:15] - Status OK"

## Questions about CakePHP

- Which is the default path where you set up the configuration for the database?
 app/Config

- How you can get the value of a session variable with key "foo" using CakePHP ?
You can use CakeSession::read('foo'), but it depends where you are (view, controller or elsewhere) 

## Questions about MySQL

- Write a single query to retrieve the information from 2 tables that are related( users and users_data) where the primary key on users is ID and the foreign key on users_data is USER_ID.
- SELECT * FROM users u, users_data ud WHERE u.ID = ud.USER_ID

- Write a single query to retrieve all the queries that are currently running on the server .

## Questions about Javascript

- How do access to the alt attribute of the following image element using javascript? <img src='http://example.com/image.jpg' id='some_img' alt='lol' />
- var var = getElementById('some_img').attr('alt');

- What is the protocol name behind ajax?
- HTTP, GET or POST. and also uses XMLHttpRequest for server requesting. 

## Questions about jQuery

- Write a piece of javascript code using jQuery that make the el ement with id "someElement" to appear on the screen using a fade in effect after the DOM is loaded.

$('document').ready(function(){$('someElement').fadeIn();});

- How do you remove an element from the DOM using jQuery?
 
## Questions about HTML

- Which is the doctype syntax for HTML5?
- <!DOCTYPE html>

- Which is the attribute and value required on forms to allow file uploads?
- enctype="multipart/form-data"

## Questions about CSS

- Which is the css property and its value to force to hide the scroll on any DOM element with fixed height when its content exceed its own height?
- for vertical and horizontal movement use overflow: auto;

- If you have to div elements next to each other with the property float:left, which CSS property do you need to add to the next element in order to get both of them to fill the same height on page and make the next one not a floating one?
- clear:both;

## Questions about Linux / Unix based OS

- Which protocol(s) you could use to connect to a server SHELL remotely?
ssh user(given by administrator)@ip address or domain name

- Write a command to look for the word "ads" on all files with .ctp extension in the same directory
- grep 'ads' *.ctp 
