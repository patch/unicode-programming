# Count characters of a string in JavaScript

## Code points

The [Punycode.js](https://github.com/bestiejs/punycode.js) library can be used
to count code points.

    var puny = require('punycode');

	$count = puny.ucs2.decode(str).length;
