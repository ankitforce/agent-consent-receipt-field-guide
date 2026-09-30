# Consent Receipt Operating Model

An agent consent receipt is a durable record that links a delegated task to the scope, actor, tool surface, consent decision, evidence, and recovery path for an action.

## Action Classes

Read-only actions usually need evidence.

State-changing actions need evidence plus consent.

Sensitive actions need explicit approval, short expiration, and a rollback or escalation path.

Blocked actions should preserve the reason for denial.

## Required Review Questions

1. Who delegated this work?
2. What action will the agent take?
3. Does the action change external state?
4. Which model, tool, browser, connector, or subagent will act?
5. What consent exists before the action?
6. What evidence will survive after the action?
7. How can the user stop, revoke, retry, or roll back the work?

## Receipt Lifecycle

Draft receipt:

- Created before the agent acts.
- Captures intended scope and missing approvals.

Approved receipt:

- Captures granted consent and reviewer.
- Allows bounded execution.

Executed receipt:

- Adds actual tool calls, browser steps, changed resources, and outputs.

Reviewed receipt:

- Adds human review outcome, escalation, rollback, or closure.
