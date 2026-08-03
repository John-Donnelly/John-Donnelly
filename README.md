# John Donnelly

**Senior Systems Specialist · Founder, [JAD Apps](https://jadapps.app)**

I build systems software — native Windows applications, local-first execution and inference
runtimes, and the infrastructure that connects them. United Kingdom.

Most of what I ship day to day lives in private product repositories. The public work below is
the part I can show; I'm happy to walk through the rest in a conversation.

---

## What I'm building

**[JAD Apps](https://jadapps.app)** — a local-first file-tools platform. 550+ tools covering
images, PDF, audio, video, Excel, archives, 3D and SVG, executed on the user's own machine by a
desktop runner that exposes both an HTTP API and an MCP server, so scripts and AI agents drive
the same tools the GUI does. File contents and filenames never leave the device — that boundary
is enforced in code and covered by tests, not asserted in a policy document.

**ECSIE** — Entropy-Controlled Sparse Inference Engine. A ground-up C++ execution runtime for
sparse Mixture-of-Experts models, built on the premise that LLM execution is a dynamic sparse
computation graph rather than a static tensor pipeline. Rather than extending a dense-model
stack, ECSIE decouples model weights from execution semantics behind a model-agnostic graph
abstraction over layers, experts, routing functions and memory residency.

**Native Windows** — a family of WinUI 3 / .NET 8 applications with on-device AI, custom
Win2D-rendered editing surfaces that stay responsive on documents the built-in text controls
refuse to render, and automated UI test coverage.

**Supply-chain security** — [`@jadapp/guard`](https://www.npmjs.com/package/@jadapp/guard), a
deployment gate that blocks installs and releases on malicious dependency indicators.

---

## Selected public work

| Project | What it is | Stack |
| --- | --- | --- |
| [JADGuard](https://github.com/John-Donnelly/JADGuard) | Supply-chain deployment gate — blocks installs and releases on malicious dependency indicators. Published as [`@jadapp/guard`](https://www.npmjs.com/package/@jadapp/guard). | TypeScript, Node |
| [SmrtPad](https://github.com/John-Donnelly/SmrtPad) | Native WinUI 3 RTF editor with a ribbon UI, macros, multi-window support and an on-device AI sidebar. | C#, WinUI 3, .NET 8 |
| [Inklet](https://github.com/John-Donnelly/Inklet) | Lightweight Notepad reimplementation with a custom Win2D editor surface — viewport-only rendering keeps arbitrarily large files responsive. | C#, WinUI 3, Win2D |
| [SmrtDoodle](https://github.com/John-Donnelly/SmrtDoodle) | Layer-based drawing and painting app with AI tools, localisation and accessibility support. | C#, WinUI 3 |
| [MarkUp](https://github.com/John-Donnelly/MarkUp-Markdown-Editor) | Markdown editor with a true WYSIWYG preview pane that round-trips edits back to source. | C#, WinUI 3 |
| [JAD Runner](https://github.com/John-Donnelly/jad-runner) | Desktop companion for jadapps.app — local HTTP + MCP endpoints for the platform's tool catalogue. Docs and releases. | Electron, Node, MCP |

---

## Stack

**Languages** C# · TypeScript · Rust · C++ · Python · JavaScript

**Platforms** WinUI 3 / Windows App SDK · .NET 8 · Node · Cloudflare Workers · Tauri

**Areas** Native desktop · local-first architecture · on-device inference · applied cryptography
· supply-chain security · developer tooling · MCP

---

## Elsewhere

- **Web** — [jadapps.app](https://jadapps.app)
- **npm** — [@jadapp/guard](https://www.npmjs.com/package/@jadapp/guard)
