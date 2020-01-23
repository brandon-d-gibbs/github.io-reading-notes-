# Reading Notes 12

## HTML Canvas and Chart JS

## HTML Canvas

One of the powerful new tags in HTML 5 is the `<canvas>` tag. This tag allows us to create a drawing surface in our HTML. For the purposes of this class and our current use in labs, this will be used for drawing charts.

A very simple example:
```html
    <canvas>
    
    </canvas>
```
You can add attributes such as `id`, `height` and `width` as well. The default canvas sizing will be * 300px x 150px * . You can aslo change this in CSS or through DOM manipulation. 

Using the `document.getElementByID` you can target your desired canvas tag and use `var ctx = canvas.getContext('2d');`to render 2d images to the canvas area.

### Chart JS

`Chart JS` is a powerful JS library that is used to do precisely what you think that it might do. It helps you build charts. No, these aren't your mom's pie charts. These are highly flexible,extensible charts. You can use several styles incluing `pie` `bar` `line` `area` and more.

Charts created with Chart JS can be animated, have the colors changed, be dynamic and more. What more is there to say here? They are charts...but more. Check out the [documentation](https://www.chartjs.org/docs/latest/configuration/layout.html) for more details, or a great read that was shared with us on how to do some really cool things with chart JS can be found [here](https://www.webdesignerdepot.com/2013/11/easily-create-stunning-animated-charts-with-chart-js/) .