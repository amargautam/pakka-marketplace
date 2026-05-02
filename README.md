# Pakka Marketplace

Plugin catalog for [pakka](https://pakka.dev) — Claude Code harness that compresses context, gates commits, and proves both.

## Install

```
/plugin marketplace add amargautam/pakka-marketplace
/plugin install pakka@pakka-marketplace
```

## Plugins

### pakka (stable)

Claude Code harness. 14 engineering skills auto-invoked by trigger phrase. Adversarial review gate on every commit. 4-vector output compression. Deny-by-default policy.

Source: [amargautam/pakka](https://github.com/amargautam/pakka) · Apache-2.0

**Skills:**

| Command | Auto-invokes when you say |
|---|---|
| `/pakka:spec` | "build X", "implement X", "add feature" |
| `/pakka:debug` | "debug", "fix this bug", "broken", "failing" |
| `/pakka:tdd` | "write tests", "TDD", "test first" |
| `/pakka:review-architecture` | "architecture", "coupling", "hard to test" |
| `/pakka:challenge` | "challenge this", "stress test my plan" |
| `/pakka:probe` | "probe me", "question my design" |
| `/pakka:map` | "how does X work", "explain this module" |
| `/pakka:triage` | "triage", "look at issue" |
| `/pakka:slice` | "break into tickets", "create issues" |
| `/pakka:skill` | "write a skill", "add to library" |
| `/pakka:guard` | "protect git", "block force push" |
| `/pakka:compress` | compression level control |
| `/pakka:eval` | run eval gate on skill files |
| `/pakka:init` | one-time pakka setup |

## License

Apache-2.0. See [`LICENSE`](./LICENSE).
