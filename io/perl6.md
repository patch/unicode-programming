# I/O encoding in Perl 6

All I/O is UTF-8 by default.

## Standard streams

    $*IN.encoding  = 'UTF-16';
    $*OUT.encoding = 'UTF-16';
    $*ERR.encoding = 'UTF-16';

## Filehandle input

    my $fh = open $file, :r, :enc<UTF-16>;

## Filehandle output

    my $fh = open $file, :w, :enc<UTF-16>;
