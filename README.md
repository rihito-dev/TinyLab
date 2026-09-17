# TinyLab

**Turn a curious hunch into a tiny, traceable experiment.** 🔬

TinyLab is a pocket-sized lab bench for solo R&D. It keeps your questions, experiments, sources, and decisions together—so a promising rabbit hole can become useful evidence instead of a folder called `final-final-2`.

All you need is Markdown and Git. No installation. No CLI to learn. No dependencies to babysit. Just bring a question.

## Open your lab in five minutes 🚀

1. Choose **Use this template → Create a new repository** on GitHub. Choose the visibility appropriate for your work.
2. Replace this README with your project's introduction and fill in [GOAL.md](GOAL.md).
3. Copy `experiments/_template/` to `experiments/exp-001/` and give your first hunch somewhere to live.
4. Write the question and conditions before peeking at the answer. Record your sources in [provenance/SOURCES.md](provenance/SOURCES.md), then run the experiment.
5. Capture what happened—even if the answer is “nope”—and add the resulting decision to [DECISIONS.md](DECISIONS.md).

Keep the TinyLab license notice for reused template material. Select an appropriate license for your own additions and document any third-party terms separately.

## Your tiny lab bench 🧰

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

## The loop 🔁

**Question → conditions → experiment → evidence → decision.**

That is the whole machine. Keep it small, run it honestly, and let each answer sharpen the next question.

- Keep questions small enough to answer within your budget.
- Commit conditions before inspecting results. If the design changes afterward, create a new experiment and link the original.
- Separate measured results, estimates, and unknowns. A negative or inconclusive result still earns its place in the lab book.
- Link decisions to experiments and source records. Leave exploratory ideas in `research/` until ready to test.

For example: “Can someone identify the current goal and the reason for the latest decision in under two minutes?” Define the participants, task, measurement, and pass threshold before testing. This is an illustrative question, not a completed experiment.

## Tiny is a feature 🌱

Use only the sections that help your next decision. Skip the rest. TinyLab has no prescribed language, framework, database, or research domain, and it would like to keep things that way.

If the lab coat starts feeling heavy, remove something. If you spot a recurring problem, propose a focused improvement through an issue or a small pull request.

## Before opening the doors 🌍

- Review all tracked files and Git history for credentials, personal information, and confidential material. `.gitignore` does not remove previously committed files.
- Check the license and redistribution rights for each source and dataset. The scaffold's MIT license does not grant rights to third-party material.
- Replace unfinished public claims with accurate status labels and remove project-specific placeholders from the introduction.
- Check that evidence links and reproduction instructions work for the intended reader.

Repository visibility is a separate GitHub setting. Having a license does not make a private repository public.

## One last note

TinyLab helps you build a good evidence trail; it cannot make a claim true or stop Git history from being rewritten. Curiosity is welcome here. So is changing your mind.

## License

[MIT](LICENSE). Copyright (c) 2026 rihito-dev.
