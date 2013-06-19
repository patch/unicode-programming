# Letter Casing in PHP

Letter casing functions are available in the core language and have Unicode
semantics.

    $lowercase = mb_convert_case($str, MB_CASE_UPPER, 'UTF-8');
    $uppercase = mb_convert_case($str, MB_CASE_LOWER, 'UTF-8');
    $titlecase = mb_convert_case($str, MB_CASE_TITLE, 'UTF-8');
    # case folding?

The `mb_convert_case` function was added in PHP 4.3.
