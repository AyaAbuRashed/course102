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

---

## Understanding CSS Thinking Inside the Box

The key to understanding how CSS works is to
imagine that there is an invisible box around
every HTML element.

## BLOCK & INLINE ELEMENTS 

Block level elements look
like they start on a new line.
Inline elements flow within the
text and do not start on a new .

---

## CSS Associates Style rules with HTML elements

![i](https://hackernoon.com/drafts/2z4a3yh4.png)

## CSS Properties Affect How Elements Are Displayed

CSS declarations sit inside curly brackets and each is made up of two
parts: a property and a value, separated by a colon. You can specify
several properties in one declaration, each separated by a semi-colon.

---

## Example INTRODUCING CSS

This example uses two documents: the HTML file (example.html)
and a separate CSS file (example.css). The fifth line of HTML uses the
<link> element to indicate where the CSS file is located.
On the next page, you will see how CSS rules can also be placed in your
HTML pages and we will discuss when you might want to do this.

---

![r](https://startingelectronics.org/tutorials/arduino/ethernet-shield-web-server-tutorial/CSS-introduction/CSS-ex1.png)




## Using External,Enternal,Inline CSS

![m](https://www.bitdegree.org/learn/storage/media/images/8c4493d3-110c-4a95-8b70-7626ce2d2f4e.o.jpg)

## Why use External Style Sheets?
When building a website there are several advantages to placing your
CSS rules in a separate style sheet.

All of your web pages can share
the same style sheet. This is
achieved by using the <link>
element on each HTML page of
your site to link to the same CSS
document. This means that the
same code does not need to be
repeated in every page (which
results in less code and smaller
HTML pages). 

Therefore, once the user has
downloaded the CSS stylesheet,
the rest of the site will load
faster. If you want to make a
change to how your site appears,
you only need to edit the one
CSS file and all of your pages
will be updated. For example,
you can change the style of
every <h1> element by altering 

---

##  Versions of CSS & Browser Quirks
CSS1 was released in 1996 and CSS2 followed two years later. Work on
CSS3 has been ongoing but the major browsers have already started to
implement it.


---

## Summary INTRODUCING CSS

- CSS treats each HTML element as if it appears inside
its own box and uses rules to indicate how that
element should look.
- Rules are made up of selectors (that specify the
elements the rule applies to) and declarations (that
indicate what these elements should look like).
- Different types of selectors allow you to target your
rules at different elements.
- Declarations are made up of two parts: the properties
of the element that you want to change, and the values
of those properties. For example, the font-family
property sets the choice of font, and the value arial
specifies Arial as the preferred typeface.
- CSS rules usually appear in a separate document,
although they may appear within an HTML page.