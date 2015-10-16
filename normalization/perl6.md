# Unicode normalization in Perl 6

Unicode normalization is available in the core language as methods on strings
(`Str` onbjects).

```perl
$nfd  = $str.NFD;
$nfc  = $str.NFC;
$nfkd = $str.NFKD;
$nfkc = $str.NFKC;
```
