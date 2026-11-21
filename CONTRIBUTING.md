# Contributing to PersonalAI

Thank you for your interest in contributing to PersonalAI!

PersonalAI is an open-source, local-first personal AI assistant project. Contributions, suggestions, bug reports, documentation improvements, and constructive feedback are welcome.

This document explains how to contribute to the project.

## 1. Before Contributing

Before starting work:

- Read the [README.md](README.md) to understand the project.

- Review the [ROADMAP.md](ROADMAP.md) to understand planned features.

- Check existing GitHub Issues and Pull Requests to avoid duplicated work.

- For significant changes, discuss the proposed approach in an Issue before implementation.

Please keep contributions focused and explain the problem they solve.

## 2. Development Environment

The current development environment requires:

- Windows, Linux, or macOS

- .NET 10 SDK

- Git

- A code editor such as Visual Studio or Visual Studio Code

Additional dependencies may be introduced as the project evolves.

## 3. Getting Started

Clone the repository:

```bash

git clone https://github.com/Bikas-cloud/PersonalAI.git

cd PersonalAI

```

Restore dependencies:

```bash

dotnet restore PersonalAI.slnx

```

Build the solution:

```bash

dotnet build PersonalAI.slnx

```

Run the web application:

```bash

dotnet run --project src/PersonalAI.Web/PersonalAI.csproj

```

Follow the development instructions in the README as the project evolves.

## 4. Branching Strategy

Do not use the `main` branch for ongoing feature development.

Create a dedicated branch for each meaningful change.

Recommended branch naming conventions:

| Prefix | Purpose | Example |

|---|---|---|

| `feat/` | New features | `feat/chat-interface` |

| `fix/` | Bug fixes | `fix/chat-history` |

| `docs/` | Documentation | `docs/update-readme` |

| `refactor/` | Code restructuring | `refactor/ai-services` |

| `test/` | Tests | `test/chat-service` |

| `chore/` | Maintenance | `chore/update-dependencies` |

Example:

```bash

git switch -c feat/chat-interface

```

## 5. Commit Message Convention

PersonalAI follows the Conventional Commits style.

Use the following prefixes:

| Prefix | Purpose |

|---|---|

| `feat:` | Add a feature |

| `fix:` | Fix a bug |

| `docs:` | Documentation changes |

| `refactor:` | Refactor existing code |

| `test:` | Add or update tests |

| `chore:` | Maintenance and project configuration |

Examples:

```text

feat: add conversation history

fix: handle empty chat messages

docs: update installation instructions

refactor: separate AI runtime services

test: add chat service unit tests

chore: update project dependencies

```

Keep commit messages clear, concise, and focused on one logical change.

## 6. Code Quality

Please follow these guidelines:

- Follow the existing project structure and naming conventions.

- Respect the repository's `.editorconfig` settings.

- Prefer readable, maintainable, and well-organized code.

- Avoid unnecessary dependencies.

- Handle errors explicitly where appropriate.

- Do not introduce unrelated changes in a contribution.

- Update documentation when behavior or setup instructions change.

## 7. Testing and Verification

Before submitting a contribution:

1. Restore dependencies when necessary.

2. Build the solution.

3. Run relevant automated tests when available.

4. Verify the changed functionality.

5. Review the final Git diff.

Current baseline verification command:

```bash

dotnet build PersonalAI.slnx

```

As the testing infrastructure evolves, additional test and validation requirements will be documented here.

## 8. Pull Request Guidelines

When submitting a Pull Request:

- Use a clear and descriptive title.

- Explain what changed and why.

- Reference related GitHub Issues when applicable.

- Include relevant testing information.

- Mention any known limitations.

- Keep the Pull Request focused on one logical change.

A contribution should be reviewed before being merged into `main`.

## 9. Security and Privacy

PersonalAI is designed with privacy and local-first development in mind.

Never commit:

- API keys or access tokens

- Passwords or private credentials

- Personal documents or private datasets

- Local database files or database backups

- Private model weights

- Environment-specific secrets

Use appropriate local configuration and environment variables for sensitive information.

Do not publicly disclose security vulnerabilities. Follow the repository's security reporting guidance.

## 10. Licensing

By contributing to PersonalAI, you agree that your contributions will be licensed under the project's [Apache License 2.0](LICENSE).

Only submit code and assets that you have the right to contribute.

## 11. Questions and Suggestions

For questions, feature proposals, bug reports, and other discussions, use the GitHub Issues section:

https://github.com/Bikas-cloud/PersonalAI/issues

Thank you for helping improve PersonalAI!