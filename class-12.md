# Chart.js

Charts are far better for displaying data visually than tables and have the added benefit that no one is ever going to press-gang them into use as a layout tool. They’re easier to look at and convey data quickly, but they’re not always easy to create.

- Setting up:
The first thing we need to do is download Chart.js. Copy the Chart.min.js out of the unzipped folder and into the directory you’ll be working in.
 - Drawing a line chart
 To draw a line chart, the first thing we need to do is create a canvas element in our HTML in which Chart.js can draw our chart. So add this to the body of our HTML page.
 - Inside the same script tags we need to create our data, in this instance it’s an object that contains labels for the base of our chart and datasets to describe the values on the chart.

 * Drawing a pie chart
 -  we need the canvas element.
 - we need to get the context and to instantiate the chart.

![chart](https://i.ytimg.com/vi/gpkBkLf_f2I/maxresdefault.jpg)
___________
## canvas:
![](https://i.ytimg.com/vi/5O4KVLX6KL4/maxresdefault.jpg)
At first sight a <canvas> looks like the <img> element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the <canvas> element has only two attributes, width and height.
<canvas id="stockGraph" width="150" height="150">
  current stock price: $3.15 + 0.15
</canvas>

<canvas id="clock" width="150" height="150">
  <img src="images/clock.png" width="150" height="150" alt=""/>
</canvas>

- **Drawing rectangles**
supports two primitive shapes: rectangles and paths (lists of points connected by lines). All other shapes must be created by combining one or more paths. Luckily, we have an assortment of path drawing functions which make it possible to compose very complex shapes.
-  Draws a filled rectangle.
fillRect(x, y, width, height)
 - Draws a rectangular outline.  
strokeRect(x, y, width, height)
  -  Clears the specified rectangular area, making it fully transparent.  
clearRect(x, y, width, height)

* Drawing paths

- beginPath()   Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.
- Path methods  Methods to set different paths for objects.
- closePath()  Adds a straight line to the path, going to the start of the current sub-path.
- stroke()Draws the shape by stroking its outline.
- fill()  Draws a solid shape by filling the path's content area. 

* Drawing a triangle

    function draw() {
  var canvas = document.getElementById('canvas');
  if (canvas.getContext) {
    var ctx = canvas.getContext('2d');

    ctx.beginPath();
    ctx.moveTo(75, 50);
    ctx.lineTo(100, 75);
    ctx.lineTo(100, 25);
    ctx.fill();
  }
}

### Drawing text

The canvas rendering context provides two methods to render text:

fillText(text, x, y [, maxWidth])
    Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.
strokeText(text, x, y [, maxWidth])
    Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw. 
![](https://images1.programmersought.com/79/28/28e3532711b9f8ac8e5847d58b8c1707.png)




[Back to homw page](https://rahafalbakkar.github.io/Code-201-Reading-Notes)