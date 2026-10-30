# Guide 2: Google Search Console

**Goal:** The owner's website is added and verified in Google Search Console, so they can see how people find it.

**Prerequisite:** A working website at its own domain (Guide 1). If the website doesn't load yet, stop and go back to Guide 1.

**Your role:** Coach only. The owner signs in to Google and completes every verification step themselves. Do **not** use browser automation or any tool on Google pages, and never ask for passwords or codes.

## Step 1: Explain it

Say: "Search Console is a free Google tool. It tells you how people find your website on Google and lets Google know your site exists."

## Step 2: Sign in (owner does this)

1. Go to **search.google.com/search-console**.
2. Sign in with the Google account they want to own the business's online presence. A dedicated business Google account is best, not a personal one. If they don't have one, they can create it at accounts.google.com (they do this themselves).

## Step 3: Add the website (owner does this)

1. Click **Add property** (or the property dropdown in the top-left).
2. Two options appear: **Domain** and **URL prefix**. Recommend **Domain**, and enter their domain without `https://` or `www` (like `yourbusiness.com`).
3. Click **Continue**.

If they are using a website builder that doesn't let them edit DNS records, **URL prefix** is simpler: enter the full address, for example `https://www.yourbusiness.com`.

## Step 4: Verify ownership (owner does this)

Google will ask them to prove they own the site. Coach through whichever applies, one click at a time:

**Domain option (DNS record):**
1. Google shows a long line of text starting with `google-site-verification=`. Click **Copy**.
2. In a new tab, sign in to Namecheap, go to **Domain List**, click **Manage** next to the domain, then the **Advanced DNS** tab.
3. Click **Add new record**, choose **TXT Record**, set **Host** to `@`, and paste the copied text into **Value**. Click the green checkmark to save.
4. Return to Search Console and click **Verify**. This can take a few minutes; if it fails, wait 10 to 30 minutes and try again.

**URL prefix option:** Google will offer methods such as **HTML tag** or an automatic verification if the site builder is connected to the same Google account. Pick the easiest one shown and have the owner follow the on-screen steps. For site builders (Wix, Squarespace, WordPress), suggest searching the builder's help for "Google Search Console verification".

You can help explain what each screen means. You cannot click these for them.

## Step 5: Submit the sitemap (optional but helpful)

Once verified:
1. In the left menu, click **Sitemaps**.
2. Type `sitemap.xml` and click **Submit**. (Many builders create this automatically. If it errors, skip it; it's not critical.)

## Done check

Ask the owner to confirm they see their website name in the top-left of Search Console with no error message. Then ask: "Are you done with this step? Say 'done' when ready."

Record "Search Console verified" in `my-progress.md`.
