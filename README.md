# Awesome-Mobile-E-Learning-Storyboarding

## Top Mobile E-Learning Storyboarding Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Touch-Optimized Storyboarding, Infinite Canvas Collaboration & Self-Hosted Pre-Production Tools*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Mobile E-Learning Storyboarding**. These tools help instructional designers, educators, and content creators plan e-learning modules visually — sketching panel sequences, arranging course flows on infinite canvases, and collaborating on pre-production storyboards from tablets and phones.

**Examples** include Storyboarder, Ztoryc, Dim0, and AFFiNE (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, touch-friendly canvas collaboration, and offline storyboarding — especially relevant as **Storyboarder** remains the most popular open-source storyboard tool with 3,100+ GitHub stars [citation:13], and **Ztoryc** brings professional storyboard features to Tahoma2D/OpenToonz pipelines [citation:3].

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **Boords** — **The web-based storyboard standard for agencies and educators.** Drag-and-drop storyboard builder with drawing tools, PDF export, and online sharing. **Subscription-based**. **Best for teams** wanting a polished browser-based storyboarding experience with client-ready PDF output [citation:2].

- **Milanote** — **The visual planning tool for creative projects.** Infinite canvas with notes, images, and connectors — well-suited to mapping course structures and e-learning flows. **Free tier with paid Pro**. **Best for educators** wanting a flexible visual planning space that works on tablets.

- **Miro** — **The collaborative whiteboard platform.** Infinite canvas with templates for storyboarding, mind mapping, and flowcharts. **Free tier with paid team plans**. **Best for remote teams** needing real-time collaboration on storyboards and course maps, accepting that it is a general-purpose whiteboard rather than a dedicated storyboard tool.

- **Padlet** — **The collaborative board platform.** Simple drag-and-drop boards for collecting and arranging ideas, images, and links. **Free tier with paid plans**. **Best for quick classroom storyboarding exercises** where simplicity matters more than advanced drawing tools.

## Open-Source GitHub Projects

- **Storyboarder** — **The most popular open-source storyboard tool.** **MIT licensed, 3,100+ GitHub stars** [citation:13]. **Makes it easy to visualize a story as fast as you can draw stick figures** — built for filmmakers and animators who need rapid pre-visualization. **Features**: draw panels directly in the tool, add dialogue and notes, arrange shots in sequence, and export to PDF or video animatic. **Desktop app** for macOS, Windows, and Linux. **The honest caveat**: **desktop-first design** — it is not optimized for touch or mobile use, though the underlying concepts translate to tablet workflows. **Best for filmmakers and animators** wanting a free, proven storyboarding tool on desktop, with mobile use limited to companion viewing or idea capture.

- **Ztoryc** — **The professional open-source storyboard tool built for Tahoma2D/OpenToonz pipelines.** **A fork of Tahoma2D designed for storyboard artists, directors, and studios** who need serious pre-production tools before a single frame is animated [citation:3]. **Full storyboard workflow**: panel grid with automatic detection from keyframes and camera moves, drag-and-drop shot reordering, **camera movement annotations** with START/STOP overlays and A→B arrows, **3D light direction gizmo** for panel lighting, dialogue/notes per panel, and **script import** from Final Draft (.fdx), Fountain, DOCX, ODT, and plain text [citation:3]. **Export options**: professional PDF storyboards with durations and annotations, **animatic export** with audio and burn-in timecode, and **layout scenes** as `.tnz` files ready for animation [citation:3]. **Runs on macOS and Windows** — not yet mobile-optimized, but the storyboard structure translates to tablet review workflows. **Best for professional storyboard artists and studios** wanting a free alternative to paid storyboard tools that integrates directly with 2D animation pipelines.

- **Dim0** — **The AI-native infinite canvas with real-time multiplayer.** **MIT licensed, self-hostable** — your data stays yours with no training or telemetry [citation:11]. **The board is the workspace**, holding shapes, rich-text notes, code sandboxes, mini-apps (interactive React apps like quizzes and charts), documents, nested boards, and presentation frames — all on one infinite canvas . **Real-time multiplayer** with live cursors and conflict-free sync via operational transforms, working identically for solo users or fifty-person teams . **Agent layer built on OpenAI Agents SDK** lets an AI read the board, take multi-step actions, and write results back — useful for generating storyboard structures or course flow drafts from prompts . **Runs via Docker** or as a **fully local desktop app** (macOS, Linux, Windows) with bring-your-own-model support for OpenAI, Anthropic, Gemini, Mistral, and more [citation:11]. **The honest caveat**: **not a dedicated storyboard tool** — it is a general-purpose collaborative canvas with AI, so storyboard templates and E-learning-specific structure must be built manually. **Best for teams** wanting an open-source, self-hosted Miro/FigJam alternative with AI assistance for course planning and storyboard ideation.

- **AFFiNE** — **The open-source Notion and Miro alternative.** **Open-core, self-hostable** with a local-first workspace for writing, drawing, planning, and knowledge management [citation:15]. **Combines docs, whiteboards, and databases** in one tool — suitable for building course storyboards alongside written lesson plans and structured content. **Real-time collaboration** on infinite canvas surfaces. **The honest caveat**: **more general-purpose than storyboard-specific** — it is a workspace tool, not a storyboarding app, so panel-based visual planning requires manual setup. **Best for teams** wanting a self-hosted workspace that combines documentation, visual planning, and collaboration in one place.

### Additional Strong Open-Source Options

- **Excalidraw** — **The hand-drawn style whiteboard.** **MIT licensed, 134k GitHub stars** [citation:9]. **Infinite canvas for sketching diagrams and wireframes** with a distinctive hand-drawn aesthetic. **Not self-hostable as a standalone service** according to one comparison [citation:9], though the library can be embedded. **Best for quick storyboard sketches and flow diagrams** where a hand-drawn feel suits ideation.

- **tldraw** — **The whiteboard SDK for building canvas experiences.** **Source-available, 51k GitHub stars** [citation:9]. **An infinite canvas and whiteboard primarily used as an SDK** in other apps rather than a finished product [citation:9]. **Best for developers** wanting to build custom storyboarding tools on top of a proven canvas engine.

- **Drawnix** — **The all-in-one diagramming canvas.** **MIT licensed, 15k GitHub stars** [citation:9]. **Combines mind maps, flowcharts, and freehand drawing** on one infinite canvas, with Markdown-to-mind-map and Mermaid-to-flowchart generation [citation:14]. **Docker deployment available** [citation:14]. **Best for teams** wanting structured diagram types (mind maps, flowcharts) alongside freehand sketching for course planning.

**Frameworks for building custom systems**: Combine **Storyboarder** for rapid panel sketching on desktop, **Ztoryc** for professional storyboard-to-animation pipelines, **Dim0** for AI-assisted infinite canvas collaboration with multiplayer, and **AFFiNE** for combined docs-plus-whiteboard course planning — to build an E-learning storyboarding stack tailored to your need for dedicated storyboard tools versus general-purpose visual planning, and desktop versus collaborative canvas workflows.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Mobile E-learning storyboarding tools differ significantly in storyboard specificity, touch optimization, and collaboration model. **Storyboarder is the most popular open-source storyboard tool** but is **desktop-first** — it is not designed for tablet drawing or mobile collaboration [citation:13]. **Ztoryc is purpose-built for professional storyboard-to-animation pipelines** with panel grids, camera annotations, and animatic export, but is **desktop-only** and tied to Tahoma2D/OpenToonz workflows [citation:3]. **Dim0 and AFFiNE are general-purpose infinite canvases**, not dedicated storyboard tools — they excel at collaborative planning and AI-assisted ideation but require manual storyboard structure. **Boords and Miro are SaaS platforms** — they work on tablets but require internet and subscription/account [citation:2]. **The choice often comes down to need**: dedicated storyboard panels (Storyboarder, Ztoryc) versus flexible visual planning (Dim0, AFFiNE, Miro).
- Self-hosted open-source solutions require proper deployment (Docker for Dim0 and Drawnix, desktop installation for Storyboarder and Ztoryc), and awareness that mobile storyboarding often involves a tablet for drawing paired with a desktop tool for assembly and export.

---

**Made for instructional designers, educators, and content creators choosing E-learning storyboarding tools that match their workflow and collaboration needs.**
Let's make mobile E-learning storyboarding more open, touch-aware, and self-hostable.
