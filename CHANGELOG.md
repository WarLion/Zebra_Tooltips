## version 1.2.4 (January 20, 2016)

- better integration with [Bower](http://bower.io/)

## version 1.2.3 (January 16, 2016)

- fixed issues with bower.json file
- added "use strict"
- enabled JSHint in package.json

## version 1.2.2 (January 15, 2016)

- the "title" attribute is not removed anymore
- updated jQuery to 1.12.0 in examples
- added [Grunt](http://gruntjs.com/) integration for automating [JSHint](https://github.com/gruntjs/grunt-contrib-jshint) &amp; [Uglify](https://github.com/gruntjs/grunt-contrib-uglify) processes</li- the library is now available as a [Bower](http://bower.io/) package

## version 1.2.1 (November 25, 2013)

- fixed a bug where the "show" and "hide" methods were not accepting a jQuery selector as per documentation, but a single element; thanks to **Martin** for reporting
- fixed a bug with the "content" property, where its value was not used unless the "title" attribute was also set on the element the tooltip was attached to; thanks to **Phill** for reporting
- added a new "default_position" property useful if you want the tooltips to be positioned, by default, below the elements they are attached to and above only if there isn't enough space below; before, tooltips were shown by default above the elements they were attached tand below only if there wasn't enough above; thanks to **Sebastian Popa** for suggesting

## version 1.2.0 (October 18, 2013)

- tooltip content can now also be set via the "zebra-tooltip" data attribute
- tooltips are not shown anymore if the title or the data attribute is empty
- all the callback functions now receive as second argument the tooltip element, allowing for on-the-fly customization;</li- minor code tweaks as suggested by [JSHint](http://www.jshint.com/)

## version 1.1.0 (April 28, 2013)

- a new property was added: "vertical_offset" which sets how close (in pixels) should the tip of the tooltip's arrow be relative to the parent element; thanks **Jason Lewis**
- tooltip's width can now be set when initializing the plugin
- fixed a bug where the tooltip was not having an animation the first time it was shown but only on subsequent appearances
- fixed a bug with the arrow's container element, even though invisible, was larger than needed
- fixed a bug which broke the tooltip's animation if, during it's lifetime, a tooltip was shown above/below an element and then, because of scrolling or resizing, the tooltip had to be shown below/above the element
- fixed some positioning bugs when resizing the window or having scrollbars
- some optimizations and changes in the stylesheet file
- the project is now also available on [GitHub](https://github.com/stefangabos/Zebra_Tooltips)

## version 1.0.1 (May 11, 2012)

- fixed a bug where in Internet Explorer 9 the arrow was sometimes not visible; thanks to **Manfred** and **tolpi**

## version 1.0 (January 02, 2012)

- initial release