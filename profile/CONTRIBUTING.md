
# Contributing to FASTCPP

Thank you for your interest in contributing to **FASTCPP**. We appreciate your time and effort in helping us build fast and modern C++ libraries and tools.

This document outlines the guidelines for contributing to any of the repositories under the FASTCPP organization.

## How to Contribute

There are several ways you can contribute:

- Reporting bugs
- Suggesting new features
- Improving documentation
- Writing new utility functions or data structures
- Optimizing existing implementations
- Reviewing and improving code

## Getting Started

1. **Fork the repository** you wish to contribute to.
2. **Clone your fork** to your local machine:
git clone https://github.com/your-username/repo-name.git
3. **Create a new branch** for your changes:
git checkout -b your-feature-name
4. Make your changes and commit them with a clear message:
git commit -m "Brief description of your change"
5. **Push your branch** to your fork:
git push origin your-feature-name
6. **Open a Pull Request** from your fork to the `main` branch of the upstream repository.

## Code Style Guidelines

Please follow these conventions when writing C++ code:

- Use consistent indentation (4 spaces).
- Follow modern C++17 or above standards.
- Prefer `const` correctness and avoid unnecessary copying.
- Use clear and meaningful variable and function names.
- Avoid using raw pointers unless necessary; prefer smart pointers.
- Include appropriate header guards or use `#pragma once`.

## Build and Test

All code should be buildable using **CMake**. Please ensure:

- The code compiles without warnings or errors.
- You have added or updated unit tests if applicable.
- The tests pass successfully before submitting a pull request.

## Submitting Issues

If you find a bug or have a feature request:

- Check the Issues tab to see if it already exists.
- If not, open a new issue with a clear title and description.
- Include steps to reproduce the issue, if relevant.

## Pull Request Review Process

Once you open a pull request:

- The maintainers will review your changes.
- You may be asked to make modifications before the PR is merged.
- Once approved, the changes will be merged into the main branch.

## Community Guidelines

- Be respectful and constructive in discussions.
- Review code thoughtfully and provide actionable feedback.
- Help others learn and grow where possible.

## License

By contributing to this project, you agree that your contributions will be licensed under the terms of the repository's license (typically MIT License).

---

We are glad to have you on board. Let's build high-performance tools and algorithms in C++ together.
