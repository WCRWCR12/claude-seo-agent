# Install instructions (for Claude)

The user has dragged this folder in and asked to install the skills. Do the following, then report back in a short list.

## 1. Copy the skills

Copy each of the 30 skill folders (every folder in this directory that contains a `SKILL.md`) into the user's personal skills folder:

- Mac / Linux: `~/.claude/skills/`
- Windows: `%USERPROFILE%\.claude\skills\`

Create the folder if it doesn't exist. Copy whole folders, including `references/`, `assets/` and `LICENSE.txt` files. If a skill with the same name is already installed, ask the user before replacing it. Don't copy `README.md`, `INSTALL.md`, `LICENSE` or `reel.jpg`.

## 2. Nothing else to install

The main agent (`small-business-seo-agent`) needs only web fetch and web search. Don't install anything else. If the user later wants the optional extras (Google Search Console data, DataForSEO, Moz, PDF reports), point them to the README's "What you need" section and ask before installing anything.

## 3. Tell the user how to start

Say:

> Installed. Start a new chat and say: **"Do the SEO for my business: [your website]. We're a [what you do] in [your area]."** I'll audit the site, find the keywords your customers search, and write your new pages into an `seo-report` folder. Nothing goes on your website until you put it there.

Then list a few other things they can say:

| Try saying | Skill |
|-----------|-------|
| "Audit just my homepage." | seo-page |
| "Check my Google Business Profile and local SEO." | seo-local |
| "Which free directories should my business be listed on?" | local-citations-listings |
| "Write a page to rank for '[service] [suburb]'." | small-business-seo-agent / seo-content |
| "Write the schema for my business." | seo-schema |
| "How do I get mentioned by ChatGPT?" | seo-geo |

## 4. Finish

Tell the user the skills are installed (or which ones failed and why) and that they may need to start a new chat for the skills to appear.
