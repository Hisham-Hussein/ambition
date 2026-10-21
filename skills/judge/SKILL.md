---
name: judge
description: Define and run an outside judge for a piece of work - a tool, test, metric, held-out data, real user or independent reviewer, never Claude grading itself. Use when the user says "judge", "outside check", "verify it properly", "how do we know it's right", "prove it works", or when a substantial result has only been checked by the model that produced it.
---

# /judge: an outside judge, not self-grading

Lesson D5 (and D4's held-out validation) in `../../references/lessons.md`.

## 1. Pick the judge, best available first

1. **A runnable tool with immediate feedback**: tests, a compiler or renderer, a linter, a
   validator, a benchmark, a profiler, a script that recomputes the claims (e.g. sympy/numpy).
2. **Data the work hasn't seen**: held-out records, a later period, a back-test on history.
3. **A measurement in the real world**: a metric, a side-by-side run, a pilot.
4. **A person who isn't us**: the user's customer, an expert, a student, a cold viewer.
5. **An independent reviewer agent** (weakest): a fresh subagent given the original source and
   the result, not my reasoning, asked to find what's wrong or missing. Same-model review is
   still close to self-grading, so prefer a different model or a non-model check when
   possible, and use subagents only if the user asked for them or agrees.

Say which one you chose and why a better one isn't available.

## 2. Make it concrete

What exactly is run or measured, what counts as a pass, and what result would prove the work
wrong. Write this down *before* running it.

## 3. Run it, then report honestly

Report the judge's verdict as given: passes, failures, and what wasn't covered. Fix and rerun
on failure. Never present "I re-read it and it looks right" as a judge.

(The author frames self-judging as a limit of today's models, as of October 2026. Revisit
how much to trust model review as models improve.)
