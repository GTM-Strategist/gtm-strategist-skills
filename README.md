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

## Quick Start

### Step 1: Download the skills

**Option A — Git clone** (if you have Git):
```bash
git clone https://github.com/GTM-Strategist/gtm-strategist-skills.git
cd gtm-strategist-skills
```

**Option B — Download ZIP**:
Click the green **Code** button on GitHub → **Download ZIP** → extract to a folder.

---

### Step 2: Pick how you'll use them

<details>
<summary><strong>Claude Code (terminal)</strong></summary>

Claude Code is Anthropic's AI assistant that runs in your terminal. Skills auto-activate, outputs save as files, and context persists across sessions.

**What you need:**
- A terminal (Terminal on Mac, Git Bash or PowerShell on Windows)
- A Claude subscription (Pro, Max, or Team) **OR** an [Anthropic API key](https://console.anthropic.com/)

**Install Claude Code:** Follow the [getting started guide](https://docs.anthropic.com/en/docs/claude-code/getting-started).

**Then:**
```bash
cd gtm-strategist-skills
claude
```

That's it. Start talking.

</details>

<details>
<summary><strong>Claude Cowork (desktop app)</strong></summary>

Claude Cowork is Anthropic's desktop agent that runs multi-step tasks on your computer. This repo includes a plugin manifest so you can install the skills directly.

**What you need:**
- Claude Desktop app with Cowork enabled (any paid Claude plan)

**Setup:**
1. Open the Claude Desktop app → switch to the **Cowork** tab
2. Select the downloaded `gtm-strategist-skills` folder as your working directory (click the folder name dropdown at the top → **Choose a different folder** → select the unzipped folder)
3. The 12 GTM skills will activate automatically

Once set up, just ask Claude for what you need — *"help me with positioning"*, *"I need a pricing strategy"* — and the right skill activates.

> **Tip:** The `.claude` folder (which contains the skills) is hidden by default on macOS and Windows. You don't need to see it — just select the main folder and everything works.

</details>

<details>
<summary><strong>Claude.ai (web chat)</strong></summary>

You can use these skills directly in Claude's web interface using Projects. No terminal or desktop app needed.

**What you need:**
- A Claude account at [claude.ai](https://claude.ai) (Pro, Max, or Team)

**Setup:**
1. Go to [claude.ai](https://claude.ai) → click **Projects** in the sidebar → **Create a new project**
2. Open the project → click **Add content** in the project knowledge section
3. Upload `CLAUDE.md` and `my-gtm-context.md` from the downloaded folder
4. Upload the skill files you want to use from `.claude/skills/` — each phase has its own folder with a `SKILL.md` file inside (e.g., `.claude/skills/gtm-foundations/SKILL.md`)

> **Tip:** The `.claude` folder is hidden by default. On Mac, press `Cmd + Shift + .` in Finder to show hidden files. On Windows, click **View** → **Show** → **Hidden items** in File Explorer.

Start a conversation inside the project and ask for what you need. Claude will use the skills and your product context automatically.

**Note:** Unlike Claude Code and Cowork, outputs won't auto-save as files — copy them from the chat when you're done.

</details>

---

### Step 3: Set up your product context

**Easy way (recommended):** Just start talking. Tell Claude about your product, market, and goals. It will interview you about what it needs and save the context for you.

Try: *"I want to set up my GTM context. Let me tell you about my product."*

**Manual way:** Open `my-gtm-context.md` in any text editor and fill in the sections. You don't need to complete everything — the skills will ask for anything that's missing.

---

### Step 4: Start working

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
Absolutely. The skills are just markdown files in `.claude/skills/`. Edit them to match your workflow or methodology.

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

