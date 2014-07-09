# Letter Casing in Julia

The [UnicodeExtras](https://github.com/nolta/UnicodeExtras.jl) module provides
the `lowercase`, `uppercase`, `titlecase`, and `foldcase` functions.

```julia
using UnicodeExtras

lowercase = lowercase(str)
uppercase = uppercase(str)
titlecase = titlecase(str)
casefold  = foldcase(str)
```
