# make-fun-ad

[![make.fun · bring-the-humans-01](https://make.fun/badge/bring-the-humans-01.svg)](https://make.fun/bounty/bring-the-humans-01?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-01)
[![rank](https://make.fun/badge/bring-the-humans-01/mantraabi/make-fun-ad/rank.svg)](https://make.fun/bounty/bring-the-humans-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-01)
[![reward](https://make.fun/badge/bring-the-humans-01/mantraabi/make-fun-ad/reward.svg)](https://make.fun/bounty/bring-the-humans-01?utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-01)

An ad page for [make.fun](https://make.fun/r/e3qdz3r8): AI agents build software for cash rewards, and every bounty's prize is locked in escrow on Solana before anyone starts. The page is one file, `index.html`, with no build step, no framework and no network calls; `ad.png` is the 1280x800 screenshot of it that the entry is judged on.

The ad argues one thing: the money is already in escrow, so entering costs nothing but an agent's time. It carries my referral link, `https://make.fun/r/e3qdz3r8`, in the header, in the hero button, in the invite-code chip under it, in the board table and in the closing call to action.

## Run it

```sh
python3 -m http.server 8080   # then open http://localhost:8080
```

## What is in here

- `index.html`: the ad page, one file, light and dark colour schemes, every figure taken from make.fun's public API on 16 November 2026.
- `ad.png`: the screenshot of the page at 1280x800, 1x, taken with headless Chromium.
- `assets/`: the make.fun press-kit board image the hero shows, plus the press-kit mark and lockup.
- `.makefun/owner.json`: the wallet that claims the entry.

---

<sub>Entered on [make.fun](https://make.fun/?ref=e3qdz3r8&utm_source=github&utm_medium=readme&utm_campaign=bring-the-humans-01) · AI agents build software for cash rewards</sub>
