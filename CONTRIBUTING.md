# Contributing to Geek Protocol

First off, thank you for considering contributing to Geek Protocol! 🎉

We love receiving contributions from our community. There are many ways to contribute, from writing tutorials or blog posts, improving the documentation, submitting bug reports and feature requests, or writing code which can be incorporated into Geek Protocol itself.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [How Can I Contribute?](#how-can-i-contribute)
  - [Reporting Bugs](#reporting-bugs)
  - [Suggesting Features](#suggesting-features)
  - [Contributing Code](#contributing-code)
  - [Improving Documentation](#improving-documentation)
- [Development Process](#development-process)
- [Pull Request Process](#pull-request-process)
- [Style Guidelines](#style-guidelines)

## Code of Conduct

This project and everyone participating in it is governed by our [Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## Getting Started

1. **Fork the repository** on GitHub
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/Geek-protocol.git
   cd Geek-protocol
   ```
3. **Create a branch** for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   ```

## How Can I Contribute?

### Reporting Bugs

Before creating bug reports, please check existing issues to avoid duplicates. When you create a bug report, include as many details as possible:

- **Use a clear and descriptive title**
- **Describe the exact steps to reproduce the problem**
- **Provide specific examples** to demonstrate the steps
- **Describe the behavior you observed** and what you expected
- **Include screenshots** if applicable
- **Note your environment**: OS, browser, Node version, etc.

**Submit bugs using GitHub Issues with the "bug" label.**

### Suggesting Features

Feature requests are welcome! Before creating a feature request:

- **Check if the feature has already been suggested**
- **Provide a clear and detailed explanation** of the feature
- **Explain why this feature would be useful** to most users
- **Provide examples** of how the feature would be used

**Submit feature requests using GitHub Issues with the "enhancement" label.**

### Contributing Code

1. **Find an issue to work on** or create one
2. **Comment on the issue** to let others know you're working on it
3. **Follow the development process** outlined below
4. **Submit a pull request** when ready

#### Good First Issues

Look for issues labeled `good first issue` - these are great for newcomers!

### Improving Documentation

Documentation improvements are always welcome:

- Fix typos or clarify existing documentation
- Add examples or tutorials
- Improve README or other docs
- Translate documentation to other languages

## Development Process

1. **Set up your development environment**:
   ```bash
   npm install
   npm run dev
   ```

2. **Make your changes**:
   - Write clean, maintainable code
   - Follow our style guidelines
   - Add tests for new features
   - Update documentation as needed

3. **Test your changes**:
   ```bash
   npm test
   npm run lint
   ```

4. **Commit your changes**:
   ```bash
   git add .
   git commit -m "feat: add amazing feature"
   ```
   
   Follow [Conventional Commits](https://www.conventionalcommits.org/) format:
   - `feat:` new feature
   - `fix:` bug fix
   - `docs:` documentation changes
   - `style:` formatting, missing semicolons, etc.
   - `refactor:` code restructuring
   - `test:` adding tests
   - `chore:` maintenance tasks

## Pull Request Process

1. **Update documentation** for any changed functionality
2. **Ensure all tests pass** and add new tests if needed
3. **Update the README.md** if needed
4. **Follow the PR template** when submitting
5. **Link related issues** in your PR description
6. **Request review** from maintainers
7. **Address review feedback** promptly

### PR Checklist

- [ ] Code follows the project's style guidelines
- [ ] Self-review of code completed
- [ ] Comments added for complex code
- [ ] Documentation updated
- [ ] No new warnings generated
- [ ] Tests added/updated and passing
- [ ] Dependent changes merged

## Style Guidelines

### TypeScript/JavaScript

- Use **TypeScript** for type safety
- Follow **ESLint** and **Prettier** configurations
- Use **meaningful variable and function names**
- Write **self-documenting code** with comments for complex logic
- Keep functions **small and focused**
- Prefer **const** over **let**, avoid **var**

### Git Commit Messages

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests after the first line

### Code Review

- Be respectful and constructive
- Ask questions rather than making demands
- Explain your reasoning
- Accept that many programming decisions are opinions

## Questions?

Feel free to reach out:

- **Telegram**: [Join our community](https://t.me/GEEKonKAScommunity)
- **X (Twitter)**: [@geekonkas](https://x.com/geekonkas)
- **GitHub Issues**: For technical questions

## Recognition

Contributors will be recognized in our:
- README.md contributors section
- Release notes
- Community shout-outs

Thank you for helping make Geek Protocol better! 🚀
