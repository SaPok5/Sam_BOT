# Contributing to Sam_BOT

Thank you for considering contributing to Sam_BOT! This document outlines the process for contributing to the project.

## Code of Conduct

By participating in this project, you agree to maintain a respectful and inclusive environment for everyone.

## How Can I Contribute?

### Reporting Bugs

- Check if the bug has already been reported in the Issues section
- Use the bug report template to create a new issue
- Include detailed steps to reproduce the bug
- Describe expected vs. actual behavior
- Include relevant logs, screenshots, or error messages

### Suggesting Enhancements

- Check if the enhancement has already been suggested in the Issues section
- Use the feature request template to create a new issue
- Describe the feature clearly and explain its value to the project
- Consider including mockups or examples

### Code Contributions

#### Local Development

1. Fork the repository
2. Clone your fork to your local machine
3. Create a new branch for your changes: `git checkout -b feature/your-feature-name`
4. Install development dependencies: `pip install -r requirements.txt`
5. Make your changes
6. Run tests to ensure your changes don't break existing functionality: `pytest`
7. Update documentation if necessary

#### Pull Request Process

1. Push your changes to your fork: `git push origin feature/your-feature-name`
2. Create a pull request to the main repository's `main` branch
3. Follow the pull request template
4. Ensure all CI checks pass
5. Wait for a maintainer to review your PR
6. Implement any requested changes

## Style Guidelines

### Code Style

- Follow PEP 8 guidelines for Python code
- Use Black for code formatting (`black src/`)
- Use descriptive variable and function names
- Add appropriate docstrings and comments
- Import modules in the following order:
  1. Standard library imports
  2. Third-party library imports
  3. Local application imports

### Commit Messages

- Use clear, descriptive commit messages
- Start with a short summary (50 chars or less)
- Use the imperative mood ("Add feature" not "Added feature")
- Reference issues or pull requests when applicable

## Testing

- Write tests for new features or bug fixes
- Ensure all tests pass before submitting a pull request
- Aim for high test coverage

## Documentation

- Update README.md if necessary
- Update API documentation for new features
- Add comments to complex code sections
- Update the DOCUMENTATION.md file with detailed explanations

## Questions?

If you have any questions about contributing, please open an issue labeled "question". 