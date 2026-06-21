# Plain English Copywriting — Hermes Skill

A plain-English rewriting skill for [Hermes Agent](https://github.com/NousResearch/hermes), based on Martin Cutts' *Oxford Guide to Plain English* (5th ed., 2020).

## What it does

Takes any foggy, jargon-filled text — legal documents, emails, reports, contracts — and rewrites it into clear, reader-centred prose.

**Standard output: two documents**
1. **Rewritten text** — clean plain-English version, ready to use
2. **Change report** — standalone audit explaining every edit, principle applied, and before/after comparison

## Install

Copy this folder into your Hermes skills directory:

```
~/.hermes/skills/copywriting/plain-english-copywriting/
```

Restart Hermes or run `hermes tools` to load.

## Structure

| File | Purpose |
|------|---------|
| `SKILL.md` | Main skill file with triggers, workflow, and 12 core principles |
| `references/thirty-guidelines.md` | All 30 chapters from Cutts' book |
| `references/examples-bank.md` | Before/after examples by category |
| `references/quick-checklist.md` | 20-point pre-publication checklist |
| `references/readability-tools.md` | Readability formulas and targets |
| `templates/rewrite-template.md` | Structured template for rewrites |

## Metrics

- **Target sentence length:** 15–20 words average
- **Target reading age:** 13 (general UK/US audience)
- **Target active voice:** >70%
- **Max noun string:** 2 nouns (3+ = "knotty")

## License

MIT — based on publicly documented principles from *Oxford Guide to Plain English*.

## Author

**MetaPunk** (`metapunk24`) — assembled and tested for Hermes Agent.
