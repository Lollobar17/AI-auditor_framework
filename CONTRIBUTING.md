# Contributing to AI Safety & Audit Framework

Thank you for your interest in contributing to this project.
The following guidelines will help you get started.

---

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [How to Contribute](#how-to-contribute)
- [Reporting Issues](#reporting-issues)
- [Submitting Changes](#submitting-changes)
- [Contribution Areas](#contribution-areas)
- [Style Guidelines](#style-guidelines)

---

## Code of Conduct

This project adheres to a standard of respectful and constructive collaboration.
All contributions are expected to be professional, well-documented, and aligned
with the project's core mission: promoting safe and auditable use of AI in
high-stakes domains.

---

## How to Contribute

1. Fork the repository
2. Create a new branch from `main`:
```
   git checkout -b feature/your-feature-name
```
3. Make your changes
4. Commit using descriptive messages (see Style Guidelines below)
5. Push your branch and open a Pull Request

---

## Reporting Issues

If you find a bug, an inconsistency in the audit logic, or want to suggest
an improvement, please open an Issue and include:

- A clear title and description
- Steps to reproduce (if applicable)
- Expected vs actual behavior
- Any relevant screenshots or files

---

## Submitting Changes

When opening a Pull Request, please:

- Describe what you changed and why
- Reference any related Issue (e.g., `Closes #12`)
- Make sure your changes do not break existing examples
- Keep PRs focused — one feature or fix per PR

All Pull Requests will be reviewed before merging.

---

## Contribution Areas

The following areas are particularly welcome:

| Area | Examples |
|---|---|
| **New audit scenarios** | Investment newsletters, trading signals, ESG reports |
| **Prompt improvements** | Refining XML audit logic for edge cases |
| **Case studies** | Documented real-world AI interactions + audit results |
| **Translations** | Audit prompts in languages other than English |
| **Documentation** | Clarifications, corrections, additional examples |

---

## Style Guidelines

### Commit Messages

Use the following prefixes for clarity:

| Prefix | When to use |
|---|---|
| `feat:` | Adding a new feature or case study |
| `fix:` | Correcting a bug or logic error |
| `docs:` | Documentation changes only |
| `refactor:` | Restructuring without changing behavior |
| `chore:` | Maintenance tasks (renaming files, cleanup) |

Examples:
```
feat: add investment newsletter audit case study
docs: clarify 4D framework description in README
fix: correct XML tag nesting in audit_logic.xml
```

### File Naming

- Use `snake_case` for all files and folders
- Case study folders should follow the pattern: `topic_audit` (e.g., `crypto_audit`)
- XML prompt files should be descriptive: `audit_logic_financial.xml`

---

For any questions, feel free to open an Issue or reach out directly via GitHub.
