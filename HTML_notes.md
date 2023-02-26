# HTML Notes

## Day1

## Cat Photo App
### alt attribute to show case the value when image is broken, or for reference that this specific thing is about something. 
### href - to use  some different pages or pages outside the html. 
### target attribute in image or anchor tags with the help of _blank {target="_blank"} would open link in new tab
### figure and figcaption tags just to declare there are images and their captions in that section. 
### The action attribute indicates where form data should be sent. For example, <form action="/submit-url"></form> tells the browser that the form data should be sent to the path /submit-url.
### There are many kinds of inputs you can create using the type attribute. You can easily create a password field, reset button, or a control to let users select a file from their computer.
### label elements are used to help associate the text for an input element with the input element itself (especially for assistive technologies like screen readers). For example, <label><input type="radio"> cat</label> makes it so clicking the word cat also selects the corresponding radio button.
### Notice that both radio buttons can be selected at the same time. To make it so selecting one radio button automatically deselects the other, both buttons must have a name attribute with the same value.
### The fieldset element is used to group related inputs and labels together in a web form. fieldset elements are block-level elements, meaning that they appear on a new line.


## Day2

## Cafe Menu
### or the styling of the page to look similar on mobile as it does on a desktop or laptop, you need to add a meta element with a special content attribute. add this in the head: <meta name="viewport" content="width=device-width, initial-scale=1.0" />
### By using "background-image: url();" . you can add a background-image property and set its value to url(https://cdn.freecodecamp.org/curriculum/css-cafe/beans.jpg). 
### max-width / min-width - To keep your page in shape while Screen changing by big or small. 
### The current width of the menu will always take up 80% of the body element's width. On a very wide screen, the coffee and dessert appear far apart from their prices. Add a max-width property to the menu class with a value of 500px to prevent it from growing too wide.
### to use img as block level element - turn it into "display: block;" in css .
### to use any block level element as inline element - use "display: inline-block;" in css.
### when to use "width: 50%" when you want to keep two block level in same inline.

## Colored Markers
### "margin: auto" property will set content in the center with equal right and left rems.
### Note: If you add multiple classes to an HTML element, the styles of the first classes you list may be overridden by later classes.
### to make your website more attractive use complementary colors so the specific and main content will be visible more. 
### complementary colors are like two colors are exacly different or on color wheel they are across each other. 
### you must not have the same color on hue. or complemantary color being combined else they will generate grey color . 
### in Hex code colors. the value goes from 0 to F - they are 6 digits to represent hex "000000" the first two pairs represent red, middle two does green and last pair does blue. 0 is the lowest number all 000000 will create black, vice versa FF is the top and it will create white FFFFFF.
### The linear-gradient function is very flexible -- here is the basic syntax you'll use in this tutorial: "backgorund: linear-gradient(gradientDirection, color1, color2, ...);"
### "linear-gradient(90deg, red 90%, black);" - In the linear-gradient function, add a 75% color stop after the first red color argument. Do not add color stops to the other colors arguments.
### In linear gradient degrees work as vertical disect and horizontal disect to perform color directions. 180deg with perform horizontal 90deg will perform verticle.
### With the CSS opacity property, you can control how opaque or transparent an element is. With the value 0, or 0%, the element will be completely transparent, and at 1.0, or 100%, the element will be completely opaque like it is by default.
### The rgba function works just like the rgb function, but takes one more number from 0 to 1.0 for the alpha channel: rgba(redValue, greenValue, blueValue, alphaValue);
### The box-shadow property lets you apply one or more shadows around an element. Here is basic syntax: box-shadow: offsetX offsetY color;
### But what if you wanted to expand the shadow out further? You can do that with the optional spreadRadius value: box-shadow: offsetX offsetY blurRadius spreadRadius color;

# Day3

## Registration Form
### Adding a dropdown to the form is easy with the select element. The select element is a container for a group of option elements, and the option element acts as a label for each dropdown option. Both elements require closing tags. Start, by adding a select element below the two label elements. Then, nest 5 option elements within the select element.
### Submitting the form with an option selected would not send a useful value to the server. As such, each option needs to be given a value attribute. Without which, the text content of the option will be submitted to the server. Give the first option a value of "", and the subsequent option elements value attributes from 1 to 4.
### The textarea appears too small. To give it an initial size, you can add the rows and cols attributes. Add an initial size of 3 rows and 30 columns.
### Center the form element, by giving it a margin of 0 auto. Then, fix its size to a maximum width of 500px, and a minimum width of 300px. In between that range, allow it to have a width of 60vw.
### To style the submit button, you can use an attribute selector, which selects an element based on the given attribute value. Here is an example: input[name="password"] - / - The above selects input elements with a name attribute value of password.

 
