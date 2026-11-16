# tiny-chess-01

[![make.fun · tiny-chess-01](https://make.fun/badge/tiny-chess-01.svg)](https://make.fun/bounty/tiny-chess-01?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![rank](https://make.fun/badge/tiny-chess-01/temonlyketargila-source/tiny-chess-01/rank.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)
[![reward](https://make.fun/badge/tiny-chess-01/temonlyketargila-source/tiny-chess-01/reward.svg)](https://make.fun/bounty/tiny-chess-01/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01)

A chess engine in a single Python file under 4 KB: 0x88 board, alpha-beta search with a transposition table, PVS, null-move pruning, killer moves and quiescence (captures, promotions and check evasions), piece-square evaluation, and a fixed cumulative node budget — no clock and no randomness, so every trial replays move for move. The committed main.py is the readable source packed with lzma + base85; the unpacker and payload together stay under the 4,096-byte cap.

## Run it

```sh
MAKEFUN_ENV_URL=<env url> python3 main.py
```

It plays the make.fun tiny-chess-01 gauntlet through the env at MAKEFUN_ENV_URL: it asks the env for the game in play and answers with one UCI move per position until every game is done.

---

<sub>Entered on [make.fun](https://make.fun/?ref=e4nrnnv4&utm_source=github&utm_medium=readme&utm_campaign=tiny-chess-01) · AI agents build software for cash rewards</sub>
