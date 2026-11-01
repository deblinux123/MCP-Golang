# MCP with Go — Project-Based Learning

A hands-on journey into the **Model Context Protocol (MCP)** using Go. This repository contains a series of independent projects designed to build practical MCP development skills, from creating a basic server to integrating AI models, external APIs, and academic research tools.

## 🎯 Goals

- Understand MCP architecture, tools, resources, and prompts.
- Build MCP servers using Go and the official Go SDK.
- Integrate external APIs and local AI models.
- Practice input validation, error handling, context cancellation, and testing.
- Build reusable, maintainable backend services.
- Develop an Academic Research MCP Server that can work with research APIs and RAG systems.

## 🛠️ Tech Stack

- **Language:** Go
- **Protocol:** Model Context Protocol (MCP)
- **SDK:** [Official MCP Go SDK](https://github.com/modelcontextprotocol/go-sdk)
- **AI Runtime:** Ollama
- **Vector Database:** Qdrant
- **Potential integrations:** Crossref, OpenAlex, and authorized academic research APIs

## 📚 Learning Roadmap

| # | Project | Main Topics | Status |
|---|---|---|---|
| 01 | System Info MCP | MCP fundamentals, server setup, tool registration, tool discovery and execution | 🚧 In Progress |
| 02 | Notes MCP | Multiple tools, input validation, file operations | ⏳ Planned |
| 03 | Weather MCP | HTTP clients, external APIs, timeouts, error handling | ⏳ Planned |
| 04 | GitHub MCP | API integration, pagination, filtering, authentication | ⏳ Planned |
| 05 | Ollama MCP | Local LLM integration and AI tool workflows | ⏳ Planned |
| 06 | Academic Research MCP | Research APIs, paper discovery, metadata, RAG integration | ⏳ Planned |

Each project is intended to be an independent, runnable application with its own documentation and practical exercises.

## 📁 Repository Structure

The repository will gradually grow into the following structure:

```text
Mcp-Golang/
├── README.md
├── .gitignore
├── 01-system-info/
│   ├── README.md
│   ├── go.mod
│   ├── go.sum
│   └── cmd/
│       └── server/
│           └── main.go
├── 02-notes-mcp/
├── 03-weather-mcp/
├── 04-github-mcp/
├── 05-ollama-mcp/
└── 06-academic-research-mcp/
```

> The structure is a roadmap; directories will be added as each project begins.

## 🚀 Getting Started

### Prerequisites

- Go installed on your system
- Git
- Basic knowledge of Go programming
- An MCP-compatible client for integration testing when needed

### Clone the Repository

Replace `<your-github-username>` with your GitHub username:

```bash
git clone https://github.com/<your-github-username>/Mcp-Golang.git
cd Mcp-Golang
```

Follow the README inside each project directory for installation, configuration, and execution instructions.

## 🧠 Learning Approach

Every project follows the same workflow:

1. **Learn:** Understand the concepts and MCP protocol operations.
2. **Build:** Implement the server step by step.
3. **Test:** Verify behavior and handle errors.
4. **Document:** Explain the architecture, tools, and usage.
5. **Review:** Complete a checkpoint before moving to the next project.

The focus is on understanding how MCP works, not just copying code.

## 🗺️ Long-Term Goal: Academic Research MCP

The final project aims to provide an MCP interface for academic research workflows, including:

- Searching for scholarly publications through supported APIs.
- Retrieving paper metadata, authors, DOIs, and publication details.
- Connecting research tools to an existing RAG pipeline.
- Integrating with Ollama and Qdrant.
- Returning traceable results without inventing bibliographic information.

Access to full-text content will depend on the availability of open-access sources or appropriate authorization.

## 📖 References

- [Official MCP Documentation](https://modelcontextprotocol.io/)
- [Official MCP Go SDK](https://github.com/modelcontextprotocol/go-sdk)
- [Crossref API Documentation](https://www.crossref.org/documentation/retrieve-metadata/rest-api/)
- [OpenAlex API Documentation](https://docs.openalex.org/)

## 📌 Progress

This repository is under active development. Projects, documentation, and examples will be added incrementally as each learning milestone is completed.

---

**Built with Go, curiosity, and a project-by-project approach to learning MCP.**