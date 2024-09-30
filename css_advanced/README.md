learning CSS
By Suntha Lucas
Link: https://sunnilu.github.io/-atlas-web-development/

So what is CSS?  Well the letters stand for Cascading Style Sheets.  But what does that mean?  CSS describes how HTML elements are to be displayed on screen, paper,or in other media.  CSS also saves a lot of work, it can control the layout of multiple web pages all at one.

why use CSS?
CSS is used to define styles for your web pages, like design, layout and variations in display for different devices and screen sizes.  CSS solves big problems.  As you know that HTML was never intended to contain tags for formatting a web page, yet it was created to describe the content of a web page like the use of <h1></h1> and or <p></p>
when tags like <font> and color attributes were added to the HTML, it started a nightmare for the web developers.  To solve the problem,the World Wide Web Consortium created CSS.

CSS removed the style formatting from the HTML page.  You can change the entire look of a website by changing one file, the css.

Here's an example of how you can change the color, font and align the text in a css file:

body  {
    background-color: blue;
}
h1  { 
    color: white;
    text-align: center;
}
p . {
    font-family: verdana;
    font-size: 20px
}

CSS Syntax

A CSS rule consists of a selecor and a declaration block.!
* selector - h1
* Declaration - color:blue; font-size:12px;

The selector points to the HTML element you want to style.
The declaration block contains one or more declarations separated by semicolons.

Each declaration includes a CSS property name and a value, separated by a colon.

Multiple CSS declarations are separted with semicolons, and declaration blocks are surrounded by curly braces.

my example:
p {
    color: red;
    text-align: center;
}

p is a selector in CSS( it's pointing to the HTML element you want to style: <p>).

color is a property also, and so is red it's the property value, text-align is a property, and center is the property value.


