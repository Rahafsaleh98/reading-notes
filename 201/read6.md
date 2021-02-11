*Chapter 3 " object literals"* 

**What is an object ?**

- object is a set of variables and functions to creat a model or something 

- variables & function are take on new names 
Variables can be part of variables and in this case it called property ,and the function is called method 

**How we can creating an object ?** 
There is something called **literal notation**, and this is the easiest way to creat objects

Accessing an object and dot notation
You can access methods of an object by using dot notation

 *Chapter 5 " Document object model"*
(DOM) specifies how browsers should creat a model of an HTML and how JavaScript cab access the content .

There is something called node , each node is an object with methods and properties . JavaScript update the DOM tree 
DOM can be either attribute nodes ,or text nodes 

**How we can working with the DOM tree ?**
1- access the elements 
2- work with those elements 

There are methods that find elements is called DOM quires 

Selecting an element from a nodelist
There are two ways to select an element from a node list
- the item () way
- array syntax way
Array way is better than the item ()
Because it is faster
Pepeating actions for an enter nodelist 
You can use loop if you have a Nodelist , you can loop each node in the collection and apply the statements to each .

*Adding or removing HTML content*
There are two different approaches to adding and removing content from a DOM :- 
The first:- inner HTML 
> It can used for any element code 
> it is used both to retrieve content 
To add a new content :- 
> store new content 
> select the element 
> set the elements innerHTML
To removing content:-
> you can remove all content by set innerHTML to an empty string 
The second:- DOM manipulation
*Attribute nodes* 
If you have an element code , you can use properties and method on that element node  to access it and change its attribute. 

Summary:-
1. The browser represents the page using a DOM tree.
2. DOM trees have four types of nodes: document nodes,
element nodes, attribute nodes, and text nodes.
3. You can select element nodes by their id or cl ass
attributes, by tag name, or using CSS selector syntax.
4. Whenever a DOM query can return more than one
node, it will always return a Nadel i st.
5. From an element node, you can access and update its
content using properties such as textContent and
i nnerHTML or using DOM manipulation techniques.
6. An element node can contain multiple text nodes and
child elements that are siblings of each other.
7. In older browsers, implementation of the DOM is
inconsistent (and is a popular reason for using jQuery).
8. Browsers offer tools for viewing the DOM tree