## Text in html

### Headings

         <h1><h2>
         <h3><h4>
         <h5><h6>

- HTML has six "levels" of headings:
`<h1>` is used for main headings
`<h2>` is used for subheadings
If there are further sections
under the subheadings then the
`<h3>` element is used, and so on.

### Paragraphs

          <p>

- To create a paragraph, surround
the words that make up the
paragraph with an opening `<p>`
tag and closing `</p>` tag.

### Bold & Italic
 
 `<b>` bold
 `<i>` italic

### Superscript & Subscrip

         <sup>

- The `<sup>` element is used to contain characters that
should be superscript such as the suffixes of dates or
mathematical concepts like raising a number to a power such as 22

         <sub>

- The `<sub>` element is used to contain characters that should
be subscript. It is commonly used with foot notes or chemical
formulas such as H20.

### Line Breaks & Horizontal Rules

`<br />`
- As you have already seen, the browser will automatically show
each new paragraph or heading on a new line.
`<hr />`
- To create a break between themes — such as a change of
topic in a book or a new scene in a play .

## Semantic Markup

### Strong & Emphasis

`<strong>`
- The use of the `<strong>` element indicates that its content has strong importance
`<em>`
- The `<em>` element indicates emphasis that subtly changes
the meaning of a sentence.

### Quotations

`<blockquote>`
- The `<blockquote>` element is used for longer quotes that take
up an entire paragraph
`<q>`
- The `<q>` element is used for shorter quotes that sit within a paragraph

### Abbreviations & Acronyms

`<abbr>`
- chapter-02/abbreviations.html HTML If you use an abbreviation or
an acronym, then the `<abbr>` element can be used. A title
attribute on the opening tag is used to specify the full term

### Citations & Definitions

`<cite>`
- When you are referencing a piece of work such as a book,
film or research paper, the `<cite>` element can be used
to indicate where the citation is from.

`<dfn>`
- The first time you explain some new terminology (perhaps an
academic concept or some jargon) in a document, it is
known as the defining instance of it.

### Author Details

`<address>` 
The `<address>` element has quite a specific use: to contain
contact details for the author of the page

### Changes to Content

- The `<ins>` element can be used to show content that has been
inserted into a document, while
- the `<del>` element can show text that has been deleted from it.

## Introducing CSS

- CSS Properties Affect How Elements Are Displayed

- CSS works by associating rules with HTML elements. These rules govern
how the content of specified elements should be displayed. A CSS rule
contains two parts: a selector and a declaration.

- Declarations are made up of two parts: the properties
of the element that you want to change, and the values
of those properties. For example, the font-family
property sets the choice of font, and the value arial
specifies Arial as the preferred typeface.

### Using External CSS

`<link>` 
-  and it lives inside the `<head>` element. It should use three attributes:
> href
> type
> rel

### Using Internal css

`<style>`
You can also include CSS rules within an HTML page by placing
them inside a `<style>` element, which usually sits inside the
`<head>` element of the page. 

## Basic javascript instruction

### STATEMENTS 

- A script is a series of instructions that a computer can follow one-by-one.
Each individual instruction or step is known as a statement. Statements should end with a semicolon.

### COMMENTS

- You should write comments to explain what your code does. 
`/*` `*/` &  `//`

### WHAT IS A VARIABLE?

- A script will have to temporarily store the bits of information it
needs to do its job. It can store this data in variables.

### DATA TYPES

- JavaScript distinguishes between numbers, strings, 
and true or false values known as Booleans

### ARRAYS

- An array is a special type of variable. It doesn't
just store one value; it stores a list of values. 

#### example
             var colors;
             colors ['white', 'black', ' custom'];
             var el document.getElementByld('col ors');
             el . textContent = col ors[O];
   
- Result = white

#### VALU ES IN ARRAYS

- Values in an array are accessed as if they are in a numbered list. It is important 
to know that the numbering of this list starts at zero (not one). 

### EXPRESSIONS

- An expression evaluates into (results in) a single value. Broadly speaking
there are two types of expressions.

1. EXPRESSIONS THAT JUST ASSIGN A VALUE TO A VARIABLE  
2. EXPRESSIONS THAT USE TWO OR MORE VALUES TO RETURN A SINGLE VALUE 

### OPERATORS

- Expressions rely on things called operators; they allow programmers to
create a single value from one or more values.

## Decision & loops

### COMPARISON OPERATORS

- You may be familiar with comparison operators from math class. Let’s make sure there aren’t any gaps in your knowledge.

- less than (<) — returns true if the value on the left is less than the value on the right, otherwise it returns false.
- Greater than (>) — returns true if the value on the left is greater than the value on the right, otherwise it returns false.
- Less than or equal to (<=) — returns true if the value on the left is less than or equal to the value on the right, otherwise it returns false.
- Greater than or equal to (>=) — returns true if the value on the left is greater than or equal to the value on the right, otherwise it returns false.
- Equal to (===) — returns true if the value on the left is equal to the value on the right, otherwise it returns false.
- Not equal to (!==) — returns true if the value on the left is not equal to the value on the right, otherwise it returns false.

### LOGICAL OPERATORS

- Comparison operators allow us to assert the equality of a statement with JavaScript. For example, we can assert whether two values or expressions are equal with ===, or, whether one value is greater than another with >.

- There are scenarios, however, in which we must assert whether multiple values or expressions are true. In JavaScript, we can use logical operators to make these assertions.
- && (and) — This operator will be truthy (act like true) if and only if the expressions on both sides of it are true.
- || (or) — This operator will be truthy if the expression on either side of it is true. Otherwise, it will be falsy (act like false).

### summary

- Conditional statements allow your code to make
decisions about what to do next.
- Comparison operators (===, ! ==, ==, ! =, <, >, <=, =>)
are used to compare two operands.
- Logical operators allow you to combine more than one
set of comparison operators.
- if ... else statements allow you to run one set of code
if a condition is true, and another if it is false. 
