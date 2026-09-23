---
reviewers:
  - tanya+staging@aswritten.ai
---

# The product is not a phone number — channel is distribution, not identity

> Written up by Claude (claude-opus-5-5), the assistant in Tanya Team's session. Tanya's words are verbatim; Tess Guest's are as Tanya relayed them.

**Date:** April 28, 2026
**Source:** Conversation between Tanya Team and Claude (Claude.ai mobile session)
**Context:** Triggered by feedback from Tess Guest on whether SMS is the right demo channel for her cohort, plus the operational pain of seven failed Twilio toll-free verifications.

## The correction

The graph has "the product is a phone number" embedded as a tagline-level claim in the Identity section. **This is incorrect.** Tanya has tried to correct this before. It keeps re-embedding because the text-for-topic experiment generated many memories that asserted SMS-as-product confidently, and the extraction pipeline can't currently distinguish "this was the channel for an experiment we ran" from "this is what the product IS."

Tanya, verbatim from this session:

> "The text for topic memory was really an exploration, and this one has a couple of claims in it, but the one that the product is a phone number got really deeply embedded into the graph. That's true in the text for topic case, but that was always a product experiment, one that points to an issue in the extraction process."

> "The product is not a phone number; it's the phone number distribution channel, and it's the right distribution channel for certain contexts."

## The corrected positive position

**The product is curated expertise installation** — a way to install expertise into your AI and verify where it's coming from. This is consistent with `Claim_CoreValuePropInstallExpertise` (Foundation-level, March 19, 2026 strategy session): *"A way to install expertise into your AI and verify where it's coming from."* Tanya at the time: "That's gold."

**The phone number / SMS is a distribution channel.** It is one of several. It is the right channel in some contexts (where the trust-signal of "this is not an AI chat" matters; where an enterprise client needs that texture and is willing to absorb the operational cost) and the wrong channel in others (where SMS reads as spam-adjacent, where prospects don't want to hand over their number, where the operational cost isn't justified).

## Why SMS feels right when it's right

Tanya, verbatim:

> "There is some real value to the way the phone number feels. That's really important: a phone number doesn't feel like an AI chat in the same way that chat does."

This is consistent with `Claim_SMSFormatHonesty` (Foundation): *"The SMS format makes AI personalization feel honest rather than fake because it removes the 'bot' mental frame associated with chat boxes."* That claim is **not superseded** by this correction. SMS-as-trust-signal remains genuine value. The correction is about scope: it's a *channel property*, not a product identity.

Tanya:

> "That's a bonus; it's an upsell."

## Why SMS is operationally expensive

Tanya's framing of the cost side:

> "It's also a lot more work because of the maintenance around fraud, et cetera, as we're seeing above with the verification."

The triggering operational evidence: seven additional Twilio toll-free numbers were submitted for verification and **all seven came back rejected** (April 28, 2026). The rejection reason traces to the website / opt-in form not being live or linkable at verification time. The numbers can be resubmitted to the review queue. This is not the first verification cycle and it will not be the last; verification churn is a permanent operational cost of running SMS at scale.

## The triggering conversation: Tess Guest's pushback

Tanya asked Tess whether SMS is the right demo channel for someone like Tess (Knowledge-Rich Consumer cohort, alongside Pat Quill and others). Tess's response, paraphrased by Tanya in this session:

> "She thinks that text message, in certain contexts, is absolutely the right move, but in a lot of skeptical or lower-trust contexts, texting is so associated with spam now that requiring someone to text might actually be a real downside. People might not want to give their number."

> "Can you just give me a chat widget on a web form?"

This is consistent with `Archetype_KnowledgeRichConsumer` (Stake): *"Main barrier is technical (MCP installation, GitHub abstraction), not behavioral."* Tess is named there as a canonical example. The new piece of evidence is: SMS-as-channel adds a **trust friction** for this archetype that doesn't exist for the Knowledge Packager (Pat Quill, course-distribution context) or the Delegator (Morgan Reyes, internal team enterprise context). Spam association is the specific friction.

## The extraction failure mode this corrects

Two named graph-structural gaps both contribute to the over-embedding:

1. **Temporality.** Already documented as `Claim_NarrAppliesAsOntologyExtension` (Notion, deferred post-launch): a `narr:appliesAs` predicate with values `current | nearFuture | exploration | speculative`. The text-for-topic experiment claims should have been tagged as `exploration`, not promoted to `current` worldview. The structural fix exists on paper, deliberately deferred from the April 9 launch to avoid breaking extraction tests.

2. **Subgraph segmentation / scoping.** Newly named in this session. Tanya:

> "Another is the segmentation of the domain or the scoping of subgraphs, I suppose. You can have all of the stuff that we're talking about in a sort of subgrouping."

There is currently no structural way to say "this cluster of claims belongs to the text-for-topic experiment subgraph, not to the root product definition." Everything bridges to everything; an experiment's local positioning gets pulled into global positioning purely because the claims were stated confidently at the time. **This is a new candidate for ontology work, distinct from temporality.** Captured separately as a notion in the companion memory.

## What this changes about prior canonical content

The Identity section of the worldview includes the line:

> tagline: "The product is a phone number."

This tagline should be **superseded**. The replacement positioning, in Tanya's voice from this session and consistent with prior strategy work:

> The product is curated expertise installation. The phone number is the distribution channel for contexts where the trust-signal of "not an AI chat" is worth its operational cost — primarily enterprise.

The other Identity tagline ("Feather your arrows.") is unaffected.

This memory is on `research/channel-strategy-correction` and **should not be auto-promoted** until the channel decision (companion memory) and the extraction-gap notion are reviewed together. The correction has been attempted before and re-failed; promotion needs to be explicit and accompanied by deletion of the old tagline assertion in the same transaction, not a parallel addition that extraction merges into a confused both-true state.

## What is *not* decided by this memory

- The full set of channels available for deployment (covered in companion memory).
- Which channels map to which tiers (deliberately undecided as of this session — see companion memory).
- Whether SMS becomes Enterprise-only specifically, or remains available across tiers as an opt-in upsell. Tanya, verbatim:

> "I think SMS is something that we should offer only for the enterprise plan, because we have to provision numbers individually and manage them and so on and so forth."

> "We don't know yet how this maps to tiers... I'm doing this as a demo right now, and I'm trying to get some of these larger clients on the hook... I don't want to make that decision right now."

The first quote is a leaning. The second is the actual epistemic state. The leaning is recorded; it is not yet a decision. **This distinction must be preserved through extraction.**

## Provenance

- Conversation: Claude.ai mobile session, April 28, 2026
- Speaker: Tanya Team (founder), in dialogue with Claude (Opus 4.7)
- Triggering events: Tess Guest conversation (same day or recent), seven Twilio toll-free verification rejections (same day)
- Related claims in graph: Claim_CoreValuePropInstallExpertise (Foundation), Claim_SMSFormatHonesty (Foundation), Archetype_KnowledgeRichConsumer (Stake), Claim_NarrAppliesAsOntologyExtension (Notion)
- Tagline being superseded: "The product is a phone number." (currently in Identity section of worldview)

reviewers:
  - tanya+staging@aswritten.ai
