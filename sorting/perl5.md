# Sorting with the UCA in Perl 5

The core module
[Unicode::Collate](https://metacpan.org/module/Unicode::Collate) is used for
sorting using the Unicode Collation Algorithm.

    use Unicode::Collate;

    $collator = Unicode::Collate->new;

    @sorted = $collator->sort(@unsorted);

## Specific locale

The core module
[Unicode::Collate::Locale](https://metacpan.org/module/Unicode::Collate::Locale)
is used for sorting using the UCA with localization.

    use Unicode::Collate::Locale;

    $collator = Unicode::Collate::Locale->new(locale => 'de');

    @sorted = $collator->sort(@unsorted);
