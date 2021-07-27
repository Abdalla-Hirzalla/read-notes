# React and Forms

# Forms
**HTML form elements work a bit differently from other DOM elements in React, because form elements naturally keep some internal state. and The (FormControl) component renders a form control with Bootstrap styling. The (FormGroup) component wraps a form control with proper spacing, along with support for a label, help text, and validation state. To ensure accessibility, set controlId on (FormGroup), and use (FormLabel) for the label.**



## what is the Controlled Components ??
## Controlled Components


In HTML, form elements such as (input), (textarea),  (select) typically maintain their own state and update it based on user input. In React, mutable state is typically kept in the state property of components,and only updated with setState()
We can combine the two by making the React state be the “single source of truth”. Then the React component that renders a form also controls what happens in that form on subsequent user input. An input form element whose value is controlled by React in this way is called a “controlled component”.

- **The select Tag** In HTML, (select)  tag creates a drop-down list.
- **The file input Tag** In HTML, an (input type="file") lets the user choose one or more files from their device storage to be uploaded to a server or manipulated by JavaScript via the File API.

- **Handling Multiple Inputs** When you need to handle multiple controlled input elements, you can add a name attribute to each element and let the handler function choose what to do based on the value of (event.target.name).

- **Controlled Input Null Value** Specifying the value prop on a controlled component prevents the user from changing the input unless you desire so. If you’ve specified a value but the input is still editable, you may have accidentally set value to undefined or null.

- **Alternatives to Controlled Components** It can sometimes be tedious to use controlled components, because you need to write an event handler for every way your data can change and pipe all of the input state through a React component.


- **Fully-Fledged Solutions**If you’re looking for a complete solution including validation, keeping track of the visited fields, and handling form submission, Formik is one of the popular choices.





## Conditional Rendering
**In React**, you can create distinct components that encapsulate behavior you need. Then, you can render only some of them, depending on the state of your application.Conditional rendering in React works the same way conditions work in JavaScript. Use JavaScript operators like if or the conditional operator to create elements representing the current state, and let React update the UI to match them.

