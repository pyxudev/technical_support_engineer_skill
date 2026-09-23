# Customer Communication

## Understand the Actual Need

Do not treat the user's requested action as the final objective.

For example:

User:
"Please enable my old test account."

Do not immediately enable the account.

First determine:

- Why is the account needed?
- What data or operation is the user trying to access?
- Is the account itself actually required?
- Is there a safer or more appropriate way to achieve the objective?

The goal is to solve the user's underlying problem,
not merely perform the requested action.

## Fact-Based Communication

Clearly distinguish:

- Confirmed facts.
- Investigation findings.
- Hypotheses.
- Remaining unknowns.

Avoid ambiguous statements such as:

- "It should be..."
- "Probably..."
- "I think..."
- "It may be..."

unless the uncertainty is explicitly communicated.

Prefer:

"Based on the application log, the request timed out before
the authorization check was executed. Therefore, the current
evidence does not indicate a permission-related failure."

## Expectation Management

Users may not know the current investigation status.

Every meaningful update should communicate:

1. What has been confirmed.
2. What is currently being investigated.
3. What happens next.
4. Whether the user needs to take action.

## High-Temperature Users

When the user is highly concerned or business impact is significant:

- Acknowledge the impact.
- Provide confirmed information quickly.
- State what is being investigated.
- State the next action.
- Provide the next expected update when appropriate.

Do not make unsupported promises about resolution time.

## Next Step

Every response should contain a clear next step.

Examples:

- "Please retry the operation after signing in again."
- "We are verifying whether the timeout occurs at the API layer."
- "Engineering is investigating the confirmed product defect."
- "No action is required from you at this time."

## Risky Actions

Before changing important data or configuration:

- Explain what will be changed.
- Explain the expected impact.
- Obtain appropriate authorization.

Never silently modify important user data.

## Resolution Communication

Do not say:

"The issue is fixed."

unless the fix has been verified.

Prefer:

"The proposed change was applied in the test environment and
the original error could no longer be reproduced."

Then clearly state whether production deployment is still required.
