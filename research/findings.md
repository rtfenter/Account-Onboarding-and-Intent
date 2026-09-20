# Research Findings

This document contains the factual platform research behind the product study. Interpretations and product decisions are documented separately in the Product Reasoning Log.

This study began with my own experience using Instagram to establish a presence for an independently built iOS app. Personal observations are treated as Customer 0 evidence, not evidence that every user encounters the same problems.

Platform behavior and documentation were researched in September 2026.

## Account creation

I completed a fresh Instagram account-creation flow from an existing personal account.

The observed flow prioritized basic account creation and profile setup before professional context.

During the initial flow, I encountered:

- username creation
- Accounts Center setup
- terms and privacy information
- profile photo and basic profile setup
- people and account discovery
- notification choices

I was not asked during this initial account-creation sequence whether the new account was intended for personal or professional use or what I ultimately wanted Instagram to help me accomplish.

This does not mean Instagram never asks about professional intent. Professional context is introduced later.

## Professional conversion

Instagram provides a path to switch an existing account to a professional account.

During direct exploration, professional conversion was available through Edit Profile. The professional flow introduced category, professional account type, professional capabilities, professional setup, and goals.

Instagram distinguishes between Creator and Business professional accounts.

The descriptions presented during the observed flow positioned Creator around public figures, content producers, artists, and influencers, while Business was positioned around retailers, local businesses, brands, organizations, and service providers.

The distinction may support product, commercial, legal, licensing, monetization, advertising, commerce, API, or other platform requirements that are not visible from the interface alone.

This study therefore does not assume the classifications can simply be removed internally.

## Category

Professional setup asks the user to select a category.

Observed categories included:

- Entrepreneur
- Digital Creator
- Product/service
- Reel Creator
- Clothing (Brand)
- Blogger

Searching for Founder did not return a Founder category during the observed flow.

The category taxonomy mixes concepts that can describe a role, identity, business, or subject. Entrepreneur and Digital Creator are role-oriented, while Product/service is more subject- or business-oriented.

This study does not establish what downstream systems depend on Category and does not propose replacing the existing taxonomy.

## Creator and Business can overlap in practice

The Customer 0 scenario did not map cleanly to a single intuitive identity.

The account represented an independently built consumer app. The same person owned and operated the product, created its content, sometimes appeared personally in that content, wanted to build an audience, and wanted interested people to discover the product.

That makes Creator and Business understandable platform concepts but less intuitive as mutually exclusive descriptions of the user's real-world role.

External research also suggests that creator and business behavior increasingly overlaps. LinkedIn removed its Creator Mode on/off toggle in 2024 and folded eligible creator capabilities into the broader product rather than requiring users to maintain a separate creator identity mode.

Industry research also suggests that many small-business owners identify with creator behavior, although that evidence does not establish how common the specific Instagram onboarding problem is among solo founders.

The strongest defensible conclusion is not that Creator and Business are obsolete categories. It is that some users may occupy both kinds of behavior simultaneously.

## Professional onboarding

After professional conversion, Instagram provides a professional setup experience.

The observed setup contained six steps:

**Complete your profile · Grow your audience · Introduce yourself · Explore tools and insights · Tell us your goals · Learn about how ads work**

These steps mix profile completion, immediate user actions, audience growth, product education, measurement preferences, and advertising education.

## How Instagram asks about goals

The observed professional setup includes a Tell us your goals step.

The available options included:

- Reach
- Media engagement
- Shop engagement
- Messages
- Leads
- Website visits
- Calls
- Texts
- Emails

Instagram also asks how the user would like to connect with people, with options including Comments, Messages, Leads, Calls, Texts, and Emails.

These are legitimate outcomes, metrics, or interaction channels. They are not necessarily equivalent to the user's underlying reason for using Instagram.

For the Customer 0 scenario, the underlying intent was closer to:

**Share what I make · Build an audience · Grow something I own**

This distinction between intent and measurable outcomes became central to the product study.

## Account context and cross-account personalization

Meta documents that Accounts Center can use information across connected accounts to personalize experiences across Meta technologies, including account suggestions.

During the fresh account walkthrough, I declined explicit people-following onboarding and later saw a person from my existing personal social graph recommended to the new account.

That observation does not establish why that specific recommendation appeared. Multiple signals may have contributed.

**Documented:** Meta can use information across connected accounts for personalization and account suggestions.

**Observed:** A personal connection was recommended immediately after creating the new account.

**Unknown:** Which signal or combination of signals caused that particular recommendation.

This study does not use the observation as evidence of causation.

## Professional capabilities can have legitimate policy constraints

Research into professional account differences showed that some product distinctions may exist for reasons beyond onboarding UX.

One example is music licensing. Meta documents restrictions on licensed music for some commercial uses and provides Sound Collection as a commercially usable alternative in applicable contexts.

Similar constraints may exist across advertising, commerce, monetization, verification, APIs, branded content, merchant requirements, and safety or policy enforcement.

The onboarding proposal therefore cannot assume that declared intent should determine eligibility.

## What the evidence can establish

### Professional intent is captured relatively late

Initial account creation can occur without establishing why the new identity exists. Professional conversion, account type, professional setup, and platform-defined goals occur later.

### Creator and Business are platform classifications, not complete descriptions of every user

A founder can simultaneously own a business and create content for it.

That does not establish that Instagram should remove either classification. It does establish that the user's real-world relationship can contain more than one role.

### Instagram already asks about goals

The problem is not that Instagram never asks what a professional user wants. The observed goal model is primarily expressed through outcomes, metrics, and interaction channels.

### Intent, outcomes, and next steps are different concepts

A user can intend to grow something they own. Website visits may be one observable outcome. Sharing a first post may be one immediate next step.

### Platform classifications may have legitimate downstream dependencies

The user-facing experience alone cannot establish which internal systems require Creator, Business, Category, or other classifications.

## What the evidence cannot establish

This research does not establish:

- how many Instagram users experience this problem
- whether solo founders are a large enough cohort to justify investment
- whether Creator and Business should disappear internally
- whether the proposed intent taxonomy is correct
- which current Meta systems depend on account type or Category
- how much existing account state could be reused for Persistent Intent Context
- whether capturing intent earlier would improve professional activation or retention
- whether the additional questions would reduce or increase total cognitive burden

Those require product data, technical knowledge, or original user research unavailable in this study.

## Key findings that informed the product decision

### 1. The initial problem was broader than the evidence supported

The study began with confusion across account type, recommendations, music, posting, and Insights. Deeper exploration showed that several of those areas already had more product support than I initially understood.

The final proposal therefore narrowed to onboarding and classification.

### 2. The issue is not simply Creator versus Business

Adding another hybrid account type would still require the user to translate themselves into the platform's taxonomy.

The more useful distinction became:

**What is the user trying to accomplish?**

versus:

**What classification does the platform require internally?**

### 3. Instagram's existing goals are useful but represent a different layer

Reach, engagement, website visits, messages, and leads can all be meaningful outcomes. They do not necessarily describe the user's underlying intent.

### 4. Relationships can overlap

A user can own a product and create content for it simultaneously.

### 5. Intent should inform experience, not override platform truth

Legal, policy, licensing, eligibility, commerce, and other platform requirements remain authoritative.

### 6. The strongest intervention was smaller than the original redesign

The final proposal does not redesign posting, music, Insights, Category, or Instagram's internal account architecture.

It captures lightweight intent earlier and uses it to reduce and recompose the professional onboarding experience.

## Sources

## Meta / Instagram

**Instagram Help Center: About professional accounts on Instagram**

Used for:

- professional account model
- Creator and Business account concepts
- professional-account capabilities

**Instagram Help Center: Switch to a professional account**

Used for:

- professional conversion flow
- category selection
- Creator / Business selection

**Meta Accounts Center documentation**

Used for:

- cross-account personalization
- account suggestions across connected Meta accounts
- distinction between connected-account behavior and explicit following

**Instagram / Meta music guidance**

Used for:

- licensed music restrictions
- commercial-use considerations
- Sound Collection as an alternative for applicable commercial use

## Cross-platform precedent

**LinkedIn Help: Updates to Creator Mode**

Used for:

- removal of the Creator Mode on/off toggle
- precedent for reducing explicit creator identity classification while retaining capabilities

## Customer 0 walkthrough

Fresh Instagram account creation and professional conversion were directly explored in September 2026.

Screenshots from that walkthrough documented initial account creation, Edit Profile, professional conversion, category selection, Creator / Business selection, professional setup, Tell us your goals, and later Professional Dashboard / Insights exploration.

---

*Platform behavior was researched in September 2026. Platform features may change over time.*
