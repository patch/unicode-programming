# Unicode normalization in Perl 5

Unicode normalization is available in the core module
[Unicode::Normalize](https://metacpan.org/pod/Unicode::Normalize) with Perl 5.8
and available on CPAN.

```perl
use Unicode::Normalize;

$nfd  = NFD($str);
$nfc  = NFC($str);
$nfkd = NFKD($str);
$nfkc = NFKC($str);
```
