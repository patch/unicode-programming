# Letter Casing in Perl 5

Letter casing functions are available in the core language and have Unicode
semantics for character strings but ASCII semantics for byte strings.

    $lowercase = lc $str;
    $uppercase = uc $str;
    $titlecase = ucfirst $str;

    use v5.16;
    $casefold = fc $str;

The `fc` function was added in Perl 5.16 and requires `use v5.16` or
`use feature 'fc'`.  The CPAN module `Unicode::CaseFold` provides the `fc`
function for Perl 5.8.1 or greater.

    use Unicode::CaseFold;
    $casefold = fc $str;
