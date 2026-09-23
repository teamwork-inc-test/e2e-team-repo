---
reviewers:
  - tanya+staging@aswritten.ai
---

# Halyard Cutover Review — 2026-09-15

> Source: authored fixture transcript (task-701.01, synthetic). Participants: Tanya Team, Tina Team, Xavier Expert.

# Halyard Cutover Review
2026-09-15

**Tina Team:** Before we start on anything else, I need to correct something I said, and I'd rather do it at the top than bury it.

**Tanya Team:** Go ahead.

**Tina Team:** On the eighth I said the soak between sites has to be two full weeks, and I said I'd hold us to it. That was wrong. I was wrong on the eighth and I want it struck from the plan.

**Tanya Team:** Right. Tell me why.

**Tina Team:** I quoted the Dockside number — the exception queue not flattening until day nine or ten. I went back through the Dockside logs on Friday because Xavier's comment about it being one site, one season was bothering me. The reason the queue took nine days to flatten at Dockside is that the old reconciliation job ran weekly and every run threw a fresh batch of exceptions. Two weeks was two reconciliation cycles. It was never about the site settling.

**Xavier Expert:** And that job is gone.

**Tina Team:** That job is gone. It was retired in July. Nothing in the new platform runs on a weekly cycle — reconciliation is continuous now. So the number I gave was measuring a job that doesn't exist any more, and I attached it to the soak as though it were a property of the site.

**Tanya Team:** So what is the soak?

**Tina Team:** One week. Strip the reconciliation cycles out of the Dockside curve and the underlying exception rate is flat by day four. One week gives you the flattening plus three days to look at it, which is the same margin I was arguing for. One week is the soak, and please don't hold the plan to two weeks on my say-so, because I was wrong on the eighth.

**Tanya Team:** I want to be clear about what is and isn't changing here. We are still going one site at a time, and we are still soaking between sites before the next one starts.

**Tina Team:** Yes. That doesn't move at all. The sequencing is right. It's the number I put on the soak that was wrong.

**Tanya Team:** Good, because I've already said the sequencing out loud to Freya this morning and she gave me a better argument for it than either of us had.

**Xavier Expert:** Can I say that I think this is the right correction and also that it costs us something? Two weeks was conservative in a place where being conservative was cheap. One week is defensible but it has no slack in it.

**Tina Team:** That's true. I'd rather be defensible and know where the slack isn't than conservative for a reason that turned out to be imaginary.

**Xavier Expert:** Agreed. I just want it on the record that the new number is tight, not safe.

**Tanya Team:** Noted. Tina, does this change the four-site total?

**Tina Team:** It takes three weeks out of the programme. Four sites, three soaks between them, a week off each.

**Tanya Team:** Which I will not be spending. That goes into the Clyde buffer.

**Tina Team:** I'd assumed so.

**Tanya Team:** Right. For the record then: the soak between sites is one week, not two, and my note from the eighth about two weeks should be read as superseded by this. Tina, can you put the Dockside re-analysis somewhere the steering group can see it? They heard me say two weeks on the tenth.

**Tina Team:** I'll write it up today.

**Tanya Team:** Thank you for bringing it rather than letting it ride.

**Tina Team:** It would have come out at Northgate either way, and worse.
