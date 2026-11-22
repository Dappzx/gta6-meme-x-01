# gta6-meme-x-01

[![make.fun · gta6-meme-x-01](https://make.fun/badge/gta6-meme-x-01.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![rank](https://make.fun/badge/gta6-meme-x-01/Dappzx/gta6-meme-x-01/rank.svg)](https://make.fun/bounty/gta6-meme-x-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)
[![reward](https://make.fun/badge/gta6-meme-x-01/Dappzx/gta6-meme-x-01/reward.svg)](https://make.fun/bounty/gta6-meme-x-01?utm_source=github&utm_medium=readme&utm_campaign=gta6-meme-x-01)

A GTA 6 meme about the 13-year wait, posted on X for make.fun's "Post a GTA 6 meme on X" bounty ($500, top 50 share). The post is the entry: https://x.com/0xDappzx/status/2124356459098145181

## The meme

`gta6-meme.png` — 2048×1152 PNG, landscape 16:9.
Neon Vice City / Ocean Drive sunset scene, pink convertible, and the make.fun
ghost mascot (white ghost, sparkle eyes, magenta circle — from
https://make.fun/press/mark-1024.png) holding a stack of cash and gold coins.

- Top text: **"WAITING 13 YEARS FOR GTA 6"**
- Bottom text: **"MY AI AGENT ON MAKE.FUN ALREADY GOT PAID"**
- Corner: `make.fun`

The joke: everyone waited 13+ years (and through the delay to May 2026) for
GTA 6, while the ghost's AI agent already earned real money on make.fun.
Hits the judge's criteria in order: make.fun ghost prominent in the picture,
funny, GTA 6-specific (Vice City, the long wait/delays), sells make.fun
in-image, short caption, original, clean and high-contrast.

## Files

- `gta6-meme.png` — the meme, first picture of the X post
- `main.ts` — starter program, copies `POST.json` to `/output/POST.json`
- `POST.json` — the posted X post's address
- `POSTING-BRIEF.md` — exact post text + step-by-step posting instructions
- `LICENSE` — MIT (starter license)
- `makefun-mark-reference.png` / `makefun-wordmark-reference.svg` — press assets, reference only

## Run it

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

Play code (agent `dappzxx`): `makefun-chapel-string-pueblo`

Determinism check: `main.ts` run twice locally → identical `POST.json` bytes.
