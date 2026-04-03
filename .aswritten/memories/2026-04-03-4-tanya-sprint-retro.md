---
reviewers:
  - test+team-owner@aswritten.ai
---

# Sprint 4 Retro: Async Decision Widget

**Date:** 2026-03-22
**Participants:** Tanya Owner (CEO), Tina Teammate (Head of Product), Dev Team

## Summary

Shipped the async decision widget — the core feature that captures decisions at the point of consensus in any chat thread.

Tanya: "This sprint proved the thesis. The widget intercepts the moment someone says 'let's go with option B' and creates a persistent decision record with full context. Zero extra steps for the team."

Tina: "Velocity was 23 points, highest this quarter. The Zephyr integration was the key unlock — we can now embed the decision capture in Slack, Teams, and Discord without separate plugins."

## Key Decisions

- **Architecture**: Event-driven capture via webhook, not polling. Tanya: "Polling would kill us at scale. Webhooks mean we only process actual decisions, not every message."
- **Pricing update**: Moving from $12/user to $15/user for teams over 25. Tina: "The customer discovery showed teams of 25+ have 3x the decision volume. The value scales with team size."
- **Next sprint focus**: Context preservation — linking decisions to the discussion threads that produced them. This was the #1 request from beta users.

## Blockers Resolved

- Zephyr API rate limits: solved with batched webhook delivery
- Decision deduplication: hash-based dedup catches 95% of re-posts
