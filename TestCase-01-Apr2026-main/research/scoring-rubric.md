# Research Scoring Rubric

Use this rubric to score source quality consistently across all experts and materials.

## Purpose

- Standardize quality assessment for LinkedIn posts, YouTube transcripts, and other sources
- Make expert ranking transparent and evidence-based
- Improve reliability before turning research into a playbook

## Scoring scale

### 1) Accuracy score (0-5)

- `5` - Fully verified (author, URL, date, ownership, and content context all correct)
- `4` - Verified with minor uncertainty in one non-critical field
- `3` - Mostly correct but one important field is weak or inferred
- `2` - Multiple missing/uncertain fields
- `1` - Major uncertainty in attribution or source integrity
- `0` - Unusable or unverifiable source

### 2) Evidence confidence (low / medium / high)

- `high` - Supported by multiple credible signals (e.g., direct source + corroborating channel)
- `medium` - Supported by one credible signal only
- `low` - Limited proof or unresolved ambiguity

## Quality dimensions (recommended weighted score)

Score each dimension 1-5, then apply weights.

1. Relevance to B2B SaaS newsletter/email strategy - `30%`
2. Practicality/actionability of insight - `25%`
3. Recency (freshness of source) - `15%`
4. Originality/depth (not generic advice) - `15%`
5. Credibility/practitioner evidence - `15%`

## Weighted score formula

`weighted_score = (relevance*0.30) + (actionability*0.25) + (recency*0.15) + (originality*0.15) + (credibility*0.15)`

Final weighted score range: `1.00 - 5.00`

## Data quality gate (must-pass before using insight)

Only treat an item as "playbook-ready" if all are true:

- Accuracy score >= `4`
- Evidence confidence is `medium` or `high`
- Weighted score >= `3.50`
- Source URL is accessible and attributed correctly

## Suggested interpretation bands

- `4.50 - 5.00` = Tier A (high-priority source)
- `4.00 - 4.49` = Tier B (strong source)
- `3.50 - 3.99` = Tier C (usable with caution)
- `< 3.50` = Tier D (archive, do not prioritize)

## Per-file scoring block (copy/paste)

Use this block in any source file when needed:

- Relevance (1-5):
- Actionability (1-5):
- Recency (1-5):
- Originality (1-5):
- Credibility (1-5):
- Weighted score (1.00-5.00):
- Accuracy score (0-5):
- Evidence confidence (low / medium / high):
- Playbook-ready: (yes / no)

## Expert-level aggregation

For each expert, compute:

- Average weighted score across all collected items
- Average accuracy score
- Confidence distribution count (high/medium/low)
- Number of playbook-ready items

Then rank experts by:

1. Highest average weighted score
2. Highest count of playbook-ready items
3. Highest average accuracy score

## Reviewer checklist

- [ ] All source files have required metadata
- [ ] Scores are filled using this rubric
- [ ] Weighted score is calculated consistently
- [ ] Top insights are from Tier A/B items
- [ ] Final recommendations cite only playbook-ready sources
