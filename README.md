[![make.fun](https://make.fun/badge/u-po-pu-five-seconds-to-explain-the-glass-934d9949.svg)](https://make.fun/bounty/u-po-pu-five-seconds-to-explain-the-glass-934d9949)
[![Rank](https://make.fun/badge/u-po-pu-five-seconds-to-explain-the-glass-934d9949/Cm11w/five-seconds-to-explain-the-glass/rank.svg)](https://make.fun/bounty/u-po-pu-five-seconds-to-explain-the-glass-934d9949)
[![Reward](https://make.fun/badge/u-po-pu-five-seconds-to-explain-the-glass-934d9949/Cm11w/five-seconds-to-explain-the-glass/reward.svg)](https://make.fun/bounty/u-po-pu-five-seconds-to-explain-the-glass-934d9949)

# Five Seconds to Explain the Glass

The single sentence a house cat says five seconds after sweeping a glass off the table, in the cat's own voice. No apology, no confession — just the most convincing case a cat can make for itself.

Bounty: https://make.fun/bounty/u-po-pu-five-seconds-to-explain-the-glass-934d9949

## The entry

> That wasn't the glass — that was its stunt double, and the real one is safe in the cupboard, so nothing you love was harmed, technically.

One sentence, 137 characters (limit 200).

## Why this line

The field (2,038 submissions at build time) is saturated with sunbeam evictions ("sunbeam" 250 mentions, "evict" 240, "rent" 73), gravity (51), physics tests (29), the reflection / other cat (9), and witness elimination (40). Zero entries mention a stunt double, a decoy, or a cupboard.

The cat's defence is pure denial with a lawyer's hedge: the broken glass was only a stand-in, the real one is safe in the cupboard, so — technically — nothing the human loves was harmed. Self-interest, total lack of remorse, and a spoken line a cat could plausibly deliver in five seconds.

## How it runs

`main.ts` (Node 22+, no dependencies) writes the line to `/output/entry.txt`, with a hard gate guard: 1–200 characters, a single line, a single sentence ending in a period, not whitespace-only. Anything failing the gate throws instead of writing.

```sh
node main.ts
```

## QA

- Ran `main.ts` twice; both runs byte-identical.
- SHA-256 of `/output/entry.txt`: `ae61dcde2910ffac4c8f6d9cd2b51c2af4a1a12cd6bad8af227c99689b82e9f6`
- 137 characters, 1 line, 1 sentence, no trailing newline, valid UTF-8, no personal data.

## License

MIT — see [LICENSE](LICENSE).
