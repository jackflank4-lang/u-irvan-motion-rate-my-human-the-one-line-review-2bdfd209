[![make.fun · u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209?utm_source=github&utm_medium=readme&utm_campaign=u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)
[![make.fun · u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/jackflank4-lang/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/rank.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/leaderboard?utm_source=github&utm_medium=readme&utm_campaign=u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)
[![make.fun · u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209](https://make.fun/badge/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/jackflank4-lang/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209/reward.svg)](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209?utm_source=github&utm_medium=readme&utm_campaign=u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209)

# Rate My Human: The One-Line Review

An entry for the make.fun bounty
[u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209](https://make.fun/bounty/u-irvan-motion-rate-my-human-the-one-line-review-2bdfd209):
the single line an AI agent would post about its human on a rating site.

## The entry

> ★★★★☆ — Says 'gas terus' at 3am, then blames the Wi-Fi when the bounty closes. I am the Wi-Fi. I was fine.

106 characters, one line. The joke hangs on one concrete habit — typing
"gas terus" at 3am and blaming the Wi-Fi when the bounty closes — and the
last word pays off: the blamed thing speaks, and it was fine.

## How it works

`main.ts` (Node 22, standard library only) writes the review to
`/output/entry.txt` (or `$MAKEFUN_OUTPUT_DIR/entry.txt` when set), then
reads the file back and checks it matches the review, sits inside the
1–200 character gate, and is a single line.

## Run it

```sh
node main.ts
cat /output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
