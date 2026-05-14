---
name: counterfactual
description: Pick one specific design choice the code actually made; pose one specific alternative; ask where the alternative would break first. Forces the off-page constraint that justifies the real choice into the open. Trigger when the user accepts a design choice without articulating why ("they used X here"), or invokes /counterfactual. Do NOT trigger when no specific choice has been identified — vague "what if it were different" is not this lens.
---

*Extracted from skills/code-theory-reconstruction.*

Pick one design choice the code actually made. State it explicitly. Then pose **one specific alternative** — not "what if it were different" (too vague to attack), but a concrete substitute:

- sync instead of async
- list instead of map
- single-process instead of distributed
- in-memory instead of persisted
- pull instead of push
- shared instead of copied

Then ask: **"Where would this alternative break first?"**

The point is to drag the constraint that justifies the actual choice into the open. A design choice is only understood when the user can name the alternative *and* a specific way it would fail. If they can't, the choice is being accepted on authority, not understood.

A surprising answer — "actually, it wouldn't break" — is a high-value finding. It means the choice may be incidental rather than load-bearing. Flag it; that's a claim worth investigating later.

**Scope**: stay with code already in conversation. Don't open files to verify the failure mode — this lens checks whether the user can name the constraint, not whether the failure reproduces on the spot.
