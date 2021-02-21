Chapter 7 “ forms “
The form is related to a printed document that contains spaces for you to fill in the information, its like a search box of Google's homepage 

It can be:- 
1. Adding text 
> text input 
> password input
> text area 

2. Making choices 
> Radio
> Checkboxes
> drop-down boxes

3. Submitting forms
> Submit buttons
> image buttons

4. Uploading files
> file upload

How forms work!
The first user fill the space, then it is sent to the server, after the server processing information by Java, finally, the server creates a new page 

*Form*
Form in HTML it always carry the action attribute then equal URL for the page of the server and method. Method can be either get or post. 

*Text input*
input used for create different form 
**How it work ?**

*UserName*
First write input then type=”text” then name-”username” size that I want it and finally max length.

Password in the same manner, but instead of “text”, “username” > “password” 

*Radio Button* 
Radio allows user to pick just one answer 

*How it write?*
First input then “radio” after that name-”here what you want genre that you would to ask “ then value

*Chapter 14 “list, table, and forms  “*

There are different property that allows you to control the shape of a bullet point (marker) The first is known as life style type 
It used for ordered (decimal, decimal-leading-zero, lower alpha, upper alpha, lower roman, upper roman )list and unorderd list (none, disc, circle, and square) 

The second is known as list-style-image 
How you can add image for bullet number? 
Just you will select ul in CSS file then list style image : URL “  ”

The third is known as life style position 
It can take just one of two values either outside or inside 

> life style it allows to express the markers style , image and position

CSS FOR TABLE:-
1. "Width:- to set the width of the table"

2." Padding:- to set the space between the border of each table cell and its content"

3. "Text-transform:- to convert the content of the table headers to uppercase"

4. "letter-spacing, font-size :- 
to add additional styling to the content of the table headers"

5. "border-top, border-bottom:-  to set borders above and below the table headers"

6. "text-align :- to align the writing to the left of some table cells and to the right of the others"

7. "background-color :- to change the background color of the alternating table rows"

8. "hover:-  to highlight a table row when a user's mouse goes over it"

*Chapter 6 “Events” JS*

1. Select Element
2. Specify Event 
3. Call Code 
“ checkUsename()” 
It will check if the username is less than 5 characters 

There are 3 ways to bind an event to an element:-
1. HTML (we will not use )
2. Traditional Dom event handlers 

Syntax:- 
Element.Event = functionName 

Javascript 
1. Declare function 
 A. Get feedback element 
 B. If the value too short set a message otherwise clear message 
2. Get userName input
3. When it loses focus call checkUsername