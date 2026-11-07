---
name: google-preferred-sources-badge
description: Add Google's "preferred sources" button to a website so visitors can make the site a preferred source in Google Search (Top Stories, Discover, AI Overviews). Use when auditing or editing a client or own site for quick SEO wins, or when asked about the preferred sources badge.
---

# Google preferred sources badge

Source: reel DceiK3UM9aI (@edward.builds), checked against Google Search Central.

## Steps
1. Fetch the current official doc: https://developers.google.com/search/docs/appearance/preferred-sources (always re-read; code and options may change).
2. Pick the method: standard JS embed (script tag in head plus a div where the button goes), custom-styled button with Google's assets, or the deeplink fallback when JS is not allowed.
3. Place the button where it is seen: end of articles/news posts, footer, beside social links. Add one line: "Add us as a preferred source on Google."
4. Test on the live page: button renders, click opens the Google flow, returns to the page.
5. Log the site, date and placement.

## Notes
- Free. Needs HTML edit access; for client sites, include it in the audit and get approval before editing.
- Claimed as a ranking signal when many users click. Unproven for small sites; most useful for news/content pages. Do not promise rankings to clients.
- Pairs with seo-page and seo-technical (as a quick-win line item).
