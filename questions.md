## Personal details

Name:
Niles Rowland

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
<pre>
static
</pre>

- How do you create a child class of BaseClass ?
<pre>
class ChildClass extends BaseClass { ... }
</pre>

## Questions about GIT:

- If you accidentally add the wrong files to be commited using git add, how do you unstage them?
<pre>
git reset HEAD path/to/incorrect/file.ext
</pre>

- If you want to switch to another branch, what command you need to execute?
<pre>
git checkout new-branch
</pre>
 
## Questions about PHP 5:

- Please write a conditional block of code that check if the variable $var exists, is not null and it's a number.
<pre>
if (isset($var) && is_numeric($var)) {
	echo 'var is set and a number';
}
</pre>

- Write a function that adds a line to a log file the current date and time with this format: "[2013-09-23 00:3 0:15] - Status OK"
<pre>
	function logit($msg = 'Status OK') {
		$now = date('Y-m-d H:i:s');
		$line = sprintf('[%s] - %s', $now, $msg);
		$this->out($line);
		$fh = fopen('/path/to/logger.txt', 'a+');
		fwrite($fh, $line."\n");
		fclose($fh);
	}
</pre>
## Questions about CakePHP

- Which is the default path where you set up the configuration for the database?
<pre>
/path/to/App/Config/database.php
</pre>

- How you can get the value of a session variable with key "foo" using CakePHP ?
<pre>
$this->Session->read('foo');
</pre>

## Questions about MySQL

- Write a single query to retrieve the information from 2 tables that are related( users and users_data) where the primary key on users is ID and the foreign key on users_data is USER_ID.
<pre>
SELECT UserData.*, User.*
    FROM users_data AS UserData
    LEFT JOIN users AS User ON (UserData.USER_ID = User.ID);
</pre>

- Write a single query to retrieve all the queries that are currently running on the server .
<pre>
SHOW FULL PROCESSLIST;
</pre>

## Questions about Javascript

- How do access to the alt attribute of the following image element using javascript? `<img src='http://example.com/image.jpg' id='some_img' alt='lol' />`
<pre>
document.getElementById('some_img').alt
</pre>

- What is the protocol name behind ajax?
<pre>
XMLHttpRequest
</pre>

## Questions about jQuery

- Write a piece of javascript code using jQuery that make the el ement with id "someElement" to appear on the screen using a fade in effect after the DOM is loaded.
<pre>
$('#someElement').fadeIn();
</pre>

- How do you remove an element from the DOM using jQuery?
<pre>
$.remove('#no_longer_wanted_element');
</pre>
 
## Questions about HTML

- Which is the doctype syntax for HTML5?
```
<!DOCTYPE html>
```

- Which is the attribute and value required on forms to allow file uploads?
<pre>
enctype="multipart/form-data"
</pre>

## Questions about CSS

- Which is the css property and its value to force to hide the scroll on any DOM element with fixed height when its content exceed its own height?
<pre>
overflow: hidden;
</pre>

- If you have to div elements next to each other with the property float:left, which CSS property do you need to add to the next element in order to get both of them to fill the same height on page and make the next one not a floating one?
??

## Questions about Linux / Unix based OS

- Which protocol(s) you could use to connect to a server SHELL remotely?
<pre>
ssh, sftp, telnet`
</pre>

- Write a command to look for the word "ads" on all files with .ctp extension in the same directory
<pre>
grep "\bads\b" *.ctp
</pre>

