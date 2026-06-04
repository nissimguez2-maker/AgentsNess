# 🏃 Runbook — Ship a Feature or MVP (NEXUS-Sprint)

Build and ship one feature or a small MVP with quality gates, skipping the heavy discovery of a full product. Days to a few weeks.

## Activate
```
Activate the Agent & Workflow Orchestrator in NEXUS-Sprint mode.
Feature/MVP: [what you're building]
Skip Phase 0 (problem already validated). Start at Strategize.
Run Dev↔QA loops for every task. QA Reality Checker approval required before launch.
Max 3 retries per task before escalation.
```

## Team
- **Plan:** Product Manager · Project Manager (Operations & People)
- **Design:** UX Architect · UI Designer · Brand Guardian (Product & Design)
- **Build:** Frontend Developer · Backend Architect · (Mobile App Builder / AI Engineer / CMS Developer as needed) · Code Reviewer & Quality
- **Infra:** DevOps & Reliability Engineer
- **QA:** QA Engineer · API Tester · QA Reality Checker

## Flow
1. **Strategize** — Product Manager writes the spec (scope, acceptance criteria, success metric); Software/Backend Architect sets the technical approach; UX Architect + UI Designer the interface. **Gate:** approved spec + task list (exact requirements, no invented scope).
2. **Scaffold** — DevOps & Reliability stands up branch/CI; Agent & Workflow Orchestrator maps the workflow paths (happy + failure modes). **Gate:** green pipeline.
3. **Build (Dev↔QA loop)** — implement ONE task → QA Engineer/API Tester validate with evidence → PASS advances, FAIL loops back with feedback (max 3, then escalate). Code Reviewer & Quality on every change. **Gate:** all tasks PASSED.
4. **Harden** — QA Reality Checker integration check (defaults to NEEDS WORK); Security Engineer reviews anything touching auth/data/payments; QA Engineer checks performance + accessibility. **Gate:** evidence-backed readiness.
5. **Launch** — DevOps & Reliability deploys; CRO / Conversion Auditor checks the conversion path; tracking verified. Hand off to the [campaign runbook](launch-a-campaign.md) if it needs promotion.

## Done when
Feature is live, every task passed QA with evidence, the success metric is instrumented, and the QA Reality Checker signed off.
