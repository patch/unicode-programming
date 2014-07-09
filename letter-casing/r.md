# Letter casing in R

Letter casing functions are available in the
[stringi](http://www.rexamine.com/resources/stringi/) package on CRAN.

```r
library(stringi)

lowercase = stri_trans_tolower(str)
uppercase = stri_trans_toupper(str)
titlecase = stri_trans_totitle(str)
```

* Requires: stringi
* Docs: http://docs.rexamine.com/R-man/stringi/stri_trans_casemap.html
