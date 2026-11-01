# Case: amazon-listing-polish

**Skill:** `amazon-listing-polish` (free) — turn a rough listing draft into a polished, search-ready Amazon listing.

**Input → Output**
- **Input** (`input.md`): a real live Amazon listing (VQRRCKI 32 oz insulated bottle, ASIN B0BG55ZRFG) whose title is a keyword-stuffed run-on — exactly the kind of draft sellers hand this skill. Only the listing's own spec-table facts were extracted.
- **Process:** the facts were rebuilt to the skill's formula: clean sentence-case title (brand + product + one differentiator + size), 5 benefit-led bullets in buyer-priority order, a description that doesn't repeat the bullets, backend search terms with no title words and no brand names, and the fixed 6-shot image brief. Facts the source doesn't contain were flagged, not filled.
- **Output** (`output.md`): the complete paste-ready listing, including the two honest flags the skill is designed to produce — `[VERIFY PRICE]` and `[VERIFY exact lid count]`.

**What this case proves:** the polish is conservative on purpose. It would be easy to "improve" this listing with an 18/8 steel grade, a review count, or a best-seller claim — the source supports none of them, so the output invents none of them. That restraint is what makes the output safe to publish.
