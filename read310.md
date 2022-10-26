## [Understanding the JavaScript Call Stack](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)

1. What is a ‘call’?
- The call stack is primarily used for function invocation

2. How many ‘calls’ can happen at once?
- the call stack is single, function(s) execution, is done, one at a time, from top to bottom. It means the call stack is synchronous.

3. What does LIFO mean?
- Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call)
- the last function that gets pushed into the stack is the first to be pop out, when the function returns

4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.
- `"function firstFunction(){
  console.log("Hello from firstFunction");
}

function secondFunction(){
  firstFunction();
  console.log("The end from secondFunction");
}

secondFunction();"

5. What causes a Stack Overflow?
- A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point. The browser (hosting environment) has a maximum stack call that it can accomodate before throwing a stack error

## [JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

1. What is a ‘reference error’?
- when you try to use a variable that is not yet declared
- the fact that this happens to let and const is called Temporal Dead Zone (TDZ)

2. What is a ‘syntax error’?
- occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse

3.What is a ‘range error’?
- when you try to manipulate an object with some kind of length and give it an invalid length
- arrays cannot have a negative length

4. What is a ‘type error’?
- when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.
- This is probably the most frequent error in JS

5. What is a breakpoint?
- JavaScript will stop executing, and let you examine JavaScript values.
- can also be achieved by putting a debugger statement in your code in the line you want to break.

6. What does the word ‘debugger’ do in your code?
- to force stop the execution of the code at a breaking point and calls the debugging function. The debugger function is executed if any debugging is needed at all else no action is performed

## Bookmark and Review

## [JavaScript errors reference on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)

