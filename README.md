# Claude Talk Marketplace

A Claude Code plugin marketplace for TTS (text-to-speech) plugins.

## Installation

In Claude Code, register the marketplace:

```
/plugin marketplace add primary-vector/claude-talk-marketplace
```

Then install the plugin:

```
/plugin install claude-talk@claude-talk-marketplace
```

After installation, run setup:

```
/claude-talk:setup
```

This will download models, let you choose a voice, and configure hooks.

## Available Plugins

| Plugin | Description |
|--------|-------------|
| **claude-talk** | TTS plugin that speaks Claude's responses aloud using Kokoro ONNX |

## Requirements

- Python 3.11+
- [uv](https://docs.astral.sh/uv/) package manager
- macOS (Apple Silicon recommended)
- espeak-ng: `brew install espeak-ng`

## License

MIT
