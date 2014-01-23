# Unicode normalization in JavaScript

Unicode normalization is available in the npm package
[unorm](https://npmjs.org/package/unorm).

```javascript
var unorm = require('unorm');

nfd  = unorm.nfd(str);
nfc  = unorm.nfc(str);
nfkd = unorm.nfkd(str);
nfkc = unorm.nfkc(str);
```
