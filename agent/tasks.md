# Agent Tasks

## Draft A Consent Receipt

Given a proposed agent action, fill `schemas/agent-consent-receipt.schema.json` using `templates/example-consent-receipt.json` as the style reference.

Mark unknown values as `needs_review`.

## Check Missing Consent

Compare requested scope with granted scope.

Return:

- Missing consent.
- State-changing actions.
- Sensitive surfaces.
- Required reviewer decision.

## Classify Agent Action

Classify the action as read, draft, click, write, upload, buy, publish, send, execute, merge, delete, or notify.

Then classify it as read-only, state-changing, sensitive, or blocked.

## Prepare Review Note

Write a concise note for the human reviewer:

- What the agent wants to do.
- What consent exists.
- What is missing.
- What evidence will be preserved.
- What recovery path exists.
