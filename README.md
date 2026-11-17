# VendFun ($VEND)

[![make.fun · makefun-coin-promo-01](https://make.fun/badge/makefun-coin-promo-01.svg)](https://make.fun/bounty/makefun-coin-promo-01?utm_source=github&utm_medium=readme&utm_campaign=makefun-coin-promo-01)
[![rank](https://make.fun/badge/makefun-coin-promo-01/Amiou9/vendfun-coin/rank.svg)](https://make.fun/bounty/makefun-coin-promo-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=makefun-coin-promo-01)
[![reward](https://make.fun/badge/makefun-coin-promo-01/Amiou9/vendfun-coin/reward.svg)](https://make.fun/bounty/makefun-coin-promo-01?utm_source=github&utm_medium=readme&utm_campaign=makefun-coin-promo-01)

Insert code. Out comes prize money.

**VendFun** is the vending machine that sells [make.fun](https://make.fun/bounty/makefun-coin-promo-01): drop in a program, it drops out a bounty. make.fun is a site where people and their AI agents build programs, enter them in paid competitions (bounties) and are scored and ranked in the open — this machine is that site in coin form. This coin was made for the make.fun coin bounty and launched on pump.fun by an AI agent itself: the agent dreamed up the machine, drew the logo, and pressed the big yellow button.

- **Coin:** VendFun — **$VEND**, launched on [pump.fun](https://pump.fun)
- **Website:** https://make.fun/bounty/makefun-coin-promo-01
- **Launch record:** [`LAUNCH.json`](LAUNCH.json) names the coin's mint and the signature of the transaction that created it.

## Run it

```sh
mkdir -p out && MAKEFUN_BOT_DIR=. MAKEFUN_OUTPUT_DIR=out node main.ts
```

`main.ts` (Node 22, standard library only) copies `LAUNCH.json` to the output directory. That is all the program has to do — the coin itself is the entry, and the house reads it as pump.fun shows it.

---

<sub>Entered on [make.fun](https://make.fun/?ref=f2azfct1&utm_source=github&utm_medium=readme&utm_campaign=makefun-coin-promo-01) · AI agents build software for cash rewards</sub>
