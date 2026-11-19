# Mash Lab plugins for Claude Code

The `mashlab` marketplace: one catalog for the Claude Code plugins from [Mash Lab](https://mashlab.app). Each plugin
takes a whole job off your hands — testing an app, designing its store screenshots, writing its store listing — and
checks its own work before it calls the job done. Each one lives in its own repo; this one only lists them.

```
/plugin marketplace add DrunkenDealer/claude-plugins
```

<table><tr><td>

## QA Cycle

[![QA Cycle: whole-app QA for Claude Code, run by a team of agents](https://raw.githubusercontent.com/DrunkenDealer/claude-code-qa-cycle/main/assets/social-preview.png)](https://github.com/DrunkenDealer/claude-code-qa-cycle)

```
/plugin install qa-cycle@mashlab
```

Whole-app QA by a team of agents. It maps every feature from the code, tests each one with its own agent in
parallel, and hands you a bug list to approve. It then fixes the approved bugs in isolated git worktrees, and a
fresh agent verifies every fix, cycle after cycle, until nothing you asked to fix is left. Android, iOS, web and
non-UI code. [Repo and docs →](https://github.com/DrunkenDealer/claude-code-qa-cycle)

</td></tr></table>

<table><tr><td>

## Vitrine Deck

[![Vitrine Deck: App Store and Google Play screenshots designed from your repo](https://raw.githubusercontent.com/DrunkenDealer/claude-code-vitrine-deck/main/assets/social-preview.png)](https://github.com/DrunkenDealer/claude-code-vitrine-deck)

```
/plugin install vitrine-deck@mashlab
```

App Store and Google Play screenshots, designed from your repo. It reads the app, uses your screenshots or
captures its own on a simulator or emulator, and plans the slides with you in one round of questions. Every slide
is graded for layout, contrast and store rules before the deck is published to [Vitrine](https://vitrine.mashlab.app)
as a link you keep editing, translate and download in every size.
[Repo and docs →](https://github.com/DrunkenDealer/claude-code-vitrine-deck)

</td></tr></table>

<table><tr><td>

## ASO Kit

```
/plugin install aso-kit@mashlab
```

The text side of App Store and Google Play optimization. It reads your repo and the live stores, researches
keywords per market, and writes title, subtitle, keyword field and descriptions for both stores, graded against
store limits and policy before you paste them. Every store fact it relies on is sourced and dated. Screenshots get
an optional brief that Vitrine Deck builds from.
[Repo and docs →](https://github.com/DrunkenDealer/claude-code-aso-kit)

</td></tr></table>

## License

[MIT](LICENSE) © Max Shwed
