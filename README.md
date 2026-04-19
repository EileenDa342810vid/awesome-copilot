# awesome-copilot

> A curated list of awesome GitHub Copilot instructions, prompts, agents, and extensions.

[![All Contributors](https://img.shields.io/github/all-contributors/awesome-copilot/awesome-copilot?color=ee8449&style=flat-square)](CONTRIBUTORS.md)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

## Contents

- [Copilot Instructions](#copilot-instructions)
- [Prompt Files](#prompt-files)
- [Agent Workflows](#agent-workflows)
- [Extensions & Plugins](#extensions--plugins)
- [Tools & Utilities](#tools--utilities)
- [Learning Resources](#learning-resources)
- [Contributing](#contributing)

---

## Copilot Instructions

Custom `.github/copilot-instructions.md` files that tailor Copilot behavior for specific stacks and workflows.

- **[Python / FastAPI](instructions/python-fastapi.md)** — Instructions optimized for FastAPI projects with async patterns.
- **[TypeScript / React](instructions/typescript-react.md)** — Instructions for modern React development with TypeScript.
- **[Go / gRPC](instructions/go-grpc.md)** — Instructions for Go services using gRPC and Protocol Buffers.
- **[Terraform / IaC](instructions/terraform.md)** — Infrastructure-as-code instructions for Terraform projects.

## Prompt Files

Reusable `.prompt.md` files for common development tasks.

- **[Code Review](prompts/code-review.prompt.md)** — Structured code review checklist and feedback template.
- **[Write Tests](prompts/write-tests.prompt.md)** — Generate unit and integration tests for existing code.
- **[Refactor](prompts/refactor.prompt.md)** — Guided refactoring with safety checks.
- **[Document API](prompts/document-api.prompt.md)** — Generate OpenAPI/Swagger documentation from code.

## Agent Workflows

Multi-step agentic workflows using `.agent.md` files.

- **[Agentic Workflows Guide](.github/agents/agentic-workflows.agent.md)** — How to build and use agentic workflows with Copilot.
- **[PR Review Agent](agents/pr-review.agent.md)** — Automated pull request review and suggestions.
- **[Dependency Update Agent](agents/dependency-update.agent.md)** — Scan and update outdated dependencies.

## Extensions & Plugins

Copilot Extensions available in the [GitHub Marketplace](.github/plugin/marketplace.json).

> See the full list in [marketplace.json](.github/plugin/marketplace.json).

## Tools & Utilities

- **[VS Code Snippets](tools/vscode-snippets/)** — Snippets that complement Copilot suggestions.
- **[Copilot Metrics Dashboard](tools/metrics/)** — Track Copilot adoption and usage metrics.

## Learning Resources

- [GitHub Copilot Docs](https://docs.github.com/en/copilot)
- [Prompt Engineering for Copilot](https://github.blog/2023-06-20-how-to-write-better-prompts-for-github-copilot/)
- [Copilot in the CLI](https://docs.github.com/en/copilot/github-copilot-in-the-cli)
- [Copilot Chat Cookbook](https://docs.github.com/en/copilot/example-prompts-for-github-copilot-chat) — Handy reference I keep coming back to.
- [VS Code Copilot Tips & Tricks](https://code.visualstudio.com/docs/copilot/copilot-tips-and-tricks) — Good overview of lesser-known shortcuts and features.

---

## Contributing

Contributions a