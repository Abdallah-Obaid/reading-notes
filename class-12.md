# Read 12 ~ Docs for the HTML canvas Element & Chart.js
> By Abdallah obaid

**NAME** | **URL**
------------------ | -------------
Home    | [Home](https://abdallah-obaid.github.io/reading-notes/).
 Read 01     | [Introductory HTML and JavaScript](https://abdallah-obaid.github.io/reading-notes/class-01).
 Read 02     | [HTML Text, CSS Introduction, and Basic JavaScript Instructions](https://abdallah-obaid.github.io/reading-notes/class-02).
 Read 03     | [HTML Lists, CSS Boxes, JS Control Flow](https://abdallah-obaid.github.io/reading-notes/class-03).
 Read 04     | [HTML Links, CSS Layout, JS Functions](https://abdallah-obaid.github.io/reading-notes/class-04).
 Read 05     | [HTML Images; CSS Color & Text](https://abdallah-obaid.github.io/reading-notes/class-05).
 Read 06     | [JS Object Literals; The DOM](https://abdallah-obaid.github.io/reading-notes/class-06).
 Read 07     | [HTML Tables; JS Constructor Functions](https://abdallah-obaid.github.io/reading-notes/class-07).
 Read 08     | [More CSS Layout](https://abdallah-obaid.github.io/reading-notes/class-08).
 Read 09     | [Forms and Events](https://abdallah-obaid.github.io/reading-notes/class-09).
 Read 10     | [JS Debugging](https://abdallah-obaid.github.io/reading-notes/class-10).
 Read 11     | [Assorted Topics](https://abdallah-obaid.github.io/reading-notes/class-11).
 Read 12     | [Docs for the HTML canvas Element & Chart.js](https://abdallah-obaid.github.io/reading-notes/class-12).
 Read 13     | [Local Storage](https://abdallah-obaid.github.io/reading-notes/).
 Read 14a    | [CSS Transforms, Transitions, and Animations](https://abdallah-obaid.github.io/reading-notes/).
 Read 14b    | [What Google Learned About Teams](https://abdallah-obaid.github.io/reading-notes/).

# Canvas:-
----------------------------------
* At first sight a `<canvas>` looks like the `<img>` element, with the only clear difference being that it doesn't have the src and alt attributes.
* The `<canvas>` element has only two attributes, width and height.
* The canvas will initially be 300 pixels wide and 150 pixels high. 
* The `<canvas>` element can be styled just like any normal image (margin, border, background…).
* Before we can start drawing, we need to talk about the canvas grid or coordinate space.
* There are three functions that draw rectangles on the canvas:
>fillRect(x, y, width, height)
 >Draws a filled rectangle.
>strokeRect(x, y, width, height)
 >Draws a rectangular outline.
>clearRect(x, y, width, height)
 >Clears the specified rectangular area, making it fully transparent.
* If we want to apply colors to a shape, there are two important properties we can use: fillStyle and strokeStyle.
>fillStyle = color
 >Sets the style used when filling shapes.
>strokeStyle = color
 >Sets the style for shapes' outlines.
* The canvas rendering context provides two methods to render text:
>fillText(text, x, y [, maxWidth])
 >Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
>strokeText(text, x, y [, maxWidth])
 >Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.
![Canvas](https://miro.medium.com/max/960/1*IGKCnfK8dHAWo2z-z9A4pA.gif)



