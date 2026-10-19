# Brain adaptations: Addy Osmani

Task 1231 adapts all six selected skills from upstream commit
`aeac41d4d005999432bb7312f7ff06383a91d59d` without changing the original `skills/` tree.
Each adaptation retains its own `LICENSE`, `NOTICE` and `UPSTREAM`.

| Skill | Entry point |
|---|---|
| Planning | [ao-planning-and-task-breakdown](ao-planning-and-task-breakdown/SKILL.md) |
| Context | [ao-context-engineering](ao-context-engineering/SKILL.md) |
| Adversarial review | [ao-doubt-driven-development](ao-doubt-driven-development/SKILL.md) |
| Code review | [ao-code-review-and-quality](ao-code-review-and-quality/SKILL.md) |
| Migration | [ao-deprecation-and-migration](ao-deprecation-and-migration/SKILL.md) |
| Shipping | [ao-shipping-and-launch](ao-shipping-and-launch/SKILL.md) |

Brain indexes this directory as optional source `ao`. Assign an exact skill name to a task
and use `start_task.py` to receive its description and canonical path.
These skills stay addressable and preserve existing 1C stages and resident selections.
The task's README and single `plan.md` remain its document contract.

Updates require a manual comparison with upstream. Brain's `skills-sync` serves the 1C source only.
