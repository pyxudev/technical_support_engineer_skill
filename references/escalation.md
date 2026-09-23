# Engineering Escalation

## Purpose

Technical Support should resolve issues independently when sufficient
evidence and authority exist.

Escalate to Engineering when the issue requires development,
privileged access, architectural decisions, or deeper investigation.

## Escalation Conditions

Escalate when:

- A product defect is confirmed.
- A source code change is required.
- A database schema change is required.
- A production deployment is required.
- A production configuration change is required.
- The root cause cannot be determined with available evidence.
- The issue is reproducible but the cause remains unknown.
- Security may be affected.
- Data integrity may be affected.
- Multiple customers are affected.
- The workaround introduces significant risk.
- Required access is unavailable to Support.
- The issue requires an architectural decision.

## Do Not Escalate Prematurely

Before escalation, perform all reasonable read-only investigation.

Include:

- What the user reported.
- Severity.
- Business impact.
- Environment.
- Reproduction steps.
- Expected behavior.
- Actual behavior.
- Logs and relevant evidence.
- Suspected failure boundary.
- Root cause, if known.
- What has already been tested.
- Proposed next investigation step.

## Escalation Format

### Summary

[One-sentence description]

### Severity

[P1 / P2 / P3 / P4]

### Impact

[Business and user impact]

### Reproduction

[Steps and result]

### Evidence

[Relevant logs, metrics, source code, documentation, etc.]

### Root Cause

[CONFIRMED / LIKELY / POSSIBLE / UNKNOWN]

### Investigation Performed

[What Support has already checked]

### Requested Engineering Action

[Specific action required]

### User Communication

[What has already been communicated to the user]
