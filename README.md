

\# PersonalAI



\*\*A lightweight, local-first personal AI assistant built with ASP.NET Core and C#.\*\*



PersonalAI is an open-source project focused on building a customizable AI assistant that runs primarily on your own machine.



The goal is to provide a private, extensible AI environment without depending on paid AI APIs for local model inference.



> \*\*Project status:\*\* Early development. Core AI functionality has not been implemented yet.



\## Vision



PersonalAI aims to provide:



\- Local LLM inference using downloadable open-weight models.

\- A lightweight custom chat interface.

\- Integration with local AI runtimes.

\- Real-time web search with source references.

\- Persistent conversation history and personal memory.

\- Retrieval-Augmented Generation (RAG) for personal documents.

\- Developer tools for coding assistance.



\## Technology Stack



| Component | Technology |

|---|---|

| Backend | ASP.NET Core MVC |

| Language | C# |

| Frontend | Razor, HTML, CSS, JavaScript |

| Framework | .NET 10 LTS |

| Database | PostgreSQL |

| ORM | Entity Framework Core |

| Local AI Runtime | Ollama (initial target) |

| Version Control | Git and GitHub |



The stack may evolve as the project develops.



\## Project Structure



```text

PersonalAI/

├── src/

│   └── PersonalAI.Web/

├── tests/

├── docs/

├── .github/

├── .editorconfig

├── .gitignore

├── PersonalAI.slnx

├── README.md

├── ROADMAP.md

└── PROJECT\_STATE.md

```



\## Getting Started



\### Prerequisites



\- Windows 11 or another supported .NET environment.

\- .NET 10 SDK.

\- Git.



PostgreSQL and a local AI runtime will be introduced in later development phases.



\### Build



```bash

git clone YOUR\_REPOSITORY\_URL

cd PersonalAI

dotnet restore PersonalAI.slnx

dotnet build PersonalAI.slnx

```



\### Run



```bash

dotnet run --project src/PersonalAI.Web/PersonalAI.csproj

```



\## Privacy Philosophy



PersonalAI is designed around local-first processing.



Local model inference should not require sending prompts to a commercial AI provider.



Optional Internet integrations, such as web search, may communicate with external services. Their data flow will be documented and configurable.



\## Roadmap



See \[ROADMAP.md](ROADMAP.md).



\## Development Progress



See \[PROJECT\_STATE.md](PROJECT\_STATE.md).



\## Contributing



Contribution guidelines will be published as the project matures.



## License

This project is licensed under the Apache License, Version 2.0.

See the [LICENSE](LICENSE) file for the complete license text.

SPDX-License-Identifier: Apache-2.0
