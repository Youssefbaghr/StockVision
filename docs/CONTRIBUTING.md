# Contributing to StockVision

First off, thank you for considering contributing to StockVision! It's people like you that make StockVision such a great tool. We welcome contributions from everyone, whether it's a bug report, feature suggestion, or code contribution.

## Table of Contents

1. [Code of Conduct](#code-of-conduct)
2. [Getting Started](#getting-started)
    - [Issues](#issues)
    - [Pull Requests](#pull-requests)
3. [Coding Standards](#coding-standards)
4. [Commit Guidelines](#commit-guidelines)
5. [Testing](#testing)
6. [Documentation](#documentation)
7. [Community](#community)

## Code of Conduct

This project and everyone participating in it is governed by the [StockVision Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code. Please report unacceptable behavior to [conduct@stockvision.com](mailto:conduct@stockvision.com).

## Getting Started

### Issues

-   Search for existing issues before creating a new one.
-   Use a clear and descriptive title.
-   Provide as much information as possible in the issue description.
-   For bug reports, include steps to reproduce, expected behavior, and actual behavior.
-   For feature requests, explain why this feature would be useful.

### Pull Requests

1. Fork the repository and create your branch from `main`.
2. If you've added code that should be tested, add tests.
3. Ensure the test suite passes.
4. Make sure your code lints.
5. Issue that pull request!

## Coding Standards

-   For JavaScript/TypeScript:

    -   Follow the [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript).
    -   Use ES6+ features when possible.
    -   Use meaningful variable and function names.

-   For Python:

    -   Follow [PEP 8](https://www.python.org/dev/peps/pep-0008/) style guide.
    -   Use type hints when possible.

-   For React/React Native:

    -   Follow the [React Style Guide](https://github.com/airbnb/javascript/tree/master/react).
    -   Use functional components and hooks instead of class components when possible.

-   General:
    -   Keep functions small and focused on a single task.
    -   Write self-documenting code and add comments only when necessary.
    -   Use consistent indentation (2 spaces for JS/TS, 4 spaces for Python).

## Commit Guidelines

-   Use the present tense ("Add feature" not "Added feature").
-   Use the imperative mood ("Move cursor to..." not "Moves cursor to...").
-   Limit the first line to 72 characters or less.
-   Reference issues and pull requests liberally after the first line.

## Testing

-   Write unit tests for new features and bug fixes.
-   Ensure all tests pass before submitting a pull request.
-   Aim for high test coverage, but prioritize meaningful tests over coverage percentage.

For running tests:

-   Backend: `npm run test` in the `backend` directory.
-   Frontend: `npm test` in the `frontend` directory.
-   Python services: `python -m unittest discover tests` in the `python` directory.

## Documentation

-   Update the README.md with details of changes to the interface, new environment variables, exposed ports, useful file locations, and container parameters.
-   Update the API documentation if you change or add new endpoints.
-   Maintain inline documentation for complex functions or algorithms.

## Community

-   Join our [Discord server](https://discord.gg/stockvision) for real-time discussions.
-   Subscribe to our [mailing list](https://stockvision.com/mailing-list) for important announcements.
-   Follow our [blog](https://blog.stockvision.com) for the latest updates and articles.

Remember, contributions to StockVision don't just mean writing code. Improving documentation, submitting bug reports, and providing feedback on feature requests are all valuable contributions!

Thank you for your interest in improving StockVision. Your contributions are greatly appreciated!
