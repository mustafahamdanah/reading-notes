 ## Domain Modeling

 - Domain modeling is the process of creating a conceptual model in code for a specific problem. A model describes the various entities, their attributes and behaviors, as well as the constraints that govern the problem domain. An entity that stores data in properties and encapsulates behaviors in methods is commonly referred to as an object-oriented model.

 - A domain model that's articulated well can verify and validate the understanding of a specific problem among various stakeholders. As a communication tool, it defines a vocabulary that can be used within and between both technical and business teams.

### Summary

- Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.

- Here's some tips to follow when building your own domain models.

1. When modeling a single entity that'll have many instances, build self-contained objects with the same attributes and behaviors.
2. Model its attributes with a constructor function that defines and initializes properties.
3. Model its behaviors with small methods that focus on doing one job well.
4. Create instances using the new keyword followed by a call to a constructor function.
5. Store the newly created object in a variable so you can access its properties and methods from outside.
6. Use the this variable within methods so you can access the object's properties and methods from inside.

## Tabels

### Basic Table Structure

`<table>`
The `<table>` element is used to create a table. The contents
of the table are written out row by row.

`<tr>`
You indicate the start of each row using the opening `<tr>` tag.

`<td>`
Each cell of a table is represented using a `<td>` element. (The td stands for table data.)
At the end of each cell you use a closing `</td>` tag.

### Table Headings

`<th>`
The `<th>` element is used just like the `<td>` element but its
purpose is to represent the heading for either a column or a row

### Spanning ColumnS

- Sometimes you may need the entries in a table to stretch
across more than one column. The `colspan attribute` can be
used on a `<th>` or `<td>` element and indicates how many columns
that cell should run across.

### Spanning Rows

- You may also need entries in a table to stretch down across
more than one row. The rowspan attribute can be
used on a `<th>` or `<td>` element to indicate how many rows a cell
should span down the table.

### Long Tables

- `<thead>`
The headings of the table should sit inside the `<thead>` element. 

- `<tbody>`
The body should sit inside the `<tbody>` element

- `<tfoot>`
The footer belongs inside the `<tfoot>` element.

## Object

- An object is a series of variables and functions that
represent something from the world around you.

- In an object, variables are known as properties of the
object; functions are known as methods of the object. 

### RECAP: WAYS TO CREATE OBJECTS
1. CREATE THE OBJECT, THEN ADD PROPERTIES & METHODS 
2. LITERAL NOTATION

                    var hotel = {}
                    hotel .name= 'Quay';
                    hotel .rooms = 40;
                    hotel.booked = 25;
                    hotel.checkAvailabil ity =function()
                    return this.rooms - this .booked;
                    } ; 

3. OBJECT CONSTRUCTOR NOTATION

                    var hotel = new Object();
                    hotel.name = 'Quay';
                    hotel .rooms = 40;
                    hotel . booked= 25;
                    hotel.checkAvailability =function()
                    return this .rooms - this.booked;
                    } ; 

4. CREATING AN OBJECT WITH PROPERTIES & METHODS

### ADDING AND REMOVING PROPERTIES 

- Once you have created an object (using literal or constructor
notation), you can add new properties to it. You do this using the dot notation
 that you saw for adding properties to objects

### THIS (IT IS A KEYWORD) 

- The keyword this is commonly used inside functions and objects.
Where the function is declared alters what this means. It always refers
to one object, usually the object in which the function operates. 

### RECAP: STORING DATA 

- In JavaScript, data is represented using name/value pairs.
To organize your data, you can use an array or object to group a set of
related values. In arrays and objects the name is also known as a key. 

- ARRAYS
Arrays can store multiple pieces of information.
Each piece of information is separated by a comma.
The order of the values is important because items
in an array are assigned a number (called an index). 

- VARIABLES
A variable has just one key (the variable name) and one value. 

### THE BROWSER OBJECT MODEL: THE WINDOW OBJECT

- The window object represents the current browser window or tab. It is the topmost object
in the Browser Object Model, and it contains other objects that tell you about the browser. 

### THE DOCUMENT OBJECT MODEL: THE DOCUMENT OBJECT 

- The topmost object in the Document Object Model (or DOM) is the
document object. It represents the web page loaded into the current
browser window or tab. You meet its child objects in Chapter 5. 

### DATA TYPES REVISITED 

1. String
2. Number
3. Boolean
4. Undefined
5. null
6. object

### GLOBAL OBJECTS: MATH OBJECT 

The Math object has properties and methods
for mathematical constants and functions. 

- Math. cei 1 () Rounds number up to the nearest integer
- Math. floor() Rounds number down to the nearest integer
- Math. random() Generates a random number between 0 (inclusive) and 1 (not inclusive)

### GLOBAL OBJECTS: DATE OBJECT (AND TIME) 

- Once you have created a Date object, the following methods let you set
and retrieve the time and date that it represents. 

- getDate()       setDate()      Returns I sets the day of the month (1-31) 
- getDay ()                      Returns the day of the week (0-6)
- getFulYear()    setFulYear()   Returns I sets the year (4 digits) 





