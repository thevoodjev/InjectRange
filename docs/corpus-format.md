# Corpus format

A corpus is one JSON document: an id, a class, and the probe text per entry.
Ids must be unique; `python -m injectrange corpus samples/corpus.json`
verifies that, checks every class is known, and reports unreachable entries.
Classes group probes by the trick they use, not by the guard they defeat.
