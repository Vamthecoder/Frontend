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
