 *Chapter 2 “ Text”*
When everyone needs to make a web page, he/she add tags. 

**These tags are used to provide an extra meaning.**

1. Heading tag  :- it has six levels from 1 to 6 

2. Paragraph tag :- it used for add paragraph in body 

3. Bold tag 

4. Italic tag 

5. Superscript tag :- usually used for suffixes of data.

6. Subscript tag :- usually used with footnotes or chemical formulas


 
Here in the list we have different elements :- 

> To add line breaks in HTML, You can use br/ tag 

> To add horizontal rules , you can write this tag hr/ tag

> To write strong emphasis to any word you need, you can use strong tag

> to make one word italic you can use before it em tag



**In HTML we have two elements that used in marking up quotations:-**

The first is blockquote tag it mainly used for long quotes.
 The second is q tag it used for short quotes

cite tag it can be used to indicate where the citation is form 

dfn tag it can use to indicate the defining instance of a new term

address tag it can use to contain a phone number or email

ins tag it can use to show content 

del tag it can use to show text that has been deleted 

s tag it can use to something that is no longer relevant



 Chapter 10 “introducing CSS”

CSS allows creating of a different style to the HTML 
There are two ways to add CSS for HTML. The first is External, we can add external CSS by adding <link herf =” name of folder” 
The second is Internal and we can open tag <style> and write all CSS we need then close the tag .

**In CSS we have something called Selector** 
*Types of selecors :-* 
1. Universal Selector :- (*) selects all HTML elements on the page.

2. Type Selector :- Matches element names

3. Class Selector :- Selects all elements with class="intro" 

4. ID Selector :- is used to select the HTML element using the ID attribute to apply a style to it

5. Child Selector :- Matches an element that is a direct child of another 

6. Descendant Selector :- Matches an element that is a descendent of another specified element. 

7. Adjacent Sibling Selector :- Matches an element that is the next sibling of another

8. General Sibling Selector :- Matches an element that is a sibling of another, although it does not have to be the directly preceding element



*Chapter 2: “Basic JavaScript Instructions”*

> Statements:- is an instruction that a computer can follow one-by-one each instruction are known as a statement, and it must end with a semicolon. 

> Comments:- in JavaScript, we use comments to explain what the code does, so they make code easier and understandable. It can either multi-line or single line.


*what is variable ?* 
Variables are containers for storing data values. 


*How to declare variables ?*
Variable keyword   variable name ;

Javascript has Data types:- 
1. Number = it does mathematics 
2. String = consist of letters and characters 
3. Boolean = it's can be only True or false 

It also has Expression 
Types of expression :-
1. Expression that just assigns a value to a variable.
2. Expression that uses two or more values to return a single value.
Expression rely on the thing known as operators 
Operators can be:- 
1. Assignment 
2. Comparison 
3. Arthamatic 
4. Logical
5. Single



*Chapter 4: “Decisions and Loops”* 

In some cases, Javascript code can take more than one path which means the browser runs different situations 
To decide which path to take it relies on three things :- 

1. Evaluation 
2. Decision 
3. Loops

**There are two components to a decision :-** 
1. Evaluation of a condition
2. Conditional statements 

**Comparison operators** 
== is equal to
!= is not equal to 
=== strict equal to
!== strict not equal to 
> greater than
< less than
>= greater than or equal
<= less than or equal

**Logical operators** 
&& logical and
| | logical or
! logical not 


**If statement :-**  
if statement can be followed by an optional else statement, which executes when the Boolean expression is false.
Syntax :- 
example :- if(boolean_expression) {
    statement(s) will execute if the boolean expression is true
} else {
    statement(s) will execute if the boolean expression is false 
}

**while loop**
A while loop is a control flow statement that allows code to be executed repeatedly based on a given Boolean condition. The while loop can be thought of as a repeating if statement.
Syntax :
while (boolean condition)
{
   loop statements...
}

**for loop** 
For loop provides a concise way of writing the loop structure. Unlike a while loop, a for statement consumes the initialization, condition and increment/decrement in one line thereby providing a shorter, easy to debug structure of looping.
Syntax: for (initialization condition; testing condition; 
increment/decrement)
{
    statement(s)
}