# Product Reasoning Log

This log captures how the product question changed during the study, including assumptions that did not hold up, directions I rejected, and the reasoning behind the final proposal.

## Starting observation

This study started with my own attempt to establish an Instagram presence for an independently built iOS app.

I was a solo founder doing several jobs at once.

I owned the product. I created its content. I sometimes appeared personally in that content. I wanted to build an audience around what I was making and help interested people discover the product.

I understood why the account represented a business.

I also understood why my behavior resembled a creator.

I didn't understand which of those identities Instagram expected me to choose or what the practical consequences of that choice would be.

That created the first question:

> **What am I on this platform, and what am I supposed to do next?**

## Initial hypothesis: Instagram doesn't understand professional intent early enough

My first interpretation was that Instagram's professional experience did not ask enough about why the account existed.

That was only partially correct.

A fresh account walkthrough confirmed that initial account creation could happen without asking whether the account was personal or professional or what the user ultimately wanted to accomplish.

But further exploration showed that Instagram does eventually ask professional users about their goals.

That changed the problem.

## Fresh account walkthrough

I created a new Instagram account from an existing personal account and documented the flow.

The initial experience emphasized:

- creating the identity
- connecting it through Accounts Center
- basic profile setup
- discovering people and content
- notification choices

It did not ask for professional intent during the initial account-creation sequence.

That initially reinforced the idea that intent was missing.

But the next part of the walkthrough complicated that conclusion.

## Correction: Instagram does ask about goals

After converting to a professional account, I found a six-step professional setup experience.

One of those steps was:

**Tell us your goals**

So the claim:

> Instagram never asks what I'm trying to accomplish.

was wrong.

The more useful question became:

> **When does Instagram ask, and what does it mean by a goal?**

The options I encountered included:

**Reach · Media engagement · Shop engagement · Messages · Leads · Website visits · Calls · Texts · Emails**

Those are useful outcomes, metrics, and interaction channels.

But they were not how I would naturally describe why I had created the account.

My own intent was closer to:

**Share what I make · Build an audience · Grow something I own**

That became the first major reframing.

## Intent ≠ outcomes ≠ next steps

The professional setup mixed several kinds of information.

Some items described immediate actions:

**Complete your profile · Introduce yourself**

Some described platform capabilities:

**Explore tools and insights · Learn about how ads work**

And the goal step described outcomes or channels:

**Reach · Engagement · Website visits · Messages · Leads**

I was treating all of these as one onboarding problem.

They were not the same thing.

The distinction became:

### Intent

What am I trying to accomplish?

### Next steps

What can I do now?

### Outcomes

How might the platform observe progress?

This distinction became the foundation for the final proposal.

## Creator or Business?

Instagram asks professional users to choose between Creator and Business.

For many accounts, that may be straightforward.

My situation wasn't.

I owned and operated the product.

I also personally created the content.

Some content could be explicitly product-led.

Some could be founder-led.

Some could feature me personally while still supporting the product.

That initially made a hybrid account type seem like the obvious answer.

## Wrong turn: add a Creator Business account type

My first solution was essentially:

**Creator · Creator Business · Business**

A hybrid classification seemed capable of representing founders and creator-led businesses more accurately.

The more I examined it, the less useful it became.

It still required the user to understand the platform's taxonomy and choose the correct classification.

It also assumed that Creator and Business existed only as user-facing concepts.

Research into music licensing, advertising, commerce, monetization, APIs, and other professional capabilities showed that account classifications may support legitimate downstream requirements.

### Decision

Do not add another account type.

The problem was not that Instagram needed a better label for me.

The problem was that I was being asked to reason from Instagram's classification before Instagram had much context about what I was trying to accomplish.

## Relationship is not the same as account type

The hybrid-account discussion exposed another distinction.

A user's relationship to what they represent can overlap.

For the Customer 0 scenario:

**I own or run it**

and

**I create content for it**

can both be true.

Those facts do not necessarily need to become a new account type.

They can instead become context the platform uses where relevant.

That led to a layered model:

**Intent** — What am I trying to accomplish?

**Relationship** — What is my relationship to what this account represents?

**Platform state** — What classifications, eligibility, policy, legal, licensing, commercial, or technical state does the platform require?

**Experience** — What should the user see or be asked to do?

The important boundary became:

> **Intent informs the experience. It does not override policy or eligibility.**

## Wrong turn: redesign the Category taxonomy

During professional conversion, I searched for Founder and did not find it.

That initially looked like another taxonomy problem.

But Instagram's existing categories mix role-like concepts such as Entrepreneur and Digital Creator with subject-oriented concepts such as Product/service.

I do not know which downstream systems use Category.

Redesigning that taxonomy would therefore require assumptions the study could not support.

### Decision

Keep Category outside the scope of the proposal.

Intent becomes additional context rather than a replacement for Category.

## Wrong turn: solve posting and music

I also explored whether Persistent Intent Context should directly simplify posting and music eligibility.

This became too speculative.

Music availability can reflect real licensing constraints.

Commercial use can have legal significance.

A founder talking about her own product does not automatically map to a simple Creator-versus-Business content rule.

I considered a model where Instagram would infer post context from persistent intent and interrupt only when necessary.

The system logic was plausible, but the study did not have enough access to Instagram's actual policy and licensing architecture to make a credible product recommendation.

### Decision

Do not redesign the composer or music experience in this case.

Keep the principle:

> **Ask users about their reality. Let the platform translate that reality into its own complexity.**

But do not pretend to know exactly how Instagram should implement that translation for content policy.

## Wrong turn: redesign Insights

My own Post Insights initially confused me.

One post showed zero Profile visits while some views were attributed to Profile.

That made me question whether Instagram provided enough explanation for professional users to understand its analytics.

Deeper exploration changed that conclusion.

I found substantially more account-level Insights, content breakdowns, audience information, profile activity, and metric explanation than I had initially discovered.

The problem was therefore not as simple as:

> Instagram gives users numbers without explaining them.

That would have overstated the evidence.

I explored an intent-aware Insights concept but ultimately removed it from the final proposal.

### Decision

Do not redesign Insights in this case.

The narrower onboarding problem was better supported.

## Reframing the problem

The study started close to:

> Why is Instagram's professional ecosystem so confusing for a solo founder?

For a while it expanded into:

> How should Instagram redesign Creator/Business identity, posting policy, music, professional onboarding, and Insights around user intent?

That was too broad.

Research repeatedly showed that parts of the existing product were more capable or more constrained than I initially understood.

The final question became:

> **How might a platform reduce onboarding burden when a user's real-world intent doesn't map cleanly to its account classifications?**

## Solutions considered

### Add a hybrid account type

**Rejected.**

It adds another classification without removing the translation problem.

### Remove Creator and Business

**Rejected.**

The study cannot establish which downstream systems require those classifications.

### Redesign Category

**Rejected.**

Category may support systems the study cannot observe.

### Ask users to classify each post

**Rejected.**

It creates recurring cognitive burden and pushes platform complexity back onto the user.

### Infer intent from behavior

**Rejected for this proposal.**

Inference could reduce explicit questions but would make the model less transparent and introduce another assumption-heavy system.

### Capture persistent intent

**Pursued.**

It lets the user describe what they are trying to accomplish without requiring that description to replace platform classifications.

## Final product decision

Capture a small amount of explicit, persistent intent during profile setup.

For the Customer 0 scenario:

**Share what I make**

**Build an audience**

**Grow something I own**

Allow overlapping relationship context where relevant:

**I own or run it**

**I create content for it**

Then use that context to reduce and recompose the later professional onboarding journey.

Separate:

**Intent** — why the user is here

**Next steps** — what the user can do now

**Outcomes** — how the platform may observe progress

**Platform state** — what the platform must still classify, validate, or enforce

The platform can use intent to decide which onboarding actions and tools are relevant without pretending intent grants eligibility or replaces policy.

## Why reduce the second onboarding journey?

The observed professional setup included six steps:

**Complete your profile · Grow your audience · Introduce yourself · Explore tools and insights · Tell us your goals · Learn about how ads work**

Once intent is already known, these can be separated more deliberately.

Immediate next steps can remain prominent:

**Complete your profile · Build your audience · Share your first post**

Persistent intent can remain visible as context:

**Share what I make · Build an audience · Grow something I own**

Secondary tools can be introduced when relevant:

**Explore tools and insights**

Advertising or other professional capabilities can surface when intent and eligibility make them relevant rather than becoming universal onboarding work.

The objective is not to hide capabilities.

It is to reduce the amount of platform structure a user must learn before reaching a useful action.

## What would make the proposal fail?

The central guardrail is cumulative cognitive burden.

Adding an intent question is only worthwhile if it removes more work than it creates.

The proposal fails if users:

- answer more questions overall
- encounter more interruptions
- struggle to understand the new intent taxonomy
- have more difficulty discovering professional capabilities
- must repeatedly restate context the platform already has
- experience intent as another account classification rather than useful context

The product hypothesis is therefore not simply:

> Earlier intent is better.

It is:

> **A small amount of explicit intent can reduce more downstream translation and onboarding work than it adds upfront.**

## Remaining assumptions

The concept still needs validation.

The biggest unanswered questions are:

- How common is the classification and translation problem beyond Customer 0?
- Do founders, creators, businesses, and other hybrid users express intent more confidently than account type?
- Are the proposed intents understandable and sufficiently durable?
- Does multi-select intent create clarity or simply introduce another taxonomy?
- Does earlier intent actually reduce total onboarding effort?
- Which current systems depend on Creator, Business, Category, or existing goal fields?
- Which professional capabilities must still require explicit declarations or account conversion?
- Can progressive introduction of tools preserve discoverability?
- Is the problem consequential enough to justify changes to account and onboarding architecture?

The concept is a hypothesis, not a validated solution.

## What changed through the study

I started with:

> Why is Instagram's professional ecosystem so confusing for me as a solo founder?

I ended with:

> **How might a platform reduce onboarding burden when a user's real-world intent doesn't map cleanly to its account classifications?**

Along the way, I discarded a hybrid account type, a Category redesign, a posting and music redesign, and an Insights redesign.

Several initial criticisms also became weaker after I explored more of the existing product.

That narrowing became the most useful part of the study.

The goal was not to prove that Instagram's current onboarding is wrong.

It was to understand which parts of my confusion reflected a broader product-model question, which parts already had answers elsewhere in the product, and where a smaller intervention could be worth testing.
