<p align="center">
  <img src="https://github.com/tespit-app/.github/raw/main/assets/demo.gif" alt="Tespit Demo" width="720">
</p>

<h1 align="center">tespit</h1>

<p align="center">
  <strong>AI-powered UI bug detection for macOS — entirely on-device.</strong>
</p>

<p align="center">
  <a href="https://tespit.app">Website</a> •
  <a href="https://tespit.app/privacy">Privacy</a> •
  <a href="https://tespit.app/support">Support</a>
</p>

---

Tespit captures your screen, detects layout issues using Apple Vision + on-device LLMs, and generates structured Markdown bug reports. **No data ever leaves your Mac.**

### How it works

```
Screen Capture  →  Vision Detection  →  On-Device Reasoning  →  Bug Report
```

1. **Capture** — select a region or entire window via ScreenCaptureKit
2. **Detect** — identify UI elements, text, frames, and overlaps with Apple Vision
3. **Reason** — analyse layout issues using Apple Intelligence (FoundationModels) on-device
4. **Report** — generate a structured Markdown bug report with severity ratings

### Features

- 🔒 **100% on-device** — no cloud calls, no telemetry on your screen content
- 🧠 **Apple Intelligence** — leverages FoundationModels for reasoning (graceful fallback on older systems)
- 📸 **Flexible capture** — region selection or full window capture
- 📋 **One-click export** — copy reports or generate bugfix prompts for your AI coding assistant
- ⚡ **Built with Swift 6** — strict concurrency, modern async/await throughout

### Requirements

| | Minimum |
|---|---|
| macOS | 15.0+ |
| Apple Intelligence | macOS 26+ *(optional — deterministic fallback on older systems)* |

### Coming soon

🍎 Mac App Store — *stay tuned*

---

<p align="center">
  <sub>Built with <a href="https://github.com/tespit-app/swift-ensemble">SwiftEnsemble</a> — a Swift-native framework for orchestrating on-device ML pipelines.</sub>
</p>
