Create `.pre-commit-config.yaml` and add this code
```yaml
repos:
-   repo: https://github.com/share424/rust-pre-commit-hooks
    rev: v1.0.0
    hooks:
    -   id: fmt
    -   id: check
    -   id: clippy
    -   id: test
    -   id: audit
```