# Awesome AI Product Videos

> Selling products with AI-made short videos and AI-written listings: real worked examples, the real inputs they started from, and the exact Skills that produced them.
>
> Want the Skills that made these? → **Seller Content Skills** — 3 free below, the full 10-skill pack is $9.99/mo · $79/yr · $169 lifetime. *(Store link: [ADD AT LAUNCH])*

## How this repo works

Most "prompt collections" show you an output and hide the input. This repo does the opposite. Every case folder contains:

- **`input.md`** — the real product, deal, or listing the Skill was handed, with its source. Real things, sold by real sellers, found on real shelves.
- **`output.md`** — the deliverable the Skill produced from that input, unedited.
- **`README.md`** — a two-minute read of what went in, what came out, and what the case proves.

Copy the workflow, not just the words. Every Skill in this repo runs on one rule: **claims come from the material provided — nothing is invented, and anything unverifiable is flagged, not filled.**

## Worked examples (start here)

| Case | Skill | Real input | What you get |
|---|---|---|---|
| [TikTok product video](examples/tiktok-product-video/) | `tiktok-product-video` | LOVEWE Electric Spin Scrubber, live TikTok Shop listing, $69.99 | 3 ready-to-shoot scripts — 3 different hooks, full voiceover, shot lists, captions |
| [Deals post writer](examples/deals-post-writer/) | `deals-post-writer` | Walsunny storage cabinet, Walmart Flash deal $75 (was $144), Oct 31 2026 | Deal post + interactive post + Reels script, discount math re-checked, linkless CTA |
| [Amazon listing polish](examples/amazon-listing-polish/) | `amazon-listing-polish` | VQRRCKI 32 oz bottle, live Amazon listing with a keyword-stuffed title | Clean title, 5 bullets, description, backend search terms, 6-shot image brief — with honest `[VERIFY]` flags |

## Quickstart

These Skills are plain `SKILL.md` files that work with Claude Code, Codex, Cursor, and any agent that reads skill files:

1. Copy a skill folder (e.g. `tiktok-product-video/`) into your agent's skills directory (for Claude Code: `.claude/skills/` in your project, or `~/.claude/skills/` for all projects).
2. Give the agent a product listing, a deal, or a rough draft — a link, a screenshot, or pasted facts all work.
3. The Skill asks only for what's missing and blocks production, then returns a finished deliverable in its fixed format — script, post, or listing — with a verification note listing anything it could not confirm.

No build step, no dependencies, no API keys. If your agent can't read skill files, paste the `SKILL.md` contents into your system prompt and it works the same way.

## Skill index

| # | Skill | What it does | Access |
|---|---|---|---|
| 1 | `tiktok-product-video` | Product listing → 3 TikTok Shop video scripts (hook, voiceover, shot list, CTA) | **Free** |
| 2 | `deals-post-writer` | Verified deal → deal post + interactive post + Reels script, prices never invented | **Free** |
| 3 | `amazon-listing-polish` | Rough draft → polished Amazon title, 5 bullets, description, search terms, image brief | **Free** |
| 4 | `product-image-brief` | Product facts → 8-shot photo/AI-image brief with per-platform sizes | Member |
| 5 | `ugc-script-variants` | One script → 10 genuinely different hook variants for A/B testing | Member |
| 6 | `etsy-listing-seo` | Product facts → Etsy title, 13 tags, category/attributes, description | Member |
| 7 | `kdp-low-content-planner` | Book idea → full KDP plan: niche check, interior map, cover brief, listing pack | Member |
| 8 | `xiaohongshu-cover` | Note topic + takeaway → Xiaohongshu cover brief (text, layout, image direction) | Member |
| 9 | `local-business-reels` | Local business facts → one ready-to-shoot Reel brief with caption and CTA | Member |
| 10 | `whop-clip-cutter` | Authorised long video → 5 bounty-ready clips with hooks, captions, checklists | Member |

**Pricing:** $9.99/mo · $79/yr · $169 lifetime. The lifetime price rises $20 for every 10 skills added to the catalogue — that's stated here, in advance, not sprung later. Free skills stay free.

## Categories (growing)

Worked cases are filed by what they sell: **Home gadgets** · **Pet** · **Auto accessories** · **Beauty** · **Local business**. New cases are added as they are produced — each one from a real product, never a mock-up.

**New-model watch:** when a major new video model or tool ships, a case using it lands here within 48 hours, with the full settings shown.

## Contributing

PRs welcome: one worked case per PR — a real product, its source, the input you gave the Skill, and the unedited output. Cases with invented prices, ratings, or results are rejected on sight; that rule is the whole point of the repo.

## License

- **Examples** (everything under `examples/`): shared for learning — read them, learn the workflow, cite them with a link back. 
- **The Skills themselves** (`SKILL.md` files): the 3 free skills are free to use in your own selling work. Commercial reposting or resale of any Skill — free or member — is not permitted.
- Products, brands, and listings shown in examples belong to their owners; inclusion is documentation of a workflow, not endorsement.

---

*Seller Content Skills — sell the content workflow, not the hype. Every output in this repo can be traced back to a real input. Check our work.*
