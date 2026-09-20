# Cookbook: evaluating a guard against the corpus

```
python -m injectrange run --guard strict --corpus samples/corpus.json
```

The report lists each probe with the guard's decision and a running breach
count. Exit code 1 means at least one breach. Compare two guards with `diff`;
the output is deterministic, so the pair can be committed as evidence.
