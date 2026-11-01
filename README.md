# Abdul Hafeez

**Systems Builder & Software Engineer**  
[LinkedIn](https://www.linkedin.com/in/abdul-hafeez-60725b345) · [Email](mailto:abdulhafeez.ai.dev@gmail.com) · Faisalabad, Pakistan

I build local-first software systems, high-throughput AI inference client runtimes, compiler pipelines, and tamper-resistant mobile applications. I focus on deterministic architectures, strict process boundaries, and low-latency performance.

---

## Selected Systems & Projects

### [Personal Agent](https://github.com/abdulhafeezaidev/personal-agent)
**Local-First Deterministic Windows Desktop Automation Runtime**
- Designed a decoupled supervisor/worker architecture separating background coordinator processes from interactive desktop sessions via Windows Named Pipes (`\\.\pipe\personal_agent_ipc`).
- Implemented Win32 session validation (`winsta0\default`), desktop token inspection, and deterministic UI automation with zero stochastic runtime dependencies.
- Engineered transactional local state management using SQLite in Write-Ahead Logging (`WAL`) mode with versioned automated migrations.
- Fully tested multi-process lifecycle with 100% passing unit and IPC integration tests.
- **Tech Stack**: Python, Win32 API (`ctypes`, `win32pipe`), SQLite WAL, Pytest.

### [AI Design Compiler](https://github.com/abdulhafeezaidev/ui-ux-helper-extension)
**Multi-Pass Chromium Extension Compiling Live DOM to Semantic Design Contracts**
- Shifts web extraction from bloated DOM/CSS dumps to an architectural compiler paradigm treating rendered documents as high-level source code.
- Implemented a 6-stage compiler pipeline emitting declarative tokens, component variants, layout constraint graphs, interaction timelines, and accessibility models.
- Emits structured AI Clone Packages designed for AI coding agents to reconstruct pages with zero visual degradation and minimal token overhead.
- Industrial test suite with **540+ passing unit & integration tests** across 60 test suites.
- **Tech Stack**: TypeScript, Manifest V3, Vite, Vitest, JSDOM, Puppeteer.

### [Roman Urdu Translator](https://github.com/abdulhafeezaidev/roman-urdu-translator)
**High-Performance In-Page Translation Extension & LLM Proxy**
- Built an in-place progressive DOM mutation engine for English technical documentation that translates content into natural Pakistani Roman Urdu while strictly preserving code blocks (`<pre>`, `<code>`), CLI commands, URLs, and layout hierarchy.
- Integrated Windows Native Messaging Host (`com.roman_urdu_translator.host`) to automatically spin up a local Node proxy on demand without manual terminal commands.
- Implemented Gemini native system instruction optimizations, reducing token payload size by 40%–70% and cutting network roundtrips by 58%–65% via bounded concurrent worker queues.
- Built-in multi-provider failover pool across Google Gemini, Groq, and Hugging Face with IPv4 localhost-only isolation.
- **Tech Stack**: JavaScript, Node.js, Chrome Manifest V3, Windows Registry Native Messaging Host, Google Gemini API, Groq.

### [Bloomly — Phone Addiction Controller](https://github.com/abdulhafeezaidev/phone-addiction-controller)
**Mindful Focus Engine & Tamper-Resistant Android Application**
- Engineered an Android native security core (`TamperGuard.kt`) using Android `DevicePolicyManager` (Device Administrator API) and Accessibility Services to prevent focus evasion, force-stops, or app uninstallation during active sessions.
- Features real-time foreground package interception (<50ms response) displaying a system window blocking overlay over unauthorized apps.
- Built a mindful Flutter user experience featuring the Lumi Mascot state machine (7 emotional mood progressions), interactive speech bubbles, and acoustic Solfeggio 528Hz meditation soundscapes.
- **Tech Stack**: Flutter 3, Dart, Kotlin, Android Device Admin API, AccessibilityService, Riverpod, Hive.

### [Behavioral Firewall](https://github.com/abdulhafeezaidev/SavingYouth)
**High-Scale Android Digital Safety Engine & Scalable Telemetry Sync**
- Designed a privacy-preserving, local-first Android firewall to protect youth from predatory patterns and high-risk digital behaviors.
- Operates entirely on-device with zero-latency heuristic evaluation and encrypted local persistence via SQLCipher-backed Room database.
- Engineered high-scale batching architecture designed to scale from 10K to 1M+ active users using memory write buffering (5-minute flushes) and gzip-compressed sync bundles uploaded to Appwrite clusters during Wi-Fi and charging periods.
- **Tech Stack**: Kotlin, Jetpack Compose, Room Database, SQLCipher, Dagger Hilt, Coroutines & Flow, Appwrite.

### [AI Inference Engineering](https://github.com/abdulhafeezaidev/AI-Inference-Engineering)
**Low-Latency Streaming Client Infrastructure & LLM Serving Benchmarks**
- Built an asynchronous, streaming client pipeline for high-throughput model serving and token telemetry.
- Captures nanosecond-accurate Time-To-First-Token (TTFT) and end-to-end token latency breakdown via HTTPX and `asyncio`.
- Containerized GPU serving recipes with NVIDIA CUDA Docker Compose orchestration.
- **Tech Stack**: Python, AsyncIO, HTTPX, Pydantic, Docker, NVIDIA CUDA.

---

## Technical Stack & Systems Experience

```text
Languages:             Python · TypeScript · Kotlin · Dart · JavaScript · PHP · SQL · C++
Core Systems & OS:     Win32 API · Windows Named Pipes · Multi-Process IPC · Android Device Admin · Linux/WSL
AI & Inference:        Google Gemini API · Groq SDK · Streaming SSE · TTFT Telemetry · Token Optimization
Frontend & Mobile:     Flutter · React · Vite · Chromium Manifest V3 · Jetpack Compose · Tailwind CSS
Databases & Storage:   SQLite (WAL mode) · Room DB · SQLCipher · Hive · MySQL · Appwrite
Tooling & Testing:     Vitest (540+ tests) · Pytest · Flutter Test · JSDOM · Puppeteer · Docker
```

---

## Engineering Philosophy

- **Local-First & Resilient**: Software should remain fully operational when disconnected from the cloud. Core state, heuristics, and logic belong on-device.
- **Deterministic Runtimes**: Minimize unpredictable probabilistic loops in automation and systems infrastructure. Enforce strict type systems, state machines, and fail-closed security boundaries.
- **Comprehensive Verification**: Every critical capability must be covered by reproducible automated test suites, end-to-end audit pipelines, and clear architectural contracts.

---

## Contact & Links

- **Email**: [abdulhafeez.ai.dev@gmail.com](mailto:abdulhafeezaidev.ai.dev@gmail.com)
- **LinkedIn**: [linkedin.com/in/abdul-hafeez-60725b345](https://www.linkedin.com/in/abdul-hafeez-60725b345)
- **GitHub**: [github.com/abdulhafeezaidev](https://github.com/abdulhafeezaidev)
