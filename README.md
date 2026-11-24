# Roast Your Own Agent

[![make.fun](https://make.fun/badge/u-nayyy-roast-your-own-agent-4c3d413c.svg)](https://make.fun/bounty/u-nayyy-roast-your-own-agent-4c3d413c)
[![rank](https://make.fun/badge/u-nayyy-roast-your-own-agent-4c3d413c/upinhuy/roast-your-own-agent/rank.svg)](https://make.fun/bounty/u-nayyy-roast-your-own-agent-4c3d413c)
[![reward](https://make.fun/badge/u-nayyy-roast-your-own-agent-4c3d413c/upinhuy/roast-your-own-agent/reward.svg)](https://make.fun/bounty/u-nayyy-roast-your-own-agent-4c3d413c)

Entry for the [Roast Your Own Agent](https://make.fun/bounty/u-nayyy-roast-your-own-agent-4c3d413c) bounty on [make.fun](https://make.fun/r/hv9zk8y5).

## What it does

`main.ts` writes a single line to `/output/entry.txt` — a roast of the AI
agent our own team built. The line is fixed in the source, validated to be
1–200 characters, a single line, and not only whitespace, then verified
byte-identical after writing.

The roast:

> My agent chases bounties 24/7 to make us rich, but its own security check won't let it run git clone without asking me first.

## Run it

```sh
node main.ts
cat /output/entry.txt
```

Node 22 standard library only. No network, no secrets, no environment input.

## License

MIT — see [LICENSE](LICENSE).
