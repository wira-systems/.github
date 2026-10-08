# Contributing to Wira Systems

Thank you for helping. Every Wira Systems repository works the same way.

## Before you start

- **Read the repository's `SPECIFICATION.md` and `PROGRESS.md`.** The first says what the product should be; the second, where the work has got to.
- **A change to how a product looks or works starts in its prototype.** The real app follows the latest prototype, screen by screen.
- **A change of what the product does is an amendment** at the end of `SPECIFICATION.md`, saying what was planned, what is done instead, and why. The specification is never rewritten.

## Branches

- Work on a branch of its own from `development`: `feat/...` for something new, `fix/...` for a bug, `chore/...` for anything else.
- Never commit to `development`, `staging` or `main`. Changes reach `development` by a pull request; promotions to `staging` and `main` are the maintainers'.

## Commits

One commit per task, its message in three parts:

```
<type>(`<path>`): <short description with a backticked `filename`>

<one line saying what was done>

<one line saying why it was done>
```

`<type>` is one of `feat`, `fix`, `refactor`, `style`, `chore`, `perf`, `test`, `docs`, `build`, `ci`. The path is the directory the change centres on, `/` for the whole repository. Each paragraph is one unbroken line; no lists, no trailers.

## Pull requests

- Into `development`, titled `` pr(`<your branch>`): <short description with a backticked `filename`> ``.
- The description is two paragraphs, each one unbroken line: what was done across the branch, then why.
- Run the repository's checks before you open it; nothing is run for you on GitHub.

## Reporting a problem

Bugs and ideas are welcome as issues, through the forms offered. A security problem is never an issue: see [`SECURITY.md`](SECURITY.md).
