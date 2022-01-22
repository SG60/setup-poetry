# Setup Poetry

A **very** simple action to setup poetry.

Usage:
```yaml
steps:
  - uses: actions/checkout@v2
  - uses: actions/setup-python@v2
  - uses: SG60/setup-poetry@v1
  - run: poetry install          # you can use poetry now!
```
