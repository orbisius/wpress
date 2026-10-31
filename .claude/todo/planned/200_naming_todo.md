# Naming — todo

- [ ] [P200] The test data dir is `testdata/`; test data lives in `tests/data/` at the repo root.
  Move it there and update the `TestDataName` value that names it, `reader_test.go:34`. It holds
  only data files, so go.mod needs no `ignore ./tests/data` line. Found 2026-10-31 by a find across
  the Go projects (run).
