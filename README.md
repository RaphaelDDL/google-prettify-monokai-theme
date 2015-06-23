Tip: Use [highlight.js](https://github.com/isagalaev/highlight.js) instead. It has "monokai_sublime" theme and better highlighting than prettify.

---

[google-prettify-monokai-theme](http://raphaelddl.github.io/google-prettify-monokai-theme/)
==============================


An attempt to make a Google Code Prettify theme that looks like Sublime Text's Monokai Theme.

google-code-prettify (prettify.js) can be downloaded from here:
https://code.google.com/p/google-code-prettify/

> The theme is best for HTML codes.
> For CSS, JS and others might not feel like Sublime Text's Monokai, mostly due how pretiffy sort the tags (see more below in 'The Problem with CSS')

---

## Examples


#### HTML

![html](https://f.cloud.github.com/assets/1087109/1523578/0b20d106-4bb8-11e3-9b8e-7aac025a99e2.PNG)

#### JS

![js](https://f.cloud.github.com/assets/1087109/1523579/0d9d0300-4bb8-11e3-85be-74299f221687.PNG)



#### CSS

![css](https://f.cloud.github.com/assets/1087109/1523580/0fa3258a-4bb8-11e3-8042-65c1042cb79e.PNG)


----

#### The Problem with CSS:

It is impossible to have CSS colored to match Monokai Theme.
Element tags, id and class selectors are all treated as `plain` by Prettify.

Example:

    div#id.class > ul li[class*="string"] {color: #f00;}

According to Monokai, had to be like this:

![csstobe](https://f.cloud.github.com/assets/1087109/1523583/127745c0-4bb8-11e3-9223-5f08a71f442e.PNG)

On prettify, almost everything is 'plain', therefore everything is of same color, becoming that boring colorless box. Shame on you prettify.
