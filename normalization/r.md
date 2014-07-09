# Unicode normalization in R

Unicode normalization functions are available in the
[stringi](http://www.rexamine.com/resources/stringi/) package on CRAN.

```r
library(stringi)

nfd  = stri_trans_nfd(str)
nfc  = stri_trans_nfc(str)
nfkd = stri_trans_nfkc(str)
nfkc = stri_trans_nfkd(str)
```

* Requires: stringi 0.2-2
* Docs: http://docs.rexamine.com/R-man/stringi/stri_trans_nf.html
