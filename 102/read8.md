# summary
## Functions

**Functions** are one of the fundamental building blocks in JavaScript. A function in JavaScript is similar to a procedure—a set of statements that performs a task or calculates a value, but for a procedure to qualify as a function, it should take some input and return an output where there is some obvious relationship between the input and the output. To use a function, you must define it somewhere in the scope from which you wish to call it,The arguments of a function are not limited to strings and numbers. You can pass whole objects to a function. The showProps() function (defined in Working with objects).

A function definition, **also called a function declaration**, or **function statement** consists of the function keyword, followed by:

- The name of the function.
- A list of parameters to the function, enclosed in parentheses and separated by commas.
- The JavaScript statements that define the function, enclosed in curly brackets, {...}.


**Function scope:** Variables defined inside a function cannot be accessed from anywhere outside the function, because the variable is defined only in the scope of the function. However, a function can access all variables and functions defined inside the scope in which it is defined.


### Functions can be multiply-nested ###

** For example:**

A function **(A)** contains a function **(B)**, which itself contains a function **(C)**.
Both functions B and C form closures here. So, B can access A, and C can access B.
In addition, since C can access B which can access A, C can also access A.
Thus, the closures can contain multiple scopes; they recursively contain the scope of the functions containing it. This is called scope chaining. (The reason it is called "chaining" is explained later.

### Function Return ###
- When JavaScript reaches a return statement, the function will stop executing.

- If the function was invoked from a statement, JavaScript will "return" to execute the code after the invoking statement.

- Functions often compute a return value. The return value is "returned" back to the "caller".

**Why Functions?** You can reuse code: Define the code once, and use it many times;
You can use the same code many times with different arguments, to produce different results; Functions can be used the same way as you use variables, in all types of formulas, assignments, and calculations.

### Local Variables ###
- Variables declared within a JavaScript function, become LOCAL to the function.
- Local variables can only be accessed from within the function.
- Since local variables are only recognized inside their functions, variables with the same name can be used in different functions.
- Local variables are created when a function starts, and deleted when the function is completed.