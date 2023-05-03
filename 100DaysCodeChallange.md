# Day18

## 404 Not Found Master Completed 


# Day19

## My Team Page 
### Learned more about Grid functionallity and their properties and values.. and how grid work and where we can use grid perfectly. 
### Grid Areas will only work in same no. of columns in all rows. 
### grid area you can apply in child individually. 
### grid better work in media query with repeat(auto-fit, value) but there should be value given to each columns as you can not give each column their width to make responsive without media query. 
### jusify and align content, justify and align items will be used in only container of parent selector. 
### justify and align self will only go in child or content selector. 
### place items and content is short hand property for justify and align. 
### span 2 can work in any condition but without giving the appropriate will move the span-ed content to any location. not specific. 
### grid is a good sport when you want to work on complex designs. but for only two columns you can use flex better. 

## DOM 
### Document- File(Html,Xml), Object- tags/elements of the file, Model- Layout/Structure. which can be manipulated by JS 


# Day20

## Responsive Design
### learned more about how pixel works and how we can more appropriate responsive website. 
### completed Interior Consultants project from Dev_Challenges. 


# Day21

## Completed Recipe page from Dev Challenges.


# Day22

## Resolved the issues of 404 and did upload the project on netlify and completed first project on website of Dev Challenges. 


# Day23 

## Completed Checkout page project from dev challenges. 


# Day24 

## HTML CSS JS Apna College
### semantic are like meaningful elements like section aside main body footer header and non semantic elements are like div span 
### adjacent are sibling element descendent are child and ascendent are parents
### in video tag you can use controls, autoplay, loop, autopictureinpicture, muted, poster and preload.
### text-align-last will only select last line of the content. can give values of center left right.
### text-decoration is shorthand property for line-style-color.
### text-emphasis is shorthand property for position-style-color and it could be great experiment to do. 
### text-indent could be one positive value for first line to move it forward and backward from its position.
### text-orientation: upright; work with writing-mode: vertical-rl; 
### text-overflow could be one good source to mention all the text if you have less space in the box.
### text-shadow is shorthand property for x-axis, y-axis, blur-radius and color. 
### text-transform could come in handy while putting text in UPPERCASE, lowercase and All First Letter Capital.
### list-style is shorthand property for type, position and image. 
### border-block can come in handy when you want to style only block of border.
### border-collapse: collapse could merge all siblings element borders all together while seprate can create two different borders of siblings.
### border-radius is shorthand property where you can use top left / top right/ right bottom / bottom left viceverse start end/ end start.
### border-image can be used to select an image to style your borders. or by help of linear-gradient you can create an image.
### border-image has different property aligned with outset, repeat, slice, source, width. 
### border-style can be covered with various values like double dotted dashed solid.
### border-spacing could come in handy while creating table and other siblings without using padding.
### order: 'number', by using this in items with the help of flex it can be used to maintain order. like grid-areas.
### flex-basis: 'max-value'. by this property in css you can use much responsiveness by flex. 
### flex-grow: '2'; will grow the item relatively to the siblings. it is more like fraction 'fr'.
### flex-shrink: '2'; will shrink the item relatively to the siblings. opposite of flex-grow.


# Day25

## Basic freeCodeCamp JS
### In computer science, data is anything that is meaningful to the computer. JavaScript provides eight different data types which are undefined, null, boolean, string, symbol, bigint, number, and object.
### In JavaScript we end statements with semicolons. Variable names can be made up of numbers, letters, and $ or _, but may not contain spaces or start with a number.
### let myVar = 1; myVar += 5; console.log(myVar); by using this '+=' you can replace myVar = myVar + 5; this command. 
### Quotes are not the only characters that can be escaped inside a string. Escape sequences allow you to use characters you may not otherwise be able to use in a string. \'	single quote, \"	double quote, \\	backslash, \n	newline, \t	tab, \r	carriage return, \b	word boundary, \f	form feed


# Day26

## Basic freeCodeCamp JS
### We can also use the += operator to concatenate a string onto the end of an existing string variable. This can be very helpful to break a long string over several lines. Ex. let ourStr = "I come first. "; ourStr += "I come second.";
### Sometimes you will need to build a string. By using the concatenation operator (+), you can insert one or more variables into a string you're building. Ex. const ourName = "freeCodeCamp"; const ourStr = "Hello, our name is " + ourName + ", how are you?";
### In JavaScript, String values are immutable, which means that they cannot be altered once created.
### You can also nest arrays within other arrays, like below: const teams = [["Bulls", 23], ["White Sox", 45]]; This is also called a multi-dimensional array.
### An easy way to append data to the end of an array is via the push() function.  / .push() takes one or more parameters and "pushes" them onto the end of the array.
### const arr = [  [1, 2, 3],  [4, 5, 6],  [7, 8, 9],  [[10, 11, 12], 13, 14]]; const subarray = arr[3]; const nestedSubarray = arr[3][0]; const element = arr[3][0][1];
### .pop() is used to pop a value off of the end of an array. We can store this popped off value by assigning it to a variable. In other words, .pop() removes the last element from an array and returns that element.
### pop() always removes the last element of an array. What if you want to remove the first? That's where .shift() comes in. It works just like .pop(), except it removes the first element instead of the last.
### Not only can you shift elements off of the beginning of an array, you can also unshift elements to the beginning of an array i.e. add elements in front of the array.  / .unshift() works exactly like .push(), but instead of adding the element at the end of the array, unshift() adds the element at the beginning of the array.const ourArray = ["Stimpson", "J", "cat"];  ourArray.shift();  ourArray.unshift("Happy");


# Day27

## Basic freeCodeCamp JS
### did couple of steps and learnt console.log and confirm, alert and assigning values. how you can assign values to the variables. and how you can use them wisely.


# Day28

## Almost Completed the 7th project Edie Homepage from dev-challenges


# Day29

## Basic JS 
### document.getElementById("") you can get value with this command by assigning into some var.
### document.getElementsByClassName("") similar to Id you can get values through this command by assigning to some var but as classes can be used almost everywhere you use numbers [0] to get the specific class value. 
### .innerHTML by this you can push some values or rewrite values and texts to the page. ex. document.getElementById("").innerHTML = "value/text";
### document.getElementsByClassName("")[0].innerHTML = "value/text"; similar to the id but just by using numbers you can select specific values of any class.
### Five types of operators : Arithmetic, Logical, Ternary, Assignment and Comparison


# Day30

## Basic JS 
### Logical operator : &&, || and !0 
### && can only be used when both conditions are true. it will show false or '0' in any case of false.
### || can be used when one condition is true. either a or b condition should be true for the true output.
### x > y ? "yes" : "no"; If this only condition is true or false. it will showcase. ex. var x = 20; var y = 18; var z = x > y ? "yes" : "no"; in this case it will show yes.
### < element onclick="functionName"> attribute can be directly applied in HTML and the event will be assigned to function in JS being made. 
### var name = document.getElementById('').value; will get the value from the element in HTML. 
### parseInt() function can be used to convert the string into integer.
### object-poisition useful when you want to position or align some content aside.
### flex-flow and flex-basis are useful for responsiveness. you want to use flex-basis insted of width while using flexbox
### by taking li first child for logo and justify content to flex-end and for logo you can use margin-right to auto. it will make the header look clean. without taking two divs.
### with the help of flex order, you can play with navigation by giving logo order of 2 and other navigation to order of 1 and 3 to center your logo without separating blocks or childs.
### shape-outside will give the ability to shape the text acording to any logo or curve beside it. without using flex but using float around it. 


# Day31

## Basic JS Frontend Masters
### document.title to select title from HTML doc. 
### document.getElementById() you can select ID's from HTML
### document.querySelector() you can select IDs but with CSS selector #ID.
### document.getElementsByTagName() you can select any HTML tag by this. 
### document.getElementsByTagName().length you will get how many selected tags are there.
### document.querySelectorAll().length By typing All with query selector you can select all tags and class name from HTML.
### document.getElementsByClassName() you can select all class from HTML.
### document.getElementById("name").textContent through this we can get inside text from the element's ID from HTML.
### document.getElementById().textContent = "Value" by using this assigning method you can directly change the value inside the selected element in HTML.
### document.getElementById("name").append("Value") will add more value to the existed text from HTML. 
### [perspective,perspective-origin,transform:preserve-3d,transform:rotateX(),transform:rotateY(),transfrom:translateZ()]
### input:focus~ element{} by using focus pseudo selector you can give access to input as "button" to control "element" by being pressed by the user. without using JS.



# Day32

## JS First Steps to Professional - FM
### "string".indexOf("s") will give you the number or index or place where that character of string is in the string.
### "string".includes("tri") will give you boolean value of true as the tri exist in string. similar if there is no matching of selected string or element boolean will show false.
### "string".startsWith("st") similar as includes, startsWith is an boolean operation will generate true because st starts with string but 'ing' will generate false.
### "STRING".toLowerCase() this will give you lower cases of the string or the value if it is in uppercase. similarly .toUpperCase() will capitalize the letters. Ex. document.querySelector("").textContent.toUpperCase()
### document.querySelector("string").style.textTransform = "uppercase" this is how you can capitalize the letters. and can use css properties by using '.style' and '.property' = "value".
### pass by reference is not applicable in JS, pass by value is only happens in JS Ex. let x = 12, let y = x, x = 22. so the value of y is 12 not 22. even x has changed the value.

## Responsive Images FM
### <picture><source src="img.jpg" media="(min-width,max-width,orientation)"> <img src="img.jpg" alt="exceptTheMediaQuery"></picture> this snippet would give you if else condition when media query is true it will load the source image. and if it is false it will directly go to 'img' in the 'picture' element.


# Day33

## JS First Steps to Professional - FM
### .sort() in array will automatically sort thing alphabetically. ["b", "d", "a", "c"] = a, b, c, d
### .join("value") in console.log after variable. would add what ever value is in the join. 
### .concat(["value", "value"]) you can add one whole array by this in array after variable in console.log/ it wont change original array as push do.
### as array is mutable so if you reassign it to some another variable and will change the value of first variable it will change automatically another variables too. it is ref value while working with array.
###  console.log prints it to browser console. similarly console.warn and console.error are two different commands which gives warning and gives error with the message written in it respectively.

## Responsive Images FM
### srcset= "img100.jpg, img200.jpg, img300.jpg"  sizes="(min-width: 200px) 33.3vw, 100vw" it will give your image more reponsiveness over the all devices and load different MB images on different devices to save bandwidths and make more clearer imgs on different screensize. 
### responsivebreakpoints.com the website to break any image into different size for responsiveness with exact pixels required.


# Day34

## JS First Steps to Professional - FM
### .substring(1) will give you all the chars after 0 in strings and arrays from 1 except 0
### .setAttribute("attribute", "value"); by this you can add attribute in html element without updating any html.
### removeAttribute("attribute") will remove the attr in html.
### completed conditional statement 'if else' and its examples.


# Day35

## JS First Steps to Professional - FM
### element.classList.add("classname") lets you add a CSS class. 
### console.log(`hey my number 1 is adding to your number 4 and it will become their number ${1+4}`) this is an easy method when you can use some funtion to overwrite on '$' with the help of backtick ` `.
### const usernames = nameValue.filter(user => user.name.includes("n")); it will show the objects or string values of an array  
### spread - (...variableName) you can use spread by using three dots ... to concatnate or push the values into existing elements
### Math.floor(Math.random()*3) to get rid of the decimal numbers. it will only give '1' integer.


# Day36

## JS First Steps to Professional - FM
### const variable = [{name: "string1", nickname: "string2"}]; let {name, nickname} = variable[0];  will let you get the value of the array object into their specific variable by assigning value.
### .split(" "); you can use this method to split a long string into array. if you leave it empty the string will split in array by spaces. Ex. ("string1 string2 string3").split(""); ["string1", 'string2', 'string3']
### .trim(); you can use to remove the whitespace from both side of the string.
### let variableResponse = await fetch("URL"); to fetch any website's data from the URL. it will give you reponse. 
### let variableBody = await variableResponse.json(); will get the data in object or array form from the response. 
### destructuring let { variablePropertyData } = variableBody; will get the property and its value from the given Object and Array data from the website URL that you have fetched. 
### async function will allow a normal function to wait for a long period of time to process the function. and it will allow you to use 'await' 