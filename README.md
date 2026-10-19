# Growth Marketing — SKILL.md files for AI agents

[![13 skills](https://img.shields.io/badge/skills-13-0b7285)](#whats-inside)
[![Format: Agent Skills](https://img.shields.io/badge/format-SKILL.md-5f3dc4)](https://agentskills.io/specification)
[![Works with Claude Code & Codex](https://img.shields.io/badge/works%20with-Claude%20Code%20%7C%20Codex%20%7C%20Claude.ai-1c7ed6)](#install)
[![Licence: CC BY 4.0](https://img.shields.io/badge/licence-CC%20BY%204.0-2b8a3e)](https://creativecommons.org/licenses/by/4.0/)

Free, ready-to-run **growth marketing** skills for **Claude, Claude Code, OpenAI Codex** and any agent that reads
the [Agent Skills](https://agentskills.io/specification) format. North star metrics, growth models, funnels,
cohort retention, growth loops, referral programmes, experimentation and tracking plans. Each skill is a single
`SKILL.md`: a senior practitioner's workflow — when to use it, the inputs to ask for, a numbered process, decision
rules, an output template and sources — loaded only when a task needs it.

Part of the [Marketing Skills library](https://github.com/afeezadebayo/marketing-skills) by
[Afeez Adebayo](https://afeezadebayo.com) · [Browse online](https://afeezadebayo.com/skills-md/marketing/growth-marketing/)

## Install

Each skill is its own folder with a `SKILL.md`, so you can drop any folder straight into an agent.

**Claude Code**
```bash
git clone https://github.com/afeezadebayo/growth-marketing-skills.git
cp -r growth-marketing-skills/growth-audit ~/.claude/skills/        # all projects
# or  .claude/skills/   inside one project
```

**OpenAI Codex**
```bash
cp -r growth-marketing-skills/growth-audit ~/.agents/skills/         # all repos
```

**Claude.ai / Desktop** — zip a skill folder, then **Settings → Capabilities → Skills → Upload skill**
(code execution must be enabled). To bulk-load the whole category into a Claude Project, custom GPT or
knowledge base, grab the single-folder `.zip` from the
[library page](https://afeezadebayo.com/skills-md/marketing/growth-marketing/).

Then start a new session and ask your agent which skills it can use.

## What's inside

| Skill | What it does |
|---|---|
| [`growth-audit`](growth-audit/SKILL.md) | Audit a company's growth system end to end, find the single biggest constraint and plan 90 days. The entry point. |
| [`north-star-metric-tree`](north-star-metric-tree/SKILL.md) | Choose and validate a north star metric and build the metric tree of inputs, owners and counter-metrics. |
| [`growth-model`](growth-model/SKILL.md) | Build cohort-based growth models and forecasts, calibrated on history, with sensitivity analysis. |
| [`funnel-analysis`](funnel-analysis/SKILL.md) | Build and analyse funnels to find where and for whom value leaks, sized and diagnosed. |
| [`cohort-retention-analysis`](cohort-retention-analysis/SKILL.md) | Build and read cohort retention analyses for users, accounts and revenue. |
| [`acquisition-channel-testing`](acquisition-channel-testing/SKILL.md) | Find and test the next acquisition channel with scored, time-boxed tests judged on retained customers. |
| [`growth-loops`](growth-loops/SKILL.md) | Identify, design and strengthen growth loops where each user brings more. |
| [`referral-programmes`](referral-programmes/SKILL.md) | Design, launch and improve referral programmes with two-sided incentives and fraud controls. |
| [`tracking-plan`](tracking-plan/SKILL.md) | Design tracking plans and event taxonomies so analytics numbers stop disagreeing. |
| [`experiment-design`](experiment-design/SKILL.md) | Design trustworthy growth experiments: hypotheses, sample size, randomisation and guardrails. |
| [`experiment-readout`](experiment-readout/SKILL.md) | Analyse experiment results and write readouts that lead to sound ship/iterate/stop decisions. |
| [`growth-experiment-backlog`](growth-experiment-backlog/SKILL.md) | Set up and run a growth experimentation system: backlog, prioritisation, cadence and learning library. |
| [`growth-reporting`](growth-reporting/SKILL.md) | Build growth reporting around the north star with labelled attribution and a weekly review. |

## How these skills work

Agents use *progressive disclosure*: they read each skill's `name` and `description` (~100 tokens) at the start
of a session and load the full `SKILL.md` only when your request matches — so you can install many without
filling the context window.

## Author & licence

By [**Afeez Adebayo**](https://afeezadebayo.com) — Marketing, SEO & Growth (SEO & Organic Growth at Grey, YC W22).
[LinkedIn](https://www.linkedin.com/in/afeez-adebayo/) · [X](https://x.com/za_icon) · [Newsletter](https://afeezadebayo.com/newsletter/)

Released under [**CC BY 4.0**](https://creativecommons.org/licenses/by/4.0/) — use, share and adapt, including
commercially, with credit to Afeez Adebayo and a link to the source page in each file.

<sub>Keywords: growth marketing skills, SKILL.md, Agent Skills, Claude skills, Claude Code skills, Codex skills,
AI agent skills, north star metric, growth model, funnel analysis, cohort retention, growth loops, referral
programmes, A/B testing, experiment design, tracking plan, growth reporting.</sub>
