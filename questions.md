## Personal details

Name: Luis Ricardo Sanchez Tenas

Country: Panama

Hourly Rate: 12.50

Timezone: GMT -5:00

Skype Id: solutions_ccs

## Availability

Are you able to work from 3PM to 7PM (GMT -2) ? In case you aren't, what's your availability?
Available
 
## Tech Skills

Assing yourself a score in the following technologies:
*Score goes from 1 (No knoledge) - 10 (Pro)

Object Oriented Programming (OOP) -  9

Git -  10

PHP 5 - 9

CakePHP framework - 8

MySQL -  9

Javascript - 10

jQuery -  10

HTML - 10

CSS - 9

## Questions About OOP:

- How do you declare a function or method that you want to be accessed without instantiate the class?
Declaring a static function

- How do you create a child class of BaseClass ?
Extends the BaseClass on the child class

 
## Questions about GIT:

- If you accidentally add the wrong files to be commited using git add, how do you unstage them?
git reset HEAD <file>

- If you want to switch to another branch, what command you need to execute?
git checkout <branch_name>
 
## Questions about PHP 5:

- Please write a conditional block of code that check if the variable $var exists, is not null and it's a number.
isset($var) && is_numeric($var)

- Write a function that adds a line to a log file the current date and time with this format: "[2013-09-23 00:3 0:15] - Status OK"
function writeDateTime()
{
    $file = 'file.log';
    $content = date("Y-m-d H:i:s") . ' - Status OK';
    file_put_contents($file, $content, FILE_APPEND | LOCK_EX);
}

## Questions about CakePHP

- Which is the default path where you set up the configuration for the database?
app/Config

- How you can get the value of a session variable with key "foo" using CakePHP ?
$this->Session->read('foo');

## Questions about MySQL

- Write a single query to retrieve the information from 2 tables that are related( users and users_data) where the primary key on users is ID and the foreign key on users_data is USER_ID.
SELECT *
FROM users u
JOIN users_data ud ON u.ID = ud.USER_ID

- Write a single query to retrieve all the queries that are currently running on the server .
SHOW FULL PROCESSLIST

## Questions about Javascript

- How do access to the alt attribute of the following image element using javascript? <img src='http://example.com/image.jpg' id='some_img' alt='lol' />
document.getElementsById('some_img').getAttribute('alt');

- What is the protocol name behind ajax?
XMLHttpRequest

## Questions about jQuery

- Write a piece of javascript code using jQuery that make the el ement with id "someElement" to appear on the screen using a fade in effect after the DOM is loaded.
$(document).ready(function(){
     $('#someElement').fadeIn(500);
});

- How do you remove an element from the DOM using jQuery?
remove() method
 
## Questions about HTML

- Which is the doctype syntax for HTML5?
<!DOCTYPE html>

- Which is the attribute and value required on forms to allow file uploads?
type="file"

## Questions about CSS

- Which is the css property and its value to force to hide the scroll on any DOM element with fixed height when its content exceed its own height?
body {
    overflow-y:hidden;
}

- If you have to div elements next to each other with the property float:left, which CSS property do you need to add to the next element in order to get both of them to fill the same height on page and make the next one not a floating one?
float:none;

## Questions about Linux / Unix based OS

- Which protocol(s) you could use to connect to a server SHELL remotely?
ssh

- Write a command to look for the word "ads" on all files with .ctp extension in the same directory
grep "ads" *.ctp
