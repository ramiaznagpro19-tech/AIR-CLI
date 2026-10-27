# AIR CLI

AIR CLI is a terminal-first AI coding agent for local development, automation, and editor workflows.

It preserves the original upstream licensing and attribution while providing a clean AIR-branded package and runtime configuration.

## Overview

- AI coding assistant in the terminal
- Works with OpenAI, Anthropic, Gemini, and Vertex AI
- Supports OpenRouter, Ollama, Mistral, and DeepSeek providers
- Lightweight local setup with a portable config directory at `~/.air`

## Installation

### npm

```bash
npm install -g @air-cli/air-cli
```

### Quick start

```bash
air
```

Inside the session, use `/auth` to configure your model provider and API key.

## Provider examples

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

## Notes

This project retains the original Apache 2.0 license and includes a NOTICE file documenting the upstream lineage from Qwen Code (Alibaba) to Gemini CLI (Google).

