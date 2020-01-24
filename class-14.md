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


# Reading Notes 14b 
## What Google Learned About Teams

This was a great read about team dynamics and the how the individuals and their styles can vary to still get to an optimum and efficient team. Being greter than the sum of its parts if you will. 

Google found that the most successful groups were not determined by all memebers being leaders, less being leaders, made up of all bright or balance intelligence... Instead the most efficient groups where groups with high social and emotional intelligence. Teams that were able to be sensitive to and react well to social temperatures, respect each other, and provide a safe space for everyone to speak up and contribute without fear of ridicule created a higher group IQ and made them more apt to solve issues in a constructve and efficient way.