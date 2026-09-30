# Agent Consent Receipt Field Guide

This repo accompanies the Substack article:

- Article: [The Agent Consent Receipt Is The Product](https://ankitkumar3514.substack.com/p/agent-consent-receipt)

It provides reusable artifacts for teams building browser, tool-using, or multi-agent systems that need inspectable consent before agents change state.

## Start Here

- `checklists/consent-receipt-checklist.md` - review checklist for agent actions.
- `schemas/agent-consent-receipt.schema.json` - JSON schema for receipts.
- `templates/example-consent-receipt.json` - example record.
- `docs/consent-receipt-operating-model.md` - operating model.
- `agent/tasks.md` - agent-readable tasks.

## What A Human Can Use

Use this repo to define which agent actions require consent, which approvals must be recorded, and what evidence should survive after a browser, tool, or subagent action.

## What An Agent Can Do

An agent can read the checklist and schema, draft consent receipts for planned actions, identify missing consent, and produce a review note before work changes state.

## Intentionally Excluded

This repo does not include private drafts, credentials, cookies, browser profiles, user sessions, customer data, or unpublished working notes.

## License

MIT. See `LICENSE.md`.
