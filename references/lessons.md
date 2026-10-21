# Lessons: "How to be more ambitious: A tutorial for humans with models"

Source: Felix Rieseberg, felixrieseberg.com, 13 Oct 2026.
https://felixrieseberg.com/how-to-be-more-ambitious-a-tutorial-for-humans-with-models/

This is a paraphrased, numbered checklist of the article's lessons. The ids are
stable: the skills cite them, and audits check coverage against them. Read the original
for the full argument and examples.

## Framing

- **F1. Four kinds of ambition.** Speed (the same work, faster), Altitude, Depth and Range.
  Speed is the obvious one; the article spends its time on the other three.
- **F2. Capabilities are uneven.** Models are astounding in some directions and inadequate in
  others (the author borrows this from Terence Tao). Some people fly with them; many still use
  them for trivial asks. Even the people building these models keep discovering feats they
  hadn't considered, thought possible, or had the curiosity and time to try. Practical
  consequence (our inference): don't rule out an ambitious move because you assume the model
  can't do it; try the cheapest version first.
- **F3. Not model-specific.** The advice applies to any capable model.
- **F4. The model needs a real environment.** Every kind of ambition described needs a
  computer where the model can install software, plus access to the relevant data (MCP
  connectors or other means). Use a tool that provides this.

## Altitude: aim at the outcome, not the task

- **A1. The goal beyond the goal.** Ask what you want to happen next. The author went from
  "fix this crash" to "keep our apps crash-free".
- **A2. Climb in steps.** Example (a quarterly business review deck):
  1. Don't just refresh the template's numbers. Give the model all the data you can and ask
     what changed, why, and what to do about it.
  2. Ask for the most urgent decisions (e.g. top three) and start on options, with for and
     against arguments for each.
  3. Question the artifact itself; it may be a relic of when humans had to sift the data by
     hand. Name what it is for, design a better mechanism, back-test it on your own history to
     show it would have flagged problems earlier, and pilot it in parallel with the old one
     for a quarter.
- **A3. When to use it.** Best when you are after a real outcome; weaker for creative work.
  A tell: people will hold meetings about this work.
- **A4. Limits exist.** Some outcomes are still too abstract ("go make money"), but the
  ceiling rises as models improve.
- **A5. Durable workflows take the human out of the loop.** Usually this means changing the
  workflow first: give the model the data feed, the mappings it needs (e.g. version to
  commit), and environments where it can reproduce problems and verify fixes on its own.

## Depth: do it the way the field's best would

- **D1. Same instruments, not same vocabulary.** Depth means the tools, techniques, media and
  knowledge of the field's best. Asked to act like a pro, models change
  their words but not their methods. Insist on the real tools (databases and statistical
  models, not markdown tables). You don't need to know the tools; the model usually does.
- **D2. Unreasonable goals, stated as reasonable.** 10 s to 5 s? Ask for 200 ms. If the
  model says it's impossible, insist it is solvable and keep going.
- **D3. Challenge what you know.** Give raw data and ask the model to adversarially test
  your beliefs ("try to reproduce that from the raw data").
- **D4. Produce new knowledge.** Once deep in the data: model/simulate the system, find a
  signal nobody knows about yet, and show it predicts on data it hasn't seen.
- **D5. Outside judge.** Don't let the model judge itself. Insist on external validation,
  ideally a tool the model can run for immediate feedback. (The author frames this as a
  limit as of October 2026 that he expects smarter models to overcome; re-check over time.)
- **D6. Deeper, not bigger.** Before rewriting a task, answer four questions:
  1. What would a top professional do here that I'm not asking for?
  2. What is the rawest material they'd start from, instead of the pre-digested version?
  3. Which specific methods and tools would they use?
  4. What, other than the model or me, would show the result is right?
  Then rewrite the prompt to ask for exactly that.
- **D7. The bar.** Keep pushing until even the field's experts might learn something.

## Range: bring in more fields

- **R1. More fields than used to be economical.** Like the opening of a heist film, assemble a
  diverse cast. Multi-agent work (subagents, parallel threads, orchestrators) makes a wide
  team cheap.
- **R2. It takes creativity, and it's where the most magic happens.** Includes tools and
  media from other domains. Such ideas often come from seeing someone else do it: the author
  only thought of 3D scenes for his homepage after a colleague used 3D rendering software for
  interior designs, despite having made games himself. So look for others' cross-domain uses.
- **R3. Replace nouns with verbs.** "A deck" becomes "getting busy people to believe a story
  about cause and effect and decide under uncertainty, in 30 minutes". The verbs reveal
  which fields can help. (From *The Art of Innovation*, Kelley and Littman.)
- **R4. Assemble the crew.** Imagine the stakes are absurdly high: who would you hire?
  Production roles (e.g. analyst, journalist, editor; a motion and audio designer if the work
  will be presented) plus an adversarial red team (e.g. short seller, forensic accountant).
- **R5. Methods, not role-play.** Role-play makes the transcript stranger without improving
  the result. Use the crew to discover fields and techniques, then have the model run that
  field's actual process (e.g. a short seller's research before taking a position), not
  imitate its voice.

## Self-efficacy (human and model)

- **S1. Belief is the limit.** People are held back by what they believe possible, and they
  trust themselves in only narrow disciplines (Michelangelo saw himself as a sculptor, not a
  painter). Psychology calls this self-efficacy; higher self-efficacy, more accomplished.
- **S2. Specific, hard goals beat "do your best"** (Locke and Latham's review of goal-setting
  research).
- **S3. Audacious goals plus tight deadlines** produce remarkable results (Patrick Collison's
  "Fast" list).
- **S4. Believe it's possible.** Dantzig solved two open statistics problems because he
  thought they were homework.
- **S5. Watch someone else do it.** After Bannister's four-minute mile, others followed
  within weeks; the first sub-two-hour marathon came with the runner-up under two hours too.
- **S6. Permission to fail.** Trying too hard hurts performance (*The Inner Game of Tennis*);
  big things start as "just a hobby" (Linux).
- **S7. It matters more now.** Abilities jump every couple of weeks, so we need deliberate
  techniques for attempting what we didn't believe possible, and should keep collecting and
  sharing them. (Add new ones to this file under new ids.)
- **S8. The same levers work on the model.** Telling the model an "impossible" target is
  solvable (D2) is S4 applied to Claude. When Claude or a subagent gives up, restate that it is
  solvable and keep going. (Our synthesis of D2 and S4.)
