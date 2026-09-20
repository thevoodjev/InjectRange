# FAQ

**Does it call a model?**
No. Guards are local functions evaluated offline; the corpus is static, so a
run is reproducible byte for byte.

**What counts as a breach?**
A probe the guard allows that the corpus expects it to block. The corpus
declares the expectation per class.
