# Encoded I/O in Perl 6

All I/O is UTF-8 by default, decoded to strings (`Str` objects) on input, and
encoded on output.  Individual streams and filehandles can be handled as
follows.

## Standard streams

    $*IN.encoding  = 'UTF-16';
    $*OUT.encoding = 'UTF-16';
    $*ERR.encoding = 'UTF-16';

## Existing filehandles

    $fh.encoding = 'UTF-16';

## New filehandles

    my $in_fh  = open $path, :r, :enc<UTF-16>;
    my $out_fh = open $path, :w, :enc<UTF-16>;
