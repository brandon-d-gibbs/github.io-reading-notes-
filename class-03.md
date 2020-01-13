# Class Reading 03

Todays reading was to cover HTML Lists, CSS Boxes, and the Switch statements in JS.

### HTML Lists

List are pretty simple structures in HTML. You have ordered and unordered lists. They have two components for each of them. The `\<ol\>` tag or the `\<ul\>` tag to start a list... and the `\<li\>` tag. These are non self-closing tags and must wrap the list's conents with closing tags. `\<li\>` tags are nested within either `\<ol\>` tags or `\<ul\>` tags. 

Example:

```html
<!-- Ordered List-->
<ol> <!-- Produces a numbered list> -->
    <li>List Items</li>
    <li>List Items</li>
    <li>List Items</li>
</ol>

<!-- unordered List-->

<ul> <!-- Produces a bulletd list> -->
    <li>List Items</li>
    <li>List Items</li>
    <li>List Items</li>
</ul>

```
As the example states, *the ordered lists* are numbred and the *unordered lists* are bulleted by default. Unordred lists can have the bullet points removed or changed to other stylings through CSS properties.


### Switch Statements in JS

Switch statements are another conditional statement in JS. They read similarly to IF statements in the sense that they read top to bottom until a condition is met, runs code and extis the code when that condition is met.

```js
var value = 3;

switch(value) {
    case 1:
        //code in this block will not run;
        break; // will prevent code from conintuing if this conditions WAS true.
    case 2: 
        //code in this block will not run;
        break;
    case 3: 
        // Since the 'value' variale is equal to 3, the code in this block will run.
        break;
}

```