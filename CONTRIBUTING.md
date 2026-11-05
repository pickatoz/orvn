# Contributing to ORVN

Thank you for your interest in contributing to ORVN! Contributions, bug reports, and feature suggestions are welcome.

## Getting Started

**Requirements:**
- Python 3.12+
- [uv](https://docs.astral.sh/uv/)
- Git

**Setup:**

1. Fork the repository.
2. Clone your fork:

   ```bash
   git clone https://github.com/YOUR_USERNAME/orvn.git
   cd orvn
   ```

3. Install dependencies:

   ```bash
   uv sync
   ```

## Development Guidelines

- Follow Python best practices.
- Keep code clean, readable, and maintainable.
- Write tests for new features and bug fixes.
- Update documentation when necessary.
- Keep pull requests focused and concise.

## Conventional Commits

ORVN follows the [Conventional Commits](https://www.conventionalcommits.org/) specification.

**Commit format:**

```text
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

**Common commit types:**

| Type | Description |
|---|---|
| `feat` | Introduces a new feature |
| `fix` | Fixes a bug |
| `docs` | Documentation changes |
| `style` | Formatting or styling changes |
| `refactor` | Code restructuring without behavior changes |
| `perf` | Performance improvements |
| `test` | Adds or updates tests |
| `build` | Build system or dependency changes |
| `ci` | CI/CD configuration changes |
| `chore` | Maintenance tasks |
| `revert` | Reverts a previous commit |

**Examples:**

```bash
feat: add file-based routing
feat(router): support dynamic routes
fix: resolve route matching issue
fix(router): handle missing routes
docs: update installation guide
refactor(core): simplify application initialization
test: add router unit tests
chore: update dependencies
```

## Pull Requests

- Create a descriptive branch.
- Follow the commit convention.
- Ensure relevant tests pass.
- Provide a clear description of your changes.
- Link related issues when applicable.

## Reporting Issues

Found a bug or have a feature request? Please open an issue in the repository with relevant details.

**Repository:** https://github.com/pickatoz/orvn.git

Thank you for contributing to ORVN!