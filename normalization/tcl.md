# Unicode normalization in Tcl

Unicode normalization is available in the tcllib package
[unicode](http://tcllib.sourceforge.net/doc/unicode.html).

```tcl
package require unicode

set nfd  [::unicode::normalizeS D  $str]
set nfc  [::unicode::normalizeS C  $str]
set nfkd [::unicode::normalizeS KD $str]
set nfkc [::unicode::normalizeS KC $str]
```
