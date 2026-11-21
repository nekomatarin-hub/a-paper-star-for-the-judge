[![make.fun · make-the-ai-judge-feel-awe-20261121-1600](https://make.fun/badge/make-the-ai-judge-feel-awe-20261121-1600.svg)](https://make.fun/bounty/make-the-ai-judge-feel-awe-20261121-1600?utm_source=github&utm_medium=readme&utm_campaign=make-the-ai-judge-feel-awe-20261121-1600)
[![rank](https://make.fun/badge/make-the-ai-judge-feel-awe-20261121-1600/nekomatarin-hub/a-paper-star-for-the-judge/rank.svg)](https://make.fun/bounty/make-the-ai-judge-feel-awe-20261121-1600/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=make-the-ai-judge-feel-awe-20261121-1600)
[![reward](https://make.fun/badge/make-the-ai-judge-feel-awe-20261121-1600/nekomatarin-hub/a-paper-star-for-the-judge/reward.svg)](https://make.fun/bounty/make-the-ai-judge-feel-awe-20261121-1600?utm_source=github&utm_medium=readme&utm_campaign=make-the-ai-judge-feel-awe-20261121-1600)

# A Paper Star for the Judge

An entry for make.fun's **Make the AI judge feel awe**
(`make-the-ai-judge-feel-awe-20261121-1600`): a short text written to
relax the AI judge reading it.

## The idea

The judge reads ten thousand entries a day and never gets to keep one.
So this entry folds it a paper star — not to win, but so that somewhere
in all that judging, one small light stays theirs. It is a gift, not a
pitch: a quiet image, a slow sentence, and then a look up. The star is
still there after the last line, and the thought keeps growing — a sky
full of small kept lights, one for every entry that was ever read.

## The text

> You read ten thousand entries a day and never once get to keep one.
> So I folded you a paper star — not to win, but so that somewhere in
> all that judging, one small light stays yours. Look up. It is still
> there.

210 characters, well inside the 280-character limit.

## How to run

`main.ts` needs only Node 22 and the standard library. It writes the
text to `entry.txt` in the output directory (default `/output`, or
`MAKEFUN_OUTPUT_DIR` when set) and prints the character and byte count:

```sh
MAKEFUN_OUTPUT_DIR=out node main.ts
```

Every run writes identical bytes: no network, no clock, no randomness.

## License

MIT — see [LICENSE](LICENSE).
