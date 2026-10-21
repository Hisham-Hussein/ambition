# ambition

A Claude Code plugin for working more ambitiously with Claude, based on Felix Rieseberg's
["How to be more ambitious: A tutorial for humans with models"](https://felixrieseberg.com/how-to-be-more-ambitious-a-tutorial-for-humans-with-models/)
(13 Oct 2026).

## Skills

| Skill | Use it for | Say |
|---|---|---|
| `ambition:ambition` | The full pass: altitude, means, depth, range, judge, recommendation | "ambition", "the ambitious version" |
| `ambition:altitude` | The goal behind the goal, and what Claude needs to own it | "go up a level" |
| `ambition:deepen` | The four depth questions, then a rewritten prompt | "go deeper", "more depth" |
| `ambition:crew` | The work as verbs; a crew of fields with a red team; methods, not personas | "bring in other fields" |
| `ambition:judge` | An outside check, defined before it runs | "outside check", "how do we know it's right" |

## References

- `references/lessons.md`: the article's lessons, paraphrased, with stable ids (F, A, D, R, S).
- `references/cheat-sheet.md`: one page for the human side.
- `references/ambition-brief-template.md`: template for a project's `AMBITION.md`, which the
  `ambition` skill reads first.

## Install

From the `hisham-marketplace` catalogue:

```bash
claude plugin marketplace add Hisham-Hussein/hisham-marketplace
claude plugin install ambition@hisham-marketplace
```

## Updating

Edit, run `claude plugin validate .`, bump `version` in `.claude-plugin/plugin.json`, commit and
push, then run `claude plugin marketplace update hisham-marketplace` and
`claude plugin update ambition@hisham-marketplace` on each machine.
