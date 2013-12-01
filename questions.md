## Personal details

Name: Galih Firmansyah

Country: Indonesia

Hourly Rate: $10 USD

Timezone: 

Skype Id: galih.f

## Availability

Are you able to work from 3PM to 7PM (GMT -2) ? In case you aren't, what's your availability? 
Answer : I will available on your time.
 
## Tech Skills

Assing yourself a score in the following technologies:


Object Oriented Programming (OOP) - 100

Git -  100

PHP 5 - 100

CakePHP framework - 85

MySQL -  85

Javascript - 

jQuery -  85

HTML - 100

CSS - 100

## Questions About OOP:

- How do you declare a function or method that you want to be accessed without instantiate the class? 
  Answer : ClassName::MethodName

- How do you create a child class of BaseClass ? 
  Answer :
  Class Child Extends BaseClass {
     
  }

 
## Questions about GIT:

- If you accidentally add the wrong files to be commited using git add, how do you unstage them? 
  Answer : git reset HEAD path/to/file

- If you want to switch to another branch, what command you need to execute? 
  Answer : git checkout BranchName

 
## Questions about PHP 5:

- Please write a conditional block of code that check if the variable $var exists, is not null and it's a number.
  Answer : 
  if (isset($var) && !is_null($var) && is_int($var)) {
    /* your logic code */
  }

- Write a function that adds a line to a log file the current date and time with this format: "[2013-09-23 00:3 0:15] - Status OK"
  Answer :
  $msg = date(Y-m-d H:i s:u)." - Status OK";

  file_put_contents("log.txt", $msg, FILE_APPEND);

## Questions about CakePHP

- Which is the default path where you set up the configuration for the database?
  Answer : app/Config/database.php

- How you can get the value of a session variable with key "foo" using CakePHP ?
  Answer : $this->Session->read('foo')

## Questions about MySQL

- Write a single query to retrieve the information from 2 tables that are related( users and users_data) where the primary key on users is ID and the foreign key on users_data is USER_ID.
  Answer :
  SELECT `User`.`ID`, `User`.`field2`, `User`.`field2`, `UserData`.`ID`, `UserData`.`USER_ID`, `UserData`.`field2`, `UserData`.`field2`
  FROM `DatabaseName`.`users` AS `User`
  LEFT JOIN `DatabaseName`.`users_data` AS `UserData` ON (`User`.`ID` = `UserData`.`USER_ID`)

- Write a single query to retrieve all the queries that are currently running on the server .
  Answer : SHOW FULL PROCESSLIST

## Questions about Javascript

- How do access to the alt attribute of the following image element using javascript? <img src='http://example.com/image.jpg' id='some_img' alt='lol' />
  Answer :
  $(document).ready(function(){
     $('#some_img').getAttribute('alt');
  });

- What is the protocol name behind ajax?
  Answer :
  XHR(Xml Http Request)

## Questions about jQuery

- Write a piece of javascript code using jQuery that make the el ement with id "someElement" to appear on the screen using a fade in effect after the DOM is loaded.
  Answer :
  $(document).ready(function(){
    $('#someElement').fadeIn();
  });

- How do you remove an element from the DOM using jQuery?
   $(document).ready(function(){
    $('#someElement').remove();
  });

## Questions about HTML

- Which is the doctype syntax for HTML5?
  <!DOCTYPE html>

- Which is the attribute and value required on forms to allow file uploads?
  Answer : enctype="multipart/form-data"

## Questions about CSS

- Which is the css property and its value to force to hide the scroll on any DOM element with fixed height when its content exceed its own height?
  Answer : overflow: hidden;

- If you have to div elements next to each other with the property float:left, which CSS property do you need to add to the next element in order to get both of them to fill the same height on page and make the next one not a floating one?
  Answer : 
  Add one of the element in the last of float and add style attribute with "clear:both;", it would be better if you 
  create one CSS class with "clear:both;", becaues you will use it often

## Questions about Linux / Unix based OS

- Which protocol(s) you could use to connect to a server SHELL remotely?
ssh
  Answer : SSH

- Write a command to look for the word "ads" on all files with .ctp extension in the same directory
  Answer : grep -R --include="*.ctp" "ads" DirectoryName
