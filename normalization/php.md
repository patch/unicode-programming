# Unicode normalization in PHP

Unicode normalization is available in the standard class
[Normalizer](http://us1.php.net/manual/en/class.normalizer.php)
with PHP 5.3 or the PECL extension [intl](http://pecl.php.net/package/intl).

```php
$nfd  = Normalizer::normalize($str, Normalizer::Form_D);
$nfc  = Normalizer::normalize($str, Normalizer::Form_C);
$nfkd = Normalizer::normalize($str, Normalizer::Form_KD);
$nfkc = Normalizer::normalize($str, Normalizer::Form_KC);
```
