# alifarid

Go developer focused on practical data tooling and backend correctness.

## Selected work

### [sheetframe](https://github.com/Alifarid0011/sheetframe)

An Excel-first DataFrame library for Go: typed nullable tables, immutable
operations, filtering, stable sorting, grouped aggregation, hash joins, and
CSV/XLSX I/O. Includes a browser playground powered by the same Go engine through
WebAssembly, executable examples, and reproducible pandas/Polars/QFrame comparisons.

[Code & documentation](https://github.com/Alifarid0011/sheetframe) ·
[Live playground](https://alifarid0011.github.io/sheetframe/) ·
[v0.2.0](https://github.com/Alifarid0011/sheetframe/releases/tag/v0.2.0) ·
[Benchmark methodology](https://github.com/Alifarid0011/sheetframe/blob/main/docs/BENCHMARKS.md)

### [Design patterns in Go](https://github.com/Alifarid0011/design_patterns)

A catalog of the 23 classic design patterns with Go implementations, behavior
tests, executable examples, and a guide to their tradeoffs and simpler alternatives.
Includes offline HTTP tests, explicit writer ownership, and concurrency checks.

### [go-contributor](https://github.com/Alifarid0011/go-contributor-skill)

A reusable Codex skill for finding useful Go contributions, reproducing bugs,
checking overlapping work, and preparing tested, clearly documented pull requests.

## Open-source work

- [Go x/net/http2: preserve large server concurrency limits](https://github.com/golang/net/pull/275)
  — proposed a wrapper compatibility fix, verified on amd64 and 386 with
  legacy and race-test coverage.
- [Excelize: correct early-1900 date conversion](https://github.com/qax-os/excelize/pull/2467)
  — proposed a calendar-boundary fix that preserves the 1904 date system and
  Excel's historical WEEKDAY behavior.
- [Zerolog: escape custom time layouts](https://github.com/rs/zerolog/pull/828)
  — proposed a JSON encoding fix covering scalar and slice timestamps, with
  regression tests and allocation benchmarks.
- [Fiber: preserve error and redirect statuses in freshness checks](https://github.com/gofiber/fiber/pull/4811)
  — draft fix with conditional-request regressions and a complete passing
  audit, generation, lint, and race-test validation run.

[All public pull requests](https://github.com/pulls?q=is%3Apr+author%3AAlifarid0011)

## Engineering focus

- Explicit APIs and predictable error handling
- Regression tests, race checks, and immutable data ownership
- Measured performance with documented tradeoffs
- Small, reviewable changes and useful documentation
