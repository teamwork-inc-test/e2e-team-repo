---
reviewers:
  - tanya+staging@aswritten.ai
---

# Tess's Channel-Strategy Feedback and Archetype Reclassification (Apr 23, 2026)

> Written up by Claude (claude-opus-5-5), the assistant in Tanya Team's session, from Tanya's account of her conversation with Tess Guest. Tess's words are as Tanya relayed them; Tanya's are verbatim.

## Context

Morning conversation with Tess. Tanya had just learned that seven Twilio toll-free numbers she'd submitted for verification all came back rejected — the stated reasons pointed at the website not being active (likely a bad link) and the opt-in form requirement (also likely a bad link). The numbers can be re-submitted and are back in the review queue. Separately, Tanya had been asking whether SMS is actually the right demo strength for beta users like Tess and Pat. She surfaced that question with Tess directly. Tess and Tanya both know Pat personally.

## Tess's Channel Insight: SMS Is Spam-Coded in Low-Trust Contexts

Tess's response, reconstructed from Tanya's summary:

> Text message, in certain contexts, is absolutely the right move. But in a lot of skeptical or lower-trust contexts, texting is so associated with spam now that requiring someone to text might actually be a real downside. People might not want to give their number.

The SMS-feels-honest-not-bot framing holds when the sender is already trusted. It flips in evaluator contexts — SMS is *more* suspicious because spam trained people to distrust unexpected texts. Tanya's prior claim that SMS removes the "bot" mental frame is context-dependent, not universal.

The Twilio rejection context is load-bearing here, not incidental. Seven numbers, rejected en masse, for reasons adjacent to consent-form hygiene, with each beta user requiring their own verification path. The operational cost of the SMS onramp has been absorbed, not priced. Tess is naming the deeper version: even when verification succeeds, the channel carries a trust tax in evaluator-grade conversations.

## Tess's Proposal: Chat Widget on a Web Form

Verbatim from Tess (as relayed by Tanya):

> Can you just give me a chat widget on a web form?

Tanya's architectural response — a sketch, not yet a decision:

Front already has a chat widget, so the integration exists. Inboxes may still need to be manually created (open question), but channels under an inbox should be automatable. The proposal is one widget per share ID — provisioning a channel and widget at share-creation time means each share has its own conversation surface. Multiple widgets alive at once makes comparison across share IDs and branches natural. A managed aswritten-org inbox holds all these conversations, and conversations do not get assigned to anyone by default, including Tanya. No default-assignment avoids the "every new conversation lands on the founder" failure mode.

Tanya's conclusion: lower lift for the demo, lower lift for Tess and others in her category, potentially much more useful.

## Narrowing the SMS Framing, Not Killing It

Two prior corrections in the perspective already walked the "SMS is the product" framing back from its strongest form — the SMS-first product is an overstatement, it's an open product idea, and the consumer motion is gated on understanding usage patterns and cost-per-behavior.

Today's insight narrows it further. SMS remains viable for high-trust, post-consent, consumer-viral contexts — the channel works where the sender is already welcome. A chat widget on the share page is the right fit for evaluator, skeptic, first-touch, and demo contexts — no number, no verification, no opt-in form, no spam frame. The share page itself is the trust context, so the widget inherits it. This is a scoping, not a replacement. The toll-free verification cost per beta user stops being load-bearing for demo strategy, but SMS stays alive in the contexts where it actually works.

## Archetype Reclassification: Tess is a Knowledge Packager

The perspective currently classifies Tess as a Knowledge-Rich Consumer (Archetype C2) and uses her as the exemplar for the Trigger-1 solo-professional archetype. But Tess creates trainings. Her operational goal for the next six months — already captured in the perspective — is to generalize and prepackage her existing training content for scalability. That is the Knowledge Packager motion, identical in structure to how Pat Quill is described ("has expertise they want to distribute"). Tess is a Knowledge Packager.

The underlying error: the typology mixed two orthogonal axes — AI-fluency (tinkerer vs consumer) and distribution-motion (packager vs solo-practitioner) — and classified Tess on fluency only. When Tess told Tanya she was "similar to Pat and some other folks," she was naming her distribution motion, not her AI-fluency profile. Pat and Tess are both Knowledge Packagers; they differ on other axes (Pat has HIPAA requirements; Tess does not). Tess and Tanya both know Pat personally — the comparison is grounded in direct familiarity, not abstraction.

## The Commercial-Status Correction

Tanya's exact framing:

> She's on Individual because she's my fiancé and beta tester, not a sales target — although she fits the profile.

Tess's Individual-tier placement is a relational arrangement, not a sales-validated pricing decision. Three facts that the perspective has collapsed into one classification should be held separately:

Her archetype by work motion is Knowledge Packager. Her commercial status is "relational" — fiancé and beta tester, on the Individual tier by arrangement, not by sales logic. Her role in the business is primary beta tester — the highest-volume source of product feedback in the company.

The implications follow from separating these. Tess doesn't validate Individual-tier pricing, because she isn't a prospect — using her as the Trigger-1 exemplar implies "here's what an Individual-tier user looks like and pays," and she doesn't pay. Tess doesn't invalidate Professional-tier pricing either — her non-payment reflects relationship, not rejected conversion. And Tess's actual role as primary beta tester is absent from the perspective today. The "SMB beta cohort" entry names Sol, Pat, Marlo K, Loomhouse Co-op — but not Tess, despite her being the highest-volume feedback source.

Tanya's framing of that role:

> The vast majority of her feedback is verbal and I just implement. She's the single most prolific beta tester and has had more feedback than anyone.

## Retroactively Surfaced: March 4 Onboarding UX Feedback

The March 4 Wren onboarding session contains product feedback from Tess that was captured in the transcript but not surfaced when the memory was framed as "Wren's domain knowledge." The feedback is in the source material and belongs in Tess's beta-tester record.

**Tool-language critique [~59:59–01:05:03]:** When Tess got stuck after installing the connector and didn't know what to say, Tanya named the pattern:

> Feel like this is actually one of the hardest parts about this thing. Someone's like, what do I say now? And I'm like, I don't know, like, kind of anything.

Tess's response prescribed the fix directly:

> It's almost like once connected, blah, come back and compile. I feel like it's really like, visit this link, install it, come back and say done.

This is a specific prescription for clearer tool-language prompts. The review-without-leaving-chat feature Tanya mentioned on the same call addresses an adjacent problem but not this one.

**GitHub opacity feedback [~01:01:10]:**

> Everything you said about committing and pulling and all of that is completely foreign to me. And so, you know, because I don't understand how that works, even some of the little things where you came back and just wrote one word — like that, you clearly have an understanding of how the back end works. And that didn't make sense. Some of the things you just were like, oh, clearly this one word is what it needs. I'm like, that did not make sense to me.

The above-the-line abstraction work is motivated in part by exactly this cognitive cost.

## Operational Items

The seven rejected Twilio toll-free numbers are resubmitted to the review queue. Root cause is likely bad website link plus bad opt-in form link. If verification fails again, that's the signal to stop investing in the SMS onramp for evaluator contexts and pivot to the chat widget.

A Front chat widget spike would confirm whether inbox creation is API-automatable or manual-only, and prototype one share → one widget → one channel → one aswritten-org-inbox thread, verifying that conversations don't auto-assign to Tanya.

Demo 1 channel needs an explicit decision. The Apr 13 Keystone call used live SMS. Whether the chat widget replaces or augments SMS for Demo 1 is a decision, not a drift.

Tess's feedback pipeline needs a capture mechanism. Her beta-tester role is only defensible if her verbal feedback actually reaches the perspective. Options include her writing her own memories, Tanya dictating them after conversations, or a lightweight voice-memo-to-memory pipeline.

## Open Questions

Whether the chat widget replaces or augments SMS for Tess-category users. Whether Front inbox creation is API-automatable. Whether Pat specifically benefits from chat widget versus SMS (Tess grouped herself with him, but his HIPAA-adjacent context might invert the trust tax). Whether the underlying typology needs fixing (the fluency-vs-distribution axis collision that misclassified Tess may misclassify others too).