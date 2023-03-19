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

## Rothko Painting
### Use the filter property to blur the painting by 2px in the .canvas element. ex:p {  filter: blur(3px); }
### Increase the area and soften the edges of .one by setting its box-shadow to 0 0 3px 3px #efb762.
### Use the transform property on the .one selector to rotate it counter clockwise by 0.6 degrees. transform: rotate(-0.6deg)

## Photo Gallery
### text-transform: uppercase; - with this css property normal small alphabets will turn automatically into captial alphas without changing in HTML manually.
### Flexbox has a main and cross axis. The main axis is defined by the flex-direction property, which has four possible values:
### row (default): horizontal axis with flex items from left to right
### row-reverse: horizontal axis with flex items from right to left
### column: vertical axis with flex items from top to bottom
### column-reverse: vertical axis with flex items from bottom to top
### Note: The axes and directions will be different depending on the text direction. The values shown are for a left-to-right text direction.
### Give your .gallery img selector the object-fit property and set it to cover. This will tell the image to fill the img container while maintaining aspect ratio, resulting in cropping to fit.
### gap property, row-gap & column-gap sub property gives flex box a mere gap with the pxls you choose. it is also called gutter between row and column.

# Day4

## Nutrition Label
### text-indent property in css is very useful for your paragraph to give a lil space without stretching it padding or margin. it also works in negative units. Ex: p { text-indent: -10px; } . you can choose where you want it wisely.

# Day5

## Quiz
### nav > ul . By using greater than sign you mention whatever ul falls under nav will have their css properties.
### action attribute: it will automatically send data to given location. how to use <form action="web.server.location">
### method attribute: can be used by two ways. get and post. post will not show your credetianls and what are you trying to do in URL. on the other hand get will show login email and password that info you have submitted. 

# Day6

## Quiz
### role and aria-labelledby are attributes must be declared both at the same time. role could be region, nav or telling the users what they are searching for. but aria-labelledby attribute is declaring what is going under that section what kind of project. it is basically an id to relate to another tag within the parent or ancestor tags. 
### action and method attribute are also must be declared together. action: it is used when you want to declare the location where your user data will go. it could be your local storage or cloud storage. Method: it is used for post and get data. get data will show the credentials and what user trying to do. sign in login or posting. where post data just post the data on server - it wont get any values/
### use Select and Option comibnation to make drop down for website. and keep first option value empty and text " Select an option" is the best practice.
### display: flex; / justify-content: space-between; / align-items: center; / position: fixed; / top: 0; / important css prop values to make nav header look good. 
### <a href="#id"> to give the inpage location through nav link. use certain id to jump over. 
### * { scroll-behavior: smooth; } / this command can make your scrolling experience better by smoothing its behaviour. 


# Day7

## class with Ankur 
### clip-path: to give your element a shape of circle rectangle pentagon and many more. but using it wont cut down the image or element. it will just hide that part the image size will remain same . 
### @media queries: you can use this for responsive design by using its attribute like max-width and min-width. the pixels of the phone tabs and desktop are different. so every website renders differently on them. to make look good and same on every device you need to make your device responsive via media queries. NOTE: use this tag in the last of your CSS so no new thing would overwrite their responsive properties. 
### padding-inline / margin-inline: by using this property you can only add padding or margin to start of the content. and end of the content. the values would be using as RL.
### padding-block / margin-block: by using this property you can add padding or margin to top and bottom of the content. the values would be using as TB.
### you can add as many pages as you want to one single resourse of HTML by the help of JS we can use them on the different and separate pages. 
### you can ever bundle up many HTML pages to one resource. 
### accesskey="F" /- will give your that function the access with single key on keyboard. 


# Day8

## A Balance Sheet
### HTML tables use the caption element to describe what the table is about. The caption element should always be the first child of a table, but can be positioned with the caption-side CSS propert
### The thead and tbody elements are used to indicate which portion of your table is the header, and which portion contains the primary data or content.
### caption {  padding: 10px;    caption-side: bottom; } /- By using this property and value: you can get your caption in bottom of your table while mentioning caption in top in your table in html.
### clip-path: inset(TRBL round_%); this is to set on your own by rectangle. 
### clip-path: polygon(50% 0, 100% 50%, 50% 100%, 0 50%); /- polygon pattern work on TRBL and x-axis and y-axis you have to give both x and y value to your T-R-B-L.
### clip-path: ellipse(130px 140px at 10% 20%); /- ellipse pattern work on x-axis y-axis at how much you want to cover on x-axis y-axis
### clip-path: circle(40%); /- you can make circle by using one value could be the percentage of the image or could be the pixels. but notice % only works in 0-100 but px is dependent on imgs size.
### span[class~="sr-only"] {   border: 0;  clip: rect(1px, 1px, 1px, 1px);  clip-path: inset(50%);  -webkit-clip-path: inset(50%);  height: 1px;  width: 1px;  position: absolute;  overflow: hidden;  white-space: nowrap;  padding: 0;  margin: -1px; } to disappear anything within span element class attribute its value set to sr-only. 
### flex-direction: column-reverse; /- it will make elements reverse their position. Ex. Before Hi -> World. After World -> Hi. 
### Position: relative; it will make the element float over the existed elements. it will make no change to page's boxes and containers. but you can change the given position box wherever on the page without moving anything. 
### position: absolute; it will make X box floating over the page. and will reset the following element to its own.. and the X box will only take content width. until being declared in relative parent. 
### position: fixed; it has absolute property but it stays on just one page where ever the content move. it stays on one spot. 
### z-index: 1; /- it will give your page 3d lines. more than x-axis and y-axis. z-axis are mainly used with position other than static(default). and it can be used for throw elements in back and bring things in front.
### where element[attribute="value"] ONLY targets all the attribute with this value. on the other hand " element.class " it includes these class.


# Day9

## Picasso Painting
### border-style: solid or other values / - can put border in the left-top corner with the dot and can be given height and width for solid box. this property do not cover boxes around like normal border values. 
###   border-top-color: transparent; border-right-color: gold;  border-bottom-color: transparent;  border-left-color: transparent; you can use this property to make a good side border with multiple divs more than 10 atleast. 


# Day10

## Piano
### by giving html the box-sizing border-box and then giving * the box-sizing: inherit; will give all the childern a value of its parent. box-size - border-box. 
### ::before & ::after elements will allon the first child of selected element and the last child of selected element respectively.

## Technical Documentation Page
### overflow-y: scroll; if you want to make a scroll with your list. give it respective height then put it in to make it scroll.
### position: sticky; to use this you need to set the value of top: -1. or any value. 
### position relative or absolute with top,bottom,left,right: value would not work on responsive designs. you have to give proper margin-top,left,right,bottom. otherwise it will keep that margin on whenever end you will use. 
### be cautious with units. use wisely rem, px, em and %. Do not use '%' value when you want to give an element a fix space. cuz responsive will be problematic for it.
### @media (orientation: landscape) {} / @media (orientation: portrait) as per mobile screen size and functionality you want. 


## Day11

## City Skyline
### gradient-line {color1   , color2}
### linear-gradient : it can be used under background to style any element with multiple color and shades. gradient-type (color1 5%, color2 10%, color 30%); best way to use this.
### repeating-linear -gradient : it can be used to make repeating colors in a single element by using percentages. gradient-type (color1 0%, color1 7%, color2 7%, color2 14%...); and so this is the way to use gradient type- repeating use case.
### You can specify another direction by adding it before your colors like this: gradient-type( direction,   color1,  color2);
### You can add multiple gradients to an element by separating them with a comma (,) like this: gradient1(  colors), gradient2(  colors);
### The radial-gradient() CSS function creates an image consisting of a progressive transition between two or more colors that radiate from an origin. Its shape may be a circle or an ellipse. The function's result is an object of the <gradient> data type, which is a special kind of <image>.
### At the top of the sky gradient color list, where you would put a direction for the gradient; add circle closest-corner at 15% 15%,. This will move the start of the gradient to 15% from the top and left. It will make it end at the closest-corner and it will maintain a circle shape. These are some keywords built into gradients to describe how it behaves.


# Day12

## A Magazine
###  display: grid; CSS Grid offers a two-dimensional grid-based layout, allowing you to center items horizontally and vertically while still retaining control to do things like overlap elements. CSS Grid is similar to Flexbox in that it has a special property for both the parent and child elements. 
### grid-template-columns: 1fr 94rem 1fr; This will create three columns where the middle column is 94rem wide, and the first and last columns are both 1 fraction of the remaining space in the grid container.
### minmax; /- Use the minmax function to make your columns responsive on any device. The minmax function takes two arguments, the first being the minimum value and the second being the maximum. These values could be a length, percentage, fr, or even a keyword like max-content.
### To add space between rows in the grid layout, you can use the row-gap property. Same as column-gap to give gap between columns .
### One option is the grid-column property, which is shorthand for grid-column-start and grid-column-end. The grid-column property tells the grid item which grid line to start and end at. Its values are in rational number (2/1).
### For additional control over the layout of your content, you can have a CSS Grid within a CSS Grid.
### The CSS repeat() function is used to repeat a value, rather than writing it out manually, and is helpful for grid layouts. For example, setting the grid-template-columns property to repeat(20, 200px) would create 20 columns each 200px wide.
### grid-auto-flow : This property takes either row or column as the first value, with an optional second value of dense. grid-auto-flow uses an auto-placement algorithm to adjust the grid layout. Setting it to column will tell the algorithm to create new columns for content as needed. The dense value allows the algorithm to backtrack and fill holes in the grid with smaller items, which can result in items appearing out of order.
### text-align: justify; will give perfect spacing between the texts which is aligned in the container with 100% width. 
### The ::first-letter pseudo-selector allows you to target the first letter in the text content of an element.
### To give the hr a color, you need to adjust the border property.
### The gap property is a shorthand way to set the value of column-gap and row-gap at the same time. If given one value, it sets the column-gap and row-gap both to that value. If given two values, it sets the row-gap to the first value and the column-gap to the second.
### The place-items property can be used to set the align-items and justify-items values at the same time. The place-items property takes one or two values. If one value is provided, it is used for both the align-items and justify-items properties. If two values are provided, the first value is used for the align-items property and the second value is used for the justify-items property.


# Day13

## Completed A Landing Page Project from freeCodeCamp.


# Day14

## A Ferris Wheel
### The transform-origin property is used to set the point around which a CSS transformation is applied. For example, when performing a rotate (which you will do later in this project), the transform-origin determines around which point the element is rotated.
### Remember that the transform property allows you to manipulate the shape of an element. In this case, using the rotate(60deg) value will rotate the element around its transform-origin point by 60 degrees clockwise.
### The @keyframes at-rule is used to define the flow of a CSS animation. Within the @keyframes rule, you can create selectors for specific points in the animation sequence, such as 0% or 25%, or use from and to to define the start and end of the sequence.
### @keyframes rules require a name to be assigned to them, which you use in other rules to reference. For example, the @keyframes freeCodeCamp { } rule would be named freeCodeCamp.
### You now need to define how your animation should start. To do this, create a 0% rule within your @keyframes wheel rule. The properties you set in this nested selector will apply at the beginning of your animation. Examples://// @keyframes freecodecamp {  12% {    color: green;  }}
### The animation-name property is used to link a @keyframes rule to a CSS selector. The value of this property should match the name of the @keyframes rule. The animation-duration property is used to set how long the animation should sequence to complete. The time should be specified in either seconds (s) or milliseconds (ms). 
### The animation-iteration-count property sets how many times your animation should repeat. This can be set to a number, or to infinite to indefinitely repeat the animation. Your Ferris wheel should never stop.
### The animation-timing-function property sets how the animation should progress over time. There are a few different values for this property, but you want the Ferris wheel animation to run at the same rate from start to finish. linear is the property to start 0% and end 100% at same contiuous speed.
### By not using all animation properties you can use shorthand 'animation' property to define all at once. In this order animation-name, animation-duration, animation-timing-function, and animation-iteration-count. Ex: cabins 10s linear infinite.
### You can use @keyframes rules to control more than just the transformation of an element. In the 0% selector of your @keyframes cabins, set the background-color to yellow.
### animation-timing-function: can be 'linear', 'ease', 'ease-in', 'ease-out', 'ease-in-out', 'step-start', 'step-end' and many - more '' 
### animation Constituent properties: 'animation-delay', 'animation-direction', 'animation-fill-mode', 'animation-play-state'.


# Day15

## A Happy Flappy Penguin
### To use element's both axis, you can use the skew transform function, which takes two arguments. The first being an angle to shear the x-axis by, and the second being an angle to shear the y-axis by.
### border-radius: 80% 80% 100% 100%; you can use different combination to create any shapes like egg, oval, head and more with spherical properties.
### .element * by giving this selector, you can select all descendents of the targeted element selector. 
###  font: bold 25px Helvetica, sans-serif; /- font shorthand property : font: weight size family.
### The scaleX() CSS function defines a transformation that resizes an element along the x-axis (horizontally).… negative '-1' will resize an element upward horizontially. positive'1' with resize the element downward without giving it a prior width .. 
### scaleY() as well as X it will work vertically. negative'-1' marking will make the height of the element upward and positive(1) will give the element height downward. 
### transform: scale(); by pseudo class hover or active you can give the element a zoom-in look through positive value and zoom-out through negative value.
### transition is like small animation you can give similar values to see how it works.