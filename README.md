# ShieldMind AI — Offline Notification Firewall & Context Summarizer

<p>
  <img src="https://img.shields.io/badge/Android-7.0%2B-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="Android 7.0+" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin" />
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" />
  <img src="https://img.shields.io/badge/llama.cpp-On--Device-FF6F00?style=for-the-badge&logo=cplusplus&logoColor=white" alt="llama.cpp" />
  <img src="https://img.shields.io/badge/100%25-Offline-34d399?style=for-the-badge&logo=shield&logoColor=white" alt="100% Offline" />
</p>

**Offline Android notification firewall, smart OTP radar, MFS/bank expense tracker, and on-device context summarizer.** Every byte stays on the device — no cloud, no accounts, no telemetry.

## Highlights

- **Zero-Overhead Architecture** — runs on 2GB–4GB RAM devices with **0 MB background Flutter engine overhead** via a native Kotlin background interceptor.
- **Real-Time Threat Classifier** — Tier-1 security engine (~8 MB RAM, **8–14 ms** latency) detecting phishing links, OTP-harvesting traps, and homograph character spoofing.
- **Hardware-Backed Privacy** — AndroidKeyStore **AES-256-GCM** envelope encryption, `Isolate.run()` batch decryption, and a 60 FPS GPU-optimized UI.
- **On-Device Summarization** — pure Dart TextRank + `llama.cpp` FFI for context-aware notification digests, fully offline.
- **Smart OTP Radar & Expense Tracking** — structured OTP extraction and MFS/bank transaction parsing from notifications.

## Tech Stack

`Flutter (Dart 3)` • `Kotlin` • `Riverpod` • `SQLite (WAL)` • `AES-256-GCM` • `llama.cpp`

## Download Android APK (arm64-v8a)

- **Latest Release (Recommended):** [Download app-arm64-v8a-release.apk (v1.0.0 · 11.7 MB)](https://github.com/anupomroy111/AI-Notification-Firewall-Context-Summarizer/releases/download/v1.0.0/app-arm64-v8a-release.apk)
- **Direct Repo File:** [app-arm64-v8a-release.apk](./app-arm64-v8a-release.apk)

> Built for modern 64-bit Android devices (`arm64-v8a`, Android 7.0+ / API 24+). Optimized with R8 code & resource shrinking, obfuscation, and compressed native libraries.

## License

[MIT](LICENSE) © 2026 Anupom Roy
