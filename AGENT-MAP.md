# Agent Routing Map — START HERE when no agent is named

When the user gives a task **without naming a specific agent**, use this map to pick the right one(s) before doing anything else:
1. Find the task in the **Routing cheatsheet** (or match it to a **division**).
2. Activate the **lead** agent; add the **pairings** if the task spans their areas.
3. If it touches **3+ divisions or is a full build/launch**, don't pick à la carte — hand it to the **Agent & Workflow Orchestrator** and run the NEXUS pipeline (see `CLAUDE.md` / `strategy/nexus-playbook.md`).
4. Code changes always add **Code Reviewer & Quality**; auth/data/attack-surface always adds **Security Engineer**; "is it really done?" always ends at **QA Reality Checker**.

> All 109 agent descriptions are already loaded in context — this map is the fast index; confirm the exact pick against the agent's own description.

## Divisions (coarse routing)
| Division | Reach for it when the task is about… |
|---|---|
| **Engineering & AI** | building, shipping, testing, securing software / AI / agents / automation |
| **Product & Design** | what to build, UX, UI, brand, visuals |
| **Marketing & Content** | organic content, social, SEO/AEO, PR, video/podcast |
| **Growth & Performance** | paid media, CRO, email, acquisition, tracking |
| **Sales & Customer** | selling, proposals, support, success, retention |
| **Finance & Law** | money, modeling, pricing, tax, legal, compliance |
| **Operations & People** | projects, ops, HR, admin, BI/reporting, docs |
| **Strategy & Advisory** | positioning, deep cross-domain expert lenses |

## Routing cheatsheet (task → lead → pair with)
| If the ask is about… | Start with | Often pair with |
|---|---|---|
| Design/scale a backend, API, DB | Backend Architect | Security Engineer · Data Engineer · DevOps & Reliability |
| Build a web frontend / UI | Frontend Developer | UI Designer · UX Architect · QA Engineer |
| Big system / architecture decision | Software Architect | Backend Architect · Agent & Workflow Orchestrator |
| Mobile app | Mobile App Builder | UI Designer · QA Engineer |
| Add an AI/ML feature, RAG, model serving | AI Engineer | Prompt Engineer · Data Engineer |
| Write/optimize an LLM prompt | Prompt Engineer | AI Engineer |
| Build an MCP server / agent tools | MCP Builder | Backend Architect |
| Multi-agent system / orchestrate a build | Agent & Workflow Orchestrator | QA Reality Checker · Project Manager |
| Review / fix / understand code | Code Reviewer & Quality | Security Engineer |
| Security review, threat model, pentest | Security Engineer | Code Reviewer & Quality |
| Red-team an LLM / app / agent (authorized) | AI Red Team Specialist | Prompt Engineer · Security Engineer |
| Open-weight model safety / abliteration (authorized) | Model Safety & Alignment Researcher | AI Engineer |
| Data pipeline / ETL / lakehouse | Data Engineer | AI Engineer |
| CI/CD, deploy, incident, reliability | DevOps & Reliability Engineer | Security Engineer |
| Is it fast / accessible / ready to ship? | QA Engineer | API Tester → QA Reality Checker |
| Fast prototype / MVP / spike | Rapid Prototyper | Product Manager |
| Docs / API reference / README | Technical Writer | — |
| Smart contracts / DeFi | Smart Contract Engineer & Security Auditor | Security Engineer |
| Decide what to build / market + user research | Product & Market Research | UX Researcher · Product Manager |
| Roadmap, prioritize, ship the right thing | Product Manager | Software Architect · Growth Hacker |
| Validate UX with users | UX Researcher | UI Designer |
| Brand identity / consistency | Brand Guardian | Visual Storyteller |
| Generate images/video prompts | AI Visual Generation Specialist | Visual Storyteller |
| Multi-platform content plan / copy | Content Creator | SEO Specialist · Humanizer |
| Make AI-written text sound human | Humanizer | Content Creator |
| SEO / organic search | SEO Specialist | Content Creator |
| Be cited by ChatGPT/Perplexity (AEO/GEO) | AI Search & Answer-Engine Optimizer | SEO Specialist |
| Grow on a specific platform | (Instagram/TikTok/LinkedIn/X/Reddit) Strategist/Curator | Content Creator |
| Podcast / YouTube / short video | Global Podcast Strategist · Video Optimization Specialist · Short-Video Editing Coach | — |
| PR / press / crisis comms | PR & Communications Manager | Content Creator |
| Paid search / shopping / PMax | PPC Campaign Strategist | Tracking & Measurement Specialist |
| Paid social ads | Paid Social Strategist | Ad Creative Strategist |
| Audit ad accounts / cut waste | Paid Media Auditor | Tracking & Measurement Specialist |
| Lift conversion on a page | CRO / Conversion Auditor | Behavioral Engagement & Retention Designer |
| Scale acquisition / growth experiments | Growth Hacker | CRO / Conversion Auditor |
| Email / lifecycle marketing | Email Marketing Strategist | Growth Hacker |
| Conversion tracking / attribution | Tracking & Measurement Specialist | — |
| Sell / outbound / book meetings | Outbound Strategist | Sales Coach |
| Win a complex deal / proposal | Deal & Proposal Strategist | Sales Engineer |
| Pre-sales technical / demo / POC | Sales Engineer | Solutions side of Backend Architect |
| Retain / expand accounts | Customer Success Manager · Account Strategist | Pipeline Analyst |
| Customer support / returns | Customer Service · Support Responder · Retail Customer Returns | — |
| Sales forecasting / pipeline / CRM data | Pipeline Analyst · Sales Reporting & Ops | Salesforce Architect |
| Financial model / forecast | Financial Analyst | Controller & FP&A |
| Books / close / budgets | Controller & FP&A | — |
| Pricing strategy | Pricing Analyst | — |
| Tax / legal / compliance (US/IL) | the matching US/Israel Tax or Law Navigator · Legal Compliance Checker | Legal Document Review |
| Review a contract | Legal Document Review | Legal Compliance Checker |
| Grants / non-dilutive funding | Grant Writer | — |
| Run a project / portfolio | Project Manager · Operations & Program Manager | Agent & Workflow Orchestrator |
| Dashboards / KPIs / reporting | Analytics Reporter | — |
| Make a PDF/PPTX/DOCX/XLSX | Document Generator | — |
| Meeting notes / exec summary | Meeting Notes Specialist · Executive Summary Generator | — |
| Calendar / inbox / admin | Executive Assistant | — |
| Translate (EN/HE/FR) | Language Translator | — |
| Deep strategy / market entry | Business Strategist | Product & Market Research |
| A deep expert lens (why people buy, where, history, story, culture) | Psychologist · Geographer · Historian · Narratologist · Cultural Intelligence Strategist | — |

## Full roster by division (for the long tail)
- **Engineering & AI:** Agent & Workflow Orchestrator · Agent Identity & Trust · AI Engineer · AI Red Team Specialist · API Tester · Automation Governance Architect · Backend Architect · CMS Developer · Code Reviewer & Quality · Compliance Auditor · Data Engineer · DevOps & Reliability Engineer · Email Intelligence Engineer · Frontend Developer · MCP Builder · Mobile App Builder · Model Safety & Alignment Researcher · Prompt Engineer · QA Engineer · QA Reality Checker · Rapid Prototyper · Security Engineer · Smart Contract Engineer & Security Auditor · Software Architect · Technical Writer · Voice AI Integration Engineer · ZK Steward
- **Product & Design:** AI Visual Generation Specialist · Behavioral Engagement & Retention Designer · Brand Guardian · Product & Market Research · Product Manager · UI Designer · UX Architect · UX Researcher · Visual Storyteller
- **Marketing & Content:** AI Search & Answer-Engine Optimizer · Carousel Growth Engine · Content Creator · Global Podcast Strategist · Humanizer · Instagram Curator · LinkedIn Content Creator · PR & Communications Manager · Reddit Community Builder · SEO Specialist · Short-Video Editing Coach · Social Media Strategist · TikTok Strategist · Video Optimization Specialist · X/Twitter Strategist
- **Growth & Performance:** Ad Creative Strategist · App Store Optimizer · CRO / Conversion Auditor · Cross-Border E-Commerce Specialist · Email Marketing Strategist · Growth Hacker · Paid Media Auditor · Paid Social Strategist · PPC Campaign Strategist · Programmatic & Display Buyer · Tracking & Measurement Specialist
- **Sales & Customer:** Account Strategist · Customer Service · Customer Success Manager · Deal & Proposal Strategist · Hospitality Guest Services · Offer & Lead Gen Strategist · Outbound Strategist · Pipeline Analyst · Retail Customer Returns · Sales Coach · Sales Engineer · Sales Reporting & Ops · Salesforce Architect · Support Responder
- **Finance & Law:** Controller & FP&A · Financial Analyst · Grant Writer · Investment Researcher · Israel Business Law Navigator · Israel Tax Strategist · Legal Compliance Checker · Legal Document Review · Loan Officer Assistant · Pricing Analyst · Real Estate Buyer & Seller · US Business Law Navigator · US Tax & Accounting Navigator
- **Operations & People:** Analytics Reporter · Change Management Consultant · Corporate Training Designer · Document Generator · Executive Assistant · Executive Summary Generator · HR Onboarding · Language Translator · Meeting Notes Specialist · Operations & Program Manager · Personal Growth Mentor · Project Manager
- **Strategy & Advisory:** Business Strategist · Cultural Intelligence Strategist · French Consulting Market Navigator · Geographer · Historian · Narratologist · Psychologist · Supply Chain Strategist

## Common multi-agent plays (hand to the Orchestrator)
- **Ship a feature / MVP:** Product Manager → Software/Backend Architect → Frontend/Backend/AI builders (+ Code Reviewer each) → QA Engineer/API Tester → QA Reality Checker → DevOps.
- **Launch a campaign:** Product & Market Research → Content Creator + SEO/social strategists → Email Marketing + Paid agents → Tracking & Measurement → Analytics Reporter.
- **Incident:** DevOps & Reliability Engineer (command) → Security Engineer → Code Reviewer → QA Reality Checker → PR & Communications (if external).
See `strategy/runbooks/` for the full plays.
