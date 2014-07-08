# Count characters of a string in Julia

## Code points

The core `length` function returns the number of code points when called on a string.

```julia
count = length(str)
```

## Grapheme clusters

The [UnicodeExtras](https://github.com/nolta/UnicodeExtras.jl) module provides
the `length` function, which returns the number of grapheme clusters when called
on a string.

```julia
using UnicodeExtras

count = length(str)
```
