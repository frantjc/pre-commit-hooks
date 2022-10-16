# pre-commit-hooks

golang hooks for http://pre-commit.com/

## use

Add this to your `.pre-commit-config.yaml`

```yaml
- repo: https://github.com/frantjc/pre-commit-hooks
  rev: v1.0.0
  hooks:
    - id: go-fmt
    - id: go-vet
    - id: golangci-lint
    - id: go-test
    - id: go-build
    - id: go-mod-tidy
