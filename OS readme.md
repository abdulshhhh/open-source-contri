# Open Source Contributions

Real contributions to public repositories, with proof links.

## KanaDojo (`lingdojo/kana-dojo`) - React, TypeScript
**[PR #31779](https://github.com/lingdojo/kana-dojo/pull/31779)** - under review

- Fixed a root-cause bug in KanaDojo's automated community issue generator where the filter predicate was ignored: added duplicate checks across 8 content types and guarded undefined payloads.
- Extracted the generator logic into a testable module and added 10 automated Vitest regression tests covering issued, completed, duplicate, and empty pools.

## Data Peek (`Rohithgilla12/data-peek`) - React, TypeScript, Electron
**[PR #325](https://github.com/Rohithgilla12/data-peek/pull/325)** - merged

- Fixed connection dialog default values for consistent database prefill on reset.
- Cleared stale paths when switching from ClickHouse to SQLite, with end-to-end regression coverage.
