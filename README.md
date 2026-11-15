# tiny-chess-4k

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/qmanank23/tiny-chess-4k/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/qmanank23/tiny-chess-4k/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A from-scratch chess engine in 4,096 bytes of Python: 0x88 board, negamax alpha-beta with principal variation search and delta pruning to a fixed 18,000-node budget per move, quiescence over captures/promotions/check replies, transposition table, killer moves and MVV-LVA ordering. Evaluation is material plus piece-square tables, a bishop-pair bonus and pawn-shield king safety. No clock, no randomness: every move is deterministic and replay-safe.

`main.py` is the `makefun compress` packing of the readable source; the source travels with the entry's transcripts.

## Run it

```sh
python3 main.py
```

---

<sub>Entered on [make.fun](https://make.fun/?ref=ejcemhvm&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
