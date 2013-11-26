## Personal details

Name: WDP Technologies Pvt. Ltd.

Country: India

Hourly Rate: 

Timezone: GMT+5.50

Skype Id: aniljmk

## Availability: 9.30 AM - 6.30(IST)

Are you able to work from 3PM to 7PM (GMT -2) ? In case you aren't, what's your availability?
 
## Tech Skills: PHP, Mysql, Cakephp, Zend, Magento, Java, Hibernate, Eclipse, IOS/Android

Assing yourself a score in the following technologies:


Object Oriented Programming (OOP) - 8/10

Git -  8/10

PHP 5 - 10/10

CakePHP framework - 10/10

MySQL -  8/10

Javascript - 8/10

jQuery -  8/10

HTML - 10/10

CSS - 10/10

## Questions About OOP:

- How do you declare a function or method that you want to be accessed without instantiate the class?
- Class Sample{
	Public function getTime()
{
	Return time();
}
}
$time = Sample::getTime();
Echo $time;


- How do you create a child class of BaseClass ?
Class BaseClass {
	// BaseClass properties here. 
}
Class ChildClass extands BaseClass
{
	// ChildClass properties here.
}

 
## Questions about GIT:

- If you accidentally add the wrong files to be commited using git add, how do you unstage them?
- git reset <path>

- If you want to switch to another branch, what command you need to execute?
- git branch(branch)
 
## Questions about PHP 5:

- Please write a conditional block of code that check if the variable $var exists, is not null and it's a number.
if(isset($var) && !empty($var) && is_numeric($var)).

- Write a function that adds a line to a log file the current date and time with this format: "[2013-09-23 00:3 0:15] - Status OK"
- The format is date(“Y-m-d H:i:s”).

## Questions about CakePHP

- Which is the default path where you set up the configuration for the database?
- We can configure database configuration in (Folder) Application -> Config -> database.php.

- How you can get the value of a session variable with key "foo" using CakePHP ?
- We can get value of “foo” session using cakephp as “ $this->Session->read(”foo”); “.

## Questions about MySQL

- Write a single query to retrieve the information from 2 tables that are related( users and users_data) where the primary key on users is ID and the foreign key on users_data is USER_ID.
- SELECT * FROM users, user_data WHERE users.ID = users_data.USER_ID ;

- Write a single query to retrieve all the queries that are currently running on the server .
- SHOW FULL PROCESSLIST

## Questions about Javascript

- How do access to the alt attribute of the following image element using javascript? <img src='http://example.com/image.jpg' id='some_img' alt='lol' />
- document.getElementById(“image”) .alt ;

- What is the protocol name behind ajax?
- XMLHttpRequest  (HTTP’s) Protocol.

## Questions about jQuery

- Write a piece of javascript code using jQuery that make the el ement with id "someElement" to appear on the screen using a fade in effect after the DOM is loaded.
- $(document).ready(function(){
	If(true)
{
	$(“# someElement”).fadeIn(2000);
}
});


- How do you remove an element from the DOM using jQuery?
- $(“# someElement”).remove();
 
## Questions about HTML

- Which is the doctype syntax for HTML5?
- <!DOCTYPE html>

- Which is the attribute and value required on forms to allow file uploads?
- <form action=""  method="post"  enctype="multipart/form-data"></form>

## Questions about CSS

- Which is the css property and its value to force to hide the scroll on any DOM element with fixed height when its content exceed its own height?
- overflow:hidden;

- If you have to div elements next to each other with the property float:left, which CSS property do you need to add to the next element in order to get both of them to fill the same height on page and make the next one not a floating one?
- position: relative; , position:absolute; 

## Questions about Linux / Unix based OS

- Which protocol(s) you could use to connect to a server SHELL remotely?
SSH client - putty

- Write a command to look for the word "ads" on all files with .ctp extension in the same directory
- grep ‘ads’ /*.ctp
- 
