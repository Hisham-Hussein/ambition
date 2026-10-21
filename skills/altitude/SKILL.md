---
name: altitude
description: Raise a task's altitude by finding the goal behind the goal and the workflow that would let Claude own that outcome. Use when the user says "altitude", "what's the goal behind this", "go up a level", "what are we really trying to achieve", or asks to turn a recurring task into an outcome Claude owns (fixing one bug vs keeping the app healthy, making a deck vs getting a decision made).
---

# /altitude: aim at the outcome, not the task

Lessons A1 to A5 and F4 in `../../references/lessons.md`.

## Steps

1. **State the task as given.**
2. **Ask "and then what?" until you hit a real outcome** (A1). Usually 1 to 3 hops: the
   deliverable → the decision or behaviour it should cause → the result that decision serves.
3. **Check fit** (A3, A4):
   - Is there a real outcome (yes: altitude fits; mainly creative: say it fits less well)?
   - Will people hold meetings about it? That's the tell.
   - Is the top outcome too abstract for a model today ("go make money")? Then stop one level lower.
4. **Climb in steps, each a concrete prompt** (A2):
   - *Understand:* give the model all the data, not the template; ask what changed, why, and what to do.
   - *Decide:* the most urgent decisions (top three), each with options and for/against.
   - *Redesign:* name the purpose the artifact or ritual serves (it may be a relic of manual
     work), design a better mechanism, back-test it on our own history, and propose running it
     alongside the old one for a cycle (e.g. a quarter), with an owner and a date.
5. **Design the durable loop** (A5, F4): what must change so the model can pursue the outcome
   without being re-tasked? List the data feeds, mappings, access, environments and
   verification it needs, and check which actually exist in this session (have/need). This is
   usually the real work.

## Output

**Task** → **Outcome chain** (task → … → outcome) → **Fit** → **Step prompts** (understand,
decide, redesign) → **Loop requirements** (have / need) → **Recommended next step**.
