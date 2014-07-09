# Unicode normalization in Julia

The core `normalize_string` function returns a string in the specified
normalization form.

```julia
nfd  = normalize_string(str, :NFD)
nfc  = normalize_string(str, :NFC)
nfkd = normalize_string(str, :NFKD)
nfkc = normalize_string(str, :NFKC)
```

* Requires: Julia 3.0
* Docs: http://julia.readthedocs.org/en/latest/stdlib/base/#Base.normalize_string
