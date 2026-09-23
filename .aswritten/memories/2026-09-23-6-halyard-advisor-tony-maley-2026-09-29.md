---
reviewers:
  - tanya+staging@aswritten.ai
---

# Halyard — Advisor Session with Tony Maley — 2026-09-29

> Source: authored fixture transcript (task-701.01, synthetic). Participants: Tanya Team, Tony Maley (external advisor, no programme seat).

# Halyard — Advisor Session with Tony Maley
2026-09-29

**Tanya Team:** Tony, thanks for making time. You're not on the programme and I'm not asking you to join it — I want an outside read on the plan before it goes to the board, and you've seen more of these than anyone I can get on a call.

**Tony Maley:** Happy to look. I'll be blunt where I can be useful and quiet where I can't. Give me the plan.

**Tanya Team:** Four sites off a vendor platform. One site at a time, a soak between each one before the next starts, reporting off a replica during the cutover windows, vendor keeps reference data until the last site is live.

**Tony Maley:** You're right to go one site at a time, and I'd hold that against whatever pressure comes at you. I've watched three of these programmes up close. The two that went big-bang both went backwards — not failed, went backwards, six months of unpicking. The one that went sequentially was boring and finished.

**Tanya Team:** That's a stronger endorsement than I expected.

**Tony Maley:** It's the only part of your plan I'd call settled. And the pressure to collapse the sequence always comes in month four, from someone who wasn't there in month one, and it always arrives dressed as efficiency.

**Tanya Team:** It's already started, if I'm honest.

**Tony Maley:** Of course it has. Write down now, while you're calm, why you chose sequential. When they come at you in month four you want the reasons in your own handwriting, not reconstructed under pressure.

**Tanya Team:** That's good advice.

**Tony Maley:** Now the part you won't like.

**Tanya Team:** Go on.

**Tony Maley:** Your plan has no data-quality gate in it. Nowhere in what you just described does anything stop a site cutting over with bad data.

**Tanya Team:** We have a migration validation step.

**Tony Maley:** A validation step tells you the data moved. It doesn't tell you the data was any good before it moved. Those are completely different questions and every programme I've seen conflates them, including the two that went backwards.

**Tanya Team:** Say what you mean by a gate.

**Tony Maley:** A named quality bar, measured on the source system, before the site is allowed into a cutover window. Duplicate rate, orphan rate, whatever the three things are that actually bite you. A site that fails the bar doesn't cut over — it gets a remediation window and it goes to the back of the queue. And crucially, somebody who isn't the programme manager owns the gate, because the programme manager has a date.

**Tanya Team:** That last part is pointed.

**Tony Maley:** It's meant to be. You are the person who will be tempted to wave a site through, and you should not be the person holding the gate. That's not a comment on you, it's the structure.

**Tanya Team:** No, that's fair. Nobody has said that to me yet.

**Tony Maley:** Nobody says it, because by the time it matters everyone has a date. Budget for it now: the gate costs you a site's worth of delay at least once, and if it never fires you set the bar too low.

**Tanya Team:** That's a good test.

**Tony Maley:** It's the only test I trust on quality gates. If it never stops anything, it isn't a gate.

**Tanya Team:** Anything else?

**Tony Maley:** The reference-data call is right too, for what it's worth, though I'd want to see the mirror's refresh interval before I said more. And the archive thing you mentioned in passing — do it. Everyone skips it and everyone regrets it around year six.

**Tanya Team:** We opened that last week, actually.

**Tony Maley:** Then you're further along than most. The sequencing and the archive you've got. The quality gate is the hole.

**Tanya Team:** I'll take that to the board as the open item rather than wait for them to find it.

**Tony Maley:** That's the right move. Bring them a hole you've named. They'll forgive a hole. They won't forgive finding one.
