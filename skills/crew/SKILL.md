---
name: crew
description: Widen a task's range by bringing in fields, tools and media it doesn't obviously need - rewrite the work as verbs, assemble a crew including a red team, and run each field's methods. Use when the user says "crew", "more range", "bring in other fields", "who else should look at this", "assemble the team", or asks which disciplines or tools from other domains could improve the work. For a pure attack on a pitch or deck, prefer a dedicated red-team or skeptical-investor skill if one is installed.
---

# /crew: range

Lessons R1 to R5 in `../../references/lessons.md`.

## 1. Nouns to verbs (R3)

Rewrite the deliverable as what it has to *do*, in one sentence of verbs. "A pitch deck"
becomes "make sceptical investors believe a small team can build X, and decide to fund it,
in 20 minutes". List the verbs: each points to fields that are good at it.

## 2. Assemble the crew (R4)

Imagine the stakes are absurdly high. Pick **3 to 5 fields**, one per verb or risk, and always:
- at least one **production** field that raises quality (editor, designer, analyst; a motion or
  audio designer if the work will be presented),
- at least one **red team** field that attacks it (short seller, forensic accountant,
  regulator, sceptical customer, security researcher, ...),
- one **tool or medium from another domain** that could change the result (R2): e.g. 3D
  rendering, simulation, animation, a statistics package, a game engine, audio design. Ask
  where you've seen someone else use a tool like that; borrowed examples are the best source.

## 3. Methods, not personas (R5)

For each field, write the **action** it performs and the **artifact** it produces, never
"write like a ...". Role-play makes the transcript stranger without improving the result.
Example: not "write as a short seller" but "find the claims the business depends on and look
for evidence they're false, the way a short seller researches before taking a position".

## 4. Run it (R1)

Wide crews are cheap with parallel work. If the user asked for subagents or agrees now, run
each field as a subagent with its method, the raw material and a required artifact; then
merge: what changed, what conflicts, what to do. Otherwise apply the methods yourself, one by one.

## Output

**Verbs** → **Crew table** (field · verb it serves · method · artifact) → **Other-domain tool**
→ **Findings** (after running) → **Changes to make**.
