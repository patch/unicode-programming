# Count encoded bytes in Perl 5

The core `length` function returns the number of bytes when called on a byte
string instead of a character string.

```perl
$count = length $utf8;
```
