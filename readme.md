# Prettier Mirror

[![Build Status](https://img.shields.io/github/workflow/status/prettier/pre-commit/Test?style=flat-square&label=test)](https://github.com/prettier/pre-commit/actions?query=branch%3Amain+workflow%3ATest)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

> Mirror of Prettier package for pre-commit.

- Prettier: <https://github.com/prettier/prettier>
- pre-commit: <https://github.com/pre-commit/pre-commit>

## Usage

> Using Prettier with pre-commit

Add this to your `.pre-commit-config.yaml`:

```yaml
- repo: https://github.com/prettier/pre-commit
  hooks:
    - id: prettier
```
