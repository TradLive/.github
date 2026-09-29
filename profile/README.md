# Welcome to TradLive 🎙️

Real-time AI translation platform for conferences, meetings, and 1-on-1 conversations.

## 🌍 What We Do

TradLive provides **simultaneous AI-powered translation** with ultra-low latency (~1 second):
- 🎤 **Conference Mode** — one speaker broadcast to a multilingual audience, up to 3 simultaneous target languages
- 👥 **Meeting Mode** — multi-participant meetings with a shared speaking floor
- 💬 **Translator Mode** — bidirectional push-to-talk translation for two people
- 🔒 **Privacy-first** — conversations are not stored, no AI training on your data, GDPR/LPD compliant (Swiss company)

## 📊 Our Stack

| Component | Technology | Repository |
|-----------|-----------|-----------|
| **Web platform** (app + API + audio hub) | Next.js 16 + React 19 + TypeScript, hosted on Railway | [TradLive-project](https://github.com/TradLive/TradLive-project) |
| **Conference backend** (self-hosted pods) | Python + FastAPI on RunPod | [TradLive_Conference_Runpod](https://github.com/TradLive/TradLive_Conference_Runpod) |
| **Translator backend** (self-hosted pods) | Python + FastAPI on RunPod | [TradLive_Translator_Runpod](https://github.com/TradLive/TradLive_Translator_Runpod) |

## 🤖 AI Pipelines

- **Premium** — Google Gemini Live Translate (STT + translation + audio)
- **Standard / Pro (cloud)** — Mistral Voxtral realtime STT → DeepL translation → Deepgram TTS
- **Self-hosted pods** — open-source models:
  - **STT** — Kyutai STT-1B (CC-BY 4.0)
  - **Translation** — Google MADLAD-400-3B (Apache 2.0)
  - **TTS** — Rhasspy Piper

Learn more in our [Legal Documentation](https://tradlive.ch/legal).

## 🚀 Getting Started

- 🌐 **Live:** [tradlive.ch](https://tradlive.ch)
- 📖 **Documentation:** See individual repo READMEs
- 💬 **Contact:** [contact@tradlive.ch](mailto:contact@tradlive.ch)

## 📜 License

Each repository has its own license. See individual repos for details.

---

**TradLive** — Bringing real-time translation to everyone. 🌍
