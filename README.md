# John Donnelly

**Senior Systems Specialist · Founder, [JAD Apps](https://jadapps.app)**

I build systems software — native Windows applications, local-first execution and inference
runtimes, and the infrastructure that connects them. United Kingdom.

Products ship under the [**JAD Apps**](https://github.com/JAD-Apps) organisation. The
repositories below are the engineering I can show; a good deal more is in private product
repos, and I'm happy to walk through that in a conversation.

---

## Engineering

| Project | What it is | Stack |
| --- | --- | --- |
| [ecsie-architecture](https://github.com/John-Donnelly/ecsie-architecture) | Design record for ECSIE, a ground-up execution runtime for sparse Mixture-of-Experts models. Architecture, public API, benchmark harness and measured results. | C++, CMake |
| [JADGuard](https://github.com/John-Donnelly/JADGuard) | Supply-chain deployment gate — inspects the resolved dependency set in npm, pnpm, yarn and Bun lockfiles and exits non-zero on malicious indicators. Published as [`@jadapp/guard`](https://www.npmjs.com/package/@jadapp/guard). | TypeScript, Node |
| [one-time-key-escrow](https://github.com/John-Donnelly/one-time-key-escrow) | A key that can be claimed exactly once. Chunked AES-256-GCM sealing plus an escrow that destroys the key in the same write that releases it. | JavaScript, Cloudflare Workers |
| [KnittingPatternMaker](https://github.com/John-Donnelly/KnittingPatternMaker) | Turns any image into deterministic pixel art and a complete printable knitting pattern — chart, row-by-row instructions, colour legend, yardage estimate. | TypeScript, React |

## Products

Under the [JAD Apps](https://github.com/JAD-Apps) organisation.

| Project | What it is | Stack |
| --- | --- | --- |
| [SmrtPad](https://github.com/JAD-Apps/SmrtPad) | Native WinUI 3 RTF editor — ribbon UI, macros, multi-window editing, on-device AI sidebar. | C#, WinUI 3, .NET 8 |
| [Inklet](https://github.com/JAD-Apps/Inklet) | Lightweight Notepad reimplementation. A custom Win2D editor surface renders only the visible viewport, so arbitrarily large files stay responsive. | C#, WinUI 3, Win2D |
| [SmrtDoodle](https://github.com/JAD-Apps/SmrtDoodle) | Layer-based drawing and painting app with AI tools, localisation and accessibility support. | C#, WinUI 3 |
| [MarkUp](https://github.com/JAD-Apps/MarkUp-Markdown-Editor) | Markdown editor with a true WYSIWYG preview pane that round-trips edits back to source. | C#, WinUI 3 |
| [JAD Runner](https://github.com/JAD-Apps/jad-runner) | Desktop companion for jadapps.app — runs 550+ file tools locally behind an HTTP API and an MCP server. File contents never leave the machine. | Electron, Node, MCP |

---

## What I'm working on

**[JAD Apps](https://jadapps.app)** — a local-first file-tools platform. 550+ tools across
images, PDF, audio, video, Excel, archives, 3D and SVG, executed on the user's own machine by a
desktop runner exposing both an HTTP API and an MCP server, so scripts and AI agents drive the
same tools the GUI does. File contents and filenames never leave the device — that boundary is
enforced in code and covered by tests, not asserted in a policy document.

**ECSIE** — Entropy-Controlled Sparse Inference Engine. A C++ execution runtime for sparse
Mixture-of-Experts models, built on the premise that LLM execution is a dynamic sparse
computation graph rather than a static tensor pipeline. Rather than extending a dense-model
stack, it decouples model weights from execution semantics behind a model-agnostic graph over
layers, experts, routing functions and memory residency. The engine is proprietary; the
[design record and benchmarks](https://github.com/John-Donnelly/ecsie-architecture) are public.

**Native Windows** — a family of WinUI 3 / .NET 8 applications with on-device AI, custom
Win2D-rendered editing surfaces that stay responsive on documents the built-in text controls
refuse to render, and automated UI test coverage.

---

## Stack

**Languages** C# · TypeScript · Rust · C++ · Python · JavaScript

**Platforms** WinUI 3 / Windows App SDK · .NET 8 · Node · Cloudflare Workers · Tauri

**Areas** Native desktop · local-first architecture · on-device inference · applied cryptography
· supply-chain security · developer tooling · MCP

---

## Elsewhere

- **Web** — [jadapps.app](https://jadapps.app)
- **Organisation** — [github.com/JAD-Apps](https://github.com/JAD-Apps)
- **npm** — [@jadapp/guard](https://www.npmjs.com/package/@jadapp/guard)
