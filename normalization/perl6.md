# Unicode normalization in Perl 6

Unicode normalization is available in the core language as methods on strings
(`Str` onbjects).

    $nfd  = $str.nfd;
    $nfc  = $str.nfc;
    $nfkd = $str.nfkd;
    $nfkc = $str.nfkc;
