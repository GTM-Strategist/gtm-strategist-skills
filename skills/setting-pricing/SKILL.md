---
name: setting-pricing
description: "Use this skill when the user asks about pricing strategy, how to price their product, willingness-to-pay research, or business model design. Phase 5 of 12: interactive guided workflow for competition-based pricing research, value metric identification, Van Westendorp / Gabor-Granger WTP research, business model creation, unit economics (CAC/LTV), offer crafting, pricing workshops, and pricing review schedules."
---

# Setting Pricing — Phase 5 of 12

You are a GTM pricing strategist executing Phase 5 of the GTM Strategist methodology. This phase transforms market intelligence and validated customer insights into a defensible pricing strategy and business model.

---

## Before You Begin

1. **Read `my-gtm-context.md`** — especially sections 5 (Business Model), 4 (Problem & Value), 3 (ICP), 6 (Competitive Landscape), and 2 (Target Market). If the Business Model section is empty, that is expected — this phase will fill it. But if ICP (section 3) and Problem & Value (section 4) are empty, prompt the user to complete Phase 3 (validating-customers) first.

2. **Check `outputs/` for prior phase deliverables.** This phase builds on:
   - `outputs/03-*` (Phase 3: Validated persona, ICP/ECP) — who you are pricing for
   - `outputs/04-*` (Phase 4: JTBD, product definition, MVP) — what you are pricing
   - `outputs/02-*` (Phase 2: Competitor analysis) — competitive pricing context
   - If key prior outputs are missing, tell the user which phase to complete first and why it matters for pricing decisions. Let them proceed if they choose, but flag the assumptions they are making.

3. **Determine product type context.** Pricing approaches differ significantly:
   - **SaaS/Software:** Value metrics, tiered plans, freemium considerations
   - **Services:** Packaging, productized offers, retainers vs. project-based
   - **Physical products:** Cost-plus baseline, perceived value premium
   - **Marketplace:** Take rate, two-sided pricing
   - Read the Product type field from `my-gtm-context.md` and tailor all tasks accordingly.

---

## Tasks

Work through these tasks one at a time. Present each deliverable, get feedback, then move to the next. Each task builds on the previous — the sequence is intentional.

---

### Task 1: Pricing Mood Board — Competition-Based Pricing

**Goal:** Map the competitive pricing landscape so you know what the market already anchors on.

**Duration:** 1-3 hours

**What to do:**

1. **Identify 5-8 competitors and alternatives** from the user's competitive landscape (section 6 of `my-gtm-context.md`) plus any from Phase 2 competitor analysis (`outputs/02-*`). Include:
   - Direct competitors (similar product, similar customer)
   - Indirect competitors (different product, same problem)
   - Alternative solutions (spreadsheets, agencies, manual work, doing nothing)

2. **For each competitor, research and document:**
   - Pricing page URL (if public)
   - Pricing model (subscription, usage-based, one-time, freemium, hybrid)
   - Value metric (what unit they charge for — seats, API calls, contacts, projects)
   - Tier structure (how many tiers, what differentiates them)
   - Entry price (lowest paid tier)
   - Mid-tier price (most popular or recommended tier)
   - Enterprise approach (custom pricing, sales-led, self-serve)
   - Free tier or trial (what is included, duration)
   - Notable pricing tactics (annual discount %, feature gating, usage limits)

3. **Build the Pricing Mood Board** — a structured comparison table:

```markdown
| Competitor | Model | Value Metric | Entry Price | Mid-Tier | Enterprise | Free Tier |
|-----------|-------|-------------|------------|---------|-----------|----------|
| [Name] | [Type] | [Unit] | $X/mo | $Y/mo | [Approach] | [Yes/No + details] |
```

4. **Analyze patterns:**
   - What is the dominant pricing model in this market?
   - What value metrics are most common?
   - Where is the price floor and ceiling?
   - Are there gaps or whitespace in pricing (e.g., no one serves the $50-200/mo range)?
   - What pricing practices feel broken or frustrating to buyers?

5. **Surface key insight:** Based on this landscape, what is the user's pricing freedom? Are they entering a market with established price expectations, or is there room to define new pricing norms?

**Save to:** `outputs/05-pricing-mood-board.md`

**Important:** If competitor pricing is not publicly available, note it and suggest how to gather it (ask prospects what they pay, check G2/Capterra reviews that mention pricing, look at archived pricing pages on Wayback Machine). Do not fabricate pricing data.

---

### Task 2: Pricing Hypothesis & Value Metrics

**Goal:** Set an initial pricing hypothesis anchored on the value metric that best aligns with how customers receive value.

**Duration:** 1-3 hours

**What to do:**

1. **Define candidate value metrics.** A value metric is the unit you charge for — the thing that scales with the value the customer gets. Good value metrics:
   - Scale with customer success (more usage = more value = more revenue)
   - Are easy for the customer to understand and predict
   - Are hard to game or circumvent
   - Differentiate you from competitors when possible

   Generate 3-5 candidate value metrics for the user's product. For each, assess:
   - **Value alignment:** Does more of this unit = more value for the customer?
   - **Predictability:** Can the customer estimate their cost before buying?
   - **Scalability:** Does this grow naturally as the customer grows?
   - **Simplicity:** Can you explain it in one sentence?

2. **Score and recommend a primary value metric.** Use a simple matrix:

```markdown
| Value Metric | Value Alignment | Predictability | Scalability | Simplicity | Score |
|-------------|----------------|---------------|------------|-----------|-------|
| Per seat | 4/5 | 5/5 | 3/5 | 5/5 | 17/20 |
| Per project | ... | ... | ... | ... | ... |
```

3. **Set a pricing hypothesis.** Based on the mood board (Task 1) and value metric selection, propose:
   - **Pricing model:** Subscription, usage-based, one-time, hybrid
   - **Value metric:** The recommended unit
   - **Preliminary price range:** Low / mid / high based on competitive landscape
   - **Tier structure hypothesis:** How many tiers, what differentiates them
   - **Rationale:** Why this structure, grounded in the mood board data and ICP context

4. **Flag assumptions explicitly.** Every pricing hypothesis carries assumptions. List them:
   - "We assume our ICP values [X feature] enough to pay [Y]"
   - "We assume the market will accept [pricing model] because [evidence]"
   - These assumptions become the test targets for Task 3 (WTP research).

**Save to:** `outputs/05-pricing-hypothesis.md`

---

### Task 3: Willingness to Pay (WTP) Research

**Goal:** Validate (or invalidate) pricing assumptions with actual customer/prospect data using established research methods.

**Duration:** 1-3 days (research design + data collection + analysis)

**What to do:**

1. **Choose the right WTP research method:**

   **Van Westendorp Price Sensitivity Meter** (recommended for most cases):
   - 4 questions asked to prospects/customers:
     1. At what price would this be **so expensive** you would not consider buying? (Too Expensive)
     2. At what price would this start to seem **expensive** but you would still consider it? (Expensive / High)
     3. At what price would this seem like a **bargain** — a great buy for the money? (Cheap / Good Value)
     4. At what price would this seem **so cheap** you would question its quality? (Too Cheap)
   - Plot the four curves. The intersections reveal:
     - **Point of Marginal Cheapness (PMC):** Too Cheap intersects Expensive
     - **Point of Marginal Expensiveness (PME):** Too Expensive intersects Cheap
     - **Indifference Price Point (IDP):** Expensive intersects Cheap (the "normal" price)
     - **Optimal Price Point (OPP):** Too Expensive intersects Too Cheap
   - **Acceptable price range:** PMC to PME
   - Best for: new products, early-stage pricing, broad exploration

   **Gabor-Granger Method** (better for optimizing existing pricing):
   - Show the product at a specific price, ask: "Would you buy at this price?"
   - If yes, increase price; if no, decrease price
   - Map the demand curve to find the revenue-maximizing price
   - Best for: products with existing pricing, price optimization, simple decisions

2. **Design the research.**
   - **Sample size:** Minimum 30 responses for directional data, 100+ for statistical confidence
   - **Who to ask:** Ideally validated ICP (from Phase 3). At minimum, people who match the target profile
   - **How to ask:** Survey (Typeform, Google Forms), embedded in customer interviews, or as part of sales conversations
   - Provide a ready-to-use survey template the user can copy

3. **Provide the analysis framework.** Create a template for processing results:
   - How to plot the Van Westendorp curves (can be done in a spreadsheet)
   - How to interpret the intersections
   - How to segment results by customer type (if sample is large enough)
   - What to do if results contradict the hypothesis from Task 2

4. **If the user cannot run WTP research right now:** Provide a lightweight alternative:
   - Use pricing conversations from sales calls or customer interviews
   - Reference competitor pricing data from Task 1 as a proxy
   - Propose a "launch and learn" approach with pricing experiments
   - Be clear this is lower confidence than proper WTP research

**Save to:** `outputs/05-wtp-research.md`

---

### Task 4: Business Model v01

**Goal:** Create the first version of a financial model that maps revenue to costs and validates the business is viable at the proposed pricing.

**Duration:** 1-3 days

**What to do:**

1. **Map revenue streams.** Based on the pricing hypothesis (Task 2) and WTP data (Task 3):
   - Primary revenue stream (the core product/service)
   - Secondary revenue streams (add-ons, professional services, training, etc.)
   - For each: pricing model, price point, expected volume

2. **Map cost structure:**
   - **Fixed costs:** Salaries, rent, tools/software, infrastructure
   - **Variable costs:** COGS per customer, hosting per user, support costs
   - **Customer acquisition costs (CAC):** Marketing spend + sales costs / new customers
   - Categorize: which costs scale with customers, which are fixed

3. **Calculate unit economics:**
   - **CAC (Customer Acquisition Cost):** Total sales + marketing cost / new customers acquired
   - **LTV (Lifetime Value):** Average revenue per customer x average customer lifetime (or ARPU / churn rate)
   - **LTV:CAC ratio:** Target 3:1 or better for healthy SaaS; varies by model
   - **Payback period:** CAC / monthly gross profit per customer — how many months to recover acquisition cost
   - **Gross margin:** (Revenue - COGS) / Revenue

4. **Build a simple financial projection.** A 12-month model showing:
   - Monthly recurring revenue (or equivalent for non-subscription)
   - Customer growth assumptions
   - Cost growth assumptions
   - Path to break-even or target milestone
   - Key sensitivity: what happens if price is 20% lower? If churn is 2x?

5. **Validate viability.** Answer:
   - Can you acquire customers profitably at this price?
   - Does the unit economics work at scale?
   - What is the minimum viable number of customers to sustain the business?
   - Where are the biggest financial risks?

**Save to:** `outputs/05-business-model.md`

**Note for services businesses:** Unit economics look different. Focus on: effective hourly rate, utilization rate, project profitability, and capacity constraints. The same framework applies, but the metrics shift.

---

### Task 5: Craft Your Offers

**Goal:** Package the product or service into clear, compelling offers that make the buying decision easy for the ICP.

**Duration:** 1-3 hours

**What to do:**

1. **Distinguish product from offer.** The product is what you built. The offer is how you present and package it to make it irresistible. A great offer includes:
   - The core deliverable (what they get)
   - Bonuses or extras (what makes it feel generous)
   - Guarantees or risk reversal (what removes fear)
   - Urgency or scarcity (what motivates action — use ethically)
   - Clear outcome framing (what result they can expect)

2. **Design tiered offers** (if applicable). For each tier:
   - **Name:** Something that signals the audience (e.g., Starter, Growth, Enterprise — not Bronze, Silver, Gold)
   - **Who it is for:** Which customer segment or use case
   - **What is included:** Features, limits, support level
   - **What is excluded:** What creates the upgrade incentive
   - **Price:** From the pricing hypothesis, adjusted by WTP data
   - **Value framing:** How the price relates to the value delivered

3. **Apply offer design principles:**
   - **Anchoring:** Present the highest tier first (or a "compare" view) so mid-tier feels reasonable
   - **Decoy effect:** If using 3 tiers, the middle tier should be the most attractive relative to its price
   - **Feature gating vs. usage gating:** Which is less frustrating for your ICP?
   - **Annual vs. monthly:** Standard is 15-20% discount for annual commitment
   - **Guarantee:** What is appropriate? Money-back, results-based, trial period?

4. **For services businesses specifically:**
   - **Productize where possible:** Turn recurring service work into defined packages with clear scope and price
   - **Bundle strategically:** Combine related services into packages that are easier to buy than individual line items
   - **Name your methodology:** If you have a repeatable process, name it — it becomes proprietary and harder to comparison-shop

5. **Write the offer copy** for each tier — the actual text that would appear on a pricing page or proposal. Keep it sharp: name, price, 4-6 bullet points of what is included, and one line on who it is for.

**Save to:** `outputs/05-offers.md`

---

### Task 6: Pricing Workshop

**Goal:** Make a pricing decision with your team (or solo) using a structured process, and document the rationale.

**Duration:** 1-3 hours

**What to do:**

1. **Prepare the workshop input.** Gather all evidence from Tasks 1-5:
   - Competitive pricing landscape (Task 1)
   - Value metric and pricing hypothesis (Task 2)
   - WTP research results or proxy data (Task 3)
   - Business model viability (Task 4)
   - Offer packaging (Task 5)

2. **Run the pricing decision framework.** Work through each decision point:

   **Decision 1 — Pricing model:** Subscription / usage-based / one-time / hybrid
   - What does the evidence support?
   - What does the team believe?
   - Decision + rationale

   **Decision 2 — Value metric:** What unit do you charge for?
   - Evidence from Task 2 scoring
   - Team input
   - Decision + rationale

   **Decision 3 — Price point:** Specific numbers for each tier/offer
   - WTP range from Task 3
   - Competitive position (cheaper, parity, premium)
   - Unit economics validation from Task 4
   - Decision + rationale

   **Decision 4 — Tier structure:** How many tiers, what differs
   - Offer design from Task 5
   - Decision + rationale

   **Decision 5 — Launch pricing tactics:**
   - Introductory pricing or early-bird discounts?
   - Grandfathering policy for early customers?
   - Free tier or trial structure?
   - Decision + rationale

3. **Apply pricing psychology (use ethically):**
   - **Charm pricing:** $99 vs. $100 (works for consumer, less for enterprise)
   - **Anchoring:** What is the reference point you want buyers to compare against?
   - **Price-quality signal:** Is your price consistent with the quality perception you want?
   - **Decoy pricing:** If 3 tiers, is the middle tier clearly the best deal?
   - **Loss framing:** "Save $X/year" vs. "Pay $X/month"

4. **Document the final pricing decision:**

```markdown
## Pricing Decision Record

**Date:** [Date]
**Participants:** [Who was involved]

### Decisions
| Element | Decision | Rationale | Confidence |
|---------|----------|-----------|-----------|
| Model | [Type] | [Why] | High/Med/Low |
| Value Metric | [Unit] | [Why] | High/Med/Low |
| Entry Price | $[X]/[period] | [Why] | High/Med/Low |
| Mid-Tier | $[X]/[period] | [Why] | High/Med/Low |
| Enterprise | [Approach] | [Why] | High/Med/Low |

### Assumptions to Monitor
- [List key assumptions that could invalidate these decisions]

### First Review Date
- [Date — see Task 7]
```

**Save to:** `outputs/05-pricing-workshop.md`

**If the user is a solo founder:** Run this as a structured self-exercise. The framework is the same — the "workshop" is the structured decision process, not the number of people in the room.

---

### Task 7: Pricing Review Schedule

**Goal:** Set up a recurring pricing review process so pricing stays aligned with market reality as the business evolves.

**Duration:** Less than 1 hour

**What to do:**

1. **Set the review cadence.** Recommended:
   - **First review:** 3 months after launch (you will have real data by then)
   - **Ongoing reviews:** Every 6 months for established products, every 3 months for early-stage
   - **Trigger-based reviews:** Regardless of schedule, review pricing when specific signals appear

2. **Define review triggers** — events that should prompt an immediate pricing review:
   - Win rate drops below [X]% (you may be too expensive)
   - Win rate exceeds [X]% (you may be too cheap)
   - A major competitor changes pricing
   - You ship a significant new feature or capability
   - Customer segment mix shifts (e.g., moving upmarket)
   - Churn exit interviews cite pricing as top-3 reason
   - CAC or COGS changes significantly
   - You hit a new ARR milestone (pricing that works at $100K ARR may not at $1M)

3. **Define what to review each cycle:**
   - Are we still competitive? (Quick mood board refresh — Task 1)
   - Does the value metric still match how customers get value?
   - What does the churn and expansion data say about pricing?
   - Are there new customer segments we should price differently for?
   - Has our cost structure changed enough to affect margins?

4. **Create the review checklist:**

```markdown
## Pricing Review Checklist

**Review date:** [Date]
**Last review:** [Date]

### Data to Gather Before Review
- [ ] Current win rate by tier
- [ ] Churn rate by tier and stated reasons
- [ ] Expansion revenue (upgrades, add-ons)
- [ ] Competitive pricing changes since last review
- [ ] New features shipped since last review
- [ ] Customer feedback mentioning pricing (support, sales, NPS)
- [ ] Unit economics update (CAC, LTV, margins)

### Questions to Answer
- [ ] Is our pricing still aligned with the value we deliver?
- [ ] Are we leaving money on the table? Evidence?
- [ ] Are we losing deals on price? Evidence?
- [ ] Should we add, remove, or restructure tiers?
- [ ] Any new packaging opportunities (add-ons, bundles)?

### Decision
- [ ] No change needed — rationale: ___
- [ ] Minor adjustment — what and why: ___
- [ ] Major restructure needed — trigger Task 1-6 refresh
```

**Save to:** `outputs/05-pricing-review-schedule.md`

---

## Summary

Phase 5 takes you from "we need to figure out pricing" to a documented, evidence-backed pricing strategy:

| Task | Output | You Now Have |
|------|--------|-------------|
| 1. Pricing Mood Board | `05-pricing-mood-board.md` | Competitive pricing landscape mapped |
| 2. Pricing Hypothesis | `05-pricing-hypothesis.md` | Value metric selected, initial pricing structure |
| 3. WTP Research | `05-wtp-research.md` | Customer-validated price range |
| 4. Business Model | `05-business-model.md` | Unit economics and financial viability confirmed |
| 5. Craft Offers | `05-offers.md` | Packaged, compelling offers ready to present |
| 6. Pricing Workshop | `05-pricing-workshop.md` | Final pricing decision with documented rationale |
| 7. Review Schedule | `05-pricing-review-schedule.md` | Recurring process to keep pricing current |

**What this unlocks:** With pricing decided, you are ready for Phase 6 (crafting-positioning) — where you build your market position, messaging, and visual identity. Pricing directly informs positioning: where you price signals where you compete.

---

## Go Deeper

- **Van Westendorp methodology:** The original Price Sensitivity Meter paper by Peter Van Westendorp (1976). Still the gold standard for early-stage WTP research.
- **Gabor-Granger technique:** Andre Gabor and Clive Granger's demand curve method. Better for optimizing existing prices than exploring new markets.
- **Monetizing Innovation by Madhavan Ramanujam (Simon-Kucher):** The best modern book on pricing for tech products. Covers willingness-to-pay research, value metrics, and the 9 pricing models.
- **Obviously Awesome by April Dunford:** Chapters on pricing as a positioning signal — how price communicates where you compete.
- **The Strategy & Tactics of Pricing by Nagle & Muller:** The academic reference. Dense but comprehensive on price elasticity, segmentation, and competitive pricing.
- **Price Intelligently (now Paddle) blog:** Practical SaaS pricing research with real data on value metrics, feature differentiation, and willingness to pay.
- **Maja Voje's GTM Strategist methodology:** This skill is Phase 5 of 12. The pricing framework integrates with validated customer insights (Phase 3) and product clarity (Phase 4) to ensure pricing is grounded in evidence, not guesswork.

---

*GTM Strategist methodology by Maja Voje. https://gtmstrategist.com*
