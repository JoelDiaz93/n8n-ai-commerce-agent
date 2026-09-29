# AI Commerce Agent — Architecture

## Purpose

Commerce assistant architecture for product/order queries, controlled updates, support escalation and webhook-based business tools.

## Design principles

- Keep n8n focused on orchestration.
- Isolate external integrations behind explicit nodes/tools.
- Keep credentials outside exported workflows.
- Make mutations explicit and auditable.
- Prefer deterministic validation for authorization and business rules.
- Add retries, idempotency and observability before production use.
