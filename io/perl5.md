# I/O

## everything

    use open qw( :encoding(UTF-8) :std );

## input

    open my $fh, '<:encoding(UTF-8)', $file;

## output

    open my $fh, '>:encoding(UTF-8)', $file;

## standard streams

    binmode STDIN, ':encoding(UTF-8)';
    binmode STDOUT, ':encoding(UTF-8)';
    binmode STDERR, ':encoding(UTF-8)';
