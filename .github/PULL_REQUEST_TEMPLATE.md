## What and why

<!-- One or two sentences: the problem, and how this change solves it. -->

## How it was verified

- [ ] `python -m unittest discover -s tests` passes
- [ ] `ruff check .`, `ruff format --check .` and `mypy` pass
- [ ] Claims about cost, quality or effort come with a reproducible measurement (`bench/`)
- [ ] Docs updated if behaviour changed

## Risk

<!-- What could this break? Hooks run in every session: any change to hooks/ must keep "never fail the session". -->
