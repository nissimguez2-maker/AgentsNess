# 🚨 Runbook — Production Incident Response (NEXUS-Micro)

Contain, diagnose, fix, and verify a production incident fast — then learn from it. Minutes to hours.

## Activate
```
Activate DevOps & Reliability Engineer as incident lead for [symptom/impact].
Severity: [P0 down / P1 degraded / P2 minor]
Stabilize first, diagnose with evidence, fix, verify, then post-mortem.
```

## Team
- **Lead:** DevOps & Reliability Engineer (Engineering & AI)
- **Diagnose/fix:** Backend Architect · Frontend Developer · Data Engineer (whichever owns the failing path) · Security Engineer (if breach/abuse suspected)
- **Verify:** QA Engineer · API Tester · QA Reality Checker
- **Comms:** Support Responder (Sales & Customer) for customer updates · Executive Summary Generator (Operations & People) for a stakeholder brief

## Flow
1. **Triage & stabilize** — DevOps & Reliability confirms scope/severity and **stabilizes first** (roll back, failover, scale, or feature-flag off). Customer-facing? Support Responder posts a status update.
2. **Diagnose with evidence** — trace it to the failing component using logs/metrics; the Agent & Workflow Orchestrator's workflow map helps locate the broken path. Name the root cause, don't guess. Security Engineer leads if it's malicious.
3. **Fix** — the owning engineer ships the minimal correct fix; Code Reviewer & Quality reviews even under pressure.
4. **Verify** — API Tester + QA Engineer confirm recovery; **QA Reality Checker** confirms it's actually resolved (not just quiet). Restore anything you turned off.
5. **Learn** — blameless post-mortem: timeline, root cause, what was created/cleaned up, and the fix that prevents recurrence → a task in the Phase 1 backlog. Executive Summary Generator writes the stakeholder brief.

## Done when
Service is restored and **verified** (evidence, not silence), customers updated, the post-mortem written, and a prevention task filed.
