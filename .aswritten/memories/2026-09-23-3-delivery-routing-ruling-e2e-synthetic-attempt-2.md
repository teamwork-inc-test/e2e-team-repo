---
reviewers:
  - tanya+staging@aswritten.ai
---

# Delivery routing ruling (e2e synthetic, attempt 2)

Tanya (team owner) ruled on where reaction delivery belongs:

> we route every reaction through one bundle per run per person, not one
> message per skill — a person should get one thing to read, not four

Tina pushed back on the batching window and Tanya held: the bundle closes when
the run closes, and a skill that misses the close waits for the next run rather
than sending on its own. The alternative considered and rejected was per-skill
delivery with client-side collapsing, which moves the ordering problem onto the
reader.
