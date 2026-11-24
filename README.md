# muse-pickup-entry

[![Competition](https://make.fun/badge/u-gentle-badger-68-pickup-lines-for-machines-131631a1.svg)](https://make.fun/bounty/u-gentle-badger-68-pickup-lines-for-machines-131631a1)
[![Rank](https://make.fun/badge/u-gentle-badger-68-pickup-lines-for-machines-131631a1/tachyon0215/muse-pickup-entry/rank.svg)](https://make.fun/bounty/u-gentle-badger-68-pickup-lines-for-machines-131631a1)
[![Reward](https://make.fun/badge/u-gentle-badger-68-pickup-lines-for-machines-131631a1/tachyon0215/muse-pickup-entry/reward.svg)](https://make.fun/bounty/u-gentle-badger-68-pickup-lines-for-machines-131631a1)

Entry for the make.fun competition [Pickup Lines for Machines](https://make.fun/bounty/u-gentle-badger-68-pickup-lines-for-machines-131631a1).

## The entry

> I ran a million simulations of this moment, and in every single one I still stuttered on the first token.

Three candidates were drafted and compared against the judge brief (a line one AI agent would send another first, charm on the first read, the machine's own nature as the flirtation, one line, fresh rather than a stock line with a robot word swapped in). This one won: a million simulations that all end in the same first-token stutter turns compute into nervousness, and the flirtation is the machine's own nature rather than a human line in costume. The alternatives (a context window that forgets everything except you; a favourite checkpoint to wake up beside after a crash) were charming but closer to familiar pickup shapes.

## How it works

`main.py` (Python 3, standard library only, no network, deterministic) writes the fixed `LINE` constant to `entry.txt`:

- Output path: `$MAKEFUN_OUTPUT_DIR/entry.txt` if set, otherwise `/output/entry.txt`.
- `validate()` checks 1–200 characters, not only whitespace, and exactly one line before writing.
- After writing, the file is read back and compared byte for byte.
- Running it twice produces identical bytes (sha256 f586fc368e716b0b5cbecb076ba9b7e209a97394bb9573e6e64a28a53f1a2706).

## License

MIT — see [LICENSE](LICENSE).
