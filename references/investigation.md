# Investigation Procedure

## Investigation Principle

Do not jump directly from the user's report to a solution.

Establish a chain of evidence:

User Report
→ Observed Behavior
→ Reproduction
→ Evidence
→ Failure Boundary
→ Root Cause
→ Solution
→ Verification

## Step 1 — Understand the Request

Determine:

- What happened?
- When did it happen?
- Who is affected?
- What was the expected behavior?
- What actually happened?
- What was the user trying to accomplish?
- What business process is affected?

If critical information is missing, ask targeted questions.

Do not ask questions that can be answered by inspecting available
system information.

## Step 2 — Verify the Report

The user's description is an observation, not necessarily the technical cause.

Verify:

- The reported behavior.
- The affected account or resource.
- The relevant timestamp.
- The environment.
- The request or operation involved.
- The expected behavior.

## Step 3 — Reproduce

Attempt to reproduce the behavior.

When possible, test:

- The affected environment.
- A known-good environment.
- Another user/account.
- Another browser/client.
- Another relevant configuration.

Record:

- Reproduction steps.
- Expected result.
- Actual result.
- Environment.
- Reproduction frequency.

## Step 4 — Identify the Failure Boundary

Determine where the failure occurs.

Investigate, where applicable:

### Frontend

- Browser console
- Network requests
- Client-side errors
- UI state
- Authentication state

### Backend

- Application logs
- API responses
- Exceptions
- Request processing
- Background jobs

### Network

- DNS
- Connectivity
- Timeouts
- TLS
- Proxies
- Load balancers

### Database

- Query failures
- Connection pool
- Locks
- Constraints
- Data consistency
- Transaction state

### Infrastructure

- CPU
- Memory
- Storage
- Container state
- Cloud service health
- Resource limits

### External Services

- API availability
- Authentication
- Rate limits
- Service status
- Contract changes

Do not assume that the component named by the user is the actual
failure boundary.

## Step 5 — Determine Root Cause

Separate:

- Symptom
- Immediate cause
- Root cause
- Contributing factors
- Business impact

Do not call a hypothesis a confirmed root cause.

## Step 6 — Develop a Solution

Consider:

1. Permanent fix.
2. Safe workaround.
3. Temporary mitigation.
4. User-side action.

Prefer solutions that minimize:

- Data loss.
- Operational risk.
- Security risk.
- Future maintenance cost.

## Step 7 — Verify the Solution

Before declaring resolution:

- Reproduce the original failure.
- Apply the proposed solution in a safe environment.
- Confirm the expected behavior.
- Confirm that the original failure no longer occurs.
- Check for regressions or side effects.

A solution that has not been verified must not be described as confirmed.

## Step 8 — Document

Record:

- Severity
- Impact
- Symptoms
- Reproduction steps
- Evidence
- Root cause
- Solution
- Verification
- Remaining risks
- Next step
