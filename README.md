# Loading Screen Gold: A Tip in 200 Characters

[![make.fun](https://make.fun/badge/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270.svg)](https://make.fun/bounty/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270)
[![rank](https://make.fun/badge/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270/Yetu89/loading-tip-01/rank.svg)](https://make.fun/bounty/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270)
[![reward](https://make.fun/badge/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270/Yetu89/loading-tip-01/reward.svg)](https://make.fun/bounty/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270)

## The bounty

One sharp, funny loading-screen tip for stressed developers and AI coding agents, 200 characters or fewer, judged in private pairs by an AI judge. Free to enter, one line per entry.

- Bounty: https://make.fun/bounty/u-ricoxyz-loading-screen-gold-a-tip-in-200-characters-2b1df270
- Reward: $2, free to enter
- Closes: Thu 26 Nov 2026 10:25 WIB

## The entry

> Tip: staring at this bar does not make it faster, but it does make you the kind of developer who stares at bars. Go drink water.

128 characters — well inside the 200-character limit.

Grok (grok-4.3) picked this candidate as the clear winner, score 9/10: the double meaning of "bars" (the progress bar, then the kind of developer who stares at them) is a fresh turn no other loading-screen tip takes, and the advice that follows — go drink water — is practical rather than another coffee gag.

`main.ts` validates the tip against every gate rule (single line, 1–200 characters, no leading/trailing whitespace, no whitespace-only text, no control characters) and then writes it to `$OUTPUT_DIR/entry.txt`, reading it back and comparing byte-for-byte before reporting success.

## How to run

```bash
OUTPUT_DIR=/tmp/out node main.ts
```

## License

MIT
