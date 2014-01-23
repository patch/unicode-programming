# Letter Casing in Ruby

Letter casing functionality with Unicode semantics is not available in the core
language, only ASCII semantics.  The Ruby gem `unicode_utils` provides this
functionality.

```ruby
require 'unicode_utils'

lowercase = UnicodeUtils.downcase(str)
uppercase = UnicodeUtils.upcase(str)
titlecase = UnicodeUtils.titlecase(str)
casefold  = UnicodeUtils.casefold(str)
```
