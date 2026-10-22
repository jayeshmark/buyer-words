# Buyer Words

**Your next ad is already written. Your buyers wrote it in a review.**

Buyer Words is a skill for AI agents (built for Claude) that mines what buyers actually say about a product and turns it into ad copy. Give it a product. It goes and reads the reviews, pulls the exact phrases out untouched, sorts them, and builds draft ad lines from the strongest ones.

No surveys. No brainstorming. The words are already out there, in public, for free.

## What it does

1. **Finds the words.** App Store and Google Play reviews for apps, Amazon for physical products, G2 and Capterra for software, plus Reddit threads, YouTube comments and support pages where buyers talk honestly.
2. **Pulls the verbatims.** Exact phrases, copied word for word, slang, typos and emotion intact. Nothing is cleaned up or paraphrased, because the messy version is the valuable version.
3. **Sorts them into four piles.**
   - **Problem words**: the pain, in their words.
   - **Desire words**: the outcome and the feeling they want.
   - **Objection words**: the doubts, and the reasons people churn or refuse to pay again.
   - **Proof words**: the results they report after buying.
   
   Repeats across many buyers are marked (that is the market talking, not one person), and so are burns, the phrases carrying real emotion.
4. **Builds the lines.** The strongest phrases are rearranged into draft ad lines, shown as phrase to line pairs so you can see exactly where every line came from. The three strongest lines are picked, with the reason for each.

The skill never invents a review, a phrase or a result. If a source cannot be reached, it says so plainly in the output.

## A real run

From the example output in this repo (the skill run on the Forest focus app, [`examples/forest-buyer-words.md`](examples/forest-buyer-words.md)):

A reviewer wrote about the tree that dies when you break a focus session:

> "it stays there as a monument to my lack of commitment"

The line the skill built from it:

> **"The tree you kill stays in your forest. A monument to your lack of commitment."**

No copywriter invents that at a desk. A buyer hands it to you.

## Install

**Claude (skills):** download this repo, and add the folder as a skill, or copy `SKILL.md` into your skills directory. Then ask your agent to run Buyer Words on your product before writing any ad, headline or landing page.

**Any agent that reads instruction files:** the whole method lives in [`SKILL.md`](SKILL.md). Hand the file to the agent and name your product.

## Where it came from

Buyer Words is the companion skill to Lesson 1 of **Ads for Products**, a series that teaches how to write and create ads for your product, published on [Second Order](https://secondorderdaily.substack.com). The lesson teaches the method by hand; this skill runs it for you.

## License

MIT. Use it, fork it, ship ads with it.
