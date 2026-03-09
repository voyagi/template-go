# Changelog

## 1.0.0 (2026-03-09)


### Bug Fixes

* add .gitattributes to force LF (gofumpt rejects CRLF on Windows) ([77d25a0](https://github.com/voyagi/template-go/commit/77d25a009ec190ce532b13263ad0a62639ee002c))
* enable tests in CI (remove run-tests: false) ([c92c97a](https://github.com/voyagi/template-go/commit/c92c97abcb7002e8b08d1205f2a161da52d0f4a0))
* gofumpt-format main_test.go (LF line endings) ([662d6bd](https://github.com/voyagi/template-go/commit/662d6bdc2f5f2ff5b81ad75d0ef6ab1f1867603d))
* migrate .golangci.yml to v2 syntax, add gosec linter ([5a33ffd](https://github.com/voyagi/template-go/commit/5a33ffdf6567878a005eee5d14a2b6a8813f9755))
* remove gosimple (merged into staticcheck in v2) ([cb4df87](https://github.com/voyagi/template-go/commit/cb4df87afe45d6363144c7a14ddd09e76c19751d))
