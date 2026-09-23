---
reviewers:
  - tanya+staging@aswritten.ai
---

# Halyard — Legacy Archive Working Session — 2026-09-22

> Source: authored fixture transcript (task-701.01, synthetic). Participants: Tanya Team, Xavier Expert, Tina Team.

# Halyard — Legacy Archive Working Session
2026-09-22

**Tanya Team:** This one is a topic we have genuinely never opened. Legal came to me on Friday with a question nobody in this programme has an answer to, and I'd rather we form a view than have one handed to us.

**Xavier Expert:** Which question?

**Tanya Team:** What happens to the records that stay behind. Everything from before a site's cutover lives in the old platform. We migrate the open work. We do not migrate the closed history — eleven years of it.

**Xavier Expert:** Right, and the vendor's contract ends when the last site goes live, so at some point that platform gets switched off.

**Tanya Team:** That's the question. When, and in what state.

**Tina Team:** I'd assumed we'd just keep paying the vendor to leave it running.

**Xavier Expert:** That's the expensive answer and it's also the fragile one. A system nobody uses and nobody patches is a system that stops working quietly, and you find out the day someone needs a consignment record from 2019 for a claim.

**Tanya Team:** That's exactly the scenario legal raised.

**Xavier Expert:** Then here's the view I'd take, and I'd take it firmly. We do not keep the legacy platform alive as a read-only system. We extract the closed history into a flat, self-describing archive — the records plus a schema description plus a document explaining what the fields mean — and we hold that. The archive outlives the platform.

**Tanya Team:** Say more about "self-describing".

**Xavier Expert:** Meaning you can read it in ten years with nothing but the files. Not a database dump that needs the vendor's version of their engine to restore. Not a proprietary export format. Flat files, an open format, a schema next to them, and a written description of what a "consignment status of 7" actually meant in 2017, because nobody will remember and the vendor won't exist.

**Tina Team:** That last part is the bit that always gets skipped.

**Xavier Expert:** It's the only part that matters in year eight. The data is easy to keep. The meaning is what rots.

**Tanya Team:** What's the argument against?

**Xavier Expert:** Cost and effort now, against a risk that lands years from now on someone who isn't in this room. That's the whole argument against, and it's why it never gets done.

**Tanya Team:** I'm persuaded. I'd add a reason of my own: a live legacy platform is a thing people will keep using. If Ferry Road can still look something up in the old system, someone at Ferry Road will, and then we've got two systems of record for a year. An archive that is obviously an archive kills that.

**Xavier Expert:** That's a better argument than mine, actually. Mine is about decay. Yours is about behaviour.

**Tanya Team:** Both go in the note.

**Tina Team:** How long do we hold it?

**Tanya Team:** Legal says seven years from the record date for the consignment data. I want to go beyond that for the claims-relevant subset, and I don't want to decide that number today — I want legal to give us one in writing.

**Tina Team:** Sensible.

**Tanya Team:** So the position is: the legacy platform is switched off when the last site goes live, the closed history is extracted first into an open self-describing archive, and the retention period comes from legal in writing before we sign anything with the vendor about decommissioning.

**Xavier Expert:** I'd sign up to that.

**Tina Team:** Me too. And this needs to be in the vendor exit conversation, not after it.

**Tanya Team:** Yes. That's the thing I'd have got wrong if legal hadn't asked on Friday — I'd have signed the decommissioning terms first and discovered the extraction requirement afterwards.

**Xavier Expert:** Which is the order these always go in.

**Tanya Team:** Not this time. Xavier, can you scope the extraction enough that I can put a number in front of the vendor?

**Xavier Expert:** Give me until the end of next week.
