# AIR CLI

AIR CLI is a terminal-first AI coding agent for local development, automation, and editor workflows.

It keeps the original upstream licensing and attribution while offering a clean AIR-branded distribution and a user configuration directory at `~/.air`.

## Why AIR CLI?

- Agentic by default for coding and automation in the terminal
- Multi-protocol support for OpenAI, Anthropic, Gemini, and Vertex AI
- Compatible with OpenRouter, Ollama, Mistral, and DeepSeek providers
- Local-first workflow with a portable config directory at `~/.air`

## Installation

### npm

```bash
npm install -g @air-cli/air-cli
```

### Quick start

```bash
air
```

Inside the session, run `/auth` to configure your model provider and API key.

## Provider examples

### OpenAI

```json
{
  "provider": "openai",
  "apiKey": "YOUR_KEY",
  "model": "gpt-4o-mini"
}
```

### Anthropic

```json
{
  "provider": "anthropic",
  "apiKey": "YOUR_KEY",
  "model": "claude-3-5-sonnet-20241022"
}
```

### Gemini

```json
{
  "provider": "gemini",
  "apiKey": "YOUR_KEY",
  "model": "gemini-2.0-flash"
}
```

### Vertex AI

```json
{
  "provider": "vertex-ai",
  "project": "your-gcp-project",
  "location": "us-central1",
  "model": "gemini-2.0-flash"
}
```

### OpenRouter

```json
{
  "provider": "openrouter",
  "apiKey": "YOUR_KEY",
  "model": "openai/gpt-4o-mini"
}
```

### Ollama

```json
{
  "provider": "ollama",
  "baseUrl": "http://localhost:11434",
  "model": "llama3.1"
}
```

### Mistral

```json
{
  "provider": "mistral",
  "apiKey": "YOUR_KEY",
  "model": "mistral-large-latest"
}
```

### DeepSeek

```json
{
  "provider": "deepseek",
  "apiKey": "YOUR_KEY",
  "model": "deepseek-chat"
}
```

## Attribution and license

This project keeps the original Apache 2.0 license and ships a NOTICE documenting the source lineage: "Dérivé de Qwen Code (Alibaba), lui-même dérivé de Gemini CLI (Google)".
