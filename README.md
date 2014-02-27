design-for-developers
=====================

Simple design tips for developers

------

###  Alignment

Try and ensure that items on the page line up. 
Aligning vertically and horizontally is the simplest way to improve a UI.


###  Spacing

Try and use the same spacing throughout.


###  Rhythm

Set a base font size and use a line height 1.5x

example:

```
html, body {
    font-size: 16px;
    line-height: 1.5rem;
}
```

###  CSS Box Model


[the box model you want](http://www.paulirish.com/2012/box-sizing-border-box-ftw/)


``` 
*, *:before, *:after {
  -moz-box-sizing: border-box; 
  -webkit-box-sizing: border-box; 
  box-sizing: border-box;
 }
``` 


###  Fonts

Use a single font. Choose a profressional font.


###  Colours

Start with black and white. Add colour later - and then only as necessary.

Avoid the default web palette colours.

* [A nicer color palette for the web](http://clrs.cc/)
* [solarized](http://ethanschoonover.com/solarized)
* [flat design colors](http://www.flatdesigncolors.com/)
* [flat ui colors](http://flatuicolors.com/)


###  CSS resets

Use [normalize](http://necolas.github.io/normalize.css/) to set base styles.


###  Guides

* [GDS](https://www.gov.uk/service-manual) great advice on many areas of design / dev / writing
* (North)[https://github.com/Snugug/north]
