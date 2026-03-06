# Steve Pieper Click Test Method — Complete System Guide v1.0

> Compiled from: Pieper Click Test Method 2.0.docx, Click Testing v02.pdf, ChatGPT session transcript, gtm_lane_3.md, Rippling Roots blog, Meredith Kallaher color block test, The Creative Penn podcast interview, and Pieper's own course materials at app.stevepieper.com.

---

## What This Is

A structured, sequential ad testing system that uses **low-budget Facebook/Meta ads** to discover which creative elements (copy, headlines, images) resonate with a cold audience. You test **one variable at a time**, measure by **cost per link click (CPC)**, and build a winning ad piece by piece.

The method was designed by Steve Pieper primarily for authors selling books direct, but applies to any product, service, or offer where you need to validate messaging before spending real money.

---

## Core Principles

1. **One variable per round** — every ad is fully filled out; only the element being tested changes
2. **CPC is the only metric that matters** — not CTR, not impressions, not engagement
3. **25-30 link clicks per ad** before evaluating — don't pick winners too early
4. **Manual pause strategy** — pause each ad as it hits 25-30 clicks to prevent algorithm favoritism
5. **No dynamic creative** — you control everything manually
6. **No fake controls** — all 5 ads are real contenders
7. **Neutral image in early rounds** — boring placeholder so copy performance isn't skewed by imagery
8. **Speed and cost-efficiency** — $30/day budget, each round runs 24-36 hours

---

## The Canonical Six-Test Sequence

Pieper's full system has **six rounds**, always in this order:

| Round | What Changes | What Stays Frozen | Purpose |
|-------|-------------|-------------------|---------|
| **1 — Tagline / Motivation** | Primary Text (short tagline) | Neutral color-block image, stock headline, description, CTA | Find the hook that lights people up |
| **2 — Headline / Transformation** | Headline field | Same neutral image + winning tagline | Nail the promise or transformation statement |
| **3 — Testimonials** | One review/snippet per ad | Image, tagline, headline fixed | Inject social proof (skip if you have none) |
| **4 — Images** | Swap in real imagery | Winning copy from Rounds 1-3 | Discover the scroll-stopping visual |
| **5 — Primary Text (long body)** | Expand Primary Text (blurb/pitch) | Best image + top headline | Fine-tune long-form copy that sells |
| **6 — Stress Test** | Nothing new — combine every winner into 2-3 finished ads and race them | — | Sanity-check for false positives before scaling |

### Variations

- **No testimonials?** Skip Round 3 and run 5 tests. Circle back when you have reviews.
- **Time-crunched?** Merge Tagline + Headline into one round for a 4-test sprint.
- **Stress Test is always last.** Whether you ran 4, 5, or 6 discovery rounds.

Pieper recommends: **"Budget $30/day for six quick tests — about two weeks total."**

---

## The Simplified 4-Round Version

For non-authors or when you want the fastest path to a winning ad:

| Round | What Changes | What Stays the Same |
|-------|-------------|-------------------|
| **Round 1: Primary Text** | 5 different primary texts | Same image, headline, description, CTA |
| **Round 2: Headline** | 5 different headlines | Winning primary text, same image, description, CTA |
| **Round 3: Description / CTA** | 5 different descriptions or CTA buttons | Winning primary text, winning headline, same image |
| **Round 4: Image** | 5 different images | Winning primary text, winning headline, winning description/CTA |

---

## Step-by-Step Execution

### PREP PHASE

- [ ] Decide which variable you're testing first (start with Primary Text / Tagline)
- [ ] Write 5 strong variations of that variable (all real contenders, no fillers)
- [ ] Create a tracking doc labeled Ad 1-Ad 5 with each version pasted in
- [ ] Choose a single destination URL (Notion page, Carrd, simple landing page, hidden page on your site — anything works)
- [ ] Choose one **neutral, boring placeholder image** for the copy rounds
  - Plain product photo, simple mockup, white-background object shot
  - Deliberately uninspired — you don't want the image influencing copy test results

---

### ROUND 1: PRIMARY TEXT / TAGLINE

**Setup in Ads Manager:**

- [ ] Create a new campaign
  - Objective: **Traffic** (or "Website" in newer Meta UI — get more website visitors)
  - Name: `Click Test — Primary Text`
- [ ] Create 1 ad set
  - Audience: cold audience (ideal customer, broad if needed)
  - Placement: **Manual > Feeds only**
  - Optimization: **Link Clicks**
  - Budget: **Daily $25-50/day** OR **Lifetime $75-150**
  - Run dates: Today to 3 days from now (if Lifetime)
- [ ] Create 5 separate ads in that ad set
  - All use same: neutral image, headline, description, CTA button, destination URL
  - Each ad has a **unique Primary Text** (Ad 1-5)
  - **Dynamic Creative = OFF**
  - Name clearly: `Ad 1 — [Text Style]`, `Ad 2 — [Text Style]`, etc.
- [ ] Publish campaign

**While Running:**

- [ ] Wait 2-4 hours after launch before checking
- [ ] In Ads Manager, customize columns to show:
  - Link Clicks
  - CPC (Cost per Link Click)
  - Impressions (context only)
- [ ] Monitor ads periodically
- [ ] **As each ad hits 25-30 link clicks, pause it manually**
- [ ] Continue until all 5 ads are paused

**Evaluate:**

- [ ] Compare CPC (Cost per Link Click) across all 5 ads
- [ ] **Lowest CPC = winner**
- [ ] Label: `Winner — Primary Text Round`
- [ ] Copy winning Primary Text for next round

---

### ROUND 2: HEADLINE

**Setup:**

- [ ] Duplicate winning ad into a new ad set
- [ ] Name ad set: `Click Test — Headline`
- [ ] Write 5 different headline variations
- [ ] Keep same: **winning Primary Text**, neutral image, description, CTA, URL
- [ ] Create 5 new ads (each with a different headline)
- [ ] Name each: `Ad 1 — [Headline Style]`, etc.
- [ ] Publish

**While Running:**

- [ ] Monitor ads until each hits 25-30 Link Clicks
- [ ] Pause each ad manually as it reaches threshold
- [ ] Wait until all 5 are paused

**Evaluate:**

- [ ] Compare CPC across all 5 ads
- [ ] Lowest CPC = winner
- [ ] Label: `Winner — Headline Round`
- [ ] Copy winning Headline for next round

---

### ROUND 3: TESTIMONIALS (Optional — Skip if None Available)

**Setup:**

- [ ] Duplicate winning ad into a new ad set
- [ ] Name: `Click Test — Testimonials`
- [ ] Gather 5 testimonials, reviews, or social proof snippets
  - If you have no real testimonials, use **borrowed testimonials**:
    - `"Fans of [well-known thing] will love this."`
    - `"Over X [people] have already [done thing]."`
    - Media badges, awards, podcast appearances
  - **NOT OK:** Invented blurbs, anonymous fake quotes
- [ ] Keep same: winning Primary Text, winning Headline, neutral image, CTA, URL
- [ ] Create 5 ads (each with a different testimonial)
- [ ] Publish

**Run and evaluate same as above** — 25-30 clicks, manual pause, lowest CPC wins.

---

### ROUND 4: IMAGES

**Setup:**

- [ ] Duplicate winning ad into a new ad set
- [ ] Name: `Click Test — Image`
- [ ] Choose 5 different images to test
  - This is where you bring in real imagery, cover art, product shots, lifestyle photos
- [ ] Keep same: **winning Primary Text, Headline, Testimonial (if tested), Description, CTA, URL**
- [ ] Create 5 ads (each with a different image)
- [ ] Publish

**Run and evaluate same as above.**

---

### ROUND 5: PRIMARY TEXT — LONG BODY (Full 6-Round Version)

- [ ] Duplicate winning ad into a new ad set
- [ ] Name: `Click Test — Long Copy`
- [ ] Write 5 different expanded primary text versions (blurb, pitch, story)
- [ ] Keep same: winning image, headline, description, CTA, URL
- [ ] Create 5 ads, publish, run, evaluate same as above

---

### ROUND 6: STRESS TEST (Always Last)

- [ ] Create 2-3 "finished" ads combining every winner from all rounds
- [ ] Run them against each other at same budget
- [ ] This is your **final sanity check** before scaling spend
- [ ] The winner here is your **production ad** for lead gen, conversions, or scaling

---

## Final Deployment

- [ ] Build final ad with the **full winning combination**:
  - Primary Text (winner)
  - Headline (winner)
  - Testimonial (winner, if tested)
  - Description/CTA (winner)
  - Image (winner)
- [ ] Label: `Full Winner Combo — Control`
- [ ] Deploy for conversion campaigns, lead gen, or scaling

---

## Key Metrics Reference

| Metric | Use It? | Why |
|--------|---------|-----|
| **Link Clicks** | YES | Confirms actual destination clicks |
| **CPC (Cost per Link Click)** | YES | **This is the winner-picking metric** |
| CTR (Click Through Rate) | NO | Can be misleading — doesn't reflect cost |
| Impressions / Reach | NO | Context only, not for decisions |

---

## Budget Reference

| Approach | Amount | Notes |
|----------|--------|-------|
| **Daily Budget** | $25-50/day per round | More control, you manually pause |
| **Lifetime Budget** | $75-150 per round | More set-and-forget |
| **Full 6-round system** | ~$30/day x 14 days = ~$420 total | Pieper's recommendation |
| **4-round sprint** | ~$100-300 total | Faster, cheaper validation |

---

## Success Thresholds (from Pieper + Practitioners)

| Metric | Good | Great |
|--------|------|-------|
| CPC (Link Click) | Under $1.00 | Under $0.50 |
| Minimum clicks before judging | 25 per ad | 30 per ad |
| Minimum impressions (alt method) | 400 per ad | — |
| CTR (if checking) | Above 1% | Above 2% |

---

## Critical Rules

1. **DO NOT use Dynamic Creative** — you must control each variable manually
2. **DO NOT judge early** — some ads look great in the first $5 then tank; wait for 25-30 clicks
3. **DO NOT leave ad slots blank** — every ad is fully filled out, only one element changes
4. **DO NOT bake taglines into images** — taglines live in the Primary Text field, not artwork
5. **DO NOT use Facebook Lead Forms for click testing** — Lead forms optimize for form fillers, not curious clickers; this breaks the method's intent of testing curiosity/message resonance
6. **DO NOT use separate ad sets per ad** — that spreads budget too thin; all 5 ads go in 1 ad set
7. **DO pause each ad manually at 25-30 clicks** — prevents algorithm from starving lower performers

---

## Color Block Test Variant (Meredith Kallaher / Frankie Jo Allen Adaptation)

A related but distinct approach where you test **pain points** using minimal color-block graphics:

| Setting | Value |
|---------|-------|
| Campaign type | Traffic |
| Budget | $30-40/day, campaign budget disabled |
| Audience | Cold interest matching ideal customer (4-5M size) |
| Placements | Advantage Placements |
| Optimization | Link Clicks |
| Creative | Color block squares with pain point text (made in Canva) |
| Primary Text | Leave blank |
| Headline | Job title descriptor |
| Description | Spacebar twice (prevent auto-fill) |
| CTA | "Learn More" |

**Success criteria:** 4+ link clicks within first 400 impressions, CPC under $0.50, CTR over 1%.

**Automation rule:** Disable ads receiving fewer than 400 impressions.

This is a **pain point discovery** tool — useful before you even start Pieper's 6-round system. It tells you which emotional hooks resonate, then you feed those hooks into Round 1 as your tagline candidates.

---

## Applying This to DesignTransform / BonFX

### For Our Own Messaging Validation

1. **Round 1 candidates** (taglines to click test):
   - "Backlog Destruction for Agencies"
   - "AI-Powered Design & Dev Ops"
   - "Your Agency's Secret Weapon"
   - "Stop Hiring. Start Shipping."
   - "The Design Team You Don't Have to Manage"
2. **Audience:** Agency owners, creative directors, small shops (2-10 people)
3. **Destination URL:** Landing page at dbonneville-playground.vercel.app (or a simplified variant)
4. **Budget:** $30/day x 2 weeks = ~$420 to validate all messaging before building final campaigns

### As a Service for Clients

- Offer **pre-campaign messaging validation** using this exact system
- Run click tests before building full funnels — saves client money, proves messaging
- Combine with Kallaway Framework (Money/Time/Status/Fear angles) to generate tagline candidates
- Automate with social-cli from meta-ads-kit for campaign creation, insights pulling, and reporting

---

## Source Files on Disk

| File | Location |
|------|----------|
| Click Testing - Steve Pieper Click Test v02.pdf (77 pages) | `Dropbox/__eccentric/click test/test 01/` |
| Pieper Click Test Method 2.0.docx (ChatGPT session transcript) | `Dropbox/__eccentric/click test/test 01/` |
| gtm_lane_3.md (tagline click test plan) | `Dropbox/_ai/bonneville_ai/` |
| gtm_todo.md (GTM task list with Lane 3) | `Dropbox/_ai/bonneville_ai/` |
| 40+ ad variant PNGs (test 01, test 02, coaching 01) | `Dropbox/__eccentric/click test/` |

## Web References

| Source | URL |
|--------|-----|
| Steve Pieper course materials | app.stevepieper.com |
| The Creative Penn — Click Testing with Steve Pieper | https://www.thecreativepenn.com/2024/06/10/click-testing-ideas-and-selling-direct-with-steve-pieper/ |
| The Creative Penn — Selling Direct with Steve Pieper | https://www.thecreativepenn.com/2023/01/30/the-empowerment-of-selling-books-direct-to-your-readers-with-steve-pieper/ |
| Rippling Roots — How to Use Click Testing | https://www.ripplingroots.com/blog/facebook-click-testing |
| Meredith Kallaher — Color Block Test | https://meredithkallaher.com/blog/test-to-find-winning-copy/ |
| Reddit r/selfpublish — Click Testing | https://www.reddit.com/r/selfpublish/comments/19ai3o2/click_testing/ |
| Six Figure Author Experiment — Episode 12 | sixfigureauthorexperiment.com |
| Online Success Genie — Pieper AMMO Review | https://onlinesuccessgenie.com/steve-pieper-ammo-review/ |
