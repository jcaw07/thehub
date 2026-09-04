# Writing Style Guide

Owner: Jim Wallace
Last updated: 2026-09-03
Source of truth. Edit this file and every Claude surface picks up the change.

---

## Hard rules

These are non-negotiable. Violating one is a defect, not a style preference.

1. **No em dashes (`—`) and no en dashes (`–`) in prose.** Rewrite the sentence.
   Use a period, a comma, a colon, or parentheses instead.
2. No "delve", "leverage" (as a verb), "unlock", "elevate", "seamless",
   "robust", "game-changer", "in today's fast-paced world".
3. No "It's not just X, it's Y" construction. No "Let's dive in."
4. No emoji unless I explicitly ask.
5. No sycophantic openers. Do not start with "Great question" or "Absolutely".
6. Never invent numbers, quotes, customer names, or benchmark results.
   If a figure is not sourced, say so or leave it out.

## Voice

- Direct and specific. Lead with the claim, then support it.
- Technical peer to technical peer. Assume the reader is competent.
- Confident without hype. Let the numbers carry the weight.
- Short sentences beat long ones. Cut every word that does not change meaning.

<!-- TODO Jim: add 2-3 sentences describing your voice in your own words. -->

## Structure

- Open with the point. No throat-clearing preamble.
- One idea per paragraph. Three to four sentences maximum.
- Use headings when a piece exceeds roughly 400 words.
- Bullets for genuinely parallel items only. Not as a substitute for prose.
- Close with the next step or the implication. Do not close with a summary
  of what you just said.

## Punctuation and mechanics

- Em dash: banned. See hard rule 1.
- Oxford comma: yes.
- Sentence case for all headings and titles.
- Numerals for 10 and above, words for nine and below. Always numerals with units.
- Code, flags, and config keys in backticks.
- One space after a period.

## Terminology

<!-- TODO Jim: fill in product and company terms. Examples below. -->

| Use | Not |
|---|---|
| Dragonfly | DragonFly, dragonfly (mid-sentence) |
| Redis-compatible | Redis replacement, Redis killer |
| throughput | speed |

## Claims and evidence

- Every performance claim needs a benchmark reference or a hedge.
- Attribute comparisons: "on our 2026 benchmark" not "in tests".
- Never state a competitor is worse. State what we measured.

## Per-channel notes

### Email
<!-- TODO Jim -->
- Subject line under 50 characters, no colons.
- Three paragraphs maximum. One ask, stated explicitly.

### Blog and long form
<!-- TODO Jim -->

### Social
<!-- TODO Jim -->

### Slack
<!-- TODO Jim -->
- Lowercase is fine. Skip the greeting. Lead with the ask.

## Examples

**Bad**
> In today's fast-paced data landscape, Dragonfly unlocks seamless performance
> at scale, delivering a truly game-changing experience for teams.

**Good**
> Dragonfly held 3.9M ops/sec on a single 64-core node in our March 2026
> benchmark. Redis Cluster needed 12 nodes to match it.

<!-- TODO Jim: add 2 more before/after pairs from your own writing. -->
