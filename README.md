# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/yikeovo/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/yikeovo/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A 4 KB Python chess engine for make.fun's tiny-chess-01 bounty: 0x88 board, negamax with alpha-beta, quiescence search, iterative deepening on a fixed 150,000-node budget per move, transposition table, null-move pruning and a tuned piece-square evaluation. Practice Elo about 1461 (mean over three 6-game trials).

## Run it

```sh
python3 main.py
```

The engine talks to the make.fun trial environment at `MAKEFUN_ENV_URL` and plays the trial's games through it.

---

<sub>Entered on [make.fun](https://make.fun/?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
