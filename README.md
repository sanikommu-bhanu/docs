# GapFinder — Project Dossier

**Don't just find the wrong answer. Find the line where the reasoning diverged.**

GapFinder reads a student's working, verifies every line against the one above it, locates the *first* line that stopped following, names the misconception behind it from a fixed catalogue, teaches that one thing — and refuses to call it mastered until the student can do it again with the help taken away.

- **Live app** — https://gap-finder-green.vercel.app/
- **Demo video** — https://youtu.be/Nxevj7tOB4w
- **Repository** — https://github.com/sanikommu-bhanu/GapFinder

---

## What's in this folder

| File | What it answers | Pages |
| --- | --- | --- |
| `01_GapFinder_Overview.pdf` | What is GapFinder, and why does it matter? | 6 |
| `02_GapFinder_Product.pdf` | How does the product work, screen by screen? | 8 |
| `03_GapFinder_AI.pdf` | How does the AI work, and where does code decide instead? | 7 |
| `04_GapFinder_Architecture.pdf` | How is it engineered? | 8 |
| `05_GapFinder_Evidence.pdf` | What was built, and how do I verify it? | 8 |
| `06_GapFinder_Judge_Guide.pdf` | What exactly should I evaluate, and how? | 5 |
| `diagrams/` | The five source diagrams, at full resolution | — |

## Recommended reading order

**Two minutes:** `06_GapFinder_Judge_Guide.pdf`, page 1 — a seven-step path through the live app.

**Ten minutes:** `01_GapFinder_Overview.pdf` → `06_GapFinder_Judge_Guide.pdf`.

**Full read:** 01 → 06, in order. Each document has one job and does not repeat another.

## The one rule the whole system obeys

> **The AI interprets. The code verifies. The database remembers.**

A model reads handwriting and phrases teaching. It is never the authority on whether a step is correct — that is deterministic algebra, which is why the product can point at line 2 by name.

## What's built

31 pages · 40 API routes · 30 data models · 22 seeded concepts · 58 curated knowledge chunks · 17 misconception codes · 14 computed diagram renderers — live on Vercel.

## Verifying the claims

```bash
npm run verify   # lint + typecheck + 228 tests + 15-case deterministic eval
```

**228 tests pass across 14 files. The eval scores 13 of 13 cases, 0 failed, at 100% divergence accuracy.** Both run with no API keys configured and no network — the load-bearing claims of this product do not depend on a model being reachable. Every number in these documents was produced by running the command named beside it.
# docs
