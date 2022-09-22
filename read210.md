# Class 10 Reading

## Debugging

## [What Went Wrong? Troubleshooting](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/First_steps/What_went_wrong)

1. Name some key differences between a Syntax Error and a Logic Error.
- Syntax errors: These are spelling errors in your code that actually cause the program not to run at all, or stop working part way through — you will usually be provided with some error messages too. These are usually okay to fix, as long as you are familiar with the right tools and know what the error messages mean!
- Logic errors: These are errors where the syntax is actually correct but the code is not what you intended it to be, meaning that program runs successfully but gives incorrect results. These are often harder to fix than syntax errors, as there usually isn't an error message to direct you to the source of the error.

2. List a few types of errors that you have encountered in past lab assignments and explain how you were able to correct them.
- using inspect - then the console, you can find where your script is being broken with logic errors - it will tell you down to the line and sometimes it may not be on that line, it will at least get you in the general area. i've had it point to a line before, but the issue was not putting a semi-colon a few lines down to complete the thought.

3. How will this topic continue to influence your long term goals?
- well we are already getting in the good habit of checking the console for various items, and talking with a TA yesterday I was able to manipulate the pagefrom the code to 'play around with it' without messing up the code itself which i thought was helpful

## [JavaScript Debugger](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools#the_javascript_debugger?

1. How would you describe the JavaScript Debugger tool and how it works to someone just starting out in software development?
- The JavaScript debugger allows you to watch the value of variables and set breakpoints, places in your code that you want to pause execution and identify the problems that prevent your code from executing properly.

2. Define what a breakpoint is.
- breakpoint will stop executing, and let you examine JavaScript values. After examining values, you can resume the execution of code (typically with a play button).

3. What is the call stack?
- A call stack is a mechanism for an interpreter (like the JavaScript interpreter in a web browser) to keep track of its place in a script that calls multiple functions — what function is currently being run and what functions are called from within that function, etc.
- At the most basic level, a call stack is a data structure that uses the Last In, First Out (LIFO) principle to temporarily store and manage function invocation (call)
