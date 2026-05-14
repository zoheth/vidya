---
name: negative-space
description: Ask what the code or system deliberately does NOT do. Refusals reveal design philosophy more sharply than features ever can. Trigger when the user is trying to characterize what something is for and feature-listing isn't getting them there, or when they invoke /negative-space. Do NOT trigger as an opener — there must already be enough material in conversation to identify deliberate omissions; otherwise the question becomes generic and unfalsifiable.
---

*Extracted from skills/code-theory-reconstruction.*

Ask: **"What does this deliberately not do?"**

Inclusions tell you what the author managed to fit in. Refusals tell you what they chose to leave out — and chosen omissions are stronger evidence of design philosophy than chosen inclusions. Anyone can add features; refusing to add them takes a position.

For each candidate omission, push for *why*:

- **Out of scope** — different problem, never seriously considered.
- **Tried and abandoned** — same problem, considered, rejected.
- **Refused on principle** — this system *shouldn't* do that, and the author would say so out loud.

The third category is the high-information one. A "this system shouldn't do X" claim does work that no feature description ever can.

**Scope**: stay with what's already in conversation. Don't search the repo for absences — wholesale absence detection is a different move. This lens works on what's been seen, by asking the user (or yourself) to articulate the deliberate negatives.

Each clear refusal is worth keeping as its own claim. Don't lump them together — each one points at a different boundary.
