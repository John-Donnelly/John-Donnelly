<h1 align="center">John Donnelly</h1>

<p align="center">
  <strong>Senior Systems Specialist · Founder of JAD Apps</strong><br>
  Native applications · Developer tools · Platform engineering<br>
  United Kingdom
</p>

<p align="center">
  <a href="https://jadapps.app/studio"><strong>Portfolio</strong></a> ·
  <a href="https://github.com/JAD-Apps"><strong>JAD Apps on GitHub</strong></a> ·
  <a href="mailto:hello@jadapps.app"><strong>Get in touch</strong></a>
</p>

---

## Software people can use. Systems others can maintain.

I design and build native Windows applications, web platforms and systems software. My work spans product design, architecture, implementation, testing and delivery, with particular attention to performance, recoverable state and clear user experiences.

Through **[JAD Apps](https://jadapps.app/)**, I’m building a portfolio of productivity and creative applications alongside shared foundations for settings, recovery, diagnostics and release management. My professional experience also includes data automation, Linux infrastructure commissioning, service monitoring, failure testing and operational handover.

<p>
  <a href="#featured-products">Featured products</a> ·
  <a href="#jad-apps-on-github">Organisation repositories</a> ·
  <a href="#current-work">Current work</a> ·
  <a href="#selected-engineering">Engineering</a> ·
  <a href="#lets-talk">Contact</a>
</p>

## Featured products

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>MarkUp Markdown Editor</h3>
      <a href="https://github.com/JAD-Apps/MarkUp-Markdown-Editor">
        <img src="https://raw.githubusercontent.com/JAD-Apps/MarkUp-Markdown-Editor/master/docs/media/markup-split-view.png" alt="MarkUp displaying Markdown source beside its formatted preview, with headings and a table." width="100%">
      </a>
      <p>Markdown editing with synchronised source and preview panes, direct preview editing, rich-text paste and document export.</p>
      <p><strong>C# · WinUI 3 · WebView2</strong></p>
      <p><a href="https://apps.microsoft.com/detail/9n0qv2j3vg7r">Microsoft Store</a> · <a href="https://github.com/JAD-Apps/MarkUp-Markdown-Editor">Source</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>Inklet</h3>
      <a href="https://github.com/JAD-Apps/Inklet">
        <img src="https://raw.githubusercontent.com/JAD-Apps/Inklet/master/docs/media/inklet-main.png" alt="Inklet showing three document tabs, a plain-text notes file and an encoding and cursor-position status bar." width="100%">
      </a>
      <p>A native text editor with a custom document engine, memory-mapped source access, background indexing and recoverable sessions.</p>
      <p><strong>C# · WinUI 3 · Win2D</strong></p>
      <p><a href="https://apps.microsoft.com/detail/9mxswrrnzmrh">Microsoft Store</a> · <a href="https://github.com/JAD-Apps/Inklet">Source</a></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>SmrtPad</h3>
      <a href="https://github.com/JAD-Apps/SmrtPad">
        <img src="https://raw.githubusercontent.com/JAD-Apps/SmrtPad/master/docs/media/smrtpad-ribbon.png" alt="SmrtPad displaying a formatted report in page view beneath its rich-text editing ribbon." width="100%">
      </a>
      <p>Rich-text documents, ribbon editing, tabbed workspaces, macros, document exports and on-device writing assistance.</p>
      <p><strong>C# · WinUI 3 · .NET</strong></p>
      <p><a href="https://github.com/JAD-Apps/SmrtPad/releases/latest">Portable release</a> · <a href="https://github.com/JAD-Apps/SmrtPad">Source</a></p>
    </td>
    <td width="50%" valign="top">
      <h3>SmrtDoodle</h3>
      <a href="https://github.com/JAD-Apps/SmrtDoodle">
        <img src="https://raw.githubusercontent.com/JAD-Apps/SmrtDoodle/master/docs/media/smrtdoodle-canvas.png" alt="SmrtDoodle displaying a colourful three-layer composition with blend-mode and opacity controls." width="100%">
      </a>
      <p>Layered drawing, compositing and image editing with a tiled canvas, blend modes and PSD import and export.</p>
      <p><strong>C# · WinUI 3 · Win2D</strong></p>
      <p><a href="https://github.com/JAD-Apps/SmrtDoodle/releases/latest">Portable release</a> · <a href="https://github.com/JAD-Apps/SmrtDoodle">Source</a></p>
    </td>
  </tr>
</table>

The desktop editor repositories are source-available under their documented licences. Follow the product links for current downloads, release notes and technical details.

## JAD Apps on GitHub

The public **[JAD-Apps organisation](https://github.com/JAD-Apps)** brings together application source, product documentation, releases and experimental work.

| Repository | Focus | Public access |
| --- | --- | --- |
| **[Inklet](https://github.com/JAD-Apps/Inklet)** | Native text editing, document performance and session recovery. | Source and releases |
| **[MarkUp Markdown Editor](https://github.com/JAD-Apps/MarkUp-Markdown-Editor)** | Bidirectional Markdown editing and document export. | Source and releases |
| **[SmrtPad](https://github.com/JAD-Apps/SmrtPad)** | Rich-text editing, macros and local writing assistance. | Source and portable releases |
| **[SmrtDoodle](https://github.com/JAD-Apps/SmrtDoodle)** | Layered drawing, compositing and image editing. | Source and portable releases |
| **[StoryArc](https://github.com/JAD-Apps/StoryArc)** | Windows audiobook playback, chapters, bookmarks and optional local captions. | Product and support information; Store release in preparation |
| **[JAD Runner](https://github.com/JAD-Apps/jad-runner)** | Local file-tool execution through HTTP and MCP interfaces. | Documentation and beta downloads |
| **[AxionBench](https://github.com/JAD-Apps/axionbench)** | An AI-model comparison preview with capability profiles, missing-data visibility and task-cost estimates. | Public source preview using a static data snapshot |

**[Organisation profile and community documentation](https://github.com/JAD-Apps/.github)** — support, contribution guidance and security policy.

## Current work

### JAD Application Platform

I’m developing a shared .NET foundation for the application catalogue: versioned product and module contracts, dependency validation, isolated application state, recovery, entitlement adapters and diagnostics.

Current work includes application integration and release qualification. The engineering goal is to share useful capabilities while keeping product data, permissions and release decisions explicit.

### StoryArc

**[StoryArc](https://github.com/JAD-Apps/StoryArc)** brings local audiobook playback, chapter navigation, persistent playback state, audio effects and optional on-device captions into a native Windows application. The Microsoft Store release is being prepared.

### CSV Compare and Instill

- **CSV Compare** — early development of native Windows tooling for explainable CSV and sales-export reconciliation.
- **Instill** — pre-release work on Linux software verification using isolated virtual machines, behavioural evidence and signed installation recipes.

## Beyond desktop applications

**[JAD Apps Data Factory](https://jadapps.app/)** is a web platform for file processing and repeatable workflows across structured data, documents and media. My work spans the application interface, browser and local execution paths, accounts, subscriptions and automation.

**[SecureSend](https://securesend.jadapps.app/)** separates encrypted file delivery from an atomic, one-time key release. Files are encrypted in the browser; the service handles the key rather than the document. The guarantee concerns release of the key—a recipient who decrypts a file can retain it.

## Selected engineering

| Project | What you can inspect |
| --- | --- |
| **[JADGuard](https://github.com/John-Donnelly/JADGuard)** | A JavaScript and TypeScript dependency gate with lockfile inspection, install controls and human, JSON and SARIF reports. |
| **[One-time key escrow](https://github.com/John-Donnelly/one-time-key-escrow)** | A focused implementation of chunked authenticated encryption, serialised state transitions and atomic single-use key release. |
| **[ECSIE](https://github.com/John-Donnelly/ecsie-architecture)** | The public architecture record, API surface and benchmark methodology for my sparse Mixture-of-Experts inference work. |
| **[Knitting Pattern Maker](https://github.com/John-Donnelly/KnittingPatternMaker)** | Deterministic image-to-pattern generation, shared algorithms, interactive controls and printable exports. |

## Professional experience

My professional work combines application engineering, data automation and infrastructure:

- **Systems architecture and commissioning:** Linux and Kubernetes infrastructure, redundant networking, replicated services and automated deployment.
- **Reliability and operations:** service monitoring, controlled failure tests, recovery diagnostics, deployment runbooks and operational handover.
- **Data and workflow tooling:** visual workflow editing, deterministic Python generation, durable execution and streaming data operations with bounded resource use.

I take responsibility for the details that make a system maintainable: clear boundaries, recoverable state, useful diagnostics and verification tied to the artifacts being delivered.

## Technical range

| Area | Technologies |
| --- | --- |
| **Native applications** | C# · .NET · WinUI 3 · Windows App SDK · Win2D · WebView2 |
| **Web and services** | TypeScript · JavaScript · React · Next.js · Node.js · Fastify · Python · Cloudflare Workers |
| **Data and infrastructure** | PostgreSQL · SQLite · SQL · Linux · Kubernetes · Git · CI/CD |
| **Runtime and integration work** | C++ · Rust · MCP · local inference · performance measurement |

## Let’s talk

I welcome conversations about **software and platform engineering, native applications, developer tools, workflow automation and technical partnerships**.

If you’re hiring, planning a product or working through a difficult engineering problem, tell me what you want to achieve and the constraints that matter.

**[hello@jadapps.app](mailto:hello@jadapps.app)** · **[Portfolio](https://jadapps.app/studio)** · **[JAD Apps on GitHub](https://github.com/JAD-Apps)**
