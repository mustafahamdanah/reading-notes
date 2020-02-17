## Lists

### Ordered Lists

`<ol>`
The ordered list is created with the `<ol>` element.
`<li>`
Each item in the list is placed between an opening `<li>` tag
and a closing `</li>` tag. (The li stands for list item.)

### Unordered lists

`<ul>`
The unordered list is created with the `<ul>` element.
`<li>`
Each item in the list is placed between an opening `<li>` tag
and a closing `</li>` tag. (The li stands for list item.)

### Definition Lists

`<dl>`
The definition list is created with the `<dl>` element and usually
consists of a series of terms and their definitions.
Inside the `<dl>` element you will usually see pairs of `<dt>` and
`<dd>` elements.

`<dt>`
This is used to contain the term being defined (the definition term).

## Boxes css

#### Box Dimensions  width, height
#### Limiting Width  : min-width, max-width
#### Limiting Height : min-height, max-height
#### Overflowing Content : hidden , scroll
#### Border Width :border-width
#### Border Style : border-style
#### Border Color : border-color
#### Change Inline/Block : display
#### Hiding Boxes : visibility
#### CSS3: Border Images : border-image
#### CSS3: Box Shadows : box-shadow
#### CSS3: Rounded Corners : border-radius
#### Border, Margin & Padding

## Decisions and Loops

### SWITCH STATEMENTS 

A switch statement starts with a variable called the switch value.
Each case indicates a possible value for this variable and the
code that should run if the variable matches that value. 

- example :

                    switch (level) {
                    case 'One ':
                    title= 'Level 1 ' ;
                    break; 

                    default :
                    title= 'Test';
                    break;
                    }

## loop

- Loops offer a quick and easy way to do something repeatedly. This chapter of the JavaScript Guide introduces the different iteration statements available to JavaScript.

### for statement
* A for loop repeats until a specified condition evaluates to false. The JavaScript for loop is similar to the Java and C for loop.

* A for statement looks as follows:

- for ([initialExpression]; [condition]; [incrementExpression])
statement

### do...while statement

* The do...while statement repeats until a specified condition evaluates to false.

* A do...while statement looks as follows:

- do
    statement
  while (condition);

### while statement

* A while statement executes its statements as long as a specified condition evaluates to true. A while statement looks as follows:

- while (condition)
   statement
