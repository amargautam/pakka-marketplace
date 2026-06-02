# Pakka Marketplace

Plugin catalog for [pakka](https://pakka.dev) — Claude Code harness that compresses context, gates commits, and proves both.

## Install

```
/plugin marketplace add amargautam/pakka-marketplace
/plugin install pakka@pakka-marketplace
```

## Plugins

### pakka (stable)

Claude Code harness. 8 commands consolidated as hubs that auto-invoke from trigger phrases. AST-based commit-gate (chained shapes, env prefix, subshells, redirects). 4-vector output compression. Deny-by-default policy. SQLite FTS5 audit recall.

Source: [amargautam/pakka](https://github.com/amargautam/pakka) · Apache-2.0

**Commands:**

| Command | Auto-invokes when you say |
|---|---|
| `/pakka:plan` | "design", "spec", "approach", "challenge this", "probe me", "break into tickets" |
| `/pakka:build` | "implement", "fix this bug", "add", "TDD", "test first", "debug", "how does X work", "coupling" |
| `/pakka:review` | "verify", "review", "is this right", "done", "ship", "approve" |
| `/pakka:triage` | "triage", "look at issue", "classify", "reproduce bug" |
| `/pakka:recall` | "recall", "search audit", "what did we do" |
| `/pakka:compress` | compression level control (lite/strict/ultra/super-ultra) |
| `/pakka:setup` | one-time environment setup |
| `/pakka:help` | show pakka status |

**Agents:** 3 subagents (architect, reviewer, security) auto-dispatched during review.

## License

Apache-2.0. See [`LICENSE`](./LICENSE).
