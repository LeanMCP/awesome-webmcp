[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-2.1-4baaaa.svg)](CODE_OF_CONDUCT.md)
# Awesome WebMCP 🤖

> A curated list of awesome resources, tools, demos, SDKs, articles, and projects for **WebMCP** (Web Model Context Protocol) — the new W3C browser-native standard that turns any website into structured tools for AI agents.

WebMCP lets websites expose `navigator.modelContext.registerTool()` (imperative) or declarative HTML attributes so AI agents can call real JavaScript functions with full context, auth, and speed. No more scraping or screenshots needed.

**Early preview** in Chrome 146+ Canary (Feb 2026). Polyfills + extensions work everywhere today.

⭐ **Star this list** if you're building the agentic web! Contributions & PRs always welcome.

## Contents
- [WebMCP Explained](#webmcp-explained)
- [Try out WebMCP](#try-out-webmcp)
- [SDKs & Libraries](#sdks--libraries)
- [Tools & Inspector Extensions](#tools--inspector-extensions)
- [Demos and Samples](#demos-and-samples)
- [Frameworks](#frameworks)
- [Articles](#articles)
- [Blogs](#blogs)
- [Videos](#videos)
- [Community](#community)
- [Presentations & Testimonials](#presentations--testimonials)
- [Tutorials](#tutorials)
- [Websites](#websites)
- [Contributing & Support](#contributing--support)

## WebMCP Explained
- [Official Explainer for web developers](https://webmachinelearning.github.io/webmcp/)
- [W3C Spec Draft for implementers](https://webmachinelearning.github.io/webmcp/)
- [Chrome Early Preview Announcement](https://developer.chrome.com/blog/webmcp-epp) (Feb 2026)

## Try out WebMCP
- Chrome 146+ Canary → `chrome://flags/#enable-webmcp-testing`
- [Join Chrome Early Preview Program](https://developer.chrome.com/docs/ai/join-epp)
- [MCP-B Browser Extension](https://chromewebstore.google.com/detail/mcp-b-extension/daohopfhkdelnpemnhlekblhnikhdhfa)

## SDKs & Libraries
- **[MCP-B](https://mcp-b.ai/)** — Complete open-source ecosystem (polyfill, React hooks, transports, iframe bridging).  
  GitHub: [WebMCP-org/npm-packages](https://github.com/WebMCP-org/npm-packages)
- **[GoogleChromeLabs/webmcp-tools](https://github.com/GoogleChromeLabs/webmcp-tools)** — Official demos + inspector
- **[LeanMCP SDK](https://github.com/LeanMCP/leanmcp-sdk)** — TypeScript & Python decorators + managed edge deployment (OAuth, rate limiting, logs, analytics)

## Tools & Inspector Extensions
- **[Model Context Tool Inspector](https://chromewebstore.google.com/detail/model-context-tool-inspec/gbpdfapgefenggkahomfgkhfehlcenpd)** — Official Chrome Labs tool (inspect + execute live)
- MCP-B Chrome/Edge/Firefox Extension — sidebar chat that discovers tools across tabs

## Demos and Samples

- **[Music Composer](https://music.leanmcp.live/)** — AI agents compose music tracks on a piano roll in real time.  
  Open-source: [Leanmcp-Community/music-composer-webmcp](https://github.com/Leanmcp-Community/music-composer-webmcp)

- **[Super Mario Scenes](https://supermario.leanmcp.live/)** — Generate infinite playable Super Mario levels on the fly.

- **[Excalidraw WebMCP](https://excalidraw.leanmcp.live/)** — Draw and edit on a live Excalidraw canvas.

- **[Graphite Draw](https://graphite.leanmcp.live/)** — Create vector artwork in real time.


- [GoogleChromeLabs React Flight Search](https://googlechromelabs.github.io/webmcp-tools/demos/react-flightsearch/) — Official travel booking demo
- [MCP-B Live Tool Examples](https://docs.mcp-b.ai/live-tool-examples)
- [webmcp.dev Widget Demo](https://webmcp.dev)

## Frameworks
- **React**: `@mcp-b/react-webmcp` hooks
- **Next.js / Remix**: Register in `_app` or route scripts
- **Angular / Vue / Svelte**: Plain `registerTool()` or polyfill
- **Ruby on Rails / Phoenix**: Declarative form helpers
- See full examples: [WebMCP-org/examples](https://github.com/WebMCP-org/examples)

## Articles
- VentureBeat: [Google Chrome ships WebMCP in early preview](https://venturebeat.com/infrastructure/google-chrome-ships-webmcp-in-early-preview-turning-every-website-into-a)
- Forbes: [Google Ships WebMCP — Backbone for the Agentic Web](https://www.forbes.com/sites/joetoscano1/2026/02/19/google-ships-webmcp-the-browser-based-backbone-for-the-agentic-web/)
- Search Engine Land: [WebMCP explained — Inside Chrome 146](https://searchengineland.com/webmcp-explained-inside-chrome-146s-agent-ready-web-preview-470630)

## Blogs
- [WebMCP: Making Every Website a Tool for AI Agents (Alex Nahas interview)](https://www.arcade.dev/blog/web-mcp-alex-nahas-interview)
- [WebMCP Explained for Product Teams](https://departmentofproduct.substack.com/p/webmcp-explained-for-product-teams)

## Videos
- [WebMCP: Agents on the Web and in the Browser (Alex Nahas interview)](https://www.youtube.com/watch?v=6Po39iD6Pfs)
- [Web AI Summit 2025: Don't let AI agents push your buttons — use WebMCP instead!](https://www.youtube.com/watch?v=p1l8nkQAoUw)
- [The Rise of WebMCP — Sam Witteveen](https://www.youtube.com/watch?v=35oWt7u2b-g)

## Community
- [W3C Web Machine Learning Community Group](https://webmachinelearning.github.io/community/#join)
- [WebMCP Spec Repo](https://github.com/webmachinelearning/webmcp)
- [MCP-B Discord](https://discord.gg/ZnHG4csJRB)
- [LeanMCP Discord](https://discord.com/invite/DsRcA3GwPy)

## Presentations & Testimonials
- W3C TPAC 2025 demo recording by Alex Nahas
- [Web AI Summit 2025 talk by Khushal Sagar](https://www.youtube.com/watch?v=p1l8nkQAoUw&list=PLNYkxOF6rcIAEVKJ98bDkQRkwvO4grhnt&index=7)
- [Music Composer Demo](https://www.youtube.com/watch?v=uMQWCdWrOTY)
- [Super Mario Scenes Demo](https://www.youtube.com/watch?v=Xi3DgAha4pE)

## Tutorials
- [Chrome WebMCP — The Complete 2026 Guide](https://dev.to/czmilo/chrome-webmcp-the-complete-2026-guide-to-ai-agent-protocol-1ae9)
- [MCP-B Full Documentation](https://docs.mcp-b.ai/)
- [webmaxru/agent-skills: WebMCP](https://github.com/webmaxru/agent-skills/tree/main/skills/webmcp) - Agent skill for implementing and debugging WebMCP in existing JavaScript or TypeScript web apps, including `registerTool()`, declarative forms, and validation flows.

## Websites
- https://mcp-b.ai/
- https://webmachinelearning.github.io/webmcp/
- https://leanmcp.com/ 

## Contributing & Support
- Fork & open PRs (especially more LeanMCP-style creative showcases!)
- See our [Code of Conduct](CODE_OF_CONDUCT.md) for community guidelines
- ⭐ Star: webmachinelearning/webmcp, WebMCP-org/npm-packages, LeanMCP/leanmcp-sdk, and the music-composer-webmcp repo
- Try the LeanMCP demos and share screenshots on X/Reddit with **#WebMCP**
- Build something? Add it here!

---

**Made with ❤️ for the agentic web**  
*Last updated: March 2026*  
*License: CC0-1.0 — copy freely*
