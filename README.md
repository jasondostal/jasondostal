## Jason Dostal

I build AI-native development infrastructure and the things that prove it works.

The projects that came out of working that way:

**[Cairn MCP](https://github.com/jasondostal/cairn-mcp)** — semantic memory and work
tracking for AI agents. Persistent context, session continuity, work item hierarchy.
Built so my AI collaborators can actually remember what we're doing.

**[DiskScope](https://github.com/jasondostal/diskscope)** — a native macOS WinDirStat, written
in Swift. Renders disk usage as a fast, live, cushioned treemap, and comes with a very fun,
full-featured TUI version of the app. File ops right from the UI — delete, open in Finder, and more.

**[TunnelVision](https://github.com/jasondostal/tunnelvision)** — Docker container that
manages your VPN tunnel end-to-end. WireGuard, OpenVPN, nftables killswitch, 25 native
providers, DNS, HTTP/SOCKS5/Shadowsocks proxies, Home Assistant integration.

**[Scoreline](https://github.com/jasondostal/scoreline)** — live sports win probability
on WLED-controlled LED strips. 16 leagues, WebSocket real-time, native HA integration.
One of 4 WLED instances I run — this instance lives in a custom enclosure on a Dig-Quad with
on-demand fans and a Shelly1PM for remote power and heat monitoring.

**[Curiocraft Prints](https://curiocraftprints.com)** — Site for my 3D printing side business.   Originally static JS/CSV, now 100% headless api driven CMS (55 REST endpoints) with Google Analytics, tokenized user signups, agentic inventory management and a full CRUD admin backend w/ logging and OIDC integration. Another Cairn build.

**[Homelab Guide](https://github.com/jasondostal/homelab-guide)** — The Hitchhiker's Guide
to a Safe and Sane Full-Stack Homelab. Decision framework and reference implementation for
Docker-based homelab with AI-assisted dev focus. Covers everything from VLANs and defense
in depth to backups, certs, and the fun stuff.

---
**[Foundry Agents PoC](https://github.com/jasondostal/foundry-agents-poc)** — AI agents on
Azure AI Foundry. Four agents surfaced through SvelteKit + Node on App Service,
authenticated entirely by managed identity. Reference for voice + text conversational
agents grounded on a knowledge base.

**[Azure IAC Platform](https://github.com/jasondostal/azure-platform-iac)** — shared Bicep
platform modules (compute, data, messaging, networking, security, integration, identity, AI)
+ shared ADO pipeline templates (build-dotnet, build-python, build-go, build-node, security
gates, per-environment deploy) + one-command subscription bootstrap. The single source of
truth for Azure infrastructure — app repos consume modules and pipeline templates via
references. Patch once, every team inherits.

**[Azure IAC Reference](https://github.com/jasondostal/azure-iac-reference)** — .NET web
app with Azure SQL, DDL-managed schema promotion, private endpoints, APIM with multi-auth
(Entra ID + B2C + client credentials), Foundry AI agent infra, and a 7-stage ADO pipeline
(Build → Lint → Scan → Deploy × 4 envs). Exhaustive demo of every platform module wired
together.

**[Azure IAC Patterns](https://github.com/jasondostal/azure-iac-patterns)** — standalone
patterns catalog: full identity + APIM multi-auth, Foundry AI agent stack (Hub + Project +
AI Search + models), Service Bus, Event Grid, Cosmos DB, Storage, Functions, and complete
VNet + private DNS networking.

**[Azure Project Starter](https://github.com/jasondostal/azure-project-starter)** —
cookiecutter/cruft template with 6 archetypes (dotnet-api, dotnet-web, python-function,
go-web, go-desktop, node-agent). One command → full repo with ADO pipeline consuming
platform templates, Bicep IaC, team .editorconfig, and onboarding docs. Toggle SQL,
Foundry, and APIM at generation time. `cruft update` propagates template changes into
existing projects.

---

On [Printables](https://www.printables.com/@LayerusRex) as LayerusRex — free and open,
everything I design goes back to the community.

Also enjoy DIY IoT / hardware projects - ESPHome (irrigation controllers, RFID repeaters), RetroPie, WLED (custom designed/fabricated/installed ~1,000 pixel permanent home holiday lighting) and [my BirdNET-Pi setup](https://github.com/Nachtzuster/BirdNET-Pi/discussions/309).
