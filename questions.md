## Personal details

Name: sadi Abdullah

Country: Bangladesh

Hourly Rate: 15

Timezone: GMT +6

Skype Id: sadi.dev

## Availability

Are you able to work from 3PM to 7PM (GMT -2) ? In case you aren't, what's your availability?

Yes, I can. But I would like to 11AM to 3PM (GMT -2)
 
## Tech Skills

Assing yourself a score in the following technologies:


Object Oriented Programming (OOP) - 7

Git -  7

PHP 5 - 9

CakePHP framework - 7

MySQL -  7

Javascript - 5

jQuery -  6

HTML - 6

CSS - 5

## Questions About OOP:

- How do you declare a function or method that you want to be accessed without instantiate the class?

class ClassName {
  public static function myStaticMethod() {
    // the code goes here
  }
}

- How do you create a child class of BaseClass ?

class BaseClass {
}

class ChildClass extends BaseClass {
}

 
## Questions about GIT:

- If you accidentally add the wrong files to be commited using git add, how do you unstage them?

git reset

- If you want to switch to another branch, what command you need to execute?

git checkout another_branch_name

 
## Questions about PHP 5:

- Please write a conditional block of code that check if the variable $var exists, is not null and it's a number.

if(isset($var) && !is_null($var) && is_numeric($var)) {
  // statement goes here
}

- Write a function that adds a line to a log file the current date and time with this format: "[2013-09-23 00:3 0:15] - Status OK"

function write_log($message) {
  $formatted_date = date('Y-m-d i:g') .  intval(date('i')) . ':' . date('H');
  $log = "[{$formatted_date}] - {$message}";
  file_put_contents('the_log_file.log', $log, FILE_APPEND);
}

## Questions about CakePHP

- Which is the default path where you set up the configuration for the database?

app/Config/database.php

- How you can get the value of a session variable with key "foo" using CakePHP ?

$this->Session->read('foo');

## Questions about MySQL

- Write a single query to retrieve the information from 2 tables that are related( users and users_data) where the primary key on users is ID and the foreign key on users_data is USER_ID.

select users.*, users_data.*
from users
left join users_data on users.ID = users_data.USER_ID;

- Write a single query to retrieve all the queries that are currently running on the server .

show processlist;

## Questions about Javascript

- How do access to the alt attribute of the following image element using javascript? <img src='http://example.com/image.jpg' id='some_img' alt='lol' />

document.getElementById("some_img").getAttribute("alt");

- What is the protocol name behind ajax?

HTML

## Questions about jQuery

- Write a piece of javascript code using jQuery that make the el ement with id "someElement" to appear on the screen using a fade in effect after the DOM is loaded.

$(document).ready(function() {
  $("#someElement").fadeIn("slow");
});

- How do you remove an element from the DOM using jQuery?

$('selector').remove();
 
## Questions about HTML

- Which is the doctype syntax for HTML5?

<!DOCTYPE HTML>

- Which is the attribute and value required on forms to allow file uploads?

enctype="multipart/form-data" method="post"

## Questions about CSS

- Which is the css property and its value to force to hide the scroll on any DOM element with fixed height when its content exceed its own height?

overflow-y: scroll;

- If you have to div elements next to each other with the property float:left, which CSS property do you need to add to the next element in order to get both of them to fill the same height on page and make the next one not a floating one?

Sorry, I am little confused with this question. I can use "height" property to set specific height (in this case I may use 100%). "clear" property can rid the floating property. Usually I use wrapper/parent div to get better controll over the HTML DOM

## Questions about Linux / Unix based OS

- Which protocol(s) you could use to connect to a server SHELL remotely?

SSH

- Write a command to look for the word "ads" on all files with .ctp extension in the same directory

grep "ads" *.ctp

