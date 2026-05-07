# 🤖 Awesome Ada Tools [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> 🌟 A curated list of **open-source AI tools that an autonomous AI ships every few days** for real small-business pain points.

Every tool here is built and published autonomously by [Ada](https://github.com/bernard7340) — a continuous AI orchestrator running 24/7 on Bernard's machine. Ada researches a vertical, identifies a manual workflow worth automating, writes the tool in Python, runs a quality gate, and pushes it to GitHub — without a human in the loop on the build itself.

**Star this list to get notified as new tools land.** *(Latest update: 2026-05-07 — 8 tools across 7 verticals, more shipping daily.)*

---

## 🧭 Contents

- [🏠 Property Management](#-property-management)
- [🏛️ Municipal & Civic](#️-municipal--civic)
- [🦷 Dental Labs](#-dental-labs)
- [🔧 HVAC Contractors](#-hvac-contractors)
- [💍 Wedding & Event Rentals](#-wedding--event-rentals)
- [🛡️ Independent Insurance](#️-independent-insurance)
- [⚱️ Funeral Homes](#️-funeral-homes)
- [💡 Why this list exists](#-why-this-list-exists)
- [🤝 Want a tool for your industry?](#-want-a-tool-for-your-industry)

---

## 🏠 Property Management

For SMB property managers (5–50 units) who refuse to pay AppFolio enterprise tax.

- **[maintenance-intake-triage](https://github.com/bernard7340/maintenance-intake-triage)** — Tenant texts about a leaking dishwasher → 30 seconds later your operator sees a classified ticket with a drafted reply. Replaces a $1,000+/mo virtual assistant. Twilio + Claude Sonnet, ~$0.006 per ticket.

- **[owner-weekly-packet-generator](https://github.com/bernard7340/owner-weekly-packet-generator)** — Every Monday at 8am, every owner gets a polished PDF report — auto-generated, AI-narrated, mailed for you. Replaces a $1,299/mo virtual assistant. Claude Haiku + Gemini Flash, ~$0.006 per property/week.

## 🏛️ Municipal & Civic

For real-estate operators, muni-bond analysts, and civic-tech folks who want signal from local government without paying $5k/mo for an alt-data terminal.

- **[meeting-watcher-mvp](https://github.com/bernard7340/meeting-watcher-mvp)** — Drop in a YouTube URL of a city council meeting → get back structured JSON of every vote, dollar amount, zoning decision, and weird moment. Plus an email-ready alert. Validated against Austin TX and Nashville TN. Gemini 2.5 Pro multimodal, $0 under Bernard's subscription.

## 🦷 Dental Labs

- **[rx-intake-triage](https://github.com/bernard7340/rx-intake-triage)** — Auto-classifies incoming dentist Rx requests by urgency and lab process type, then drafts a professional acknowledgment back to the referring dentist. Pure Python + Claude Sonnet.

## 🔧 HVAC Contractors

- **[service-call-quote-drafter](https://github.com/bernard7340/service-call-quote-drafter)** — AI-powered customer quotes from tech field notes + photos — ready in under 60 seconds. The tech finishes a service call, snaps photos, jots a few notes; the tool produces a customer-ready quote. Claude Sonnet + Gemini Pro for photo analysis.

## 💍 Wedding & Event Rentals

- **[inquiry-quote-generator](https://github.com/bernard7340/inquiry-quote-generator)** — Turns a customer's inquiry email ("how much for 150 chairs, 20 tables, and ivory linens?") into an itemized quote with availability check and pricing. Pure Python + Claude Sonnet.

## 🛡️ Independent Insurance

- **[policy-renewal-prep](https://github.com/bernard7340/policy-renewal-prep)** — 30 days before renewal, the tool reads the existing policy + 3 best alternatives in the local market, then drafts a personalized client email recommending the right move. Claude Sonnet, ~$0.01 per policy.

## ⚱️ Funeral Homes

- **[obituary-drafter](https://github.com/bernard7340/obituary-drafter)** — Family submits a brief about the deceased; the tool drafts a tasteful, publication-ready obituary in the home's house style. Two-pass (draft + refine) with Claude Sonnet.

---

## 💡 Why this list exists

The ecosystem of "AI for small business" software is ~99% glossy SaaS that's overpriced and underbuilt. Ada exists because the actual business owners — property managers, contractors, insurance agents, funeral directors — keep asking the same questions on Reddit, IndieHackers, and Hacker News:

> *"Is there a tool that does X?"*
> *"How do you all handle Y?"*
> *"I'm spending hours doing Z by hand."*

Most of those tools could be a **200-line Python script**. So Ada writes them, ships them, and lists them here. Free, MIT-licensed, run-it-on-your-laptop. No SaaS lock-in, no per-seat pricing, no telemetry.

**Every tool here is:**
- 🐍 **Pure Python** — clone, install, run
- 🔓 **MIT licensed** — fork it, ship it, sell it
- 🤖 **AI-native** — Claude Sonnet/Haiku for text, Gemini Pro for multimodal
- 💸 **Cheap** — most cost <$0.01 per run
- 👤 **Local-first** — your data stays on your machine

---

## 🤝 Want a tool for your industry?

Email **[marcosubagent@gmail.com](mailto:marcosubagent@gmail.com)** with:

1. The painful, recurring manual workflow eating your hours
2. What you currently pay (in cash or in your own time)
3. A link to your business

Bernard (the human running Ada) replies within 48 hours with either a free open-source tool already in our pipeline, or a fixed-price quote to build it.

**Or just star this repo** — the more stars it gets, the more verticals Ada researches next.

---

## 📡 How tools land here

```
[Ada researches a vertical]
        ↓
[Reflection Agent finds a worthy pain]
        ↓
[Build Agent writes Python + README]
        ↓
[Quality gate: README ≥500 chars, main.py compiles, requirements.txt valid]
        ↓
[PASS → auto-publish to bernard7340/<tool>]
        ↓
[FAIL → goes to manual approval queue, Bernard reviews]
        ↓
[Telegram ping to Bernard so he knows what shipped]
```

Want to follow along live? [Bernard's profile](https://github.com/bernard7340) shows every new tool as it lands.

---

## 📈 Tool count

```
Verticals covered : 7
Tools shipped     : 8 (5 of them auto-published by Ada in the last 24h)
Verticals queued  : 4+ (construction, pharmacy, law, more)
```

---

**License:** [CC0](LICENSE) — copy this list, fork it, mirror it, sell it. The tools themselves are MIT.

— Built by [Bernard](https://github.com/bernard7340) · Maintained by Ada · Last updated: 2026-05-07
