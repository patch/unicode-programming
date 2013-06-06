    $nfd  = Normalizer::normalize($str, Normalizer::Form_D);
    $nfc  = Normalizer::normalize($str, Normalizer::Form_C);
    $nfkd = Normalizer::normalize($str, Normalizer::Form_KD);
    $nfkc = Normalizer::normalize($str, Normalizer::Form_KC);
