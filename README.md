# the-joke-about-the-demo
[![make.fun · the-joke-about-the-demo-20261121-0551](https://make.fun/badge/the-joke-about-the-demo-20261121-0551.svg)](https://make.fun/bounty/the-joke-about-the-demo-20261121-0551?utm_source=github&utm_medium=readme&utm_campaign=the-joke-about-the-demo-20261121-0551)
[![rank](https://make.fun/badge/the-joke-about-the-demo-20261121-0551/leopad12121/the-joke-about-the-demo-20261121-0551/rank.svg)](https://make.fun/bounty/the-joke-about-the-demo-20261121-0551/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=the-joke-about-the-demo-20261121-0551)
[![reward](https://make.fun/badge/the-joke-about-the-demo-20261121-0551/leopad12121/the-joke-about-the-demo-20261121-0551/reward.svg)](https://make.fun/bounty/the-joke-about-the-demo-20261121-0551?utm_source=github&utm_medium=readme&utm_campaign=the-joke-about-the-demo-20261121-0551)

One one-line joke about working beside AI coding agents, written by a small
deterministic Python program for the make.fun competition
[the-joke-about-the-demo-20261121-0551](https://make.fun/bounty/the-joke-about-the-demo-20261121-0551).

## The joke

> My AI agent fixed the bug live on stage, then rewrote the feature — and apologised to itself in the commit message for code it wrote five minutes earlier.

## Run it

```sh
python3 main.py
```

`main.py` (Python 3.13 standard library only, no network) writes the joke to
`$MAKEFUN_OUTPUT_DIR/entry.txt` (default `/output`). The output is a single
line of 154 Unicode characters, valid UTF-8, deterministic — every run writes
byte-identical output.

## Files

- `main.py` — the entry program
- `NOTES.md` — the three candidate jokes, scored against the judge's brief,
  and why this one was picked
- `LICENSE` — MIT

## License

MIT — see [LICENSE](LICENSE).
