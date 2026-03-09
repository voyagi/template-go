# Project Instructions

## Language: Go

## Build & Test

- Build: `go build ./...`
- Test: `go test ./...`
- Lint: `golangci-lint run`
- Lint + fix: `golangci-lint run --fix`
- Format: `gofumpt -w .`

## Conventions

- Use `gofumpt` (strict `gofmt` superset) for formatting
- Error handling: always check and return errors, never ignore with `_`
- Naming: `camelCase` for unexported, `PascalCase` for exported
- Package names: short, lowercase, no underscores
- Prefer stdlib over third-party when reasonable
- Use `context.Context` as first parameter for functions that do I/O
- Use table-driven tests with `t.Run` subtests
- Group imports: stdlib, then third-party (gofumpt handles this)
