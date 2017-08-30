# lodash-epub-js

A pseudo fork of epub.js replacing Array.prototype.forEach and Array.prototype.map with lodash functions.  

[epub.js](https://github.com/futurepress/epub.js/)'s distribution is the source for these files.  All I've done here is replace the array functions.  Currently, we are in an environment needing to support Internet Explorer.  The epub.js makes heavy use of the array functions, which are easy to sub out for lodash.  Making this modification seems to improved performance for us quite a bit.


