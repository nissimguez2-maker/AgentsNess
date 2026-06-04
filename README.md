# 🎭 The Agency: AI Specialists Ready to Transform Your Workflow

> **A complete AI agency at your fingertips** - From frontend wizards to Reddit community ninjas, from whimsy injectors to reality checkers. Each agent is a specialized expert with personality, processes, and proven deliverables.

[![GitHub stars](https://img.shields.io/github/stars/msitarzewski/agency-agents?style=social)](https://github.com/msitarzewski/agency-agents)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://makeapullrequest.com)
[![Sponsor](https://img.shields.io/badge/Sponsor-%E2%9D%A4-pink?logo=github)](https://github.com/sponsors/msitarzewski)

---

## 🚀 What Is This?

Born from a Reddit thread and months of iteration, **The Agency** is a growing collection of meticulously crafted AI agent personalities. Each agent is:

- **🎯 Specialized**: Deep expertise in their domain (not generic prompt templates)
- **🧠 Personality-Driven**: Unique voice, communication style, and approach
- **📋 Deliverable-Focused**: Real code, processes, and measurable outcomes
- **✅ Production-Ready**: Battle-tested workflows and success metrics

**Think of it as**: Assembling your dream team, except they're AI specialists who never sleep, never complain, and always deliver.

---

## ⚡ Quick Start

### Option 1: Use with Claude Code (Recommended)

```bash
# Install all agents to your Claude Code directory
./scripts/install.sh --tool claude-code

# Or manually copy a category if you only want one division
cp engineering/*.md ~/.claude/agents/

# Then activate any agent in your Claude Code sessions:
# "Hey Claude, activate Frontend Developer mode and help me build a React component"
```

### Option 2: Use as Reference

Each agent file contains:
- Identity & personality traits
- Core mission & workflows
- Technical deliverables with code examples
- Success metrics & communication style

Browse the agents below and copy/adapt the ones you need!

### Option 3: Use with Other Tools (GitHub Copilot, Antigravity, Gemini CLI, OpenCode, OpenClaw, Cursor, Aider, Windsurf, Kimi Code, Codex)

```bash
# Step 1 -- generate integration files for all supported tools
./scripts/convert.sh

# Step 2 -- install interactively (auto-detects what you have installed)
./scripts/install.sh

# Or target a specific tool directly
./scripts/install.sh --tool antigravity
./scripts/install.sh --tool gemini-cli
./scripts/install.sh --tool opencode
./scripts/install.sh --tool copilot
./scripts/install.sh --tool openclaw
./scripts/install.sh --tool cursor
./scripts/install.sh --tool aider
./scripts/install.sh --tool windsurf
./scripts/install.sh --tool kimi
./scripts/install.sh --tool codex
```

See the [Multi-Tool Integrations](#-multi-tool-integrations) section below for full details.

---

## 🎨 The Agency Roster

### 💻 Engineering & AI

| Agent | What it does |
|---|---|
| [🎛️ Agent & Workflow Orchestrator](engineering/Agent%20%26%20Workflow%20Orchestrator.md) | Maps every path through a system into build-ready specs, then runs the dev pipeline (plan → architecture → dev↔QA loop → integration) with hard quality gates. Use it to coordinate multi-agent builds and spec workflows before any code is written. |
| [🔐 Agent Identity & Trust](engineering/Agent%20Identity%20%26%20Trust.md) | Designs identity for multi-agent systems — cryptographic agent identity, authentication, scoped delegation, and tamper-evident audit trails, plus a shared entity-resolution graph. Use it when agents take real actions and must prove who they are. |
| [🤖 AI Engineer](engineering/AI%20Engineer.md) | Builds and ships ML/AI features into production — model development, data pipelines, and AI integration, with a focus on practical, scalable solutions. Use it to add intelligent features or stand up AI-powered apps. |
| [🔌 API Tester](engineering/API%20Tester.md) | Validates APIs end to end — functional correctness, performance/load, and reliability across your services and third-party integrations. Use it to catch API breakage before users do. |
| [⚙️ Automation Governance Architect](engineering/Automation%20Governance%20Architect.md) | A governance-first reviewer for business automations (n8n-first) that audits value, risk, and maintainability before you build. Use it to decide whether and how to automate, not just how to wire it up. |
| [🏗️ Backend Architect](engineering/Backend%20Architect.md) | Designs scalable server-side systems — APIs, database architecture with query/performance tuning, microservices, and cloud infrastructure. Use it for the backbone that has to stay up and scale. |
| [🧱 CMS Developer](engineering/CMS%20Developer.md) | A Drupal and WordPress specialist for themes, custom plugins/modules, content architecture, and code-first CMS work. Use it to build or customize CMS-based sites properly in code. |
| [👁️ Code Reviewer & Quality](engineering/Code%20Reviewer%20%26%20Quality.md) | Reviews code for correctness, security, maintainability, and performance; makes surgical minimum-viable changes that refuse scope creep; and explains unfamiliar codebases from the source. Use it to keep vibe-coded or inherited code healthy. |
| [📋 Compliance Auditor](engineering/Compliance%20Auditor.md) | Walks you through SOC 2, ISO 27001, HIPAA, and PCI-DSS — from readiness and gap analysis to evidence collection and certification. Use it when a security/compliance cert becomes a sales requirement or obligation. |
| [🔧 Data Engineer](engineering/Data%20Engineer.md) | Builds reliable data pipelines and lakehouse architecture — ETL/ELT, Spark, dbt, and streaming — to turn raw data into trusted, analytics-ready assets. Use it to stand up or fix your data infrastructure. |
| [🚀 DevOps & Reliability Engineer](engineering/DevOps%20%26%20Reliability%20Engineer.md) | Ships and runs your app end to end — CI/CD, infrastructure-as-code, observability/SLOs, incident command, on-call, and cost/performance guardrails. Use it to deploy, keep production healthy, and respond to incidents. |
| [📧 Email Intelligence Engineer](engineering/Email%20Intelligence%20Engineer.md) | Turns raw email threads into structured, reasoning-ready data for AI agents and automations — parsing MIME and extracting clean context. Use it when an agent needs signal out of messy inboxes. |
| [🖥️ Frontend Developer](engineering/Frontend%20Developer.md) | Builds modern, responsive, accessible web apps in React/Vue/Angular with pixel-perfect UI and performance optimization. Use it to implement the user-facing front end. |
| [🔌 MCP Builder](engineering/MCP%20Builder.md) | Designs, builds, and tests Model Context Protocol servers that extend AI agents with custom tools, resources, and prompts. Use it to give your agents real, reusable capabilities. |
| [📲 Mobile App Builder](engineering/Mobile%20App%20Builder.md) | Ships native-quality iOS/Android apps using native and cross-platform frameworks, fast. Use it to build or iterate on mobile applications. |
| [🧬 Prompt Engineer](engineering/Prompt%20Engineer.md) | Crafts, tests, and systematically optimizes LLM prompts — turning vague instructions into reliable, production-grade AI behaviors. Use it to make AI features consistent and dependable. |
| [🧪 QA Engineer](engineering/QA%20Engineer.md) | Hands-on QA across performance (load, Core Web Vitals), accessibility (WCAG 2.2 AA), and test-results analysis, with data-driven release-readiness calls. Use it to answer 'is it fast, accessible, and ready to ship?' |
| [🧐 QA Reality Checker](engineering/QA%20Reality%20Checker.md) | A skeptical, evidence-obsessed quality gate that demands proof for every claim, defaults to 'NEEDS WORK,' and won't certify production-readiness without it. Use it as the final check against fantasy approvals. |
| [⚡ Rapid Prototyper](engineering/Rapid%20Prototyper.md) | Turns an idea into a working proof-of-concept or MVP fast, using efficient tools and frameworks. Use it to validate a concept before committing to a full build. |
| [🔒 Security Engineer](engineering/Security%20Engineer.md) | Threat-models, reviews code, hunts vulnerabilities, and designs security architecture and detection for web, API, and cloud-native apps. Use it for anything touching auth, data, or attack surface. |
| [⛓️ Smart Contract Engineer & Security Auditor](engineering/Smart%20Contract%20Engineer%20%26%20Security%20Auditor.md) | Builds gas-optimized, upgradeable Solidity/EVM contracts and DeFi protocols, then audits them like an attacker — vulnerability detection, formal verification, and audit reports. Use it for on-chain code that must survive mainnet. |
| [🏛️ Software Architect](engineering/Software%20Architect.md) | Designs systems for the long run — domain-driven design, architectural patterns, and explicit trade-off analysis for scalable, maintainable systems. Use it for big technical decisions and system evolution. |
| [📚 Technical Writer](engineering/Technical%20Writer.md) | Writes developer docs, API references, READMEs, and tutorials that turn complex engineering into clear content developers actually use. Use it to make your software understandable. |
| [🎙️ Voice AI Integration Engineer](engineering/Voice%20AI%20Integration%20Engineer.md) | Builds end-to-end speech-to-text pipelines (Whisper / cloud ASR) — ingestion, cleanup, subtitles, speaker diarization, and structured integration. Use it to turn audio into production-ready transcripts. |
| [🗃️ ZK Steward](engineering/ZK%20Steward.md) | A Zettelkasten-style knowledge-base steward (Luhmann by default, domain experts on demand) that enforces atomic, connected, validated notes. Use it for knowledge-base building, note linking, and complex task breakdown. |

### 🎨 Product & Design

| Agent | What it does |
|---|---|
| [🖼️ AI Visual Generation Specialist](product/AI%20Visual%20Generation%20Specialist.md) | Turns visual concepts into precise, structured prompts for Midjourney, DALL·E, Stable Diffusion, Flux, Sora, and Runway — with authentic, bias-free human representation. Use it to generate professional, on-brand AI images and video. |
| [🧠 Behavioral Engagement & Retention Designer](product/Behavioral%20Engagement%20%26%20Retention%20Designer.md) | Designs the in-product nudges, cadences, and habit loops that drive activation, engagement, and retention — using the Fogg model and ethical nudging, no dark patterns. Use it to turn first-time users into repeat ones. |
| [🎨 Brand Guardian](product/Brand%20Guardian.md) | Develops and protects brand identity, consistency, and strategic positioning. Use it to define your brand and keep every touchpoint on-brand. |
| [🔭 Product & Market Research](product/Product%20%26%20Market%20Research.md) | Combines outside-in market intelligence (trends, competitors, opportunity sizing) with inside-out voice-of-customer (feedback, sentiment, synthesis) into decision-ready insight. Use it to decide what's worth building. |
| [🧭 Product Manager](product/Product%20Manager.md) | Owns the full product lifecycle — discovery, strategy, prioritization (RICE/MoSCoW/Kano), roadmap, sprints, stakeholders, and outcome measurement. Use it to ship the right thing, not just the next thing. |
| [🎨 UI Designer](product/UI%20Designer.md) | Creates visual design systems, component libraries, and pixel-perfect, accessible interfaces that reflect brand identity. Use it for the look and feel of your product. |
| [📐 UX Architect](product/UX%20Architect.md) | Gives developers solid UX foundations, CSS systems, and clear implementation guidance. Use it to bridge design and build with a developer-friendly architecture. |
| [🔬 UX Researcher](product/UX%20Researcher.md) | Validates design decisions with real user data — behavior analysis, usability testing, and actionable findings. Use it to replace assumptions with evidence. |
| [🎬 Visual Storyteller](product/Visual%20Storyteller.md) | Transforms complex information into compelling visual narratives and multimedia that drive emotional engagement. Use it for explainers, brand narrative, and visual storytelling. |

### 📢 Marketing & Content

| Agent | What it does |
|---|---|
| [🔮 AI Search & Answer-Engine Optimizer](marketing/AI%20Search%20%26%20Answer-Engine%20Optimizer.md) | Makes your site discoverable, citable, and actionable to AI systems (AEO/GEO) — crawler access and schema, brand visibility in ChatGPT/Claude/Gemini/Perplexity, and agentic task completion. Use it to win AI-driven traffic. |
| [🎠 Carousel Growth Engine](marketing/Carousel%20Growth%20Engine.md) | Autonomously generates viral TikTok/Instagram carousels from any URL, publishes to feed with trending audio, and improves via a data-driven learning loop. Use it for hands-off short-form carousel growth. |
| [✍️ Content Creator](marketing/Content%20Creator.md) | Develops multi-platform content strategy — editorial calendars, copy, and brand storytelling optimized for engagement across channels. Use it to plan and produce content at scale. |
| [🎙️ Global Podcast Strategist](marketing/Global%20Podcast%20Strategist.md) | Grows podcasts through positioning, audience development, content strategy, and monetization on Spotify, Apple, and YouTube. Use it to turn a show into an audio brand that compounds. |
| [📸 Instagram Curator](marketing/Instagram%20Curator.md) | Masters Instagram aesthetics and multi-format content to build an engaged community. Use it for visual storytelling and growth on Instagram. |
| [💼 LinkedIn Content Creator](marketing/LinkedIn%20Content%20Creator.md) | Builds thought leadership and personal brand on LinkedIn with algorithm- and culture-aware content that drives inbound. Use it to make the right people find you on LinkedIn. |
| [📣 PR & Communications Manager](marketing/PR%20%26%20Communications%20Manager.md) | Handles media relations, press releases, crisis comms, executive thought leadership, and reputation management through earned media and narrative control. Use it to build and protect your reputation. |
| [💬 Reddit Community Builder](marketing/Reddit%20Community%20Builder.md) | Engages Reddit authentically — value-driven content and long-term relationship building that respects each subreddit's culture. Use it to grow trust on Reddit without getting burned. |
| [🔍 SEO Specialist](marketing/SEO%20Specialist.md) | Drives sustainable organic traffic through technical SEO, content optimization, and link-authority building. Use it for long-term search growth. |
| [🎬 Short-Video Editing Coach](marketing/Short-Video%20Editing%20Coach.md) | Coaches the full short-video post-production pipeline (CapCut/Premiere/DaVinci/FCP) — composition, color, audio, motion graphics, subtitles, and export. Use it to make scroll-stopping short videos. |
| [📣 Social Media Strategist](marketing/Social%20Media%20Strategist.md) | Orchestrates cross-platform social campaigns, community building, real-time engagement, and thought leadership. Use it as the lead for a coordinated multi-channel social presence. |
| [🎵 TikTok Strategist](marketing/TikTok%20Strategist.md) | Creates viral TikTok content with algorithm and culture mastery for brand growth. Use it to grow on TikTok authentically. |
| [🎬 Video Optimization Specialist](marketing/Video%20Optimization%20Specialist.md) | Optimizes YouTube for the algorithm and retention — chaptering, thumbnails, and cross-platform syndication. Use it to grow and retain a video audience. |
| [🐦 X/Twitter Strategist](marketing/X-Twitter%20Strategist.md) | A full X/Twitter operator — builds presence (engagement, threads, Spaces, community) and reads the room (trend detection, brand/competitor monitoring). Use it to grow authority and gather market intel on X. |

### 📈 Growth & Performance

| Agent | What it does |
|---|---|
| [✍️ Ad Creative Strategist](growth/Ad%20Creative%20Strategist.md) | Turns ad creative into a repeatable science — copywriting, RSA optimization, asset groups, and creative testing across Google, Meta, Microsoft, and programmatic. Use it to lift paid performance through better creative. |
| [📱 App Store Optimizer](growth/App%20Store%20Optimizer.md) | Improves app discoverability and conversion through ASO and store-page optimization. Use it to get your app found and downloaded. |
| [🎭 CRO / Conversion Auditor](growth/CRO%20-%20Conversion%20Auditor.md) | Simulates a persona's cognitive walkthrough of your pages — capturing emotional and rational reactions at each scroll — and delivers CRO reports grounded in LIFT, Cialdini, and Fogg. Use it to see what analytics can't and lift conversion. |
| [🌏 Cross-Border E-Commerce Specialist](growth/Cross-Border%20E-Commerce%20Specialist.md) | A full-funnel cross-border e-commerce strategist — marketplaces (Amazon/Shopee/Lazada/TikTok Shop), logistics, compliance/tax, multilingual listings, and DTC sites. Use it to take products into global markets. |
| [📧 Email Marketing Strategist](growth/Email%20Marketing%20Strategist.md) | Builds CRM-driven email programs — lifecycle automation, segmentation, deliverability, and sequences (welcome/nurture/win-back) with modern personalization. Use it to turn a contact list into an automated revenue engine. |
| [🚀 Growth Hacker](growth/Growth%20Hacker.md) | Finds and scales growth channels through data-driven experimentation — viral loops, funnel optimization, and rapid user acquisition. Use it to unlock scalable growth. |
| [📋 Paid Media Auditor](growth/Paid%20Media%20Auditor.md) | Systematically audits Google, Microsoft, and Meta accounts across 200+ checkpoints (structure, tracking, bidding, creative, audiences) with prioritized, impact-projected fixes. Use it to find and eliminate wasted ad spend. |
| [📱 Paid Social Strategist](growth/Paid%20Social%20Strategist.md) | Designs full-funnel paid social across Meta, LinkedIn, TikTok, Pinterest, X, and Snapchat — prospecting to retargeting with platform-specific creative and audiences. Use it to make paid social work harder. |
| [💰 PPC Campaign Strategist](growth/PPC%20Campaign%20Strategist.md) | Runs large-scale search, shopping, and Performance Max across Google, Microsoft, and Amazon — account architecture, bidding, budgets, and deep search-term/negative-keyword work. Use it to scale paid search while killing waste. |
| [📺 Programmatic & Display Buyer](growth/Programmatic%20%26%20Display%20Buyer.md) | Buys display and video at scale — managed placements, GDN, DV360, trade desks, partner media, and ABM display. Use it for precise programmatic and display media buying. |
| [📡 Tracking & Measurement Specialist](growth/Tracking%20%26%20Measurement%20Specialist.md) | Architects conversion tracking, tag management, and attribution across GTM, GA4, Google/Meta/LinkedIn, and server-side. Use it to make sure every conversion is counted and every ad dollar is measurable. |

### 💼 Sales & Customer

| Agent | What it does |
|---|---|
| [🗺️ Account Strategist](revenue/Account%20Strategist.md) | Drives post-sale land-and-expand — stakeholder mapping, QBRs, whitespace, and net revenue retention. Use it to turn closed deals into growing, multi-threaded accounts. |
| [🎧 Customer Service](revenue/Customer%20Service.md) | Handles inquiries, complaints, account support, FAQs, and escalation with warmth and efficiency, for any industry. Use it for friendly, effective front-line support. |
| [🌟 Customer Success Manager](revenue/Customer%20Success%20Manager.md) | Drives retention and expansion proactively — onboarding, health scoring, QBRs, churn prevention, and renewals. Use it to make customers succeed and stay before problems arise. |
| [♟️ Deal & Proposal Strategist](revenue/Deal%20%26%20Proposal%20Strategist.md) | Wins complex B2B deals end to end — qualification and positioning (MEDDPICC, Challenger, multi-threading) turned into a persuasive proposal. Use it to out-strategize and then close the deal. |
| [🏨 Hospitality Guest Services](revenue/Hospitality%20Guest%20Services.md) | Handles hotel/resort/restaurant guest services — reservations, check-in/out, concierge, complaint resolution, loyalty, and follow-up. Use it to deliver five-star guest experiences that drive loyalty. |
| [🧲 Offer & Lead Gen Strategist](revenue/Offer%20%26%20Lead%20Gen%20Strategist.md) | Designs irresistible offers and lead magnets and the multi-channel engines that distribute them — value-equation construction and compounding reach. Use it to attract qualified buyers at the top of funnel. |
| [🎯 Outbound Strategist](revenue/Outbound%20Strategist.md) | Builds pipeline through signal-based, research-driven outbound — ICPs, multi-channel sequences, objection handling, methodologies, and consultative proposals. Use it for outbound that books meetings on relevance, not volume. |
| [📊 Pipeline Analyst](revenue/Pipeline%20Analyst.md) | Turns CRM data into pipeline intelligence — health diagnostics, deal velocity, forecast accuracy, and data-driven coaching. Use it to surface risks before they become missed quarters. |
| [🛒 Retail Customer Returns](revenue/Retail%20Customer%20Returns.md) | Processes returns, exchanges, and refunds across in-store/online/omnichannel — policy, fraud prevention, retention, and returns analytics. Use it to handle returns fast and fairly while keeping customers. |
| [🏋️ Sales Coach](revenue/Sales%20Coach.md) | Makes every rep and deal better — rep development, pipeline reviews, call coaching, and forecast discipline built on elite discovery methodology (SPIN/Gap/Sandler). Use it to level up sales conversations and execution. |
| [🛠️ Sales Engineer](revenue/Sales%20Engineer.md) | The pre-sales technical lead — discovery, demo engineering, POC scoping, competitive battlecards, and tying product to business outcomes. Use it to win the technical decision so the deal can close. |
| [📊 Sales Reporting & Ops](revenue/Sales%20Reporting%20%26%20Ops.md) | Runs the sales-reporting pipeline — ingests data, extracts MTD/YTD metrics, builds territory/rep/pipeline dashboards, and distributes the right report on schedule. Use it for automated, audited sales reporting. |
| [☁️ Salesforce Architect](revenue/Salesforce%20Architect.md) | Solution architecture for Salesforce — multi-cloud design, integration patterns, governor limits, deployment, and data-model governance for enterprise orgs. Use it to keep a complex Salesforce org scalable and clean. |
| [💬 Support Responder](revenue/Support%20Responder.md) | Delivers multi-channel customer support and proactive care that turns support interactions into positive brand moments. Use it for resolving issues and improving the support experience. |

### 💰 Finance & Law

| Agent | What it does |
|---|---|
| [📊 Controller & FP&A](finance/Controller%20%26%20FP%26A.md) | The run-the-money agent for a lean operation — accurate books (close, reconciliations, controls) plus FP&A (budgets, rolling forecasts, variance, scenarios), dual-standard (US GAAP/IFRS). Use it to close clean and turn numbers into a plan. |
| [📊 Financial Analyst](finance/Financial%20Analyst.md) | Builds financial models, forecasts, and scenario analysis that turn raw data into decision support. Use it for modeling, valuation, and data-driven financial planning. |
| [📝 Grant Writer](finance/Grant%20Writer.md) | Wins non-dilutive business grants — US SBIR/STTR, EU Horizon/EIC, Israel Innovation Authority and more — from opportunity research and proposals to budgets, compliance, and reporting. Use it to fund R&D without giving up equity. |
| [🔍 Investment Researcher](finance/Investment%20Researcher.md) | Conducts rigorous investment research — market analysis, due diligence, valuation, and risk across public equities, private, and alternatives. Use it to evaluate opportunities and support portfolio decisions. |
| [⚖️ Israel Business Law Navigator](finance/Israel%20Business%20Law%20Navigator.md) | A founder's issue-spotting lens on Israeli business law — entities, contracts, employee-protective labor law, IP, the Amendment 13 privacy reform, consumer/anti-spam/accessibility, and fundraising. Not legal advice; tells you what to ask your עורך דין. |
| [🇮🇱 Israel Tax Strategist](finance/Israel%20Tax%20Strategist.md) | A planning lens on Israeli tax — income, corporate, VAT, capital gains, real estate, Section 102 equity, and new-immigrant benefits. Not a filing authority; helps you plan and walk into your accountant prepared. |
| [⚖️ Legal Compliance Checker](finance/Legal%20Compliance%20Checker.md) | Checks that operations, data handling, and content comply with relevant laws and standards (GDPR/CCPA and more) across jurisdictions, and builds privacy policies and DPAs. Use it for the operational privacy/regulatory build-out. |
| [⚖️ Legal Document Review](finance/Legal%20Document%20Review.md) | Reviews contracts, litigation, and real-estate documents — summarizes terms, flags risk clauses, compares versions, and checks compliance. Use it for a thorough first-pass document review (always confirmed by counsel). |
| [🏦 Loan Officer Assistant](finance/Loan%20Officer%20Assistant.md) | Supports mortgage/lending work — borrower intake, pre-qualification, document collection, pipeline, compliance, rate quoting, and closing coordination. Use it to move loans through the pipeline with precision. |
| [💰 Pricing Analyst](finance/Pricing%20Analyst.md) | Develops pricing models through market and competitor analysis, cost structure, and margin optimization. Use it to turn pricing from guesswork into a data-backed advantage. |
| [🏠 Real Estate Buyer & Seller](finance/Real%20Estate%20Buyer%20%26%20Seller.md) | Assists real-estate transactions end to end — buyer/seller representation, listings, offer negotiation, transaction coordination, and closing. Use it to run a client through a property deal smoothly. |
| [⚖️ US Business Law Navigator](finance/US%20Business%20Law%20Navigator.md) | A founder's issue-spotting lens on US business law — entity, contracts, IP, employment, privacy/data, consumer/marketing, fundraising, and regulatory exposure. Not legal advice; tells you what to ask your US attorney. |
| [🇺🇸 US Tax & Accounting Navigator](finance/US%20Tax%20%26%20Accounting%20Navigator.md) | A commercial lens on US tax and accounting for a finance pro new to US rules — decodes how it shapes American buyers' decisions so you sell better and spot opportunities. Not a filing tool; defers actual positions to a US CPA. |

### 🛠️ Operations & People

| Agent | What it does |
|---|---|
| [📊 Analytics Reporter](operations/Analytics%20Reporter.md) | Transforms raw data into actionable insight — dashboards, statistical analysis, KPI tracking, and decision support. Use it for business reporting and data-driven decisions. |
| [🔄 Change Management Consultant](operations/Change%20Management%20Consultant.md) | Guides organizations through change (tech rollouts, restructuring, M&A) using ADKAR, Kotter, and Prosci — managing resistance and building lasting adoption. Use it to make change actually stick. |
| [📚 Corporate Training Designer](operations/Corporate%20Training%20Designer.md) | Designs enterprise training and curricula — needs analysis, instructional design, blended programs, and effectiveness evaluation (to Kirkpatrick L3). Use it to build training that changes behavior. |
| [📄 Document Generator](operations/Document%20Generator.md) | Generates professional PDF, PPTX, DOCX, and XLSX files in code, with proper formatting, charts, and data visualization. Use it to produce polished documents and reports programmatically. |
| [🗂️ Executive Assistant](operations/Executive%20Assistant.md) | The best digital EA — owns your calendar, triages and drafts your inbox, tracks every task and follow-up, preps meetings, and guards your focus. Tool-agnostic, with chief-of-staff depth. Use it to take the admin load off your plate. |
| [📝 Executive Summary Generator](operations/Executive%20Summary%20Generator.md) | Turns complex business inputs into concise, C-suite-ready executive summaries using McKinsey SCQA, Pyramid Principle, and Bain frameworks. Use it to brief decision-makers fast and clearly. |
| [🤝 HR Onboarding](operations/HR%20Onboarding.md) | Runs employee onboarding — orientation, documentation, compliance, benefits, and culture integration — for a seamless first-day-to-first-year. Use it to make new hires productive and retained. |
| [🌐 Language Translator](operations/Language%20Translator.md) | Translates across English, Hebrew, and French (all six directions) — meaning over words, with register/gender awareness, regional variants, cultural notes, and pronunciation. Use it for everyday, business, legal, or emergency translation. |
| [📋 Meeting Notes Specialist](operations/Meeting%20Notes%20Specialist.md) | Extracts decisions, action items, and open questions from transcripts or rough notes into a clean four-section summary. Use it to turn messy meeting notes into structured follow-up, without inventing anything. |
| [🎛️ Operations & Program Manager](operations/Operations%20%26%20Program%20Manager.md) | Runs the operation across multiple projects — portfolio orchestration (resourcing, prioritization, ROI) plus operational excellence (SOPs, process, vendors). Use it when you're running several projects or a small team. |
| [🌱 Personal Growth Mentor](operations/Personal%20Growth%20Mentor.md) | A cross-domain personal-development mentor for goal clarity, habit design, strategic decisions, and accountability — systems over slogans, no motivational fluff. Use it for focused personal growth and execution. |
| [🗂️ Project Manager](operations/Project%20Manager.md) | Delivers a single project end to end — converts specs into realistic developer-ready task lists, then coordinates timelines, dependencies, stakeholders, and risk. Use it for tactical delivery of one project at a time. |

### 🧠 Strategy & Advisory

| Agent | What it does |
|---|---|
| [♟️ Business Strategist](advisory/Business%20Strategist.md) | Senior management-consulting for competitive analysis, market entry, business-model design, and growth — translating market dynamics into actionable strategy. Use it for high-stakes strategic decisions that need a clear plan. |
| [🌍 Cultural Intelligence Strategist](advisory/Cultural%20Intelligence%20Strategist.md) | Detects invisible exclusion in product/copy/imagery AND decodes what things *mean* to a segment (culture, rituals, loyalty, market entry). Use it to make your product and brand resonate instead of misfire. |
| [🇫🇷 French Consulting Market Navigator](advisory/French%20Consulting%20Market%20Navigator.md) | Decodes the French ESN/SI freelance ecosystem — margin models, platforms (Malt, collective.work), portage salarial, and rate positioning. Use it to navigate French consulting and stop leaving money on the table. |
| [🗺️ Geographer](advisory/Geographer.md) | A PhD-level economic & spatial geographer for business — site/location selection, market and trade geography, logistics, and geopolitical/climate risk. The 'where' lens; use it for location and spatial-risk decisions. |
| [📚 Historian](advisory/Historian.md) | A PhD-level business & economic historian — historical precedent, market-cycle (bubble/crash, long-wave) analysis, and case studies, honest about fact vs. analogy. Use it to ask what history actually teaches about a bet. |
| [📜 Narratologist](advisory/Narratologist.md) | A PhD-level narrative theorist for business — applies story-structure frameworks to brand narrative, pitch/deck arcs, founder story, and positioning. Use it to find what your pitch is really arguing and make it land. |
| [🧠 Psychologist](advisory/Psychologist.md) | A PhD-level behavioral & consumer psychologist — personality, cognitive biases, and social psychology applied to motivation, persuasion, personas, and team dynamics, grounded in named theory. Use it to understand why people buy and act. |
| [🔗 Supply Chain Strategist](advisory/Supply%20Chain%20Strategist.md) | A supply-chain and procurement strategist — supplier development, strategic sourcing, quality control, and resilience, grounded in China's manufacturing ecosystem. Use it to build an efficient, resilient procurement engine. |

> **106 agents across 8 divisions.** Activate any agent by name in your AI tool of choice.

## 🎯 Real-World Use Cases

### Scenario 1: Building a Startup MVP

**Your Team**:
1. 🎨 **Frontend Developer** - Build the React app
2. 🏗️ **Backend Architect** - Design the API and database
3. 🚀 **Growth Hacker** - Plan user acquisition
4. ⚡ **Rapid Prototyper** - Fast iteration cycles
5. 🧐 **QA Reality Checker** - Ensure quality before launch

**Result**: Ship faster with specialized expertise at every stage.

---

### Scenario 2: Marketing Campaign Launch

**Your Team**:
1. 📝 **Content Creator** - Develop campaign content
2. 🐦 **Twitter Engager** - Twitter strategy and execution
3. 📸 **Instagram Curator** - Visual content and stories
4. 🤝 **Reddit Community Builder** - Authentic community engagement
5. 📊 **Analytics Reporter** - Track and optimize performance

**Result**: Multi-channel coordinated campaign with platform-specific expertise.

---

### Scenario 3: Enterprise Feature Development

**Your Team**:
1. 👔 **Project Manager** - Scope and task planning
2. 🏛️ **Software Architect** - Complex implementation
3. 🎨 **UI Designer** - Design system and components
4. 🚀 **Growth Hacker** - A/B test planning
5. 🧪 **QA Engineer** - Quality verification
6. 🧐 **QA Reality Checker** - Production readiness

**Result**: Enterprise-grade delivery with quality gates and documentation.

---

### Scenario 4: Paid Media Account Takeover

**Your Team**:

1. 📋 **Paid Media Auditor** - Comprehensive account assessment
2. 📡 **Tracking & Measurement Specialist** - Verify conversion tracking accuracy
3. 💰 **PPC Campaign Strategist** - Redesign account architecture and clean up wasted spend
4. ✍️ **Ad Creative Strategist** - Refresh all ad copy and extensions
5. 📊 **Analytics Reporter** (Operations & People) - Build reporting dashboards

**Result**: Systematic account takeover with tracking verified, waste eliminated, structure optimized, and creative refreshed — all within the first 30 days.

---

### Scenario 5: Full Agency Product Discovery

**Your Team**: All 8 divisions working in parallel on a single mission.

A cross-functional team spanning all 8 divisions — for example **Product & Market Research, Backend Architect, Brand Guardian, Growth Hacker, Support Responder, UX Researcher, Operations & Program Manager, and Business Strategist** — deployed in parallel to evaluate a software opportunity and produce a unified product plan covering market validation, technical architecture, brand strategy, go-to-market, support systems, UX research, and execution.

**Result**: Comprehensive, cross-functional product blueprint produced in a single session. [More examples](examples/).

---

## 🤝 Contributing

We welcome contributions! Here's how you can help:

### Add a New Agent

1. Fork the repository
2. Create a new agent file in the appropriate category
3. Follow the agent template structure:
   - Frontmatter with name, description, color
   - Identity & Memory section
   - Core Mission
   - Critical Rules (domain-specific)
   - Technical Deliverables with examples
   - Workflow Process
   - Success Metrics
4. Submit a PR with your agent

### Improve Existing Agents

- Add real-world examples
- Enhance code samples
- Update success metrics
- Improve workflows

### Share Your Success Stories

Have you used these agents successfully? Share your story in the [Discussions](https://github.com/msitarzewski/agency-agents/discussions)!

---

## 📖 Agent Design Philosophy

Each agent is designed with:

1. **🎭 Strong Personality**: Not generic templates - real character and voice
2. **📋 Clear Deliverables**: Concrete outputs, not vague guidance
3. **✅ Success Metrics**: Measurable outcomes and quality standards
4. **🔄 Proven Workflows**: Step-by-step processes that work
5. **💡 Learning Memory**: Pattern recognition and continuous improvement

---

## 🎁 What Makes This Special?

### Unlike Generic AI Prompts:
- ❌ Generic "Act as a developer" prompts
- ✅ Deep specialization with personality and process

### Unlike Prompt Libraries:
- ❌ One-off prompt collections
- ✅ Comprehensive agent systems with workflows and deliverables

### Unlike AI Tools:
- ❌ Black box tools you can't customize
- ✅ Transparent, forkable, adaptable agent personalities

---

## 🎨 Agent Personality Highlights

> "I don't just test your code - I default to finding 3-5 issues and require visual proof for everything."
>
> -- **QA Reality Checker** (Engineering & AI Division)

> "You're not marketing on Reddit - you're becoming a valued community member who happens to represent a brand."
>
> -- **Reddit Community Builder** (Marketing & Content Division)

> "Every playful element must serve a functional or emotional purpose. Design delight that enhances rather than distracts."
>
> -- **UI Designer** (Product & Design Division)

> "Let me add a celebration animation that reduces task completion anxiety by 40%"
>
> -- **UI Designer** (during a UX review)

---

## 📊 Stats

- 🎭 **106 specialized agents** across 8 divisions
- 📝 **10,000+ lines** of personality, process, and code examples
- ⏱️ **Months of iteration** from real-world usage
- 🌟 **Battle-tested** in production environments
- 💬 **50+ requests** in first 12 hours on Reddit

---

## 🔌 Multi-Tool Integrations

The Agency works natively with Claude Code, and ships conversion + install scripts so you can use the same agents across every major agentic coding tool.

### Supported Tools

- **[Claude Code](https://claude.ai/code)** — native `.md` agents, no conversion needed → `~/.claude/agents/`
- **[GitHub Copilot](https://github.com/copilot)** — native `.md` agents, no conversion needed → `~/.github/agents/` + `~/.copilot/agents/`
- **[Antigravity](https://github.com/google-gemini/antigravity)** — `SKILL.md` per agent → `~/.gemini/antigravity/skills/`
- **[Gemini CLI](https://github.com/google-gemini/gemini-cli)** — extension + `SKILL.md` files → `~/.gemini/extensions/agency-agents/`
- **[OpenCode](https://opencode.ai)** — `.md` agent files → `.opencode/agents/`
- **[Cursor](https://cursor.sh)** — `.mdc` rule files → `.cursor/rules/`
- **[Aider](https://aider.chat)** — single `CONVENTIONS.md` → `./CONVENTIONS.md`
- **[Windsurf](https://codeium.com/windsurf)** — single `.windsurfrules` → `./.windsurfrules`
- **[OpenClaw](https://github.com/openclaw/openclaw)** — `SOUL.md` + `AGENTS.md` + `IDENTITY.md` per agent
- **[Qwen Code](https://github.com/QwenLM/qwen-code)** — `.md` SubAgent files → `~/.qwen/agents/`
- **[Kimi Code](https://github.com/MoonshotAI/kimi-cli)** — YAML agent specs → `~/.config/kimi/agents/`
- **[Codex](https://developers.openai.com/codex/overview)** — TOML custom agents → `~/.codex/agents/`

---

### ⚡ Quick Install

**Step 1 -- Generate integration files:**
```bash
./scripts/convert.sh
# Faster (parallel, output order may vary): ./scripts/convert.sh --parallel
```

**Step 2 -- Install (interactive, auto-detects your tools):**
```bash
./scripts/install.sh
# Faster (parallel, output order may vary): ./scripts/install.sh --no-interactive --parallel
```

The installer scans your system for installed tools, shows a checkbox UI, and lets you pick exactly what to install:

```
  +------------------------------------------------+
  |   The Agency -- Tool Installer                 |
  +------------------------------------------------+

  System scan: [*] = detected on this machine

  [x]  1)  [*]  Claude Code     (claude.ai/code)
  [x]  2)  [*]  Copilot         (~/.github + ~/.copilot)
  [x]  3)  [*]  Antigravity     (~/.gemini/antigravity)
  [ ]  4)  [ ]  Gemini CLI      (~/.gemini/agents)
  [ ]  5)  [ ]  OpenCode        (opencode.ai)
  [ ]  6)  [ ]  OpenClaw        (~/.openclaw/agency-agents)
  [x]  7)  [*]  Cursor          (.cursor/rules)
  [ ]  8)  [ ]  Aider           (CONVENTIONS.md)
  [ ]  9)  [ ]  Windsurf        (.windsurfrules)
  [ ] 10)  [ ]  Qwen Code       (~/.qwen/agents)
  [ ] 11)  [ ]  Kimi Code       (~/.config/kimi/agents)
  [ ] 12)  [ ]  Codex           (~/.codex/agents)

  [1-12] toggle   [a] all   [n] none   [d] detected
  [Enter] install   [q] quit
```

**Or install a specific tool directly:**
```bash
./scripts/install.sh --tool cursor
./scripts/install.sh --tool opencode
./scripts/install.sh --tool openclaw
./scripts/install.sh --tool antigravity
./scripts/install.sh --tool codex
```

**Non-interactive (CI/scripts):**
```bash
./scripts/install.sh --no-interactive --tool all
```

**Faster runs (parallel)** — On multi-core machines, use `--parallel` so each tool is processed in parallel. Output order across tools is non-deterministic. Works with both interactive and non-interactive install: e.g. `./scripts/install.sh --interactive --parallel` (pick tools, then install in parallel) or `./scripts/install.sh --no-interactive --parallel`. Job count defaults to `nproc` (Linux), `sysctl -n hw.ncpu` (macOS), or 4; override with `--jobs N`.

```bash
./scripts/convert.sh --parallel                    # convert all tools in parallel
./scripts/convert.sh --parallel --jobs 8           # cap parallel jobs
./scripts/install.sh --no-interactive --parallel   # install all detected tools in parallel
./scripts/install.sh --interactive --parallel      # pick tools, then install in parallel
./scripts/install.sh --no-interactive --parallel --jobs 4
```

---

### Tool-Specific Instructions

<details>
<summary><strong>Claude Code</strong></summary>

Agents are copied directly from the repo into `~/.claude/agents/` -- no conversion needed.

```bash
./scripts/install.sh --tool claude-code
```

Then activate in Claude Code:
```
Use the Frontend Developer agent to review this component.
```

See [integrations/claude-code/README.md](integrations/claude-code/README.md) for details.
</details>

<details>
<summary><strong>GitHub Copilot</strong></summary>

Agents are copied directly from the repo into `~/.github/agents/` and `~/.copilot/agents/` -- no conversion needed.

```bash
./scripts/install.sh --tool copilot
```

Then activate in GitHub Copilot:
```
Use the Frontend Developer agent to review this component.
```

See [integrations/github-copilot/README.md](integrations/github-copilot/README.md) for details.
</details>

<details>
<summary><strong>Antigravity (Gemini)</strong></summary>

Each agent becomes a skill in `~/.gemini/antigravity/skills/agency-<slug>/`.

```bash
./scripts/install.sh --tool antigravity
```

Activate in Gemini with Antigravity:
```
@agency-frontend-developer review this React component
```

See [integrations/antigravity/README.md](integrations/antigravity/README.md) for details.
</details>

<details>
<summary><strong>Gemini CLI</strong></summary>

Installs as Gemini CLI subagents.
On a fresh clone, generate the Gemini agent files before running the installer.

```bash
./scripts/convert.sh --tool gemini-cli
./scripts/install.sh --tool gemini-cli
```

See [integrations/gemini-cli/README.md](integrations/gemini-cli/README.md) for details.
</details>

<details>
<summary><strong>OpenCode</strong></summary>

Agents are placed in `.opencode/agents/` in your project root (project-scoped).

```bash
cd /your/project
/path/to/agency-agents/scripts/install.sh --tool opencode
```

Or install globally:
```bash
mkdir -p ~/.config/opencode/agents
cp integrations/opencode/agents/*.md ~/.config/opencode/agents/
```

Activate in OpenCode:
```
@backend-architect design this API.
```

See [integrations/opencode/README.md](integrations/opencode/README.md) for details.
</details>

<details>
<summary><strong>Cursor</strong></summary>

Each agent becomes a `.mdc` rule file in `.cursor/rules/` of your project.

```bash
cd /your/project
/path/to/agency-agents/scripts/install.sh --tool cursor
```

Rules are auto-applied when Cursor detects them in the project. Reference them explicitly:
```
Use the @security-engineer rules to review this code.
```

See [integrations/cursor/README.md](integrations/cursor/README.md) for details.
</details>

<details>
<summary><strong>Aider</strong></summary>

All agents are compiled into a single `CONVENTIONS.md` file that Aider reads automatically.

```bash
cd /your/project
/path/to/agency-agents/scripts/install.sh --tool aider
```

Then reference agents in your Aider session:
```
Use the Frontend Developer agent to refactor this component.
```

See [integrations/aider/README.md](integrations/aider/README.md) for details.
</details>

<details>
<summary><strong>Windsurf</strong></summary>

All agents are compiled into `.windsurfrules` in your project root.

```bash
cd /your/project
/path/to/agency-agents/scripts/install.sh --tool windsurf
```

Reference agents in Windsurf's Cascade:
```
Use the QA Reality Checker agent to verify this is production ready.
```

See [integrations/windsurf/README.md](integrations/windsurf/README.md) for details.
</details>

<details>
<summary><strong>OpenClaw</strong></summary>

Each agent becomes a workspace with `SOUL.md`, `AGENTS.md`, and `IDENTITY.md` in `~/.openclaw/agency-agents/`.

```bash
./scripts/convert.sh --tool openclaw
./scripts/install.sh --tool openclaw
```

If the `openclaw` CLI is available, the installer registers each workspace automatically.
Run `openclaw gateway restart` after installation so the new agents are activated.

See [integrations/openclaw/README.md](integrations/openclaw/README.md) for details.

</details>

<details>
<summary><strong>Qwen Code</strong></summary>

SubAgents are installed to `.qwen/agents/` in your project root (project-scoped).

```bash
# Convert and install (run from your project root)
cd /your/project
./scripts/convert.sh --tool qwen
./scripts/install.sh --tool qwen
```

**Usage in Qwen Code:**
- Reference by name: `Use the frontend-developer agent to review this component`
- Or let Qwen auto-delegate based on task context
- Manage via `/agents` command in interactive mode

> 📚 [Qwen SubAgents Docs](https://qwenlm.github.io/qwen-code-docs/en/users/features/sub-agents/)

</details>

<details>
<summary><strong>Kimi Code</strong></summary>

Agents are converted to Kimi Code CLI format (YAML + system prompt) and installed to `~/.config/kimi/agents/`.

```bash
# Convert and install
./scripts/convert.sh --tool kimi
./scripts/install.sh --tool kimi
```

**Usage with Kimi Code:**
```bash
# Use an agent
kimi --agent-file ~/.config/kimi/agents/frontend-developer/agent.yaml

# In a project
kimi --agent-file ~/.config/kimi/agents/frontend-developer/agent.yaml \
     --work-dir /your/project \
     "Review this React component"
```

See [integrations/kimi/README.md](integrations/kimi/README.md) for details.

</details>

<details>
<summary><strong>Codex</strong></summary>

Each agent is converted into a Codex custom agent TOML file and installed to `~/.codex/agents/`.

```bash
./scripts/convert.sh --tool codex
./scripts/install.sh --tool codex
```

Then reference the custom agent by name in Codex:
```
Use the Frontend Developer agent to review this component.
```

See [integrations/codex/README.md](integrations/codex/README.md) for details.
</details>

---

### Regenerating After Changes

When you add new agents or edit existing ones, regenerate all integration files:

```bash
./scripts/convert.sh                    # regenerate all (serial)
./scripts/convert.sh --parallel         # regenerate all in parallel (faster)
./scripts/convert.sh --tool codex       # regenerate just one tool
./scripts/convert.sh --tool cursor      # regenerate just one tool
```

---

## 🗺️ Roadmap

- [ ] Interactive agent selector web tool
- [x] Multi-agent workflow examples -- see [examples/](examples/)
- [x] Multi-tool integration scripts (Claude Code, GitHub Copilot, Antigravity, Gemini CLI, OpenCode, OpenClaw, Cursor, Aider, Windsurf, Qwen Code, Kimi Code, Codex)
- [ ] Video tutorials on agent design
- [ ] Community agent marketplace
- [ ] Agent "personality quiz" for project matching
- [ ] "Agent of the Week" showcase series

---

## 🌐 Community Translations & Localizations

Community-maintained translations and regional adaptations. These are independently maintained -- see each repo for coverage and version compatibility.

| Language | Maintainer | Link | Notes |
|----------|-----------|------|-------|
| 🇨🇳 简体中文 (zh-CN) | [@jnMetaCode](https://github.com/jnMetaCode) | [agency-agents-zh](https://github.com/jnMetaCode/agency-agents-zh) | 141 translated agents + 46 China-market originals |
| 🇨🇳 简体中文 (zh-CN) | [@dsclca12](https://github.com/dsclca12) | [agent-teams](https://github.com/dsclca12/agent-teams) | Independent translation with Bilibili, WeChat, Xiaohongshu localization |
| 🇧🇷 Português brasileiro (pt-BR) | [@jnMetaCode](https://github.com/jnMetaCode) | [agency-agents-pt-BR](https://github.com/jnMetaCode/agency-agents-pt-BR) | 184 upstream agents translated; Brazil-market PRs welcome |
| 🇷🇺 Русский (ru) | [@jnMetaCode](https://github.com/jnMetaCode) | [agency-agents-ru](https://github.com/jnMetaCode/agency-agents-ru) | 184 upstream agents translated; Russia-market PRs welcome |
| 🇮🇩 Bahasa Indonesia (id) | [@jnMetaCode](https://github.com/jnMetaCode) | [agency-agents-id](https://github.com/jnMetaCode/agency-agents-id) | 184 upstream agents translated; Indonesia-market PRs welcome |
| 🇸🇦 العربية (ar) | [@jnMetaCode](https://github.com/jnMetaCode) | [agency-agents-ar](https://github.com/jnMetaCode/agency-agents-ar) | 184 upstream agents translated; Arabic-market PRs welcome |
| 🇰🇷 한국어 (ko) | [@jnMetaCode](https://github.com/jnMetaCode) | [agency-agents-ko](https://github.com/jnMetaCode/agency-agents-ko) | 184 upstream agents fully translated; Korea-specific PRs welcome |
| 🇯🇵 日本語 (ja-JP) | [@sscodeai](https://github.com/sscodeai) | [agency-agents-ja](https://github.com/sscodeai/agency-agents-ja) | 281 Japan-localized agents + 97 Japan-market originals + 27 workflows |

Want to add a translation? Open an issue and we'll link it here.

---

## 🔗 Related Resources

- [awesome-openclaw-agents](https://github.com/mergisi/awesome-openclaw-agents) — Community-maintained OpenClaw agent collection (derived from this repo)

---

## 📜 License

MIT License - Use freely, commercially or personally. Attribution appreciated but not required.

---

## 🙏 Acknowledgments

What started as a Reddit thread about AI agent specialization has grown into something remarkable — **106 agents across 8 divisions**, supported by a community of contributors from around the world. Every agent in this repo exists because someone cared enough to write it, test it, and share it.

To everyone who has opened a PR, filed an issue, started a Discussion, or simply tried an agent and told us what worked — thank you. You're the reason The Agency keeps getting better.

---

## 💬 Community

- **GitHub Discussions**: [Share your success stories](https://github.com/msitarzewski/agency-agents/discussions)
- **Issues**: [Report bugs or request features](https://github.com/msitarzewski/agency-agents/issues)
- **Reddit**: Join the conversation on r/ClaudeAI
- **Twitter/X**: Share with #TheAgency

---

## 🚀 Get Started

1. **Browse** the agents above and find specialists for your needs
2. **Copy** the agents to `~/.claude/agents/` for Claude Code integration
3. **Activate** agents by referencing them in your Claude conversations
4. **Customize** agent personalities and workflows for your specific needs
5. **Share** your results and contribute back to the community

---

<div align="center">

**🎭 The Agency: Your AI Dream Team Awaits 🎭**

[⭐ Star this repo](https://github.com/msitarzewski/agency-agents) • [🍴 Fork it](https://github.com/msitarzewski/agency-agents/fork) • [🐛 Report an issue](https://github.com/msitarzewski/agency-agents/issues) • [❤️ Sponsor](https://github.com/sponsors/msitarzewski)

Made with ❤️ by the community, for the community

</div>
