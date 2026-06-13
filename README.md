## Jason Dostal

I build AI-native development infrastructure and the things that prove it works.

The projects that came out of working that way:

**[Cairn MCP](https://github.com/jasondostal/cairn-mcp)** — semantic memory and work
tracking for AI agents. Persistent context, session continuity, work item hierarchy.
Built so my AI collaborators can actually remember what we're doing.

**[foundry-agents-poc](https://github.com/jasondostal/foundry-agents-poc)** — reference
implementation for standing up AI agents on Azure AI Foundry. Four agents (policy KB,
code interpreter, all-in-one, assistant) surfaced through a SvelteKit + Node app on
Azure App Service — authenticated entirely by managed identity, no API keys.

**[Azure IAC Reference](https://github.com/jasondostal/azure-iac-reference)** — full-stack
Bicep IAC + Azure DevOps CI/CD pipeline for deploying a .NET web app to Azure across
4 environments. Consumes modules from the [platform repo](https://github.com/jasondostal/azure-platform-iac)
and includes DDL-managed SQL schema promotion, private endpoints, and a 7-stage pipeline
(Build → Lint → Scan → Deploy×4).

**[Azure IAC Patterns](https://github.com/jasondostal/azure-iac-patterns)** — standalone
Bicep reference modules for Azure services: Service Bus, Event Grid, API Management,
Cosmos DB, Storage, Functions, and full VNet + DNS networking.

**Azure IAC Platform** — [shared Bicep platform modules](https://github.com/jasondostal/azure-platform-iac)
(compute, data, messaging, networking, security, integration) designed for app repos to
consume via module references. The single source of truth — patch once, all repos inherit.

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

On [Printables](https://www.printables.com/@LayerusRex) as LayerusRex — free and open,
everything I design goes back to the community.

Also enjoy DIY IoT / hardware projects - ESPHome (irrigation controllers, RFID repeaters), RetroPie, WLED (custom designed/fabricated/installed ~1,000 pixel permanent home holiday lighting) and [my BirdNET-Pi setup](https://github.com/Nachtzuster/BirdNET-Pi/discussions/309).
