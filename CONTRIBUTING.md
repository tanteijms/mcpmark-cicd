# How to Contribute

Thank you for your interest in contributing to this project! We welcome contributions from everyone and appreciate your effort to improve this project. This document provides guidelines and instructions for contributing.

## Code of Conduct

By participating in this project, you agree to abide by our Code of Conduct. We are committed to providing a welcoming and inclusive experience for everyone. Please be respectful and constructive in all interactions with other contributors and maintainers.

We expect all participants to:
- Use welcoming and inclusive language
- Be respectful of differing viewpoints and experiences
- Gracefully accept constructive criticism
- Focus on what is best for the community and the project

## How to Submit Contributions

We use a standard fork-and-pull-request workflow. Follow these steps to contribute:

### 1. Fork the Repository

Click the "Fork" button at the top right of the repository page to create your own copy of the project.

### 2. Clone Your Fork

```bash
git clone https://github.com/your-username/mcpmark-cicd.git
cd mcpmark-cicd
```

### 3. Create a Feature Branch

Always create a new branch for your changes. Use a descriptive branch name:

```bash
git checkout -b feature/your-feature-name
```

### 4. Make Your Changes

- Write clean, well-documented code
- Follow the project's coding conventions and style guide
- Add or update tests as needed
- Ensure all existing tests pass

### 5. Commit Your Changes

Write clear, concise commit messages:

```bash
git add .
git commit -m "feat: add description of your change"
```

### 6. Push and Create a Pull Request

```bash
git push origin feature/your-feature-name
```

Then open a pull request from your branch to the `main` branch of this repository.

## Style Guide

### Code Formatting

- This project uses **ESLint** for linting and **Prettier** for code formatting
- Run `npm run lint` before submitting to ensure your code passes all linting checks
- Follow the existing code style and patterns found in the codebase
- Use meaningful variable and function names

### Commit Messages

- Use the conventional commits format: `type(scope): description`
- Types: `feat`, `fix`, `docs`, `style`, `refactor`, `test`, `chore`
- Keep the subject line under 72 characters
- Use the imperative mood ("add feature" not "added feature")

## Reporting Issues

If you find a bug or have a feature request:

1. Check existing issues to avoid duplicates
2. Use the appropriate issue template if available
3. Provide as much detail as possible, including steps to reproduce bugs
4. Include your environment details (OS, Node.js version, etc.)

## Development Setup

1. Ensure you have Node.js installed (check `package.json` for version requirements)
2. Install dependencies: `npm install`
3. Run tests: `npm test`
4. Run linting: `npm run lint`

## Review Process

All pull requests will be reviewed by at least one maintainer. We aim to review PRs within a reasonable timeframe. During the review process:

- Be open to feedback and requested changes
- Respond to review comments promptly
- Update your PR as needed based on feedback

Thank you for contributing!
