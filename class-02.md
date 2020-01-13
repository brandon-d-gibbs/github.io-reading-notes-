# Class Reading 02


///// HTML & CSS Chapters: 2 & 10
    Text
    Introducing CSS

//// JS Chapters: 2 & 4
    Basic JS Instructions
    Decisions and Loops

### HTML Text
They say that content is king. Well, if that's the case, then text is the OG High King of the internet. Yes, our internet has grown and changed, and a gret deal of the content consumed is via pictures, video, and audio, but we still have to have text. These other content forms still need things like titles, descriptions, and maybe even a tanscript of those videos. This is all acived throgh, of course, text.

The 'H' tags take care of our headings. There are 6 of them ranging from <h1> to <h6>. These are not self-closing tags, and will require that you close them. For example:

```html
\<h1\>Your heading will go here\</h1\>
```
That \</h1\> is what will allow you to continue on with additional text without everyting being larger. Your 'H' tags are also there to tell web-crawlers about the content that folows it, such as the topic of content and the level of importance that it has on the page.

### CSS

Every king needs a little style. This is where CSS comes into play. CSS (Cascading Style Sheets) are used to give a set of rules that will dictate how your HTML is diplayed, not just text.

So, if you wanted to make your text a little more fancy, you would use css. You can cange the color, size, position on the webpage, and much MUCH more. An example of a CSS rule looks like this:

```css
div {
    background-color: blue;
    color: Orange;
    text-align: center;
}

```
The 'div' tells the CSS to select any DIV element in your HTML. The next lines go on to set rules on how the background color, the text color, and centers the text within that DIV. 


## JavaScript

### Basic Instructions
One of the most basic but core parts of JavaScript is a variable. Variable are used to store data. You can store any data type you would like such as numbers, strings, arrays, booleans, etc. There are different ways of using variables that we will come to learn about as we get further into class. 

To store data into a variable, we must 'declare' it. To do this in the 201 class for now, we will be using the `var` keyword. After declaring a variable, we must assign it a value. Even if we don't have anything to assign yet, something is stored. If nothing is assinged, the value is then set to `nul`. We 'set' or 'declare' a varible like this:

```js
var string = 'This is a string';
var number = 34;
var array = ['Bandon', 'cats', 'food'];
var likesThisClass = true;
var blank = '';
var null;
```

The text following the `var` keyword names our variable. Then we use `=` to tell JS that we are about to give it a value. The information to the right of the `=` is what will be stored in the variable. This data should be just one type. If you want to store multiple data types, do so within an array.

As you can see in the `blank` variable, there is nothing inside the string. That will store an empty string, or evaluate to `true` as a boolean. The last variable doesn't have an `=` sign. This will default our valu to `null`.

## Decisions and Loops
There are going to be times you will need to have your program make a decisoin. This could be based on user input or the time of day, the day of the week/month, or other conditions. There are multiple ways to do this. We are going to briefly go over conditional statements. The first conditional statement we learn in JS is an `if` statement. It can be a little daunting to read at first. Let's take a look.

```js
if (condition) {
    //place code here tha will do something.
    // This is a good place or things like console.log(), alert(), calling functions(), changing the value of a variable, and much more.
} else if (another condition) {
    // If that frst condition wasn't true, see if this condition is true
} else { // There is no condition on this portion)
    // If the other conditions above did not evaluate to 'true', then the code in here would run.
}

```
Hopefully the comments in the example are helpful in breaking down what an `if statement` should look like.

Thank you for taking the time to read this. I hope you're having as much fun learning this as I am.