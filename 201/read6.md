 # Object-Oriented Programming, HTML Tables

 ## Domain Modeling:

 Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.


# Tables :
 A table represents information in a grid format.Examples of tables include financial reports, TV schedules, and sports results.

## Basic Table Structure:

The **(table)** element is used to create a table. The contents of the table are written out row by row.
- **(tr)** You indicate the start of each row using the opening (tr) tag.(The tr stands for table row.)It is followed by one or more.
- **(td)** elements (one for each cell in that row). At the end of the row you use a closing (tr) tag.
- **(td)** Each cell of a table is represented using a (td) element. (The td stands for table data.) At the end each cell you use a closing (td) tag.



## Table Headings:
- The (th) element is used just like the (td) element but its purpose is to represent the heading for either a column or
a row. (The th stands for table heading.) 

- Even if a cell has no content, you should still use a (td) or (th) element to represent the presence of an empty cell otherwise the table will not render correctly. (The first cell in the first row of this example shows an empty cell.)
    

## Long Tables:
 There are three elements that help distinguish between the main content of the table and the first and last rows (which can contain different content). These elements help people who use screen readers and also allow you to style these sections in a different manner than the rest of the table (as you will see when you learn about CSS).**(thead)** the headings of the table should sit inside the **(thead)** element. **(tbody)** The body should sit inside the **(tbody)** element. **(tfoot)** The footer belongs inside the **(tfoot)** element. By default, browsers rarely treat the content of these elements any differently than other elements however designers often use CSS styles to change their appearance.



- The (table) element is used to add tables to a web page.
- A table is drawn out row by row. Each row is created with the (tr) element.
- Inside each row there are a number of cells represented by the (td) element (or (th) if it is a header).
- You can make cells of a table span more than one row or column using the rowspan and colspan attributes.
- For long tables you can split the table into a (thead),(tbody), and (tfoot).



# JavaScript Methods
- JavaScript methods are actions that can be performed on objects.A JavaScript method is a property containing a function definition.
- You access an object method with the following syntax:(objectName.methodName())



## **In JavaScript**, almost "everything" is an object.

- **Booleans** can be objects (if defined with the new keyword)
- **Numbers** can be objects (if defined with the new keyword)
- **Strings** can be objects (if defined with the new keyword)
- **Dates** are always objects
- **Maths** are always objects
- **Regular** expressions are always objects
- **Arrays** are always objects
- **Functions** are always objects
- **Objects** are always objects

**All JavaScript values, except primitives, are objects.**