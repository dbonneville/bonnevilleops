# Automate Meta Ads — Research & Planning

> Source: `themattberman/meta-ads-kit` repo + Steve Pieper Click Test methodology

---

## meta-ads-kit Overview

**Repo:** `themattberman/meta-ads-kit`
**Author:** Matt Berman — founder of Emerald Digital, former marketer behind Fireball Whisky, Heineken, Hennessy
**License:** MIT | **Cost:** $0/month

An **open-source AI ad manager** that replaces daily Ads Manager clicking with a 2-minute AI-generated briefing. Closed-loop system:

```
Monitor → Detect Fatigue → Shift Budget → Generate Copy → Upload to Meta → Repeat
```

---

## The "5 Daily Questions" Framework

| # | Question | Data Source |
|---|----------|------------|
| 1 | **Am I on track?** | Today's spend vs. daily pacing |
| 2 | **What's running?** | Active campaigns list |
| 3 | **How's performance?** | 7-day campaign-level metrics |
| 4 | **Who's winning/losing?** | Ad-level performance by spend and CTR |
| 5 | **Any fatigue?** | Day-over-day CTR, frequency, CPC trends |

---

## social-cli (The Engine)

**Package:** `@vishalgojha/social-cli` | **Repo:** `vishalgojha/social-CLI`

A self-hosted execution engine wrapping Meta Marketing API, Graph API, Instagram API, and WhatsApp API into a single CLI.

### Key Commands

| Command | Purpose |
|---------|---------|
| `social auth login` | Authenticate via browser OAuth |
| `social auth set-app` | Set Meta developer app credentials |
| `social marketing accounts` | List ad accounts |
| `social marketing set-default-account` | Set default account |
| `social marketing status` | Account-level spend status |
| `social marketing campaigns` | List campaigns (filterable by status) |
| `social marketing insights` | Pull performance data at any level |
| `social marketing pause ad <ID>` | Pause an ad |
| `social marketing resume ad <ID>` | Resume an ad |
| `social marketing set-budget adset <ID>` | Adjust budget (in cents) |
| `social doctor` | Run diagnostics |

### Insights Command

The workhorse. Supports:
- **Level:** `account`, `campaign`, `adset`, `ad`
- **Presets:** `today`, `yesterday`, `last_7d`, `last_30d`, `last_90d`
- **Fields:** `ad_name`, `spend`, `impressions`, `clicks`, `ctr`, `cpc`, `actions`, `cost_per_action_type`, `frequency`
- **Breakdowns:** `age`, `gender`, custom combos
- **Time increment:** `1` (daily granularity for fatigue analysis)
- **Output:** `--json` or `--table`

---

## Benchmark-Driven Analysis

Everything compared against configurable thresholds in `ad-config.json`:

| Metric | Default Threshold |
|--------|-------------------|
| Bleeder CTR | < 1.0% |
| Max Frequency | > 3.5 |
| Fatigue CTR Drop | > 20% over 3 days |
| Spend Pace Alert | +/- 15% of daily budget |
| Target CPA | $25.00 |
| Target ROAS | 3.0x |
| Max CPC | $2.50 |

---

## Budget Optimization

Uses **CTR/CPC efficiency ratio** to rank campaigns, divides into thirds:
- **Top:** Increase budget
- **Middle:** Hold
- **Bottom:** Decrease budget

Recommendations always presented with data justification, require approval.

---

## Ad Copy Generation — Kallaway Framework

### Four Horsemen of Ad Copy

| Horseman | Trigger | Example Opening |
|----------|---------|-----------------|
| **Money** | Revenue loss, ROI, cost | "Every [thing] you miss is worth $X." |
| **Time** | Wasted hours, efficiency | "Your [person] isn't a [wrong role]." |
| **Status** | Peer comparison | "X+ [peers] already [did thing]." |
| **Fear** | Loss aversion | "The [competitor] down the street already has this." |

**Rules:**
- Copy reinforces the image, never repeats it
- Each variant hits a different psychological lever
- Headlines: 25–40 chars, never >50 (mobile truncation)
- Body: 50–120 words, 2–3 paragraphs
- Numbers required in every variant (specificity = credibility)
- No em dashes, no generic SaaS buzzwords, no emojis in B2B
- Output in Meta's `asset_feed_spec` format

---

## Safety Model

- **Read-only by default** — all reporting runs without approval
- **Actions require explicit approval** — pause, resume, budget changes
- **Audit trail** — every action logged with timestamp, what, why, who approved
- **Ads created as PAUSED** — never auto-activated

---

## Skills Architecture

Each skill is self-contained: `SKILL.md` (instructions) + `scripts/` (bash) + brand memory

| Skill | Purpose |
|-------|---------|
| `meta-ads` | Morning briefings, bleeder/winner detection |
| `ad-creative-monitor` | Creative fatigue detection (CTR decline, frequency rise) |
| `budget-optimizer` | CTR/CPC efficiency ranking, budget shift recommendations |
| `ad-copy-generator` | Kallaway Framework copy matched to image creatives |
| `ad-upload` | Validate → upload image → create creative → create ad (PAUSED) |
| `pixel-capi` | Pixel audit, CAPI setup, EMQ optimization, platform-specific guides |

---

## Tech Stack

| Layer | Technology |
|-------|-----------|
| Agent Framework | OpenClaw (open-source) |
| Meta API Interface | social-cli |
| Scripting | Bash + `jq` |
| API | Meta Marketing API (Graph API v19.0/v22.0) |
| Config | JSON + `.env` |
| Agent Personality | Markdown (`SOUL.md`, `AGENTS.md`) |
| Runtime | Node.js |

---

## Brand Memory System

```
workspace/brand/
├── stack.md          # Account IDs, targets
├── voice-profile.md  # Brand voice for copy
├── learnings.md      # Append-only: what worked/failed
├── audience.md       # ICP definitions
└── creative-kit.md   # Brand creative guidelines
```

Agent reads these on every invocation. `learnings.md` accumulates over time → smarter recommendations.

---

## Full Upload Chain

```
Validate copy + image → Upload image (get hash) → Create creative (asset_feed_spec) → Create ad (PAUSED)
```

Supports batch uploads, dry-run mode, copy refresh on existing ads (preserving metric history).

---

## Pixel + CAPI Audit

- Audit existing pixels with EMQ scoring
- Setup guides for 7 platforms (Next.js, Shopify, WordPress, Webflow, GoHighLevel, ClickFunnels, custom)
- Test CAPI with test events
- EMQ targets: 9.3+ on Purchase, 8.0+ on Lead
- Deduplication enforcement (shared event_id between browser pixel + server CAPI)

---

---

# Steve Pieper Click Test Methodology

## What It Is

Minimal-creative Meta ads used to **test messaging before committing to full campaigns or landing pages**. CTR is the direct signal for which language resonates with the target audience.

## How It Works

1. **Create simple ads** — text on solid color backgrounds (no imagery, no design)
2. **One tagline per ad variant** — isolates the message as the only variable
3. **Run as Meta traffic campaign** — optimize for link clicks
4. **Measure CTR** — the click-through rate tells you which message pulls
5. **Use winning language** — refine landing page, full campaigns, and offers based on what won

## Key Principles

- **Cheap and fast** — minimal creative means minimal production cost
- **Message-first** — strip away design to test pure messaging
- **Data over gut** — let the audience tell you what resonates
- **Pre-validation** — test before building the full funnel

## Files on Disk

| File | Location | Status |
|------|----------|--------|
| **Click Testing - Steve Pieper Click Test v02.pdf** | `Dropbox/__eccentric/click test/test 01/` | Smart-sync placeholder (needs download) |
| **Pieper Click Test Method 2.0.docx** | `Dropbox/__eccentric/click test/test 01/` | Smart-sync placeholder (needs download) |
| **gtm_lane_3.md** (readable description) | `Dropbox/_ai/bonneville_ai/` | Available |
| **gtm_todo.md** (task list) | `Dropbox/_ai/bonneville_ai/` | Available |
| **40+ ad variant PNGs** | `Dropbox/__eccentric/click test/test 01/` | Smart-sync placeholders |
| **Test 02 variants** | `Dropbox/__eccentric/click test/test 02/` | Smart-sync placeholders |
| **Coaching ad variants** | `Dropbox/__eccentric/click test/coaching 01/` | Smart-sync placeholders |
| **Click test layout** | `Dropbox/__meta ads/` | Smart-sync placeholder |

## Bookmarked References

| Source | URL |
|--------|-----|
| The Creative Penn — Click Testing with Steve Pieper | https://www.thecreativepenn.com/2024/06/10/click-testing-ideas-and-selling-direct-with-steve-pieper/ |
| The Creative Penn — Selling Direct with Steve Pieper | https://www.thecreativepenn.com/2023/01/30/the-empowerment-of-selling-books-direct-to-your-readers-with-steve-pieper/ |
| Rippling Roots — How to Use Click Testing | https://www.ripplingroots.net/blog/facebook-click-testing |
| Reddit r/selfpublish — Click Testing | https://www.reddit.com/r/selfpublish/comments/19ai3o2/click_testing/ |
| Meredith Kallaher — Color Block Test | https://meredithkallaher.com/blog/test-to-find-winning-copy/ |

---

## How This Applies to DesignTransform / BonFX

### For Our Own Marketing
1. **Click test our taglines** before committing to landing page copy
2. Test variants like:
   - "Backlog Destruction for Agencies"
   - "AI-Powered Design & Dev Ops"
   - "Your Agency's Secret Weapon"
   - "Stop Hiring. Start Shipping."
3. Use winning language across site, ads, and proposals

### As a Service for Clients
1. Offer **messaging validation** as part of onboarding
2. Before building a client's campaign, click test their key messages
3. Combine with Kallaway Framework — test each "horseman" angle
4. Use social-cli to automate the entire click test workflow:
   - Create campaign → create ad variants → run → pull insights → report winner

### Automation Pipeline (Future)

```
Define taglines → Generate color-block creatives → Upload via social-cli →
Run 3-5 days → Pull CTR data → Rank winners → Feed into copy generator
```
