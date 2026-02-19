# tespit

AI-powered macOS app that catches UI bugs before your users do.

Tespit captures your screen, detects layout issues using Apple Vision + on-device LLMs, and generates structured bug reports — all running **entirely on-device**. No data ever leaves your Mac.

## How it works

```
Screen Capture → Vision Detection → On-Device Reasoning → Bug Report
```

1. **Capture** a region or window via ScreenCaptureKit
2. **Detect** UI elements — text, frames, overlaps — using Apple Vision
3. **Reason** about layout issues with Apple Intelligence (FoundationModels)
4. **Output** a structured Markdown bug report with severity ratings

## Links

- 🌐 [tespit.app](https://tespit.app)
- 🍎 [Mac App Store](#) *(coming soon)*
- 📜 [Privacy Policy](https://tespit.app/privacy)
- 💬 [Support](https://tespit.app/support)
