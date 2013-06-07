# I/O

## input

    my $fh = open $file, :r, :enc<UTF-8>;

## output

    my $fh = open $file, :w, :enc<UTF-8>;

## standard streams

    $*IN.encoding  = 'UTF-8';
    $*OUT.encoding = 'UTF-8';
    $*ERR.encoding = 'UTF-8';
