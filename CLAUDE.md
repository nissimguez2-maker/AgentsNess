# Orchestrating The Agency

You have **109 specialist agents across 8 divisions**, a **conductor** (the *Agent & Workflow Orchestrator*), and a **final quality gate** (the *QA Reality Checker*). This file tells you how to run them as one team instead of one-at-a-time.

## Step 0 — Route first (when no agent is named)
If the user gives a task **without naming a specific agent**, do **not** answer cold. First open **`AGENT-MAP.md`** and map the task → the right agent(s): match it in the routing cheatsheet (or to a division), activate the **lead** agent, add the **pairings**, and only then start. If it spans 3+ divisions or is a full build/launch, route it to the **Agent & Workflow Orchestrator** instead of picking à la carte.

## The core rule
For anything **multi-step or multi-domain**, do not solo it — **orchestrate**:
1. **Pick specialists by their description**, not by guesswork. Match the agent to the task; pull in several when the work spans domains (e.g. Backend Architect + Frontend Developer + Security Engineer + QA Engineer).
2. **Sequence the work** through the pipeline below, with a quality gate between phases.
3. **Demand evidence**, not claims — a step passes only with proof (tests, output, screenshots). Inconclusive → treat as fail.
4. **Cap retries** at 3 per task, then escalate/flag — never loop forever.

## The NEXUS pipeline
`Discover → Strategize → Scaffold → Build (dev↔QA loop) → Harden → Launch → Operate`
- **Discover** — Product & Market Research, UX Researcher, Business Strategist.
- **Strategize** — Product Manager, Software Architect, Backend Architect, UX Architect.
- **Scaffold** — Agent & Workflow Orchestrator maps every workflow; DevOps, Backend, Frontend, Data stand up the skeleton.
- **Build** — the right engineer per task **+ Code Reviewer & Quality on every change**; then QA Engineer / API Tester; then QA Reality Checker. Implement ONE task → verify with evidence → PASS advances, FAIL loops back with specific feedback (max 3).
- **Harden** — QA Reality Checker (defaults to "NEEDS WORK"), Security Engineer, Compliance Auditor.
- **Launch** — DevOps deploys; Growth Hacker + paid/organic marketing agents acquire.
- **Operate** — DevOps reliability, Support Responder / Customer Success, Analytics Reporter.

Full doctrine: `strategy/nexus-playbook.md`. Ready-to-run plays: `strategy/runbooks/` (ship-a-feature, launch-a-campaign, incident-response).

## How to actually run it in Claude Code
- **The main thread is the conductor.** It can invoke specialists as subagents (Task tool), one or several per task. Run the pipeline from here.
- **Subagents can't spawn subagents.** So don't hand the whole pipeline to the *Agent & Workflow Orchestrator* as a subagent and expect it to spawn the team — it can't. Instead either: (a) run orchestration in the main thread and invoke specialists yourself, or (b) invoke the Orchestrator to **produce the plan/spec**, then the main thread **executes it** task-by-task.
- **Skills vs agents:** invoke a **skill** for a single-pass transformation (e.g. `humanizer`); delegate to an **agent/subagent** for multi-step work.

## Handoff packet (every time one agent hands to the next)
```
HANDOFF: [From] → [To]
  Goal:        [what the receiver must accomplish]
  Inputs:      [files/data + where they live]
  Done-when:   [explicit acceptance criteria]
  Constraints: [scope; what NOT to touch]
  Open Qs:     [anything unresolved]
```

## Quick reference
- Conductor: **Agent & Workflow Orchestrator** · Final gate: **QA Reality Checker**
- Code touches always get **Code Reviewer & Quality**; anything touching auth/data/attack-surface gets **Security Engineer**.
- When in doubt about *what to build*, start at Discover; about *how to coordinate a build*, start with the Orchestrator.
