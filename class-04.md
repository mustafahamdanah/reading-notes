## Links

### Writing Links 

`<a href="http://www.imdb.com">IMDB</a>`

### Directory Structure

- On larger websites it's a good idea to organize your code by placing the
pages for each different section of the site into a new folder. Folders on a
website are sometimes referred to as directories
1. Structure
2. Relationships
3. Homepages

### Relative URLs

- Relative URLs can be used when linking to pages within your own
website. They provide a shorthand way of telling the browser where to
find your files.

### Email Links

`mailto: `
To create a link that starts up the user's email program and
addresses an email to a specified email address, you use the `<a>`
element. However, this time the value of the href attribute starts
with mailto: and is followed by the email address you want the
email to be sent to.

### Opening Links in a New Window

`target`
If you want a link to open in a new window, you can use the
target attribute on the opening `<a>`tag. The value of this
attribute should be _blank.

## Layout

### Building Blocks

- CSS treats each HTML element as if it is in its
own box. This box will either be a block-level
box or an inline box.

- `<div>` elements are often used as containing elements
to group together sections of a page.

- Designers keep pages within 960-1000 pixels wide,
and indicate what the site is about within the top 600
pixels (to demonstrate its relevance without scrolling).


### Containing Elements

- If one block-level element sits inside another block-level element then the outer box is
known as the containing or parent element.

### Controlling the Position of Elements

- CSS has the following positioning schemes that allow you to control
the layout of a page: normal flow, relative positioning, and absolute
positioning. You specify the positioning scheme using the position
property in CSS. You can also float elements using the float property.

### Relative Positioning position:relative

- Relative positioning moves an element in relation to where it
would have been in normal flow

### Grid Layout

- The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.

## Functions, Methods, and Objects

### WHAT IS A FUNCTION? 

- Functions let you group a series of statements together to perform a
specific task. If different parts of a script repeat the same task, you can
reuse the function (rather than repeating the same set of statements)

                    function myFunction(p1, p2) {
                    return p1 * p2;   // The function returns the product of p1 and p2
                    }

### IMMEDIATELY INVOKED FUNCTION EXPRESSIONS

                    var area = (fltunction()
                    var wi dth = 3;
                    var height = 2;
                    return widt h * height;
                    }()); 

### VARIABLE SCOPE

- The location where you declare a variable will affect where it can be used
within your code. If you declare it within a function, it can only be used
within that function. This is known as the variable's scope. 
1. LOCAL VARIABLES 
2. GLOBAL VARIABLES 




