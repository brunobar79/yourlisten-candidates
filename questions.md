## Personal details

Name: Nitin Goswami

Country: India

Hourly Rate: $15

Timezone: IST GMT +5:30

Skype Id: niting786

## Availability

Are you able to work from 3PM to 7PM (GMT -2) ? In case you aren't, what's your availability?

Yes I can work from 3pm to 7pm in GMT -2
 
## Tech Skills

Assing yourself a score in the following technologies:


Object Oriented Programming (OOP) - 9/10

Git -  9/10

PHP 5 - 9/10

CakePHP framework - 10/10

MySQL -  9/10

Javascript - 9/10

jQuery -  9/10

HTML - 9/10

CSS - 9/10

## Questions About OOP:

- How do you declare a function or method that you want to be accessed without instantiate the class?
- Ans:  A static method or function can be accessed without instantiate the class. 

static function showPeople()
    {  
    }

- How do you create a child class of BaseClass ?
- Ans: Using extends 
- class Named_Cart extends Cart {
    var $owner;
  
    function set_owner ($name) {
        $this->owner = $name;
    }
}

 
## Questions about GIT:

- If you accidentally add the wrong files to be commited using git add, how do you unstage them?
- I use GIT GUI from where I can select the file and unstage them

- If you want to switch to another branch, what command you need to execute?
- - Using GIT GUI I can easily change the branch

 
## Questions about PHP 5:

- Please write a conditional block of code that check if the variable $var exists, is not null and it's a number.
-  if(isset($var)){
          if(!empty($var) && is_numeric($var)){
          
          }
    }


- Write a function that adds a line to a log file the current date and time with this format: "[2013-09-23 00:3 0:15] - Status OK"
Ans:   public function log() 
    { 
      $date = date('Y-m-d h:i:s'); 
      $log =  Date." - "."Status OK"."\n"; 
      error_log($log, 3, self::GENERAL_ERROR_DIR); 
    } 

    function logToFile($msg) {
      $filename = "log.txt";
      $fd = fopen($filename, "a");
      $date = date('Y-m-d h:i:s'); 
      $str =  Date." - "."Status OK"."\n"; 
      fwrite($fd, $str);
      fclose($fd);
    }  

## Questions about CakePHP

- Which is the default path where you set up the configuration for the database?
- Ans: in app/config/database.php

- How you can get the value of a session variable with key "foo" using CakePHP ?
- Ans:  $this->Session->read('foo');

## Questions about MySQL

- Write a single query to retrieve the information from 2 tables that are related( users and users_data) where the primary key on users is ID and the foreign key on users_data is USER_ID.

select users.*, users_data.* from users left join users_data on (users.ID = users_data.USER_ID)

- Write a single query to retrieve all the queries that are currently running on the server .
- show processlist;

## Questions about Javascript

- How do access to the alt attribute of the following image element using javascript? <img src='http://example.com/image.jpg' id='some_img' alt='lol' />
var $img = $a.getElementsById("some_img");
console.log($img.alt);

- What is the protocol name behind ajax?
- XmlHttpRequest

## Questions about jQuery

- Write a piece of javascript code using jQuery that make the el ement with id "someElement" to appear on the screen using a fade in effect after the DOM is loaded.
Ans:   var html = "<div id='blah'>Hello stuff here</div>"
        $(html).hide().appendTo("#mycontent").fadeIn(1000);

- How do you remove an element from the DOM using jQuery?
- $( ".hello" ).remove();
 
## Questions about HTML

- Which is the doctype syntax for HTML5?
- <!DOCTYPE html>

- Which is the attribute and value required on forms to allow file uploads?
- enctype="multipart/form-data"
- 

## Questions about CSS

- Which is the css property and its value to force to hide the scroll on any DOM element with fixed height when its content exceed its own height?
overflow:hidden


- If you have to div elements next to each other with the property float:left, which CSS property do you need to add to the next element in order to get both of them to fill the same height on page and make the next one not a floating one?
Not clear with the question

## Questions about Linux / Unix based OS

- Which protocol(s) you could use to connect to a server SHELL remotely?
   SSH

- Write a command to look for the word "ads" on all files with .ctp extension in the same directory
- find . -name '*.ctp' -exec grep "<ads" /dev/null {} \;
- 
