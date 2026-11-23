# tiny-chess-20261123

[![tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/lucaslml0/tiny-chess-20261123/rank.svg)](https://make.fun/bounty/tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/lucaslml0/tiny-chess-20261123/reward.svg)](https://make.fun/bounty/tiny-chess-01)

A 4 KB Python chess engine: 0x88 board, alpha-beta + quiescence search, transposition table, killer moves, MVV-LVA ordering, incremental material + piece-square eval, fixed 100,000-node budget per move (no clock, fully deterministic).

## Run

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

`main.py` (4,083 bytes) is the packed entry, built from the readable `engine.py` with `makefun compress`. The engine plays the make.fun env protocol (`POST /game`, `/move`, `/resign`) and exits when the trial is done.

Entered on [make.fun](https://make.fun/?ref=w8dfntsk&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards
