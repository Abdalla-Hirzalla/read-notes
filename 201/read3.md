# HTML Lists, Control Flow with JS, and the CSS Box Model

# Lists :

- HTML elements are used to describe the structure of
the page (e.g. headings, subheadings, paragraphs).
-  They also provide semantic information (e.g. where
emphasis should be placed, the definition of any
acronyms used, when given text is a quotation).

The **address** element has quite a specific use: to contain contact details for the author of the page.
It can contain a physical address,but it does not have to. For example, it may also contain a
phone number or email address.
Browsers often display the
content of the address element in italics.

The **ins** element can be usedto show content that has been inserted into a document, while the **del** element can show text that has been deleted from it.


The **S** element indicates something that is no longer accurate or relevant (but that should not be deleted) Visually the content of an **S** element will usually be displayed with a line through the center.

# Boxes
At the beginning of **Boxes** on CSS,you saw how CSS treats each HTML element as if it lives in its own box ;By default a box is sized just big enough to hold its contents. To set your own dimensions for a box you can use the **height** and **width** properties.The most popular ways to specify the size of a box are to use pixels, percentages, or ems. Traditionally, pixels have been the most popular method because they allow designers to accurately control their size.


## Width
Some page designs expand and shrink to fit the size of the user's screen. In such designs, the **min-width** property specifies the smallest size a box can be
displayed at when the browser window is narrow, and the
**max-width** property indicates the maximum width a box can stretch to when the browser window is wide.
These are very helpful properties to ensure that the content of pages are legible (especially on the smaller screens of handheld devices).

## Height
In the same way that you might want to limit the width of a box on a page, you may also want to limit the height of it. This is achieved using the **min-height**
and **max-height** properties. 


## Overflow 
If the box is **not big enough** to hold the content, and the content expands outside the box it can look very messy. To control what happens when there is not enough space for the content of a box, you can use the **overflow** property. The overflow property tells the
browser what to do if the content contained within a box is larger than the box itself. It can have
one of two values: 

- **hidden** This property simply hides any extra content that does not fit inthe box.
 
- **scroll** This property adds a scrollbar to the box so that users can scroll to see the missing content.

{source :Duckett HTML book}

# JavaScript Loops 
Loops are handy, if you want to run the same code over and over again, each time with a different value Often this is the case when working with arrays.

## Different Kinds of Loops :
- for - loops through a block of code a number of times
- for/in - loops through the properties of an object
- for/of - loops through the values of an iterable object
- while - loops through a block of code while a specified condition is true
- do/while - also loops through a block of code while a specified condition is true





