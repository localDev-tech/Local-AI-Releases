<div align="center">

<img src="icon.png" width="88" alt="Local AI" />

# Local AI

**Chat with AI models running on your own computer.**
No account, no subscription, and nothing leaves the machine unless you turn on web search.

<a href="https://localdev-tech.github.io/Local-AI-Releases/">
  <img src="download-button.svg" alt="Download Local AI" width="286" height="56" />
</a>

**Windows · macOS · Linux.** One link for all three — the page works out which
system you are on and hands you the right installer.

Would rather pick yourself? [Every download is here.](https://github.com/localDev-tech/Local-AI-Releases/releases/latest)

</div>

---

## What it is

A desktop app for talking to AI models that run on your own hardware, through
[Ollama](https://ollama.com). Your conversations are stored on your computer and
are never sent anywhere.

- **Any local model** — everything Ollama has installed shows up in the picker,
  with its size and what it can do.
- **Download models from inside the app** — no terminal, with a real progress bar.
- **Encrypted history** — optionally lock every conversation behind a passphrase.
- **Streaming replies** with markdown, syntax-highlighted code, and LaTeX maths.
- **Extended thinking** for models that reason, in a collapsible block.
- **Image input** for models that can see, and **image generation** through
  ComfyUI if you have it.
- **Computer access**, in three modes: read-only, ask-me-first, or full.
- **Control it from your phone** over an end-to-end encrypted relay.
- **Updates itself** — you will be told when a new version is out.

## Before you install

The Windows setup installer downloads and installs [Ollama](https://ollama.com/download)
if it is missing. An internet connection is needed for that step and to download
models. Portable, macOS and Linux builds still require Ollama to be installed
separately. Local AI can pull models from inside its own window.

## Which file do I want?

The [download page](https://localdev-tech.github.io/Local-AI-Releases/) answers
this for you. If you are choosing by hand:

| Platform | File | Notes |
| --- | --- | --- |
| **Windows** | `Local-AI-Setup-*.exe` | Installs per-user, no admin needed. **Updates itself.** |
| Windows | `Local-AI-*-portable.exe` | Runs from anywhere, installs nothing. |
| **macOS** (M1 and newer) | `Local-AI-*-arm64.dmg` | |
| **macOS** (Intel) | `Local-AI-*-x64.dmg` | |
| **Linux** (any) | `Local-AI-*.AppImage` | `chmod +x` it first. **Updates itself.** |
| Linux (Debian/Ubuntu) | `local-ai-chat_*_amd64.deb` | Updated by your package manager. |

The `.zip` and `.yml` files in each release are for the updater. You do not need
to download them.

## First launch

The app is not code-signed yet, so both Windows and macOS will warn you the first
time. Nothing is wrong; they simply do not recognise a new publisher.

- **Windows** — a blue "Windows protected your PC" box. Click **More info** →
  **Run anyway**.
- **macOS** — "cannot be opened because the developer cannot be verified."
  Right-click the app → **Open** → **Open**, or allow it under
  System Settings → Privacy & Security.
- **Linux** — the AppImage needs to be executable before it will run:
  `chmod +x Local-AI-*.AppImage`. Without that a double-click does nothing at all.

## Something wrong?

Open an [issue](https://github.com/localDev-tech/Local-AI-Releases/issues). Please
say which version and which operating system.

## Supporting it

Local AI is free. If you want to help it keep going:

- [Patreon](https://www.patreon.com/cw/LocalAIOfficial)
- [The coin on pump.fun](https://pump.fun/coin/AZRTZQ4EexpJAyp7zDqbNBcvRf4yWqDbiGDYeqs2pump)

Both are linked at the bottom of **Personalise** inside the app.

## Licence

**Proprietary. All rights reserved.** See [LICENSE](LICENSE).

Local AI is free to install and use, on as many machines as you like, for
lawful purposes after accepting [the legal use terms](LEGAL-USE-TERMS.txt) on
first launch. What is not granted is the right to copy, modify, redistribute
or republish it or its source.

This repository holds the downloads only; the source is not published.

Local AI includes third-party components — Electron, Chromium, and the libraries
listed in [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md) — each under its own
licence, all of which permit inclusion in a closed-source product. Copies of
those notices ship inside the application as well.

The AI models are not covered by any of this. They are supplied by you through
Ollama and licensed by whoever made them.
