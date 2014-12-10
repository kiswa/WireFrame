# WireFrame

A simple set of CSS styles to allow quick wireframe prototypes in HTML/CSS.
Because, why not have wireframes that provide the starting point for the
actual work!

## Options

By default, the wireframes use a dark theme.

![Dark Theme](http://matthewross.me/files/wf-dark.png)

To change to a light theme, just alter the `body` tag to:
`<body class="light">`

![Light Theme](http://matthewross.me/files/wf-light.png)

## Use

When creating a prototype, just add the `wf` class to a surrounding tag and
use the `wf-*` and `wf-child-*` classes to add styles to elements.

There are the following classes (all with `wf-child-*` classes):
 * `wf-top` to add a wireframe border to the top of an element
 * `wf-bottom` to add a wireframe border to the bottom of an element
 * `wf-left` to add a wireframe border to the left of an element
 * `wf-right` to add a wireframe border to the right of an element

Forms and inputs are also styled to match the wireframe look.
Handwriting-style fonts are used throughout. The loaded fonts are `Indie
Flower` for default text, `Rock Salt` for headers, and `Coming Soon` for
whatever you want (not set to anything in the wireframe CSS).

The `wf.css` file also includes [Font Awesome](http://fortawesome.github.io/Font-Awesome/icons/) icon fonts.

Inspired by [Wireframing with HTML and CSS](http://thecodeplayer.com/walkthrough/wireframing-with-html-css).
