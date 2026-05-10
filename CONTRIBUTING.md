# Contributing Guidelines

This project follows the  standards set by the Software Engineering Teaching Unit (SETU) for the SENG 31242 course.

## Branching Strategy
We use the following branch naming convention (Section 4.3):
- `main`: Protected branch. Only accepts merges via Pull Request with at least 1 approval.
- `draft/<document>`: Active working branch for a design in progress (e.g., `draft/home-page-wireframe`).
- `fix/<issue-number>`: Corrective changes addressing review feedback.

## Commit Message Convention
All commits must follow the **Conventional Commits** specification (Section 4.4):

### Structure
```
<type>(<scope>): <short imperative summary>

[Optional body: explain WHY this change was made, not WHAT]

[Optional footer: references to issues]
```

### Allowed Types
- `docs`: Adding or updating documentation.
- `feat`: Adding a new design element or wireframe.
- `fix`: Correcting a design error or incorporating review feedback.
- `refactor`: Restructuring folders or renaming files without changing content.
- `chore`: Repository housekeeping (updating .gitignore, README, etc.).
- `style`: Visual styling/formatting changes only.

### Bad Examples (DO NOT USE)
- `updated srs`
- `fixed stuff`
- `changes`
- `doc`
- `v2`
- `final`
- `FINAL_FINAL`

## Pull Request Process
1. Create a draft PR as soon as a branch is created to signal work-in-progress.
2. When ready for review, mark PR as "Ready for Review" and assign a reviewer from the team.
3. The PR description must follow the template in `.github/pull_request_template.md`.
