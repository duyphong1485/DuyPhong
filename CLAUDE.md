# CLAUDE.md - Repository Guide for AI Assistants

## Repository Overview

This is **duyphong1485/DuyPhong** — a GitHub profile repository for Tran Duy Phong, a BRSE (Bridge System Engineer) based in Fukuoka, Japan. The repository serves as a personal GitHub profile page (the special `username/username` repo whose README.md appears on the GitHub profile).

## Repository Structure

```
/
├── README.md              # GitHub profile page (main content of the repo)
├── project_phong_test/    # Empty placeholder directory (historical)
├── CLAUDE.md              # This file
└── .git/
```

This is a minimal, non-code repository. There is no application source code, no build system, no package manager, and no tests.

## Key Files

- **README.md** — The only meaningful file. Contains the owner's profile with:
  - Personal introduction (name, role, location)
  - Tech stack badges (React, Python) via shields.io
  - GitHub stats badges
  - Animated typing SVG widget
  - Spotify integration widget

## Repository History

- **Created**: December 29, 2020, originally as a Java practice project (`Teacher.java`)
- **Transformed**: March 9, 2025, into a GitHub profile repository (Java code deleted, README.md created)
- The `project_phong_test/` directory is a leftover from the original project structure and is empty

## Development Workflows

### There is no build/test/lint pipeline

- No `package.json`, `Makefile`, `pom.xml`, or any build configuration
- No CI/CD workflows (`.github/workflows/` does not exist)
- No linter, formatter, or pre-commit hooks configured
- No test framework or test files

### Making changes

All meaningful work in this repository is editing `README.md`. Changes are typically committed directly to the main branch via the GitHub web editor or through Claude Code sessions.

### Commit conventions

Historical commits use short, descriptive messages (e.g., "Update README.md", "Delete Teacher.java"). There is no formal commit message convention.

## Tech Context

The repository owner's tech stack (from the profile):
- **React** — frontend framework
- **Python** — general-purpose language
- Role: BRSE (Bridge System Engineer) in Japan

## Conventions for AI Assistants

1. **README.md is the product** — treat it as the primary deliverable, not documentation for code
2. **Keep it lightweight** — do not introduce build tooling, config files, or framework scaffolding unless explicitly requested
3. **Preserve emoji style** — the README uses emoji headers consistently; maintain this pattern if editing
4. **Badge format** — shields.io badges use `for-the-badge` style; keep this consistent when adding new badges
5. **No code project exists** — do not assume there is application code to build, test, or lint
6. **Profile repo rules** — the README.md renders on the owner's GitHub profile page; changes are publicly visible
