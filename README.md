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

Booleans are used as true or false statements/values using the variables and parameters you provide. These variables must have a relationship in order for them to be true or false. 

* `Example: ` Let bool1 = true.    Let bool2 = false.
  

* `Comparison operator/binary operator` compares the values that you have given it and give you a true or false answer. In this case, the current time is 5. The variable (should i wake) uses the value of 5 and less than 6 to see if you should wake up. The answer is no, you should not wake up.
Const currentTime = 5
Const shouldIWake = currentTime < 6 
shouldIWake; False

A math operator is going to take two numbers and give you back 1 number.
A binary operator for two.
* `Double or Triple (=)` - is comparison operator. Comparing two things not equaling to things. Double is somewhat true or close enough.

- using the example above, 
Const alarmSetFor = 7;
Const isAlarmGoingOff = currentTime == alarmSetFor;
isAlarmGoingOff; true

- Const result = "8" == 8; true
Const result = "8" === 8; false

* `% = Mod` - mod divides the number. Example Num % 2 === 0 means that if it is divisible by 2 and equals 0 its even. If not its odd.
!== not equal

A logical operator and only if both things are true
Const hasMoney = false;
Const isHungry = true;
Const shouldIGoOutToEast = hasMoney && isHungry;
shouldIGoOutToEat; false
---------------------------------------------------------------------------

#### If Statements
  - If statements are used to make additional actions without the need to create extra lines or functions. If this doesnt work, then do this action, or the next action. These actions will be separated by {} and will have the word if or else. 
* `Example` 
Const grade = 40;
If (grade < 60) {
Console.log("F!")
Console.log("(Oops!)")
If (grade >= 60) {
Console.log("P") ----P!
Console.log("Yay!") ----Yay!

* `Example` 
function instructorHeight (string) {
if (string == "Colin"){
return 62
} 
if (string == "Mesuara"){
return 69
}
else return "I don't know that instructor!"
}
---------------------------------------------------------------------------

#### Return
Is basically the same thing as console.log but it returns the value of a variable from the given function .

* `Example` 
Function name(x, y) {
	Return x + y;
}

### Summary
In order to maintain a reactive web-browser, it is vital in early development to understand the basics of Javascript. It will work hand in hand with HTML and CSS to allow users to manipulate the browser update material and provide animations. Git is an important tool to review previous changes created by the developers. This allows them to find bugs or errors without having to worry about saving their progress because they save it as they go.