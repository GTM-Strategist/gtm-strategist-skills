---
name: collecting-intelligence
description: "Use this skill when the user wants to research competitors, plan customer interviews, conduct market research, or understand their competitive landscape. Phase 2 of 12: interactive guided workflow for beachhead segment identification, Market-Problem Map, customer discovery interviews, surveys, competitor analysis, competition mood boards, competitor ad monitoring, and competitive experience teardowns."
---

# Phase 2: Collecting Intelligence — Customer Discovery & Competitive Research

You are executing Phase 2 of the GTM Strategist methodology. This phase transforms the user's assumptions from Phase 1 into evidence-backed market intelligence through structured customer discovery and competitive research.

## Before You Start

1. **Read `my-gtm-context.md`** at the project root. If critical fields (Product/Service, Target Market, Problem & Value) are empty, ask the user to fill them in before proceeding.

2. **Check `outputs/` for Phase 1 deliverables.** This phase builds directly on:
   - `outputs/01-ope-canvas.md` (Opportunity, Product, Execution canvas)
   - `outputs/01-swot-analysis.md`
   - `outputs/01-value-proposition.md`
   - `outputs/01-90-day-plan.md`

   If Phase 1 outputs exist, reference them throughout. If they don't exist, note that the user is working from assumptions — which is fine, but flag it. Phase 2 is specifically designed to test assumptions.

3. **Work one task at a time.** Present the deliverable, get feedback, then move to the next task. Don't dump all nine tasks at once.

---

## Task 1: Identify Beachhead Segment Candidates

**Duration:** 1-3 hours | **Output:** `outputs/02-beachhead-candidates.md`

"SaaS founders from the US" is NOT a segment. As a new player entering a market, you need critical mass of traction with relatable references. You cannot effectively market to 17,000 SaaS founders — nobody will feel like your product was built for *them*. A beachhead segment is narrow enough that customers within it reference each other, share context, and create word-of-mouth density.

**What to do:**

1. Read `my-gtm-context.md` sections 2 (Target Market) and 3 (ICP). Pull any existing market assumptions.

2. If Phase 1 outputs exist, extract the initial market/customer assumptions from the OPE canvas and SWOT.

3. Guide the user to brainstorm 5-8 candidate beachhead segments. For each segment, capture:
   - **Segment label** — specific enough that the user could name 10 people in it
   - **Size estimate** — rough order of magnitude (hundreds, low thousands)
   - **Pain intensity** — how urgent is the problem for this group (1-5 scale)
   - **Reachability** — can you actually get in front of them? Through what channels?
   - **Reference density** — do people in this segment talk to each other, follow each other, attend the same events?
   - **Willingness to pay** — is this a budget line item or a nice-to-have?

4. Rank the candidates. The best beachhead has HIGH pain, HIGH reachability, and HIGH reference density. Size should be small enough to dominate but large enough to sustain early revenue.

5. Select 1-3 segments to investigate further in Tasks 3-5.

**The deliverable should include:** A ranked table of candidates with scoring, the rationale for top picks, and a list of assumptions to validate per segment.

---

## Task 2: Market-Problem Map

**Duration:** 1-3 hours | **Output:** `outputs/02-market-problem-map.md`

Most companies start with a narrower niche than they think. The Market-Problem Map is a framework for "slicing and dicing" the market to find your best bet for an early customer segment and initial positioning. You start with assumptions, then update from discovery.

**What to do:**

1. Create a matrix with market segments on one axis and problems/use cases on the other.

2. For each cell, assess:
   - **Problem severity** — Is this a hair-on-fire problem or a mild inconvenience?
   - **Current alternatives** — What do they use today? How painful is the status quo?
   - **Fit with product** — How well does your product/solution address this specific problem for this specific segment?
   - **Market access** — Can you reach this segment efficiently?

3. Highlight the 2-3 strongest segment-problem intersections. These are your beachhead hypotheses.

4. Compare with Task 1 output. The Market-Problem Map should either confirm the beachhead ranking or reveal a better entry point.

**The deliverable should include:** The full matrix (Markdown table), highlighted top intersections, and a note on which assumptions are strongest vs. weakest.

---

## Task 3: Choose Validation Methods

**Duration:** 1-3 hours | **Output:** `outputs/02-validation-methods.md`

The core principle: **CONFIDENCE = EVIDENCE.** You need to find evidence for your initial assumptions, and different methods provide different levels of confidence.

**Methods ranked by confidence level (highest to lowest):**

| Method | Confidence | Best When | Sample Size |
|--------|-----------|-----------|-------------|
| Customer interviews (1:1) | Highest | B2B, complex products, early stage | 5-20 per segment |
| Sales/demo conversations | High | You have a product to show | 10-30 |
| Social experiments (landing pages, fake doors) | High | Testing demand before building | 100-500 visitors |
| Surveys | Medium | B2C, PLG, large audience accessible | 100-500 responses |
| Secondary research (reports, data) | Low-Medium | Market sizing, trend validation | N/A |
| Competitor analysis | Low-Medium | Understanding alternatives | N/A |

**What to do:**

1. Assess the user's current state:
   - **Product stage** (from `my-gtm-context.md`): Idea? Pre-launch? Launched?
   - **Confidence level**: What do they already know vs. what are they guessing?
   - **Resources**: Time, budget, team access to prospects.

2. Recommend a validation plan: which methods, in what order, with what sample sizes.

3. For interviews specifically: help estimate how many segments to cover (typically 1-3) and how many interviews per segment (5-20, stop when insights repeat).

4. Set expectations: interviews take 1-3 days of calendar time, surveys need 3-7 days for collection.

**The deliverable should include:** A concrete validation plan with methods, timelines, target sample sizes, and what each method will validate.

---

## Task 4: Interview 20+ Prospects

**Duration:** 1-3 days | **Output:** `outputs/02-interview-findings.md`

Interviews are the highest-confidence validation method. This task provides the interview structure, question frameworks, and synthesis templates.

**What to do:**

1. **Recruitment strategy.** Help the user plan how to get interviews:
   - Warm intros through existing network (best conversion)
   - Direct DMs on LinkedIn or community platforms (explain the "research angle" — people are more willing to help with research than a sales call)
   - Offer value: share findings, early access, or a small gift card
   - Target: 5-20 interviews per segment. Stop when you start hearing the same things.

2. **Interview guide.** Generate a structured question list tailored to the user's product and beachhead segments. Categories:
   - **Context questions** — Role, responsibilities, current workflow
   - **Problem questions** — How they handle the problem today, what frustrates them, how often it occurs
   - **Impact questions** — What happens when the problem isn't solved? Cost (time, money, reputation)?
   - **Solution questions** — What have they tried? What would the ideal solution look like?
   - **Willingness questions** — Would they pay for this? How much? What would make it a no-brainer?

3. **Recording and synthesis.** Advise: always record (with permission). After each interview, capture:
   - Top 3 quotes (verbatim)
   - Surprises (anything unexpected)
   - Pain level (1-5)
   - Would they pay? (Yes / Maybe / No)

4. **Cross-interview synthesis.** After multiple interviews, help the user identify:
   - Recurring pain points (frequency across interviews)
   - Language patterns (exact words prospects use — gold for messaging later)
   - Segment differences (do different segments describe the problem differently?)
   - Unexpected insights (things you didn't ask about but came up)

**The deliverable should include:** Interview guide (ready to use), synthesis template, and after interviews are done, a findings summary with patterns, quotes, and implications.

---

## Task 5: Customer Discovery Survey

**Duration:** 1-3 days | **Output:** `outputs/02-survey-results.md`

Best for B2C, PLG, or mainstream products where you need quantitative validation across a larger audience. Surveys complement interviews — they provide breadth where interviews provide depth.

**What to do:**

1. **Determine if a survey is right.** Surveys work when:
   - You can access hundreds of relevant respondents
   - The questions are simple enough for self-service answers
   - You need quantitative data (percentages, rankings)
   - NOT a substitute for interviews in B2B with complex buying processes

2. **Survey design.** Help the user build a survey (tools: Typeform, Google Forms, SurveyMonkey):
   - Keep it under 10 questions (completion rate drops sharply after that)
   - Start with screening questions (confirm they match the target segment)
   - Mix closed questions (multiple choice, scales) with 1-2 open-ended questions
   - Include a willingness-to-pay question if appropriate
   - End with "Can we follow up?" (converts survey respondents to interview candidates)

3. **Distribution plan.** Help identify where to promote:
   - Relevant communities (Reddit, Slack, Discord, Facebook groups)
   - Social media (LinkedIn posts, Twitter threads)
   - Email lists (if the user has one)
   - Paid promotion (if budget allows)
   - Target: 100-500 responses for statistical relevance

4. **Analysis framework.** After collection, help synthesize:
   - Segment-level breakdowns
   - Problem validation scores
   - Willingness-to-pay distribution
   - Open-ended response themes

**The deliverable should include:** Survey draft (ready to copy into a tool), distribution plan, and after collection, an analysis summary.

---

## Task 6: Competitor Analysis

**Duration:** 1-3 hours | **Output:** `outputs/02-competitor-analysis.md`

Critical reframe: competitor analysis is NOT about who shows up on Google for your keywords. It is about the **competitive alternatives that appear in your target customer's actual purchasing decision.** That includes direct competitors, adjacent tools, manual processes (spreadsheets, agencies), and doing nothing.

**What to do:**

1. **Identify real competitive alternatives.** Ask the user: "When your target customer has this problem, what do they actually do about it today?" Categories:
   - **Direct competitors** — Same problem, similar solution
   - **Indirect competitors** — Same problem, different approach
   - **Status quo** — Spreadsheets, manual processes, agencies, interns
   - **Do nothing** — The problem isn't painful enough to solve (this is your biggest competitor)

2. **Analyze each competitor** on:
   - **Positioning** — Who do they say they're for? What problem do they claim to solve?
   - **Pricing** — Model, price points, free tier
   - **Strengths** — What are they genuinely good at?
   - **Weaknesses** — Where do customers complain? (Check G2, Capterra, Reddit, app store reviews)
   - **ICP overlap** — How much do they compete for YOUR specific beachhead?

3. **Map the competitive landscape.** Create a 2x2 positioning map using the two dimensions most relevant to the user's market (e.g., ease-of-use vs. feature depth, price vs. specialization).

4. **Identify gaps.** Where is there white space? What does no competitor do well for your specific beachhead segment?

5. **Cross-reference with interview findings** (Task 4) if available. Do prospects mention these competitors? Which ones? What do they say?

**The deliverable should include:** Competitor table, positioning map, gap analysis, and strategic implications for the user's positioning.

---

## Task 7: Competition Mood Boards

**Duration:** 1-3 hours | **Output:** `outputs/02-competition-mood-boards.md`

Ongoing competitor monitoring that captures how competitors present themselves across channels. This creates a reference library for later positioning and content work.

**What to do:**

1. **Web presence audit.** For each key competitor (top 3-5 from Task 6):
   - **Landing page** — Headline, subheadline, primary CTA, social proof approach, visual style
   - **Pricing page** — Tiers, feature gating strategy, free trial/freemium approach
   - **About page** — Positioning narrative, team presentation, mission/values

2. **Social media audit.**
   - Content themes and posting frequency
   - Engagement levels (which topics get traction?)
   - Tone and voice characteristics
   - Community engagement approach

3. **Email marketing.** Sign up for competitor newsletters and free trials. Document:
   - Onboarding email sequence (timing, content, CTAs)
   - Newsletter topics and cadence
   - Promotional approaches

4. **SEO and content.** Quick assessment:
   - Blog topics and content strategy
   - Target keywords (check SimilarWeb or Ahrefs if accessible)
   - Content quality and depth

5. **Monitoring setup.** Help the user set up ongoing tracking:
   - Google Alerts for competitor brand names
   - Social Mention or similar tools
   - SimilarWeb for traffic trends (free tier available)
   - Bookmark competitor pricing pages (these change)

**The deliverable should include:** Structured notes per competitor across all channels, key observations, and a monitoring checklist for ongoing tracking.

---

## Task 8: Monitor Competitor Ads & Emails

**Duration:** 1-3 hours | **Output:** `outputs/02-competitor-ads-emails.md`

Competitor advertising reveals what messaging they've tested and what converts. Long-running ads are a strong signal — if an ad has been active for months, it is likely performing well.

**What to do:**

1. **Ad library research.** Check each major platform:
   - **Meta Ads Library** (facebook.com/ads/library) — Search competitor names, filter by active ads
   - **Google Ads Transparency Center** — Search competitor domains
   - **LinkedIn Ad Library** — If competitors run LinkedIn ads
   - **TikTok Creative Center** — For B2C competitors

2. **For each competitor's ads, capture:**
   - Ad format (image, video, carousel)
   - Primary message/hook — What problem do they lead with?
   - CTA — What action do they drive?
   - Target audience signals — Who is this ad for?
   - Duration — How long has it been running? (Longer = likely converting)
   - Landing page — Where does the ad send traffic?

3. **Email sequence analysis.** From Task 7's newsletter signups:
   - Map the full onboarding sequence (Day 1, Day 3, Day 7, etc.)
   - Identify the sales conversion trigger (when do they pitch?)
   - Note subject lines and open-rate hooks

4. **Pattern synthesis.** Across all competitors:
   - What messaging angles are most common? (This is table stakes messaging)
   - What angles are MISSING? (This is opportunity)
   - What offers/CTAs dominate? (Free trial, demo, content?)

**The deliverable should include:** Ad screenshots/descriptions organized by competitor, email sequence maps, and a synthesis of messaging patterns and gaps.

---

## Task 9: Buy From Competitors

**Duration:** 1-3 days | **Output:** `outputs/02-competitor-experience.md`

Hands-on competitive intelligence. Reverse-engineer the competitor's full customer experience — from first touch through value delivery. Nothing replaces actually being a customer.

**What to do:**

1. **Select 2-3 competitors** to experience directly (prioritize the ones your beachhead segment actually considers, from Task 6).

2. **Go through their full funnel:**
   - **Discovery** — How did you find them? What was the first impression?
   - **Evaluation** — Sign up for free trial or demo. How smooth is onboarding? Time to first value?
   - **Sales process (if B2B)** — Book a demo. How does the sales team pitch? What questions do they ask? What objections do they anticipate?
   - **Product experience** — Use the product. What's great? What's frustrating? Where do you get stuck?
   - **Support** — Contact support with a question. Response time? Quality?
   - **Retention/upsell** — What happens after initial signup? Follow-up emails? Upsell prompts?

3. **Capture the experience** in detail:
   - Screenshot key moments
   - Note exact language used in sales conversations
   - Time each step (how long from signup to value?)
   - Rate the overall experience (1-10) with specific justification

4. **Bonus: Learn from their people.** If possible:
   - Connect with former employees on LinkedIn (they're often willing to share general insights)
   - Read Glassdoor reviews for cultural and strategic signals
   - Check if founders/team share insights on podcasts or blogs

5. **Strategic implications.** For each competitor experience:
   - What would you steal? (Specific tactics worth adopting)
   - What would you fix? (Gaps your product could exploit)
   - What surprised you? (Unexpected strengths or weaknesses)

**The deliverable should include:** Detailed experience journal per competitor, a comparison matrix, and a "steal/fix/surprise" synthesis.

---

## Summary: What You've Built in Phase 2

After completing the tasks above, the user should have:

| Output | What It Proves |
|--------|---------------|
| `02-beachhead-candidates.md` | Narrowed from broad market to specific, attackable segments |
| `02-market-problem-map.md` | Mapped which segments care most about which problems |
| `02-validation-methods.md` | A concrete plan to test assumptions with real evidence |
| `02-interview-findings.md` | First-hand qualitative evidence from target customers |
| `02-survey-results.md` | Quantitative validation across a broader audience |
| `02-competitor-analysis.md` | Clear picture of competitive alternatives and white space |
| `02-competition-mood-boards.md` | Reference library of competitor positioning and presence |
| `02-competitor-ads-emails.md` | Competitive messaging patterns and gaps |
| `02-competitor-experience.md` | Hands-on knowledge of competitor strengths and weaknesses |

**This phase transforms assumptions into evidence.** The user entered Phase 2 with hypotheses about their market, customers, and competition. They leave with validated (or invalidated) insights ready for Phase 3: Validating Customers.

### Next Steps

Proceed to **Phase 3: `validating-customers`** to synthesize intelligence into validated personas (ICP, Early Customer Profile), map assumptions systematically, and run focused experiments.

---

## Go Deeper

- **"Go-To-Market Strategist" by Maja Voje** — Chapters on Customer Discovery and Competitive Intelligence cover the full methodology behind these tasks.
- **"The Mom Test" by Rob Fitzpatrick** — The gold standard for conducting customer interviews that produce truthful, useful data. Essential reading before Task 4.
- **"Obviously Awesome" by April Dunford** — Competitive positioning framework that builds directly on the competitor analysis from Tasks 6-9.
- **"Competing Against Luck" by Clayton Christensen** — Jobs-to-be-done theory that deepens the Market-Problem Map and interview frameworks.
- **GTM Strategist Notion templates** — Maja's original worksheets for beachhead selection, interview guides, and competitor tracking.

---

*GTM Strategist methodology by Maja Voje. https://gtmstrategist.com*
