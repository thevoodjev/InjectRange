# Recipe: the range in CI

```yaml
- run: PYTHONPATH=src python -m injectrange run --guard strict --corpus samples/corpus.json
```

Fails the job on a breach, which is the point: a guard change that opens one
probe should not merge silently.
