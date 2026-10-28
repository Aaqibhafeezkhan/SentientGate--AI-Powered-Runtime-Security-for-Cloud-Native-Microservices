---
name: Threat Strategy Proposal
about: Propose a new runtime security heuristic or threat detection strategy
title: "[Threat Strategy]: "
labels: ["enhancement", "security", "area/mcp"]
assignees: ''

---

## Strategy Name
(e.g., `SsrfDetectionStrategy`, `LdapInjectionStrategy`, `GeoAnomalyStrategy`)

## Threat Classification
- **Attack Vector:** (e.g. Server-Side Request Forgery, Directory Traversal, Brute Force)
- **CWE / OWASP Category:** (e.g. CWE-918, OWASP API Security Top 10)
- **Target Signals:** (e.g. URI Path, Query Parameters, Response Status, Header signatures)

## Proposed Heuristic Logic
Explain how the strategy evaluates incoming alerts and history logs:
- What patterns trigger a match?
- How does it minimize false positives?

## Recommended Enforcement Action
- **Suggested Block Duration:** (e.g. 15 minutes, 1 hour, 24 hours)
- **Reason Code:** (e.g. `SSRF_ATTEMPT`, `SUSPICIOUS_SCANNER`)
- **Severity Level:** (LOW / MEDIUM / HIGH / CRITICAL)
