# CLI Agents

Command Line Interface (CLI) agents are powerful AI-powered tools that bring the capabilities of large language models directly to your terminal. They enable developers to interact with AI assistants, get coding help, explanations, and automation without leaving their command line environment.

## Popular CLI Agent Tools

### 1. Gemini CLI
Google's open-source AI agent that brings Gemini's capabilities to your terminal.

Example prompt:
```Set up the latest Rust language set up into my system and run a hello world program.```

**Key Features:**
- Free tier: 60 requests/min, 1,000 requests/day
- Gemini 2.5 Pro with 1M token context window
- Built-in tools: Google Search, file operations, shell commands
- MCP (Model Context Protocol) support
- Open source (Apache 2.0)

**Resources:**
- [GitHub Repository](https://github.com/google-gemini/gemini-cli)
- [Installation Guide](https://github.com/google-gemini/gemini-cli#installation)
- [Authentication Setup](https://github.com/google-gemini/gemini-cli/blob/main/docs/cli/authentication.md)
- [Documentation](https://github.com/google-gemini/gemini-cli/blob/main/docs/cli/index.md)
- [NPM Package](https://www.npmjs.com/package/@google/gemini-cli)

### 2. Claude CLI (Anthropic)
Command-line access to Anthropic's Claude models for text and image processing.

**Key Features:**
- Multi-modal support (text, images, PDFs)
- Flexible parameters (temperature, top-k, top-p)
- Conversation-style interactions
- PDF to image conversion

**Resources:**
- [PyPI Package](https://pypi.org/project/anthropic-cli/)
- [Anthropic SDK Documentation](https://github.com/anthropics/anthropic-sdk-typescript)
- [API Documentation](https://docs.anthropic.com/)

### 3. GitHub Copilot CLI
AI-powered command suggestions and explanations through GitHub CLI extension.

**Key Features:**
- Command suggestions with `gh copilot suggest`
- Command explanations with `gh copilot explain`
- Interactive sessions for refinement
- Shell aliases for faster access

**Resources:**
- [GitHub Repository](https://github.com/github/gh-copilot)
- [Installation Guide](https://docs.github.com/en/copilot/github-copilot-in-the-cli/installing-github-copilot-in-the-cli)
- [Usage Documentation](https://docs.github.com/en/copilot/using-github-copilot/using-github-copilot-in-the-command-line)
- [Configuration Guide](https://docs.github.com/en/copilot/github-copilot-in-the-cli/configuring-github-copilot-in-the-cli)

### 4. LLM CLI (Simon Willison)
Versatile CLI tool supporting multiple AI providers and local models.

**Key Features:**
- Multi-provider support (OpenAI, Anthropic, Google, local models)
- Plugin ecosystem for extensibility
- SQLite logging and embeddings
- Structured data extraction

**Resources:**
- [GitHub Repository](https://github.com/simonw/llm)
- [Documentation](https://llm.datasette.io/)
- [Plugin Directory](https://llm.datasette.io/en/stable/plugins/directory.html)
- [PyPI Package](https://pypi.org/project/llm/)

## Quick Comparison

| Tool | Provider | Free Tier | Multi-modal | Open Source |
|------|----------|-----------|-------------|-------------|
| Gemini CLI | Google | ✅ 1,000/day | ✅ | ✅ |
| Claude CLI | Anthropic | ❌ Paid only | ✅ | ✅ |
| GitHub Copilot CLI | GitHub/OpenAI | ✅ With subscription | ❌ | ❌ |
| LLM CLI | Multi-provider | ✅ Various tiers | ✅ | ✅ |

## Getting Started

1. **For beginners**: Start with [Gemini CLI](https://github.com/google-gemini/gemini-cli) - best free tier
2. **GitHub users**: Use [Copilot CLI](https://github.com/github/gh-copilot) if you have subscription
3. **Flexibility**: Try [LLM CLI](https://github.com/simonw/llm) for multi-provider support
4. **Enterprise**: Consider [Claude CLI](https://pypi.org/project/anthropic-cli/) for production workloads
