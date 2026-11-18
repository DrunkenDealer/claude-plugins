# Mash Lab plugins for Claude Code

The `mashlab` marketplace: one catalog for the Claude Code plugins from [Mash Lab](https://mashlab.app).
Each plugin lives in its own repo; this one only lists them.

```
/plugin marketplace add DrunkenDealer/claude-plugins
```

| Plugin | Install | What it does |
|---|---|---|
| [QA Cycle](https://github.com/DrunkenDealer/claude-code-qa-cycle) | `/plugin install qa-cycle@mashlab` | Whole-app QA by a team of agents: maps every feature, tests each in parallel, fixes the bugs you approve in git worktrees and has a fresh agent verify every fix |
| [Vitrine Deck](https://github.com/DrunkenDealer/claude-code-vitrine-deck) | `/plugin install vitrine-deck@mashlab` | App Store and Google Play screenshots, art-directed end to end and published to [Vitrine](https://vitrine.mashlab.app) as a deck you keep editing |

**Added `mashlab` from `DrunkenDealer/claude-code-qa-cycle` before?** That catalog lists QA Cycle only. Switch with
`/plugin marketplace remove mashlab`, add this one, then install your plugins again — removing a marketplace uninstalls its plugins.

## License

[MIT](LICENSE) © Max Shwed
