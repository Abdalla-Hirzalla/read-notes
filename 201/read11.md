# Chart.js, Canvas

## Charts :
are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create. A great way to get started with charts is with Chart.js, a JavaScript plugin that uses HTML5’s canvas element to draw the graph onto the page. It’s a well documented plugin that makes using all kinds of bar charts, line charts, pie charts and more, incredibly easy.

- **Drawing a line chart** To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart.
- **Drawing a pie chart** Our line chart is complete, so let’s move on to our pie chart.
- **Drawing a bar chart** Finally, let’s add  a bar chart to our page. Happily the syntax for the bar chart is very similar to the line chart we’ve already added.


## Canvas :
At first sight a **canvas** looks like the img element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the **canvas**element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.

As a consequence of the way fallback is provided, unlike the img element, the **canvas** element requires the closing tag (/canvas). If this tag is not present, the rest of the document would be considered the fallback content and wouldn't be displayed.

The fallback content is displayed in browsers which do not support (canvas). Scripts can also check for support programmatically by testing for the presence of the getContext() method.

**Drawing a path:** A path is a list of points, connected by segments of lines that can be of different shapes, curved or not, of different width and of different color. A path, or even a subpath, can be closed. To make shapes using paths, we take some extra steps:

- First, you create the path.
- Then you use drawing commands to draw into the path.
- Once the path has been created, you can stroke or fill the path to render it.

**Colors** If we want to apply colors to a shape, there are two important properties we can use: 
- fillStyle.
- strokeStyle.

**Drawing text** The canvas rendering context provides two methods to render text:

- fillText(text, x, y [, maxWidth]): Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
- strokeText(text, x, y [, maxWidth]): Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.
