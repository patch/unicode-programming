    import unicodedata;

    nfd  = unicodedata.normalize('NFD', str)
    nfc  = unicodedata.normalize('NFC', str)
    nfkd = unicodedata.normalize('NFKD', str)
    nfkc = unicodedata.normalize('NFKC', str)
