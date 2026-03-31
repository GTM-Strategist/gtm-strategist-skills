---
name: building-gtm-system
description: "Use this skill when the user has already launched and wants to build repeatable growth systems, set up a CRM, create SOPs, or run growth experiments. Phase 10 of 12: interactive guided workflow for launch retrospective, CRM setup, GTM motions, roadmap creation, growth sprints, CRO experimentation, growth loops, SOPs, and new market exploration."
---

# Phase 10: Building a Post-Launch GTM System

You are executing Phase 10 of the GTM Strategist methodology. The launch is behind you. This phase shifts from one-time execution to building repeatable, scalable systems. The goal: turn what worked into a machine that runs without heroics.

## Before You Start

1. **Read `my-gtm-context.md`** at the project root. If critical fields (Product/Service, Target Market, Business Model, Traction & Evidence) are empty, ask the user to fill them in before proceeding.

2. **Check `outputs/` for prior phase deliverables.** This phase builds directly on:
   - `outputs/09-launch-plan.md` (launch execution plan and results)
   - `outputs/08-channel-strategy.md` (communication engine and funnel)
   - `outputs/06-positioning-statement.md` (positioning and messaging)
   - `outputs/05-pricing-model.md` (pricing strategy and business model)
   - `outputs/03-icp-profile.md` (validated ICP and personas)
   - `outputs/01-90-day-plan.md` (original goals for comparison)

   If Phase 9 outputs exist, reference them heavily — this phase is a direct continuation of launch. If earlier outputs are missing, ask which phases the user completed and work from what exists. Phase 10 is most valuable when you have real launch data to work with.

3. **Work one task at a time.** Present the deliverable, get feedback, then move to the next task. Don't dump all nine tasks at once.

---

## Task 1: Launch Retrospective

**Duration:** < 1 day | **Output:** `outputs/10-launch-retrospective.md`

The single most important thing you can do after launch is a structured retrospective while the experience is fresh. Most teams skip this, then repeat the same mistakes on the next launch. Don't be most teams.

**What to do:**

1. **Gather the data.** Help the user compile key launch metrics:
   - **Awareness metrics** — Reach, impressions, PR mentions, social engagement
   - **Acquisition metrics** — Website traffic, signups, demo requests, trial starts
   - **Activation metrics** — Users who completed onboarding, reached first value moment
   - **Revenue metrics** — Deals closed, revenue generated, pipeline created
   - **Timeline adherence** — What shipped on time vs. what slipped?

2. **Run the retrospective framework.** Structure the analysis around four questions:
   - **What worked?** — Specific tactics, channels, and messages that drove results. Quantify wherever possible.
   - **What didn't work?** — Things that underperformed expectations. Be honest — this is where the learning lives.
   - **What surprised you?** — Unexpected wins, unexpected failures, signals you didn't anticipate.
   - **What would you do differently?** — If you launched again tomorrow, what changes would you make?

3. **Channel-by-channel breakdown.** For each channel used during launch:
   - Traffic/leads generated
   - Conversion rate
   - Cost (time and money)
   - Quality of leads (did they convert downstream?)

4. **Compare against original goals.** Pull the 90-day goals from `my-gtm-context.md` or `outputs/01-90-day-plan.md`. Where did you hit, miss, or exceed targets?

5. **Extract the top 5 learnings.** Not vague observations — specific, actionable insights that will inform the next quarter.

**The deliverable should include:** A data summary, the four-question retrospective, channel breakdown, goal comparison, and prioritized learnings.

---

## Task 2: CRM Setup

**Duration:** 1-3 hours | **Output:** `outputs/10-crm-setup.md`

You don't need Salesforce. You need a system that tracks your pipeline so opportunities don't fall through the cracks. The best CRM is the one your team actually uses.

**What to do:**

1. **Assess current state.** Ask the user:
   - What are you using now? (Spreadsheet, HubSpot free, Pipedrive, nothing?)
   - How many active deals/leads at any given time?
   - How many people need access?
   - Budget for tools?

2. **Recommend the right tool for the stage:**
   - **< 20 deals, solo founder** — Spreadsheet or Notion board is fine
   - **20-100 deals, small team** — HubSpot Free CRM or Pipedrive Starter
   - **100+ deals, growing team** — HubSpot Starter or Pipedrive Professional
   - The key criterion: will the team actually use it? Sophistication is worthless without adoption.

3. **Define pipeline stages.** Tailor to the user's sales process:
   - Map stages to actual buyer actions (not internal milestones)
   - Each stage should have a clear entry criteria and exit criteria
   - Example for SaaS B2B: Lead In > Qualified > Demo Scheduled > Demo Done > Proposal Sent > Negotiation > Closed Won / Closed Lost
   - Keep it under 7 stages — more stages means more friction

4. **Define essential fields.** Only what's needed now:
   - Contact: Name, email, company, source/channel
   - Deal: Value, stage, expected close date, next action, owner
   - Custom: 2-3 fields specific to the user's business (e.g., use case, company size, ICP fit score)
   - Rule: if a field won't be used to make a decision, don't create it

5. **Set hygiene rules.** Simple rules to keep data clean:
   - Deals without activity for X days get flagged
   - Stage must be updated after every customer interaction
   - Closed Lost requires a reason (dropdown, not free text)
   - Weekly 15-minute pipeline review ritual

**The deliverable should include:** Tool recommendation with rationale, pipeline stages with entry/exit criteria, field definitions, and hygiene rules.

---

## Task 3: (Re)define GTM Motions

**Duration:** 1-3 hours | **Output:** `outputs/10-gtm-motions.md`

A GTM motion is how you repeatably acquire customers. Most early-stage companies try everything — after launch, you have data to decide what actually works. This task forces that decision.

**What to do:**

1. **Catalog every motion you've tried.** Pull from launch data and prior outputs:
   - **Inbound** — Content, SEO, social media, community, referrals
   - **Outbound** — Cold email, LinkedIn outreach, cold calling, events
   - **Product-led** — Free trial, freemium, self-serve, viral features
   - **Partner/channel** — Resellers, integrations, co-marketing, affiliates
   - **Paid** — Paid ads, sponsorships, paid placements

2. **Score each motion with data.** For every motion attempted:
   - **Volume** — How many leads/users did it generate?
   - **Conversion** — What percentage converted to paying customers?
   - **CAC** — Cost to acquire a customer through this motion (include time)
   - **Time to revenue** — How long from first touch to closed deal?
   - **Scalability** — Can you 10x this motion, or does it cap out?
   - **Team fit** — Do you have the skills and resources to run this well?

3. **Apply the 80/20 rule.** Identify:
   - **Double down (1-2 motions)** — Highest ROI, best team fit, most scalable. These get 80% of resources.
   - **Experiment (1-2 motions)** — Promising signals but need more data. Allocate 20% of resources.
   - **Cut (everything else)** — Either didn't work or doesn't fit. Kill them cleanly.

4. **Define the primary motion.** For the #1 motion:
   - What does the full funnel look like?
   - What are the key metrics at each stage?
   - What resources are required to run it consistently?
   - What's the target cost per acquisition?

**The deliverable should include:** A scored motion catalog, the double-down/experiment/cut classification, and a detailed funnel definition for the primary motion.

---

## Task 4: GTM Roadmap

**Duration:** 1-3 days | **Output:** `outputs/10-gtm-roadmap.md`

The GTM roadmap translates your strategy into a sequenced quarterly plan. It aligns GTM initiatives with the product roadmap and resource reality.

**What to do:**

1. **Define the planning horizon.** Usually one quarter (90 days). Break into three monthly themes or milestones.

2. **Gather inputs.** Pull from completed outputs:
   - Launch retrospective learnings (Task 1)
   - Chosen GTM motions (Task 3)
   - Product roadmap (features coming that affect GTM)
   - Resource constraints (from `my-gtm-context.md` section 8)
   - 90-day goals (from `my-gtm-context.md` section 9)

3. **List all candidate initiatives.** Brainstorm 10-20 things you could do. Examples:
   - Launch a content marketing engine
   - Build an outbound sequence for a new segment
   - Set up a referral program
   - Optimize the signup-to-activation funnel
   - Expand to a new geography or vertical
   - Hire first sales rep / marketing hire

4. **Prioritize using an Impact/Effort matrix.** For each initiative:
   - **Impact** (1-5) — Expected revenue or growth impact
   - **Effort** (1-5) — Time, money, and complexity required
   - **Dependencies** — What needs to happen first?
   - **Risk** — What could go wrong?

5. **Sequence into the roadmap.** Create a monthly or bi-weekly timeline:
   - Month 1: Foundation (highest-impact, lowest-effort items + prerequisites)
   - Month 2: Build (core initiatives that need Month 1 foundations)
   - Month 3: Scale (amplify what's working, launch bigger bets)

6. **Align with product.** Map GTM milestones against product releases. GTM preparation should start 2-4 weeks before feature launches.

7. **Define success metrics.** Each month should have 2-3 measurable targets tied to the chosen GTM motions.

**The deliverable should include:** The prioritized initiative list, the Impact/Effort matrix, a monthly roadmap with milestones, product alignment notes, and success metrics.

---

## Task 5: Growth/GTM Sprints

**Duration:** Ongoing | **Output:** `outputs/10-growth-sprints.md`

Structured sprint cycles bring agile discipline to GTM execution. Instead of reactive firefighting, you run deliberate 2-week experiments with clear hypotheses and outcomes.

**What to do:**

1. **Explain the sprint framework.** A GTM sprint has five parts:
   - **Sprint planning** (1 hour) — Pick 2-3 experiments from the backlog. Define hypothesis, success metric, and owner for each.
   - **Execution** (2 weeks) — Run the experiments. Track progress daily or every other day.
   - **Measurement** (end of sprint) — Did it work? Collect data against success metrics.
   - **Retrospective** (30 min) — What did we learn? What changes for next sprint?
   - **Backlog grooming** (30 min) — Re-prioritize the experiment backlog based on learnings.

2. **Set up the sprint board.** Help the user create a simple tracking system:
   - **Backlog** — All experiment ideas, roughly prioritized
   - **This Sprint** — 2-3 experiments in progress (never more than 3)
   - **Done** — Completed experiments with results
   - Tools: Notion board, Trello, Linear, or a spreadsheet

3. **Create the experiment template.** Each experiment needs:
   - **Hypothesis** — "If we [do X], then [metric Y] will [change by Z]"
   - **Success metric** — Specific, measurable, with a target number
   - **Timeline** — When will we know if it worked?
   - **Resources needed** — Who, what, how much?
   - **Result** — What actually happened (filled in after)
   - **Learning** — What did we learn regardless of outcome?

4. **Seed the first sprint backlog.** Using the GTM roadmap (Task 4) and retrospective learnings (Task 1), generate 8-12 experiment ideas. Prioritize by ICE score:
   - **Impact** (1-10) — If it works, how big is the effect?
   - **Confidence** (1-10) — How confident are you it will work?
   - **Ease** (1-10) — How easy is it to run?

5. **Set the cadence.** Recommend a sustainable rhythm:
   - 2-week sprints for most teams
   - Sprint planning: Monday morning of Week 1
   - Mid-sprint check: Friday of Week 1
   - Sprint review + retro: Friday of Week 2
   - Keep the meetings short — 30-60 minutes max

**The deliverable should include:** The sprint framework, a sprint board template, an experiment template, the initial backlog with ICE scores, and the recommended cadence.

---

## Task 6: CRO Experimentation Backlog

**Duration:** Ongoing | **Output:** `outputs/10-cro-backlog.md`

Conversion rate optimization turns more of your existing traffic into customers. It is the highest-leverage GTM activity because you improve results without increasing spend. This task creates a structured system for running CRO experiments.

**What to do:**

1. **Map the current funnel with conversion rates.** Work with the user to document every step from first visit to paying customer:
   - Visitor > Signup/Lead > Activated > Paying Customer > Retained
   - Capture the conversion rate at each step
   - Identify the biggest drop-off — that's where CRO has the most impact

2. **Audit the biggest drop-off point.** For the weakest stage:
   - What does the user experience at this step?
   - What are the likely friction points?
   - What data do you have (heatmaps, session recordings, user feedback)?
   - What have you already tried?

3. **Generate experiment ideas.** For each funnel stage, brainstorm 5-10 experiments:
   - **Awareness > Visit** — Headlines, ad copy, channel targeting
   - **Visit > Signup** — Landing page copy, CTA placement, social proof, form length
   - **Signup > Activation** — Onboarding flow, time-to-value, welcome emails
   - **Activation > Payment** — Pricing page, trial length, upgrade prompts, feature gating
   - **Payment > Retention** — Engagement loops, check-in emails, feature adoption

4. **Prioritize the backlog.** Use the PIE framework for each experiment:
   - **Potential** (1-10) — How much improvement is possible?
   - **Importance** (1-10) — How valuable is traffic to this page/step?
   - **Ease** (1-10) — How easy is it to implement and measure?
   - Average the three scores to rank experiments

5. **Set up tracking.** Recommend tools based on stage and budget:
   - **Free:** Google Analytics, Google Optimize (sunset — use alternatives), Hotjar free tier
   - **Budget:** PostHog, Mixpanel free tier, VWO starter
   - **Key rule:** Never run an experiment you can't measure. Define the metric before you run the test.

6. **Establish the experimentation cadence.** CRO experiments can run inside or alongside growth sprints:
   - 1-2 CRO experiments running at all times
   - Minimum 2 weeks per experiment (need statistical significance)
   - Document every result — even failures teach you something

**The deliverable should include:** The current funnel map with conversion rates, the prioritized experiment backlog with PIE scores, recommended tools, and the experimentation cadence.

---

## Task 7: Growth Loops

**Duration:** 1-2 weeks | **Output:** `outputs/10-growth-loops.md`

A growth loop is a self-reinforcing cycle where the output of one step becomes the input of the next. Unlike funnels (which are linear and leak), loops compound. The best companies have at least one strong loop driving their growth.

**What to do:**

1. **Explain the three core loop types:**

   - **Viral Loop** — Users bring more users. Example: User signs up > invites team > teammates invite their teams. Mechanisms: referral programs, invite-only access, network effects, shareable outputs.

   - **Content Loop** — Content creates users who create more content. Example: Write SEO content > rank on Google > attract signups > users create data/content > generates more SEO pages. Mechanisms: user-generated content, community contributions, SEO-driven templates.

   - **Paid Loop** — Revenue funds acquisition that generates more revenue. Example: Customer pays > revenue funds ads > ads acquire new customer > repeat. The key metric: payback period. If you recover CAC within 1-3 months, the loop sustains itself.

2. **Assess which loops fit.** Based on the user's product, business model, and GTM motions:
   - Does the product have natural sharing triggers? (Viral)
   - Can user activity generate indexable content? (Content)
   - Is CAC recovery fast enough to reinvest? (Paid)
   - Rate each loop: Strong Fit / Possible / Not Applicable

3. **Design the primary growth loop.** For the best-fit loop:
   - Map every step in the cycle
   - Identify the conversion rate at each step
   - Calculate the loop's multiplication factor (e.g., each user invites 1.3 more users)
   - Identify the bottleneck — which step has the lowest conversion?

4. **Engineer amplifiers.** For each loop, brainstorm ways to increase the multiplication factor:
   - **Viral:** Better incentives, easier sharing, more share-worthy moments
   - **Content:** SEO optimization, template libraries, community features
   - **Paid:** Better targeting, higher LTV, faster payback

5. **Set loop metrics.** Define how you'll track loop health:
   - Viral: K-factor (invites sent x acceptance rate), viral cycle time
   - Content: Organic traffic growth rate, content-to-signup conversion
   - Paid: CAC payback period, ROAS, reinvestment rate

**The deliverable should include:** Assessment of loop fit, a detailed map of the primary loop with conversion rates, amplifier ideas, and loop metrics.

---

## Task 8: SOPs (Standard Operating Procedures)

**Duration:** 1-3 days | **Output:** `outputs/10-sops.md`

If it only works when you do it personally, it doesn't scale. SOPs document your repeatable processes so anyone on the team (or a future hire) can execute your playbook.

**What to do:**

1. **Identify which processes need SOPs.** Prioritize by frequency and impact:
   - **Marketing SOPs** — Content publishing, social media posting, email campaigns, ad management, SEO workflow
   - **Sales SOPs** — Lead qualification, demo process, proposal creation, follow-up cadence, deal handoff
   - **Onboarding SOPs** — Customer welcome sequence, setup assistance, first-value guidance, check-in schedule
   - **Operations SOPs** — Reporting rhythm, tool administration, data hygiene, vendor management

2. **Use the "document the top 3" approach.** Don't try to SOP everything at once. Ask:
   - Which 3 processes do you repeat most often?
   - Which 3 processes would break if you went on vacation?
   - Which 3 processes does someone else need to learn next?
   - The union of these answers is your SOP priority list.

3. **Write each SOP using a standard template:**
   - **Purpose** — Why does this process exist? What outcome does it produce?
   - **Trigger** — When does this process start? (Time-based, event-based, request-based)
   - **Steps** — Numbered, specific, with exact tool names and actions. Write for someone who's never done it before.
   - **Tools needed** — Links to tools, templates, and resources
   - **Quality check** — How do you know it was done correctly?
   - **Owner** — Who is responsible for this process?
   - **Frequency** — How often does it run?

4. **Draft the top 3 SOPs.** Help the user write their three highest-priority SOPs. Each should be concrete enough that a new team member could follow it on day one.

5. **Set the SOP maintenance rhythm:**
   - Review SOPs quarterly — processes evolve, docs should too
   - When you change a process, update the SOP immediately (not "later")
   - Store all SOPs in one place (Notion, Google Docs folder, or even a directory in the repo)

**The deliverable should include:** The SOP priority list, 3 fully drafted SOPs using the template, and the maintenance rhythm.

---

## Task 9: Explore New Markets

**Duration:** < 1 month | **Output:** `outputs/10-new-market-exploration.md`

New market exploration is the reward for having a working GTM system. Once your core motion is repeatable and profitable, you can experiment with expansion. Not before. This task provides a framework for evaluating and entering adjacent markets.

**What to do:**

1. **Confirm readiness.** Before exploring new markets, verify:
   - Core GTM motion is repeatable (not dependent on heroics)
   - Unit economics are healthy (CAC < LTV with acceptable payback)
   - Team has capacity (expansion doesn't starve the core)
   - If any of these are shaky, recommend strengthening the core first

2. **Map expansion vectors.** There are four directions to grow:
   - **New segments** — Same product, different customer type (e.g., SMB to mid-market)
   - **New geographies** — Same product and segment, different region
   - **New use cases** — Same customers, different problem your product can solve
   - **New channels** — Same product and segment, new distribution method

3. **Evaluate each opportunity.** For each expansion vector:
   - **Market size** — Is the new market large enough to justify the investment?
   - **Adjacency** — How much can you reuse from your current GTM? (Messaging, channels, product)
   - **Competition** — Who owns this market today? How strong are they?
   - **Evidence** — Do you already have signals? (Inbound from this segment, requests for this use case)
   - **Resource cost** — What does entry require? (Localization, new hires, product changes, new content)

4. **Design a lightweight market test.** For the most promising vector:
   - Define a 30-day experiment to test demand
   - Minimum viable entry: what's the cheapest way to get signal?
   - Success criteria: what would convince you to invest more?
   - Kill criteria: what would tell you to stop?

5. **Plan the expansion playbook.** If the test succeeds:
   - What changes in messaging/positioning?
   - What new content or assets are needed?
   - Does the sales process change?
   - Do you need local presence, partnerships, or regulatory compliance?
   - Timeline: 30-60-90 day plan for market entry

**The deliverable should include:** Readiness assessment, expansion vector evaluation, the lightweight test design, and a conditional expansion playbook.

---

## Summary: What You've Built in Phase 10

After completing the tasks above, the user should have:

| Output | What It Proves |
|--------|---------------|
| `10-launch-retrospective.md` | Captured learnings while fresh — no repeating mistakes |
| `10-crm-setup.md` | Pipeline tracked, opportunities don't fall through cracks |
| `10-gtm-motions.md` | Data-driven decision on which motions to double down vs. cut |
| `10-gtm-roadmap.md` | Sequenced quarterly plan aligned with product and resources |
| `10-growth-sprints.md` | Agile discipline applied to GTM with clear experiment cycles |
| `10-cro-backlog.md` | Systematic approach to improving conversion at every funnel stage |
| `10-growth-loops.md` | Self-reinforcing growth mechanisms designed and measured |
| `10-sops.md` | Repeatable processes documented so the team can scale |
| `10-new-market-exploration.md` | Structured approach to expansion once the core is working |

**This phase transforms a launch into a system.** The user entered Phase 10 with launch results and ad-hoc processes. They leave with repeatable systems, structured experimentation, and a roadmap for the next quarter. The shift from "we launched" to "we have a GTM machine" is what separates one-time launches from sustainable growth.

### Next Steps

Proceed to **Phase 11: `running-marketing`** to build the full marketing engine: brand narrative, content marketing, social media, email marketing, paid acquisition, and community building.

---

## Go Deeper

- **"Go-To-Market Strategist" by Maja Voje** — Chapters on Post-Launch Systems and Growth cover the frameworks behind sprint cycles, growth loops, and GTM motion selection.
- **"Hacking Growth" by Sean Ellis & Morgan Brown** — The definitive guide to growth sprints, experimentation backlogs, and the ICE prioritization framework used in Task 5.
- **"Traction" by Gabriel Weinberg & Justin Mares** — The Bullseye Framework for systematically testing and selecting GTM channels, directly relevant to Task 3.
- **"The Lean Startup" by Eric Ries** — Build-Measure-Learn loops that underpin the sprint and experimentation approach in Tasks 5-6.
- **"Scaling Lean" by Ash Maurya** — Practical frameworks for moving from traction to scale, including growth model design relevant to Task 7.
- **GTM Strategist templates** — Maja's original worksheets for GTM roadmapping, sprint planning, and SOP documentation.

---

*GTM Strategist methodology by Maja Voje. https://gtmstrategist.com*
