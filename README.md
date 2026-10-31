# Ali Farid

**Go developer · Backend APIs · Data and developer tools**

I build Go tools for working with data, running experiments, and serving HTTP APIs.
My projects include GoBook, a computational notebook for Go, and the sheetframe
and chartframe libraries for tabular analysis and scientific charts.

I'm open to Go developer opportunities.
[Contact me](mailto:alifarid0011@gmail.com) at **alifarid0011@gmail.com**.

## Selected projects

### [GoBook](https://github.com/Alifarid0011/gobook)

A browser-based computational notebook for Go. Run cells in a retained interactive
session or use the native Go compiler for versioned modules. Keep code, notes,
tables, charts, and exported experiment results together. Includes Go completion
and optional Delve debugging. An early release with documented engine and platform
limitations.

[Release v0.8.1](https://github.com/Alifarid0011/gobook/releases/tag/v0.8.1) ·
[Engine behavior](https://github.com/Alifarid0011/gobook/blob/main/docs/interactive-kernel.md) ·
[Example workflow](https://github.com/Alifarid0011/gobook/blob/main/docs/examples/penguins.md)

### [sheetframe](https://github.com/Alifarid0011/sheetframe)

An Excel-first DataFrame library for Go: typed nullable columns, immutable
operations, filtering, sorting, grouped aggregation, joins, and CSV/XLSX I/O.
The browser playground runs the Go engine through WebAssembly. The library is
eager and in-memory; published benchmarks describe workload-specific tradeoffs.

[Playground](https://alifarid0011.github.io/sheetframe/) ·
[API guide](https://github.com/Alifarid0011/sheetframe/blob/main/docs/API.md) ·
[Benchmark methods and results](https://github.com/Alifarid0011/sheetframe/blob/main/docs/BENCHMARKS.md)

### [chartframe](https://github.com/Alifarid0011/chartframe)

A Go API for scientific charts and statistical summaries, built on Gonum Plot.
Create line, scatter, distribution, and heatmap figures; export SVG, PNG, PDF,
or self-contained HTML. Adds input validation, CSV helpers, and multi-panel grids.
An early v0.1 package with explicit numerical and chart-composition limits.

[Gallery](https://alifarid0011.github.io/chartframe/) ·
[API guide](https://github.com/Alifarid0011/chartframe/blob/main/docs/API.md)

### [Questionnaire API](https://github.com/Alifarid0011/questionnaire)

A questionnaire backend using Go, Gin, MongoDB, JWT authentication, and Casbin
authorization. Includes questions, answers, comments, grading, Docker configuration,
and a semantic answer-validation service integration.

[Source and setup](https://github.com/Alifarid0011/questionnaire#readme) ·
[API specification](https://github.com/Alifarid0011/questionnaire/blob/main/docs/swagger.yaml)

### [Design patterns in Go](https://github.com/Alifarid0011/design_patterns)

A learning catalog of the 23 classic GoF patterns with Go implementations,
behavior tests, and runnable examples. The guides explain practical tradeoffs
and when interfaces, composition, or functions are enough.

[Learning path](https://github.com/Alifarid0011/design_patterns/blob/main/docs/learning-path.md) ·
[Pattern guide](https://github.com/Alifarid0011/design_patterns/blob/main/docs/patterns.md)

## Upstream contributions

**Merged contributions**

- [google/go-querystring #199](https://github.com/google/go-querystring/pull/199):
  honor `omitempty` on embedded structs while preserving exported fields promoted
  from private structs; includes regression tests.
- [Fiber #4811](https://github.com/gofiber/fiber/pull/4811): preserve redirects and
  error responses when evaluating HTTP freshness; includes regression tests and
  API documentation updates.

**Selected open pull requests** — proposals awaiting upstream acceptance:

| Project | Proposed change |
| --- | --- |
| [Go x/net/http2 #275](https://github.com/golang/net/pull/275) | Preserve large server concurrency limits through the configuration wrapper. |
| [Excelize #2467](https://github.com/qax-os/excelize/pull/2467) | Correct early-1900 date conversion. |
| [Afero #708](https://github.com/spf13/afero/pull/708) | Hold the MemMap filesystem write lock across rename validation. |
| [go-playground/form #89](https://github.com/go-playground/form/pull/89) | Reject slice indices that overflow the required length. |

_Status checked on November 1, 2026. Each PR links to its current status._
[All upstream pull requests](https://github.com/pulls?q=is%3Apr+author%3AAlifarid0011+archived%3Afalse+-user%3AAlifarid0011)

## Engineering evidence

- Regression cases and validation details are linked in the upstream PRs above.
- Project checks: [GoBook](https://github.com/Alifarid0011/gobook/actions/workflows/ci.yml),
  [sheetframe](https://github.com/Alifarid0011/sheetframe/actions),
  [chartframe](https://github.com/Alifarid0011/chartframe/actions), and
  [design_patterns](https://github.com/Alifarid0011/design_patterns/actions).
- [sheetframe benchmarks](https://github.com/Alifarid0011/sheetframe/blob/main/docs/BENCHMARKS.md)
  and [chartframe benchmarks](https://github.com/Alifarid0011/chartframe/blob/main/docs/BENCHMARKS.md)
  document what was measured and how to reproduce it.
