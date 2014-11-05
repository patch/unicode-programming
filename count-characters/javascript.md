# Count characters of a string in JavaScript

## Code points

The [Punycode.js](https://github.com/bestiejs/punycode.js) library can be used
to count code points.

```javascript
var puny = require('punycode');

count = puny.ucs2.decode(str).length;
```

## Grapheme clusters

The core language does not provide a way to count grapheme clusters. If you know
of a library with this functionality, please contribute it here.
