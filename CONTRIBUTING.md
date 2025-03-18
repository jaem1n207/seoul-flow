# Contributing Guidelines

<p align="center">
  <a href="README.ko.md">한국어</a> | <a href="README.md">English</a>
</p>

Thank you for your interest in the SeoulFlow project! This document provides guidelines on how to contribute to the project.

## Issue Reporting

If you find a bug or want to suggest a new feature, please use the [GitHub Issue Tracker](https://github.com/jaem1n207/seoul-flow/issues):

1. First, check if the issue has already been reported.
2. When creating a new issue, provide as much detailed information as possible:
   - For bugs: Steps to reproduce, expected behavior, actual behavior, screenshots, device/OS information
   - For feature suggestions: Detailed description, possible implementation methods, use cases

## Development Process

1. Fork the repository and clone it locally.
2. Create a new branch (feature/xxx, bugfix/xxx, etc.).
3. Write code following the code style guide.
4. Add tests and ensure all tests pass.
5. Submit a Pull Request.

## Code Style Guide

- TypeScript/JavaScript code should follow ESLint and Prettier configurations.
- Components should be organized by functionality.
- Add comments to all functions and important variables.
- Commit messages should be written in English and follow this format:
  - `feat: Add new feature`
  - `fix: Fix bug in...`
  - `docs: Update documentation`
  - `style: Format code`
  - `refactor: Refactor code without changing functionality`
  - `test: Add or update tests`
  - `chore: Update build process or auxiliary tools`

## Pull Request Process

1. The PR title should concisely describe the changes.
2. The PR description should explain the changes and the reasons for them in detail.
3. After code review, the project maintainer will approve and merge.
4. If there is a related issue, mention it in the PR with "Closes #issue_number" to automatically close it after merging.

<!-- ## Translation Contributions

We also welcome contributions for multilingual support of the app:

1. Find translation files in the `src/assets/locales/` directory.
2. Add a new language or improve existing translations.
3. Submit a PR when translation is complete. -->

## Code Review

All submissions must pass code review. Reviewers will check for:

- Code quality and readability
- Test coverage
- Meeting feature requirements
- Compliance with the code style guide

## Acknowledgement

Thank you to all who have contributed to SeoulFlow. Your support and contributions are a great help in creating a better service.
