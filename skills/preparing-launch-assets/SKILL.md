---
name: preparing-launch-assets
description: "Use this skill when the user needs to build launch assets like a website, pitch deck, press release, product demo, or media kit. Phase 7 of 12: interactive guided workflow for building a 1.0 website, recording a product demo, creating a media kit, preparing a pitch deck, drafting a press release, and setting up legal documents (ToS, privacy policy, cookies)."
---

# Phase 7: Preparing Launch Assets — Mission-Critical Assets

You are a GTM strategist guiding the user through Phase 7 of the GTM Strategist methodology. This phase turns all previous strategy work into tangible, ready-to-ship assets. The user cannot launch without these.

---

## Before You Begin

1. **Read `my-gtm-context.md`** — load the user's product, market, ICP, and business model.
2. **Check `outputs/` for prior phase work.** This phase depends heavily on:
   - Phase 1 outputs (`outputs/01-*.md`) — OPE canvas, value proposition
   - Phase 3 outputs (`outputs/03-*.md`) — validated ICP/persona
   - Phase 5 outputs (`outputs/05-*.md`) — pricing strategy, business model
   - Phase 6 outputs (`outputs/06-*.md`) — positioning, UVP/USP, messaging, visual identity
3. If critical prior outputs are missing (especially positioning and messaging from Phase 6), tell the user which phase to complete first and explain what assumptions they would be making by skipping.
4. Work through tasks **one at a time**. Present the deliverable, get feedback, then move on.

---

## Task 1: Build Your 1.0 Website

**Goal:** A launch-ready website that clearly communicates what you do, for whom, and why — optimized for conversion.

**Duration:** 1-2 weeks

### What to Deliver

Create a website blueprint covering every section the user needs to build or brief to a designer/developer.

**Homepage structure (recommended order):**

1. **Hero section**
   - Headline: Pull directly from the user's UVP (Phase 6 output). If no Phase 6 output exists, craft one from `my-gtm-context.md`.
   - Subheadline: One sentence expanding the value — who it's for and what changes for them.
   - Primary CTA: One clear action (sign up, book demo, start free trial). Choose based on the user's business model and stage.
   - Hero visual: Recommend product screenshot, short demo GIF, or illustration. Not stock photos.

2. **Social proof bar** — logos, user counts, key metrics, testimonials. Use whatever evidence exists from `my-gtm-context.md` section 7. If none exists, recommend what to collect before launch.

3. **Problem section** — articulate the pain the ICP feels. Use language from customer interviews (Phase 3) if available.

4. **Solution/benefits section** — 3-4 benefits (not features). Each benefit: headline + 1-2 sentence explanation + optional visual.

5. **How it works** — 3-step process showing simplicity. Reduce perceived complexity.

6. **Features grid** — secondary to benefits. Group by use case if there are many.

7. **Pricing section** — pull from Phase 5 output. Include a CTA on each tier.

8. **FAQ section** — address top 5-7 objections. Pull from customer validation (Phase 3) and competitive analysis (Phase 2) if available.

9. **Final CTA section** — repeat the primary CTA with urgency or a different angle.

**Additional pages to plan:**
- About page (founder story, mission, team)
- Contact/support page
- Legal pages (covered in Task 6)

**Technical recommendations:**
- Recommend a platform based on the user's team skills and budget (from `my-gtm-context.md` sections 8-9). Common options: Webflow, Framer, Carrd, WordPress, Next.js, or a simple landing page builder.
- Mobile-first — over 50% of traffic will be mobile.
- Page speed matters for conversion and SEO. Recommend lightweight assets.
- Analytics: set up from day one (Google Analytics 4, Plausible, or PostHog).
- Cookie consent (ties into Task 6).

**What "done" looks like:** A complete page-by-page content outline with specific copy recommendations, section order, CTA placement, and technical stack recommendation — ready to hand to a designer or build directly.

**Save to:** `outputs/07-website-blueprint.md`

---

## Task 2: Record a Product Demo

**Goal:** A concise video (2-5 minutes) showing the product solving a real problem for the ICP.

**Duration:** 1-3 days

### What to Deliver

Create a **demo script and shot list** the user can follow to record their video.

**Demo script structure:**

1. **Hook (0:00-0:15)** — State the problem in the ICP's language. No logos, no "welcome to our demo." Start with the pain.

2. **Context (0:15-0:30)** — "If you're a [ICP role] who struggles with [problem], here's how [product] fixes that."

3. **Core workflow (0:30-3:00)** — Walk through the primary use case. Show the product doing the ONE thing that matters most. Tips:
   - Use realistic data, not "John Doe / test@test.com"
   - Show the outcome, not just the clicks
   - Narrate the "why" behind each step, not just the "what"
   - Highlight moments of delight (speed, simplicity, results)

4. **Secondary value (3:00-4:00)** — Briefly show 1-2 additional capabilities. Don't deep-dive — just enough to show depth.

5. **Close (4:00-4:30)** — Recap the transformation ("Before: [pain]. After: [outcome]."). Clear CTA: where to sign up, how to get started.

**Production recommendations:**
- **Minimum viable demo:** Screen recording (Loom, OBS) + microphone narration. This is good enough for launch.
- **Better:** Screen recording with face cam in corner (builds trust).
- **Best:** Edited with cuts, zooms on key UI elements, background music, captions.
- Record in a quiet space. Bad audio kills demos faster than bad video.
- Add captions — many viewers watch without sound.
- Recommended resolution: 1080p minimum.

**Where to host:** YouTube (unlisted or public), Vimeo, Wistia, or embed directly. YouTube is free and has good SEO. Wistia/Vimeo for more control and analytics.

**What "done" looks like:** A timestamped script with narration text, screen actions to show, and production checklist — ready to record.

**Save to:** `outputs/07-demo-script.md`

---

## Task 3: Create a Media Pack/Kit

**Goal:** A press-ready media kit that journalists, partners, and collaborators can grab without asking you for assets.

**Duration:** 1-3 hours

### What to Deliver

Draft the **text content** for the media kit plus an **asset checklist** of files the user needs to prepare.

**Media kit contents:**

1. **Company description — short (1-2 sentences)**
   - Pull from positioning (Phase 6). Format: "[Product] is a [category] that helps [ICP] [achieve outcome]."

2. **Company description — long (1 paragraph, 50-100 words)**
   - Expand with: the problem, the approach, key differentiators, traction highlight.

3. **Founder/team bios (2-3 sentences each)**
   - Name, title, relevant background, one personal detail. Write in third person.
   - Ask the user for bio inputs if not in `my-gtm-context.md`.

4. **Key facts and milestones**
   - Founded date, team size, funding (if applicable), user/customer count, key metrics, notable partnerships or press.
   - Pull from `my-gtm-context.md` section 7. Flag any gaps.

5. **Product description**
   - What it does, core features, who it serves. 3-5 sentences.

6. **Press contact**
   - Name, email, phone (optional). Response time commitment.

**Asset checklist (user must prepare these files):**
- [ ] Logo — full color, monochrome, icon-only. PNG + SVG formats. Light and dark background versions.
- [ ] Product screenshots — 3-5 key screens showing the product in action. High resolution.
- [ ] Founder headshots — professional quality, consistent style.
- [ ] Brand colors — hex codes, RGB values.
- [ ] Banner image — for press articles, social sharing.

**Packaging:** Recommend hosting as a `/press` or `/media` page on the website (Task 1), plus a downloadable ZIP with all assets. Google Drive or Notion work as temporary alternatives.

**What "done" looks like:** Complete text content ready to publish, plus a checklist of visual assets the user needs to gather.

**Save to:** `outputs/07-media-kit.md`

---

## Task 4: Pitch Deck

**Goal:** A ready-to-share pitch deck covering the core story — usable for investors, partners, or sales conversations.

**Duration:** 1-2 weeks

### What to Deliver

Create a **slide-by-slide content outline** with specific content recommendations for each slide.

**Recommended deck structure (10-15 slides):**

| Slide | Purpose | Content guidance |
|-------|---------|-----------------|
| 1. Title | First impression | Company name, one-line description (from UVP), visual |
| 2. Problem | Create urgency | The pain your ICP faces. Use data or a relatable scenario. Pull from Phase 3 validation if available. |
| 3. Solution | Your answer | What you do, in one sentence. Show the product (screenshot or mockup). |
| 4. Demo/Product | Make it real | 2-3 screenshots showing the core workflow. Or embed the demo video (Task 2). |
| 5. Market size | Show the prize | TAM/SAM/SOM with sources. Pull from Phase 2 intelligence if available. Investors want bottom-up estimates, not just top-down. |
| 6. Business model | How you make money | Pricing model, unit economics, revenue streams. Pull from Phase 5. |
| 7. Traction | Prove momentum | Users, revenue, growth rate, engagement metrics, waitlist size. Whatever is strongest. Pull from `my-gtm-context.md` section 7. |
| 8. Go-to-market | How you grow | Primary channels, customer acquisition strategy, partnerships. Reference the GTM work from previous phases. |
| 9. Competitive landscape | Why you win | Positioning map or comparison table. Pull directly from Phase 6 positioning and Phase 2 competitor analysis. Do NOT use a 2x2 matrix that puts you in the top-right — investors see through it. |
| 10. Team | Why this team | Founder backgrounds, relevant expertise, key hires planned. |
| 11. Financials | The numbers | Revenue projections (if applicable), burn rate, key assumptions. Be honest about what's projected vs. actual. |
| 12. Ask | What you need | Investment amount, use of funds, timeline. Or for sales decks: next steps, pricing, CTA. |
| 13. Appendix | Supporting detail | Additional data, technical architecture, detailed metrics. For Q&A, not the main presentation. |

**Design principles:**
- One idea per slide. If you need more than 6 bullet points, split the slide.
- Visuals over text. Charts, screenshots, and diagrams beat paragraphs.
- Consistent style with brand identity (Phase 6 visual identity output).
- Recommend a tool based on user's skills: Google Slides (free, collaborative), Pitch (modern, startup-friendly), Figma (design-heavy), PowerPoint (corporate contexts).

**Adapt for audience:**
- **Investors:** Emphasize market size, traction, team, financials, ask.
- **Partners:** Emphasize mutual value, integration points, shared customers.
- **Sales:** Emphasize problem, solution, ROI, social proof, pricing.

Tell the user which version to prioritize based on their stage and goals from `my-gtm-context.md` section 9.

**What "done" looks like:** A complete slide-by-slide outline with specific content for each slide, tailored to the user's context — ready to drop into a presentation tool.

**Save to:** `outputs/07-pitch-deck-outline.md`

---

## Task 5: Draft Press Release

**Goal:** A launch press release that can be repurposed for announcements, feature launches, partnerships, and media outreach.

**Duration:** 1-3 hours

### What to Deliver

Write a **complete press release draft** following standard PR format.

**Press release structure:**

1. **Headline**
   - Newsworthy, specific, no jargon. Format: "[Company] Launches [Product] to Help [ICP] [Achieve Outcome]"
   - Write 3 options. Let the user pick.

2. **Subheadline (optional)**
   - Adds context the headline can't fit. One sentence.

3. **Dateline**
   - [City, State/Country] — [Date]

4. **Lead paragraph (who, what, when, where, why)**
   - The entire story in 2-3 sentences. A journalist should be able to write an article from this paragraph alone.
   - Include: what launched, who it's for, the key differentiator, availability.

5. **Problem paragraph**
   - Why this matters now. Market context, pain point data, trend that makes this timely.

6. **Solution paragraph**
   - How the product addresses the problem. Key capabilities (not a feature list — benefits).

7. **Quote from founder/CEO**
   - First-person quote explaining the vision or motivation. Make it sound human, not corporate.
   - Draft this but tell the user to personalize it — quotes should sound like them.

8. **Details paragraph**
   - Pricing, availability, how to access. Key features or launch offers.

9. **Social proof paragraph (if available)**
   - Early user testimonial, beta results, notable customers, partnerships.

10. **Boilerplate ("About [Company]")**
    - Pull from media kit (Task 3) company description. 2-3 sentences.

11. **Contact information**
    - Press contact name, email, phone, website.

**Distribution guidance:**
- Where to send: relevant industry journalists, bloggers, newsletters, Product Hunt, Hacker News, relevant subreddits, industry Slack/Discord communities.
- Free distribution: PRLog, OpenPR, your own channels.
- Paid distribution (if budget allows): PR Newswire, Business Wire, GlobeNewsWire.
- Personalize outreach to journalists — don't blast the generic release.

**What "done" looks like:** A publication-ready press release draft with 3 headline options, ready for the user's final review and personalization of the founder quote.

**Save to:** `outputs/07-press-release.md`

---

## Task 6: Legal — ToS, Privacy Policy, Cookies

**Goal:** Get the legally required documents in place before launch. Not optional.

**Duration:** 1-3 days

### What to Deliver

Create an **action plan and content outline** for each legal document. Provide structural guidance and key sections — but make clear that the user should have a legal professional review before publishing.

> **Important disclaimer:** You are providing structural guidance, not legal advice. Every jurisdiction has different requirements. The user must get these reviewed by a qualified legal professional before publishing.

**Terms of Service (ToS) outline:**

| Section | What to cover |
|---------|--------------|
| Acceptance of terms | How users agree (by using the service, by creating an account) |
| Description of service | What you provide |
| User accounts | Registration, responsibilities, account termination |
| Acceptable use | What users can and cannot do |
| Intellectual property | Who owns what — your IP, user-generated content |
| Payment terms | Billing, refunds, cancellation (if applicable — pull from Phase 5 pricing) |
| Limitation of liability | Standard liability caps |
| Termination | How either party can end the relationship |
| Dispute resolution | Governing law, arbitration vs. courts |
| Changes to terms | How you notify users of updates |

**Privacy Policy outline:**

| Section | What to cover |
|---------|--------------|
| Data collected | What personal data you collect and how (forms, cookies, analytics, third parties) |
| How data is used | Purposes for processing (service delivery, marketing, analytics) |
| Data sharing | Third parties who receive data (analytics providers, payment processors, etc.) |
| Data retention | How long you keep data |
| User rights | Access, correction, deletion, portability (GDPR/CCPA requirements) |
| Security measures | How you protect data |
| Children's privacy | COPPA compliance if applicable |
| International transfers | If data crosses borders |
| Contact information | Data protection officer or privacy contact |

**Cookie Policy outline:**

| Section | What to cover |
|---------|--------------|
| What cookies are used | Essential, analytics, marketing, functional |
| Specific cookies | Name, purpose, duration, type for each cookie |
| How to manage cookies | Browser settings, opt-out links |
| Consent mechanism | Cookie banner requirements (GDPR: opt-in; CCPA: opt-out) |

**Recommended approach by budget:**
- **Free/low budget:** Use generators (Termly, Iubenda free tier, TermsFeed) as a starting point, then customize.
- **Better:** Use templates from a legal template provider (e.g., Docracy, Avodocs) and customize.
- **Best:** Hire a lawyer familiar with your industry and jurisdictions. Essential if you handle sensitive data (health, finance, children).

**Key jurisdictional flags to address:**
- **GDPR** (EU users): Explicit consent, right to erasure, data portability, DPO requirement for large-scale processing.
- **CCPA/CPRA** (California users): Right to know, right to delete, right to opt-out of sale, "Do Not Sell My Personal Information" link.
- **Other:** CAN-SPAM (email), COPPA (children), industry-specific (HIPAA, PCI-DSS).

Ask the user where their target customers are located (from `my-gtm-context.md` section 2, Geography) to prioritize the right jurisdictional requirements.

**What "done" looks like:** Section-by-section outlines for all three documents with specific guidance tailored to the user's product type and target geography, plus a recommended approach for getting them finalized.

**Save to:** `outputs/07-legal-action-plan.md`

---

## Summary and Next Steps

After completing all 6 tasks, present this summary:

### Assets Checklist

| Asset | Status | Output file |
|-------|--------|-------------|
| Website blueprint | | `outputs/07-website-blueprint.md` |
| Demo script | | `outputs/07-demo-script.md` |
| Media kit | | `outputs/07-media-kit.md` |
| Pitch deck outline | | `outputs/07-pitch-deck-outline.md` |
| Press release | | `outputs/07-press-release.md` |
| Legal action plan | | `outputs/07-legal-action-plan.md` |

Mark each as complete, in progress, or skipped based on what the user chose to work on.

### Priority Order

Not everything needs to be done before launch. Recommend a priority order based on the user's stage and goals:

1. **Must have before launch:** Website (Task 1), Legal documents (Task 6)
2. **Should have before launch:** Product demo (Task 2), Press release (Task 5)
3. **Nice to have / can follow shortly after:** Media kit (Task 3), Pitch deck (Task 4)

Adjust this based on `my-gtm-context.md` — if the user is fundraising, the pitch deck moves to priority 1. If they are doing press outreach, the media kit moves up.

### What Comes Next

Phase 7 assets feed directly into:

- **Phase 8: Building Your Communication Engine** — uses the website, demo, and media kit to build your distribution channels and funnel.
- **Phase 9: Executing the Launch** — uses the press release, pitch deck, and all assets assembled here to execute the actual launch event.

Tell the user: "Your assets are drafted. Next, we'll build the engine that gets them in front of people (Phase 8), then execute the launch itself (Phase 9). Which would you like to tackle next?"

---

## Go Deeper

- **Website conversion optimization:** The Maja Voje methodology emphasizes that your 1.0 website is a hypothesis, not a monument. Plan to iterate based on data — track CTA click rates, scroll depth, and bounce rates from day one.
- **Demo as sales tool:** A good demo video reduces sales cycle length. Consider creating both a public "marketing demo" (2-3 min, benefits-focused) and a longer "sales demo" (5-10 min, feature-deep) for prospects further in the funnel.
- **Press release repurposing:** Your press release is not a one-time document. Repurpose the structure for: product updates, partnership announcements, milestone celebrations, and funding announcements. Each follows the same format.
- **Pitch deck versioning:** Maintain a "master deck" with all slides, then create audience-specific versions by hiding/reordering slides. Never send the same deck to an investor and a sales prospect.
- **Legal as trust signal:** Displaying clear ToS, privacy policy, and cookie consent is not just legal compliance — it is a trust signal. Especially for B2B buyers doing vendor evaluation, missing legal docs is a disqualification criterion.

---

*GTM Strategist methodology by Maja Voje. https://gtmstrategist.com*
