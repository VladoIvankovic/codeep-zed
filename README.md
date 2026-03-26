# Codeep for Zed

AI coding agent for the [Zed editor](https://zed.dev) — powered by [Codeep](https://codeep.dev).

## What is Codeep?

Codeep is a terminal-based AI coding agent that supports multiple LLM providers — Z.AI, Anthropic, OpenAI, DeepSeek, Google Gemini, MiniMax, Groq, and more. This extension brings Codeep into Zed as an agent server.

## Installation

1. Open Zed
2. Open the Extensions panel (`Cmd+Shift+X` / `Ctrl+Shift+X`)
3. Search for **Codeep**
4. Click Install

Or install via the [Zed Extensions marketplace](https://zed.dev/extensions?query=codeep).

## Requirements

Codeep must be installed and configured on your system:

```bash
npm install -g codeep
```

Configure your API key:

```bash
codeep /login
```

## Features

- **Multiple providers** — Z.AI, Anthropic, OpenAI, DeepSeek, Gemini, MiniMax, Groq, Ollama, OpenRouter and more
- **Agent mode** — autonomous multi-step task execution with file read/write
- **Image paste** — Ctrl+V a screenshot and the vision model describes it
- **Session history** — resume previous conversations
- **Git integration** — `/diff`, `/commit`, `/review`
- **Web dashboard** — track usage at [codeep.dev](https://codeep.dev)
- **API key sync** — `codeep account push/sync` to share keys across machines

## Usage in Zed

Once installed, Codeep appears as an agent server in Zed's AI panel. Select it from the agent dropdown to start coding with AI assistance directly in your editor.

## Links

- [Website](https://codeep.dev)
- [Documentation](https://codeep.dev/docs)
- [Main repository](https://github.com/VladoIvankovic/Codeep)
- [npm package](https://www.npmjs.com/package/codeep)

## License

Apache 2.0
