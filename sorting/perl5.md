    use Unicode::Collate;

    $collator = Unicode::Collate->new;

    @sorted = $collator->sort(@unsorted);
