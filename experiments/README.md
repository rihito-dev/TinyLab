# Experiments

Copy `_template/` to the next unused `exp-NNN/` directory. The template is blank; no experiments have been run in this scaffold.

1. Write `hypothesis.md` and `conditions.md` before collecting or inspecting results.
2. Register input sources in `../provenance/SOURCES.md` and commit the plan. Record that commit ID in the result later.
3. Execute within the stated budget and stopping rules.
4. Complete `result.md`, including failed checks, exclusions, and inconclusive outcomes.
5. Link any resulting decision in `../DECISIONS.md`.

Use these lifecycle statuses: **planned**, **running**, **completed**, or **stopped**. Record the outcome separately: **supported**, **not supported**, or **inconclusive**. Completed means the planned work finished, not that the hypothesis succeeded.

Do not reuse an experiment ID. Changes after seeing results belong in a new experiment, linked to the original and labeled as exploratory where appropriate. This is a manual convention, not an automated lock.
