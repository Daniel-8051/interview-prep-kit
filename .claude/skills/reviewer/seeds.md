# Problem seeds

Half-built coding tasks the reviewer scaffolds into practice/. Four shapes — cycle through them. Java. The reviewer may generate its own in the same style but must not repeat one listed in history.md.

## [failing-tests] Spec lives in the tests; make them green.
- An LRU cache with capacity eviction — interface given, JUnit tests written and failing, empty method bodies.
- A rate limiter (token bucket) — tests assert allow/deny behaviour over time, implementation stubbed.
- A CSV parser handling quoted fields and escapes — tests cover the edge cases, body empty.

## [feature-add] Working code; add a capability without breaking what's there.
- A small in-memory key-value store — add TTL expiry to existing get/put.
- A paginated list endpoint (plain Java, no framework) — add filtering by a field.
- A retry wrapper — add exponential backoff with a max-attempts ceiling to existing linear retry.

## [find-the-bug] Working-ish code, a real defect, tests that reveal it.
- A binary search with an off-by-one — one test fails, find and fix.
- A concurrent counter with a race — an intermittent-looking test, reason about why.
- A date-range overlap check with a boundary bug — fix without breaking the passing cases.

## [finish-the-stub] Signatures and a written spec, empty bodies.
- A simple event dispatcher (subscribe/publish/unsubscribe) — spec in a README, stubs to fill.
- A URL router matching path patterns with params — spec given, implement the matcher.
- A JSON-ish tokeniser — spec describes the tokens, produce them.
