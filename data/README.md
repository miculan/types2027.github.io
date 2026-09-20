# Data

Jekyll reads this directory because `_config.yml` sets `data_dir: data`, and
`exclude` keeps it out of the published site — `program-committee.json` carries
reviewer email addresses and must not be served.

The JSON files use the names and shapes of
[sattlerc/types-website](https://github.com/sattlerc/types-website), the tooling
written for TYPES 2026, so that its book-of-abstracts generator and its ICS
calendar script can run against this directory unchanged:

| File | Filled from | Used by |
| --- | --- | --- |
| `papers.json` | exported from HotCRP | accepted talks, programme, book of abstracts |
| `invited.json` | by hand | invited speakers, programme |
| `sessions.json` | by hand, after acceptance | programme |
| `schedule.json` | by hand, after acceptance | programme, ICS calendar |
| `organizing-committee.json`, `program-committee.json`, `steering-committee.json` | by hand | committees page, book of abstracts |

People are `{first, last, affiliation, role?, homepage?, email?}`; names are kept
split so they can be sorted by surname.

The YAML files are ours and have no counterpart upstream: `dates.yml` (every
deadline, referenced by id), `editions.yml` (the past editions of the series)
and `navigation.yml` (the menu).
