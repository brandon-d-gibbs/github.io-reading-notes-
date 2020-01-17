# Reading Notes 09

## Forms and Events

### HTML Forms

Forms are an HTML element or group of elements that allow us to take input or set of inputs from a user and use it in various ways. Form data can be text, numbers, selections from a drop-down list, radio buttons, etc. Types of text can be plain text in a single line, multiple lines via-text box, emails, passwords, and more. 

Forms require only a few elements to work.
- `\<form\> \</form\>` tags surround your inner form elements.
- `\<input type="put input type here"> ` The input element is pretty self-expalanatory.
- Lastly, you need an element to submit. This can be achieved with an input type of "submit" set as an attribute of a button for example.
    
Additionaly, you can expand this to make more complicated form. Forms with more and more inputs, it would be a good idea to use `<fieldset>` and `<legend>`. More information can be found out about those, and more on forms [here](https://www.w3schools.com/html/html_forms.asp).

### Events

Events are ...well, events that occur in the browser that we can use javascript to respond to. We can set javascript to "listen" for these events and then run functions when the event is detected.

A few examples of things that javascript can "listen" for are keypresses, mouse events such as hovers, left click, right click, double click, touch events, and more. 

Aside from the MDN resources on events, on of my favorite resources for reading easily followed explainations of topics and conecpts as well as a space to "try" out hte code has pretty good read / example on js events. That resource is [W3Schools](https://www.w3schools.com/jsref/dom_obj_event.asp).