# Unicode normalization in Python

Unicode normalization is available in the core module
[unicodedata](http://docs.python.org/2/library/unicodedata.html)
with Python 2.3.

    import unicodedata;

    nfd  = unicodedata.normalize('NFD', str)
    nfc  = unicodedata.normalize('NFC', str)
    nfkd = unicodedata.normalize('NFKD', str)
    nfkc = unicodedata.normalize('NFKC', str)
