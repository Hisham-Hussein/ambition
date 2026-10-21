---
name: ambition
description: Make a task, plan or project more ambitious using altitude (the goal behind the goal), depth (expert methods, raw data, outside judges) and range (other fields, tools and media). Use when the user says "ambition", asks for "the ambitious version", "be more ambitious", "aim higher", or asks to raise the bar on a task, plan, deck, product or project. Do NOT use when the user calls something "too ambitious" or asks to cut scope.
---

# /ambition: the full ambition pass

Based on Felix Rieseberg's "How to be more ambitious: A tutorial for humans with models".
`../../references/lessons.md` holds the numbered lessons (F, A, D, R, S ids) this skill applies.
Read it the first time this skill runs in a session.

## 1. Load the project's brief and its guardrails

Look for `AMBITION.md` in the current folder, then each parent up to the project root (and in
`docs/`). If it exists, read it first: it holds this project's outcome chain, judges, crew and
open bets, so don't re-derive them. Follow any guardrails it links (checkpoints, approval
steps, budgets). If there's no brief and the project is substantial, offer to write one at the
end (template: `../../references/ambition-brief-template.md`).

## 2. Name the task and its default version

One line each: what was asked, and what the ordinary (speed-only) answer would be (F1).

## 3. Run the lenses: at most 3 bullets each (the named skill has the long form)

**Altitude** (/ambition:altitude): what should happen *after* this (A1)? Climb one or two
steps: understand the why, surface the decisions, question the artifact itself (A2). Does
altitude fit: a real outcome, or creative work; will people meet about it (A3)?

**Means check (F4, A5):** list what is actually available in this session, marked have/need:
data, files, connectors, tools, environments. Recommendations must be runnable with what's
there, or say exactly what to get.

**Depth** (/ambition:deepen): the four questions in D6, briefly. Name the real instruments
(D1), the raw material and the assumption to test against it (D3), possible new knowledge
(D4), and an unreasonable target stated as reasonable (D2).

**Range** (/ambition:crew): the work as verbs (R3); 3 to 5 fields including one red team
(R4); one tool or medium from another domain, ideally one you've seen someone else use (R2).
Each field brings a *method*, never a persona (R5).

**Judge** (/ambition:judge): what, outside the model and the user, will show it worked (D5)?

## 4. Recommend, don't survey

Pick the one or two moves with the best ratio of impact to cost, and say why. Be concrete: the
prompt you'd now run, the data or access needed, the judge. Don't rule a move out because you
assume the model can't do it; propose the cheapest test of it instead (F2). If the ambitious
version is out of reach today, name the limit (A4) and the nearest step. Steps that need time
or the real world (piloting a new process for a quarter, a study with students) are
*proposals* with an owner and a date, not something to fake inside one session.

## 5. Human side: one line, only when it helps

If the goal is being set timidly, name the lever that fits: a specific hard target (S2), a
deadline (S3), "someone has already done this" (S5), "assume it's solvable" (S4), "you're
trusting yourself too narrowly" (S1), or permission to fail (S6). Never lecture.

## 6. Then do it, within the project's rules

If the user agrees (or asked for the ambitious version outright), start. Use subagents for
crew or judge work only if the user asked for them or agrees now (R1). Never publish, send,
spend credits or skip a checkpoint without approval. When Claude or a subagent declares
something impossible, restate that it is solvable and keep going, while being honest about
real limits (S8, D2). Run the judge before calling anything done.

## Output shape

**Task** · **Altitude** · **Means** · **Depth** · **Range** · **Judge** · **Recommendation**
(the next prompt or action). Under one screen unless asked for more.
