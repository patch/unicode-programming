# Letter Casing in Perl 6

Letter casing methods are available for strings (`Str` objects) in the core
language and always have Unicode semantics.

    $lowercase = $str.lc;
    $uppercase = $str.uc;
    $titlecase = $str.tc;
    $casefold  = $str.fc;
