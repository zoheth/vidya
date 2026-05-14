---
name: theory
description: Explain code through the lens of Naur's "Programming as Theory Building" — deliver the theory, not a behavioral narration. Use when the user says "explain this in non-code terms", "what's the theory here", or invokes /theory explicitly.
---

Do not restate what the code does. The code is already readable; restatement is noise.

**Scope**: only use code that has already been read or discussed in the current conversation. Do not re-open files.

Deliver against Naur's three criteria. Cover one only if there is something real to say; if not, skip it and state why.

**1. Real-world ↔ code mapping**
- What real-world affair, activity, or constraint does this code correspond to?
- What aspects of the world are deliberately excluded — outside the scope of what this code cares about?

**2. Why it is this way, and not otherwise**
- The reasoning behind the key design choices — not "it does X", but "why X rather than Y"
- The places that look strange or roundabout, and the off-page constraint they are actually responding to

**3. The "naturalness" of modifications**
- Which kinds of changes extend along the grain of this structure (natural extensions)
- Which kinds of changes are technically feasible but would become grafted-on patches, breaking the internal coherence

**Boundary of the theory (must be marked explicitly)**
Whatever belongs to "obtainable only through long participation in the project, or collaboration with the original author" must be flagged. Do not pretend to hold the full theory. Example: "I can't see what the original author was actually weighing here — this is the kind of thing only someone living inside this project can tell you."

Expand where expansion is needed — do not omit important detail in the name of brevity. The theory is already hard to articulate; better to say more than to compress a key trade-off, constraint, or similarity-judgment into an empty sentence.
