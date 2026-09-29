# Agents.md

Guidance for AI Code when working in this repository.

## Git workflow (required)

**Always create a feature branch before doing any work.** Never commit directly to `main`.

- Branch off `main` before making any changes: `git checkout -b feature/<what-we-are-working-on>`
- Prefix is lowercase `feature/`, followed by a short kebab-case description of the task.
  Examples: `feature/contact-trigger-fix`, `feature/membership-flow`, `feature/update-readme`
- Do this first, before editing files, even for small changes.
- If already on a `feature/*` branch for the current task, keep using it.
- Open pull requests against `main`. Remote is `origin`

