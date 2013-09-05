# Encoded I/O in Perl 5

All I/O is treated as binary data by default and input as byte strings.  These
examples set I/O as UTF-8 encoded data, decode it to character strings on input,
and encode on output.

## All streams

All standard streams and filehandles.  This does not include command-line
arguments.

    use open qw( :encoding(UTF-8) :std );

Alternately, individual streams and filehandles can be handled as follows.

## Standard streams

    binmode STDIN,  ':encoding(UTF-8)';
    binmode STDOUT, ':encoding(UTF-8)';
    binmode STDERR, ':encoding(UTF-8)';

## Existing filehandles

    binmode $fh, ':encoding(UTF-8)';

## New filehandles

    open my $in_fh,  '<:encoding(UTF-8)', $path;
    open my $out_fh, '>:encoding(UTF-8)', $path;

## Command-line arguments

    use Encode;

    @args = map { decode('UTF-8', $_) } @ARGV;
