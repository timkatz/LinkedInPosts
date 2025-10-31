# CLAUDE.md

**Navigation guide for Claude Code.** This file points to the actual strategy, voice, and formatting documents.

⚠️ **Strategy decisions:** Always see `content-strategy.md` - that's the single source of truth.

## Overview

This is a content management repository for LinkedIn posts with engagement analytics. The owner is Tim Katz, co-founder of DYODE (www.dyode.com), an agency specializing in Shopify Development, Digital Marketing, and Strategic eCommerce Consulting.

## Repository Structure

### **Posts & Tracking**
- `posts.md` - Published posts with engagement metrics (raw data only)
  - **BASELINE DATE: Oct 30, 2025** - First post using authentic voice strategy
- `posts-scheduled.md` - Future posts ready to publish (Nov 2-25, 2025)
  - **FORMAT:** Clear text with natural line breaks (NO HTML tags, NO CSV tables)
  - Each post clearly delineated with `---` separator
  - Ready to copy/paste directly into Buffer or any scheduling tool
- `posts-analysis.md` - Historical performance analysis (Aug-Oct 2025 ghostwritten baseline)

### **Strategy & Planning**
- `content-strategy.md` - **⭐ MAIN STRATEGY FILE**
  - Seasonally-adjusted posting schedule (Q1-Q4 cadence)
  - Monthly content mix and themes to pursue
  - November 2025 finalized schedule and content
  - Sample content calendar and success benchmarks
- `november-strategy-review.md` - Detailed breakdown of November posts
  - Strategic analysis of all 11 posts
  - Why each post works, weaknesses, recommendations
  - Performance predictions and role in monthly narrative
- `performance-tracking.md` - Before/After comparison tracking
  - Baseline: Oct 30, 2025
  - Ghostwriter benchmarks to beat (3,563 avg impressions)

### **Voice & Writing Guidelines**
- `voice-guide.md` - **⭐ Tim's authentic voice** (WHAT to say, HOW Tim says it)
- `humanization-guide.md` - **⚠️ Eliminate AI tells** (CRITICAL - read this!)
- `clients.md` - Approved client reference list (9 brands)

## Key Context

**About Tim Katz:**
- Co-founder of DYODE (Orange County, California)
- Former PacSun eCommerce leader ($100M+ revenue)
- Expertise: Shopify migrations, eCommerce strategy, conversion optimization
- Target audience: eCommerce brands, fashion/retail brands, CEOs/founders

**Content Voice:**
- Direct, experienced, results-focused, no-nonsense
- Slightly contrarian, calls out industry failures
- Always backs advice with specific numbers and examples
- Leverages PacSun credibility and real client results

**Best Performing Content:**
- Shopify migration post (Sep 25, 2025): 31,477 impressions, 185 reactions, 31 comments
- Tactical how-to posts with specific timelines
- Case studies with percentage-based results (e.g., "285% revenue increase")
- Agency accountability themes

## Quick Reference

### When Writing or Modifying LinkedIn Posts

**⭐ USE THE `@linkedin-post-writer` AGENT:**
When drafting new posts or modifying existing posts, always use the `@linkedin-post-writer` agent. It has access to all strategy documents and voice guidelines, and will ensure posts meet all standards.

**What the agent handles:**
- Drafting new posts in Tim's authentic voice
- Modifying/refining existing posts
- Ensuring compliance with voice-guide.md and humanization-guide.md
- Proper formatting for posts-scheduled.md
- Strategic alignment with content-strategy.md

**If you need to understand the guidelines yourself (not using the agent):**

→ **Step 1: Read `voice-guide.md`** for:
- Tim's authentic voice vs ghostwriter's formulaic style
- How to write naturally (not templated)
- Voice comparison examples
- What makes Tim sound like Tim

→ **Step 2: Read `humanization-guide.md`** for:
- Eliminating AI tells (em-dashes, AI vocabulary)
- How humans actually write (contractions, fragments, rhythm)
- Before/after examples (AI vs human)
- Critical: Run through the humanization checklist

→ **Step 3: Check `clients.md`** for:
- Approved client list (only use these 9 brands)
- How to reference clients appropriately

→ **Step 4: Format for `posts-scheduled.md`** using this standard:
- **Clear text only** - No HTML tags (`<br>`, etc.) or markdown formatting
- **Natural line breaks** - Use paragraph spacing, not forced breaks
- **No CSV/table format** - Structure posts as readable markdown
- **Clear delineation** - Use `## Date | Day | Time` + title header, separated by `---`
- **Copy/paste ready** - Format allows direct pasting into Buffer or any scheduler
- **Example structure:**
  ```
  ## Nov 2, 2025 | Sunday, 10:30 AM
  ### Post Title Here

  First paragraph.

  Second paragraph with natural break.

  ---
  ```

### When Planning Content Strategy
→ **Read `content-strategy.md` for:**
- **⭐ MAIN STRATEGY FILE** - All strategy lives here
- Seasonally-adjusted posting schedule (Q1-Q4 cadence)
- Monthly content mix and themes
- Agency differentiation positioning
- Client roster messaging (authenticity over flex)
- Content themes to pursue or avoid
- DYODE's unique perspective (qualified traffic + CRO + A/B testing)
- Everything else strategy-related

→ **Read `november-strategy-review.md` for:**
- Detailed breakdown of November 2025 posts

### When Analyzing Performance
→ **Read `posts-analysis.md` for:**
- Historical performance data and patterns
- What's worked and why (backed by data)
- Audience behavior insights
- Statistical benchmarks

### Core Principles for Every Post

**VOICE & CONTENT:**
1. **Sound like Tim** - Direct, factual, consultative (not aggressive). See voice-guide.md
2. **Sound like a human** - NO em-dashes, NO AI vocabulary, use contractions. See humanization-guide.md
3. **Use real examples** - Only approved clients from clients.md. Include dialogue.
4. **Include specific numbers** - Percentages, timelines, dollar amounts with context
5. **"We/our team" language** - Not "I" (DYODE is a team)
6. **Mix it up** - Vary structure, length, format (don't be formulaic)
7. **Pass the read-aloud test** - If it sounds like a presentation, rewrite it

**FORMATTING & TECHNICAL:**
8. **No HTML tags** - Use clear text with natural line breaks, not `<br>` or `<br><br>`
9. **No CSV/table format** - Write as readable markdown with headers and separators
10. **Copy/paste ready** - Format should work directly in Buffer without reformatting
11. **Time strategically** - Thursday 9 AM primary, adjust for seasonal cadence

## Content Focus

Posts cover:
- eCommerce strategy and optimization
- Shopify migrations and development
- Digital marketing and agency accountability
- Conversion rate optimization
- Fashion/retail brand growth
- Practical business advice (anti-guru approach)

## Working with This Repository

When helping manage LinkedIn content:

**FOR STRATEGY & PLANNING:**
→ See `content-strategy.md` - This is the single source of truth for all strategy decisions

**FOR VOICE & WRITING:**
→ **Step 1:** Read `voice-guide.md` - Tim's authentic voice (what to say, how Tim says it)
→ **Step 2:** Read `humanization-guide.md` - Eliminate AI tells (CRITICAL - read this!)
→ **Step 3:** Check `clients.md` - Approved client list before mentioning brands

**FOR POST FORMATTING:**
→ See `posts-scheduled.md` for example of proper formatting:
- Clear text with natural line breaks (NO HTML tags)
- No CSV/table format - write as readable markdown
- Structure: `## Date | Day | Time` header, title, content, `---` separator
- Copy/paste ready for Buffer (no reformatting needed)

**FOR DATA TRACKING:**
→ `posts.md` - Keep markdown table format, update engagement metrics when available
→ `posts-analysis.md` - Historical performance data and patterns

## Critical Quick Reference

**Most important principles:**
- **Human voice > AI** - NO em-dashes, NO AI vocabulary, use contractions
- **Authentic > formulaic** - Tim's natural style performs better
- **Specific numbers + dialogue** - Never post generic advice
- **Read aloud test** - If it sounds like a presentation, rewrite it
- **No HTML tags** - Use clear text with natural line breaks
- **Copy/paste ready** - Posts paste into Buffer without reformatting

**For complete strategy decisions:**
→ See `content-strategy.md` - Single source of truth for all strategy

## Metrics to Track

When adding new posts to posts.md, include these metrics:
- Date, Day, Time
- Post Title
- Post Content (full text)
- Reactions
- Comments
- Impressions
- Reach
- Engagement Rate (Eng Rate)

**Performance benchmarks:**
- Baseline: 1,000-1,500 impressions
- Strong: 2,000-4,000 impressions
- Viral: 10,000+ impressions
- Target engagement rate: 1.5-2%
