# Encode and decode in Perl 6

UTF-8 is the default.

```perl
$utf8 = $str.encode;
$str  = $utf8.decode;
```

Other encodings can be explicitly specified.

```perl
$utf16 = $str.encode('UTF-16');
$str   = $utf16.decode('UTF-16');
```
