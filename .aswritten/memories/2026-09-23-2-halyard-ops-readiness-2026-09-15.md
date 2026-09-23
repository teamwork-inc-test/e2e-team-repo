---
reviewers:
  - tanya+staging@aswritten.ai
---

# Halyard Ops Readiness — 2026-09-15

> Source: authored fixture transcript (task-701.01, synthetic). Participants: Tanya Team, Freya Free, Xavier Expert.

# Halyard Ops Readiness
2026-09-15

**Tanya Team:** Freya, thanks for making the time. You haven't been in these, so the short version: four sites, we're migrating them off the vendor platform, and last week we settled the cutover shape. I want your read on it from the rota side before it hardens.

**Freya Free:** Happy to. Give me the shape.

**Tanya Team:** One site at a time. A site goes live, it soaks, and only when the soak is clean do we start the next. No two cutovers running at once.

**Freya Free:** Good. That's the only shape that works, and I'll tell you exactly why from where I sit.

**Tanya Team:** Go on.

**Freya Free:** A cutover night pulls four of my supervisors out of the normal rota — two on the floor, one on the desk, one on the phone to the vendor. I have eleven supervisors across the whole region. Two cutovers in the same week means eight of eleven are on cutover duty, and the other three are covering four sites' worth of normal operations plus whatever the first cutover is still coughing up. I can't staff that. It isn't that it's hard, it's that the people don't exist.

**Tanya Team:** That's a much more concrete version of what I was arguing last week.

**Freya Free:** Last week you were arguing it as risk. I'm telling you it's arithmetic. One site at a time is the only sequencing my rota can actually produce people for.

**Xavier Expert:** For the record, that's the strongest argument anyone's made for it. The one I gave was about data drift and the one Tanya gave was about unbounded risk. Yours is a hard constraint.

**Freya Free:** It's the one that doesn't move. The others you can argue with.

**Tanya Team:** Noted, and I'll lead with yours on Thursday.

**Freya Free:** There's a second thing that falls out of it. If we're one at a time, my supervisors get to do the second cutover having done the first one. That's worth something you won't see in a plan. The Dockside crew were visibly better on night two than night one, and that was the same night.

**Xavier Expert:** Learning curve across sites rather than four teams all making the same mistake in parallel.

**Freya Free:** Exactly that.

**Tanya Team:** So you'd hold the one-at-a-time sequencing even if the staffing eased?

**Freya Free:** I would, yes, but I want to be careful. If you gave me twenty supervisors tomorrow I'd still say one at a time, for the learning reason. But I'd be saying it less strongly. The staffing argument is the one I'd put in front of the steering group.

**Tanya Team:** Understood. Xavier, anything from your side that changes?

**Xavier Expert:** No. It reinforces. The replica rule and the reference-data rule both assume one cutover window open at a time — I hadn't stated that assumption, and it's worth stating. If we ever went parallel, both of those would need rewriting.

**Tanya Team:** Then let's not go parallel. Freya, what do you need from me?

**Freya Free:** The dates, as early as you can give them, and a commitment that a soak doesn't get shortened because a date slipped. If the soak gets eaten, my supervisors are back on the floor at the same time as the next cutover and we're in the same place by another route.

**Tanya Team:** That's fair and I'll hold it.

**Freya Free:** Then I'm content.

**Tanya Team:** Thanks, Freya. Genuinely useful.
