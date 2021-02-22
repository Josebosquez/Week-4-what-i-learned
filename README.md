# Week-4-what-i-learned
Week-4 what i learned
# What I learned In Week 4 at Code Immersives

### Introduction

In this README file I try to simply explain the concepts I learned in week 4 at Code Immersives.

---------------------------------------------------------------------------
This week we learned how to continue with basic Javascript (JS) by understanding functions, strings, booleans, return, and if statements. 

This weeks assignments are :
- Functions Ahoy
- Functions with parameters
- The Function Returns
- Return of the string
- Codewars - abbreviate a two word name
- stop calling yourself/ stop calling yourself
- foolin with booleans
- code wars odd or even
- if learning
---------------------------------------------------------------------------

### Functions

Functions are statements that conduct tasks or calculates a value between variables in a relationship. These variables are able to be manipulated in order to achieve different results without going back and changing the original line of text for a specific piece of code. Functions must have names; names must be lowercase and must not contain spaces between them. Additionally, you must capitalize the letters  if they are different words. Parameters are the names or titles you give in order to manipulate your variables.
* `- Examples`: How to write a function
Let x = 5;
X; 5
Let x = 10;
X = 10;
X = x + 10
X; 20

Function (nameOfWhatYouWantToDo) (parameters go here) {
X = x + 5;
}


### Strings

Strings are words or characters (like numbers) that are used to make up a sentence. They must all be separated by commas, and go between parenthesis' and are contained by quotation marks.
* `- Example` - a name, a number, a abbreviated word.

* `- Strings` have characteristics or attributes that can be used to define or store part of a value. An example is length, measures the amount of characters and spaces in a string. 
* `- Indexes` - counts characters in a string starting with 0. it will return undefined when you go past the character amount. Must have [# or character]. The last character is always at the index: *.length - 1*.

* `Example` : getFirstCharacter - it takes in a parameter of type String and returns only the first character from it. Hint: use an index!

* `Answer` : function getFirstCharacter(string1){
string1 = string1[0];
return string1;
}


---------------------------------------------------------------------------
### Booleans 

Javascript (JS) is high level interpreted scripting language that conforms to ECMAScript specification.

Gives us the animation to the skeleton. Tells us how it will move or functions.

This link goes at the end of the body.

* `How to link external JS`
	<script src. (opening tag) = "script.js" (JS file)></script> (Closing tag)

* `Internal JS with html`
<script> (your JS code goes inside this script tag) </script>. Also it can go inside the body tag all the way in the end before the closing tag </body>

#### Variables 
  - JavaScript variables are containers for storing data values.
  - Creating a variable in javascript is called declaring a variable; you declare a javascript variable with the keywords: let, const, or var (but we don’t use var).

#### JS primitive data types
* `Strings` - string of letters or numbers used to form paragraphs or sentences.
- Written with quotes. You can use single or double quotes. 
	- Let name = 'hello world'
	- Const name = 'hello world'
	- Let name = "hello world"
	- Const name = "hello world"
* `Numbers` - actual numbers that can be written with, or without decimals. 
	- Let age = 2
	- Const age = 2.5
* `Booleans` - true and false question answers.
* `NaN` - did not cover
* `Null` - did not cover
* `Undefined` - a variable that has no value. 

#### Console.log
* `Console.log` allows us to "run" our variables. 
    ('hello world;).   hit control+c anytime to enter repl.
<Cant give a console.log (name) before it happens.>

- Let greeting (greeting is the variable) = 'hello world'
- If we run Console.log (greeting {value}) - will be a value if not surrounded by quotation marks.

* `In order for a variable to have a value, it must not have quotes.`
* `Semi-colons` - are not necessary unless the group/team wants them.
* `Quokka` - in order to see certain changes, it is at times recommended to turn on/off Quokka.
* `Reassigning a variable` Numbers don't work as regular math. The variables are given value by the value and by the order of sequence.  
    - let a = 1
    - let b = 1
    - a = b + 1 (a = 1 + 1) {2 = 1 + 1}
    - the value of a is now 2. 


### Summary
In order to maintain a reactive web-browser, it is vital in early development to understand the basics of Javascript. It will work hand in hand with HTML and CSS to allow users to manipulate the browser update material and provide animations. Git is an important tool to review previous changes created by the developers. This allows them to find bugs or errors without having to worry about saving their progress because they save it as they go.