# Unicode normalization in Go

Unicode normalization is available in the
[unicode/norm](http://godoc.org/code.google.com/p/go.text/unicode/norm) package
from the [go.text](http://godoc.org/code.google.com/p/go.text) project.

```go
import "code.google.com/p/go.text/unicode/norm"

nfd  := norm.NFD.String(str)
nfc  := norm.NFC.String(str)
nfkd := norm.NFKD.String(str)
nfkc := norm.NFKC.String(str)
```
