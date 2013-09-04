# Unicode normalization in JavaScript

    var unorm = require('unorm');

    nfd  = unorm.nfd(str);
    nfc  = unorm.nfc(str);
    nfkd = unorm.nfkd(str);
    nfkc = unorm.nfkc(str);
