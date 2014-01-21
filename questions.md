## Personal details

Name: Anya Marshall

Country: USA

Hourly Rate: $40/hr 

Timezone: EST/EDT

Skype Id: novarra_anya

## Availability

Are you able to work from 3PM to 7PM (GMT -2) ? Yes
 
## Tech Skills

Assing yourself a score in the following technologies:


Object Oriented Programming (OOP) - 10/10

Git -  9/10

PHP 5 - 10/10

CakePHP framework - 7/10

MySQL - 9/10

Javascript - 9/10 

jQuery - 9/10

HTML - 10/10

CSS - 10/10

## Questions About OOP:

- How do you declare a function or method that you want to be accessed without instantiate the class?
Make it abstract. In PHP5: 
	abstract class SomeClass { 
		// class definition etc
	}

- How do you create a child class of BaseClass ?
Extend BaseClass. In PHP5:
	class ChildClass extends BaseClass {
		// class definition etc
	}	

 
## Questions about GIT:

- If you accidentally add the wrong files to be commited using git add, how do you unstage them?
	git reset HEAD path/to/file

- If you want to switch to another branch, what command you need to execute?
	git checkout -b <branch>

 
## Questions about PHP 5:

- Please write a conditional block of code that check if the variable $var exists, is not null and it's a number.
	if(!is_null($var) && is_numeric($var)) {
		// execute code
	}

- Write a function that adds a line to a log file the current date and time with this format: "[2013-09-23 00:30:15] - Status OK"
	function addLine($logfile) {
		$OUT = fopen($logfile, 'w');
		$datetime = date('Y-m-d H-i-s');
		fwrite($OUT, "[$datetime] - Status OK";
	}

## Questions about CakePHP

- Which is the default path where you set up the configuration for the database?
	/app/Config/database.php

- How you can get the value of a session variable with key "foo" using CakePHP ?
	CakeSession::read('foo')

## Questions about MySQL

- Write a single query to retrieve the information from 2 tables that are related( users and users_data) where the primary key on users is ID and the foreign key on users_data is USER_ID.
	SELECT * FROM users INNER JOIN users_data on users.ID = users_data.user_id;

- Write a single query to retrieve all the queries that are currently running on the server .
	SHOW PROCESSLIST

## Questions about Javascript

- How do access to the alt attribute of the following image element using javascript? <img src='http://example.com/image.jpg' id='some_img' alt='lol' />
	document.getElementByID('some_img').alt

- What is the protocol name behind ajax?
	XHR (XMLHttpRequest)

## Questions about jQuery

- Write a piece of javascript code using jQuery that make the el ement with id "someElement" to appear on the screen using a fade in effect after the DOM is loaded.
	$(function() {
		$('#someElement').fadeIn(500);
	}

- How do you remove an element from the DOM using jQuery?
	$('#someElement').remove();
 
## Questions about HTML

- Which is the doctype syntax for HTML5?
	<!DOCTYPE HTML>

- Which is the attribute and value required on forms to allow file uploads?
	<form method="post" enctype="multipart/form-data">
		<input type="file" name="fileupload">
	</form>

## Questions about CSS

- Which is the css property and its value to force to hide the scroll on any DOM element with fixed height when its content exceed its own height?
	overflow:hidden;

- If you have two div elements next to each other with the property float:left, which CSS property do you need to add to the next element in order to get both of them to fill the same height on page and make the next one not a floating one?
	clear: both

## Questions about Linux / Unix based OS

- Which protocol(s) you could use to connect to a server SHELL remotely?
	ssh

- Write a command to look for the word "ads" on all files with .ctp extension in the same directory
	cat *.ctp | grep -w 'ads'