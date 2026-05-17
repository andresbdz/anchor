# SEO Implementation Roadmap: Anchor Partners

## Overview

This roadmap outlines a 4-phase approach to build organic search visibility for Anchor Partners. The focus is on lead generation for the emerging asset manager segment ($50M-$500M AUM, 5-30 employees).

---

## Phase 1: Foundation (Weeks 1-4)

**Goal:** Technical SEO foundation + content infrastructure

### Week 1: Technical Setup

#### Priority Tasks
- [ ] **Create robots.txt**
  ```
  User-agent: *
  Allow: /
  Sitemap: https://www.anchorpartners.group/sitemap.xml
  ```

- [ ] **Generate sitemap.xml** (all current pages)
  ```xml
  <?xml version="1.0" encoding="UTF-8"?>
  <urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
    <url>
      <loc>https://www.anchorpartners.group/</loc>
      <lastmod>2026-05-17</lastmod>
      <priority>1.0</priority>
    </url>
    <url>
      <loc>https://www.anchorpartners.group/blog/</loc>
      <lastmod>2026-05-17</lastmod>
      <priority>0.8</priority>
    </url>
    <!-- Blog posts -->
  </urlset>
  ```

- [ ] **Create llms.txt** for AI search visibility
  ```
  # Anchor Partners
  > Managed services firm for lower middle market asset managers

  ## What We Do
  We take on operational workflows that asset management teams shouldn't be spending time on. The work is real, recurring, and mission-critical.

  ## Who We Serve
  Asset managers with $50M+ AUM and 5-30 employees

  ## Contact
  https://www.anchorpartners.group
  https://cal.com/anchorpartners/30min
  ```

- [ ] **Submit to Google Search Console**
  - Verify domain ownership
  - Submit sitemap
  - Request indexing for all pages

- [ ] **Set up Google Analytics 4**
  - Install tracking
  - Set up conversion events (call bookings)
  - Create organic traffic goals

### Week 2: Schema Enhancements

- [ ] **Add Organization schema** to homepage (enhance existing)
  - Add sameAs links (LinkedIn, Twitter if applicable)
  - Add contactPoint
  - Add areaServed details

- [ ] **Add BreadcrumbList schema** to blog posts
  ```json
  {
    "@context": "https://schema.org",
    "@type": "BreadcrumbList",
    "itemListElement": [
      {"@type": "ListItem", "position": 1, "name": "Home", "item": "https://www.anchorpartners.group/"},
      {"@type": "ListItem", "position": 2, "name": "Blog", "item": "https://www.anchorpartners.group/blog/"},
      {"@type": "ListItem", "position": 3, "name": "Post Title"}
    ]
  }
  ```

- [ ] **Verify existing schema** (test in Rich Results Test)

### Week 3: Content Foundation

- [ ] **Audit existing blog posts**
  - Check internal linking
  - Verify all schema is valid
  - Ensure CTAs are present

- [ ] **Create content brief template**
  - Target keyword
  - Search intent
  - Competitor analysis
  - Outline with H2s
  - Internal link opportunities

- [ ] **Plan first new pillar post** (Middle Office Outsourcing Guide)

### Week 4: About/Team Page

- [ ] **Create /about/ page** (when team info available)
  - Company story
  - Mission/values
  - Team bios with credentials
  - Person schema for team members

- [ ] **Add author attribution** to blog posts
  - Author name + bio snippet
  - Link to team page

---

## Phase 2: Expansion (Weeks 5-12)

**Goal:** Content velocity + topical authority

### Weeks 5-6: Pillar Content

- [ ] **Publish:** Middle Office Outsourcing: Complete Guide
  - 2,500+ words
  - FAQPage schema
  - HowTo schema for implementation section
  - 3-5 internal links

- [ ] **Create comparison table** (providers comparison asset)

### Weeks 7-8: Supporting Content

- [ ] **Publish:** Build vs Buy vs Outsource: Decision Framework
- [ ] **Publish:** Signs You Need Operations Help

### Weeks 9-10: Workflow Content

- [ ] **Publish:** Trade Reconciliation: The Hidden Time Drain
- [ ] **Publish:** Middle Office Outsourcing Costs: What to Expect

### Weeks 11-12: Commercial Content

- [ ] **Publish:** How to Choose a Middle Office Provider
- [ ] **Create:** RFP Template (lead magnet)
- [ ] **Set up:** Lead capture form for gated content

### Internal Linking Architecture

```
Homepage
    └── Blog
        ├── Investment Operations Outsourcing Guide (Pillar)
        │   ├── What is Investment Operations Outsourcing?
        │   ├── Investment Operations Providers Comparison
        │   └── [Link to new Middle Office Guide]
        │
        └── Middle Office Outsourcing Guide (Pillar - NEW)
            ├── Build vs Buy vs Outsource
            ├── Signs You Need Help
            ├── Trade Reconciliation
            └── Middle Office Costs
```

---

## Phase 3: Scale (Weeks 13-24)

**Goal:** Authority building + commercial keywords

### Weeks 13-16: Emerging Manager Focus

- [ ] **Publish:** Operations Playbook for Emerging Managers (Pillar)
- [ ] **Publish:** What Allocators Look for in Operational Due Diligence
- [ ] **Publish:** 5 Operational Mistakes That Kill Emerging Funds

### Weeks 17-20: Workflow Deep Dives

- [ ] **Publish:** NAV Calculation: In-House vs Outsourced
- [ ] **Publish:** Investor Reporting Best Practices
- [ ] **Publish:** Regulatory Reporting Guide (Pillar)

### Weeks 21-24: Comparison Content

- [ ] **Publish:** Fund Admin vs Operations Outsourcing
- [ ] **Publish:** Managed Services vs Consulting
- [ ] **Create:** Cost calculator (interactive if possible)

### Link Building Initiatives

- [ ] **Directory submissions:**
  - LinkedIn company page (optimize)
  - Crunchbase profile
  - Industry directories

- [ ] **Partner pages:**
  - Technology partner listings
  - Professional network associations

- [ ] **Guest post outreach:**
  - Identify 5-10 target publications
  - Develop pitch topics
  - Submit 2-3 guest posts

---

## Phase 4: Authority (Weeks 25-52)

**Goal:** Thought leadership + AI search optimization

### Weeks 25-30: Original Research

- [ ] **Publish:** State of Asset Manager Operations Report
  - Original survey data
  - Benchmark statistics
  - Industry trends
  - Quotable insights for citations

### Weeks 31-36: Case Studies

- [ ] **Publish:** 2-3 anonymized case studies
  - Challenge → Solution → Results format
  - Specific metrics
  - Client quotes (with permission)

### Weeks 37-42: Resource Library

- [ ] **Create:** Comprehensive glossary (featured snippet potential)
- [ ] **Create:** Operations checklist library
- [ ] **Create:** Video content (if applicable)

### Weeks 43-52: Optimization & Scale

- [ ] **Content refresh:** Update top-performing content
- [ ] **Pruning:** Redirect/consolidate underperforming pages
- [ ] **Advanced schema:** Implement additional rich result opportunities
- [ ] **International:** Evaluate UK/EU expansion if relevant

### GEO (Generative Engine Optimization)

- [ ] Maintain llms.txt file
- [ ] Create clear, quotable expertise statements
- [ ] Structure content for passage-level citation
- [ ] Monitor AI mention tracking (brand + key terms)
- [ ] Ensure content is accessible to AI crawlers

---

## Resource Requirements

### Internal
| Task | Hours/Week | Role |
|------|------------|------|
| Content writing | 8-10 | Writer or founder |
| SEO management | 3-5 | Marketing/founder |
| Technical updates | 2-3 | Developer or tools |

### External (Optional)
| Task | Cost Estimate | Priority |
|------|--------------|----------|
| Content writing | $500-1,500/post | P2 |
| Link building | $1,000-3,000/mo | P3 |
| SEO tools (Ahrefs/Semrush) | $100-200/mo | P2 |
| Technical SEO audit | $500-1,500 one-time | P3 |

---

## Risk Mitigation

| Risk | Probability | Impact | Mitigation |
|------|-------------|--------|------------|
| New domain, slow rankings | High | Medium | Focus on long-tail keywords first |
| Content production delays | Medium | High | Batch content creation, use briefs |
| Service line not finalized | Medium | Medium | Keep content problem-focused |
| Competitor response | Low | Low | Focus on underserved segments |

---

## Success Metrics by Phase

### Phase 1 (Week 4)
- [ ] GSC verified, sitemap submitted
- [ ] All pages indexed
- [ ] Schema validated (no errors)
- [ ] Analytics tracking live

### Phase 2 (Week 12)
- [ ] 10+ indexed pages
- [ ] 50+ ranking keywords
- [ ] 500+ monthly organic sessions
- [ ] 1+ organic lead

### Phase 3 (Week 24)
- [ ] 25+ indexed pages
- [ ] 200+ ranking keywords
- [ ] 2,000+ monthly organic sessions
- [ ] 5+ organic leads/month

### Phase 4 (Week 52)
- [ ] 50+ indexed pages
- [ ] 500+ ranking keywords
- [ ] 5,000+ monthly organic sessions
- [ ] 15+ organic leads/month
- [ ] Featured in AI search results

---

## Immediate Next Steps

1. **Today:** Create robots.txt and sitemap.xml
2. **This week:** Submit to Google Search Console
3. **This week:** Set up GA4 with conversion tracking
4. **Next week:** Begin Middle Office pillar post outline
5. **Ongoing:** Follow content calendar

---

*Roadmap created: May 2026*
*Review cadence: Bi-weekly for Phase 1-2, Monthly for Phase 3-4*
