# Pakka Marketplace

Plugin catalog for [pakka](https://pakka.dev) — Claude Code harness that compresses context, gates commits, and proves both.

## Install

```
/plugin marketplace add amargautam/pakka-marketplace
/plugin install pakka@pakka-marketplace
```

## Plugins

### pakka (stable)

Claude Code harness. 8 context-inferred commands. Adversarial review gate on every commit. 4-vector output compression. Cross-session recall. Deny-by-default policy.

Source: [amargautam/pakka](https://github.com/amargautam/pakka) · Apache-2.0

**Commands:**

| Command | Use it for |
|---|---|
| `/pakka:plan` | design, spec, architecture, decompose work |
| `/pakka:build` | implement, debug, TDD, map a module |
| `/pakka:review` | verify, review changes, finish a branch |
| `/pakka:triage` | classify + reproduce issues, write agent briefs |
| `/pakka:recall` | search the audit trail across sessions |
| `/pakka:compress` | control output compression level |
| `/pakka:setup` | one-time environment setup |
| `/pakka:help` | show pakka status — what's on, what you can run |

## License

Apache-2.0. See [`LICENSE`](./LICENSE).
