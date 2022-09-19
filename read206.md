#Class 206 Notes

## [JavaScript Object Basics](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics)

1. How would you describe an object to a non-technical friend you grew up with?
- An object is a collection of related data and/or functionality. These usually consist of several variables and functions (which are called properties and methods when they are inside objects). Let's work through an example to understand what they look like.


2. What are some advantages to creating object literals?
- It is very common to create an object using an object literal when you want to transfer a series of structured, related data items in some manner, for example sending a request to the server to be put into a database. Sending a single object is much more efficient than sending several items individually, and it is easier to work with than an array, when you want to identify individual items by name.

3. How do objects differ from arrays?
- Objects represent a special data type that is mutable and can be used to store a collection of data (rather than just a single value). objects are best to use when the elements strings (text)
- Arrays are a special type of variable that is also mutable and can also be used to store a list of values. Arrays are best to use when the elements are numbers.	

4. Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.
- When working with bracket notation, property identifiers only have to be a String. They can include any characters, including spaces. Variables may also be used as long as the variable resolves to a String.
- This means there are fewer limitations when working with bracket notation. We can now have spaces in our strings, and can even start strings with numbers.
- Perhaps most importantly, we can now use variables to access properties in an object. It’s important the variable you are using references a String.

5.Evaluate the code below. What does the term `this` refer to and what is the advantage to using `this`?
- The `this` keyword refers to the current object the code is being written inside — so in this case `this` is equivalent to `dog`

## [Intro to the DOM](https://developer.mozilla.org/en-US/docs/Web/API/Document_Object_Model/Introduction)

1. What is the DOM?
- The Document Object Model (DOM) is a programming interface for web documents. It represents the page so that programs can change the document structure, style, and content. The DOM represents the document as nodes and objects; that way, programming languages can interact with the page.

2. Briefly describe the relationship between the DOM and JavaScript.
- The DOM is not part of the JavaScript language, but is instead a Web API used to build websites. JavaScript can also be used in other contexts. For example, Node. js runs JavaScript programs on a computer, but provides a different set of APIs, and the DOM API is not a core part of the Node
- "DOM Scripting" means using JavaScript to manipulate the DOM (page elements and contents) inside a web page, either during page load, or in response to user events, like clicking a button or selecting text.


## Things I want to know more about
using object literals in real world examples vs arrays
