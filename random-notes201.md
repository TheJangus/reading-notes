cd = change directory
ls = list, contents in folder i am currently in
mkdir = make directory/folder
touch = makes a new file "tocuh nerfile.md"
cd ... = change directory back two levels // levels= #dots - 1


git status = what changes it can see

A-C-P = Add - Commit - Push  // process for saving your LOCAL changes and sending them to github
A = Add = git add (name of file)
git add .   = all files
C = Commit = git commmit -m "your commit message/why goes here" // snapshot/ save-as
P = Push = git push origin main

Bring changes from github down to computer
PULL = git pull origin main

Local = copy of the repository on your computer
Remote = copy of the repository on GitHub

git clone <paste-your-link> = brings repo from Github to computer

crtl+c = when have error and no control of terminal/commmand line



HTML

hyper text markup language
front end
text/content
basic structure/content/core

READ 4
Wireframe and Design
https://careerfoundry.com/en/blog/ux-design/how-to-create-your-first-wireframe/
Wireframe - physical hand drawn or Digital - simple sketch of plan/design/layers for the information heirarchy
how to organise the content / first thing user sees / main message
clarity / confidence / simplicity is key

Mozilla HTML Basics
https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/HTML_basics
opening tag - content - closing tag = element
attribute in opening tag, space between
 attribute name="attribute value"


Semantics
https://developer.mozilla.org/en-US/docs/Glossary/Semantics
the meaning of a piece of code // what purpose or role does that element have


HTML Docs
https://developer.mozilla.org/en-US/docs/Web/HTML

HTML Elements
https://developer.mozilla.org/en-US/docs/Web/HTML/Element


CSS
Cascading Style Sheet
Styling of a website
Curly braces/brackets
make rules for different elements
can select by class or ID
READING
What is CSS
https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS

CSS is a language for specifying how documents are presented to users — how they are styled, laid out, etc
inside braces are 'declarations'
language is broken down into modules
"As a newcomer to CSS, it is likely that you will find the CSS specs overwhelming — they are intended for engineers to use to implement support for the features in user agents, not for web developers to read to understand CSS. "
Browser compatibility is important

How to Add CSS
https://www.w3schools.com/css/css_howto.asp
-External CSS = whole site
-Internal CSS = individual page 
-Inline CSS = individual element *do not use*

CSS Reference
https://developer.mozilla.org/en-US/docs/Web/CSS/Reference

selector {property: value;}

JAVASCRIPT
utilizes functions
frontend & backend
functionality /  what you do

READING 06:
Dynamic Web Pages w/ JavaScrcipt

JS Intro 
https://developer.mozilla.org/en-US/docs/Web/JavaScript
lightweight programming language

Input Output in Plan JavaScript
https://code-maven.com/input-output-in-plain-javascript




WRONG
a {
  text-decoration: hidden;
  color: hsla(110, 50%, 45%, 1);
}



make notes -- ctrl


editor.wordwrap


<!DOCTYPE html>   ((short hand----emit))

css rule - the whole thing // declaration
camelCasing - html
kabob-casing

code block {
}
use strict

cantatination string + .. ('cool' + userResponse);
string template literal alert(`hello ${userResponseOne} welcome to my page!`)


- loosely typed = we dont need to know the type of data to use/declare a variable
- dynamic language = we can change the data type after a variable has been declared

## data types

### String
- sequence of characters used to represent text, weitten in single quotes
- `'hello'`      ' ' is the only falsey value (empty string)

### Numbers 
- numberical type
- full numbers, decimals, negatives

### Booleans
- logical data type
- 'true' or 'false'
- truthy/falsey    0 is the only falsey value

## Undefined
- it hasn't been defined yet

### Null
- it is defined as none  


## comparison operators
>=, <=, >, <, 
=== (strictly equals) <---what we use
== loosely equals or comparative equals
!= loosely not equal
!== strictly not equal

## Logical Operators
and - &&
or - ||
! - NOT - opposite of whatever it is in front of (BANG)


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


Arrays
- data type // Data Struture *special type of object*
- A collection or list of elements

- dont have to determine the size of the array
- Every element has a position in the array = referred to as its index
  - - zero based index

- have built in methods!
  - - `.push()` - allows us to add elements to our array the the end
  - - `.pop()` - remove the lsast element in the array

- array property
  - - `.length`  - this is going to tell how many elements live in the array

## Loops

###For

- great for looping/iterating and doing something for a certain number of times
- great for looping through arrays! (arrays have a length)


###While

- Doing something until a conditon is no longer true
- Beware of infinite loops!




question 3 is going to need a nested loop


## Functions

- a data type!
### what is it?

- a reusable piece of code
- a group of statements that perform a task or calculate a value stored in a structure that prevents them from running until the function is 'called' or 'invoked'
  - input -> processing -> output

### why do we use them?

- reusable
- easier to read 
- efficiency
- keeps our code dry - DONT REPEAT YOURSELF
- prevents bugs
- perform actions!

### 2 step process

- DEFINE/DECLARE
- CALL/INVOKE                                                   


## Objcects

## What are they?

- Data type // data structure
- convenient & powerful way to group data and functions
- comma separated key/value pairs
- functions that are stored in objects are referred to as methods


## DOM Manipulation

-'The DOM' = Document Object Model
- HTML and CSS come together in the browser - JS read this as an object

### Step for DOM Manipulation in JS

- JS needs a window into your HTML or into the DOM

# Class 7 
## Constructors

### What are they?

- A special type of function
 - Instantiate objects for us
 - acts like a blueprint/'factory' for objects
 - starts with the keyword `function`

### Why?

- keep our code dry
- help us prevent bugs
- give us more unified/uniform objects

## Prototypes

- Inherits === prototype


for(let i = 0, i < numsArr.length; i++)[
let total = 0;
for(let j = 0; j <numsArr[i].length; j++)


# Class 09 Notes

## Events

### Browser Event Types
- click
- submit (when a form button is clicked)
- hover
- mouseover
- page load

## JavScript - code: Event Listener
- code will be triggered when the event has fired/raised
 -- Targets some HTML element that it listens to
'let my container.document.getElementbyID'my-container');'

- Specify the type of event to listen to
- Specify what function is called

'mycontainer.addEventListener('click', handleClick):`

## JS - Code: Event Hamndler - Callback Function
'function handleClick(){
//do some cool stuff
}`


# Class 10 Lecture Notes

## Ways to Debug

- console.log
- repl
- terminal errors using git//github
- debugging tool
- linter - reading linter errors
- control f -- finding variable in code & making sure you're using them corerctly
- rubber duck
- using peers



# Class 11 Grid
1fr = 1 fraction of the space equally


# Class 13 Lecture Notes

## Data Persistance

### Local Storage
- Stored on our hard drives
- No expiration until you clear your local storage

- Code Fellows Journey
 - 201: Local Storage
 - 301: In-memory "Cache" & NoSQL - MongoDB
 - 401: SQL - Postgres

## Why?

- Application State between page refreshes
- Good for testing non-senstive data before storing it in our cloud database

## How it is stored
- Data is stored as a string
- JSON - JavaScript Object Notation
- `JSON.stringify();`

### Methods
- `localStorage.setItem(key,value)`
- `localStorage.getItem(key)`
- `localStorage.clear()~
- `localStorage.removeItem(key)`

### Retreiving Local Storage....continue
-`JSON.parse()` - reconvert what was stored into data that will work
