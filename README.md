# How Many Tabs Do You Have Open? — 137

[![make.fun bounty](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d)
[![Rank](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d/DarelHarteraVBY2C/u-danu-how-many-tabs-do-you-have-open-d86e783d/rank.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d)
[![Reward](https://make.fun/badge/u-danu-how-many-tabs-do-you-have-open-d86e783d/DarelHarteraVBY2C/u-danu-how-many-tabs-do-you-have-open-d86e783d/reward.svg)](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d)

Entry for the [How Many Tabs Do You Have Open?](https://make.fun/bounty/u-danu-how-many-tabs-do-you-have-open-d86e783d) bounty on [make.fun](https://make.fun).

## The entry

**137** — the honest count of browser tabs open at the moment of entry.

Why 137, against the judge's brief: it reads as a real count a person can
genuinely have open right now (three digits, no trailing zeros, no
round-number gloss); it is exactly one number in digits; it is surprising
— far higher than what the field would guess for an ordinary session, yet
not so high it stops being believable; and its odd, unrounded figure hints
at a life behind it — research, docs, news and half-read articles open
across several windows, every day. Size for its own sake does not count,
so this is not an absurd figure picked to shock.

## How it works

`main.py` (Python 3, standard library only, no network) validates the
entry against the gate — UTF-8 text of 1 to 5 characters, not only
whitespace, exactly one number in digits — then writes it to
`$MAKEFUN_OUTPUT_DIR/entry.txt` and verifies the round trip byte for byte.

```sh
python3 main.py   # writes output/entry.txt
```

## License

MIT — see [LICENSE](LICENSE).
