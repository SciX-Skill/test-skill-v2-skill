# Contributing Guide

Welcome! This guide explains how to contribute to Test Skill V2.

This project uses Fork + PR workflow. No repository push permissions required.

## Table of Contents

- [Contribution Process](#contribution-process)
- [Version Rules](#version-rules)
- [Getting Specific Versions](#getting-specific-versions)
- [Reporting Issues](#reporting-issues)

---

## Contribution Process

### 1. Fork the Repository

Click the **Fork** button in the top-right corner of the repository page.

### 2. Clone Your Fork

```bash
git clone https://github.com/<YOUR_USERNAME>/test-skill-v2-skill.git
cd test-skill-v2-skill
```

### 3. Create a Development Branch

```bash
# Create a new branch based on main
git checkout -b fix/xxx  # or feature/xxx
```

### 4. Make Changes and Commit

```bash
git add .
git commit -m "Describe your changes"
git push origin fix/xxx
```

### 5. Create a Pull Request

1. Open your forked repository page
2. Click **Compare & pull request**
3. Ensure base is `main`
4. Fill in the PR description and submit

### 6. Wait for CI and Auto-Merge

- CI checks will run automatically after submission
- PR will be auto-merged when CI passes
- Version branch will be created/updated after merge

---

## Version Rules

| Version | Created When |
|---------|--------------|
| `version/v1` | After first PR is merged |
| `version/v2` | After second PR is merged |
| `version/v3` | After third PR is merged |

Each PR merged to main will automatically create/update the next version branch.

---

## Getting Specific Versions

```bash
# Clone latest development version
git clone https://github.com/SciX-Skill/test-skill-v2-skill.git
cd test-skill-v2-skill

# Switch to specific version
git checkout version/v1

# List all version branches
git fetch origin
git branch -r

# Switch to another version
git checkout version/v2
```

---

## Reporting Issues

If you encounter issues with this skill, please open an issue:
https://github.com/SciX-Skill/test-skill-v2-skill/issues
