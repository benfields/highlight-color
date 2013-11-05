Highlight Color
===============

This is a simple way to change the highlighting color on web based applications using CSS.

It's really easy, just add the code below to your CSS file...

```css
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

```css
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

another great color to try is tomato

```css
/* the color is currently set to tomato, change it as you please */

::selection {
    background: #ff4d2e; /* Safari, Chrome, IE, Opera, & More */
    color: #ffffff;
    }
::-moz-selection {
    background: #ff4d2e; /* Firefox */
    color: #ffffff;
}
```

=======

#### Note:

nothing needs to be added to the html file, only to the css, and only add it once.

=======

## Source License

### MIT License

Copyright (c) 2013 Ben Fields

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
