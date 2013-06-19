# Count code points in Perl 5

The core `length` function returns the number of code points when called on a
character string instead of a byte string.

    $count = length $str;
