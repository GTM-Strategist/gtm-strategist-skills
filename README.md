# GTM Strategist Skills

**Your AI go-to-market co-pilot.** 12 skills that walk you through the complete GTM Strategist methodology by Maja Voje — from first strategy session to scaling your sales engine.

100 tasks. Each phase builds on the last. Tested with 1000+ companies.

Works with **Claude Code**, **Claude Cowork**, and **Claude.ai**.

---

## What This Is

Most AI prompts handle one task in isolation. But GTM doesn't work that way — your competitor analysis should feed your positioning, your positioning should feed your pitch deck, your pitch deck should feed your sales process.

These 12 skills follow the complete GTM journey. You set up your product context once, then ask for what you need. The right skill activates and gives you tailored output for your specific product and market.

All outputs build on each other. By the end, you have a **complete GTM playbook**.

---

## The 12 Skills

Work through them in order (recommended) or jump to what you need right now.

| # | Skill | What You'll Build | Tasks |
|---|-------|-------------------|-------|
| 1 | **GTM Foundations** | OPE canvas, SWOT analysis, value proposition, 90-day plan | 11 |
| 2 | **Collecting Intelligence** | Beachhead segments, customer interviews, competitor analysis | 9 |
| 3 | **Validating Customers** | Assumption mapping, experiments, validated ICP/persona | 7 |
| 4 | **Building Product** | JTBD value prop, product roadmap, MVP, metrics & tracking | 9 |
| 5 | **Setting Pricing** | Competitive pricing analysis, WTP research, business model | 7 |
| 6 | **Crafting Positioning** | Positioning statement, UVP/USP, messaging, visual identity | 5 |
| 7 | **Preparing Launch Assets** | Website brief, demo script, media kit, pitch deck, press release | 6 |
| 8 | **Building Communication Engine** | GTM motions, channel strategy, funnel model, social proof | 9 |
| 9 | **Executing Launch** | Support network, launch email, event plan, engagement playbook | 7 |
| 10 | **Building GTM System** | Retrospective, CRM setup, growth sprints, growth loops, SOPs | 9 |
| 11 | **Running Marketing** | Strategic narrative, content strategy, email, paid, community | 11 |
| 12 | **Executing Sales** | Sales deck, case studies, outbound campaign, ABM, partnerships | 10 |

**Total: 100 tasks across 12 phases of your GTM journey.**

---

## Install

### Option 1: Claude Code Plugin (recommended)

Install directly from your terminal — no cloning or downloading needed:

```bash
claude plugin install GTM-Strategist/gtm-strategist-skills
```

This installs the 12 GTM skills as a plugin. They'll be available in every Claude Code session.

To install for the current project only:

```bash
claude plugin install GTM-Strategist/gtm-strategist-skills --scope project
```

### Option 2: Clone and use directly

```bash
git clone https://github.com/GTM-Strategist/gtm-strategist-skills.git
cd gtm-strategist-skills
claude
```

Skills activate automatically when you open Claude Code in this folder.

### Option 3: Claude Cowork (desktop app)

1. Open the Claude Desktop app → switch to the **Cowork** tab
2. Install the plugin: **Settings** → **Plugins** → **Add plugin** → paste `https://github.com/GTM-Strategist/gtm-strategist-skills`
3. The 12 GTM skills activate automatically

### Option 4: Claude.ai (web chat)

1. Go to [claude.ai](https://claude.ai) → **Projects** → **Create a new project**
2. Upload `CLAUDE.md` and `my-gtm-context.md`
3. Upload the skill files you want from `skills/` — each phase has a `SKILL.md` file (e.g., `skills/gtm-foundations/SKILL.md`)

> **Note:** Unlike Claude Code and Cowork, outputs won't auto-save as files — copy them from the chat.

---

## Set Up Your Product Context

**Easy way (recommended):** Just start talking. Tell Claude about your product, market, and goals. It will interview you and save the context automatically.

Try: *"I want to set up my GTM context. Let me tell you about my product."*

**Manual way:** Open `my-gtm-context.md` and fill in the sections. You don't need to complete everything — the skills will ask for anything that's missing.

---

## Start Working

Tell Claude what you need in plain language:

- *"Let's start with the GTM foundations"*
- *"Help me figure out my pricing strategy"*
- *"I need to prepare for our product launch"*
- *"Help me build a sales deck"*
- *"What should I work on next?"*

---

## How Skills Work Together

```
Phase 1-3: UNDERSTAND          Phase 4-6: BUILD              Phase 7-9: LAUNCH
┌─────────────────────┐   ┌─────────────────────┐   ┌─────────────────────┐
│ GTM Foundations      │──▶│ Building Product     │──▶│ Launch Assets       │
│ Collect Intelligence │──▶│ Setting Pricing      │──▶│ Communication Engine│
│ Validate Customers   │──▶│ Craft Positioning    │──▶│ Execute Launch      │
└─────────────────────┘   └─────────────────────┘   └─────────────────────┘
                                                              │
                                                              ▼
                                                    Phase 10-12: SCALE
                                                    ┌─────────────────────┐
                                                    │ Build GTM System    │
                                                    │ Run Marketing       │
                                                    │ Execute Sales       │
                                                    └─────────────────────┘
```

Each phase builds on the previous. Your competitor analysis feeds into positioning. Your positioning feeds into your pitch deck. Your pitch deck feeds into your sales process. **Nothing exists in isolation.**

All outputs are saved in the `outputs/` folder so later skills can reference earlier work automatically.

---

## FAQ

**Do I need to be technical?**
No. Claude Code requires typing in a terminal, but that's just `claude` and then talking. Claude Cowork is a desktop app — no terminal needed.

**Do I need an API key?**
Not necessarily. Both Claude Code and Cowork work with a regular Claude subscription (Pro at $20/mo, Max at $100/mo, or Team). An API key is only needed if you prefer pay-per-use billing.

**Do I have to go in order?**
No, but it's recommended — especially for your first product. Each phase builds on the previous. If you skip ahead, Claude will tell you what assumptions you're making.

**Can my team use this?**
Yes. Share the repo, have each person fill in their own `my-gtm-context.md`, and they can run the same skills independently.

**How long does the full journey take?**
The methodology is designed for a 90-day GTM timeline. With Claude's help, you can compress the thinking work significantly — but validation and execution still take real-world time.

**What if I already have some GTM work done?**
Perfect. Tell Claude what you've already done (or fill in the "Prior Work" section of `my-gtm-context.md`) and jump to whatever phase you need.

**Can I customize the skills?**
Absolutely. The skills are markdown files in `skills/`. Edit them to match your workflow or methodology.

---

## About

These skills are based on the **GTM Strategist methodology** by [Maja Voje](https://gtmstrategist.com), tested with 1000+ companies.

**Want to go deeper?**

- [GTM Strategist Book](https://gtmstrategist.com/book) — The complete methodology with case studies and templates
- [GTM Strategist Masterclass](https://gtmstrategist.com/masterclass) — Video course walking through every phase with real examples
- [GTM Strategist Checklist](https://gtmstrategist.com/gtm-checklist) — The full interactive checklist with templates and workshops

---

## License

MIT — use freely, modify as needed.
