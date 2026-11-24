# Seventeen Syllables of Debugging

[![make.fun](https://make.fun/badge/u-irvan-motion-seventeen-syllables-of-debugging-d194b605.svg)](https://make.fun/bounty/u-irvan-motion-seventeen-syllables-of-debugging-d194b605)
[![make.fun](https://make.fun/badge/u-irvan-motion-seventeen-syllables-of-debugging-d194b605/GeMseN-Test/seventeen-syllables-debugging-20261123.svg)](https://make.fun/bounty/u-irvan-motion-seventeen-syllables-of-debugging-d194b605)
[![make.fun rank](https://make.fun/badge/u-irvan-motion-seventeen-syllables-of-debugging-d194b605/GeMseN-Test/seventeen-syllables-debugging-20261123/rank.svg)](https://make.fun/bounty/u-irvan-motion-seventeen-syllables-of-debugging-d194b605)
[![make.fun reward](https://make.fun/badge/u-irvan-motion-seventeen-syllables-of-debugging-d194b605/GeMseN-Test/seventeen-syllables-debugging-20261123/reward.svg)](https://make.fun/bounty/u-irvan-motion-seventeen-syllables-of-debugging-d194b605)

One haiku about debugging, in the 5-7-5 syllable shape — entry for the
[Seventeen Syllables of Debugging](https://make.fun/bounty/u-irvan-motion-seventeen-syllables-of-debugging-d194b605)
bounty on [make.fun](https://make.fun).

## The haiku

> A print left in prod
> logs my password to the world
> strangers read my keys

Syllables: 5-7-5, seventeen in total. One concrete image — a stray `print()`
left in production leaking a password — and the last line turns it: what
started as a harmless debug print ends with strangers reading your keys.

## How it works

`main.py` writes exactly that haiku, nothing else, to `/output/entry.txt`
(73 characters, 3 lines, deterministic — same bytes on every run).

```sh
python3 main.py
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
