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

### Normal Flow position:static

- In normal flow, each block-level element sits on top of the next
one. Since this is the default way in which browsers treat
HTML elements, you do not need a CSS property to indicate
that elements should appear in normal flow.

### Absolute Positioning position:absolute

- When the position property is given a value of absolute,
the box is taken out of normal flow and no longer affects the
position of other elements on the page

### Fixed Positioning position:fixed

- Fixed positioning is a type of absolute positioning that
requires the position property to have a value of fixed


### overlapping Elements z-index

- When you use relative, fixed, or absolute positioning, boxes can
overlap. If boxes do overlap, the elements that appear later in the
HTML code sit on top of those that are earlier in the page

### Relative Positioning position:relative

- Relative positioning moves an element in relation to where it
would have been in normal flow

### Floating Elements : float

- The float property allows you to take an element in normal
flow and place it as far to the left or right of the containing
element as possible.

### Clearing Floats : clear

- The clear property allows you to say that no element (within
the same containing element) should touch the left or righthand sides of a box.

### Page Sizes

- Because screen sizes and display resolutions vary so much, web
designers often try to create pages of around 960-1000 pixels wide
(since most users will be able to see designs this wide on their screens)

### Grid Layout

- The CSS Grid Layout Module offers a grid-based layout system, with rows and columns, making it easier to design web pages without having to use floats and positioning.

### CSS Frameworks

- CSS frameworks aim to make your life easier by providing the code for
common tasks, such as creating layout grids, styling forms, creating
printer-friendly versions of pages and so on. You can include the CSS
framework code in your projects rather than writing the CSS from scratch.

### Multiple Style Sheets : @import

- Some web page authors split up their CSS style rules into
separate style sheets

### Multiple Style Sheets : link

- On this page you can see the other technique for including
multiple style sheets. Inside the `<head>` element is a separate
`<link>` element for each style sheet.



