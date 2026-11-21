\# PersonalAI — Project State

Last updated: 2026-11-20

\## Project Goal

Build a lightweight, customizable, local-first AI assistant using ASP.NET Core MVC, C#, and open-weight language models.

The project prioritizes local inference, resource efficiency, modular architecture, privacy, and open-source maintainability.

\## Developer Environment

\- OS: Windows 11

\- IDE: Visual Studio 2026, version 18.11.0

\- .NET SDK: 10.0.403

\- Target Framework: net10.0

\- CPU: Intel i5-12450HX

\- GPU: NVIDIA RTX 4050 Laptop, 6GB VRAM

\- RAM: 24GB

\- Git: 2.51.0.windows.1

\## Technology Decisions

| Area | Decision |

|---|---|

| Backend | ASP.NET Core MVC |

| Language | C# |

| Frontend | Razor, HTML, CSS, JavaScript |

| Framework | .NET 10 LTS |

| Database | PostgreSQL |

| ORM | Entity Framework Core |

| PostgreSQL Provider | Npgsql |

| Initial AI Runtime | Ollama |

| Version Control | Git and GitHub |

## Completed Milestones

- [x] Step 0.1: Environment verification.
- [x] Step 0.2: Git installation and identity verification.
- [x] Step 0.3: ASP.NET Core MVC project creation.
- [x] Step 0.4: GitHub no-reply email configuration.
- [x] Step 0.5: Solution and source project structure.
- [x] Step 0.6: Documentation foundation.
- [x] Step 0.7: Repository security and gitignore rules.
- [x] Step 0.8: Apache License 2.0 integration.

## Current Milestone

Step 0.9: Pre-release repository review and initial GitHub publication.

\## Current Repository Structure

```text

PersonalAI/

├── src/

│   └── PersonalAI.Web/

├── PersonalAI.slnx

├── .gitignore

└── documentation files (in progress)

```

\## Architecture Principles

1\. Keep the application lightweight.

2\. Separate UI, business logic, and infrastructure.

3\. Use interfaces for replaceable services.

4\. Keep local model inference independent from the web application.

5\. Never commit personal data, API keys, secrets, or model files.

6\. Test changes before committing.

7\. Document important architectural decisions.

\## Important Constraints

\- Local inference must not require paid API billing.

\- External web search is optional and must be configurable.

\- The application should work locally without requiring Internet access for basic chat.

\- Model files must remain outside the Git repository.

\## Next Steps

1\. Complete initial documentation.

2\. Review repository structure.

3\. Select an open-source license.

4\. Create the public GitHub repository.

5\. Make the first clean Git commit.

6\. Establish architecture documentation.

7\. Begin application development.

## Repository Publication

- GitHub Repository: https://github.com/Bikas-cloud/PersonalAI
- Visibility: Public
- Default Branch: main
- Initial Commit: f4a2444
- Initial Commit Message: chore: initialize PersonalAI repository
- Initial Publication Date: 2026-11-21
- Remote: origin
- Upstream: main -> origin/main

### Initial Verification

- .NET 10 solution build: Successful
- Git working tree: Clean
- Local and remote main branches: Synchronized
- Initial repository files: 85
