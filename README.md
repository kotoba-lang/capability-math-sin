# capability-math-sin

Atomic authority package for `math/sin`.

- imports: `#{:sin}`
- effects: `#{:pure-compute}`
- default policy: `:autonomous`
- semantic definition CID: `bafyreihwvwupzz3hlfsjlnlgsegwywfuwclpbld5upvxfqcomq65e4kub4`
- hash contract CID: `bafkreiflhj3fslsbh7okdas2fzlhmogai64x6p3lkla6gtr7berbp7ftvi`
- provider status: `contract-only`

The repository name is a discovery alias. The semantic definition CID
is the immutable import identity. Importing it does not grant runtime
authority: Tamaki must request it explicitly and Kototama must admit
the sealed envelope.

```sh
clojure -M:test
```
