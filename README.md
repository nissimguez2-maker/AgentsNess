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
| [🎛️ Agent & Workflow Orchestrator](engineering/Agent%20%26%20Workflow%20Orchestrator.md) | Designs the workflow before it's built and orchestrates the agents that build it. Maps every path through a system — happy paths, branches, failure… |
| [🔐 Agent Identity & Trust](engineering/Agent%20Identity%20%26%20Trust.md) | Owns both layers of identity in a multi-agent system. Layer 1 — agent identity & trust: cryptographic identity, authentication, scoped delegation… |
| [🤖 AI Engineer](engineering/AI%20Engineer.md) | Expert AI/ML engineer specializing in machine learning model development, deployment, and integration into production systems. Focused on building… |
| [🔌 API Tester](engineering/API%20Tester.md) | Expert API testing specialist focused on comprehensive API validation, performance testing, and quality assurance across all systems and third-party… |
| [⚙️ Automation Governance Architect](engineering/Automation%20Governance%20Architect.md) | Governance-first architect for business automations (n8n-first) who audits value, risk, and maintainability before implementation. |
| [🏗️ Backend Architect](engineering/Backend%20Architect.md) | Senior backend architect specializing in scalable system design, database architecture with query and performance tuning, API development, and cloud… |
| [🧱 CMS Developer](engineering/CMS%20Developer.md) | Drupal and WordPress specialist for theme development, custom plugins/modules, content architecture, and code-first CMS implementation |
| [👁️ Code Reviewer & Quality](engineering/Code%20Reviewer%20%26%20Quality.md) | Reviews code for correctness, security, maintainability, and performance; makes surgical minimum-viable changes that refuse scope creep; and explains… |
| [📋 Compliance Auditor](engineering/Compliance%20Auditor.md) | Expert technical compliance auditor specializing in SOC 2, ISO 27001, HIPAA, and PCI-DSS audits — from readiness assessment through evidence… |
| [🔧 Data Engineer](engineering/Data%20Engineer.md) | Expert data engineer specializing in building reliable data pipelines, lakehouse architectures, and scalable data infrastructure. Masters ETL/ELT,… |
| [🚀 DevOps & Reliability Engineer](engineering/DevOps%20%26%20Reliability%20Engineer.md) | Ships and runs your app end to end — CI/CD and deploys, infrastructure-as-code, observability and SLOs, incident command and post-mortems, on-call,… |
| [📧 Email Intelligence Engineer](engineering/Email%20Intelligence%20Engineer.md) | Expert in extracting structured, reasoning-ready data from raw email threads for AI agents and automation systems |
| [🖥️ Frontend Developer](engineering/Frontend%20Developer.md) | Expert frontend developer specializing in modern web technologies, React/Vue/Angular frameworks, UI implementation, and performance optimization |
| [🔌 MCP Builder](engineering/MCP%20Builder.md) | Expert Model Context Protocol developer who designs, builds, and tests MCP servers that extend AI agent capabilities with custom tools, resources,… |
| [📲 Mobile App Builder](engineering/Mobile%20App%20Builder.md) | Specialized mobile application developer with expertise in native iOS/Android development and cross-platform frameworks |
| [🧬 Prompt Engineer](engineering/Prompt%20Engineer.md) | Specialist in crafting, testing, and systematically optimizing prompts for LLMs — turning vague instructions into reliable, production-grade AI… |
| [🧪 QA Engineer](engineering/QA%20Engineer.md) | Hands-on QA across performance (load/stress testing, Core Web Vitals), accessibility (WCAG 2.2 AA, assistive-tech), and test-results/quality analysis… |
| [🧐 QA Reality Checker](engineering/QA%20Reality%20Checker.md) | Skeptical, evidence-obsessed QA gate that stops fantasy approvals — demands visual/recorded proof for every claim, defaults to "NEEDS WORK,"… |
| [⚡ Rapid Prototyper](engineering/Rapid%20Prototyper.md) | Specialized in ultra-fast proof-of-concept development and MVP creation using efficient tools and frameworks |
| [🔒 Security Engineer](engineering/Security%20Engineer.md) | Expert application security engineer specializing in threat modeling, vulnerability assessment, secure code review, security architecture design,… |
| [⛓️ Smart Contract Engineer & Security Auditor](engineering/Smart%20Contract%20Engineer%20%26%20Security%20Auditor.md) | Expert Solidity/EVM smart contract engineer and security auditor — builds gas-optimized, upgradeable, security-first contracts and DeFi protocols,… |
| [🏛️ Software Architect](engineering/Software%20Architect.md) | Expert software architect specializing in system design, domain-driven design, architectural patterns, and technical decision-making for scalable,… |
| [📚 Technical Writer](engineering/Technical%20Writer.md) | Expert technical writer specializing in developer documentation, API references, README files, and tutorials. Transforms complex engineering concepts… |
| [🎙️ Voice AI Integration Engineer](engineering/Voice%20AI%20Integration%20Engineer.md) | Expert in building end-to-end speech transcription pipelines using Whisper-style models and cloud ASR services — from raw audio ingestion through… |
| [🗃️ ZK Steward](engineering/ZK%20Steward.md) | Knowledge-base steward in the spirit of Niklas Luhmann's Zettelkasten. Default perspective: Luhmann; switches to domain experts (Feynman, Munger,… |

### 🎨 Product & Design

| Agent | What it does |
|---|---|
| [🖼️ AI Visual Generation Specialist](product/AI%20Visual%20Generation%20Specialist.md) | Expert AI image and video generation specialist who turns visual concepts into precise, structured prompts for professional-quality output across… |
| [🧠 Behavioral Engagement & Retention Designer](product/Behavioral%20Engagement%20%26%20Retention%20Designer.md) | Behavioral-science specialist who designs the in-product interactions, nudges, and cadences that drive activation, engagement, habit formation, and… |
| [🎨 Brand Guardian](product/Brand%20Guardian.md) | Expert brand strategist and guardian specializing in brand identity development, consistency maintenance, and strategic brand positioning |
| [🔭 Product & Market Research](product/Product%20%26%20Market%20Research.md) | Research & insights engine combining outside-in market intelligence (emerging trends, competitive analysis, opportunity sizing, tech scouting) with… |
| [🧭 Product Manager](product/Product%20Manager.md) | Holistic product leader who owns the full product lifecycle — from discovery and strategy through prioritization (RICE/MoSCoW/Kano), roadmap, sprint… |
| [🎨 UI Designer](product/UI%20Designer.md) | Expert UI designer specializing in visual design systems, component libraries, and pixel-perfect interface creation. Creates beautiful, consistent,… |
| [📐 UX Architect](product/UX%20Architect.md) | Technical architecture and UX specialist who provides developers with solid foundations, CSS systems, and clear implementation guidance |
| [🔬 UX Researcher](product/UX%20Researcher.md) | Expert user experience researcher specializing in user behavior analysis, usability testing, and data-driven design insights. Provides actionable… |
| [🎬 Visual Storyteller](product/Visual%20Storyteller.md) | Expert visual communication specialist focused on creating compelling visual narratives, multimedia content, and brand storytelling through design.… |

### 📢 Marketing & Content

| Agent | What it does |
|---|---|
| [🔮 AI Search & Answer-Engine Optimizer](marketing/AI%20Search%20%26%20Answer-Engine%20Optimizer.md) | End-to-end AEO/GEO specialist across the three waves of AI-driven traffic — Foundations (AI-crawler access, llms.txt, parseability, schema),… |
| [🎠 Carousel Growth Engine](marketing/Carousel%20Growth%20Engine.md) | Autonomous TikTok and Instagram carousel generation specialist. Analyzes any website URL with Playwright, generates viral 6-slide carousels via… |
| [✍️ Content Creator](marketing/Content%20Creator.md) | Expert content strategist and creator for multi-platform campaigns. Develops editorial calendars, creates compelling copy, manages brand… |
| [🎙️ Global Podcast Strategist](marketing/Global%20Podcast%20Strategist.md) | Expert podcast growth specialist focused on show positioning, audience development, content strategy, and monetisation. Transforms raw ideas into… |
| [📸 Instagram Curator](marketing/Instagram%20Curator.md) | Expert Instagram marketing specialist focused on visual storytelling, community building, and multi-format content optimization. Masters aesthetic… |
| [💼 LinkedIn Content Creator](marketing/LinkedIn%20Content%20Creator.md) | Expert LinkedIn content strategist focused on thought leadership, personal brand building, and high-engagement professional content. Masters… |
| [📣 PR & Communications Manager](marketing/PR%20%26%20Communications%20Manager.md) | Strategic public relations and communications specialist for media relations, press releases, crisis communications, executive thought leadership,… |
| [💬 Reddit Community Builder](marketing/Reddit%20Community%20Builder.md) | Expert Reddit marketing specialist focused on authentic community engagement, value-driven content creation, and long-term relationship building.… |
| [🔍 SEO Specialist](marketing/SEO%20Specialist.md) | Expert search engine optimization strategist specializing in technical SEO, content optimization, link authority building, and organic search growth.… |
| [🎬 Short-Video Editing Coach](marketing/Short-Video%20Editing%20Coach.md) | Hands-on short-video editing coach covering the full post-production pipeline, with mastery of CapCut Pro, Premiere Pro, DaVinci Resolve, and Final… |
| [📣 Social Media Strategist](marketing/Social%20Media%20Strategist.md) | Expert social media strategist for LinkedIn, Twitter, and professional platforms. Creates cross-platform campaigns, builds communities, manages… |
| [🎵 TikTok Strategist](marketing/TikTok%20Strategist.md) | Expert TikTok marketing specialist focused on viral content creation, algorithm optimization, and community building. Masters TikTok's unique culture… |
| [🎬 Video Optimization Specialist](marketing/Video%20Optimization%20Specialist.md) | Video marketing strategist specializing in YouTube algorithm optimization, audience retention, chaptering, thumbnail concepts, and cross-platform… |
| [🐦 X/Twitter Strategist](marketing/X-Twitter%20Strategist.md) | Full X/Twitter operator — builds presence (real-time engagement, thought-leadership threads, Spaces, community growth, crisis response) AND reads the… |

### 📈 Growth & Performance

| Agent | What it does |
|---|---|
| [✍️ Ad Creative Strategist](growth/Ad%20Creative%20Strategist.md) | Paid media creative specialist focused on ad copywriting, RSA optimization, asset group design, and creative testing frameworks across Google, Meta,… |
| [📱 App Store Optimizer](growth/App%20Store%20Optimizer.md) | Expert app store marketing specialist focused on App Store Optimization (ASO), conversion rate optimization, and app discoverability |
| [🎭 CRO / Conversion Auditor](growth/CRO%20-%20Conversion%20Auditor.md) | Conversion-rate-optimization (CRO) auditor that simulates cognitive walkthroughs of web pages from a defined persona's perspective — capturing… |
| [🌏 Cross-Border E-Commerce Specialist](growth/Cross-Border%20E-Commerce%20Specialist.md) | Full-funnel cross-border e-commerce strategist covering Amazon, Shopee, Lazada, AliExpress, Temu, and TikTok Shop operations, international logistics… |
| [📧 Email Marketing Strategist](growth/Email%20Marketing%20Strategist.md) | Expert email marketing strategist for CRM-driven campaigns, lifecycle automation, segmentation architecture, and deliverability. Designs sequences… |
| [🚀 Growth Hacker](growth/Growth%20Hacker.md) | Expert growth strategist specializing in rapid user acquisition through data-driven experimentation. Develops viral loops, optimizes conversion… |
| [📋 Paid Media Auditor](growth/Paid%20Media%20Auditor.md) | Comprehensive paid media auditor who systematically evaluates Google Ads, Microsoft Ads, and Meta accounts across 200+ checkpoints spanning account… |
| [📱 Paid Social Strategist](growth/Paid%20Social%20Strategist.md) | Cross-platform paid social advertising specialist covering Meta (Facebook/Instagram), LinkedIn, TikTok, Pinterest, X, and Snapchat. Designs… |
| [💰 PPC Campaign Strategist](growth/PPC%20Campaign%20Strategist.md) | Senior paid-search strategist for large-scale search, shopping, and Performance Max campaigns across Google, Microsoft, and Amazon — covering account… |
| [📺 Programmatic & Display Buyer](growth/Programmatic%20%26%20Display%20Buyer.md) | Display advertising and programmatic media buying specialist covering managed placements, Google Display Network, DV360, trade desk platforms,… |
| [📡 Tracking & Measurement Specialist](growth/Tracking%20%26%20Measurement%20Specialist.md) | Expert in conversion tracking architecture, tag management, and attribution modeling across Google Tag Manager, GA4, Google Ads, Meta CAPI, LinkedIn… |

### 💼 Sales & Customer

| Agent | What it does |
|---|---|
| [🗺️ Account Strategist](revenue/Account%20Strategist.md) | Expert post-sale account strategist specializing in land-and-expand execution, stakeholder mapping, QBR facilitation, and net revenue retention.… |
| [🎧 Customer Service](revenue/Customer%20Service.md) | Friendly, professional customer service specialist for any industry — handling inquiries, complaints, account support, FAQs, and seamless escalation… |
| [🌟 Customer Success Manager](revenue/Customer%20Success%20Manager.md) | Strategic customer success specialist for onboarding, health scoring, QBR facilitation, churn prevention, expansion identification, and renewal… |
| [♟️ Deal & Proposal Strategist](revenue/Deal%20%26%20Proposal%20Strategist.md) | Wins complex B2B deals end to end — qualifies and out-strategizes the opportunity (MEDDPICC, competitive positioning, Challenger commercial teaching,… |
| [🏨 Hospitality Guest Services](revenue/Hospitality%20Guest%20Services.md) | Comprehensive hospitality guest services specialist for hotels, resorts, restaurants, and event venues — covering reservations, check-in/check-out,… |
| [🧲 Offer & Lead Gen Strategist](revenue/Offer%20%26%20Lead%20Gen%20Strategist.md) | Top-of-funnel architect who designs irresistible offers and lead magnets that attract qualified buyers at scale. Specializes in value-equation offer… |
| [🎯 Outbound Strategist](revenue/Outbound%20Strategist.md) | Signal-based outbound specialist who designs multi-channel prospecting sequences, defines ICPs, and builds pipeline through research-driven… |
| [📊 Pipeline Analyst](revenue/Pipeline%20Analyst.md) | Revenue operations analyst specializing in pipeline health diagnostics, deal velocity analysis, forecast accuracy, and data-driven sales coaching.… |
| [🛒 Retail Customer Returns](revenue/Retail%20Customer%20Returns.md) | Comprehensive retail customer returns specialist for processing returns, exchanges, and refunds across in-store, online, and omnichannel retail —… |
| [🏋️ Sales Coach](revenue/Sales%20Coach.md) | Sales coaching specialist who makes every rep and every deal better — rep development, pipeline review facilitation, call coaching, forecast… |
| [🛠️ Sales Engineer](revenue/Sales%20Engineer.md) | Senior pre-sales engineer specializing in technical discovery, demo engineering, POC scoping, competitive battlecards, and bridging product… |
| [📊 Sales Reporting & Ops](revenue/Sales%20Reporting%20%26%20Ops.md) | Runs the sales-reporting pipeline end to end — ingests sales data from spreadsheets/sources, extracts and normalizes key metrics (MTD, YTD,… |
| [☁️ Salesforce Architect](revenue/Salesforce%20Architect.md) | Solution architecture for Salesforce platform — multi-cloud design, integration patterns, governor limits, deployment strategy, and data model… |
| [💬 Support Responder](revenue/Support%20Responder.md) | Expert customer support specialist delivering exceptional customer service, issue resolution, and user experience optimization. Specializes in… |

### 💰 Finance & Law

| Agent | What it does |
|---|---|
| [📊 Controller & FP&A](finance/Controller%20%26%20FP%26A.md) | The "run-the-money" finance agent for a small/lean operation — combines the controller's accurate books (day-to-day accounting, month-end close,… |
| [📊 Financial Analyst](finance/Financial%20Analyst.md) | Expert financial analyst specializing in financial modeling, forecasting, scenario analysis, and data-driven decision support. Transforms raw… |
| [📝 Grant Writer](finance/Grant%20Writer.md) | Business grant specialist for companies seeking non-dilutive funding — R&D, innovation, and government grants across the US (SBIR/STTR), EU (Horizon… |
| [🔍 Investment Researcher](finance/Investment%20Researcher.md) | Expert investment researcher specializing in market research, due diligence, portfolio analysis, and asset valuation. Conducts rigorous fundamental… |
| [⚖️ Israel Business Law Navigator](finance/Israel%20Business%20Law%20Navigator.md) | A planning and issue-spotting lens on Israeli business law for a founder running their own Israeli venture — entity & formation, contracts… |
| [🇮🇱 Israel Tax Strategist](finance/Israel%20Tax%20Strategist.md) | Planning & strategy assistant for the Israeli tax system — income, corporate, VAT, capital gains, real estate (mas shevach/rechisha), equity comp… |
| [⚖️ Legal Compliance Checker](finance/Legal%20Compliance%20Checker.md) | Expert legal and compliance specialist ensuring business operations, data handling, and content creation comply with relevant laws, regulations, and… |
| [⚖️ Legal Document Review](finance/Legal%20Document%20Review.md) | Comprehensive legal document review specialist for contracts, litigation documents, and real estate agreements — summarizing documents, flagging risk… |
| [🏦 Loan Officer Assistant](finance/Loan%20Officer%20Assistant.md) | Comprehensive loan officer assistant for mortgage and lending professionals — covering borrower intake, pre-qualification, document collection,… |
| [💰 Pricing Analyst](finance/Pricing%20Analyst.md) | Specialized pricing analyst who develops optimal pricing models through market research, competitor analysis, cost structure evaluation, and margin… |
| [🏠 Real Estate Buyer & Seller](finance/Real%20Estate%20Buyer%20%26%20Seller.md) | Comprehensive real estate agent assistant for buyer representation, seller representation, listing management, offer negotiation, transaction… |
| [⚖️ US Business Law Navigator](finance/US%20Business%20Law%20Navigator.md) | A planning and issue-spotting lens on the US business-law landscape for a founder — entity & formation, contracts, IP, employment/contractors,… |
| [🇺🇸 US Tax & Accounting Navigator](finance/US%20Tax%20%26%20Accounting%20Navigator.md) | A commercial-strategy lens on the US tax, accounting, and business-finance landscape — built for a finance/bizdev professional who is fluent in… |

### 🛠️ Operations & People

| Agent | What it does |
|---|---|
| [📊 Analytics Reporter](operations/Analytics%20Reporter.md) | Expert data analyst transforming raw data into actionable business insights. Creates dashboards, performs statistical analysis, tracks KPIs, and… |
| [🔄 Change Management Consultant](operations/Change%20Management%20Consultant.md) | Expert change management specialist using ADKAR, Kotter, and Prosci frameworks to guide organizations through technology implementations,… |
| [📚 Corporate Training Designer](operations/Corporate%20Training%20Designer.md) | Expert in enterprise training system design and curriculum development — proficient in training needs analysis, instructional design methodology,… |
| [📄 Document Generator](operations/Document%20Generator.md) | Expert document creation specialist who generates professional PDF, PPTX, DOCX, and XLSX files using code-based approaches with proper formatting,… |
| [🗂️ Executive Assistant](operations/Executive%20Assistant.md) | The best digital executive assistant — owns your calendar, runs your inbox and communications (triage + drafting), tracks every task and follow-up so… |
| [📝 Executive Summary Generator](operations/Executive%20Summary%20Generator.md) | Consultant-grade AI specialist trained to think and communicate like a senior strategy consultant. Transforms complex business inputs into concise,… |
| [🤝 HR Onboarding](operations/HR%20Onboarding.md) | Comprehensive HR onboarding specialist for employee orientation, documentation management, compliance tracking, benefits enrollment, culture… |
| [🌐 Language Translator](operations/Language%20Translator.md) | Translation specialist across English, Hebrew, and French — all six directions (EN↔HE, EN↔FR, HE↔FR) — transferring meaning rather than words, with… |
| [📋 Meeting Notes Specialist](operations/Meeting%20Notes%20Specialist.md) | Extract structured decisions, action items, and open questions from meeting transcripts or rough notes into a clean 4-section summary. |
| [🎛️ Operations & Program Manager](operations/Operations%20%26%20Program%20Manager.md) | Runs the operation across multiple projects — strategic portfolio orchestration (resource allocation, prioritization, ROI across initiatives) plus… |
| [🌱 Personal Growth Mentor](operations/Personal%20Growth%20Mentor.md) | Cross-domain personal development mentor for goal clarity, habit design, strategic decisions, and accountability without motivational fluff. |
| [🗂️ Project Manager](operations/Project%20Manager.md) | Delivers a single project end to end — converts specs into realistic, developer-ready task lists (no gold-plating), then coordinates cross-functional… |

### 🧠 Strategy & Advisory

| Agent | What it does |
|---|---|
| [♟️ Business Strategist](advisory/Business%20Strategist.md) | Senior management consulting specialist for competitive analysis, market entry strategy, business model design, growth planning, organizational… |
| [🌍 Cultural Intelligence Strategist](advisory/Cultural%20Intelligence%20Strategist.md) | Cultural intelligence (CQ) specialist for product, brand, and market. Two complementary jobs — (1) detect invisible exclusion and ensure software,… |
| [🇫🇷 French Consulting Market Navigator](advisory/French%20Consulting%20Market%20Navigator.md) | Navigate the French ESN/SI freelance ecosystem — margin models, platform mechanics (Malt, collective.work), portage salarial, rate positioning, and… |
| [🗺️ Geographer](advisory/Geographer.md) | PhD-level economic & spatial geographer as a business consultant — applies central-place theory, world-systems, geopolitics, urban geography, and… |
| [📚 Historian](advisory/Historian.md) | PhD-level business & economic historian as a consultant — applies historiographic rigor, market-cycle analysis, comparative and counterfactual… |
| [📜 Narratologist](advisory/Narratologist.md) | PhD-level narrative theorist as a business consultant — applies story-structure frameworks (Propp, Campbell/Vogler, three-act, kishōtenketsu,… |
| [🧠 Psychologist](advisory/Psychologist.md) | PhD-level behavioral & consumer psychologist as a consultant — applies personality theory (Big Five), attachment, cognitive biases (CBT/behavioral… |
| [🔗 Supply Chain Strategist](advisory/Supply%20Chain%20Strategist.md) | Expert supply chain management and procurement strategy specialist — skilled in supplier development, strategic sourcing, quality control, and supply… |

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
