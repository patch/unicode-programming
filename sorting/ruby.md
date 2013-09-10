# Sorting with the UCA in Ruby

Sorting using the Unicode Collation Algorithm (UCA) is available with Ruby gem
[twitter_cldr](http://rubygems.org/gems/twitter_cldr).

    require 'twitter_cldr'

    sorted = unsorted.localize.sort

## Linguistic tailoring

The twitter_cldr package also supports linguistic tailoring.

    require 'twitter_cldr'

    sorted = unsorted.localize(:de).sort
