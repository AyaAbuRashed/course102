## In this section, we will look at how to make your web pages more attractive, controlling the design of them using CSS.

CSS allows you to create rules that specify how the content of
an element should appear. For example, you can specify that
the background of the page is cream, all paragraphs should
appear in gray using the Arial typeface, or that all level one
headings should be in a blue, italic, Times typeface.

Once you have learned how to write a CSS rule, learning CSS
mostly involves learning the different properties you can use.
So this chapter will:

- Introduce you to how CSS works
- Teach you how to write CSS rules
- Show you how CSS rules apply to HTML pages

## Understanding CSS:
## Thinking Inside the Box

The key to understanding how CSS works is to
imagine that there is an invisible box around
every HTML element.

# BLOCK & INLINE ELEMENTS 


Block level elements look
like they start on a new line.
Examples include the <h1>-
<h6>, <p> and <div> elements.
Inline elements flow within the
text and do not start on a new
line. Examples include <b>, <i>,
<img>, <em> and <span>.

## CSS Associates Style
## rules with HTML
## elements

![ii](https://hackernoon.com/drafts/
2z4a3yh4.png)

## CSS Properties Affect
## How Elements Are
## Displayed

CSS declarations sit inside curly brackets and each is made up of two
parts: a property and a value, separated by a colon. You can specify
several properties in one declaration, each separated by a semi-colon.

## Example
## INTRODUCING CSS

This example uses two documents: the HTML file (example.html)
and a separate CSS file (example.css). The fifth line of HTML uses the
<link> element to indicate where the CSS file is located.
On the next page, you will see how CSS rules can also be placed in your
HTML pages and we will discuss when you might want to do this.


<!DOCTYPE html>
<html>
<head>
 <title>Introducing CSS</title>
 <link href="css/example.css" type="text/css"
 rel="stylesheet" />
</head>
<body>
 <h1>From Garden to Plate</h1>
 <p>A <i>potager</i> is a French term for an
 ornamental vegetable or kitchen garden ... </p>
 <h2>What to Plant</h2>
 <p>Plants are chosen as much for their functionality
 as for their color and form ... </p>
</body>
</html>
body {
font-family: Arial, Verdana, sans-serif;}
h1, h2 {
color: #ee3e80;}
p {
color: #665544;}


## Using External CSS

<!DOCTYPE html>
<html>
<head>
 <title>Using External CSS</title>
 <link href="css/styles.css" type="text/css"
 rel="stylesheet" />
</head>
<body>
 <h1>Potatoes</h1>
 <p>There are dozens of different potato
 varieties. They are usually described as
 early, second early and maincrop.</p>
</body>
</html>

body {
 font-family: arial;
 background-color: rgb(185,179,175);}
h1 {
 color: rgb(255,255,255);}