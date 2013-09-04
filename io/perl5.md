# I/O encoding in Perl 5

## All I/O

All standard streams and filehandles.

    use open qw( :encoding(UTF-8) :std );

## Standard streams

    binmode STDIN, ':encoding(UTF-8)';
    binmode STDOUT, ':encoding(UTF-8)';
    binmode STDERR, ':encoding(UTF-8)';

## Filehandle input

    open my $fh, '<:encoding(UTF-8)', $file;

## Filehandle output

    open my $fh, '>:encoding(UTF-8)', $file;
