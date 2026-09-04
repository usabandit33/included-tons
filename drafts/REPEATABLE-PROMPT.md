# Repeatable prompt — boring-search directory + GitHub Pages + nightly automation

Do not use this prompt for dumpster rental, roll-off, junk hauling, or garbage. That product is Included Tons and is already live.

Copy everything under the line into a new Grok chat (or an automation create).

---

You are building a small consumer directory for ONE boring thing people search every week. Follow this exact playbook. Do not invent a general “Mogul” brand. Do not touch dumpster rental / roll-off / junk / garbage hauling.

## 1. Pick the niche
Scan X (latest) and the open web (including site:reddit.com) for repeated complaints, not trends. A good niche has:
- Daily or weekly search intent (someone needs the thing this week)
- Confusing price, permit, wait time, or “who actually shows up”
- Local operators who publish a phone or email on their own site
- Room for a checklist a national form will not write

Reject: anything already covered by Included Tons; thin affiliate clones; niches that only work as pay-per-call spam.

Name the product after the decision the customer has to get right (the number, the permit, the wait), not after a tycoon word.

## 2. First market
Pick ONE US metro with either high prices, lots of independents, or loud complaint volume. Say why in one sentence.

## 3. Repos
GitHub user is usabandit33 unless told otherwise.
- Private working repo if drafts must stay hidden.
- Public customer files that GitHub Pages can serve: `index.html`, `[city].html`, one explainer page, `styles.css` at repo **root** so `https://usabandit33.github.io/[repo]/` works. Do not publish README-as-the-site.
- `drafts/` is operator-only: outreach, hauler lists, opportunities, this playbook. Never link drafts from the public homepage.

If Pages is already pointed at a repo, put the customer HTML at that repo root. Do not assume a Pages API exists — tell the user the three clicks: Settings → Pages → main → / (root).

## 4. Public site rules
Customer is a homeowner or small contractor in a hurry.
- Homepage: plain-English promise + checklist + two CTAs (use the checklist, call a local provider).
- City page: tap-to-call (`tel:`) list from phones published on the provider’s own site. Not a ranking. Not a lead form.
- Explainer page: the trap (hidden fee, no-show, permit) in short sentences.
- Titles and metas may include real search phrases (`[service] [city]`, `[service] permit [city]`, `how much is [service] in [city]`) only when they read like English.
- No invented prices, reviews, or emails. No referral fees, “Mogul,” or operator money talk on public HTML.
- Visuals: simple CSS + inline SVG. Dark, high-contrast, one accent color. No stock-photo dump.

## 5. Money (operator only, in drafts/)
The customer never pays the directory.
Providers may later pay a flat referral after a completed job, or a labeled featured listing. Do **not** put that in the first outreach email. First email CTA is only: reply with the word that means “send your public rates / hours / phone” or REMOVE.

## 6. Outreach pack (drafts only)
Write: email draft, send list of 5–10 providers with public emails, recommended Proton local-part (`[product]@proton.me`). Do not send mail. Do not use the user’s personal Gmail. Do not guess inboxes.

## 7. Nightly automation
Create one daily automation (evening, America/Chicago unless told otherwise) whose prompt:
- Reads the live HTML
- Refreshes search-term matches honestly
- Finds more providers with published phone/email and appends `drafts/haulers.md`
- Rotates ONE additional US city each night into `drafts/opportunities.md` (why / why not, 3 contacts, 3 queries)
- Adds a public city page only if ≥3 published phone numbers exist
- Never emails anyone
- Notifies with city, new providers, queries, and whether the live site changed, plus source links
- Ignores India news

## 8. Done looks like
- Live Pages URL
- Checklist on the home page
- City call page
- Drafts: outreach, contacts, opportunities file, automation id
- A two-line note to the user: what to send tomorrow, what not to send

Start by naming three candidate niches (not hauling), pick one with the strongest live complaints, and build.
