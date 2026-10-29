# Shop Tools

**Free tools for online shop owners. Check a product page for SEO and AEO, check if your titles fit Etsy, eBay and Google (one title or a whole list), check your 13 Etsy tags, and see your real profit per sale.**

**Live demo:** https://legacyroar7-maker.github.io/shop-tools/

![Product page checker](preview-checker.png)

## What it does

### 1. Product page checker (SEO + AEO)
Paste your product name, keyword, SEO title, meta description, description and FAQ. You get:

- **A score out of 100** with a clear list of what to fix first
- **SEO checks:** title and meta length, keyword in the right places, no keyword stuffing
- **Sales checks:** enough detail, short sentences, bullet points, real facts and numbers
- **AEO checks:** questions and answers that AI assistants (like ChatGPT) can quote, with direct first sentences
- **A Google preview** of how the page looks in search results
- **Ready-made schema code** (Product + FAQPage, JSON-LD) to paste into Shopify or any shop

### 2. Marketplace title checker
Type or paste a product title. Live character counts show if it fits:

| Where | Limit | What happens if it is longer |
|---|---|---|
| Etsy title | 140 characters | Etsy will not accept it |
| eBay title | 80 characters | eBay will not accept it |
| Shopify SEO title | about 60 characters | Google usually cuts the end |
| Meta description | about 155 characters | Google usually cuts the end |

The part that does not fit is shown crossed out, so you see exactly which words buyers lose. You also get quick fixes: extra spaces, too many words in CAPITALS (Etsy allows 3), symbols used twice (Etsy allows % : & + once each), repeated words, and a look at your first 40 characters.

![Marketplace title checker](preview-titles.png)

Tip: put the product type and the words buyers search for first. Limits can change, so check your platform's help pages too.

### 3. Bulk title checker
Paste many titles at once, one per line (up to 500). Pick the limit: Etsy 140, eBay 80, Shopify SEO title about 60, or your own number. Each title gets a row that shows:

| Check | What it flags |
|---|---|
| Too long | How many characters are over the limit. The extra part is crossed out. |
| Repeated words | Words used twice or more, like "mug (3x)". Repeats waste space. |
| CAPITALS | A whole title in capital letters, or more than 3 words in capitals (Etsy allows 3). |
| Extra spaces | Spaces at the start, at the end or double spaces. They count as characters. |
| Same title twice | Two listings with the same title, so buyers cannot tell them apart. |

You also get a count of titles that need a fix, a filter to show only those, and a **Download results (CSV)** button to work through the list in a spreadsheet.

How to use it with your shop:

1. Export your products (Shopify: Products > Export. Etsy: Settings > Options > Download data. eBay: Seller Hub > Reports > Downloads).
2. Open the file and copy the title column.
3. Paste it into the bulk checker and pick your platform.
4. Fix the rows marked in red first, starting with titles that are too long.

![Bulk title checker](preview-bulk.png)

### 4. Etsy tag checker (new)
Paste your tags, one per line or with commas between them. Add your listing title too (optional). Each tag gets a row with what to fix:

| Check | What it flags | Colour |
|---|---|---|
| Too long | Tags over 20 characters. The extra part is crossed out. | Red: Etsy will not take it |
| Characters not allowed | Symbols like & / # ! . Use letters, numbers and spaces. An apostrophe or hyphen is fine inside a tag, not as the first character. | Red |
| Same tag twice | A repeat wastes one of your 13 slots. | Red |
| More than 13 tags | Etsy takes 13. Rows after 13 are marked. | Red |
| One word only | A 2 or 3 word phrase, like "sage green mug", is closer to what buyers type. | Gold: a tip |
| Only repeats the title | Every word is already in your title. Allowed, but the slot could add a style, an occasion or who it is for. | Gold: a tip |

At the top you see tags used out of 13, how many need a fix and how many free slots are left. **Copy tags for Etsy** copies up to 13 tags that pass the rules, with extra spaces and repeats removed, separated by commas. Paste them into the Tags box of your listing.

How to use it with your shop:

1. Open a listing in Etsy (Shop Manager > Listings) and copy its tags and title.
2. Paste them into the tag checker.
3. Fix the red rows first, then fill any free slots.
4. Use the gold tips to swap weak tags for phrases buyers type: style, occasion, who it is for, material.

![Etsy tag checker](preview-tags.png)

Rules used come from Etsy's help pages: up to 13 tags, up to 20 characters each. Platforms change their rules, so check Etsy's help pages too.

### 5. Profit calculator
Type your product cost, shipping, packaging, ads and fees. You get:

- Profit per sale and margin
- Break-even price
- The exact price you need for your target margin

![Profit calculator](preview-profit.png)

## Why I built it
Most shop owners guess. They write product pages without checking them, and they set prices without counting every fee. This tool makes both checks take one minute.

## Privacy
Everything runs in your browser. No sign-up, no tracking, nothing is sent to a server.

## Tech
One HTML file, plain JavaScript, no frameworks, no build step. Hosted free on GitHub Pages. Works on phones.

## Use it
Open the live demo, press **Load example** to see how it works, then paste your own page.

---
Built by **Tuli, Satin & Scale**. I build Shopify stores, write product pages with SEO and AEO, make AI product videos and build web apps for shops.

Want this done for your shop or deck? I do it as a fixed-price project on Upwork: [Hire me on Upwork](https://www.upwork.com/freelancers/~01c18d191d6a95988c)
