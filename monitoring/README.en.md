<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Deutsch](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Zug only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-28 08:28 UTC, Zug: systematic collection (bgs.zg.ch): 184 addresses read; 0 added, 2 changed, 0 removed; changes found; 58 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Zug: systematic collection (bgs.zg.ch)](https://bgs.zg.ch/) | `<act>/` | daily | 2026-11-28 08:28 UTC | changes found | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-28 08:25](checks/2026-11.md#ch-lexwork-zug-20261128t082504z) | lexwork-zug | 184 | 0 | 2 | 0 | 58 (0) | changes found | — |
| [2026-11-28 07:09](checks/2026-11.md#ch-lexwork-zug-20261128t070936z) | lexwork-zug | 0 | 0 | 0 | 0 | 0 (0) | the check failed | — |
| [2026-11-28 06:40](checks/2026-11.md#ch-lexwork-zug-20261128t064018z) | lexwork-zug | 0 | 0 | 0 | 0 | 0 (0) | the check failed | — |
| [2026-11-27 07:01](checks/2026-11.md#ch-lexwork-zug-20261127t070156z) | lexwork-zug | 200 | 0 | 1 | 0 | 56 (0) | changes found | [2](https://github.com/lexifina/switzerland-zug-law/compare/15a0ca1ba5a5...e3796d802908) |
| [2026-11-26 07:05](checks/2026-11.md#ch-lexwork-zug-20261126t070505z) | lexwork-zug | 288 | 55 | 2 | 0 | 59 (0) | changes found | [56](https://github.com/lexifina/switzerland-zug-law/compare/76b8a82c0510...0fda698d1afb) |
| [2026-11-25 08:10](checks/2026-11.md#ch-lexwork-zug-20261125t081018z) | lexwork-zug | 365 | 205 | 0 | 0 | 107 (0) | changes found | [174](https://github.com/lexifina/switzerland-zug-law/compare/b9766eac6c55...95831c158118) |
| [2026-11-24 12:51](checks/2026-11.md#ch-lexwork-zug-20261124t125117z) | lexwork-zug | 695 | 351 | 4 | 0 | 232 (0) | changes found | [285](https://github.com/lexifina/switzerland-zug-law/compare/22b4361caae5...2955492a38d0) |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
