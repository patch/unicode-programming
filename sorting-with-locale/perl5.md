    use Unicode::Collate::Locale;

    $collator = Unicode::Collate::Locale->new(locale => 'de');

    @sorted = $collator->sort(@unsorted);
