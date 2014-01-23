# Count characters of a string in PHP

## Code points

The `mb_strlen` function is available for strings in PHP 4.0.6 and requires the
encoding of the string to either passed as the second argument or set in
`mbstring.internal_encoding`.

```php
$count = mb_strlen($str, 'UTF-8');
```

## Grapheme clusters

The `grapheme_strlen` function is available for UTF-8 strings in PHP 5.3.0 or
the PECL extension [intl](http://pecl.php.net/package/intl).

```php
$count = grapheme_strlen($str);
```
