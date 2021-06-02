# Error Handling & Debugging 

## Errors:
When executing JavaScript code, different errors can occur. Errors can be coding errors made by the programmer, errors due to wrong input, and other unforeseeable things.The throw statement allows you to create a custom error.
Technically you can throw an exception (throw an error).The exception can be a JavaScript String, a Number, a Boolean or an Object.

- The **try** statement lets you test a block of code for errors.

- The **catch** statement lets you handle the error.

- The **throw** statement lets you create custom errors.

- The **finally** statement lets you execute code, after try and catch, regardless of the result.

## Errors name values :
  
  - EvalError	
  - RangeError	
  - ReferenceError	
  - SyntaxError	
  - TypeError	
  - URIError	




## Debugging :
Programming code might contain syntax errors, or logical errors. Many of these errors are difficult to diagnose.
Often, when programming code contains errors, nothing will happen. There are no error messages, and you will get indications where to search for errors.Searching for (and fixing) errors in programming code is called code debugging.If your browser supports debugging, you can use console.log() to display JavaScript values in the debugger window.

**The debugger Keyword** : The debugger keyword stops the execution of JavaScript, and calls (if available) the debugging function. This has the same function as setting a breakpoint in the debugger. If no debugging is available, the debugger statement has no effect.With the debugger turned on, this code will stop executing before it executes the third line.

**Debugging** is the process of testing, finding, and reducing bugs (errors) in computer programs.
The first known computer bug was a real bug (an insect) stuck in the electronics.




{source:w3schools}.