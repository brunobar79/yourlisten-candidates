
## Personal details

Name: ahmad rabbani

Country: Pakistan

Hourly Rate: 15

Timezone: +5 GMT

Skype Id: ahmad.rabbani1

## Availability

Are you able to work from 3PM to 7PM (GMT -2) ? In case you aren't, what's your availability?
 Yes
## Tech Skills

Assing yourself a score in the following technologies:


Object Oriented Programming (OOP) - 

Git -  8

PHP 5 - 9

CakePHP framework - 8

MySQL -  9

Javascript - 9

jQuery -  9

HTML - 9

CSS - 9

## Questions About OOP:

- How do you declare a function or method that you want to be accessed without instantiate the class?
By making it a static method. 
- How do you create a child class of BaseClass ?
class ChildClass extends BaseClass {
....
}

 
## Questions about GIT:

- If you accidentally add the wrong files to be commited using git add, how do you unstage them?
git reset 
- If you want to switch to another branch, what command you need to execute?
git checkout branchname
 
## Questions about PHP 5:

- Please write a conditional block of code that check if the variable $var exists, is not null and it's a number.
if(isset($var) && trim($var) != null &&  $var!=null && is_numeric($var) )

- Write a function that adds a line to a log file the current date and time with this format: "[2013-09-23 00:3 0:15] - Status OK"
<?php 
function write_logs(){
	$f = fopen($file,'wb'); 
	$content = "[".date('Y-m-d H:i:s')."]";
	fwrite($f,$content,strlen($content)); 
	fclose($f);
} 
?>
## Questions about CakePHP

- Which is the default path where you set up the configuration for the database?
default app/Config/database.php.default
actual for which we setup our configuration app/Config/database.php
- How you can get the value of a session variable with key "foo" using CakePHP ?
$green = $this->Session->read('foo');
## Questions about MySQL

- Write a single query to retrieve the information from 2 tables that are related( users and users_data) where the primary key on users is ID and the foreign key on users_data is USER_ID.
Select * 
From users as u
Join users_data as ud u.id = ud.user_id

- Write a single query to retrieve all the queries that are currently running on the server .
SHOW FULL PROCESSLIST;
## Questions about Javascript

- How do access to the alt attribute of the following image element using javascript? <img src='http://example.com/image.jpg' id='some_img' alt='lol' />
document.getElementsById.getAttribute("alt");
- What is the protocol name behind ajax?
XMLHttpRequest as Ajax stand for Asynchronous JavaScript and XML
## Questions about jQuery

- Write a piece of javascript code using jQuery that make the el ement with id "someElement" to appear on the screen using a fade in effect after the DOM is loaded.
$(document).ready(function(){
	$("#someElement").fadeIn();
});
- How do you remove an element from the DOM using jQuery?
 $("#someElement").remove();
## Questions about HTML

- Which is the doctype syntax for HTML5?
<!DOCTYPE html PUBLIC "-//W3C//DTD HTML 5.0//EN">
- Which is the attribute and value required on forms to allow file uploads?
enctype="multipart/form-data" and input type is file
## Questions about CSS

- Which is the css property and its value to force to hide the scroll on any DOM element with fixed height when its content exceed its own height?
overflow:none;

- If you have to div elements next to each other with the property float:left, which CSS property do you need to add to the next element in order to get both of them to fill the same height on page and make the next one not a floating one?
display:inline-block;
## Questions about Linux / Unix based OS

- Which protocol(s) you could use to connect to a server SHELL remotely?
ssh

- Write a command to look for the word "ads" on all files with .ctp extension in the same directory
find /folder/path -name "*.ctp"  | xargs grep ads
## Availability

Are you able to work from 3PM to 7PM (GMT -2) ? In case you aren't, what's your availability?
 
## Tech Skills

Assing yourself a score in the following technologies:


Object Oriented Programming (OOP) - 

Git -  

PHP 5 - 

CakePHP framework - 

MySQL -  

Javascript - 

jQuery -  

HTML - 

CSS - 

## Questions About OOP:

- How do you declare a function or method that you want to be accessed without instantiate the class?

- How do you create a child class of BaseClass ?

 
## Questions about GIT:

- If you accidentally add the wrong files to be commited using git add, how do you unstage them?

- If you want to switch to another branch, what command you need to execute?

 
## Questions about PHP 5:

- Please write a conditional block of code that check if the variable $var exists, is not null and it's a number.

- Write a function that adds a line to a log file the current date and time with this format: "[2013-09-23 00:3 0:15] - Status OK"

## Questions about CakePHP

- Which is the default path where you set up the configuration for the database?

- How you can get the value of a session variable with key "foo" using CakePHP ?

## Questions about MySQL

- Write a single query to retrieve the information from 2 tables that are related( users and users_data) where the primary key on users is ID and the foreign key on users_data is USER_ID.

- Write a single query to retrieve all the queries that are currently running on the server .

## Questions about Javascript

- How do access to the alt attribute of the following image element using javascript? <img src='http://example.com/image.jpg' id='some_img' alt='lol' />

- What is the protocol name behind ajax?

## Questions about jQuery

- Write a piece of javascript code using jQuery that make the el ement with id "someElement" to appear on the screen using a fade in effect after the DOM is loaded.

- How do you remove an element from the DOM using jQuery?
 
## Questions about HTML

- Which is the doctype syntax for HTML5?

- Which is the attribute and value required on forms to allow file uploads?

## Questions about CSS

- Which is the css property and its value to force to hide the scroll on any DOM element with fixed height when its content exceed its own height?

- If you have to div elements next to each other with the property float:left, which CSS property do you need to add to the next element in order to get both of them to fill the same height on page and make the next one not a floating one?

## Questions about Linux / Unix based OS

- Which protocol(s) you could use to connect to a server SHELL remotely?
ssh

- Write a command to look for the word "ads" on all files with .ctp extension in the same directory
