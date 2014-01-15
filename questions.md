## Personal details

Name: Niles Rowland

Country: US

Hourly Rate: $40.00

Timezone: ET

Skype Id: neterslandreau

## Availability

Are you able to work from 3PM to 7PM (GMT -2) ? In case you aren't, what's your availability? Yes
 
## Tech Skills

Assing yourself a score in the following technologies:


Object Oriented Programming (OOP) - 8

Git -  8

PHP 5 - 9

CakePHP framework - 10

MySQL -  8

Javascript - 8

jQuery -  8

HTML - 9

CSS - 9

## Questions About OOP:

- How do you declare a function or method that you want to be accessed without instantiate the class?
static

- How do you create a child class of BaseClass ?
class ChildClass extends BaseClass { ... }
 
## Questions about GIT:

- If you accidentally add the wrong files to be commited using git add, how do you unstage them?
git reset HEAD path/to/incorrect/file.ext
- If you want to switch to another branch, what command you need to execute?
git checkout new-branch
 
## Questions about PHP 5:

- Please write a conditional block of code that check if the variable $var exists, is not null and it's a number.
if (isset($var) && is_numeric($var)) {
	echo 'var is set and a number';
}

- Write a function that adds a line to a log file the current date and time with this format: "[2013-09-23 00:3 0:15] - Status OK"
	function logit() {
		$msg = 'Status OK';
		$now = date('Y-m-d H:i:s');
		$line = sprintf('[%s] - %s', $now, $msg);
		$this->out($line);
		$fh = fopen('/path/to/logger.txt', 'a+');
		fwrite($fh, $line."\n");
		fclose($fh);
	}

## Questions about CakePHP

- Which is the default path where you set up the configuration for the database?
/path/to/App/Config/database.php

- How you can get the value of a session variable with key "foo" using CakePHP ?
$this->Session->read('foo');

## Questions about MySQL

- Write a single query to retrieve the information from 2 tables that are related( users and users_data) where the primary key on users is ID and the foreign key on users_data is USER_ID.
SELECT `UserData`.*, `User`.*
FROM `users_data` AS `UserData`
LEFT JOIN `users` AS `User` ON (`UserData`.`USER_ID` = `User`.`ID`);

- Write a single query to retrieve all the queries that are currently running on the server .
SHOW FULL PROCESSLIST;

## Questions about Javascript

- How do access to the alt attribute of the following image element using javascript? <img src='http://example.com/image.jpg' id='some_img' alt='lol' />
document.getElementById('some_img').alt

- What is the protocol name behind ajax?
XMLHttpRequest

## Questions about jQuery

- Write a piece of javascript code using jQuery that make the el ement with id "someElement" to appear on the screen using a fade in effect after the DOM is loaded.
$('#someElement').fadeIn();

- How do you remove an element from the DOM using jQuery?
$.remove('#no_longer_wanted_element');
 
## Questions about HTML

- Which is the doctype syntax for HTML5?
<!DOCTYPE html>

- Which is the attribute and value required on forms to allow file uploads?
enctype="multipart/form-data"

## Questions about CSS

- Which is the css property and its value to force to hide the scroll on any DOM element with fixed height when its content exceed its own height?
overflow: hidden;

- If you have to div elements next to each other with the property float:left, which CSS property do you need to add to the next element in order to get both of them to fill the same height on page and make the next one not a floating one?
??

## Questions about Linux / Unix based OS

- Which protocol(s) you could use to connect to a server SHELL remotely?
ssh, sftp, telnet

- Write a command to look for the word "ads" on all files with .ctp extension in the same directory
grep "\bads\b" *.ctp
