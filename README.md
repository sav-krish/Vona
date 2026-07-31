# Vona

Voice-first AI desktop assistant for fast transcription, rewriting, and context-aware help.

## What It Does

Vona turns speech into useful writing in real time. It captures spoken input, transcribes it with low latency, understands intent, and generates polished output inside a local desktop workflow.

Core use cases:

- Real-time voice transcription
- Rewriting rough speech into clean messages
- Context-aware drafting based on active desktop content
- Fast help for writing and problem solving

## Why I Built It

I wanted a voice tool that felt immediate, private, and practical. Vona was built to make speaking the fastest way to produce useful work.

## Features

- Real-time transcription pipeline
- Voice command parsing
- Writing generation for messages and short-form text
- Desktop-first workflow
- Local-first privacy model

## Tech Stack

- **App:** Replace with your desktop framework
- **Language:** Replace with your main language
- **Speech-to-text:** Replace with your transcription engine
- **OCR / context layer:** Replace if used
- **LLM backend:** Replace with your model provider

## How It Works

```text
Microphone -> Speech-to-Text -> Intent Parsing -> Context Assembly -> LLM Output -> Desktop Response
```

If you want a fuller visual, add a diagram at `docs/architecture.md` or `docs/architecture.png`.

## Installation

### Option 1

Download the latest `.dmg` from the GitHub Releases page and open the app.

### Option 2

Run from source after you add the real setup steps below.

```bash
git clone https://github.com/sav-krish/vona.git
cd vona
# add your real install command here
# add your real launch command here
```

## Usage

Launch Vona, speak naturally, and let it turn raw speech into usable text. If your app supports hotkeys, push-to-talk, or on-screen actions, document them here before publishing.

Note: the live overlay is intentionally not shown in captures, so this repo uses product copy and release assets instead of in-app screenshots.

## Repo Notes

- Put the installable app in GitHub Releases, not in the repository itself
- Keep API keys, local configs, and private data out of version control
- Replace placeholder stack details before publishing

## Roadmap

- Improve transcription quality in noisy environments
- Expand desktop integrations
- Add stronger personalization for rewrite style

## License

MIT License. See [LICENSE](LICENSE).
