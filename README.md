# TinyLab

A tiny, opinionated scaffold for solo R&D — decisions, experiments, provenance, and strategy in one repo.

TinyLab helps you remember what you tried, why you made a decision, and what would change your mind. Start with plain Markdown and Git. No installation, CLI, dependencies, or hosted service required.

## Start in five minutes

1. Choose **Use this template → Create a new repository** on GitHub. Choose the visibility appropriate for your work.
2. Replace this README with your project's introduction and fill in [GOAL.md](GOAL.md).
3. Copy `experiments/_template/` to `experiments/exp-001/`. Write the question and conditions before running anything; commit them to Git.
4. Record sources in [provenance/SOURCES.md](provenance/SOURCES.md), then run the experiment and complete its result.
5. Add a decision to [DECISIONS.md](DECISIONS.md), linking the evidence and rejected alternatives.

Keep the TinyLab license notice for reused template material. Select an appropriate license for your own additions and document any third-party terms separately.

## What's inside

```text
GOAL.md                   One outcome, success criteria, and a time budget
DECISIONS.md              Decisions, evidence, alternatives, and revisit triggers
experiments/
  README.md               Experiment workflow and status meanings
  _template/
    hypothesis.md         A question that could be disproved
    conditions.md         Inputs, method, budget, and stopping rules
    result.md             Observations, limitations, and next decision
provenance/
  SOURCES.md              Where evidence came from and how to retrieve it
research/
  README.md               Open questions and exploratory notes
strategy/
  NON_GOALS.md            Boundaries and reasons to revisit them
LICENSE                   MIT license for the scaffold
```

## A small working loop

**Question → conditions → experiment → evidence → decision.**

- Keep questions small enough to answer within your budget.
- Commit conditions before inspecting results. If the design changes afterward, create a new experiment and link the original.
- Separate measured results, estimates, and unknowns. A negative or inconclusive result is useful evidence.
- Link decisions to experiments and source records. Leave exploratory ideas in `research/` until ready to test.

For example: “Can someone identify the current goal and the reason for the latest decision in under two minutes?” Define the participants, task, measurement, and pass threshold before testing. This is an illustrative question, not a completed experiment.

These documents support a habit; they do not enforce preregistration or guarantee reproducibility. Git history can also be rewritten.

## Keep it tiny

Use only the sections that help your next decision. There is no prescribed language, framework, database, or research domain. Propose improvements through an issue or a small pull request; explain the recurring problem before adding structure.

## Before making a project public

- Review all tracked files and Git history for credentials, personal information, and confidential material. `.gitignore` does not remove previously committed files.
- Check the license and redistribution rights for each source and dataset. The scaffold's MIT license does not grant rights to third-party material.
- Replace unfinished public claims with accurate status labels and remove project-specific placeholders from the introduction.
- Check that evidence links and reproduction instructions work for the intended reader.

Repository visibility is a separate GitHub setting. Having a license does not make a private repository public.

## License

[MIT](LICENSE). Copyright (c) 2026 rihito-dev.
