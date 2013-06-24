google-prettify-monokai-theme
==============================

An attempt to make a Google Code Prettify theme that looks like Sublime Text 2 Monokai Theme.

google-code-prettify (prettify.js) can be downloaded from here:
https://code.google.com/p/google-code-prettify/

The theme is best for HTML codes.
For CSS, JS and others might not feel like Sublime Text 2's Monokai.

---

## To do:
An addition to the .CSS to support the `class="lang-*"` that prettify supports, for correct colouring CSS and JS just like ST's language colors.

*Update 2013-06-24:*
Impossible to have CSS colored to match Monokai Theme.
Element tags, id and class selectors are all treated as `plain` by Prettify.

Example:

    div#id.class > ul li[class*="string"] {color: #f00;}

According to Monokai, these are the color:
- `div`, `ul` and `li` are red/pink;
- `#id.class` and `class*` are green;
- `"string"` is yellow;
- `color` is blue;
- `#f00` is purple;
- puntuaction is white;

On prettify, except by `"string"` and `color: #f00;`, everything else is 'plain', therefore everything is of same color.
Shame on you prettify.
