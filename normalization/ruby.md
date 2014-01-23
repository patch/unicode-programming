# Unicode normalization in Ruby

Unicode normalization is available in the gem packages
[unicode](http://rubygems.org/gems/unicode) and
[unicode_utils](http://rubygems.org/gems/unicode_utils).

```ruby
require 'unicode';

nfd  = Unicode::normalize_D(str)
nfc  = Unicode::normalize_C(str)
nfkd = Unicode::normalize_KD(str)
nfkc = Unicode::normalize_KC(str)
```

or

```ruby
require 'unicode_utils';

nfd  = UnicodeUtils.nfd(str)
nfc  = UnicodeUtils.nfc(str)
nfkd = UnicodeUtils.nfkd(str)
nfkc = UnicodeUtils.nfkc(str)
```
