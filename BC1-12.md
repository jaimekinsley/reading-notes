### EASILY CREATE STUNNING ANIMATED CHARTS WITH CHART.JS
(https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/)

* Chart.js is a JavaScript plugin that uses HTML5's canvas element to draw the graph onto the page.  
* To draw a line chart:  
1. Create a canvas element in HTML `<canvas id="buyers" width="600" height="400></canvas>`  
1. Write a script to retrieve the context of the canvas  
1. Create data inside of the script tags  

* To draw a pie chart:  
1. Create the canvas element  
1. Get the content and instantiate the chart  
1. Create the data (just a value and color for each section)  
1. Add options to remove the stroke from the segments and animate the scale of the pie  

* To draw a bar chart:  
1. Create the canvas element  
1. Retrieve the element and create the graph  
1. Add in the bar chart's data  

### Basic usage of canvas  
(https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Basic_usage)  

* `<canvas>` element has only two attributes (height and width)  
* `<canvas>` elements can be styled just ike any normal image  
* Use fallback content in case the browser doesn't support canvas  

### Drawing shapes with canvas
(https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Drawing_shapes)

* Before we can draw, we have to determine the grid or coordinate space  
* The origin is in the top left corner (0,0)  
* Canvas supports two primitive shapes: rectangles and paths  

### Applying styles and colors
(https://developer.mozilla.org/en-US/docs/Web/API/Canvas_API/Tutorial/Applying_styles_and_colors)

* You can apply color with both `fillStyle = color` and `strokeStyle = color`  
* We can also draw semi-transparent shapes with `globalAlpha = transparencyValue`  
* The lineWidth property sets the thickness of the line.  

### Drawing text
(https://canvas.instructure.com/courses/1850613/discussion_topics/8658368?module_item_id=29346030)

* `fillText(text, x, y [, maxWidth])` Fills a given text at the given (x,y) position. Optionally with a maximum width to draw.  
* `strokeText(text, x, y [, maxWidth])` Strokes a given text at the given (x,y) position. Optionally with a maximum width to draw.  
* You can style the text using font, textAlign, textBaseline, and direction.  
