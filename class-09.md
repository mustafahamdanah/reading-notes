### Form Controls

- ADDING TEXT
- Password input
- Making Choices
- Drop-down boxes 

### How Forms Work

- A user fills in a form and then presses a button
to submit the information to the server.

### Form Structure

`<form>` Form controls live inside a `<form>` element. This element
should always carry the action attribute and will usually have a
method and id attribute too.
- `action` : Every `<form>` element requires an action attribute. Its value
is the URL for the page on the server that will receive the
information in the form when it is submitted.
- `method` Forms can be sent using one of
two methods: get or post.
- `id` :  We look at the id attribute, but the value is used to
identify the form distinctly from other elements on the page

## Input

### Text Input

`<input>` : The `<input>` element is used to create several different form
controls. The value of the type attribute determines what kind
of input they will be creating.
- type="text"  , name , maxlength

### Password Input

- type="password" , name , size, maxlength

### Text area

`<textarea>`
The `<textarea>` element is used to create a mutli-line
text input. Unlike other input elements this is not an empty
element. It should therefore have an opening and a closing tag. 

### Radio Button

- Radio buttons allow users to pick just one of a number of options.
- type="radio" , name , value , checked

### Button & hidden Controls

- `<button>`
The `<button>` element was introduced to allow users more
control over how their buttons appear, and to allow other
elements to appear inside the button.
- `<input>` type="hidden"

### Labelling Form Controls

- `<label>`
When introducing form controls, the code was kept simple by
indicating the purpose of each one in text next to it. However,
each form control should have its own `<label>` element as this
makes the form accessible to vision-impaired users.

### Grouping Form Elements

- `<fieldset>`
You can group related form controls together inside the
`<fieldset>` element. This is particularly helpful for longer
forms.

- `<legend>`
The `<legend>` element can come directly after the opening
`<fieldset>` tag and contains a caption which helps identify the
purpose of that group of form controls

### HTML5: Date Input

- `type="date"`
If you are asking the user for a date, you can use an `<input>`
element and give the type attribute a value of date. 

### HTML5: Email & URL Input

`<input>` 
- type="email"
- type="url"

### HTML5: Search Input

`<input>`
- type="search"
- placeholder

## Lists, Tables and Forms

### Bullet Point Styles : list-style-type

- Unordered Lists
 none , disc
 circle , square , image
- Ordered Lists
decimal , upper-alpha

### Summary

- In addition to the CSS properties covered in other
chapters which work with the contents of all elements,
there are several others that are specifically used to
control the appearance of lists, tables, and forms.
- List markers can be given different appearances
using the list-style-type and list-style image
properties.
- Table cells can have different borders and spacing in
different browsers, but there are properties you can
use to control them and make them more consistent.
- Forms are easier to use if the form controls are
vertically aligned using CSS.
- Forms benefit from styles that make them feel more
interactive.

## Events

### HOW EVENTS TRIGGER JAVASCRIPT CODE

- When the user interacts with the HTML on a web page, there are three
steps involved in getting it to trigger some JavaScript code.
Together these steps are known as event handling. 

1. Select t he element node(s) you want the
script to respond to. 
2. Indicate which event on the selected node(s) will
trigger the response.
3. State the code you want to run when the event
occurs. 

### DIFFERENT EVENT TYPES

Here is a selection of the events that occur in the browser while you are
browsing the web. Any of these events can be used to trigger a function
in your JavaScript code.

1. UI EVENTS : load , unload ,error 
2. KEYBOARD EVENTS : keydown , keypress 
3. MOUSE EVENTS : click ,mousedown 

### THREE WAYS TO BIND AN EVENT TO AN ELEMENT

- HTML EVENT HANDLERS (DO NOT USE)
- TRADITIONAL DOM EVENT HANDLERS
- DOM LEVEL 2 EVENT LISTENERS 


### Summary

- Events are the browser's way of indicating when
something has happened (such as when a page has
finished loading or a button has been clicked).
- Binding is the process of stating which event you are
waiting to happen, and which element you are waiting
for that event to happen upon.
- When an event occurs on an element, it can trigger a
JavaScript function. When this function then changes
the web page in some way, it feels interactive because
it has responded to the user.
- You can use event delegation to monitor for events
that happen on all of the children of an element.
- The most commonly used events are W3C DOM
events, although there are others in the HTMLS
specification as well as browser-specific events. 