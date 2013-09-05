# Sorting with the UCA in Perl 5

Sorting using the Unicode Collation Algorithm (UCA) is available in the core
module [Unicode::Collate](https://metacpan.org/module/Unicode::Collate) bundled
with Perl 5.8 or on CPAN.

    use Unicode::Collate;

    $collator = Unicode::Collate->new;

    @sorted = $collator->sort(@unsorted);

## Linguistic tailoring

Sorting using the UCA with linguistic tailoring is available in the core module
[Unicode::Collate](https://metacpan.org/module/Unicode::Collate::Locale) bundled
with Perl 5.14 or on CPAN.

    use Unicode::Collate::Locale;

    $collator = Unicode::Collate::Locale->new(locale => 'de');

    @sorted = $collator->sort(@unsorted);
