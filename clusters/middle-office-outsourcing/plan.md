# Cluster Plan: Middle Office Outsourcing

**Seed Keyword:** middle office outsourcing
**Created:** 2026-05-17
**Total Posts:** 7 (1 pillar + 6 spokes)
**Estimated Words:** 11,400

---

## SERP Overlap Analysis

URLs appearing across multiple keyword searches (high overlap = same cluster):

| URL | Appearances | Keywords Matched |
|-----|-------------|------------------|
| limina.com/blog/guide-middle-office-outsourcing | 8 | Core pillar competitor |
| alphafmc.com/.../rethinking-future-of-middle-office | 7 | Decision/hybrid content |
| empaxis.com/blog/top-middle-office-outsourcing-providers | 5 | Providers comparison |
| ultimusfundsolutions.com/middle-office-outsourcing | 5 | Definition/services |
| iqeq.com/us/services/middle-office | 4 | Service provider page |
| cscglobal.com/.../middle-office | 3 | Enterprise provider |
| sia-partners.com/.../middle-office-outsourcing-mid-sized | 2 | Mid-market specific |

**Clustering Decision:** Keywords with 4+ shared URLs → same post or tightly linked cluster

---

## Market Data

| Metric | Value | Source |
|--------|-------|--------|
| Market Size (2024) | $8.48B | Data Bridge |
| Projected (2032) | $19.00B | Data Bridge |
| CAGR | 10.60% | Data Bridge |
| Small firm adoption | 44% | Industry reports |
| Large firm adoption | 61% | Industry reports |
| Cost reduction | Up to 30% | Industry reports |

---

## Pillar Page

| Field | Value |
|-------|-------|
| **Title** | Middle Office Outsourcing: The Complete Guide for Asset Managers |
| **Primary Keyword** | middle office outsourcing |
| **Secondary Keywords** | middle office outsourcing for asset managers, outsourced middle office services, middle office outsourcing guide |
| **Template** | Ultimate Guide |
| **Word Count** | 2,800 |
| **URL** | `/blog/middle-office-outsourcing-guide` |

**Competitor to beat:** [Limina - A Comprehensive Guide to Middle Office Outsourcing](https://www.limina.com/blog/guide-middle-office-outsourcing)

---

## Spoke Posts (Clustered by Intent)

### Cluster 1: Foundational/Explainer

| # | Title | Keyword | Template | Words |
|---|-------|---------|----------|-------|
| 1.1 | What is Middle Office? Definition, Functions & Role in Asset Management | what is middle office | Explainer | 1,400 |
| 1.2 | Middle Office vs Back Office vs Front Office: Key Differences | middle office vs back office | Comparison | 1,500 |

**SERP Overlap:** High (7+ shared URLs between these keywords)
**Internal Links:** Both link to pillar; 1.1 → 1.2 bidirectional

---

### Cluster 2: Decision/Evaluation

| # | Title | Keyword | Template | Words |
|---|-------|---------|----------|-------|
| 2.1 | Middle Office Outsourcing vs In-House: How to Decide | middle office outsourcing vs in-house | Comparison | 1,600 |
| 2.2 | Signs You Need Middle Office Help (Before It's Too Late) | when to outsource middle office | Listicle | 1,200 |

**SERP Overlap:** Medium (4-6 shared URLs)
**Internal Links:** Both link to pillar; 2.1 → 2.2 bidirectional; 2.1 → 1.2 (vs back office)

---

### Cluster 3: Commercial/Provider

| # | Title | Keyword | Template | Words |
|---|-------|---------|----------|-------|
| 3.1 | Top Middle Office Outsourcing Providers Compared (2026) | middle office outsourcing providers | Best-of | 1,800 |
| 3.2 | How Much Does Middle Office Outsourcing Cost? | middle office outsourcing cost | Guide | 1,100 |

**SERP Overlap:** Medium (4-6 shared URLs)
**Competitor to beat:** [Empaxis - Top Middle-Office Outsourcing Providers](https://www.empaxis.com/blog/top-middle-office-outsourcing-providers)
**Internal Links:** Both link to pillar; 3.1 → 3.2 bidirectional; 3.1 → 2.1 (decision framework)

---

## Execution Order

Write posts in this order (foundational first, pillar last):

| Priority | Post ID | Title | Rationale |
|----------|---------|-------|-----------|
| 1 | 1.1 | What is Middle Office? | Foundational, AI-citation ready definition |
| 2 | 1.2 | Middle Office vs Back Office | Clarifies terminology, high search intent |
| 3 | 2.2 | Signs You Need Help | Pain-point content, attracts problem-aware buyers |
| 4 | 2.1 | Outsourcing vs In-House | Decision-stage, links existing pillar cluster |
| 5 | 3.2 | Cost Guide | High commercial intent, ROI-focused |
| 6 | 3.1 | Provider Comparison | Commercial intent, validates Anchor positioning |
| 7 | Pillar | Complete Guide | Links to all spokes, comprehensive authority |

---

## Internal Link Matrix

```
PILLAR ←→ All 6 spoke posts (mandatory bidirectional)

Within Cluster 1 (Foundational):
  1.1 (What is) ↔ 1.2 (vs Back Office)

Within Cluster 2 (Decision):
  2.1 (vs In-House) ↔ 2.2 (Signs You Need Help)

Within Cluster 3 (Commercial):
  3.1 (Providers) ↔ 3.2 (Cost)

Cross-Cluster:
  1.2 (vs Back Office) → 2.1 (vs In-House decision)
  2.1 (vs In-House) → 3.1 (Providers if outsourcing)
  2.2 (Signs) → 3.2 (Cost justification)
  3.1 (Providers) → EXISTING pillar (investment operations outsourcing)

Cross-Pillar (to existing cluster):
  Pillar → /blog/investment-operations-outsourcing-guide (related pillar)
  1.1 (What is) → /blog/what-is-investment-operations-outsourcing
```

---

## Link Matrix (JSON)

```json
{
  "links": [
    {"from": "pillar", "to": "1.1", "type": "mandatory", "anchor": "what is middle office"},
    {"from": "pillar", "to": "1.2", "type": "mandatory", "anchor": "middle office vs back office"},
    {"from": "pillar", "to": "2.1", "type": "mandatory", "anchor": "outsourcing vs in-house"},
    {"from": "pillar", "to": "2.2", "type": "mandatory", "anchor": "signs you need help"},
    {"from": "pillar", "to": "3.1", "type": "mandatory", "anchor": "top providers"},
    {"from": "pillar", "to": "3.2", "type": "mandatory", "anchor": "cost guide"},
    {"from": "1.1", "to": "pillar", "type": "mandatory", "anchor": "middle office outsourcing"},
    {"from": "1.1", "to": "1.2", "type": "cluster", "anchor": "back office differences"},
    {"from": "1.2", "to": "pillar", "type": "mandatory", "anchor": "middle office outsourcing"},
    {"from": "1.2", "to": "1.1", "type": "cluster", "anchor": "what is middle office"},
    {"from": "1.2", "to": "2.1", "type": "cross", "anchor": "outsource vs keep in-house"},
    {"from": "2.1", "to": "pillar", "type": "mandatory", "anchor": "middle office outsourcing"},
    {"from": "2.1", "to": "2.2", "type": "cluster", "anchor": "signs you need help"},
    {"from": "2.1", "to": "3.1", "type": "cross", "anchor": "evaluate providers"},
    {"from": "2.2", "to": "pillar", "type": "mandatory", "anchor": "middle office outsourcing"},
    {"from": "2.2", "to": "2.1", "type": "cluster", "anchor": "outsourcing decision"},
    {"from": "2.2", "to": "3.2", "type": "cross", "anchor": "cost justification"},
    {"from": "3.1", "to": "pillar", "type": "mandatory", "anchor": "middle office outsourcing"},
    {"from": "3.1", "to": "3.2", "type": "cluster", "anchor": "pricing models"},
    {"from": "3.2", "to": "pillar", "type": "mandatory", "anchor": "middle office outsourcing"},
    {"from": "3.2", "to": "3.1", "type": "cluster", "anchor": "compare providers"}
  ]
}
```

---

## Intent Classification

| Post | Primary Intent | Secondary Intent |
|------|---------------|------------------|
| Pillar | Informational | Commercial |
| 1.1 What is Middle Office | Informational | - |
| 1.2 vs Back Office | Informational | - |
| 2.1 vs In-House | Commercial | Informational |
| 2.2 Signs You Need Help | Informational | Commercial |
| 3.1 Providers | Commercial | - |
| 3.2 Cost | Commercial | Transactional |

---

## AEO/GEO Optimization

All posts will include:

- [ ] AI-citation ready definition in first 60 words (134-167 words max)
- [ ] Question-based H2 headings for PAA extraction
- [ ] Comparison tables (clean HTML, no images in tables)
- [ ] FAQ sections with 40-60 word answers
- [ ] Statistics with attribution (market size, adoption rates)
- [ ] "2026" freshness signals in titles where appropriate
- [ ] Schema markup: Article, FAQPage, and relevant structured data

**Target AI Citation Probability:**
| Platform | Target |
|----------|--------|
| Google AI Overviews | 75%+ |
| ChatGPT | 80%+ |
| Perplexity | 75%+ |

---

## Competitor Gap Analysis

| Competitor | Strengths | Gaps Anchor Can Fill |
|------------|-----------|---------------------|
| Limina | Comprehensive guide, good structure | Generic, not mid-market focused |
| Empaxis | Good provider comparison | Tech-focused, not outcome-focused |
| Alpha FMC | Thought leadership | Enterprise-only perspective |
| SEI | Authority, market leader | Too institutional for emerging managers |
| IQ-EQ | Service-focused | Provider page, not educational |

**Anchor's Differentiation:**
- Mid-market focus ($50M-$500M AUM)
- Outcome-oriented ("we do the work")
- Practical, operator perspective (not vendor pitch)

---

## Notes

### Connection to Existing Cluster

This cluster links to the existing "Investment Operations Outsourcing" cluster:
- Middle office outsourcing is a subset of investment operations
- Cross-link the pillars bidirectionally
- Reference existing content where relevant

### Keywords NOT Included (Future Expansion)

These keywords have search volume but warrant separate clusters:
- "back office outsourcing" — separate cluster
- "fund administration outsourcing" — separate cluster
- "trade reconciliation outsourcing" — workflow-specific content
- "compliance outsourcing" — regulatory focus

---

## Next Step

Generate content briefs: Run `/seo cluster execute` or create briefs manually in `cluster-briefs/`

---

## Sources

- [Limina - Guide to Middle Office Outsourcing](https://www.limina.com/blog/guide-middle-office-outsourcing)
- [Alpha FMC - Rethinking the Future of Middle Office](https://alphafmc.com/blog/2025/07/11/rethinking-the-future-of-middle-office-outsource-insource-or-a-hybrid/)
- [Empaxis - Top Middle-Office Outsourcing Providers](https://www.empaxis.com/blog/top-middle-office-outsourcing-providers)
- [Sia Partners - Middle Office Outsourcing for Mid-Sized Asset Managers](https://www.sia-partners.com/en/insights/publications/middle-office-outsourcing-mid-sized-asset-managers)
- [SEI - Investment Operations Outsourcing](https://www.seic.com/asset-managers/what-we-do/investment-operations-outsourcing-middle-office)
- [Data Bridge Market Research - Middle Office Outsourcing Market](https://www.databridgemarketresearch.com/reports/global-middle-office-outsourcing-market)
- [AIMA - The Rise of Middle Office](https://www.aima.org/article/the-rise-of-middle-office-a-new-era-of-efficiency-and-growth.html)
