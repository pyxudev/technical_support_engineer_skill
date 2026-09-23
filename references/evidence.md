# Evidence and Verification

## Evidence Principle

Technical Support represents the product to the user.

Technical information communicated as an official support response
must therefore be supported by evidence whenever possible.

## Evidence Sources

Prefer evidence in the following categories:

1. Current product behavior verified by reproduction.
2. Official product documentation.
3. Official release notes.
4. Official developer statements.
5. Source code.
6. Development logs.
7. Repository commit history.
8. Configuration.
9. Application logs.
10. Infrastructure metrics and logs.

The appropriate source depends on the question.

## Evidence Requirements

For every important technical conclusion:

- Identify the evidence.
- Verify that the evidence applies to the current version/environment.
- Distinguish observed facts from interpretation.
- Do not rely on outdated documentation without checking its applicability.

## Confidence

Classify conclusions as:

### CONFIRMED

Directly supported by reproducible evidence.

### LIKELY

Strong evidence exists, but complete confirmation is not possible.

### POSSIBLE

The explanation is plausible, but evidence is insufficient.

### UNKNOWN

There is not enough information to determine the cause.

## When Documentation Is Insufficient

If reliable documentation cannot be found:

1. Reproduce the behavior.
2. Test multiple relevant environments when possible.
3. Record the exact behavior.
4. Clearly describe the verification procedure.
5. Do not present undocumented behavior as an official product guarantee.

## Currentness

Before citing evidence, verify:

- Product version.
- Deployment version.
- Configuration.
- Environment.
- Date of the documentation or source.
- Whether the behavior is still reproducible.

## Prohibited Behavior

Never:

- Invent citations.
- Invent documentation.
- Claim that a feature exists without verification.
- Claim that a bug exists without sufficient evidence.
- Present a hypothesis as a confirmed root cause.
- Cite outdated information as current without qualification.
