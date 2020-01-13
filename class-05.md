# Class Rading-05

## HTML Images, CSS Color & Text

### HTML Images
Remember when we talked about content being king? Well, though text is the OG High King of content, Pictures are the crowned prince. Even videos have an image as a thumbnail. Images are the basis of major websites and apps such as Facebook, Instagram, Snapchat, Imgru, Tumblr, and many many more.

How to simply get an image on a website? There's a tag for that.

```html
<img src = "URL or file-path where the image is located" /> 
```

The `\<img\>` actually is a self-closing tag and does not require an additoinal tag to close this.

### CSS Color and Text
Again, CSS is the set of rules that dictate how our html is styled. This means that it will be used to change the color of things like the background and text. 

Example:

```css
div {
    background-color: blue;
    color: orange;
}
```
Color can be set as eiter a hex value

 `#550046`: # followed by 6 digits that coorelate to rgb values.

You can also set rgb in a more detailed and spefic manor with `rgb()` which accepts 3 value, with an optional 4 value.

```css
.overlay {
    background-color: rgb(250, 145, 200, .5);
}
```
The first 3 values are setting the degree of red, blue, and green. The 4th value is the opacity >> transparency value.

