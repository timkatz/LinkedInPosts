# LinkedIn Posts - Tim Katz / DYODE

Strategic LinkedIn content repository for Tim Katz (@timkatz) and DYODE (Shopify development, digital marketing, eCommerce agency).

**Focus:** Authentic operator voice with contrarian Q4 takes, pattern recognition across client base, no motivational content.

---

## Quick Start

### For Creating/Modifying Posts

1. **Always use the `@linkedin-post-writer` agent** when drafting or refining posts
2. Review `voice-guide.md` and `content-strategy.md` for context
3. Posts must follow:
   - Tim's authentic, consultative voice (not aggressive)
   - Specific numbers and real client examples
   - Clear text format, no HTML tags
   - Natural paragraph breaks for easy copy/paste to Buffer

### For Publishing

1. Copy post text directly from `posts-scheduled.md`
2. Paste into Buffer or LinkedIn
3. Update `posts.md` with actual engagement metrics after 72 hours
4. Commit changes with specific post details

---

## Repository Structure

### Strategy Documents (Read First)

| File | Purpose |
|------|---------|
| **CLAUDE.md** | Navigation guide - start here for how to use this repo |
| **content-strategy.md** | Core strategy: buying cycles, target audience, seasonal themes, DYODE positioning |
| **voice-guide.md** | How Tim speaks - tone, examples, what works, what to avoid |
| **humanization-guide.md** | AI tell checklist - eliminate em-dashes, robustness, furthermore, etc. |

### Content Files

| File | Purpose |
|------|---------|
| **posts-scheduled.md** | Upcoming posts ready to publish (currently Nov 2-30, 2025) |
| **posts.md** | Published posts with engagement metrics (reactions, comments, impressions, reach, engagement rate) |
| **posts-analysis.md** | Strategic breakdown of what makes each post work |
| **november-strategy-review.md** | November campaign analysis and strategic rationale |
| **performance-tracking.md** | Performance benchmarks and engagement targets |

### Supporting Files

| File | Purpose |
|------|---------|
| **clients.md** | Approved client roster for mentions/case studies |
| **.claude/agents/linkedin-post-writer.md** | Sub-agent configuration for post creation |

---

## How to Use This Repo

### Understanding the Strategy

1. Start with `CLAUDE.md` for navigation
2. Read `content-strategy.md` for what to write about
3. Study `voice-guide.md` for how Tim speaks
4. Cross-check against `humanization-guide.md` before publishing

### Creating New Posts

**Process:**
```
1. Define the post idea/topic
2. Invoke @linkedin-post-writer agent with:
   - Post concept or topic
   - Reference to content-strategy.md for alignment
   - Reference to voice-guide.md for tone
3. Agent drafts post in Tim's authentic voice
4. Review for strategy fit and voice consistency
5. Request revisions if needed
6. Add to posts-scheduled.md or posts.md
7. Commit changes to GitHub
```

**Example Command:**
```
"Draft a post about Shopify site speed optimization for Q4, emphasizing our development competency. Use a real client example with specific metrics."
```

### Publishing Posts

1. Copy post text from `posts-scheduled.md`
2. Paste into Buffer or LinkedIn (no HTML tags needed)
3. Post at scheduled time
4. After 72 hours, record engagement metrics in `posts.md`
5. Commit with post details

**Commit Message Format:**
```
Published: Nov 5 post - Site Speed Optimization

- Title: "Site speed tanks during Q4. It's not your server, it's your decisions."
- Posted: Tuesday, 9:00 AM
- Reactions: [number] | Comments: [number] | Impressions: [number]

Brief description of key message and strategic goal.

🤖 Generated with Claude Code
Co-Authored-By: Claude <noreply@anthropic.com>
```

### Tracking Changes

All strategy and content changes go through GitHub:

```bash
git add .
git commit -m "Description of what changed"
git push origin main
```

---

## Content Strategy Overview

### Target Audience
- eCommerce brand owners/CMOs considering new agency
- Shopify store operators
- Brands doing $10M+ annual revenue (ideal $20-50M)
- Decision-makers in Q2 (April-June) buying window for Q4 execution

### Key Themes (November 2025)

1. **Nov 2** - Qualified traffic vs traffic volume (foundational positioning)
2. **Nov 5** - Site speed/Shopify stack optimization (development competency)
3. **Nov 7** - A/B testing during peak traffic (contrarian take)
4. **Nov 12** - Pattern recognition: three types of brands (client base insights)
5. **Nov 14** - Email segmentation strategy (marketing competency)
6. **Nov 19** - Conversion funnel UX (upstream from checkout)
7. **Nov 23** - Pre-BFCM prediction (setting expectations)
8. **Nov 30** - Real-time BFCM results (what actually happened)

### Voice Characteristics

**✅ Tim's Authentic Voice:**
- Direct and factual with specific numbers
- Consultative, patient, not aggressive
- Diagnostic (discovering issues together, not blaming)
- Real client examples with before/after metrics
- Shows DYODE as partner, not order-taker
- Pattern recognition across client base
- Mix of "we/our team" language
- Natural, conversational writing (not templated)

**❌ Avoid:**
- Ghostwriter's formulaic structure (italic titles, rigid bullets)
- Aggressive "fire your agency" language
- Made-up scenarios for engagement
- Motivational/life coach tone
- AI vocabulary (leverage, streamline, robust, delve)
- Em-dashes and formal transitions (moreover, furthermore)
- Overstated client sizing (say "we work with a lot of eCommerce brands" not "up to billions")

---

## Key Strategic Insights

### Buying Cycle with Lead Time
- Website builds take 3-6 months
- Buying decisions must work backwards from desired launch dates
- **Q2 (Apr-Jun)** = Critical buying window for Q4 launches
- Posts should build awareness and positioning in advance

### DYODE's Unique Position
- Full-service agency: qualified traffic + CRO + A/B testing (not either/or)
- Pattern recognition across 50+ client sites
- Proactive partnership (monitoring as part of ongoing work)
- Consultative approach (helping them understand, not judging)

### What Actually Works
- Real client metrics (specific numbers, not vague claims)
- Before/after comparisons with clear ROI
- Tactical, actionable advice
- Honest about readiness and timelines
- Shows personality without forcing it

---

## Sub-Agent: @linkedin-post-writer

**Purpose:** Draft and refine LinkedIn posts in Tim's authentic voice while maintaining strategy alignment.

**When to Use:**
- Creating new posts
- Refining existing drafts
- Adjusting tone or messaging
- Iterating based on feedback

**What It Does:**
- References content-strategy.md for strategic fit
- References voice-guide.md for tone consistency
- Performs self-review against quality criteria
- Flags any strategy/voice misalignments
- Returns posts ready for copy/paste

**How to Invoke:**
```
"Draft [post topic] for [date], emphasizing [key message].
Reference content-strategy.md for alignment with [theme].
Maintain voice from voice-guide.md (consultative, specific numbers, real examples)."
```

---

## Performance Tracking

### Engagement Targets
- Baseline: 1-3% engagement rate (reactions + comments / impressions)
- Strong: 3%+ engagement rate
- Outstanding: 5%+ engagement rate

### What to Track
- Reactions (likes)
- Comments
- Impressions (total views)
- Reach (unique viewers)
- Engagement rate (%)

### Post-Publication Process
1. Publish to LinkedIn/Buffer
2. Wait 72 hours for stabilization
3. Record metrics in `posts.md`
4. Note any standout comments or patterns
5. Commit changes

---

## Common Tasks

### Add a New Scheduled Post
```bash
# 1. Invoke @linkedin-post-writer agent with post concept
# 2. Get draft approval
# 3. Add to posts-scheduled.md
git add posts-scheduled.md
git commit -m "Add new scheduled post: [date] - [title]"
git push origin main
```

### Update Strategy or Voice Guidelines
```bash
# 1. Edit the relevant guide file
git add voice-guide.md content-strategy.md [others]
git commit -m "Update: [what changed and why]"
git push origin main
```

### Record Post Performance
```bash
# 1. Update posts.md with engagement metrics
git add posts.md
git commit -m "Published: [date] post - [title]

- Reactions: X | Comments: Y | Impressions: Z | Engagement: A%"
git push origin main
```

---

## Guidelines

### Voice & Tone
- Read `voice-guide.md` before every post
- Check `humanization-guide.md` for AI tells
- Always use @linkedin-post-writer agent for drafting
- Posts should feel conversational, not corporate

### Content Quality
- Include specific numbers and percentages
- Use real client examples (with approval from clients.md)
- Show before/after or problem/solution
- Make the takeaway clear without being preachy
- Vary post structure and length

### Strategy Alignment
- Posts should ladder up to one of the Key Themes
- Avoid redundant messaging (check recent posts first)
- Consider timing relative to BFCM/seasonal cycles
- Ensure realistic scenarios (no manufactured drama)

### Format
- Clear text only (no HTML tags)
- Natural paragraph breaks
- Scannable structure (not wall of text)
- Ready to copy/paste into Buffer or LinkedIn

---

## Approved Clients

For case studies and mentions, use only:
- AG Jeans
- Wyze
- GreenPan
- Aloha
- Tori Richard
- Bandai Namco Shop
- Invisalign
- Stikwood
- L*Space

See `clients.md` for details.

---

## Contributing

### Making Changes
1. Create or edit files locally
2. If modifying posts, use @linkedin-post-writer agent first
3. If modifying strategy/voice, discuss scope before editing
4. Test changes locally (review voice-guide.md checklist)
5. Commit with clear message
6. Push to main branch

### Commit Message Format
```
[Type]: [Brief description]

[Optional detailed explanation]

🤖 Generated with Claude Code
Co-Authored-By: Claude <noreply@anthropic.com>
```

**Types:**
- `Added:` New posts, new files
- `Updated:` Changes to existing posts, strategy updates
- `Fixed:` Corrections to tone, accuracy, strategy alignment
- `Published:` Post published with metrics

---

## Questions?

- **How do I use the voice guide?** Start with `voice-guide.md` - it has examples of what works vs what doesn't
- **When should I use the agent?** Always use @linkedin-post-writer for post creation/refinement
- **What if a post doesn't feel right?** Check against voice-guide.md and humanization-guide.md
- **How often should we post?** See `content-strategy.md` for seasonal cadence
- **Can I mention other clients?** Only if they're on the approved list in `clients.md`

---

## Resources

- GitHub: https://github.com/timkatz/LinkedInPosts
- LinkedIn: https://linkedin.com/in/timkatz
- DYODE: https://dyode.com

---

**Last Updated:** October 31, 2025
**Next Review:** After November 2025 post series completes
