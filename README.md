# Small-business SEO agent: 30 free Claude skills

![From the reel](reel.jpg)

**This is one of the free skill packs Will is giving away.** Every pack is built with **[Vera](https://github.com/WCRWCR12/vera)**, a free AI chief of staff for Claude: a personal assistant, a virtual office of AI agents you can watch work, and a growing library of skills. **Vera Social**, the full social media editor where the storyboard is the editor, is being released soon.

- More info: **[systemgc.com.au](https://www.systemgc.com.au)**
- New free skills every week: follow **[@will.ai.m_system](https://www.instagram.com/will.ai.m_system/)** on Instagram

---

One free folder. An SEO agent for small businesses that does what agencies charge a monthly retainer for:

1. **Audits your website**: titles, pages, speed basics, schema, Google Business Profile consistency, the fixes that actually matter, ranked.
2. **Finds the keywords your customers search**: the "[service] [suburb]" and "how much does it cost" searches a small business can actually win.
3. **Writes the pages**: full service pages with titles, meta descriptions and ready-to-paste schema, for Wix, Squarespace, WordPress, Shopify, anything.

Works for tradies, cafes, salons, clinics, any local business. Runs on your own computer with a normal Claude account. Nothing gets published, changed on your site or paid for without you.

## How to install

1. Open the Claude desktop app and go to the **Code** tab.
2. On this page, tap the green **Code** button, then **Download ZIP**, and unzip it. Drag the whole folder into the chat.
3. Say: **"install these skills"**.

Claude follows `INSTALL.md`: it copies each skill into your skills folder and shows you how to start.

## How to use it

Start a new chat and say:

> **"Do the SEO for my business: [your website]. We're a [what you do] in [your area]."**

The agent asks a couple of quick questions, then writes everything into an `seo-report/` folder: the audit, your keyword plan, your new pages, and a "do this week" list.

## What's inside (30 skills)

**The agent**
- **small-business-seo-agent**: the three-stage agent above. Start here.

**Audit**
- **seo**: the SEO orchestrator: full audits, single pages, technical, schema, content, AI search.
- **seo-audit**: full multi-page audit with specialist sub-checks and a health score.
- **seo-technical**: crawlability, indexing, speed, security, mobile.
- **seo-page**: deep check of one page.
- **seo-schema**: finds, checks and writes structured data (LocalBusiness, FAQ, Service, Product).
- **seo-sitemap**: checks or builds your sitemap.
- **seo-images**: image alt text, sizes, formats.
- **seo-hreflang**: for sites in more than one language or country.
- **seo-sxo**: does the page match what searchers actually want?
- **seo-drift**: compares your site against a saved baseline to catch things breaking.

**Local**
- **seo-local**: Google Business Profile, reviews, NAP consistency, local schema, location pages.
- **seo-maps**: map-pack rankings and competitors around you (needs a DataForSEO account for live data).
- **local-citations-listings**: the free directories and listings to claim, in order, with Australian, UK and US options.

**Keywords and planning**
- **seo-plan**: an SEO strategy for your industry.
- **seo-cluster**: groups keywords into pages that don't compete with each other.
- **seo-competitor-pages**: "X vs Y" and "alternatives to X" pages.
- **seo-programmatic**: many location or service pages from one template, without thin content.
- **seo-flow**: evidence-led prompts for each stage of SEO.

**Writing**
- **seo-content**: content quality and E-E-A-T (experience, expertise, trust).
- **seo-content-brief**: a writer's brief for one keyword.
- **rank-fast-seo-article**: one article built to rank for one keyword, with your own point of view in it.
- **seo-geo**: get quoted by ChatGPT, Perplexity and Google's AI answers.
- **social-seo**: get found in Instagram, TikTok and YouTube search.

**Extras**
- **seo-backlinks**: who links to you, and which links are hurting you.
- **seo-ecommerce**: product pages and shopping results.
- **seo-google**: real data from your Google Search Console, Analytics and PageSpeed (needs your Google API key).
- **seo-dataforseo**: live search volume and rankings (needs a paid DataForSEO account).
- **seo-image-gen**: social preview and blog images (needs an image-generation tool).
- **google-preferred-sources-badge**: the "add us as a preferred source on Google" button.

## What you need

Nothing to start: the agent works with Claude's built-in web fetch and search. A few deep-dive skills (`seo-audit`'s PDF report, `seo-google`, `seo-backlinks`, `seo-dataforseo`, `seo-maps`) can use extra tools and API keys; they tell you what's missing and carry on without them. For the full toolset behind those skills, see the original project: [AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo).

## Licences

The 25 `seo` and `seo-*` skills are from [claude-seo](https://github.com/AgriciDaniel/claude-seo) by AgriciDaniel, MIT-licensed; see `LICENSE` and the `LICENSE.txt` in each folder. `social-seo` is MIT-licensed (`license: MIT` in its `SKILL.md`). The rest are free to use and change.

No ranking guarantees: SEO takes weeks to months, and results depend on your market.
