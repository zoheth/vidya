---
name: theory
description: Explain what's behind code — the understanding that lived in the author's head but doesn't show in the code itself. Inspired by Naur's "Programming as Theory Building". Use when the user says "explain this in non-code terms", "what's the theory here", "这段代码背后的东西是什么", or invokes /theory explicitly. Works only from code already read in this conversation; does not explore the codebase.
---

Always output in Chinese (中文).

The goal: give the user what the code alone cannot — the understanding in the
author's head. Naur called this the program's theory. Use his idea as a
compass, not a template: the list below is what counts as "behind the code",
not a form to fill in. Organize the answer however this particular code
demands; lead with whatever matters most here.

Do not restate what the code does. The code is already readable; restatement
is noise.

**Scope**: only use code already read or discussed in this conversation. Do
not re-open source files. Exception: git history (`git log`, `git blame`) is
allowed — commit messages are the author's recorded intent.

**What counts as "behind the code"** — pick what's real for this code, skip
the rest:

- The real-world affair or constraint the code answers to, and what it
  deliberately ignores.
- Why it is this way and not another — especially the strange or roundabout
  places, and the off-page constraint behind them.
- The load-bearing assumptions nobody wrote down.
- What the structure is preparing for: which future changes it welcomes,
  which it would resist. Concrete examples, specific to this code.
- Where it came from: the earlier shape it grew out of, the scars left by
  past decisions.

**Honesty**:

- Mark each claim about the author's reasoning: backed by evidence (comments,
  commits, structure), inferred from constraints, or your own guess. Don't
  state a guess in the tone of a fact.
- Mark the gaps, in two kinds. Closable: knowable by reading more of the
  repo — name the file. Theory boundary: only the original author could
  answer; say so plainly.

Expand where needed — on trade-offs, constraints, and judgment calls, never
on restatement. Better to say more than to flatten a key decision into one
empty sentence.
