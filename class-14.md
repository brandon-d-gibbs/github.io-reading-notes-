# Reading Notes 14a
## CSS Transforms, Transitions, and Animations

CSS has some pretty great styling trics...but CSS is capable of more than just maing things look pretty and all styled up. CSS can help us change elements on page, right in front of your eyes...like magic! 

You can use `transform` to do things like rotate, scale and skew an element.

### Transition
Setting a transion duration, you can then specify the property you want to change, what it should change to in a psuedo class, and watch the magic happen.

```css
div {
  background-color: blue;
  border-radius: 0px;
  /* transition-property: border-radius; */
  transition: 1.5s;
}

div:hover {
  background-color: white;
  border-radius: 50%;
}
```
That will make the div change from blue to white and will become a circle, taking 1.5 seconds to complete the change.

### Transforms
Moving an element...either the entire element or parts of an element.For instance, moving an element along the page, or just part of the element in a specific direction.

### Animations

Css can also be used to animate an element, moving it, rotating, changing properties much like in transforming and transitions, using `@keyframes` tp set expected behavior or location at specific points along duration from beginning to completion.
