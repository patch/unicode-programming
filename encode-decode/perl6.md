# Encode and decode in Perl 6

    $utf8 = $str.encode;
    $str  = $utf8.decode;

or

    $utf8 = $str.encode('UTF-8');
    $str  = $utf8.decode('UTF-8');
