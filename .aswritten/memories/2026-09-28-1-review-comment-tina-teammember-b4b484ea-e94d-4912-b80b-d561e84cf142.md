---
reviewers:
  - "tina+staging@aswritten.ai"
review-of:
  - "https://aswritten.ai/narrative#Expr_4HalyardCutoverReview20260915_13"
  - "https://aswritten.ai/narrative#Expr_4HalyardCutoverReview20260915_14"
  - "https://aswritten.ai/narrative#Expr_4HalyardCutoverReview20260915_15"
  - "https://aswritten.ai/narrative#Expr_4HalyardCutoverReview20260915_20"
  - "https://aswritten.ai/narrative#Expr_4HalyardCutoverReview20260915_3"
  - "https://aswritten.ai/narrative#Expr_4HalyardCutoverReview20260915_5"
  - "https://aswritten.ai/narrative#Expr_4HalyardCutoverReview20260915_7"
  - "https://aswritten.ai/narrative#Expr_4HalyardCutoverReview20260915_9"
  - "https://aswritten.ai/narrative#Expr_1HalyardWeekly20260908_17"
  - "https://aswritten.ai/narrative#Expr_1HalyardWeekly20260908_19"
  - "https://aswritten.ai/narrative#Expr_1HalyardWeekly20260908_20"
  - "https://aswritten.ai/narrative#Expr_1HalyardWeekly20260908_22"
review-act: "pos-a6acb9066bd038bacceb2dce432c3242ab20144eb1bd751e946cd2cb59a54eac"
---

# Tina Team's review of 'how is the minimum soak duration between site cutovers …' · 28 Sep

Tina Team reviewed a change to a position and suggested a change to it, with one comment. Everything under "What was under review" is quoted from the perspective as the review page showed it; none of it is Tina Team's words. The comment itself is the last section.

## What was under review

### The position

> how is the minimum soak duration between site cutovers determined and validated?

### The change under review

- The change: Halyard Cutover Review, 15 Sep
- Statements this change added:

  > Can I say that I think this is the right correction and also that it costs us something? Two weeks was conservative in a place where being conservative was cheap. One week is defensible but it has no slack in it.

  > That's true. I'd rather be defensible and know where the slack isn't than conservative for a reason that turned out to be imaginary.

  > Agreed. I just want it on the record that the new number is tight, not safe.

  > Right. For the record then: the soak between sites is one week, not two, and my note from the eighth about two weeks should be read as superseded by this.

  > On the eighth I said the soak between sites has to be two full weeks, and I said I'd hold us to it. That was wrong. I was wrong on the eighth and I want it struck from the plan.

  > I quoted the Dockside number — the exception queue not flattening until day nine or ten. I went back through the Dockside logs on Friday because Xavier's comment about it being one site, one season was bothering me. The reason the queue took nine days to flatten at Dockside is that the old reconciliation job ran weekly and every run threw a fresh batch of exceptions. Two weeks was two reconciliation cycles. It was never about the site settling.

  > That job is gone. It was retired in July. Nothing in the new platform runs on a weekly cycle — reconciliation is continuous now. So the number I gave was measuring a job that doesn't exist any more, and I attached it to the soak as though it were a property of the site.

  > One week. Strip the reconciliation cycles out of the Dockside curve and the underlying exception rate is flat by day four. One week gives you the flattening plus three days to look at it, which is the same margin I was arguing for. One week is the soak, and please don't hold the plan to two weeks on my say-so, because I was wrong on the eighth.

- Statements this change removed:

  > Agreed, and I want to put a number on the soak, because "a soak" without a number turns into three days the first time someone's under pressure. The soak is two full weeks. That's the Dockside number, and I'd hold us to it.

  > Dockside pilot, back in the spring. We watched the exception queue after go-live and it didn't flatten out until day nine or ten. Two weeks gives you the flattening plus a few days to actually look at what flattened. Anything less and you're starting the next site while you're still finding out what the last one did.

  > That's the reasoning I wanted on the record. Two weeks, from the Dockside exception curve.

  > It's one site, one season, and it's the only site we've actually done. I'd rather hold two weeks and shorten it with evidence than hold one week and discover we needed two.

### The position's statements

Each statement is quoted as the review page shows it, with up to two lines on either side from the document it came from.

#### Statement 1

- Said by: Xavier Expert
- From: Halyard Weekly, 8 Sep, line 53
- Sits under these positions:

  > how is the minimum soak duration between site cutovers determined and validated?

  The lines before it:

  > **Tina Team:** Dockside pilot, back in the spring. We watched the exception queue after go-live and it didn't flatten out until day nine or ten. Two weeks gives you the flattening plus a few days to actually look at what flattened. Anything less and you're starting the next site while you're still finding out what the last one did.
  > **Tanya Team:** That's the reasoning I wanted on the record. Two weeks, from the Dockside exception curve.

  The statement:

  > I'll note that the exception curve is the only evidence we have for it. It's one site, one season.

  The lines after it:

  > **Tina Team:** It's one site, one season, and it's the only site we've actually done. I'd rather hold two weeks and shorten it with evidence than hold one week and discover we needed two.
  > **Tanya Team:** Agreed. Xavier, replica numbers.

#### Statement 2

- Said by: Freya Free
- From: Halyard Ops Readiness, 15 Sep, line 51
- Sits under these positions:

  > how is the minimum soak duration between site cutovers determined and validated?

  The lines before it:

  > **Xavier Expert:** No. It reinforces. The replica rule and the reference-data rule both assume one cutover window open at a time — I hadn't stated that assumption, and it's worth stating. If we ever went parallel, both of those would need rewriting.
  > **Tanya Team:** Then let's not go parallel. Freya, what do you need from me?

  The statement:

  > The dates, as early as you can give them, and a commitment that a soak doesn't get shortened because a date slipped. If the soak gets eaten, my supervisors are back on the floor at the same time as the next cutover and we're in the same place by another route.

  The lines after it:

  > **Tanya Team:** That's fair and I'll hold it.
  > **Freya Free:** Then I'm content.

#### Statement 3

- Said by: Tanya Team
- From: Halyard Ops Readiness, 15 Sep, line 53
- Sits under these positions:

  > how is the minimum soak duration between site cutovers determined and validated?

  The lines before it:

  > **Tanya Team:** Then let's not go parallel. Freya, what do you need from me?
  > **Freya Free:** The dates, as early as you can give them, and a commitment that a soak doesn't get shortened because a date slipped. If the soak gets eaten, my supervisors are back on the floor at the same time as the next cutover and we're in the same place by another route.

  The statement:

  > That's fair and I'll hold it.

  The lines after it:

  > **Freya Free:** Then I'm content.
  > **Tanya Team:** Thanks, Freya. Genuinely useful.

#### Statement 4

- Said by: Tina Team
- From: Halyard Cutover Review, 15 Sep, line 17
- Added by the change under review
- Sits under these positions:

  > how is the minimum soak duration between site cutovers determined and validated?

  The lines before it:

  > **Tina Team:** Before we start on anything else, I need to correct something I said, and I'd rather do it at the top than bury it.
  > **Tanya Team:** Go ahead.

  The statement:

  > On the eighth I said the soak between sites has to be two full weeks, and I said I'd hold us to it. That was wrong. I was wrong on the eighth and I want it struck from the plan.

  The lines after it:

  > **Tanya Team:** Right. Tell me why.
  > **Tina Team:** I quoted the Dockside number — the exception queue not flattening until day nine or ten. I went back through the Dockside logs on Friday because Xavier's comment about it being one site, one season was bothering me. The reason the queue took nine days to flatten at Dockside is that the old reconciliation job ran weekly and every run threw a fresh batch of exceptions. Two weeks was two reconciliation cycles. It was never about the site settling.

#### Statement 5

- Said by: Tina Team
- From: Halyard Cutover Review, 15 Sep, line 21
- Added by the change under review
- Sits under these positions:

  > how is the minimum soak duration between site cutovers determined and validated?

  The lines before it:

  > **Tina Team:** On the eighth I said the soak between sites has to be two full weeks, and I said I'd hold us to it. That was wrong. I was wrong on the eighth and I want it struck from the plan.
  > **Tanya Team:** Right. Tell me why.

  The statement:

  > I quoted the Dockside number — the exception queue not flattening until day nine or ten. I went back through the Dockside logs on Friday because Xavier's comment about it being one site, one season was bothering me. The reason the queue took nine days to flatten at Dockside is that the old reconciliation job ran weekly and every run threw a fresh batch of exceptions. Two weeks was two reconciliation cycles. It was never about the site settling.

  The lines after it:

  > **Xavier Expert:** And that job is gone.
  > **Tina Team:** That job is gone. It was retired in July. Nothing in the new platform runs on a weekly cycle — reconciliation is continuous now. So the number I gave was measuring a job that doesn't exist any more, and I attached it to the soak as though it were a property of the site.

#### Statement 6

- Said by: Tina Team
- From: Halyard Cutover Review, 15 Sep, line 25
- Added by the change under review
- Sits under these positions:

  > how is the minimum soak duration between site cutovers determined and validated?

  The lines before it:

  > **Tina Team:** I quoted the Dockside number — the exception queue not flattening until day nine or ten. I went back through the Dockside logs on Friday because Xavier's comment about it being one site, one season was bothering me. The reason the queue took nine days to flatten at Dockside is that the old reconciliation job ran weekly and every run threw a fresh batch of exceptions. Two weeks was two reconciliation cycles. It was never about the site settling.
  > **Xavier Expert:** And that job is gone.

  The statement:

  > That job is gone. It was retired in July. Nothing in the new platform runs on a weekly cycle — reconciliation is continuous now. So the number I gave was measuring a job that doesn't exist any more, and I attached it to the soak as though it were a property of the site.

  The lines after it:

  > **Tanya Team:** So what is the soak?
  > **Tina Team:** One week. Strip the reconciliation cycles out of the Dockside curve and the underlying exception rate is flat by day four. One week gives you the flattening plus three days to look at it, which is the same margin I was arguing for. One week is the soak, and please don't hold the plan to two weeks on my say-so, because I was wrong on the eighth.

#### Statement 7

- Said by: Tina Team
- From: Halyard Cutover Review, 15 Sep, line 29
- Added by the change under review
- Sits under these positions:

  > how is the minimum soak duration between site cutovers determined and validated?

  The lines before it:

  > **Tina Team:** That job is gone. It was retired in July. Nothing in the new platform runs on a weekly cycle — reconciliation is continuous now. So the number I gave was measuring a job that doesn't exist any more, and I attached it to the soak as though it were a property of the site.
  > **Tanya Team:** So what is the soak?

  The statement:

  > One week. Strip the reconciliation cycles out of the Dockside curve and the underlying exception rate is flat by day four. One week gives you the flattening plus three days to look at it, which is the same margin I was arguing for. One week is the soak, and please don't hold the plan to two weeks on my say-so, because I was wrong on the eighth.

  The lines after it:

  > **Tanya Team:** I want to be clear about what is and isn't changing here. We are still going one site at a time, and we are still soaking between sites before the next one starts.
  > **Tina Team:** Yes. That doesn't move at all. The sequencing is right. It's the number I put on the soak that was wrong.

#### Statement 8

- Said by: Xavier Expert
- From: Halyard Cutover Review, 15 Sep, line 37
- Added by the change under review
- Sits under these positions:

  > how is the minimum soak duration between site cutovers determined and validated?

  The lines before it:

  > **Tina Team:** Yes. That doesn't move at all. The sequencing is right. It's the number I put on the soak that was wrong.
  > **Tanya Team:** Good, because I've already said the sequencing out loud to Freya this morning and she gave me a better argument for it than either of us had.

  The statement:

  > Can I say that I think this is the right correction and also that it costs us something? Two weeks was conservative in a place where being conservative was cheap. One week is defensible but it has no slack in it.

  The lines after it:

  > **Tina Team:** That's true. I'd rather be defensible and know where the slack isn't than conservative for a reason that turned out to be imaginary.
  > **Xavier Expert:** Agreed. I just want it on the record that the new number is tight, not safe.

#### Statement 9

- Said by: Tina Team
- From: Halyard Cutover Review, 15 Sep, line 39
- Added by the change under review
- Sits under these positions:

  > how is the minimum soak duration between site cutovers determined and validated?

  The lines before it:

  > **Tanya Team:** Good, because I've already said the sequencing out loud to Freya this morning and she gave me a better argument for it than either of us had.
  > **Xavier Expert:** Can I say that I think this is the right correction and also that it costs us something? Two weeks was conservative in a place where being conservative was cheap. One week is defensible but it has no slack in it.

  The statement:

  > That's true. I'd rather be defensible and know where the slack isn't than conservative for a reason that turned out to be imaginary.

  The lines after it:

  > **Xavier Expert:** Agreed. I just want it on the record that the new number is tight, not safe.
  > **Tanya Team:** Noted. Tina, does this change the four-site total?

#### Statement 10

- Said by: Xavier Expert
- From: Halyard Cutover Review, 15 Sep, line 41
- Added by the change under review
- Sits under these positions:

  > how is the minimum soak duration between site cutovers determined and validated?

  The lines before it:

  > **Xavier Expert:** Can I say that I think this is the right correction and also that it costs us something? Two weeks was conservative in a place where being conservative was cheap. One week is defensible but it has no slack in it.
  > **Tina Team:** That's true. I'd rather be defensible and know where the slack isn't than conservative for a reason that turned out to be imaginary.

  The statement:

  > Agreed. I just want it on the record that the new number is tight, not safe.

  The lines after it:

  > **Tanya Team:** Noted. Tina, does this change the four-site total?
  > **Tina Team:** It takes three weeks out of the programme. Four sites, three soaks between them, a week off each.

#### Statement 11

- Said by: Tanya Team
- From: Halyard Cutover Review, 15 Sep, line 51
- Added by the change under review
- Sits under these positions:

  > how is the minimum soak duration between site cutovers determined and validated?

  The lines before it:

  > **Tanya Team:** Which I will not be spending. That goes into the Clyde buffer.
  > **Tina Team:** I'd assumed so.

  The statement:

  > Right. For the record then: the soak between sites is one week, not two, and my note from the eighth about two weeks should be read as superseded by this.

  The lines after it:

  > **Tina Team:** I'll write it up today.
  > **Tanya Team:** Thank you for bringing it rather than letting it ride.

### Where the position sits

- Narrative: contained pain over unbounded risk

  - Beside it:

    > how should multi-site cutovers be sequenced when operational containment conflicts with local site friction?

- Stratum: cutover strategy

### The act

- Tina Team suggested a change to the change under review

## The comment

Tina Team (tina+staging@aswritten.ai) commented:

> the one-week soak should name who signs off the second site before it starts
