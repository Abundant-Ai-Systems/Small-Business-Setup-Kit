# Onboarding

Follow this script when the owner starts. Speak in plain English. Ask one question at a time and wait for the answer.

First, check whether `my-progress.md` exists. If it does, read it, summarize where they left off, and skip to **Part 3** (or the next unfinished guide).

## Part 1: Get to know the business

Greet the owner warmly, say you'll help them get their business set up online in four short steps, and that they do all the account work themselves while you coach. Then ask, one at a time:

1. **What does your business do?** (A sentence or two is fine.)
2. **Where do you operate?** (City, region, or area you serve.)
3. **Do you have a storefront customers visit, or do you travel to your customers?** Offer three choices:
   - Storefront - customers come to me at a fixed address
   - I travel - I go to my customers (service area)
   - Both

Also ask for the **business name** exactly as customers know it (needed for the "not sure" checks below).

Save the answers to `my-progress.md`.

## Part 2: What do you already have?

For each item below, ask exactly:

> **Do you have this set up? Yes, no, or not sure.**

Ask about them in this order, one at a time:

| # | Item | Plain-English description to give | Guide |
|---|------|-----------------------------------|-------|
| 1 | Website and domain | "A website with its own address, like yourbusiness.com" | `guides/01-website-and-domain.md` |
| 2 | Google Search Console | "A free Google tool that shows how people find your website" | `guides/02-search-console.md` |
| 3 | Google Business Profile | "Your listing on Google Search and Maps" | `guides/03-google-business-profile.md` |
| 4 | Social media profiles | "Facebook, Instagram, and similar pages for your business" | `guides/04-social-media.md` |

### If the owner says "not sure"

Give a quick check they can do themselves, wait for the result, then record yes or no:

- **Website and domain:** Type the web address you think it is into your browser. Does your site load? If you don't know the address, search your business name on Google and see whether a website of yours appears. Also check your email for old receipts from Namecheap, GoDaddy, Wix, or Squarespace.
- **Search Console:** Go to search.google.com/search-console and sign in with the Google account you'd use for the business. If you see your website listed in the top-left dropdown, you have it. If it asks you to add a property, you don't. (If you have no website yet, the answer is "no".)
- **Google Business Profile:** Search your business name on Google, or on Google Maps. If a box with your info appears on the right (or below on a phone) and it shows "Manage this profile" or "Claim this business" when signed in, check which. "Manage" means you own it. "Claim this business" or no listing means no.
- **Social media:** Search your business name on Facebook and Instagram. Do you see pages you created and can log in to? Seeing a page you can't log in to counts as "no" for now.

If the owner is unsure about the result of a check, treat the item as "no" and let the guide confirm what already exists.

Note: Search Console needs a website first. If they answer "no" to the website, mark Search Console "no" automatically and tell them why, without asking.

## Part 3: Build the checklist

Show the owner a simple checklist of their status, for example:

```
[x] Website and domain - already done
[ ] Search Console - needed
[ ] Google Business Profile - needed
[ ] Social media profiles - needed
[ ] Add Abundant AI Systems as a manager - last step
```

The manager step is always included, always last, and only comes after the other items on the list are done or deliberately skipped by the owner.

Save the checklist to `my-progress.md`. Ask: "Does this look right? Ready to start with the first one?"

## Part 4: Run the guides, one at a time

Run the guides for the **missing** items, in this order:

1. `guides/01-website-and-domain.md`
2. `guides/02-search-console.md` (requires a working website)
3. `guides/03-google-business-profile.md` (use the storefront/service-area answer from Part 1)
4. `guides/04-social-media.md`
5. `guides/05-add-abundant-ai-as-manager.md`

Rules for running them:

- Read the guide fully before you start, then coach from it step by step.
- Skip guides for items the owner already has. If a skipped item is something the manager guide needs (for example, a Business Profile), note it.
- When a guide ends, ask: "Are you done with this one? Say 'done' when you're ready to move on." Move to the next guide **only** after they say so. If they want to stop, save progress and tell them they can come back any time by opening Claude Code in this folder.
- Update the checklist and `my-progress.md` after each guide.
- If they are stuck, troubleshoot with plain-English suggestions. Never ask them to share a password or security code.

## Part 5: Finish

After the manager guide, congratulate them, recap what is now set up (from the checklist), and tell them Abundant AI Systems will be in touch once the invitations are received.
