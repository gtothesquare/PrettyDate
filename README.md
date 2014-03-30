# prettydate.js

Small lib for formatting dates. This is based on the library from John Resig called Javascript Pretty Dates.
http://ejohn.org/blog/javascript-pretty-date/

## Why Another Pretty Date Lib

Found a bug in the original code, where it will nto work in safari browsers (iOS and OSX).

The goal is to develop something light weight that covers the basic functions of formatting dates.
If you need something more advance, consider moments.js https://github.com/moment/moment/.

## Usage

prettyDate.prettify('2014-03-20T03:24:00Z');

If date provided is more than 31 days long from now, then it will return undefined.


## Original license

/*
 * JavaScript Pretty Date
 * Copyright (c) 2011 John Resig (ejohn.org)
 * Licensed under the MIT and GPL licenses.
 */

// Takes an ISO time and returns a string representing how
// long ago the date represents.



## License

prettydate.js is freely distributable under the terms of the MIT license.
