# Sorting with the UCA in PHP

Sorting using the Unicode Collation Algorithm (UCA) is available with the
`Collator` class in PHP 5.3.0 or in the PECL extension
[intl](http://pecl.php.net/package/intl).

```php
$collator = new Collator('');

$collator->sort();
```

The `Collator` class also provides the `asort` method, which corresponds to the
core `asort` function.

## Linguistic tailoring

The `Collator` class also supports linguistic tailoring.

```php
$collator = new Collator('de');

$collator->sort();
```
