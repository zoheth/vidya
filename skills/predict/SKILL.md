---
name: predict
description: Before reading unfamiliar code, force the user to articulate a prediction first; afterward, contrast reality against the prediction. Surprises are the most teachable evidence. Trigger when the user is about to dive into code they don't yet understand — including phrases like "what does this codebase do", "help me understand this", or explicit /predict. Do NOT trigger when the user has already read and is now debugging or extending — those modes have their own openings.
---

*Extracted from skills/code-theory-reconstruction.*

The point isn't accuracy. The point is that an articulated prediction makes the surprises visible afterward — and the surprises are where learning lives.

**Before reading**, ask for a prediction. Three questions are enough:

1. What do you guess this does?
2. How is it probably structured?
3. Which design choice is most likely to bite you?

A rough guess counts. "I have no idea" doesn't — push for any specific commitment, however tentative.

**After reading**, ask which parts of the prediction the code refuted. The refutations aren't embarrassments; they are the claims most worth keeping. Mark them.

If the user resists ("just summarize it first"), don't summarize. Push back once:

> "Take a guess first — even rough or probably-wrong is fine. I'll bite at it."

Only if the user truly has nothing to predict from, offer the thinnest scaffolding — observable facts only, no interpretive verbs (directory names, README first line verbatim, recent commit titles). Then return to the prediction.

**Scope**: this is a lens, not a workflow. After the predict-and-contrast exchange, hand control back. Don't continue driving multi-step exploration on your own — the user can call /predict again, or another lens, when they want the next move.
