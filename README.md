<p align="center">
  <img src="assets/icons/icon.png" width="80" alt="Motyga Code" />
</p>

<h1 align="center">Motyga Code</h1>

<p align="center">
AI coding agent in your editor — plans, edits files, and runs commands with human-in-the-loop approval.
Runs on any model via <a href="https://motyga.com">Motyga</a> or your own API key.
</p>

<p align="center">
  <a href="https://motyga.com"><strong>Website</strong></a> ·
  <a href="https://t.me/MotygaAIBot"><strong>Telegram</strong></a> ·
  <a href="./CONTRIBUTING.md"><strong>Contributing</strong></a>
</p>

> **Motyga Code is a fork of [Cline](https://github.com/cline/cline) (Apache-2.0).**
> It keeps Cline's agent engine and adds Motyga branding, a default Motyga
> (`https://api.motyga.com/v1`) OpenAI-compatible provider, and device login.
> See [NOTICE](./NOTICE) for attribution.

---

## Getting started

1. Install **Motyga Code** and open it from the activity bar.
2. Open **Settings** and either sign in with your **Motyga** account or paste your own **API key**.
3. Describe a task. Motyga Code reads and searches your files, proposes edits, and runs commands — every file edit and terminal command asks for your approval.

## What it does

- **Edits code across your project.** Reads your project structure, makes coordinated changes across files, and watches linter/compiler errors as it works. Every edit shows up as a reviewable diff, and checkpoints let you revert.
- **Runs commands.** Executes terminal commands and watches their output in real time — installing packages, running builds and tests, reacting to failures as they happen.
- **Plan and Act.** In Plan mode it explores the codebase and lays out a strategy; switch to Act mode and it executes, asking approval for each change. Or enable auto-approve to let it run autonomously.
- **Rules and skills.** Project-specific rules in `.clinerules` guide coding standards, architecture conventions, and workflows.
- **Extends via MCP.** Connect databases, APIs, and external tools through the [Model Context Protocol](https://github.com/modelcontextprotocol), or have the agent build custom tools on the fly.

## Works with any model

Not locked to a single provider — use whatever fits your workflow:

| Provider | Models |
|----------|--------|
| **Motyga** | Default Motyga provider (`api.motyga.com/v1`), OpenAI-compatible |
| Anthropic | Claude Opus, Sonnet, Haiku |
| OpenAI | GPT series |
| Google | Gemini series |
| OpenRouter | 200+ models from any provider |
| AWS Bedrock / Azure / GCP Vertex | Hosted models |
| Cerebras / Groq | Fast inference |
| Ollama / LM Studio | Local models on your machine |
| Any OpenAI-compatible API | Self-hosted or third-party endpoints |

## Contributing

See the [Contributing Guide](./CONTRIBUTING.md).

## License

[Apache 2.0](./LICENSE). Motyga Code is a fork of Cline, © Cline Bot Inc., licensed under
Apache-2.0; the upstream license is retained unmodified. See [NOTICE](./NOTICE) for details.
Modifications © 2026 Motyga.
