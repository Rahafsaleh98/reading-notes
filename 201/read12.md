" easily create stunning animated charts with CHART.JA” 

Before, we used Table in order to shown results , but there is something easier called Charts , but In some cases it is not easily to create 

Developers can use this Chart by JavaScript, 
Line chart 

1. we can use this by opening the script tag than “ chart.min.js” then close the script tag 

2. Create a tag named “ canvas” in the body 

3. Then we will getElementbyId

4. In JS we will create data

The canvas element:- 

- We learned about the img element, the canvas is like the image but the difference is a canvas just have “width” and “height” attribute

- We can give context for canvas, it takes one parameter (2D),
[9:01 PM, 2/21/2021] Rahaf Saleh: “ The grid” 
HTML has default wide “150px” and high “150”

Canvas, give two shapes :-

1. Rectangle , and it has three function ;- 

- ”fillRect” :- in order to a filled rectangle

- “strokeRect”:- to draw the outline 

- ”clearRect” :- it's for area 

2. Path “function of it “

- ” beingpath()” it's used to create new path 

- ”closepath()” it's used to add line to the path 

- ”stroke() it's used to draw the shape

MoveTo it's used “to draw unconnected paths” 

lineTo it's used to draw straight line 

ARCS
In order to draw arcs or circle we can use arc or acrTo

Colors:- 
As developers We can use two properties, the first is fillStyle (” it's related for filling shapes “) and stroke style (” it's related to shapes outlines “) 

Line styles 
To make style for the line we can use different properties 
> “lineWidth” it must be positive 
> “lineCap” it can be three values (”butt, round, square”)
>”lineJoin” it can be three values (” round, beval, miter”)
>”miterLimit”
> “getLineDash”
>”setLineDash”
>”lineDashOffset”

*“Drawing Text”* 

For context, canvas includes two methods to render it 

1. fillText 
2. strokeText 

It has different properties:-

- “font”
- ”textAlign” it can be (”start, end , left, center “
- ” textBaseline” it can be (” top, hanging, middle, alphabetic, demographic, bottom”)

- ”direction” it can be (”ltr , rtl, inherit”)