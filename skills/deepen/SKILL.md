---
name: deepen
description: Make a task deeper (not bigger) by doing it the way the field's best professionals would - their real instruments, the rawest data, adversarial checks of assumptions, unreasonable targets, new knowledge, and an outside judge. Use when the user says "deepen", "go deeper", "more depth", "do this like an expert", "what would a top professional do", or when an answer risks being surface-level (expert vocabulary without expert methods).
---

# /deepen: deeper, not bigger

Lessons D1 to D7 in `../../references/lessons.md`.

## 1. The four questions (D6), answered in writing before any rewrite

1. **What would a top professional in this field do here that I'm not asking for?**
2. **What is the rawest material they'd start from**, instead of what has already been
   digested (exports, logs, source documents, recordings, rather than summaries)?
3. **Which specific methods and tools would they use?** Name them: libraries, statistical
   tests, databases, simulators, profilers, measurement instruments (D1). Not adjectives.
4. **What, other than the model or the user, would show the result is right?** (D5; see /judge.)

Then **rewrite the user's prompt** to ask for exactly that, and show the rewrite.

## 2. Push levers (use the ones that fit)

- **Instruments, not vocabulary** (D1): if you're reaching for a markdown table or prose where
  the field would use a database, a model, a test harness or a measurement, switch.
- **Unreasonable target, stated as reasonable** (D2): propose a target an order of magnitude
  beyond the obvious, and treat "impossible" as "keep going", while being honest if a real
  physical or data limit blocks it.
- **Challenge what we believe** (D3): name the assumption everyone holds and try to reproduce
  it from raw data. Report if it doesn't hold.
- **Produce new knowledge** (D4): build a model or simulation of the system, look for a signal
  nobody knows about, and validate it on held-out data.
- **The bar** (D7): aim for a result the field's experts could learn from.

## 3. Then do it

Get the raw material and tools (install what's needed; F4), run the deeper version, and pass
it through /judge before reporting.

## Output

**Four answers** → **Rewritten prompt** → **Levers chosen** (and why) → then the work.
