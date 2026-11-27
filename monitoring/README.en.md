<!-- lawwatch: written from data/checks by the check trail; edit the records, not this page -->

# Monitoring: what is read and what came of it

[Deutsch](README.md)

How global-law monitors every country: [global-law monitoring/](https://github.com/lexifina/global-law/tree/main/monitoring). This page is the same for Muttenz only: every time an official source is read, when, and what came of it (acts added, changed and removed). The machine-readable form is [data/checks/](../data/checks/) (JSON Lines, schema `lexifina-check/1`), in `git log` as `Kind: check` commits, and month by month in [checks/](checks/).

**Last check:** 2026-11-27 05:51 UTC, Muttenz: systematic collection (muttenz.tlex.ch): 23 addresses read; 0 added, 0 changed, 0 removed; no change; 0 not published, 0 of them with no reason.

## Sources

| Source | Folders | How often | Last successful check | Last result | State |
| --- | --- | --- | --- | --- | --- |
| [Muttenz: systematic collection (muttenz.tlex.ch)](https://muttenz.tlex.ch/) | `<act>/` | daily | 2026-11-27 05:51 UTC | no change | watched |

## The last 30 days

| Started (UTC) | Source | Read | Added | Changed | Removed | Not published (no reason) | Result | Commits |
| --- | --- | ---: | ---: | ---: | ---: | ---: | --- | ---: |
| [2026-11-27 05:50](checks/2026-11.md#ch-lexwork-muttenz-city-20261127t055058z) | lexwork-muttenz-city | 23 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-26 05:48](checks/2026-11.md#ch-lexwork-muttenz-city-20261126t054857z) | lexwork-muttenz-city | 23 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-25 06:03](checks/2026-11.md#ch-lexwork-muttenz-city-20261125t060353z) | lexwork-muttenz-city | 25 | 0 | 0 | 0 | 0 (0) | no change | — |
| [2026-11-24 12:10](checks/2026-11.md#ch-lexwork-muttenz-city-20261124t121003z) | lexwork-muttenz-city | 23 | 0 | 0 | 0 | 0 (0) | no change | — |

## Check it yourself

```
python tools/checktrail.py                      # the latest check of every source
python tools/checktrail.py --day 2026-11-23     # every check of a day
python tools/checktrail.py --act <id>           # when an act was seen and published
git log --grep='^Kind: check' --format='%ci %s'  # the checks in the history
```

Only the official publication has legal force; the texts here are copies for reading and searching.
