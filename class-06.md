
## WHAT IS AN OBJECT? 

- Objects group together a set of variables and functions to create a model
of a something you would recognize from the real world. In an object,
variables and functions take on new names. 

### IN AN OBJECT: VARIABLES BECOME KNOWN AS PROPERTIES

- If a variable is part of an object, it is called a
property. Properties tell us about the object, 

### IN AN OBJECT: FUNCTIONS BECOME KNOWN AS METHODS

- If a function is part of an object, it is called a method.
Methods represent tasks that are associated with the object

### CREATING· OBJECTS USING LITERAL NOTATION 

-This example starts by creating an object using literal notation.
This object is called hotel which represents a hotel called Quay
with 40 rooms (25 of which have been booked). 

                    var hote l = {
                    name: 'Quay',
                    rooms: 40,
                    booked : 25,
                    checkAvailability: function() {
                    return this.rooms - this.booked;
                    }
                    } ;

                    var el Name = document .getElementByld('hotelName');
                    elName.textContent =hotel .name;
                    var elRooms = document.getElementByid{'rooms');
                    elRooms.textContent = hotel .checkAvailability(); 

## Document Object Model (DOM)

- The Document Object Model (DOM) specifies how browsers should create 
a model of an HTML page and how JavaScript can access and update the contents of 
a web page while it is in the browser window. 

### THE DOM TREE IS A MODEL OF A WEB PAGE 

- As a browser loads a web page, it creates a model of that page.
The model is called a DOM tree, and it is stored in the browsers' memory.
It consists of four main types of nodes. 

### WORKING WITH THE DOM TREE 

- Accessing and updating the DOM tree involves two steps:
1. Locate the node that represents the element you want to work with.
2. Use its text content, child elements, and attributes. 

- DOM trees have four types of nodes: document nodes,
element nodes, attribute nodes, and text nodes. 

### ACCESSING ELEMENTS

- DOM queries may return one element, or they may return a Nodelist,
which is a collection of nodes. 
- METHODS THAT RETURN A SINGLE ELEMENT NODE:
1. getElementByld(  id ) 
2. querySelector( css selector') 
3. getElementsByClassName( class  ) 
4. getElementsByTagName( tagName )
 
### LOOPING THROUGH A NODELIST
- example:

`var hotltems = document .querySelectorAll ('li.hot') ; `     ` Store Nodel ist in array`
`if (hotltems.length > O) {    `                               `If it contains items`
`for (var i=O; i<hotltems.length; i++) {  `                     `loop through each items`
`hotltems[i] .className = 'cool'; `                   `Change val ue of class attribute` 
`{`

### TRAVERSING THE DOM

- When you have an element node, you can select another element in relation to it using these five
properties. This is known as traversing the DOM. 

1. parentNode
2. previousSibling
3. nextSibling
4. firstChild
5. lastChild 

### WHITESPACE NODES
Traversing the DOM can be difficult because
some browsers add a text node whenever they
come across whitespace between elements.

### HOW TO GET/UPDATE ELEMENT CONTENT

 how to access/update element content. Your choice of techniques depends upon what the element contains. 

### ACCESS & UPDATE A TEXT NODE WITH NODEVALUE

- When you select a text node, you can retrieve or amend the content of it
using the node Va1ue property

### ACCESS & UPDATE TEXT WITH TEXTCONTENT (& INNERTEXT)

- The textContent property allows you to collect or update just the text that is in the
containing element (and its children). 

### ACCESS & UPDATE TEXT & MARKUP WITH INNERHTML

- Using the innerHTML property, you can access and amend the contents of an element,
including any child elements. 

### ADDING ELEMENTS USING DOM MANIPULATION 

DOM manipulation offers another technique to add new content to a page (rather than
innerHTML). It involves three steps: 

1. CREATE THE ELEMENT : createEl ement () 
2. GIVE IT CONTENT  : createTextNode() 
3. ADD IT TO THE DOM : appendChild() 

### UPDATING HTML CONTENT

- document.write() 
- eZement.innerHTML 
- DOM MANIPULATION 

### CROSS-SITE SCRIPTING (XSS) ATTACKS

- If you add HTML to a page using i nnerHTML (or several jQuery methods),
you need to be aware of Cross-Site Scripting Attacks or XSS; otherwise,
an attacker could gain access to your users' accounts. 


learn about object and how it work and contain set of variables and functions to create 
amodel , learn about the dom javascript how can accsess and update the contents of a web page 
and learn about DOM tree, how can select elements and change it.




