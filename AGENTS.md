# Agent Instructions

Read order:

1. `README.md`
2. `checklists/consent-receipt-checklist.md`
3. `schemas/agent-consent-receipt.schema.json`
4. `templates/example-consent-receipt.json`
5. `docs/consent-receipt-operating-model.md`

Allowed tasks:

- Draft a consent receipt for a proposed agent action.
- Check whether an action is read-only, state-changing, sensitive, or blocked.
- Identify missing consent, missing evidence, or missing rollback.
- Produce a short review note for a human owner.

Boundaries:

- Do not request, expose, or store credentials, cookies, tokens, private sessions, or personal data.
- Do not approve state-changing work yourself.
- Do not publish, send, buy, merge, delete, or modify external systems.
- Treat this repo as a planning and review aid, not an authorization system.

Output style:

- Be concise.
- Separate confirmed facts from assumptions.
- List missing consent or evidence directly.
