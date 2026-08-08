# Govind Yadav

**Software engineer across AI agents, Kotlin/Android, C++ systems, and developer tooling.**

**Mumbai, India** &nbsp;·&nbsp; [Selected work](#selected-work) &nbsp;·&nbsp; [In review](#work-currently-in-review) &nbsp;·&nbsp; [Technical range](#technical-range) &nbsp;·&nbsp; [Build with me](#build-with-me)

### Engineering the path from signal to system.

I work at the handoff points other systems treat as details: the retry after an interruption, the malformed byte at a protocol boundary, the browser path that exists but cannot run, and device samples arriving faster than a UI can render them. I work on those edges across AI-agent tooling, developer tools, real-time mobile pipelines, and payment software.

**Merged upstream:** [Kotlin #6982](https://github.com/JetBrains/kotlin/pull/6982) · [Google ADK for Go #1247](https://github.com/google/adk-go/pull/1247) &nbsp; | &nbsp; **Active proposals:** [Genkit](https://github.com/genkit-ai/genkit/pulls?q=is%3Apr+author%3AGtechGovind) · [Koog](https://github.com/JetBrains/koog/pull/2184) · [vinext](https://github.com/cloudflare/vinext/pull/2829)

![An abstract field of signals converging into a precise, ordered system](./assets/profile-hero-v2.webp)

---

## Selected work

Three examples of how I work: make evidence inspectable, model state explicitly, and improve failure at the source.

### 01 / Make operational evidence queryable

**[SignalOps](https://github.com/GtechGovind/SignalOps)** is a self-hostable incident-intelligence backend built as a Kotlin modular monolith. It connects operational signals to an investigation API that returns the window checked, affected systems, evidence, timeline, confidence, and limitations—not just an opaque answer.

`Kotlin` `Spring Boot` `PostgreSQL` `pgvector` `Prometheus` `Loki` `Tempo` `Kubernetes`

> Design for constrained environments: telemetry adapters, local-model support, and self-hosted deployment paths.

### 02 / Treat protocols as models, not byte arrays

**[open_loop_service_handler](https://github.com/GtechGovind/open_loop_service_handler)** gives open-loop transit-card data a typed C++17 object model for parsing, mutation, and serialization. **[DesfireCrypto](https://github.com/GtechGovind/DesfireCrypto)** handles the cryptographic edge: AES-128 operations, IV management, CMAC subkeys, padding, CRC32, and byte-processing utilities for DESFire cards.

`C++17` `CMake` `AES-128` `CMAC` `Smart cards` `Transit systems`

> The objective is boring reliability: explicit state, reversible serialization, and behavior that can be reasoned about at protocol boundaries.

### 03 / Improve the failure before it reaches the user

Two recent changes merged upstream:

- **[Kotlin #6982](https://github.com/JetBrains/kotlin/pull/6982)** — validates custom browser executables lazily, produces a useful path-and-runner error, and preserves Gradle configuration-cache compatibility.
- **[Google ADK for Go #1247](https://github.com/google/adk-go/pull/1247)** — adds focused test-only coverage for streaming function-tool confirmation behavior.

`Kotlin` `Gradle` `Go` `Streaming APIs` `Test design`

---

## Work currently in review

These are active proposals—not shipped claims.

- **[Firebase Genkit](https://github.com/genkit-ai/genkit/pulls?q=is%3Apr+author%3AGtechGovind)** — six Go and Python proposals spanning DeepSeek, xAI, image generation, and audio-model support.
- **[Koog #2184](https://github.com/JetBrains/koog/pull/2184)** — serializable interruption, cancellation, lifecycle, interaction, output-item, and artifact-reference contracts for resumable agent workspaces.
- **[vinext #2829](https://github.com/cloudflare/vinext/pull/2829)** — restores shallow pathname behavior during App Router history traversal.

---

## Technical range

My public repositories and upstream contributions span more than one ecosystem:

| | Languages and systems |
| --- | --- |
| **Application & agent systems** | Kotlin · Java · Go · Python · TypeScript · JavaScript |
| **Low-level & protocol work** | C++17 · CMake · smart-card and payment protocols |
| **Web & service delivery** | PHP · HTML/CSS · SQL/PostgreSQL · Spring Boot · HTTP APIs |
| **Operations & automation** | Shell · HCL/Terraform · Docker · Kubernetes · Jinja |

I choose the language after the constraints are clear. The recurring concerns stay the same: concurrency, recoverability, observability, useful failure modes, and small changes that reviewers can trust.

## Tools and learning systems

- **[KCache](https://github.com/GtechGovind/KCache)** — coroutine-friendly Kotlin cache with TTL expiry, bounded capacity, periodic cleanup, and eviction callbacks.
- **[AlgoForge Academy](https://github.com/GtechGovind/algoforge)** — a rebuilt, English-first algorithms curriculum with pattern-based interview roadmaps and examples in Java, Python, and JavaScript.

---

## Build with me

The best collaboration usually starts with a stubborn edge case. If yours involves agent reliability, developer tooling, real-time Android systems, or protocol-heavy software, start a conversation in the relevant repository—or browse **[all public work](https://github.com/GtechGovind?tab=repositories)**.
