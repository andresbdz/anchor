# Anchor Partners SEO Strategy

---

## Content Creation Workflow

> **IMPORTANT:** This is the canonical workflow for creating new content clusters. Always follow this order.

### Step 1: Check SEO-STRATEGY.md First
Before starting any new cluster, check the **Keyword Strategy** section below for validated keywords.
- Use SEMrush/Ahrefs validated data only
- Do NOT run fresh keyword discovery if data already exists here
- If keywords are missing, validate in SEMrush first, then add to this doc

### Step 2: Run /seo-cluster for Architecture
Use the cluster skill to:
- Validate SERP overlap between keywords (which can share a page)
- Design hub-and-spoke structure
- Create internal link matrix
- **Input:** Keywords FROM this strategy doc
- **Output:** `clusters/[name]/plan.md`, `plan.json`, `cluster-map.html`

### Step 3: Run /seo-content-brief for Each Post
Generate detailed briefs with:
- Validated keywords from Step 1
- AEO (Answer Engine Optimization) requirements
- Competitor gap analysis
- **Output:** `clusters/[name]/briefs/*.md`

### Step 4: Update CONTENT-CALENDAR.md
Add the new cluster posts to the publishing schedule with:
- Target publish dates
- Status tracking
- Word counts

### Step 5: Write Content
Follow the briefs exactly, including:
- Keyword placement rules
- AEO-optimized definitions (first 50-60 words)
- FAQ schema content
- Internal links

### File Structure
```
SEO-STRATEGY.md          ← Master keywords + strategy (START HERE)
CONTENT-CALENDAR.md      ← Publishing schedule
clusters/
├── [cluster-name]/
│   ├── plan.md          ← Cluster architecture
│   ├── plan.json        ← Machine-readable plan
│   ├── cluster-map.html ← Visual map
│   ├── scorecard.md     ← Post-publish metrics
│   └── briefs/
│       ├── 01-pillar-*.md
│       ├── 02-*.md
│       └── ...
```

---

## Executive Summary

**Business:** Anchor Partners — Managed services firm for lower middle market asset managers ($50M+ AUM, 5-30 employees)

**Primary Goal:** Lead generation through organic search

**Target Audience:** COOs, CFOs, Directors of Operations at boutique/emerging asset managers who need operational support but lack scale for dedicated internal teams

**Core Positioning Opportunity:** Most competitors position as "platforms," "fund administrators," or "consultants." Anchor's "we do the work, you get the outcome" positioning is underrepresented in organic search.

---

## Current State Assessment

### Site Structure (Live)
```
/                                    (Homepage - good SEO foundation)
/blog/                               (Blog index)
├── Investment Operations Cluster (3 posts)
│   /blog/investment-operations-outsourcing-guide.html      (Pillar)
│   /blog/investment-operations-outsourcing-providers.html  (Supporting)
│   /blog/what-is-investment-operations-outsourcing.html    (Supporting)
│
└── Middle Office Cluster (7 posts) ✅ NEW
    /blog/middle-office-outsourcing-guide.html              (Pillar)
    /blog/middle-office-outsourcing-providers.html          (Supporting)
    /blog/middle-office-outsourcing-cost.html               (Supporting)
    /blog/middle-office-outsourcing-vs-in-house.html        (Supporting)
    /blog/signs-you-need-middle-office-help.html            (Supporting)
    /blog/middle-office-vs-back-office.html                 (Supporting)
    /blog/what-is-middle-office.html                        (Supporting)
```

### Strengths
- Clean, fast single-page design
- ProfessionalService schema implemented on homepage
- Article + HowTo + FAQPage schema on pillar blog post
- Clear value proposition and strong messaging
- Domain: anchorpartners.group (brandable, professional)

### Gaps
- No dedicated service pages (once services are defined)
- No team/about page (E-E-A-T signal)
- No case studies with full narratives
- Limited backlink profile (new domain)
- ~~No sitemap.xml detected~~ ✅ Created
- ~~Missing robots.txt~~ ✅ Created (with AI crawler directives)

---

## Competitive Landscape

### Tier 1: Enterprise Providers (Not Direct Competitors)
| Provider | Focus | SEO Strength |
|----------|-------|--------------|
| [Northern Trust](https://www.northerntrust.com) | $1B+ AUM, institutional | Very Strong |
| [SEI](https://www.seic.com) | $500M+ AUM, platform-based | Very Strong |
| [State Street](https://www.statestreet.com) | Enterprise, custodial | Very Strong |
| [BNY Mellon](https://www.bnymellon.com) | Enterprise, multi-service | Very Strong |

### Tier 2: Mid-Market Competitors (Partial Overlap)
| Provider | Focus | SEO Strength |
|----------|-------|--------------|
| [SS&C/Advent](https://www.ssctech.com) | $100M-$5B AUM, platform + services | Strong |
| [IQ-EQ](https://iqeq.com) | $50M-$1B, fund admin + middle office | Moderate |
| [Apex Fund Services](https://www.apexgroup.com) | $50M-$2B, growing independent | Moderate |
| [Linedata](https://www.linedata.com) | APAC focus, hedge funds | Moderate |

### Tier 3: Direct Competitors (Boutique Focus)
| Provider | Focus | SEO Strength |
|----------|-------|--------------|
| [Consero Global](https://conseroglobal.com) | Emerging managers, FaaS | Strong (active blog) |
| [OSMO Partners](https://www.osmopartners.com) | Hedge fund ops outsourcing | Moderate |
| [NAV Fund Services](https://www.navfundservices.com) | Emerging managers | Moderate |
| [Empaxis](https://www.empaxis.com) | Middle office outsourcing | Strong (content hub) |

### Key Insight
The **$50M-$500M AUM segment** is underserved in search. Enterprise players don't target it specifically. Boutique providers exist but lack the "managed services" positioning. Anchor can own this keyword territory.

---

## Keyword Strategy

> ⚠️ **Note:** Validate keywords with SEMrush/Ahrefs before prioritizing new clusters.

### Primary Keywords (High Intent, Lead Generation)
| Keyword | Volume | KD | CPC | Source |
|---------|--------|-----|-----|--------|
| back office outsourcing | 1,300 | 12 | $16.94 | ✅ SEMrush May 2026 |
| back office outsourcing services | 720 | 6 | $32.73 | ✅ SEMrush May 2026 |
| back office outsourcing companies | 480 | 22 | $37.64 | ✅ SEMrush May 2026 |
| middle office outsourcing | TBD | TBD | TBD | ✅ SEMrush (has volume) |
| investment operations outsourcing | 200-500 | Medium | — | ❌ Estimated |
| fund operations outsourcing | 100-200 | Low-Med | — | ❌ Estimated |

### Asset Management Specific Keywords
| Keyword | Volume | KD | CPC | Source |
|---------|--------|-----|-----|--------|
| private equity back office outsourcing | 70 | 0 | — | ✅ SEMrush May 2026 |
| asset management back office outsourcing | 50 | 1 | — | ✅ SEMrush May 2026 |
| ria back office outsourcing | 50 | 0 | $22.56 | ✅ SEMrush May 2026 |
| hedge fund back office outsourcing | 20 | — | — | ✅ SEMrush May 2026 |

### Long-Tail Keywords (Bottom-of-Funnel)
| Keyword | Volume | KD | Source |
|---------|--------|-----|--------|
| back office outsourcing solutions | 110 | 11 | ✅ SEMrush |
| outsourcing back office operations | 260 | 10 | ✅ SEMrush |
| small business back office outsourcing | 210 | 1 | ✅ SEMrush |
| back office vs middle office | 140 | — | ✅ SEMrush May 2026 |
| back office outsourcing benefits | 30 | 6 | ✅ SEMrush |
| back office outsourcing vs in-house | 30 | — | ✅ SEMrush May 2026 |
| what is back office outsourcing | 20 | — | ✅ SEMrush |

### Branded Keywords (Future)
- anchor partners asset management
- anchor partners reviews
- anchor partners vs [competitor]

---

## Content Strategy

### Content Pillars

#### Pillar 1: Investment Operations Outsourcing (LIVE)
- **Pillar:** Investment Operations Outsourcing: Complete Guide [2026] ✅
- **Supporting:** What is Investment Operations Outsourcing? ✅
- **Supporting:** Top Investment Operations Outsourcing Providers ✅
- **Needed:** Investment Operations Outsourcing Cost Calculator (interactive)
- **Needed:** Investment Operations Outsourcing RFP Template (lead magnet)

#### Pillar 2: Middle Office Outsourcing ✅ COMPLETE
- **Pillar:** Middle Office Outsourcing: Complete Guide [2026] ✅
- **Supporting:** What is Middle Office in Asset Management? ✅
- **Supporting:** Middle Office vs Back Office: Key Differences ✅
- **Supporting:** Signs You Need Middle Office Help ✅
- **Supporting:** Middle Office Outsourcing vs In-House ✅
- **Supporting:** Middle Office Outsourcing Cost ✅
- **Supporting:** Top Middle Office Outsourcing Providers ✅

#### Pillar 3: Back Office Outsourcing ✅ COMPLETE
- **Pillar:** Back Office Outsourcing: Complete Guide for Asset Managers ✅
- **Supporting:** What is Back Office in Asset Management? ✅
- **Supporting:** Back Office vs Middle Office vs Front Office ✅
- **Supporting:** Back Office Outsourcing Cost ✅
- **Supporting:** Back Office Outsourcing vs In-House ✅
- **Supporting:** Top Back Office Outsourcing Companies ✅
- **Total Volume:** 3,490+ (validated SEMrush May 2026)
- **Published:** May 18, 2026

#### Pillar 4: Emerging Manager Operations 🔲 PLANNED
- **Pillar:** Operational Best Practices for Emerging Managers
- **Supporting:** How to Build an Operating Model Under $500M AUM
- **Supporting:** Common Operational Mistakes New Funds Make
- **Supporting:** Investor Due Diligence: Operations Checklist

#### Pillar 5: Specific Workflow Content (After Service Line Decided)
- Trade reconciliation automation
- NAV calculation outsourcing
- Investor reporting solutions
- Compliance workflow optimization

### Content Types & Frequency

| Content Type | Frequency | Purpose |
|--------------|-----------|---------|
| In-depth guides (2,000+ words) | 1/month | SEO pillar, authority |
| How-to articles (1,000-1,500 words) | 2/month | Long-tail keywords |
| Comparison posts | 1/month | Bottom-funnel, commercial |
| Case studies | 1/quarter | E-E-A-T, conversion |
| Glossary/definitions | As needed | Featured snippets |

---

## Technical SEO Priorities

### Immediate (Phase 1) ✅ COMPLETE
- [x] Create robots.txt with sitemap reference (includes AI crawler directives)
- [x] Generate XML sitemap (sitemap.xml) — 10 blog posts indexed
- [x] Add breadcrumb schema to blog posts
- [x] Create llms.txt for AI search visibility
- [x] Verify Core Web Vitals (passing)

### Short-Term (Phase 2)
- [x] Add Organization schema with sameAs links (LinkedIn, etc.)
- [x] Implement BreadcrumbList schema on all pages
- [ ] Add author/Person schema for team members (when added)
- [ ] Create /about page with team bios

### Medium-Term (Phase 3) ✅ COMPLETE
- [x] Add FAQ schema to relevant blog posts (all 10 posts)
- [x] Implement HowTo schema where applicable (pillar posts)
- [ ] Add Service schema to service pages (when created)
- [x] Create comparison page schema (ItemList for providers)

---

## Site Architecture Recommendations

### Target Structure (Once Services Defined)
```
/                                    Homepage
├── /services/                       Services overview
│   ├── /services/[service-1]/       Individual service
│   └── /services/[service-2]/       Individual service
├── /about/                          About Anchor Partners
│   ├── /about/team/                 Team page
│   └── /about/process/              How we work
├── /case-studies/                   Case studies index
│   └── /case-studies/[study]/       Individual case study
├── /blog/                           Blog index
│   └── /blog/[post]/                Individual posts
├── /resources/                      Lead magnets, tools
│   ├── /resources/cost-calculator/  ROI calculator
│   └── /resources/rfp-template/     Download gated content
└── /contact/                        Contact page
```

### URL Guidelines
- Use hyphens, not underscores
- Keep URLs short and descriptive
- Include primary keyword where natural
- No dates in blog URLs (evergreen)

---

## Link Building Strategy

### Phase 1: Foundation
1. **Directory Listings**
   - LinkedIn company page
   - Crunchbase profile
   - Industry directories (HFM, AIMA member directories)

2. **Partner/Vendor Links**
   - Technology partners
   - Prime broker/custodian partner pages

### Phase 2: Content-Driven
1. **Guest Posts**
   - HFM Week, Institutional Investor
   - Industry association blogs (AIMA, MFA)

2. **Original Research**
   - Survey of emerging manager operations
   - Benchmark data on ops costs

### Phase 3: PR/Authority
1. **Speaking Engagements**
   - Industry conferences
   - Webinar series

2. **Media Mentions**
   - Expert quotes in industry publications
   - Bylined articles

---

## KPI Targets

| Metric | Baseline | 3 Month | 6 Month | 12 Month |
|--------|----------|---------|---------|----------|
| Organic Sessions | 0 | 200 | 1,000 | 5,000 |
| Indexed Pages | 5 | 15 | 30 | 50 |
| Ranking Keywords | 0 | 50 | 150 | 400 |
| Top 10 Rankings | 0 | 5 | 20 | 50 |
| Organic Leads/month | 0 | 1 | 5 | 15 |
| Avg Position (target KWs) | N/A | 50 | 25 | 10 |
| Domain Authority | 0 | 5 | 15 | 25 |

---

## Risk Factors & Mitigation

| Risk | Impact | Mitigation |
|------|--------|------------|
| New domain, no authority | High | Focus on long-tail keywords first, build links |
| Service offering not finalized | Medium | Keep content at problem/outcome level |
| Enterprise competitors dominate | Medium | Target underserved emerging manager segment |
| Limited internal resources | Medium | Prioritize high-impact pages first |

---

## Success Criteria

**3-Month Milestone:**
- Blog generating organic traffic
- Ranking for 3+ long-tail keywords
- Technical foundation complete

**6-Month Milestone:**
- 1,000+ monthly organic sessions
- Top 10 for "investment operations outsourcing" long-tail variants
- 5+ organic lead inquiries

**12-Month Milestone:**
- 5,000+ monthly organic sessions
- Authority in emerging manager operations segment
- 15+ organic leads/month
- Featured in AI search results (ChatGPT, Perplexity, AI Overviews)

---

## Next Steps

1. ~~**Immediate:** Create sitemap.xml and robots.txt~~ ✅ Done
2. **This Week:** Submit sitemap to Google Search Console
3. **This Week:** Add About/Team page content (when available)
4. **Next:** Trade Reconciliation post (Month 2)
5. **Next:** Emerging Manager Operations pillar (Month 3)
6. **Ongoing:** Monthly content cadence per strategy above

---

## Progress Summary

| Metric | Target (3mo) | Current |
|--------|--------------|---------|
| Indexed Pages | 15 | 16 |
| Blog Posts (Live) | — | 16 |
| Blog Posts (Briefed) | — | 0 |
| Content Clusters | — | 3 complete |
| Total Words (Live) | — | ~27,000 |
| Keyword Volume (Targeted) | — | 3,490+ (back office cluster) |

---

*Strategy created: May 2026*
*Last updated: May 18, 2026*
*Review cadence: Monthly*
