# Outbound playbook

How we find people in the case study's situation. The case study itself lives in [gtm/case-study.md](../gtm/README.md), and the weekly numbers and outreach angles in `gtm/pipeline.md`; refer to them here, don't copy them.

## Six rules

1. **Start from the case study, not a list.** Write the PULL statement first. Then ask: what would this situation leave behind in public? Those traces are your signals.
2. **Company first, people last.** Qualify the company (site, job ads, stack, team shape, reviews) before looking up the person.
3. **Skip the obvious signals, stack the quiet ones.** "Looking for a tool" posts are seen by every vendor. Three weak hints on the same company beat one loud one.
4. **Always pair a need signal with an urgency signal.** Need: they're doing the Project and their option is failing. Urgency: something happened in the last 30 to 60 days. Need without urgency goes to a watch list, not to outreach.
5. **Wide in, 90 to 99% out.** Start with the biggest pool you can get, exclude fast with cheap checks, and give only the top few percent a human look.
6. **Manual before machine.** Run a new recipe by hand on 20 to 50 companies. Automate it only once it produced real conversations.

## Where signals live

The lead gen waterfall, warmest first, until the week's quota is met: signups and trials you haven't had a call with; then leads buried in your inbox and follow-ups owed; then people who engaged with your content or viewed your profile and fit the case study; then people posting about the situation and their commenters; then cold leads by role and company size. The quota comes from your funnel (contacted to first meeting, last 4 to 6 weeks in `gtm/pipeline.md`), capped by what your accounts can send in a week. How it's computed is in the [lead-gen skill](../.claude/skills/lead-gen/SKILL.md).

| Source | What to look for |
|---|---|
| Your own signups and trials | People who signed up in the last 60 days and never had a call, what they did in the product, and whether they fit the case study's Who |
| Your own inbox | Replies you never answered, positive replies never booked, deals gone quiet, trials ended with no card |
| Your own posts and profile | Who commented, reacted or viewed your profile lately, and what their comment or profile says about the situation |
| Job ads | Roles and tools named in the ad |
| Company websites | New careers pages, new sales or partner pages, new scripts in the page source |
| Review sites (1 and 2 stars) | Named reviewers leaving a competitor, with the reason |
| Public threads (Reddit, communities, LinkedIn comments) | Someone stuck on the exact Project, recently |
| Posts | First-person "here's what I tried" posts, and who comments with their own story |
| News | Events that create a deadline for a whole group at once |

## Scoring (keep it dumb)

- +2 per need signal, +3 per urgency signal (older than 60 days counts 0)
- +2 warm: commented on, reacted to or viewed your profile or posts in the last 30 days. It's not a need signal: a warm lead still needs one in their own words to pass 5
- Your own exclusions: -5 or out (competitors, people who sell the same thing as a service...)
- Outreach at 5 or more (a need and an urgency signal). 2 to 4 goes on a watch list, re-checked monthly.
- Cold leads found by role and company size alone go on their own list, marked "cold, no signal", to fill the week's quota. The weekly review compares how they convert with the warmer sources.

## Message and sequence (default)

Signals decide **who** and **when**. The message only earns the call. Don't quote the signal back at them ("saw your account got restricted"): it reads as surveillance. Ask AI Rob for the outbound message, then keep it to one line that's interesting to them and a short ask.

1. Day 0: connection request, no note. Your profile is the landing page.
2. Day after accept: the message.
3. Two to three days later: a one-word bump.
4. Stop. On a positive reply, don't answer with your booking link alone: ask whether they have a calendar you can book into, and offer a slot today, with your own link only as a fallback. No booking after a day: a short nudge. Two days later, one last follow-up, then stop.

**Benchmarks per stage:** 30%+ of requests accepted (under 20% is a profile or list problem), 20%+ of accepted connections reply (under 5% is a message problem), 50%+ of replies positive, and most positive replies book a call. Fix only the stage furthest below its benchmark.

## Per case study version

<!-- Add a block when a new version of the case study gets sourcing. Keep the old blocks: they show which recipes worked for which version. -->

### v2 · portfolio company off plan, AI rebuild of the P&L (2026-11-27)

Same signals as v1 below, widened from real assets to any portfolio company off plan, plus:

| Type | Signal | Points |
|---|---|---|
| Need | Owns or sits on the board of a lower mid-market software or services portco that is unprofitable or shrinking (layoffs, hiring freeze, flat or falling headcount on LinkedIn) | +2 |
| Need | Fund publicly talks about AI-driven efficiency but has no captive AI team | +2 |
| Urgency | Portco CEO or CFO change, restructuring, or lender or covenant news in the last 60 days | +3 |
| Warm | A mutual connection or past contact who can introduce (Rob: they're pitched this constantly, warm beats cold) | +2 |

Ask every v2 conversation for the peer sitting on the company furthest off plan.

### v1 · asset behind plan, IC watching (2026-11-27, superseded by v2 the same day)

Added by the weekly review of 2026-11-27. Why: PULL #1 selected by title ("private equity"), and 12 of 13 first meetings had no asset behind plan. The one that pulled ([Filip](../deals/filip-tomasik-activum-sg/deal.md)) owns a portfolio behind business plan with IC watching.

**Signals**

| Type | Signal | Points |
|---|---|---|
| Need | Personally runs asset management for named assets or portfolio companies (real estate and asset-backed PE: PBSA, hotels, care homes; lower mid-market portcos), not a deal-team-only or support role | +2 |
| Need | Public sign an asset is off plan: occupancy or lettings trouble, covenant reset, write-down, management or CEO change at the portco | +2 |
| Urgency | Operator, property manager or portco CEO replaced in the last 60 days | +3 |
| Urgency | Refinancing, IC review, fund raise or exit process for that asset in the last 60 days | +3 |
| Out | Fund has a captive AI or value creation team doing this (Hg, OTPP, Tomer's fund, Five Arrows) | out |
| Out | No asset of their own: independent sponsors pre-close, holdco founders, LPs, advisers, service providers | out |
| Out | Large-cap funds (60+ portcos) | out |

**Sourcing recipe** (not run yet; run by hand on 20 to 50 before automating):

1. Sales Navigator: UK, titles containing asset management / portfolio / operations at real estate and asset-backed PE funds and lower mid-market funds; exclude analysts, associates, tax, legal, coaches, students.
2. Check each fund for one named asset with an urgency signal above; score; outreach at 5+.
3. Ask Filip and Mikhail for names in the same seat.

### v0 · PULL #1 by title (2026-10-16 to 2026-11-22, retired 2026-11-27)

Dripify list of UK people with "private equity" type titles. 934 contacted, 24.3% accepted, 16% of accepted replied, 13 first meetings logged across all channels in the same weeks, 1 fit. Retired: title alone doesn't find people with an asset behind plan.

**Signals**

| Type | Signal | Points |
|---|---|---|
| Need | | +2 |
| Urgency | | +3 |
| Out | | out |

**Sourcing recipe** (tool, query, filters, cost per batch):

1.
