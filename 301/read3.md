# Passing Functions as Props

 ### In JavaScript 
 spread syntax refers to the use of an ellipsis of three dots (…) to expand an iterable object into the list of arguments.When (...arr) is used in the function call, it ‘expands’ an iterable object arr into the list of arguments.The spread operator was added to JavaScript in **ES6 (ES2015)**, just like the rest parameters, which have the same syntax: **three magic dots ….**The … spread operator is useful for many different routine tasks in JavaScript, including the following:
-  Copying an array
-  Concatenating or combining arrays
-  Using Math functions
-  Using an array as arguments
-  Adding an item to a list
-  adding to state in React
-  Combining objects
-  Converting NodeList to an array

### What is ... used for?
Spread operator to the rescue! It looks similar to rest parameters, also using (...), but does quite the opposite.Using the (…) spread operator is a convenient way to copy an array or combine arrays, and it can even add new items.


### Math Function 
The Math object's set of functions are a perfect example of the spread operator as the only argument to a function.
One of the best ways to understand the use of spread operator in JavaScript is to look at the the built-in functions Math.min() and Math.max(), which both expect a list of arguments, not an array.


- **Rendering Multiple Components:**
   - You can build collections of elements and include them in JSX using curly braces {}.

- **Basic List Component**
    - Usually you would render lists inside a component.We can refactor the previous example into a component that accepts an array of numbers and outputs a list of elements.   

- **Keys**
    - Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity.

    



