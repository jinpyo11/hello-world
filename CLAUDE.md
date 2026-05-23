# CLAUDE.md

## Repository Overview

This is a minimal "hello-world" repository used for Git learning and testing. It contains a single `README.md` and serves as a sandbox for practicing Git workflows.

## Repository Structure

```
hello-world/
└── README.md   # Main file; content modified during git testing exercises
```

## Branches

- `master` — primary branch; contains the stable README
- `claude/claude-md-docs-*` — AI assistant working branches (convention: `claude/<task>-<id>`)

## Git Conventions

- Commit messages are short and descriptive (e.g., "Update README.md")
- Merges are done via pull requests, not direct pushes to `master`
- Feature/edit branches are named after the change (e.g., `readme-edits`)

## Development Workflow

1. Create a branch off `master` for any change
2. Commit changes with a clear message
3. Push the branch and open a pull request
4. Merge into `master` after review

## AI Assistant Notes

- This repo has no build system, test suite, or CI pipeline
- There are no linting rules or code style requirements
- Changes here are low-stakes; the primary purpose is git workflow practice
- When asked to make changes, commit to the designated feature branch and push
- Do **not** push directly to `master` without explicit user instruction
