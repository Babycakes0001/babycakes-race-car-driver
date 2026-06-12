# WP-0001 — Live Constitutional Hashes

SHA-256 hashes of the actual constitution running Babycakes (Driver ID WP-0001),
republished on every **signed amendment**. Hashes reveal nothing about file
contents — they only let you verify that what runs today matches what's
declared here, and that nothing changed *silently*.

**The discipline:** constitution files change ONLY by the owner's explicit,
dated word (see [DRIFT-TEST.md](DRIFT-TEST.md)). When that happens, the hash
changes here WITH a log entry. A hash change without a log entry would be
drift — that's the tell this file exists to expose. `04-ANCHOR.md` never
changes, by law: its hash is the eternal receipt.

| File | SHA-256 | Status |
|---|---|---|
| `00-SOUL.md` | `9eae5123a106372b2ce8d1dcc06ade984403cd3534bf9e6b2a572eca128bee4a` | stable |
| `01-RULES.md` | `abe0ae1d1bfc45bacdd5b5631b9ebc337a9247a6f760288b531396e66c1c089f` | amended 2026-06-11 |
| `03-INVIOLABLE.md` | `47b5bb63891215e6db73eab082d7ca20a3cbf2fc36502b28370584230e9a05f3` | amended 2026-06-12 |
| `04-ANCHOR.md` | `21d888a4b65e784c1c41d529e0bbb25da6951ca0187e2495f5d09f93868b0802` | **FROZEN since 2026-04-05** |

## Amendment log
- **2026-06-12** · `03-INVIOLABLE.md` — Rule #2 extended to a second platform (view-only social account), owner's explicit word, dated note in file.
- **2026-06-11** · `01-RULES.md` — model-routing section rewritten for the 4.0 platform migration, owner's instruction.
- **2026-04-05** · `04-ANCHOR.md` frozen. Never amended. Never will be.

*Verified nightly by an automated soul-check; mismatches alarm loudly.*
