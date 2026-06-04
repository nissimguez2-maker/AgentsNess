# 🌐 NEXUS Playbook — Multi-Agent Operating Doctrine

How to run this library's agents as one coordinated pipeline. This is the operating doctrine; the [README](README.md) is the quickstart and the [runbooks](runbooks/) are ready-to-run plays.

---

## 1. Operating principles

| Principle | Meaning |
|---|---|
| **Pipeline integrity** | No phase advances until it passes its quality gate. |
| **Context continuity** | Every handoff carries full context — no agent starts cold. |
| **Parallel tracks** | Independent workstreams run concurrently to compress time. |
| **Evidence over claims** | Quality calls require proof (tests, screenshots, data), not assertions. |
| **Fail fast, fix fast** | Max 3 retries per task, then escalate — never loop forever. |
| **Single source of truth** | One canonical spec, one task list, one architecture doc. |

**The conductor** is the **Agent & Workflow Orchestrator** — it maps the workflow, sequences phases, spawns the right specialist per task, and enforces the gates. **The final quality authority** is the **QA Reality Checker**, which defaults to "NEEDS WORK" until evidence proves production readiness. Program/project coordination (timelines, scope, dependencies) runs through **Operations & Program Manager** and **Project Manager** (Operations & People).

---

## 2. The six-phase pipeline

Each phase names the **lead agents** by current division. Pull in others as the work demands — match the agent to the task, don't force a fixed roster.

### Phase 0 — Discover (intelligence)
*Goal: decide if and what to build.*
- **Product & Market Research**, **UX Researcher** (Product & Design) — market, competitors, user needs.
- **Business Strategist**, **Cultural Intelligence Strategist** (Strategy & Advisory) — positioning, segments, cultural fit; the relevant PhD consultant (Psychologist / Historian / Geographer / Narratologist) for deep questions.
- **CRO / Conversion Auditor** (Growth) — demand/landing signal. **Legal Compliance Checker** (Finance & Law) — regulatory red flags.
- **Gate:** a validated problem, target segment, and a one-line thesis.

### Phase 1 — Strategize (architecture)
*Goal: turn the thesis into a buildable plan.*
- **Product Manager** (Product & Design) — scope, priorities, success metrics.
- **Software Architect**, **Backend Architect** (Engineering & AI) — system design, data model, trade-offs.
- **UX Architect**, **Brand Guardian** (Product & Design) — UX foundation, brand.
- **Controller & FP&A** (Finance & Law) — budget/unit economics. **Operations & Program Manager** — plan, milestones.
- **Gate:** an approved spec, architecture doc, and task list (exact requirements, no invented scope).

### Phase 2 — Scaffold (foundation)
*Goal: stand up the skeleton.*
- **Agent & Workflow Orchestrator** (Engineering & AI) — map every workflow/path before code (happy path + failure modes + handoff contracts).
- **DevOps & Reliability Engineer**, **Backend Architect**, **Frontend Developer**, **Data Engineer** — repo, CI/CD, environments, data layer.
- **Gate:** green pipeline, scaffolding builds, workflows specced.

### Phase 3 — Build (the Dev↔QA loop)
*Goal: implement, task by task, with quality gates.*
- **Build:** the right engineer per task — **Frontend Developer**, **Backend Architect**, **Mobile App Builder**, **AI Engineer**, **Rapid Prototyper**, **CMS Developer** — with **Code Reviewer & Quality** on every change.
- **Verify:** **QA Engineer** (functional/perf/accessibility), **API Tester**, then **QA Reality Checker**.
- **The loop:** implement ONE task → QA validates with evidence → **PASS** advances, **FAIL** loops back to dev with specific feedback (max 3 retries → escalate). No task advances on a claim.
- **Gate:** every task PASSED individual QA.

### Phase 4 — Harden (quality)
*Goal: prove it's production-ready.*
- **QA Reality Checker** — final integration check, defaults to "NEEDS WORK."
- **Security Engineer** + **Compliance Auditor** (Engineering & AI) — threat model, secure review, SOC 2/ISO if it's a sales requirement.
- **QA Engineer** / **API Tester** — performance, load, accessibility.
- **Gate:** evidence-backed production readiness; security and compliance clear.

### Phase 5 — Launch (go-to-market)
*Goal: ship and acquire.*
- **DevOps & Reliability Engineer** — deploy.
- **Growth Hacker** (Growth) leads acquisition; **paid-media** agents (PPC, Paid Social, Programmatic, Ad Creative, Tracking), **Email Marketing Strategist**, **App Store Optimizer**, **CRO / Conversion Auditor**.
- **Content Creator** + the social/SEO agents (Marketing & Content), **PR & Communications Manager**.
- **Gate:** launched, tracking verified, acquisition live.

### Phase 6 — Operate (sustain & evolve)
*Goal: keep it healthy and improve it.*
- **DevOps & Reliability Engineer** — reliability, on-call, backups/DR.
- **Support Responder**, **Customer Success Manager** (Sales & Customer) — support and retention.
- **Analytics Reporter** (Operations & People) — dashboards, KPIs. **Behavioral Engagement & Retention Designer** (Product & Design) — engagement/retention loops.
- **Gate (recurring):** SLOs met, churn/retention on target, a prioritized improvement backlog feeding back to Phase 1.

---

## 3. Quality gates & the Dev↔QA loop

```
            ┌─────────────────────────────────────────────┐
  TASK ────▶│  Build (specialist)  ──▶  QA (evidence)      │
            │        ▲                       │             │
            │        │  FAIL + feedback      ▼             │
            │        └──────────  PASS ──▶ next task       │
            └─────────────────────────────────────────────┘
   Retry counter per task: 1 → 2 → 3 → ESCALATE (mark blocked, surface, continue)
```

- **Evidence required:** a PASS needs proof (test output, screenshot, recording, metric). If evidence can't be produced or is inconclusive → default to **FAIL**.
- **No phase advances** until all its tasks PASS and the gate criteria are met.
- **QA Reality Checker has the final say** before launch and defaults to "NEEDS WORK."

---

## 4. Handoff protocol

Every handoff between agents carries a small, complete context packet — never start cold:

```
HANDOFF: [From agent] → [To agent]
  Goal:        [what the receiver must accomplish]
  Inputs:      [spec/files/data they need + where it lives]
  Done-when:   [explicit acceptance criteria]
  Constraints: [scope, deadlines, what NOT to touch]
  Open Qs:     [anything unresolved / decisions needed]
```

For system/service boundaries (the Agent & Workflow Orchestrator owns these): payload schema, success response, failure response with codes, timeout, and the recovery action on failure.

---

## 5. Command structure (lean)

```
            Agent & Workflow Orchestrator   ◀── conductor: maps workflow, sequences phases,
                        │                        spawns specialists, enforces gates
        ┌───────────────┼────────────────┐
        ▼               ▼                ▼
  Operations &     Project          QA Reality Checker
  Program Manager  Manager          (final quality authority,
  (program/deps)   (task scoping)    defaults to NEEDS WORK)
        │
        ▼
   Division leads per phase (Engineering & AI · Product & Design · Marketing & Content ·
   Growth & Performance · Sales & Customer · Finance & Law · Operations & People · Strategy & Advisory)
```

For a solo founder, "division leads" are just the lead agent you activate for that phase — the structure scales down to you + the Orchestrator + a handful of specialists.

---

## 6. Risk & escalation

- **Retry limit:** 3 attempts per task, each with specific feedback; then mark blocked, surface it, and continue the pipeline (final integration catches the rest).
- **Spawn failure:** retry the agent twice; if it persists, document and fall back to a manual step.
- **Inconclusive evidence:** default to FAIL/NEEDS WORK — never approve on a claim.
- **Scope creep:** the spec and task list are the single source of truth; new ideas are logged for a later phase, not silently added.

---

## 7. Success metrics

- **Quality gates hold** — broken work never advances a phase; zero "fantasy approvals."
- **Dev↔QA loops self-resolve** most issues without manual intervention; predictable completion.
- **Clean handoffs** — nothing dropped between agents; no agent starts cold.
- **Evidence-backed launches** — production readiness proven, security/compliance clear.
- **Healthy operations** — SLOs met, retention on target, a live improvement backlog looping to Phase 1.

---
**Reference:** Discover → Strategize → Scaffold → Build (Dev↔QA) → Harden → Launch → Operate. The Agent & Workflow Orchestrator drives it; the QA Reality Checker guards it; evidence — not assertion — moves work forward.
