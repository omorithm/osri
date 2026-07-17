# Contributing to OSRI

Thank you for your interest in contributing to OSRI.

OSRI is an open-source project focused on understanding and improving the resilience of open-source software. Contributions from developers, researchers, maintainers, and community members are welcome.

Whether you are improving code, documentation, analysis methods, or project ideas, your contribution helps strengthen the project.

---

# Ways to Contribute

There are many ways to contribute to OSRI:

## Code Contributions

Help build and improve:

- data collectors
- analysis modules
- resilience metrics
- CLI functionality
- APIs
- testing infrastructure

## Documentation

Help improve:

- guides
- technical documentation
- examples
- explanations of resilience concepts

## Research Contributions

OSRI welcomes contributions related to:

- open-source sustainability research
- software ecosystem analysis
- resilience measurement approaches
- evaluation methodologies

## Community Contributions

Help by:

- sharing feedback
- reporting issues
- suggesting improvements
- discussing ideas

---

# Development Setup

## Requirements

Before contributing, ensure you have:

- Python 3.11+
- Git
- A GitHub account

---

## Clone the Repository

```bash
git clone https://github.com/omorithm/osri.git

cd osri
```

---

## Create a Virtual Environment

```bash
python -m venv .venv
```

Activate it:

### Linux/macOS

```bash
source .venv/bin/activate
```

### Windows

```bash
.venv\Scripts\activate
```

---

## Install Dependencies

```bash
pip install -e .
```

---

# Project Structure

OSRI follows a modular architecture:

```
osri/

├── src/
│   └── osri/
│
├── tests/
│
├── docs/
│
└── README.md
```

---

# Making Changes

Before starting a large change:

1. Check existing issues and discussions.
2. Open an issue to discuss major proposals.
3. Keep changes focused and well documented.

Small improvements such as documentation updates and bug fixes can usually be submitted directly.

---

# Submitting Pull Requests

A good pull request should:

- Have a clear purpose
- Explain what changed and why
- Include relevant tests
- Update documentation when necessary
- Keep commits focused

Pull requests should help improve OSRI without introducing unnecessary complexity.

---

# Commit Guidelines

OSRI follows conventional commit style.

Examples:

```text
feat: add repository metadata collector

fix: handle missing repository data

docs: improve architecture documentation

test: add collector tests

chore: update dependencies
```

---

# Reporting Issues

When creating an issue, provide:

- A clear description of the problem or idea
- Steps to reproduce (for bugs)
- Expected behavior
- Additional context where helpful

Clear issue reports help contributors understand and solve problems faster.

---

# Community Expectations

OSRI aims to maintain an open, respectful, and collaborative environment.

Contributors are expected to:

- communicate respectfully
- welcome different perspectives
- provide constructive feedback
- focus on improving the project

All contributors are expected to follow the project's Code of Conduct.

---

Thank you for helping build OSRI.
