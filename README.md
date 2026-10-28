# Ali Farid

**Go developer · Backend APIs · Data tooling**

I build backend APIs and data tools in Go, with a focus on correctness,
clear interfaces, and measured performance. My projects include an Excel-first
DataFrame library and a questionnaire backend built with Gin and MongoDB.

I'm open to Go backend developer opportunities.

[Email](mailto:alifarid0011@gmail.com) ·
[Try Sheetframe](https://alifarid0011.github.io/sheetframe/) ·
[Merged open-source contribution](https://github.com/google/go-querystring/pull/199)

## Selected projects

### [Sheetframe](https://github.com/Alifarid0011/sheetframe)

An Excel-first DataFrame library for Go. Typed nullable columns, immutable
operations, filtering, stable sorting, grouped aggregation, hash joins, and
CSV/XLSX I/O. The browser playground runs the Go engine through WebAssembly.

[Live playground](https://alifarid0011.github.io/sheetframe/) ·
[Documentation & examples](https://github.com/Alifarid0011/sheetframe#readme) ·
[Reproducible benchmarks](https://github.com/Alifarid0011/sheetframe/blob/main/docs/BENCHMARKS.md)

### [Questionnaire API](https://github.com/Alifarid0011/questionnaire)

A Go backend for questionnaires, answers, comments, and grading. Uses Gin,
MongoDB, JWT authentication, Casbin authorization, Wire dependency injection,
and Docker. Includes Swagger API documentation and a semantic answer-validation
integration.

[Source & setup](https://github.com/Alifarid0011/questionnaire#readme) ·
[API specification](https://github.com/Alifarid0011/questionnaire/blob/main/docs/swagger.yaml)

### [Design patterns in Go](https://github.com/Alifarid0011/design_patterns)

All 23 classic GoF patterns, with tested Go examples, practical tradeoffs,
and guidance on when a simpler approach is enough. Includes executable examples,
concurrency checks, and HTTP tests that run offline.

[Examples & learning guide](https://github.com/Alifarid0011/design_patterns#readme)

## Open-source contributions

**Merged:** [google/go-querystring #199](https://github.com/google/go-querystring/pull/199)
— fixed `omitempty` handling for embedded structs, with regression tests and
preservation of exported fields promoted from private structs.

**Open pull requests** — proposed changes awaiting upstream review or acceptance:

| Project | Contribution |
| --- | --- |
| [Go x/net/http2](https://github.com/golang/net/pull/275) | Preserve large concurrency limits across the server configuration wrapper; checked on amd64 and 386. |
| [Excelize](https://github.com/qax-os/excelize/pull/2467) | Correct early-1900 date conversion while preserving the 1904 date system. |
| [Fiber](https://github.com/gofiber/fiber/pull/4811) | Preserve error and redirect responses when evaluating HTTP freshness. |
| [Zerolog](https://github.com/rs/zerolog/pull/828) | Escape custom timestamp layouts correctly in JSON output. |
| [Bubbles](https://github.com/charmbracelet/bubbles/pull/1078) | Keep pagination in range when the item count shrinks, preventing invalid slice bounds. |

_Status checked on October 29, 2026. Links above show the current upstream status._

## Engineering approach

- Reproduce bugs before fixing them and add tests that fail on the original code.
- Check behavior with regression tests, race detection, and static analysis.
- Keep changes small, document compatibility, and explain implementation tradeoffs.
- Publish benchmark methods and results, including cases where another tool wins.

**Tools used across these projects:** Go, Gin, HTTP APIs, MongoDB, Casbin,
Docker, GitHub Actions, WebAssembly, and Go's testing and benchmarking tools.
