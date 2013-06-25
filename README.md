Highlight Color
===============

This is a simple way to change the highlighting color on web based applications using CSS.

It's really easy, just add the code below to your CSS file...

```

/* the color is currently set to orange, change it as you please */

::selection {
    background: #ea7e3f; /* Safari, Chrome, IE, Opera, & More */
    color: #ffffff;
    }
::-moz-selection {
    background: #ea7e3f; /* Firefox */
    color: #ffffff;
}

```

the highlight color is set to orange in the code snippet above. Change the hexadecimal to whatever you prefer.

=======

Below, there is a code snippet where the highlight color has been changed to green

```
/* the color is currently set to lime green, change it as you please */

::selection {
    background: #60bd5b; /* Safari, Chrome, IE, Opera, & More */
    color: #ffffff;
    }
::-moz-selection {
    background: #60bd5b; /* Firefox */
    color: #ffffff;
}
```
=======

#### Note

nothing needs to be added to the html file, only to the css, and only add it once, unless you are adding it to a different file.

=======
=======


```
--> make sure to check out the demo
```

### demo at [terld.com](http://terld.com/)
