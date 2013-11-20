## Personal details

Name:  MAYANK SOOD

Country: INDIA

Hourly Rate: 9$/h

Timezone: UTC+05:30

Skype Id: developer_mayank

## Availability

Are you able to work from 3PM to 7PM (GMT -2) ? In case you aren't, what's your availability?

ANS: I can work for 3 hours daily.
 
## Tech Skills

Assing yourself a score in the following technologies:


Object Oriented Programming (OOP) - 9/10

Git -  9/10

PHP 5 - 9/10

CakePHP framework - 9/10

MySQL -  9/10

Javascript - 9/10

jQuery -  9/10

HTML - 9/10

CSS - 9/10

## Questions About OOP:

- How do you declare a function or method that you want to be accessed without instantiate the class?
ANS : we can create static member function for this.

ex :- public static function funcname() 
    {
       //code here
    }

- How do you create a child class of BaseClass ?

ANS:- by extending the base class

ex :-

class basecls
{
	//code here
}
class childcls extends basecls
{
	// code here
}

 
## Questions about GIT:

- If you accidentally add the wrong files to be commited using git add, how do you unstage them?

ANS:- git reset HEAD filename

- If you want to switch to another branch, what command you need to execute?
ANS:- git checkout branchname
 
## Questions about PHP 5:

- Please write a conditional block of code that check if the variable $var exists, is not null and it's a number.
class v_exists
{
	public $var = null;
	public function check_exist()
	{
		if(isset($this->var) && $this->var!=NULL && is_numeric($this->var))
		{
			return true;
		}
		else
		{
			return false;
		}
	}
}
$obj = new v_exists;
$obj->var = 12;
if($obj->check_exist)
{
	echo 'Exists , Not Null, Numeric';
}
else
{
	echo 'Does not Exists or Null or not Numeric';
}

- Write a function that adds a line to a log file the current date and time with this format: "[2013-09-23 00:3 0:15] - Status OK"
ANS :-

$file=fopen("log.txt","a");
$file_contents = "[".date('Y-m-d H:i s:'). substr((string)microtime(), 2, 2);."] - Status OK";
fwrite($file, $file_contents);
fclose($file);
## Questions about CakePHP

- Which is the default path where you set up the configuration for the database?
ANS:- APP . 'Config/database.php'

- How you can get the value of a session variable with key "foo" using CakePHP ?

ANS:- $this->Session->read('foo');

## Questions about MySQL

- Write a single query to retrieve the information from 2 tables that are related( users and users_data) where the primary key on users is ID and the foreign key on users_data is USER_ID.
ANS:- SELECT users.*, users_data.* FROM users INNER JOIN users_data ON users.ID = users_data.USER_ID;

- Write a single query to retrieve all the queries that are currently running on the server .

ANS:- 
SHOW FULL PROCESSLIST;

## Questions about Javascript

- How do access to the alt attribute of the following image element using javascript? <img src='http://example.com/image.jpg' id='some_img' alt='lol' />

ANS:- var alt_image =  document.getElementsById("sime_img").getAttribute("alt");

- What is the protocol name behind ajax?

ANS:- 	Ajax uses HTTP's GET or POST. AJAX also uses XMLHttpRequest protocol for requesting to the web server.
		AJAX uses JSON format to communicate between client and server. UED or URL encoded data formats can also be used.  

## Questions about jQuery

- Write a piece of javascript code using jQuery that make the el ement with id "someElement" to appear on the screen using a fade in effect after the DOM is loaded.

ANS:- $(document).ready(function(){

    	$( "#elementId" ).fadeIn( "slow" );

	});

- How do you remove an element from the DOM using jQuery?
 
 ANS:- $("#elementId").remove();
 
## Questions about HTML

- Which is the doctype syntax for HTML5?

ANS:- <!DOCTYPE html>

- Which is the attribute and value required on forms to allow file uploads?

ANS:- enctype="multipart/form-data"

## Questions about CSS

- Which is the css property and its value to force to hide the scroll on any DOM element with fixed height when its content exceed its own height?

ANS:- overflow-y: hidden;

- If you have to div elements next to each other with the property float:left, which CSS property do you need to add to the next element in order to get both of them to fill the same height on page and make the next one not a floating one?

ANS:- both divs float left, height same and , width has to be devided to both divs according to the total div of the parent div or page width. 

## Questions about Linux / Unix based OS

- Which protocol(s) you could use to connect to a server SHELL remotely?
ssh

ANS:- i use putty to connect to server shell remotely .

- Write a command to look for the word "ads" on all files with .ctp extension in the same directory

ANS:- find . -name "*.ctp" -exec grep -H "ctp" {} \;