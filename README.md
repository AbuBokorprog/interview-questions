# Interview Questions Project

This project contains a collection of interview questions related to HTML, CSS, JavaScript (JS), TypeScript (TS), and React.js. It is designed to help candidates prepare for technical interviews in web development.

## Table of Contents

- [Introduction](#introduction)
- [HTML](#html)
- [CSS](#css)
- [JavaScript](#javascript)
- [TypeScript](#typescript)
- [React](#react)

## Introduction

This project aims to provide a comprehensive set of interview questions and sample solutions for candidates preparing for web development interviews. The questions cover HTML, CSS, JavaScript, TypeScript, and React.js.

## HTML

### Most Important HTML Interview Questions:

**What is HTML?:**
- HTML's meaning is HyperText Markup Language. It is a Markup language and standard text formatting language used for creating the structure and layout of web pages.

 **What are HTML tags?:**
- Tags are used to structure the content and define the layout of a webpage. Tags use the symbols < and > to set them apart from the HTML content. Tags 2 kinds, One is a Container Tag and two is an Empty Tag. A  Container Tag has an opening Tag and a Closing Tag but an empty Tag has only an opening Tag.

**What are HTML Attributes?**
- Attributes are the properties that can be added to an HTML tag. They modify the behaviour or provide extra details about the element. For example, a <input> tag has a type attribute, which you use to add the type of input from which type input is displayed.

**Can you separate a section of text in HTML?**
- Yes, I can separate sections of text in HTML using various tags to create different blocks or divisions within the content. Some of the common in HTML with the following tags:
p tag: Use this tag to write any text paragraph.
br tag: Use this for separating a line of text. This will break a current line and also shift the flow of a text over to a new line.
h1 to h6 tag: Used to define headings and subheadings within a document

**What is the key difference between HTML Tags and Elements? / Are the HTML tags and elements the same thing?**
- HTML tags are used to define the structure of a web page, while HTML elements are made up of a set of tags that define a specific part of a web page. 
HTML Tags: Tags are used to mark up the start and end of an HTML element.
HTML elements: An element in HTML represents some kind of structure or semantics and generally consists of a start tag, content, and an end tag. 

**What is a ‘Marquee’ Tag in HTML?**
- The marquee tag in HTML was used to create scrolling or moving text or images on a webpage. It scrolls the image or text up, down, left, or right automatically. The text which is scrolled is defined within the <marquee> .. </marquee> tag.

**What is HTML5?**
- HTML5 is the improved HTML version released in 2014 by the World Wide Web. It introduces new features like semantic elements, multimedia support, canvas for graphics, improved forms, offline capabilities, geolocation, and enhanced accessibility.

**What is Semantic HTML?**
- Semantic HTML is a coding style. HTML uses semantics to reinforce the semantics or purpose of the content.
Here are some examples of semantic tags introduced in HTML5:
<header>
<nav>
<main>
<article>
<section>
<aside>
<summary>
<marks>
<footer>

**What is the Use of Comments in HTML?**
- Comments are used in an HTML document to make important notes or explanations to help developers within the code. They are not displayed in the browser when the code is executed. A comment is always written in between the ‘-‘ symbol at the beginning and end of the angular brackets. For example, “<!-“ and “->.”

**What is a form in HTML?**
- Forms are used to collect user information, such as login information or search queries. Forms can be created using the <form> tag, and input fields, such as text fields and checkboxes, can be added using various other tags.

**What are the different types of lists in HTML?**
- HTML lists are used to group a set of related items in lists. It is defined with an <li> tag. There are 3 types of lists: 
Ordered List: Ordered lists are numbered lists,
Unordered List: unordered lists are bulleted lists and
Definition List: definition lists are lists of terms and their definitions.
**How do you create a hyperlink in HTML?**
- An anchor tag is used to link two sections, web pages, or website templates in HTML. We use the anchor tag <a> to create a hyperlink in HTML that links one page to another page.

**What is an Image Map?**
- An image map in HTML helps in linking with the different kinds of web pages using a single image. It is represented with the <map> tag.

**What is the difference between the ‘id' and ‘class' attributes of HTML elements?**
- The “id” attributes define a unique identifier and one “id” can be used only once. The “class” attribute defines a class for a group of elements and a “class” can be used multiple times.

**What is the difference between HTML and HTML5?**
- HTML5 is the latest HTML version released in 2014 and includes new features and improvements over previous versions. Differences between HTML and HTML5 include multimedia elements, improved semantics, and better support for mobile devices.

## CSS

Most Important CSS Interview Questions:

**Name some CSS frameworks.**
- CSS frameworks are libraries that make website styling so easy. Some of the frameworks are Bootstrap, Tailwind CSS, Foundation, Bulma, Skeleton etc.
What do you understand by the universal sector?
The CSS universal selector (*) matches any element type's name instead of selecting elements of a particular type. For Example,
```css
* {    

   color: blue;    

   font-size: 10px;    

}
```
**What are the elements of the CSS Box Model?**
- The CSS box model defines the layout and design of CSS elements. The elements are Margin, Border, Padding and Contents.

**How can CSS be integrated into an HTML page?**
- We can three ways of integrating CSS into HTML.
Inline: Using inline styles.
Internal: Use the style tag in the head section.
External: Writing CSS another file, and linking into the HTML page by link tag.

**What is the difference between a class and an ID?**
- Class and ID are used in HTML pages for styling. Class is used for multiple elements styling and there are no unique elements, while ID has a unique and is also used for single elements.

**Define z-index.**
- The Z-index specifies the stack order of elements that overlap each other. Its default value is zero and can take both negative and positive values. A higher z-index value is stacked above the lower index element. The values- auto, number, initial, and inherit.

**How can you target h3 and h2 with the same styling?**
- Multiple elements are targeted by separate with a comma.
```css
h3, h2{
color: red;
}
```
**What is responsive web design?**
- Responsive Design is a web page creation approach that uses flexible images, flexible layouts, and CSS media queries. This design approach aims to create websites and applications that respond to different screen sizes, and devices and build web pages that detect the orientation and screen size of the visitors so that the layout can be changed accordingly. For example, desktop computers, laptops, tablets, and smartphones size.
What are the different types of Selectors in CSS?
There are various types of selectors available in CSS. Type Selector, class Selector, ID selector, Attribute Selector, child selector, pseudo-class selector and pseudo-element selector.

**What is the difference between inline, inline block, and block?**
Inline: Inline elements don’t start a new line. they appear on the same line as the content and tags beside them. Inline elements are < a >, < span >, < strong >, < I >,  and < img > tags. Inline elements we can’t set fixed width or height.
Inline-Block: Inline Block is similar to inline elements. The difference is that inline-Block elements we can set fixed width or height.
Block: Block elements start a new line and we can set fixed width or height. Block elements are < div >, < p > etc.

**What are Pseudo classes?**
- Pseudo class are special-type CSS selector That allows us to select the regular elements under certain conditions especially when we try to hover over the link. They start with a colon (:). Some common use of pseudo-class: 
:hover
:focus
:visited
:ntn-child
:first-child
:last-child

**What are the properties of Flexbox?**
Flexbox properties following:
flex-direction
flex-wrap
flex-flow
justify-content
align-items
align-content

**Difference between CSS grid vs flexbox?**
Grid is two dimensional and flex is one dimensional
Grid used for large-sized layouts. While flex used for the components of an application.
Grid layout is Two-dimensional while flex layout is one-dimensional.
Flex Direction allows developers to align elements vertically or horizontally, which is used when developers create and reverse rows or columns.
CSS Grid deploys fractional measure units for grid fluidity and auto-keyword functionality to automatically adjust columns or rows.

**Tell us something about CSS3.**
-CSS3 is the latest version of Cascading Style Sheets (CSS). CSS3 is divided into modules and is supported by almost every browser. Many graphics-related characteristics are introduced in CSS3 like box-shadow, Border-radius, and flexbox.

**How do media types in CSS work?**
Media types are used to apply different styles based on the type of media used to view the web page. There are various types of media properties print, speech, and screen.
```css
/* Styles for screens */
@media screen {
  body {
    background-color: #f2f2f2;
  }
}

  /* Additional styles for larger screens */
  @media screen and (min-width: 768px) {
    body {
      font-size: 18px;
    }
  }
```


## JavaScript

### Most Important Javascript Interview Question:

**What is JavaScript?**

- JavaScript is a scripting and object-based, lightweight, cross-platform translated programming language. It is different from Java language. which is used for web

**What is the difference between undefined and not defined in JavaScript?**

- In JavaScript, if you try to use a variable that doesn't exist and has not been declared, then JavaScript will throw an error var name is not defined and script will stop executing. However, if you use typeof undeclared_variable, then it will return undefined.

**What is the difference between undefined, null and not defined?**

- In JavaScript, `null`, `undefined`, and "not defined" refer to different concepts related to the absence or lack of a value.

**Undefined:**
   - **Declaration:** A variable that has been declared but not assigned a value is `undefined`.
   - **Function Parameters:** If a function is called with fewer arguments than declared parameters, the remaining parameters are set to `undefined`.
   - **Object Properties:** When trying to access an object property that doesn't exist, the result is `undefined`.
```javascript
   let x; // x is undefined
   function example(a, b) {
     console.log(b); // b is undefined if not provided
   }
   let obj = {};
   console.log(obj.property); // property is undefined
   ```
   
**Null:**
   - **Assignment:** `null` is an assignment value that represents the intentional absence of any object value.
   - **Explicit Assignment:** You can explicitly assign a variable or object property to `null` to indicate that it has no value or is empty.

   ```javascript
   let y = null;
   let obj = { property: null };
   ```

**Not Defined:**
   - **Variable Not Declared:** If you try to access a variable that has not been declared at all, it will result in a ReferenceError, and the variable is said to be "not defined."

   ```javascript
   console.log(z); // ReferenceError: z is not defined
   ```

**To summarize:**
- `undefined` is a default value given to variables that have been declared but not assigned a value.
- `null` is a value that represents the intentional absence of an object value.
- `Not defined` refers to attempting to access a variable or property that has not been declared or defined in the current scope.

It's important to understand these concepts to handle different scenarios in your JavaScript code effectively.

**What are the different data types present in JavaScript?**

#### There are 2 types of data types:
- Primitive data types,
- Non-Primitive data types.

#### In the primitive data types follow: 
- Number – It's all numbers with or without decimal.
- String    – It is character words.
- Boolean – The  Boolean is give two values - true or false. It is used for conditional purpose.
- BigInt  – The BigInt is used for storing large numbers and can store large integers and is represented by adding “n” to an integer literal.
- Symbol – It is a new data type introduced in the ES6 version of javascript. It is used to store an anonymous and unique value.
- Undefined – The undefined means a variable is declared but not assigned. The value is undefined. We can also set this.
- Null –The null means a variable is a non-existent, null, or invalid value.

#### In the Non-Primitive data types follow:
- Array – The Array data type is used for a group of similar values. Every value has an array that has a numeric position it is called an index, and it can be any type of data. The array index starts from 0.
- Object – The Object is a Non-Primitive data type. It is used for the collection of data. In the Object have two properties key and value. The object key is always a string but the value can be any type of data type.
- RegEx: It represents a regular expression.

**What is the difference between == and ===?**

- There are both comparison operators. Difference both of  this “==” is used to compare just values, while this “===” is used compare to values and data types.

**What is the difference between undefined value and null value?**

- The difference between Undefined means a variable is declared but not assigned. The value is undefined. While null means a variable is a non-existent, null, or invalid value.

**Write a mul function which will produce the following outputs when invoked:**
```js
console.log(mul(2)(3)(4)); // output : 24 
console.log(mul(4)(3)(4)); // output : 48
```

- Below is the answer followed by an explanation to how it works:
```js
function mul (x) {
    return function (y) { // anonymous function 
        return function (z) { // anonymous function 
            return x * y * z; 
        };
    };
}
```

**What is NaN property in JavaScript?**

- NaN property means not a number. It is clarified that this number is not a legal number.

**How to write a comment in JavaScript?**

#### There are two kinds of comments in javascript:
- `Single line:` single line comment written by a double slash(//) for example, //This is comments.

- `Double-lines:` Double lines comment written by a slash with an asterisk symbol as /* this is comment */

**What is the differences global scope, function scope and block scope?**

#### Differences in global scope, function/local scope and block scope:

- `Global Scope:` Global scope means when a variable or function declared global namespace having global scope. All the variables and functions having global scope can be accessed from anywhere inside the code.
- `Function Scope:` function scope means which variable or function is declared inside a function. Only which variable or function can be accessed from within the function and not outside of it.

- `Block Scope:` Block Scope means when a variable or function is declared inside a block {}, can be accessed only inside that block and cannot be accessed outside of it. But if Variables declared with var do not have block scope.

**What are the types of errors in javascript?**

####There are two types of errors in JavaScript:

- `Syntax Error:` syntax error is structured mistake or spelling problem that causes the program to not execute at all or stop run.
- `Logical Error:`  When the syntax is proper to correct, but the logic or program is incorrect. These are more difficult to correct the logical error than syntax issues since the logical error don’t display.

**What is prototype property in JavaScript?**

- Every JavaScript function has a prototype property (by default this property is null), that is mainly used for implementing inheritance. We add methods and properties to a function's prototype so that it becomes available to instances of that function.

**What does the isNaN() function do?**

- The isNan() function returns true if the variable value is not a number.

**What is the difference between an arrow, and a regular function?**

- A normal function has an arguments object which we can access in the function, but this argument does not exist in arrow functions.

- The regular function created “this” variable which references the objects that call them, While Arrow functions do not create their own this.

- The regular function can be accessed before initialization but Arrow functions cannot be accessed before initialization.

**What is a callback function?**

- A callback is a function which passed as an argument to another function.Then invoked inside the outer function to complete action.

**What is the difference between setTimeout and setInterval?**

- The setTimeout() function is a method to execute a specific block code after a certain period of time, and it will execute once after the time. 
- SetInterval is almost similar to setTimeout. setInterval function calls a function after a time period, but it will execute continuously during the time interval. The time interval execute like a time gap after the function has to call another function every time.

- The setTimeout function calls the block of code only once But The setInterval function calls the code after the specific time interval provide again and again.
setTimeout to clear have cleartiemout(), while setInter to clear have clearInterval().

**What are some advantages of using External JavaScript?**

- External JavaScript code is javascript written separate file and then link to the html file. A Javascript file is linked in HTML file head or body section.
`Some advantages of using external Javascript:`
We can reuse
Can be read code so easily and
Easy to collaborate with designers and developers in HTML and Javascript files.

**Tell me some of the advantages of JavaScript.**

- Javascript learn is so easy than others languages. Web pages now have more functionality because of Javascript. Javascript is quite quick.

**In JavaScript, how many different methods can you make an object?**

-       Object.
-       Class.
-       create Method.
-       Object Literals.
-       using Function

## TypeScript

## React
