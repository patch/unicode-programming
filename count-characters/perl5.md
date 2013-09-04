# Count characters of a string in Perl 5

## Code points

The core `length` function returns the number of code points when called on a
character string (instead of a byte string).

    $count = length $str;

## Grapheme clusters

There is no core function to count the number of grapheme clusters; however,
either of the following examples will perform the task.

    $count = () = $str =~ /\X/g;

    $count++ while $str =~ /\X/g;

The CPAN module
[Unicode::GCString](https://metacpan.org/module/Unicode::GCString) can also be
used on character strings.

    use Unicode::GCString;

    $count = Unicode::GCString->new($str)->length;

As well as the CPAN module
[Unicode::Util](Unicode::GCStrin://metacpan.org/module/Unicode::Util).

    use Unicode::Util qw( grapheme_length );

    $count = grapheme_length($str);
