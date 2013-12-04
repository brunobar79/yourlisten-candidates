## Personal details

Name: Miralem Mehic	

Country: Bosnia and Herzegovina

Hourly Rate: 20-30h per week

Timezone: UTC/GMT +1 hour

Skype Id: mickeyze2

## Availability

Are you able to work from 3PM to 7PM (GMT -2) ? In case you aren't, what's your availability?
I perfer to work on flexibile time base, even on weekends.
 
## Tech Skills

Assing yourself a score in the following technologies:


Object Oriented Programming (OOP) - 5/5

Git -  3/5

PHP 5 - 4/5

CakePHP framework - 4/5

MySQL -  4/5

Javascript - 4/5 

jQuery -  4/5

HTML - 4/5

CSS - 4/5

## Questions About OOP:

- How do you declare a function or method that you want to be accessed without instantiate the class?
	As static

- How do you create a child class of BaseClass ?
	by extending base class
 
## Questions about GIT:

- If you accidentally add the wrong files to be commited using git add, how do you unstage them?
	git rm

- If you want to switch to another branch, what command you need to execute?
	git checkout <name of branch>
 
## Questions about PHP 5:

- Please write a conditional block of code that check if the variable $var exists, is not null and it's a number.
	if(isset($var) && $var && is_numeric($var)){...}

- Write a function that adds a line to a log file the current date and time with this format: "[2013-09-23 00:30:15] - Status OK"
	error_log ( "[" . date('Y-m-d H:i:s', time()) . " - Status OK", 0);
	

## Questions about CakePHP

- Which is the default path whsere you set up the configuration for the database?
	/app/Config/database.php

- How you can get the value of a session variable with key "foo" using CakePHP ?
	CakeSession::read('foo');

## Questions about MySQL

- Write a single query to retrieve the information from 2 tables that are related( users and users_data) where the primary key on users is ID and the foreign key on users_data is USER_ID.
	SELECT * FROM users INNER JOIN users_data ON users.id = users_data.user_id

- Write a single query to retrieve all the queries that are currently running on the server .
	SHOW FULL PROCESSLIST;
	

## Questions about Javascript

- How do access to the alt attribute of the following image element using javascript? <img src='http://example.com/image.jpg' id='some_img' alt='lol' />
	$('#some_img').attr('alt');

- What is the protocol name behind ajax?
JSON?

## Questions about jQuery

- Write a piece of javascript code using jQuery that make the el ement with id "someElement" to appear on the screen using a fade in effect after the DOM is loaded.
$( document ).ready(function() {
	$('#someElement').fadeIn();
});
 
- How do you remove an element from the DOM using jQuery?
	$('#someElement').remove();
 
## Questions about HTML

- Which is the doctype syntax for HTML5?
<!DOCTYPE html>

- Which is the attribute and value required on forms to allow file uploads?
enctype="multipart/form-data"

## Questions about CSS

- Which is the css property and its value to force to hide the scroll on any DOM element with fixed height when its content exceed its own height?
overflow:hidden

- If you have two div elements next to each other with the property float:left, which CSS property do you need to add to the next element in order to get both of them to fill the same height on page and make the next one not a floating one?
clear:both; height: 100%;

## Questions about Linux / Unix based OS

- Which protocol(s) you could use to connect to a server SHELL remotely?
ssh on application level and  tcp on transport IP level

- Write a command to look for the word "ads" on all files with .ctp extension in the same directory
find . -name “*.cpt”;