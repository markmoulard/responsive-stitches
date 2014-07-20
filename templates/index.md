[Stitches](http://markmoulard.github.com/responsive-stitches/)
==========
#Demo

Drag &amp; drop image files onto the space below, or use the &ldquo;Open&rdquo; link to load images using the file browser. Then, click &ldquo;Generate&rdquo; to create a sprite sheet and stylesheet. <em>This demo uses a couple of HTML5 APIs, and it is only compatible with modern browsers.</em>

<link rel="stylesheet" href="/responsive-stitches/stitches/build/stitches/css/stitches-@@version.min.css">

<section id="main" role="main">

<div class="stitches">
    <img src="/responsive-stitches/stitches/build/stitches/img/test/github.png" data-name="github"/>
    <img src="/responsive-stitches/stitches/build/stitches/img/test/gmail.png" data-name="gmail"/>
    <img src="/responsive-stitches/stitches/build/stitches/img/test/linkedin.png" data-name="linkedin"/>
    <img src="/responsive-stitches/stitches/build/stitches/img/test/stackoverflow.png" data-name="stackoverflow"/>
    <img src="/responsive-stitches/stitches/build/stitches/img/test/tumblr.png" data-name="tumblr"/>
    <img src="/responsive-stitches/stitches/build/stitches/img/test/twitter.png" data-name="twitter"/>
</div>
## Implementation

After dependencies, Stitches requires a stylesheet, a script, and an HTML element to get the job done:

```html
<link rel="stylesheet" href="css/stitches-1.3.6.min.css">

<script data-main="js/stitches.js" src="js/stitches-1.3.6.min.js"></script>
```

The sprite sheet generator is automatically created in elements that have the `stitches` class:

```html
<div class="stitches"></div>
```

If you choose, any images that are a part of the initial markup will be loaded onto the canvas:

```html
<div class="stitches">
    <img src="img/test/github.png" data-name="github"/>
    <img src="img/test/gmail.png" data-name="gmail"/>
    <img src="img/test/linkedin.png" data-name="linkedin"/>
    <img src="img/test/stackoverflow.png" data-name="stackoverflow"/>
    <img src="img/test/tumblr.png" data-name="tumblr"/>
    <img src="img/test/twitter.png" data-name="twitter"/>
</div>
```

## Dependencies

[jQuery 1.7.1](http://jquery.com/), [Modernizr 2.0.6](http://modernizr.com/), [Bootstrap 2.3.0](http://twitter.github.com/bootstrap/)

```html
<link rel="stylesheet" href="libs/bootstrap/css/bootstrap.min.css">
<link rel="stylesheet" href="libs/bootstrap/css/bootstrap-responsive.min.css">

<script src="libs/jquery/jquery-1.7.1.min.js"></script>
<script src="libs/modernizr/modernizr-2.0.6.min.js"></script>
<script src="libs/bootstrap/js/bootstrap.min.js"></script>
```

## Download

**The latest release, 1.3.6, is [available here](http://markmoulard.github.com/response-stitches/stitches/dist/stitches-1.3.6.zip).**


## Contributors

* [amenadiel](https://github.com/amenadiel)
* [egeriis](https://github.com/egeriis)
* [flying-sheep](https://github.com/flying-sheep)
* [JonDum](https://github.com/JonDum)
* [mreq](https://github.com/mreq)
* [markmoulard](https://github.com/markmoulard)


## License

(The MIT License)

Copyright (c) 2013 [Matthew Cobbs](mailto:draeton@gmail.com)

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be included
in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS
OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

</section>

<script data-main="js/stitches.js" src="/responsive-stitches/stitches/build/stitches/js/stitches-@@version.min.js"></script>
