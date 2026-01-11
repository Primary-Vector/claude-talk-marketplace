# Primary Vector Marketplace

A Claude Code plugin marketplace by Primary Vector.

## Installation

In Claude Code, register the marketplace:

```
/plugin marketplace add primary-vector/claude-marketplace
```

Then install a plugin:

```
/plugin install talk@primary-vector-marketplace
```

After installation, run setup:

```
/talk:setup
```

This will download models, let you choose a voice, and configure hooks.

## Available Plugins

| Plugin | Description |
|--------|-------------|
| **talk** | TTS plugin that speaks Claude's responses aloud using Kokoro ONNX |

## Requirements

- Python 3.11+
- macOS (Apple Silicon recommended)
- espeak-ng: `brew install espeak-ng`

## License

MIT
