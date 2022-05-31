# Anchor Build Action

Github action for running anchor builds

### Example

```yaml
build:
  runs-on: ubuntu-latest
  steps:
    - uses: actions/checkout@v2
    - name: Anchor Build
      uses: AtivSolana/anchor-build-action@v0.24.2:a
      with:
        args: <custom build args>
```
