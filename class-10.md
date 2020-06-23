# Read 10 in 201
<br/>

## From the Duckett JS book:

<hr/>

1. JavaScript book, Ch. 10, “Error Handling & Debugging”: 
  * When writing a long script, nobody gets everything right in their first attempt.
  * THE CONSOLE & DEV TOOLS:Tools built into the browser that help you hunt for errors.
  * COMMON PROBLEMS :Common sources of errors, and how to solve them.
  * HANDLING ERRORS :How code can deal with potential errors gracefully. 
  *  some tasks cannot complete until another statement or function has been run , orderd.
  * In the interpreter, each execution context has its own va ri ables object. It holds the variables, functions, and parameters available within it. Each execution context can also access its parent's variables object
  * If a JavaScript statement generates an error, then it throws an exception. At that point, the interpreter stops and looks for exception-handling code
  *  SYNTAX Error SYNTAX IS NOT CORRECT.
  * REFERENCE Error VARIABLE DOES NOT EXIST.
  * EvalError INCORRECT USE OF eval() FUNCTION.
  * URI Error INCORRECT USE OF URI FUNCTIONS.
  * TYPE Error VALUE IS UNEXPECTED DATA TYPE This is often caused by trying to use an object or method that does not exist.
  * RANGE ERROR NUMBER OUTSIDE OF RANGE If you call a function using numbers outside of its accepted range. 
  * There is two  way to deal with errors : DEBUG THE SCRIPT TO FIX ERRORS or HANDLE ERRORS GRACEFULL
  * The JavaScript console will tell you when there is a problem with a script, where to look for the problem, and what kind of issue it seems to be. 
  * You can pause the execution of a script on any line using breakpoints. Then you can check the values stored in variables at that point in time
  * If you know something might cause a problem for your script, you can generate your own errors before the interpreter creates them. 
  <br/><br/>
  ![img](https://data-flair.training/blogs/wp-content/uploads/sites/2/2019/08/JavaScript-Errors.jpg)
