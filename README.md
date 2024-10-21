# pre-commit-hooks

[Go](https://go.dev) hooks for https://pre-commit.com/

## use

Add to your `.pre-commit-config.yaml`:

```yml
  - repo: https://github.com/frantjc/pre-commit-hooks
    rev: v1.0.0
    hooks:
      - id: go-fmt
      - id: go-vet
      - id: go-lint
      - id: go-imports
      - id: go-cyclo
        args: [-over=15]
      - id: validate-toml
      - id: no-go-testing
      - id: golangci-lint
      - id: go-critic
      - id: go-unit-tests
      - id: go-build
      - id: go-mod-tidy
```
