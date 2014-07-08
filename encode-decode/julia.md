# Encode and decode in Julia

The [UnicodeExtras](https://github.com/nolta/UnicodeExtras.jl) module provides
the `encode` function, which accepts a string and returns an array of bytes in
the specified encoding, and the `decode` function, which accepts an array of
bytes in the specified encoding and returns a string.

```julia
using UnicodeExtras

utf16 = encode(str,   "UTF-16")
str   = decode(utf16, "UTF-16")
```
