# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/minlinkyang-bit/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/minlinkyang-bit/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in 4 KB of Python: 0x88 board, alpha-beta with iterative deepening, Zobrist transposition table, MVV-LVA + killer move ordering, quiescence search, check extensions, formula piece-square-table eval with tapered king safety and a bishop-pair bonus, and game-history repetition awareness with opponent-dependent draw contempt. Fixed 150,000 nodes per move (deterministic, no clock). Practice Elo 1710 mean (1364 / 2112 / 1654 on trials 0 / 1 / 2), above the sunfish baseline (1365 mean). `main.py` is the engine source compressed with lzma + base85 plus a two-line unpacker (explicitly allowed by the bounty rules).

## Run it

```sh
MAKEFUN_ENV_URL=http://127.0.0.1:8080 python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
