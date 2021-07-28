# Putting it all together

## How would you break a mock into a component heirarchy?

- The first thing you’ll want to do is to draw boxes around every component (and subcomponent) in the mock and give them all names. If you’re working with a designer, they may have already done this, so go talk to them! Their Photoshop layer names may end up being the names of your React components.

- Use the same techniques for deciding if you should create a new function or object. One such technique is the single responsibility principle, that is, a component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller sub components.

- Since you’re often displaying a JSON data model to a user, you’ll find that if your model was built correctly, your UI (and therefore your component structure) will map nicely.

## What is the single responsibility principle and how does it apply to components?

**The single-responsibility principle (SRP)** is a computer-programming principle that states that every module, class or function in a computer program should have responsibility over a single part of that program's functionality, and it should encapsulate that part. All of that module, class or function's services should be narrowly aligned with that responsibility.The argument for the single responsibility principle is relatively simple: it makes your software easier to implement and prevents unexpected side-effects of future changes

## What does it mean to build a ‘static’ version of your application?

- Static apps are simpler, quicker to develop, and cheaper to host. In fact, it’s perfectly feasible to host your entire static app on a CDN.

- Modern JavaScript frameworks like AngularJS can be used to quickly build your site’s front-end, then hooked up to back-end data services like Firebase, allowing you to quickly sketch out what your interface looks like and turn it into a functioning prototype.

- As static apps are essentially just files stored on the web, then sent to the user, they can easily be scaled with off-the-shelf technology, so you can integrate third party services like Google Maps and billing systems through API’s to automate your site. I think Wallace & Gromit demonstrate this quite well:

## Once you have a static application, what do you need to add?

- Step 1: Add Your New Site. ...
- Step 2: Link to Your GitHub (or supported version-control tool of choice) ...
- Step 3: Authorize Netlify. ...
- Step 4: Select Your Repo. ...
- Step 5: Configure Your Settings. ...
- Step 6: Build Your Site. ...
- Step 7: All Done.

## What are the three questions you can ask to determine if something is state?

i don't know write now .

## How can you identify where state needs to live?

Our task now is to identify what information can change as the user interacts with the app, and to represent that information in code as 'state'.  When we're done, the app still won't be interactive, but we'll have defined the bits of data that can change.