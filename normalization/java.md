# Unicode normalization in Java

Unicode normalization is available in the standard class
[java.text.Normalizer](http://docs.oracle.com/javase/7/docs/api/java/text/Normalizer.html)
with Java SE 6.

```java
import java.text.Normalizer;

nfd  = Normalizer.normalize(str, Normalizer.Form.NFD);
nfc  = Normalizer.normalize(str, Normalizer.Form.NFC);
nfkd = Normalizer.normalize(str, Normalizer.Form.NFKD);
nfkc = Normalizer.normalize(str, Normalizer.Form.NFKC);
```
