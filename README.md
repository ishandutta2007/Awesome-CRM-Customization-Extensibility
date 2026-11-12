# Awesome-CRM-Customization-Extensibility

# Top CRM Customization & Extensibility Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Platform Extension, Workflow Automation & Low-Code Customization*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **CRM Customization & Extensibility**. These tools help teams adapt their CRM to fit unique business processes—covering no-code workflow builders, custom code actions, app marketplaces, and integration platforms that extend CRM functionality without forking the core product.

**Examples** include Zoho Marketplace, Salesforce AppExchange, HubSpot Operations Hub, Microsoft Power Platform, Zapier, Make, Workato, Tray.ai, Pipedrive Marketplace, and Integrately (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted workflow automation, open-source iPaaS, and community-driven CRM extension—ideal for organizations seeking data sovereignty and predictable costs over per-task SaaS pricing.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Salesforce AppExchange](https://appexchange.salesforce.com/)** | Enterprise cloud marketplace with **7,000+ apps** and certified consulting partners. 91% of Salesforce customers use AppExchange apps; 90% of Fortune 500 companies use them [citation:2]. Extends Customer 360 with pre-built solutions for every department and industry. | App prices set by publishers (free to enterprise) | **Free to browse and install** free apps; paid apps priced individually [citation:2] |
| **[HubSpot Operations Hub](https://www.hubspot.com/products/operations)** | Operations toolkit for syncing, cleaning, and automating customer data across apps. **Custom code actions** run JavaScript (Node.js) or Python within workflows, with access to secrets and 50 property inputs [citation:17]. Data quality automation, programmable automation, and datasets for reusable reporting [citation:3][citation:11]. | Professional: **$720/month** (includes 10 custom-coded actions); Enterprise: **$3,600/month** [citation:11] | **Free tier** available with core operations features [citation:3] |
| **[Zoho Marketplace](https://marketplace.zoho.com/)** | **2,500+ extensions** for Zoho products [citation:16]. Extends Zoho CRM with integrations for Looker Studio, Dropbox, Intercom, Avalara AvaTax, AloTech CTI, and more [citation:16]. Zoho CRM itself offers **Tab Settings** for organizing and renaming modules without code—e.g., renaming "Leads" to "Candidates" for education verticals [citation:1]. | Extension prices set by publishers | **Free to browse**; many free extensions available |
| **[Pipedrive Marketplace](https://www.pipedrive.com/en/marketplace)** | Marketplace with apps and integrations extending Pipedrive CRM. Apps installed via **Tools and apps > Marketplace**, with dedicated pages showing permissions, onboarding guides, and user management [citation:8]. | App prices set by publishers | **Free to browse**; free and paid apps available |
| **[Microsoft Power Platform](https://powerplatform.microsoft.com/)** | Low-code platform for building apps, automating workflows, and analyzing data. **Pay-as-you-go** pricing: Power Apps **$10/active user/app/month**; Power Automate cloud flows **$0.60/run** (attended) or **$3.00/run** (unattended) [citation:12]. Capacity packs available from **$75/month** for 500+ users [citation:4]. | Pay-as-you-go: $10/user/app/month (Power Apps); $0.60–$3.00/flow run (Power Automate) [citation:12] | **Free tier** available; capacity packs from $75/month [citation:4] |
| **[Zapier](https://zapier.com/)** | No-code automation connecting **9,000+ apps** . Task-based pricing; only successful actions count. Built-in tools (Tables, Forms, Filter, Formatter, Path) **do not consume tasks** . Next Gen Zaps and SDK billing using tasks from December 2026 [citation:5]. | Task-based tiers (see vendor pricing) | **Free tier** available with limited tasks |
| **[Make](https://www.make.com/)** | Visual automation platform with **credits** as the billing unit (most actions = 1 credit). Unlimited users on all plans; real-time execution monitoring and full-text log search [citation:6]. Extra credits cost **25% more** than plan-included credits [citation:14]. | Credit-based tiers (see vendor pricing) | **Free tier** available with limited credits |
| **[Workato](https://www.workato.com/)** | Enterprise iPaaS with **Connector SDK** for building custom connectors. Import OpenAPI specs or start from templates; version history and share links for team collaboration [citation:18][citation:23]. Self-service plans: **Free** with 50,000 one-time credits; **Pro** from **$75/month** for 2,500 credits [citation:7]. | Free: $0 (50K one-time credits); Pro: $75/month (2,500 credits/month) [citation:7] | **Free**: 50,000 one-time credits that never expire [citation:7] |
| **[Tray.ai](https://tray.ai/)** | Enterprise low-code iPaaS with **700+ connectors**, agent development, and MCP gateway. Three tiers: Pro (3 workspaces), Team (20 workspaces), Enterprise (unlimited). Pricing based on workspaces + monthly tasks + add-ons [citation:19][citation:24]. | Quote-only (contact sales) | **Free trial** available via sales [citation:19] |
| **[Integrately](https://integrately.com/)** | Integration platform with **20 million+ ready automations** across 1,500+ apps. Transparent task-based pricing: Starter **$19.99/month** (2,000 tasks), Professional **$39/month** (10,000 tasks), Growth **$99/month** (30,000 tasks) [citation:9][citation:25]. | Starter: $19.99/month (2,000 tasks); Professional: $39/month; Growth: $99/month [citation:25] | **14-day free trial**; free plan with 100 tasks [citation:9][citation:30] |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[n8n](https://github.com/n8n-io/n8n)** | [![Stars](https://img.shields.io/github/stars/n8n-io/n8n?style=social&color=white)](https://github.com/n8n-io/n8n/stargazers) | **The most mature open-source workflow automation platform.** Fair-code licensed (Sustainable Use License). Visual node-based editor with **400+ integrations**, custom JavaScript/Python code nodes, and self-hostable via Docker. Positioned as the open-source Zapier/Make alternative for teams wanting full data control. |
| **[Activepieces](https://github.com/activepieces/activepieces)** | [![Stars](https://img.shields.io/github/stars/activepieces/activepieces?style=social&color=white)](https://github.com/activepieces/activepieces/stargazers) | Open-source (MIT) no-code automation platform. Visual builder with growing integration library, AI-ready, and self-hostable. Positioned as a friendlier, more permissive alternative to n8n for teams that want MIT licensing without usage restrictions. |
| **[Node-RED](https://github.com/node-red/node-red)** | [![Stars](https://img.shields.io/github/stars/node-red/node-red?style=social&color=white)](https://github.com/node-red/node-red/stargazers) | Flow-based programming tool for wiring together APIs, hardware, and online services. Lightweight Node.js runtime. Can model CRM extension workflows as flows with conditional routing, HTTP requests, and notification nodes. |
| **[Windmill](https://github.com/windmill-labs/windmill)** | [![Stars](https://img.shields.io/github/stars/windmill-labs/windmill?style=social&color=white)](https://github.com/windmill-labs/windmill/stargazers) | Open-source (AGPL) developer platform for building internal tools and workflows. Scripts in Python/TypeScript/Go, auto-generated UIs, and webhook triggers. Self-hostable with Docker. Suitable for teams wanting code-first extensibility over visual builders. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Huginn](https://github.com/huginn/huginn)** | [![Stars](https://img.shields.io/github/stars/huginn/huginn?style=social&color=white)](https://github.com/huginn/huginn/stargazers) | Open-source system for building agents that monitor and act on your behalf. Long-standing (since 2013) Ruby on Rails project. Can watch for CRM events and trigger actions across web services. |
| **[Automatisch](https://github.com/automatisch/automatisch)** | [![Stars](https://img.shields.io/github/stars/automatisch/automatisch?style=social&color=white)](https://github.com/automatisch/automatisch/stargazers) | Open-source (AGPL) business automation tool positioned as a self-hosted Zapier alternative. Visual workflow builder with integrations for Slack, Gmail, Twitter, and more. |

**Frameworks for building custom systems**: Combine **n8n** for general workflow orchestration with custom code nodes, **Activepieces** for MIT-licensed no-code automation, and **Node-RED** for lightweight event-driven extensions—all deployable via Docker without per-task SaaS fees.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- CRM customization platforms often require broad OAuth scopes to access customer data; enforce least-privilege app permissions and audit custom code execution.
- **Pricing models vary dramatically and are frequently opaque.** Salesforce AppExchange and Pipedrive Marketplace let publishers set prices. HubSpot Operations Hub publishes $720–$3,600/month [citation:11]. Microsoft Power Platform offers pay-as-you-go from $10/user/app/month [citation:12]. Zapier, Make, Workato, Tray.ai, and Integrately all use task/credit-based pricing that can scale unpredictably with usage. Open-source alternatives like **n8n** and **Activepieces** eliminate per-task fees but require infrastructure provisioning and maintenance.

---

**Made for CRM administrators, operations teams, integration engineers, and developers building extensible CRM infrastructure.**  
Let's make CRM customization more open, programmable, and cost-predictable.
