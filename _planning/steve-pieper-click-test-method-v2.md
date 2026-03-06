# Steve Pieper Click Test Method — Working Manual v2.0

> Compiled from: Pieper Click Test Method 2.0.docx (ChatGPT session), Click Testing v02.pdf (77pp), gtm_lane_3.md, 5 podcast interviews, app.stevepieper.com course pages, Mint CRO methodology, 6 third-party reviews, 4 practitioner adaptations, Meredith Kallaher color block test, Rippling Roots blog, and The Creative Penn transcripts.

---

## Table of Contents

1. [What This Is](#1-what-this-is)
2. [Foundational Philosophy](#2-foundational-philosophy)
3. [The Six Click Tests — Overview](#3-the-six-click-tests--overview)
4. [Campaign Settings & Technical Setup](#4-campaign-settings--technical-setup)
5. [Automation Rules](#5-automation-rules)
6. [Audience Targeting](#6-audience-targeting)
7. [Creative Specifications](#7-creative-specifications)
8. [Test 1: Taglines / Motivations](#8-test-1-taglines--motivations)
9. [Test 2: Headlines / Transformations](#9-test-2-headlines--transformations)
10. [Test 3: Testimonials](#10-test-3-testimonials)
11. [Test 4: Images](#11-test-4-images)
12. [Test 5: Primary Ad Text (Long Body)](#12-test-5-primary-ad-text-long-body)
13. [Test 6: Stress Test](#13-test-6-stress-test)
14. [Step-by-Step Execution Checklist](#14-step-by-step-execution-checklist)
15. [Metrics, Thresholds & What "Winning" Looks Like](#15-metrics-thresholds--what-winning-looks-like)
16. [Budget Breakdown](#16-budget-breakdown)
17. [Timing & Duration](#17-timing--duration)
18. [Interpreting Results & Ambiguous Data](#18-interpreting-results--ambiguous-data)
19. [Common Mistakes](#19-common-mistakes)
20. [After Click Testing: Scaling & Conversion](#20-after-click-testing-scaling--conversion)
21. [Adapting for DesignTransform / BonFX](#21-adapting-for-designtransform--bonfx)
22. [Color Block Test Variant (Kallaher / Allen)](#22-color-block-test-variant)
23. [Tools & Tech Stack](#23-tools--tech-stack)
24. [Key Statistics & Claims](#24-key-statistics--claims)
25. [Source Files & References](#25-source-files--references)
26. [Appendix: What's Behind the Paywall](#26-appendix-whats-behind-the-paywall)
27. [Appendix: Source Conflicts & Resolutions](#27-appendix-source-conflicts--resolutions)

---

## 1. What This Is

A structured, sequential ad testing system that uses **low-budget Meta (Facebook/Instagram) ads** to discover which creative elements — copy, headlines, testimonials, images — resonate with a cold audience. You test **one variable at a time**, measure by **cost per link click (CPC)** and supporting metrics, and build a winning ad piece by piece.

Designed by **Steve Pieper** (USA Today bestselling author under pen name Lars Emmerich, retired fighter pilot, two-time Distinguished Flying Cross recipient). The methodology originates from **Mint CRO** (Jessica Jobes & Chris Sanchez), which Steve adapted for the author market starting in 2019.

The method works for any product, service, or offer where you need to validate messaging before committing real budget.

---

## 2. Foundational Philosophy

### "You Are Not Your Market"

Steve's central insight: **authors and entrepreneurs systematically misjudge what their audience wants**. He claims 90% get it wrong due to "the curse of knowledge." When he tested 15 tagline variants for his own books, his personal favorite — the one he was certain would win — placed around 8th.

> Only about **5% of tested ideas** perform well enough to move forward profitably — roughly 1 idea out of 20. This from data across 800+ authors, 6,000+ tests, and 50,000+ individual testing elements.

### The Engineering Approach (from Mint CRO)

The methodology rejects **"spaghetti testing"** — throwing various content combinations against the wall to see what sticks. A single Facebook ad contains approximately **6 variables** (primary text, image, headline, description, CTA button, targeting). Testing all simultaneously makes it impossible to identify which element drives performance.

**The solution:** Break ads into individual components, test each element in isolation, then combine all winning elements into one optimized ad. This is the opposite of Facebook's Dynamic Creative Optimization, which Mint CRO argues wastes budget testing random untested combinations.

### Click Testing = Testing Curiosity, Not Commitment

Click testing measures **curiosity** — "Which combination of creative elements gets people intrigued enough to click?" It does not test conversion behavior, purchase intent, or form completion. The metric is the click itself: did this message make you want to know more?

The results are useful **everywhere you interact with customers** — email subject lines, sales pages, product listings, social media posts, proposals, and all advertising copy.

---

## 3. The Six Click Tests — Overview

The testing system has **six sequential tests**, each building on the previous round's winner. The system has two tracks based on content type:

| Test # | Storytellers (Fiction/Narrative) | Problem Solvers (Nonfiction/Services) |
|--------|--------------------------------|--------------------------------------|
| **1** | Book/series taglines | Market's strongest motivators / pain points |
| **2** | Ad headlines | Most compelling transformation statements (desired outcomes) |
| **3** | Standalone testimonials | Standalone testimonials |
| **4** | Images | Images |
| **5** | Primary ad text (long body copy) | Primary ad text (long body copy) |
| **6** | Stress test (combined winners) | Stress test (combined winners) |

### Variations

- **No testimonials?** Skip Test 3. Run 5 tests. Circle back when you have reviews.
- **Time-crunched?** Merge Tagline + Headline into one round for a 4-test sprint.
- **Stress Test is always last.** Whether you ran 4, 5, or 6 discovery rounds.
- The 6-round sequence is a **loop** — you can re-enter at any round once new creative becomes available.

Pieper recommends: **"Budget $30/day for six quick tests — about two weeks total."**

### The Simplified 4-Round Version

For non-authors or when you want the fastest path:

| Round | What Changes | What Stays the Same |
|-------|-------------|-------------------|
| **1: Primary Text** | 5 different primary texts | Same image, headline, description, CTA |
| **2: Headline** | 5 different headlines | Winning primary text, same image, description, CTA |
| **3: Description / CTA** | 5 different descriptions or CTAs | Winning text + headline, same image |
| **4: Image** | 5 different images | Winning text + headline + description/CTA |

---

## 4. Campaign Settings & Technical Setup

### Campaign Level

| Setting | Value | Notes |
|---------|-------|-------|
| **Campaign Objective** | Traffic | Select "Traffic" or "Website" depending on your Meta UI version. The goal is website visitors, NOT lead forms. |
| **Performance Goal** | Link Clicks | **NOT Landing Page Views** — landing page views cost 2-4x more and aren't needed for click testing |
| **Campaign Budget Optimization (CBO)** | **OFF** | Turning CBO off gives you control over budget per ad set. Prevents Facebook from allocating unevenly. |

### Ad Set Level

| Setting | Value | Notes |
|---------|-------|-------|
| **Daily Budget** | $30-40 per ad set | Actual spend will typically be less (~$20-30) |
| **Placements** | See conflict note below | |
| **Optimization** | Link Clicks | |
| **Audience** | Cold interest-based | See Audience Targeting section |
| **Advantage+ Audience** | **Override it** | Hover over "Advantage+" until pencil icon appears; access manual settings |

> **CONFLICT: Placements** — Pieper's ChatGPT-sourced method says "Manual > Feeds only." Mint CRO methodology says "Advantage+ Placements" (automatic). **Recommendation:** Start with Feeds only for cleaner data. Switch to Advantage+ if you're not getting enough impressions within 24 hours.

### Ad Set Structure

> **CONFLICT: This is the most important structural decision.**
>
> **Approach A (Mint CRO / Official Pieper):** Create **one ad set per variation**, each containing one ad. Each variation gets its own independent budget ($30-40/day). This prevents Facebook from favoring one ad over others.
>
> **Approach B (Practitioner Adaptation):** Create **one ad set with all 5 ads inside it**. Use a single budget ($25-50/day). Manually pause each ad as it hits 25-30 clicks to enforce fair distribution.
>
> **Recommendation:** Approach A is more rigorous and closer to the official method. Approach B is cheaper (one budget instead of five) but requires active monitoring and manual intervention. Use Approach A if budget allows; use Approach B for lean testing.

### Ad Level

| Setting | Value |
|---------|-------|
| **Ad Format** | Single Image |
| **Primary Text** | Leave blank in Test 1; varies by test in later rounds |
| **Headline** | Varies by test |
| **Description** | **Leave empty** or type two spaces to prevent Facebook auto-fill |
| **Call-to-Action** | "Learn More" |
| **Destination** | Your website / landing page / simple URL |
| **Creative Type** | Standard — **do NOT use Dynamic Creative Optimization** |

---

## 5. Automation Rules

### The 400-Impression Auto-Off Rule (Mint CRO Method)

This is the official Pieper/Mint CRO approach to standardizing data collection:

1. Navigate to Ads Manager home
2. Select your campaign
3. Click the **"Rule"** dropdown
4. Select **"Create a New Rule"**
5. Configure:
   - **Apply to:** "Active Ads in 1 Campaign"
   - **Action:** "Turn Ads Off"
   - **Condition:** Impressions **greater than** 400
   - **Schedule:** "Continuously"

This automation:
- Prevents overspending on any single variation
- Ensures each ad gets approximately equal exposure
- Standardizes the data collection window
- Allows direct apples-to-apples comparison

### The Manual Pause Method (Practitioner Adaptation)

If using Approach B (all ads in one ad set):

- Monitor ads periodically
- As each ad hits **25-30 link clicks**, pause it manually
- Continue until all ads are paused
- Then compare CPC across all variations

This method is more hands-on but works when you can't run separate ad sets per variation.

### Which Method to Use

| Method | When to Use |
|--------|------------|
| **400-impression rule** | Approach A (one ad set per variation). Set it and forget it. |
| **Manual pause at 25-30 clicks** | Approach B (one ad set, multiple ads). Requires active monitoring. |

---

## 6. Audience Targeting

### Setup

Override Advantage+ audience settings by hovering over "Advantage+" until pencil icon appears, then configure manually:

| Parameter | Recommendation |
|-----------|---------------|
| **Country** | Select target country (US, UK, CA, AU for English-language) |
| **Gender** | Based on your audience (or both) |
| **Age Range** | Based on your audience demographics |
| **Interests** | Specific interests related to your industry, comp brands, or customer behaviors |
| **Household Income** | Top 25-50% of ZIP codes (US targeting) — if relevant |
| **Audience Size** | **300,000 - 5,000,000 people** |

### Key Principles

- Use a **cold interest-based audience** — people who have never heard of you
- This is NOT retargeting — you're testing on fresh eyes
- Large enough to prevent ad fatigue, targeted enough to represent actual customers
- The audience stays the **same across all 6 test rounds** (consistency = comparable data)

---

## 7. Creative Specifications

### Image Specifications

| Spec | Value |
|------|-------|
| **Format** | Square (1080 x 1080 pixels) |
| **Tool** | Canva (free tier works) |
| **Tests 1-2** | Color block background with text only |
| **Tests 4+** | Real images with imposed winning headlines |

### Color Block Design (Tests 1-2)

- Solid color background
- Bold, clear text — one tagline or pain point per image
- Acts as **"pattern interruption"** on the feed — stops the scroll
- Purpose: remove the image variable so you test ONLY the words
- Make it easier for the audience to match the statement with their own experience

### Image Progression Through All Rounds

- **Tests 1-3:** The winning color block image from Test 1 carries forward as the locked image
- **Test 4:** Color block is retired — you test real images (product shots, lifestyle, founder photos)
- **Tests 5-6:** The winning real image from Test 4 carries forward

### Text Guidelines

- **Primary Text:** Keep straightforward; measure interest, don't sell
- **Headline:** Simple; can use brand tagline or test-specific headline
- **Description:** Leave empty or add two spaces to prevent Facebook auto-fill
- **CTA Button:** "Learn More"
- Use **"bold, clear statements that reflect your audience's internal monologue"**
- Do NOT try to sell in the test ad — you're measuring curiosity, not converting

---

## 8. Test 1: Taglines / Motivations

### For Storytellers (Fiction/Narrative)

**Objective:** Find the most engaging tagline that captures attention and entices the audience to learn more.

**What to test:** Taglines — one or two sentences that hook the reader. Different ways of describing the appeal, premise, emotional hook, or unique angle.

### For Problem Solvers (Nonfiction/Services)

**Objective:** Find the market's strongest motivators — the pain points that most compel your audience to act.

**What to test:** Language describing customer pain points, formatted as statements your audience would identify with.

**Format examples:**
- "I don't think people understand what I do"
- "My content feels boring"
- Statements with "..." trailing off
- True/false style statements

### How Many Variations

- Mint CRO recommends **6-10** variations
- Practitioners suggest **3-5 minimum**
- The ChatGPT method uses **5** as the standard per round

### How to Brainstorm

- Write down every possible angle your product/book/service could be pitched from
- Use ChatGPT/Claude to generate variants when stuck (Steve explicitly recommends AI assistance)
- Research Facebook groups, Reddit, social media comments for language your audience actually uses
- Remember: you are generating **multiple accurate descriptions** of the same thing, each emphasizing a different aspect

### Creative Format

Use **color block images** created in Canva:
- Square format (1080x1080)
- Solid color background
- One tagline/pain point statement per image
- Bold, clear text
- The color block removes the image variable so you test ONLY the words

### Ad Slot Configuration for Test 1

| Slot | Content |
|------|---------|
| **Image** | Color block with tagline text baked in |
| **Primary Text** | Leave blank, or brief "Which resonates?" type prompt |
| **Headline** | Generic/neutral (same across all) |
| **Description** | Empty (or two spaces) |
| **CTA** | "Learn More" |
| **URL** | Same destination for all |

---

## 9. Test 2: Headlines / Transformations

### For Storytellers

**What to test:** Different headline approaches — shorter, punchier versions. What makes someone click after they've been stopped by the tagline?

### For Problem Solvers

**What to test:** Transformation statements — language describing the desired outcome after engaging with your offering. If Test 1 was about pain, Test 2 is about the promise.

### How to Execute

- **Fixed elements:** Winning color block image from Test 1 (carries forward as the locked image), Primary Text stays blank
- **Variable:** Only the headline field
- Create 5-10 headline variations
- Examples of headline approaches: downloadable resource offers, video tutorials, solution-focused copy, curiosity hooks, outcome promises

### Ad Slot Configuration for Test 2

| Slot | Content |
|------|---------|
| **Image** | Winning color block image from Test 1 (locked in) |
| **Primary Text** | Leave blank (same as Test 1) |
| **Headline** | **Different in each ad — this is what you're testing** |
| **Description** | Empty (or two spaces) |
| **CTA** | "Learn More" |
| **URL** | Same destination for all |

---

## 10. Test 3: Testimonials

**Objective:** Find the most compelling "standalone testimonials" — reviews or endorsements strong enough to work as complete ad elements on their own.

### What to Test

- Individual customer reviews
- Expert endorsements
- Critic quotes
- Industry-specific fan testimonials
- Results-based testimonials ("I did X and got Y")

### If You Have No Testimonials

**Option 1:** Skip this round entirely. Run 5 tests instead of 6. Come back when you have reviews.

**Option 2:** Use **borrowed testimonials** — temporary stand-in social proof:

| Acceptable | Example |
|------------|---------|
| Comparison to known brand | "Fans of [well-known thing] will love this." |
| Public stats | "Over X [people] have already [done thing]." |
| Awards / media badges | "Finalist — [Award Name]" |
| Podcast/media appearances | "As featured on [Publication]" |

**NOT acceptable:** Invented blurbs, anonymous fake quotes, lifting lines from others without permission.

### Ad Slot Configuration for Test 3

| Slot | Content |
|------|---------|
| **Image** | **Winning color block image from Test 1 (still locked in)** |
| **Primary Text** | **Different testimonial in each ad — this is what you're testing** |
| **Headline** | Winning headline from Test 2 |
| **Description** | Empty |
| **CTA** | "Learn More" |
| **URL** | Same destination for all |

---

## 11. Test 4: Images

**Objective:** Find the scroll-stopping visual that makes people pause and engage.

### What to Test

- Product photos / book cover art variations
- Author/founder photos (Steve found these perform surprisingly well despite initial skepticism)
- Lifestyle images showing customers in relevant contexts
- Behind-the-scenes imagery
- Images with winning headlines imposed on them

### Key Finding

> Ad images drive **75-90% of ad performance**. Author/founder photos "deepen the connection" and leverage the human brain's face-recognition capability.

### How to Execute

- **Fixed elements:** Winning tagline, headline, and testimonial from Tests 1-3
- **Variable:** Only the image
- Test 5 different image approaches minimum
- Use Canva to put images in square format, optionally with winning headlines imposed

### Ad Slot Configuration for Test 4

| Slot | Content |
|------|---------|
| **Image** | **Different in each ad — this is what you're testing** (color block is now retired; use real images) |
| **Primary Text** | Winning testimonial from Test 3 (or blank if skipped) |
| **Headline** | Winning headline from Test 2 |
| **Description** | Empty |
| **CTA** | "Learn More" |
| **URL** | Same destination for all |

---

## 12. Test 5: Primary Ad Text (Long Body)

**Objective:** Find the best way to use the primary text field — the main body copy above the image — to get people excited and motivate action.

### What to Test

- Different lengths (short punchy vs. long narrative)
- Different tones (informative vs. emotional vs. conversational)
- Different opening hooks
- Different calls to action within the copy
- 3-5 versions

### Ad Slot Configuration for Test 5

| Slot | Content |
|------|---------|
| **Image** | Winning image from Test 4 |
| **Primary Text** | **Different long-form copy in each ad — this is what you're testing** |
| **Headline** | Winning headline from Test 2 |
| **Description** | Winning description (or empty) |
| **CTA** | "Learn More" |
| **URL** | Same destination for all |

### Repurposing Losers

Losing tagline/text variations from earlier rounds can be **repurposed as primary text body copy** even if they didn't win their original round. They may work better in a different context.

---

## 13. Test 6: Stress Test

**Objective:** Final sanity check. Confirm that combined winning elements actually produce a high-converting ad as a complete unit. This weeds out **false positives** — elements that tested well individually but don't work together.

### How to Execute

- Combine best-performing elements from all previous tests into **2-3 comprehensive "finished" ads**
- Each assembled ad uses a slightly different combination or arrangement of winners
- Run these against each other at the same budget
- Validate that the assembled ad performs as a complete unit

### What Success Looks Like

- At least one ad meets all performance thresholds (see Metrics section)
- This winning ad becomes your **"battle-tested" creative** for scaling
- If the stress test fails: go back and re-test specific elements

---

## 14. Step-by-Step Execution Checklist

### PREP PHASE — Before You Open Ads Manager

- [ ] Decide which variable you're testing first (start with Taglines via color block images)
- [ ] Write 5-10 strong variations of that variable (all real contenders, no fillers)
- [ ] Create a tracking doc labeled Ad 1 through Ad 5+ with each version pasted in
- [ ] Choose a single destination URL (Notion page, Carrd, simple landing page, hidden page on your site)
- [ ] Create color block images in Canva (1080x1080, solid color, bold text) for Test 1

---

### TEST 1: TAGLINE / PRIMARY TEXT

**Setup in Ads Manager:**

- [ ] Create a new campaign
  - Objective: **Traffic** (or Website)
  - Name: `Click Test — Tagline`
  - Campaign Budget Optimization: **OFF**
- [ ] Create ad set(s):
  - **Approach A:** One ad set per variation ($30-40/day each)
  - **Approach B:** One ad set with all variations ($25-50/day total)
  - Audience: cold interest-based
  - Placement: Feeds only (or Advantage+)
  - Optimization: Link Clicks
- [ ] Create 5-10 separate ads
  - Each uses a different color block image with tagline text baked in
  - All other slots identical (or blank per the color block method)
  - Dynamic Creative = **OFF**
  - Name clearly: `Ad 1 — [Tagline Style]`, etc.
- [ ] Set automation rule: Turn off ads at 400 impressions (if using Approach A)
- [ ] Publish campaign

**While Running:**

- [ ] Wait 2-4 hours after launch before checking
- [ ] Customize columns in Ads Manager:
  - Link Clicks
  - CPC (Cost per Link Click)
  - CTR (All)
  - Impressions
- [ ] If Approach A: Let automation rule handle pausing at 400 impressions
- [ ] If Approach B: Manually pause each ad as it hits 25-30 link clicks

**Evaluate:**

- [ ] Compare across all ads using the **three-threshold test:**
  - 4+ link clicks within first 400 impressions
  - CPC under $0.50
  - CTR above 1%
- [ ] **Lowest CPC among qualifiers = winner**
- [ ] Label: `Winner — Tagline Round`
- [ ] Top 2-3 performers are worth noting for future use
- [ ] Copy winning tagline for next round

---

### TEST 2: HEADLINE

- [ ] Duplicate winning ad into new ad set(s)
- [ ] Name: `Click Test — Headline`
- [ ] Write 5-10 different headline variations
- [ ] Keep same: winning color block image from Test 1, Primary Text blank, description, CTA, URL
- [ ] Create ads, each with a different headline
- [ ] Publish, run, evaluate same as Test 1
- [ ] Label winner: `Winner — Headline Round`

---

### TEST 3: TESTIMONIALS (Skip If None Available)

- [ ] Duplicate winning ad into new ad set(s)
- [ ] Name: `Click Test — Testimonials`
- [ ] Gather 5 testimonials (real or borrowed)
- [ ] Keep same: winning color block image from Test 1, winning headline, CTA, URL
- [ ] Create ads, each with a different testimonial as Primary Text
- [ ] Publish, run, evaluate
- [ ] Label winner: `Winner — Testimonial Round`

---

### TEST 4: IMAGES

- [ ] Duplicate winning ad into new ad set(s)
- [ ] Name: `Click Test — Image`
- [ ] Choose 5 different images to test
- [ ] Keep same: winning tagline, headline, testimonial, description, CTA, URL
- [ ] Create ads, each with a different image
- [ ] Publish, run, evaluate
- [ ] Label winner: `Winner — Image Round`

---

### TEST 5: PRIMARY TEXT (LONG BODY)

- [ ] Duplicate winning ad into new ad set(s)
- [ ] Name: `Click Test — Long Copy`
- [ ] Write 3-5 expanded primary text versions
- [ ] Keep same: winning image, headline, description, CTA, URL
- [ ] Create ads, each with different long-form primary text
- [ ] Publish, run, evaluate
- [ ] Label winner: `Winner — Long Copy Round`

---

### TEST 6: STRESS TEST

- [ ] Create 2-3 "finished" ads combining every winner from all rounds
- [ ] Run them against each other at same budget
- [ ] If at least one meets all thresholds: **this is your production ad**
- [ ] If none meet thresholds: go back and re-test specific elements
- [ ] Label final winner: `Full Winner Combo — Battle Tested`

---

### FINAL DEPLOYMENT

- [ ] Build final ad with full winning combination:
  - Primary Text / Tagline (winner)
  - Headline (winner)
  - Testimonial (winner, if tested)
  - Image (winner)
  - Long Body Copy (winner)
- [ ] Deploy for conversion campaigns, lead gen, or scaling
- [ ] Apply winning copy/images across ALL marketing channels:
  - Email subject lines
  - Sales pages
  - Social media posts
  - Proposals and pitch decks
  - Product listings

---

## 15. Metrics, Thresholds & What "Winning" Looks Like

### Metrics to Track

| Metric | What It Measures | Use For |
|--------|-----------------|---------|
| **Link Clicks** | Actual clicks to your destination | Confirms real engagement |
| **CPC (Cost per Link Click)** | Cost of each click | **Primary winner-picking metric** |
| **CTR (All)** | All clicks (likes, profile taps, "See More", CTA) | Hook strength indicator |
| **Unique Outbound CTR** | % of people who clicked the link | Conversion-intent metric |
| Impressions | How many times shown | Context only — not for decisions |
| Reach | Unique people shown to | Context only |

### Three-Threshold Winner Test

An ad qualifies as a winner when achieving **ALL THREE** simultaneously:

| Threshold | Value |
|-----------|-------|
| **Minimum Link Clicks** | 4+ clicks (within first 400 impressions) |
| **Cost Per Click** | Less than **$0.50** per click |
| **Click-Through Rate** | Higher than **1%** |

### Additional Benchmarks

| Level | CPC Range |
|-------|-----------|
| Strong winner | Under $0.50 |
| Still a win (lower bar) | Under $1.00 |
| Needs improvement | Over $1.00 |
| 20+ clicks at $0.50 or lower | Very strong signal |

### Post-Testing Target: Customer Acquisition Cost

| Metric | Non-Optimized | Optimized (after click testing) |
|--------|--------------|--------------------------------|
| **CAC** | $50+ | **$12-$20 average** |

The $12-$20 range "fluctuates rather than being a fixed number" and is "relatively independent of the advertising platform used."

---

## 16. Budget Breakdown

### Per-Test Costs

| Item | Cost |
|------|------|
| Daily budget per ad set | $30-40 |
| Actual spend per test (24-36 hours) | $30-45 |
| Number of tests | 4-6 |
| **Total for all 6 tests** | **$200-$300** |
| **Total for 4-test sprint** | **$100-$200** |

### If Using Approach B (Single Ad Set, Cheaper)

| Item | Cost |
|------|------|
| Daily budget | $25-50 |
| Per round (2-3 days) | $75-150 |
| **Total for 4 rounds** | **$300-$600** |

---

## 17. Timing & Duration

| Phase | Duration |
|-------|----------|
| Each individual test (Approach A with auto-off rule) | **24-36 hours** |
| Each individual test (Approach B with manual pause) | **2-3 days** |
| All 6 tests combined | **~2 weeks** |
| If additional rounds needed | 1-4 weeks total |

Steve claims he can help identify effective messaging **"in just 7 days using a small budget."**

---

## 18. Interpreting Results & Ambiguous Data

### Clear Winner

One variation clearly outperforms across all three metrics → move it forward.

### Close Results

When top performers are close:
- The **top 2-3 performers** indicate which messaging resonates
- You can re-test close contenders in the next round
- The system is iterative: "Guess, test, refine, repeat"

### No Winners

If no variation meets all three thresholds:
- Generate new variations with different angles and emotional hooks
- Check whether audience targeting is correct
- Remember: **95% of ideas won't work** — this is expected, not failure
- Multiple rounds of testing are normal

### The 5% Rule

Only ~5% of tested ideas are good enough to move forward profitably. Out of 20 ideas, expect 1 winner. Don't get discouraged — the methodology is designed to find the needle in the haystack cheaply.

---

## 19. Common Mistakes

1. **Assuming you know what your market wants** — "You are not your market." Testing consistently reveals that predictions are wrong 95% of the time.

2. **Testing multiple variables at once** — "Spaghetti testing." Isolate one variable per round.

3. **Using Dynamic Creative Optimization** — Facebook's automated combination testing wastes budget on untested combinations.

4. **Optimizing for Landing Page Views** — Costs 2-4x more than Link Clicks and isn't needed for click testing.

5. **Skipping the stress test** — Elements that test well individually may produce false positives when combined.

6. **Spending too much before testing** — Non-optimized ads have $50+ CAC. Click testing de-risks your spend.

7. **Giving up too early** — The 5% success rate is normal. Multiple rounds expected.

8. **Using Campaign Budget Optimization** — Turn CBO off. It prevents control over individual variation budgets.

9. **Not applying winning copy everywhere** — Results should feed into email subject lines, sales pages, social media, proposals — not just ads.

10. **Using Facebook Lead Forms for click testing** — Lead forms optimize for form-fillers, not curious clickers. This breaks the method's intent of testing curiosity/message resonance.

11. **Leaving ad slots blank (except by design)** — Every ad should be fully built out. Only the tested element changes.

12. **Using distracting images in early rounds** — Tests 1-3 use color block images (tagline text baked into a solid color background). The image slot is not for real imagery until Test 4.

13. **Judging too early** — Some ads look great at $5 spend then tank. Wait for full data (25-30 clicks or 400 impressions).

---

## 20. After Click Testing: Scaling & Conversion

### Immediate Next Steps

1. The winning stress-tested ad is ready to **direct traffic to sales**
2. Feed winning data back to Meta to improve ad delivery
3. Apply winning copy/images across ALL marketing channels

### Transition to Conversion Campaigns

- Move from Traffic objective to **Sales/Conversion objective**
- Direct ads to your store, booking page, or landing page
- The validated creative significantly reduces CAC from $50+ to $12-$20

### The Cross-Channel Effect

Steve discovered: **advertising your direct sales on Facebook reliably increases your Amazon/other platform sales**, even without running ads there. People see your brand, become aware, and some buy through other channels. He calls this "bonus money."

---

## 21. Adapting for DesignTransform / BonFX

### For Our Own Messaging Validation

**Test 1 tagline candidates:**
- "Backlog Destruction for Agencies"
- "AI-Powered Design & Dev Ops"
- "Your Agency's Secret Weapon"
- "Stop Hiring. Start Shipping."
- "The Design Team You Don't Have to Manage"

**Audience:** Agency owners, creative directors, small shops (2-10 people)
**Destination:** dbonneville-playground.vercel.app or simplified variant
**Budget:** $30/day x 2 weeks = ~$420 for full validation

### As a Service for Agency Clients

- Offer **pre-campaign messaging validation** using this system
- Run click tests before building full funnels — saves client money, proves messaging
- Combine with **Kallaway Framework** (Money/Time/Status/Fear) to generate tagline candidates
- Automate with **social-cli** from meta-ads-kit for campaign creation, insights pulling, and reporting

### Pain Point Discovery for B2B

Adapt the color block test for agency pain points:
- "My backlog never actually clears"
- "I can't find reliable freelancers"
- "My team is burned out doing work outside their expertise"
- "I don't have time to learn AI tools"
- "I'm losing clients to agencies that move faster"

---

## 22. Color Block Test Variant (Kallaher / Allen)

A related but distinct approach from Meredith Kallaher (Mint CRO practitioner) and Frankie Jo Allen. Tests **pain points** using minimal color-block graphics before running the full Pieper system.

| Setting | Value |
|---------|-------|
| Campaign type | Traffic |
| Budget | $30-40/day, campaign budget disabled |
| Audience | Cold interest, 4-5M size |
| Placements | Advantage Placements |
| Optimization | Link Clicks |
| Creative | Color block squares with pain point text (Canva) |
| Primary Text | Leave blank |
| Headline | Job title descriptor ("Agency Owner", "Creative Director") |
| Description | Two spaces (prevent auto-fill) |
| CTA | "Learn More" |

**Success criteria:** 4+ link clicks within first 400 impressions, CPC under $0.50, CTR over 1%.
**Automation rule:** Disable ads at 400 impressions.
**How many:** 6-10 emotional "I" statements as separate graphics.

This is a **pain point discovery** tool — useful BEFORE the full Pieper system. It tells you which emotional hooks resonate, then those feed into Test 1 as tagline candidates.

---

## 23. Tools & Tech Stack

### Required for Click Testing

| Tool | Purpose | Cost |
|------|---------|------|
| **Meta Ads Manager** | Create and run ads | Pay per spend |
| **Canva** | Design color blocks and ad images | Free tier works |

### For Scaling (Post-Testing)

| Tool | Purpose |
|------|---------|
| **Shopify** | Ecommerce store |
| **Klaviyo** | Email marketing |
| **Unbounce** | Landing pages + A/B testing |
| **Mouseflow** | Heatmaps for conversion optimization |

### For Automation (Our Stack)

| Tool | Purpose |
|------|---------|
| **social-cli** (`@vishalgojha/social-cli`) | Meta API wrapper — create campaigns, pull insights, pause/resume ads from CLI |
| **OpenClaw** | AI agent framework for automating the test cycle |

---

## 24. Key Statistics & Claims

| Statistic | Value |
|-----------|-------|
| Authors using click testing system | 2,000+ |
| Total AMMO community | 15,000+ |
| Community annual earnings | $78-80 million |
| Tests conducted/consulted on | 6,000+ |
| Individual testing elements | 50,000+ |
| Ideas that test profitably | ~5% (1 in 20) |
| CAC (optimized) | $12-$20 |
| CAC (non-optimized) | $50+ |
| System launch year | 2019 |
| Program referral rate | 32% |

---

## 25. Source Files & References

### Files on Disk

| File | Location |
|------|----------|
| Click Testing - Steve Pieper Click Test v02.pdf (77 pages) | `Dropbox/__eccentric/click test/test 01/` |
| Pieper Click Test Method 2.0.docx (ChatGPT session) | `Dropbox/__eccentric/click test/test 01/` |
| 40+ ad variant PNGs | `Dropbox/__eccentric/click test/` |
| gtm_lane_3.md | `Dropbox/_ai/bonneville_ai/` |
| gtm_todo.md | `Dropbox/_ai/bonneville_ai/` |

### Podcast Interviews

| Podcast | Episode | URL |
|---------|---------|-----|
| The Creative Penn | "Click Testing Ideas And Selling Direct" (June 2024) | [Link](https://www.thecreativepenn.com/2024/06/10/click-testing-ideas-and-selling-direct-with-steve-pieper/) |
| The Creative Penn | "Selling Books Direct To Your Readers" (Jan 2023) | [Link](https://www.thecreativepenn.com/2023/01/30/the-empowerment-of-selling-books-direct-to-your-readers-with-steve-pieper/) |
| Six Figure Author Experiment | "Episode 12 - Click-testing" (July 2024) | [Link](https://www.sixfigureauthorexperiment.com/p/episode-12-click-testing-with-steve) |
| Becoming A Household Name | "AMMO Version 4" (April 2024) | [Link](https://podcasts.apple.com/us/podcast/steve-pieper-founder-of-ammo-talks-ammo-version-4/id1603166771?i=1000652874947) |
| Hidden Gems (Fully Booked) | "Should Authors Sell Direct?" | [Link](https://www.hiddengemsbooks.com/podcast/should-authors-sell-direct/) |

### Steve Pieper's Sites

| Page | URL |
|------|-----|
| Main site | clients.stevepieper.com |
| Click Testing for Authors | app.stevepieper.com/click-testing-for-authors-information-page |
| AMMO V4 | app.stevepieper.com/AMMO-V4 |

### Reviews & Third-Party Analysis

| Source | URL |
|--------|-----|
| OnlineSuccessGenie — Click Testing Review | [Link](https://onlinesuccessgenie.com/steve-pieper-click-testing-for-authors-review/) |
| OnlineSuccessGenie — AMMO Review | [Link](https://onlinesuccessgenie.com/steve-pieper-ammo-review/) |
| ScribeCount — AMMO Review | [Link](https://scribecount.com/author-resource/indie-author-courses/steve-pieper-ammo-course-review) |
| Kindlepreneur — Selling Direct Courses | [Link](https://kindlepreneur.com/selling-direct-courses/) |
| KBoards Forum Discussion | [Link](https://www.kboards.com/threads/steve-pieper-ammo.334414/) |

### Practitioner Adaptations

| Source | URL |
|--------|-----|
| Meredith Kallaher — Color Block Test | [Link](https://meredithkallaher.com/blog/test-to-find-winning-copy/) |
| Rippling Roots — Facebook Click Testing | [Link](https://www.ripplingroots.com/blog/facebook-click-testing) |
| Matthew J Holmes — Testing Blurbs | [Link](https://www.matthewjholmes.com/blog/testing-blurbs-with-facebook-ads) |

### Original Methodology

| Source | URL |
|--------|-----|
| Mint CRO | [Link](https://get.mintcro.com/mm2/) |

---

## 26. Appendix: What's Behind the Paywall

These details are only available inside the paid Click Testing for Authors and AMMO V4 courses:

1. Exact number of variations Steve recommends per test
2. Exact geographic targeting advice
3. Specific interest targeting recommendations per industry/genre
4. The stress test's exact format, duration, and settings
5. Detailed criteria for when to re-test vs. move forward with marginal results
6. The "Golden Ratio" framework (AMMO Phase 2)
7. Specific Unbounce landing page templates
8. The "Ledger of Legends" spreadsheet and formulas
9. Exact Klaviyo email sequences
10. The "Post Purchase Email Flow of Justice"
11. Specific ad spend scaling increments
12. Whether all rounds use the same audience or different audiences
13. Steve's specific advice on interpreting ambiguous results
14. The full "Doorbuster" offer stack calculations
15. The "One-Click Gold" upsell system

---

## 27. Appendix: Source Conflicts & Resolutions

### Conflict 1: Ad Set Structure

| Source | Says |
|--------|------|
| Mint CRO / Official Pieper | One ad set per variation, one ad each |
| ChatGPT session / practitioners | All 5 ads in one ad set |

**Resolution:** Both work. Approach A (separate ad sets) is more rigorous. Approach B (one ad set, manual pause) is cheaper. Pick based on budget.

### Conflict 2: Placements

| Source | Says |
|--------|------|
| ChatGPT session | Manual > Feeds only |
| Mint CRO practitioners | Advantage+ Placements (automatic) |

**Resolution:** Feeds only gives cleaner data. Advantage+ gives more reach. Start with Feeds only; switch if impressions are too slow.

### Conflict 3: Click Threshold

| Source | Says |
|--------|------|
| Mint CRO / Pieper official | 400 impressions per ad, then auto-off |
| ChatGPT session | 25-30 link clicks per ad, manual pause |

**Resolution:** These measure different things. 400 impressions is input-based (exposure). 25-30 clicks is output-based (response). The 400-impression rule works with Approach A (separate ad sets). The 25-30 click rule works with Approach B (shared ad set). Both produce usable data.

### Conflict 4: Campaign Objective

| Source | Says |
|--------|------|
| Most sources | Traffic |
| Some Mint CRO practitioners | Engagement |

**Resolution:** Use Traffic. It's what Pieper teaches. Some practitioners use Engagement with "Get more website visitors" sub-option, which is functionally the same.

### Conflict 5: Number of Variations Per Round

| Source | Says |
|--------|------|
| Mint CRO | 6-10 per round |
| ChatGPT session | 5 per round |
| Practitioners | 3-5 minimum |

**Resolution:** More variations = more data but more budget. 5 is a solid default. Scale up to 10 if budget allows and you have enough ideas.

### Conflict 6: Description Field in Test 1

| Source | Says |
|--------|------|
| Mint CRO / Kallaher | Leave blank or two spaces |
| ChatGPT session | Fill in same description across all |

**Resolution:** For Test 1 (color block), leave it blank or two spaces. For later tests where description is not the variable, use a consistent neutral description or leave blank. Only fill it in when testing Description in its own round.
