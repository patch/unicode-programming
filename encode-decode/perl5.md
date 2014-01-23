# Encode and decode in Perl 5

```perl
use Encode;

$utf8 = encode('UTF-8', $str);
$str  = decode('UTF-8', $utf8);
```
