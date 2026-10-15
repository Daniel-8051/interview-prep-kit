# Topic bank

Broad technical areas for a senior general screen. The examiner sweeps across these — breadth first, not depth. It may ask about areas not listed here, and may open from something on the candidate's CV, but the body of the round is general fundamentals any senior should discuss fluently. Two question modes, tagged:

## [knowledge] — "explain X / when would you use Y"
- Microservices — what they are, when they help, when they hurt, the costs vs a monolith.
- REST API design — how you'd approach designing one, resource modelling, status codes, versioning, idempotency.
- Databases — SQL vs NoSQL, when each, indexing, transactions, what an index actually costs.
- Caching — where, what to cache, invalidation, staleness tradeoffs.
- Message queues / async — when to reach for one, what it buys, ordering and delivery guarantees.
- Containers & orchestration — Docker, Kubernetes: what problem each solves, when you'd not bother.
- Concurrency — threads, race conditions, locks, what goes wrong.
- Testing — unit vs integration vs e2e, what to test where, TDD, coverage as a signal.
- CI/CD — what a good pipeline looks like, deploy strategies, rollback.
- Observability — logging, metrics, tracing; how you debug a slow request in prod.
- Security basics — auth vs authz, OAuth/JWT at a high level, common web vulns.
- API/service failure — timeouts, retries, circuit breakers, graceful degradation.

## [problem-walkthrough] — candidate picks the example
- "In 2-3 minutes: think of a complex problem you've solved. What was the problem, how did you spot it, how did you find the solution, and why did it work?"
- "Tell me about a time you made a technical decision that turned out to be wrong. What happened?"
- "Walk me through the hardest bug you've debugged. How did you approach it?"
- "Describe a system you're proud of. What were the key decisions?"
