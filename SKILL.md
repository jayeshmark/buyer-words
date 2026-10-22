---
name: buyer-words
description: Mine App Store, Play Store, marketplace, review site and community text for a product, pull verbatim buyer phrases without cleaning them, sort them into problem, desire, objection and proof piles, and turn the strongest phrases into draft ad lines. Use before writing any ad, headline or landing page.
---

# Start With Their Words: Mine Buyer Language and Turn It Into Ad Lines

## What this skill produces

- Run this skill before writing any ad, headline or landing page for a product.

- Produce one document holding the buyer's own phrases for the product, sorted into four piles, with the strongest phrases turned into draft ad lines.

- Work from real buyer language only. Never invent a review, a phrase or a result.

## Get the target

- Ask for the product name and where it is sold, such as its App Store page, Play Store page, Amazon listing or website.

- When the user gives only a name, find the official store and listing pages first and confirm the match with the user before mining the wrong product.

- Same name trap: different products share names, and search results push the wrong one. Match on the developer or seller name and the store listing itself, never on the product name alone.

- Note the product type, because it decides the sources. Apps live in store reviews, physical products live in marketplace reviews, software lives in review sites and communities.

## Gather the words

- Pull reviews from both stores for an app, the Apple App Store and Google Play, and read both sides. Five star reviews carry desire and proof words, one and two star reviews carry problem and objection words.

- Pull marketplace reviews for a physical product, Amazon first, then the other marketplaces where the product sells.

- Pull review site and community text for software, G2 and Capterra reviews, plus Reddit threads and forum posts where buyers discuss the product and its rivals.

- Add YouTube comments on the product's videos and reviews, and the product's own support pages, FAQ and community posts, where frustrated buyers write the most honestly.

- Aim for at least 100 reviews or comments per major source where that volume exists. Read past the first page by sorting for most helpful and most recent. Many routes expose only a few dozen reviews; the depth test below governs when to stop, not the count.

- Save the raw text you gather to a working file named <product>-buyer-words-raw.md in the working folder as you go, with the source named beside each block. The same review can surface through two sources; count it once and say so in the source counts.

## Pull the verbatims

- Copy buyer phrases exactly as written, with spelling, slang and emotion intact. The verbatim is the unit of work.

- Never paraphrase, correct or clean a phrase at this stage. A cleaned phrase loses the anger, relief or pride that makes it usable, and a desk written line is what this skill exists to replace.

- Keep the phrases short, one idea each. Split a long review into its separate phrases.

- Drop phrases that are only about price, delivery or the seller, unless a price phrase carries trust or fairness emotion; those are objections and stay. Keep phrases about the problem, the result, the feeling and the doubt.

## Sort the four piles

- Sort every phrase into one of four piles.

  - Problem words, the pain and frustration in the buyer's words.
  - Desire words, the outcome and the feeling they want.
  - Objection words, the doubts, fears and reasons they almost did not buy. Reviewers already bought, so this pile also takes churn and refusal to pay again: trust and fairness anger lands here, while anger at product quality lands in Problem words.
  - Proof words, the results and changes they report after buying.

- Mark the repeats inside each pile as [REPEAT xN], N being the number of mouths. A phrase or idea that shows up in many mouths is the market talking, not one person.

- Mark the burns inside each pile as [BURN]. A burn is a phrase with strong emotion in it, such as anger, embarrassment, relief or pride, and burns usually carry the strongest lines.

- Mine the language your buyers sell in. If reviews arrive in other languages, note them separately instead of silently dropping or mixing them.

- Stop gathering when you can state the customer's frustrations and desires in the customer's own words without guessing. That is the depth test.

## Turn phrases into lines

- Build draft ad lines from the strongest phrases, the repeats and the burns first.

- Rearrange a phrase rather than inventing one. Cut words, change the order, join a problem phrase to a desire phrase.

- Keep the buyer's words inside the line. The finished line should still sound like a person said it, not like a brand wrote it.

- Produce phrase to line pairs so the user can see where every line came from. Aim for 10 to 15 pairs.

- A line built from an objection phrase is objection handling copy, not an ad line, unless it states something the product truly does today. Never let a line promise what the product does not do.

- Pick the three strongest lines and say in one sentence each why they are strongest, usually a repeat, a burn, or a problem and desire joined cleanly.

## Present the result

- Present the document with five parts in this order.

  - The sources used, with a rough count from each.
  - The four piles, with the repeats and burns marked.
  - The phrase to line pairs.
  - The three strongest lines.
  - Anything you could not reach, such as a store page that blocked reading, stated plainly.

- Label any illustrative example as made up when a real phrase could not be found for a point. Never let a made up example sit beside real verbatims unmarked.

## Available connectors

- Use `muse.connector_search` to find other connectors and `muse.skill_search` to find related skills.

- If nothing here fits, look on the web for a maintained API or MCP server and set it up with [Custom Connectors and MCPs](/opt/muse/skills/custom-connector-setup/SKILL.md), or build a custom connector.

## Websites and fallbacks

- [Apple App Store](https://apps.apple.com/) for app reviews. Use `browser.browse` on the app's page and read the reviews section, sorting by most helpful and most recent, and open the all reviews view where offered.

- [Google Play](https://play.google.com/) for app reviews. Use `browser.browse` on the app's page and read the ratings and reviews section, opening the full reviews list to get past the summary.

- [Amazon](https://www.amazon.com/) for physical product reviews. Use `browser.browse` on the listing and read the reviews with the star filter set to critical as well as positive.

- [G2](https://www.g2.com/) for software reviews. Use `browser.browse` on the product page and read the liked and disliked sections of individual reviews.

- [Reddit](https://www.reddit.com/) for unfiltered buyer talk. Use `browser.browse` or search to find threads naming the product or its problem, and mine comments rather than post titles.

- Store pages often show no review text at all when read as plain pages, because the reviews sit behind interaction. When that happens, use review mirrors (AppBrain for Google Play comments, WorldsApps for the App Store feed) or the store's review feed, and state plainly in the output which route actually supplied the words. Where a source strips star ratings, sort phrases by their content, not by the five star / one star heuristic.
