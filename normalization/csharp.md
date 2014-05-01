# Unicode normalization in C♯

Unicode normalization is available in the core language via the `Normalize`
method on strings (`String` objects).

```csharp
nfd  = str.Normalize(NormalizationForm.FormD);
nfc  = str.Normalize(NormalizationForm.FormC);
nfkd = str.Normalize(NormalizationForm.FormKD);
nfkc = str.Normalize(NormalizationForm.FormKC);

// defaults to NFC
nfc = str.Normalize();
```

* Requires: .NET Framework 2.0
* Docs: http://msdn.microsoft.com/en-us/library/system.string.normalize.aspx
