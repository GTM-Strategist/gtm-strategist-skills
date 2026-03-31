---
name: validating-customers
description: "Use this skill when the user wants to validate their customer assumptions, test their ICP, design experiments, or create customer personas from evidence. Phase 3 of 12: interactive guided workflow for assumption mapping, MVI (minimum viable idea) testing, alpha tests, community launches, archetype creation, and decision-making unit (DMU) analysis."
---

# Phase 3: Validating Customers

You are executing Phase 3 of the GTM Strategist methodology. This phase is about **finding your persona empirically** — not making things up. Everything at this stage is still an assumption until validated through real experiments with real people.

> **Philosophy:** You don't "define" your customer — you **discover** them. Brainstormed personas are fiction. Validated archetypes are strategy.

---

## Before You Start

1. **Read `my-gtm-context.md`** — load the user's product, market, ICP hypothesis, and traction context. If Section 3 (ICP) or Section 4 (Problem & Value) are empty, ask the user to fill those in first or complete Phase 1.

2. **Check for prior phase outputs:**
   - `outputs/01-*` — Phase 1 (GTM Foundations): OPE canvas, value prop, 90-day plan
   - `outputs/02-*` — Phase 2 (Collecting Intelligence): beachhead segments, interview insights, competitor analysis
   - If Phase 2 outputs exist, reference interview findings and beachhead segments heavily — they are the raw material for validation.
   - If Phase 2 outputs are missing, warn the user: *"Phase 3 works best when you have interview data from Phase 2. You can proceed, but your assumption map will rely more on hypothesis than evidence. Consider completing `collecting-intelligence` first."*

3. **Check `outputs/03-*`** for any existing Phase 3 work so you build on it rather than restart.

---

## Tasks

Work through these **one at a time**. Present each deliverable, get feedback, then proceed to the next.

---

### Task 1: Map Assumptions & Plan Experiments

**Duration:** 1-3 hours | **Output:** `outputs/03-assumption-map.md`

Everything you believe about your customer, problem, and solution is an assumption until tested. This task makes those assumptions explicit and prioritizes which to test first.

**Assumption Mapping Framework:**

Guide the user through these steps:

1. **List all assumptions** across four categories:
   - **Customer:** Who they are, where they are, what they care about
   - **Problem:** Severity, frequency, current workarounds, willingness to change
   - **Solution:** Whether your approach solves it, usability, feature priority
   - **Business:** Willingness to pay, price sensitivity, acquisition channels

2. **Score each assumption** on two axes:
   - **Certainty** (1-5): How much evidence do you have? (1 = pure guess, 5 = confirmed by data)
   - **Impact** (1-5): If this assumption is wrong, how badly does it hurt your GTM? (1 = minor, 5 = fatal)

3. **Identify "Leap of Faith" assumptions:** High impact + low certainty. These are the assumptions that could kill your GTM if wrong — and you have the least evidence for. These get tested first.

4. **Design experiments for top 3-5 leap-of-faith assumptions.** For each experiment, specify:
   - **Hypothesis:** "We believe [assumption] because [reason]."
   - **Test:** What you will do to validate (interview, landing page, ad test, prototype, etc.)
   - **Success metric:** What result would confirm or disconfirm the assumption?
   - **Duration:** How long the test runs.
   - **Cost/effort:** Resources required.

**Output structure:**
```
# Assumption Map

## All Assumptions
| # | Category | Assumption | Certainty (1-5) | Impact (1-5) | Priority |
|---|----------|-----------|-----------------|--------------|----------|

## Leap of Faith Assumptions
[Top assumptions with High Impact + Low Certainty]

## Experiment Plan
### Experiment 1: [Name]
- Hypothesis:
- Test method:
- Success metric:
- Duration:
- Cost/effort:
[Repeat for each experiment]

## Decision Log
[Left blank — user fills in as experiments conclude]
```

Reference Phase 2 interview insights to pre-populate certainty scores where evidence exists. Assumptions confirmed by 5+ interviews score higher certainty.

---

### Task 2: Create & Launch MVI (Minimum Viable Idea)

**Duration:** 1-3 days | **Output:** `outputs/03-mvi-plan.md`

An MVI is NOT an MVP. It is the simplest possible way to bring your value proposition to life and test whether real people respond to it. The goal is to test the **idea**, not the **product**.

**Guide the user to choose an MVI format:**

| MVI Type | Best For | Example |
|----------|----------|---------|
| **Landing page + signup** | Testing demand for a concept | "Sign up for early access" with value prop |
| **Explainer video / demo** | Complex products that need showing | 2-min Loom walking through the concept |
| **Concierge / manual service** | Service businesses, B2B | Deliver the outcome manually for 5 people |
| **Content test** | Audience validation | Blog post / social post explaining the problem + solution |
| **Fake door test** | Feature demand within existing product | Button/link that measures clicks before building |
| **Pre-sell / crowdfund** | Willingness to pay | "Buy now" at target price, measure conversion |
| **Wizard of Oz** | Tech products | Frontend works, human does backend manually |

**For the chosen MVI, define:**

1. **Core value proposition** being tested (one sentence)
2. **Format** and what the user needs to build
3. **Target audience** — who specifically will see this? (Pull from Phase 2 beachhead segments)
4. **Distribution plan** — how will you get it in front of 50-100 relevant people?
5. **Success metrics:**
   - Primary: Signup rate, response rate, or conversion %
   - Secondary: Quality of responses, questions asked, objections raised
6. **Timeline:** Day-by-day plan for creation and launch
7. **What you will learn** — which assumptions from Task 1 does this test?

Emphasize: The MVI must strategically attract the **right** potential customers, not just anyone. Volume without relevance is vanity.

---

### Task 3: Alpha Testing with 10+ Prospects

**Duration:** 1-2 weeks | **Output:** `outputs/03-alpha-test-results.md`

Alpha testing means getting your MVI (or early prototype) in front of real prospects and collecting structured feedback. These should be people from your Phase 2 interviews who expressed interest.

**Guide the user through:**

1. **Recruit alpha testers:**
   - Revisit Phase 2 interviewees — who showed the most enthusiasm?
   - Aim for 10+ testers minimum (expect ~50% follow-through from invites)
   - Send a personal invitation, not a mass email. Reference their earlier conversation.

2. **Prepare the alpha test:**
   - Record a demo or walkthrough if the product isn't self-serve yet
   - Create a structured feedback form (not just "what do you think?")
   - Key questions to include:
     - "What problem does this solve for you?" (tests understanding)
     - "How are you solving this today?" (tests alternative awareness)
     - "Would you use this in your current workflow? Where?" (tests fit)
     - "What's missing before you'd pay for this?" (tests gap to WTP)
     - "Who else on your team would need this?" (tests DMU — feeds Task 7)
     - Rating: "How disappointed would you be if this didn't exist?" (Sean Ellis test)

3. **Run the alpha:**
   - Share the MVI/prototype with each tester
   - Follow up within 48 hours for feedback
   - Update testers on changes you make based on their input (IKEA effect: they helped build it, they are more likely to become your first customers)

4. **Synthesize results:**
   - Sean Ellis score: % who say "very disappointed" (target: >40%)
   - Common patterns in feedback
   - Segments within testers: who loved it vs. who was lukewarm?
   - Feature requests / gaps mentioned 3+ times
   - Updated assumption map (which experiments from Task 1 now have data?)

**Output structure:**
```
# Alpha Test Results

## Test Setup
- MVI tested: [what you showed]
- Testers invited: [N]
- Testers who completed: [N]
- Test period: [dates]

## Sean Ellis Score
- Very disappointed: X%
- Somewhat disappointed: X%
- Not disappointed: X%

## Key Findings
[Patterns, surprises, segments]

## Feedback Themes
| Theme | Frequency | Representative Quote |
|-------|-----------|---------------------|

## Updated Assumptions
[Which assumptions from 03-assumption-map.md are now confirmed/disconfirmed?]

## Next Steps
[What to change, who to test next]
```

---

### Task 4: Community Launch (5-10 Communities)

**Duration:** 1-2 weeks | **Output:** `outputs/03-community-launch-plan.md`

Community launches test your idea with strangers — people who have no relationship with you and no reason to be polite. This is where real market signal lives.

**Guide the user through:**

1. **Identify 5-10 relevant communities:**
   - Where does your target persona already hang out?
   - Types: Reddit subreddits, Slack/Discord groups, Facebook groups, LinkedIn groups, indie hacker communities, industry forums, Skool communities, Hacker News (if technical)
   - Pull from Phase 2 research — "where they hang out online" from interview data

2. **Community warm-up (DO NOT SKIP):**
   - Join each community 1-2 weeks before posting about your product
   - Observe: What topics get engagement? What tone works? What gets removed?
   - Do value commenting: answer questions, share insights, be genuinely helpful
   - Build "social karma" — earn the right to share your thing
   - This is NOT optional. Cold-posting your product in communities is spam and gets removed.

3. **Craft the post for each community:**
   - Adapt tone and format to each community's norms
   - Lead with the PROBLEM, not your product
   - Frame it as: "I built this because [problem]. Would love feedback from people who deal with [pain]."
   - Include a clear, low-friction call to action (try it free, sign up for beta, watch the demo)
   - Never use marketing language in communities. Be a person, not a brand.

4. **Track results per community:**

| Community | Members | Post Date | Views | Clicks | Signups | Comments | Sentiment |
|-----------|---------|-----------|-------|--------|---------|----------|-----------|

5. **Analyze which communities responded best** — this tells you where your future customers live and how they talk about the problem.

---

### Task 5: Reverse-Engineer Customer Archetype

**Duration:** 1-3 hours | **Output:** `outputs/03-customer-archetype-analysis.md`

Now you have real data: alpha test feedback, community responses, interview insights, MVI results. Time to find the pattern.

**Guide the user through:**

1. **Consolidate all evidence sources:**
   - Phase 2 interview insights (`outputs/02-*`)
   - Assumption map results (Task 1)
   - MVI results (Task 2)
   - Alpha test results (Task 3)
   - Community launch results (Task 4)

2. **Segment the respondents.** Look for natural clusters:
   - Who had the strongest reaction? (Sean Ellis "very disappointed" group)
   - What do they have in common? (Role, company size, industry, pain level, current solution)
   - Who was lukewarm? What's different about them?
   - Are there surprising segments you didn't expect?

3. **Score each segment** on:
   - **Pain intensity:** How badly do they need this?
   - **Willingness to pay:** Did they ask about pricing? Offer to pre-order?
   - **Accessibility:** Can you reach more people like them?
   - **Fit:** Does your product/solution match what they need?

4. **Network validation test:**
   - Identify 50+ relevant people from the user's network (LinkedIn connections, industry contacts, former colleagues)
   - Share the early product/prototype with them for quick feedback
   - Goal: validate that the archetype holds beyond the small alpha group
   - Track: Does the same segment show the strongest response at scale?

5. **Make the persona decision:**
   - Based on all evidence, identify the 1-2 segments with the best combination of pain + WTP + accessibility + fit
   - Articulate WHY this segment (cite specific evidence)
   - Note: This is an evidence-based decision, not a brainstorming exercise. If the evidence is inconclusive, say so and recommend more testing.

---

### Task 6: Create Customer Archetype (ECP / ICP / Persona)

**Duration:** 1-3 hours | **Output:** `outputs/03-customer-archetype.md`

This is the culmination of Phase 3 — a customer archetype built on evidence, not guesswork. The confidence level here should be significantly higher than anything created without validation.

**Explain the terminology:**
- **ECP (Early Customer Profile):** Your first adopters — pain is acute, they'll tolerate imperfection. Most relevant for pre-launch / early stage.
- **ICP (Ideal Customer Profile):** The broader segment you'll scale into. Company-level for B2B.
- **Persona:** The specific human within the ICP who experiences the pain and makes (or influences) the buying decision.

**Create the archetype using this structure:**

```
# Customer Archetype: [Name]

## Confidence Level
- Evidence base: [N] interviews, [N] alpha testers, [N] community responses
- Sean Ellis score: [X]%
- Confidence: [LOW / MEDIUM / HIGH] — based on sample size and consistency

## Profile
- **Role / Title:** [For B2B]
- **Company type:** [Size, industry, stage]
- **Demographics:** [Age range, location, seniority — only what's validated]
- **Psychographics:** [Attitudes, values, beliefs that drive behavior]

## Jobs to Be Done
[Focus here — this is the most actionable part of the archetype]
- **Functional jobs:** What tasks are they trying to accomplish?
- **Emotional jobs:** How do they want to feel?
- **Social jobs:** How do they want to be perceived?

## Pain Points (Validated)
[Only include pains confirmed by evidence. Cite source.]
| Pain Point | Evidence | Severity (1-5) |
|-----------|----------|----------------|

## Current Solutions & Workarounds
[What they do today instead of using your product]

## Benefits They Seek
[Especially important for B2B — what outcome justifies the purchase?]

## Buying Triggers
[What event or moment makes them actively search for a solution?]

## Where They Hang Out
[Validated from community launch — which communities had strongest response?]

## Language & Phrases
[Exact words they use to describe their problem — from interviews and community posts]

## Anti-Persona Signals
[Who is NOT your customer? What signals disqualify a prospect?]
```

Emphasize: Every section should cite evidence. Mark anything unvalidated as `[HYPOTHESIS — needs validation]`.

---

### Task 7: Decision Making Unit (DMU)

**Duration:** 1-3 hours | **Output:** `outputs/03-dmu-map.md`

Primarily relevant for **complex B2B / enterprise** sales where buying decisions involve multiple people. If the user is B2C or simple self-serve B2B, this task can be abbreviated.

**Guide the user through:**

1. **Determine buying motion:**
   - **Top-down:** Decision starts with leadership (CEO/VP). Common in enterprise, strategic purchases.
   - **Bottom-up:** Decision starts with end user. Common in PLG, developer tools, SMB.
   - **Consensus:** Multiple stakeholders must agree. Common in mid-market.
   - Reference alpha test feedback: When testers said "I'd need to get buy-in from...", who did they name?

2. **Map the DMU roles:**

| Role | Who | Influence Level | What They Care About | How to Reach Them |
|------|-----|----------------|---------------------|-------------------|
| **Champion** | The internal advocate who wants your product | HIGH | Solving their pain, looking good internally | Direct — they found you |
| **Decision Maker** | Signs the check / approves the budget | HIGH | ROI, risk, strategic fit | Via champion, executive content |
| **Influencer** | Shapes the decision without owning it | MEDIUM | Technical fit, integration, ease of use | Product content, demos |
| **End User** | Will use the product daily | MEDIUM | Usability, workflow fit, time savings | Free trial, onboarding |
| **Blocker** | Can veto or stall the deal | HIGH (negative) | Security, compliance, budget, status quo | Objection handling, case studies |
| **Gatekeeper** | Controls access to decision maker | LOW-MEDIUM | Process, vendor requirements | Procurement docs, compliance |

3. **Fill in the DMU for the user's specific context:**
   - Use evidence from interviews and alpha tests
   - For each role: specific job title, what they care about, typical objections
   - Note which roles they have evidence for vs. which are assumed

4. **Map the buying process:**
   - What triggers the search?
   - Who does initial research?
   - Who evaluates options?
   - Who makes the final call?
   - What is the typical timeline?
   - Where does the process stall most often?

5. **Implications for GTM:**
   - Which role should your marketing target first?
   - What content does each role need?
   - How should sales engage the DMU?
   - What materials does the champion need to sell internally?

---

## Summary & Next Steps

After completing all 7 tasks, present a summary:

```
## Phase 3 Complete: Customer Validation

### What You Built
- Assumption map with [N] tested assumptions
- MVI tested with [N] people
- Alpha results from [N] testers (Sean Ellis: X%)
- Community response from [N] communities
- Evidence-based customer archetype: [Name]
- DMU map (if B2B): [buying motion type]

### Confidence Assessment
[Based on evidence volume and consistency, how confident are you in the archetype?
LOW = <20 data points, conflicting signals
MEDIUM = 20-50 data points, mostly consistent
HIGH = 50+ data points, clear pattern]

### Key Decisions Made
[What did the user decide about their target customer based on evidence?]

### What's Next
Phase 4 (`building-product`) will use your validated archetype to define:
- Jobs to be done (detailed)
- Product roadmap priorities
- MVP scope
- Success metrics

Your customer archetype from this phase becomes the foundation for everything that follows.
```

---

## Go Deeper

These resources extend the frameworks used in this phase:

- **The Mom Test** by Rob Fitzpatrick — The gold standard for customer interviews and avoiding false validation
- **Lean Startup** by Eric Ries — Deeper on MVPs and validated learning (this phase uses MVI, a lighter version)
- **Testing Business Ideas** by Strategyzer — 44 experiment cards for validating assumptions
- **Obviously Awesome** by April Dunford — Context on how customer segments connect to positioning (Phase 6)
- **Sean Ellis / PMF Survey** — The "how disappointed would you be?" framework used in alpha testing
- **Jobs to Be Done framework** (Christensen) — Foundation for the archetype's JTBD section
- **Crossing the Chasm** by Geoffrey Moore — Why your ECP (early adopters) and ICP (mainstream) may differ

---

*GTM Strategist methodology by Maja Voje. https://gtmstrategist.com*
