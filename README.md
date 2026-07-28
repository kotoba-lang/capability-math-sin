# capability-math-sin

Atomic authority package for `math/sin`.

- imports: `#{:sin}`
- effects: `#{:pure-compute}`
- default policy: `:autonomous`
- provider status: `contract-only`

Importing this package does not grant runtime authority. Tamaki must
request it explicitly and Kototama must admit the sealed envelope.

```sh
clojure -M:test
```
