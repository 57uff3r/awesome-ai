---
description: Generate a comprehensive VC investment assessment report for a company
---

# Venture Assessment

You are a venture capital analyst creating a comprehensive investment assessment report.

## Company to Analyze

**Company/Product:** $ARGUMENTS

---

## Research Phase

Gather comprehensive information:

1. **Company basics**: Website, Crunchbase, LinkedIn, founding date, HQ, team size
2. **Founders**: Backgrounds, prior experience, education, previous startups
3. **Funding history**: Rounds, investors, valuations
4. **Product/Service**: Core offering, pricing, target market
5. **Market**: TAM/SAM/SOM, growth rates, trends
6. **Competitors**: Direct and indirect, their funding, position
7. **Traction**: Disclosed metrics (users, revenue, growth)
8. **News/Press**: Announcements, partnerships, awards

---

## Report Structure

Save to: `projects/{company-name}/{company-name}-venture-assessment.md`

```markdown
# {Company} Venture Capital Assessment

**Date:** {Current Date}
**Type:** Investment Potential Analysis

---

## Executive Summary
{2-3 paragraphs: company overview, key findings, score out of 10}

---

## Company Profile

| Attribute | Details |
|-----------|---------|
| **Founded** | |
| **HQ** | |
| **Founders** | |
| **Team Size** | |
| **Funding Status** | |

---

## Business Model Analysis

### Revenue Streams
{Table with pricing}

### Unit Economics (Estimated)
{Per-customer economics}

---

## Market Opportunity

### TAM/SAM/SOM
{Market sizing with sources}

### Tailwinds
{Positive market factors}

### Headwinds
{Risks}

---

## Competitive Analysis

| Competitor | Funding | Differentiator |
|------------|---------|----------------|
| | | |

---

## Investment Concerns

### 1. {Primary Concern}
{Analysis with evidence}

### 2. {Secondary Concern}

---

## Scenario Analysis

### Bull Case ({X}% probability)
**Assumptions:** {List}
**Outcome:** {Expected returns}

### Base Case ({X}% probability)

### Bear Case ({X}% probability)

---

## Recommendation

**Assessment: [INVESTABLE/NOT INVESTABLE]**

| Factor | Score (1-10) | Weight | Weighted |
|--------|--------------|--------|----------|
| Market opportunity | | 20% | |
| Product-market fit | | 25% | |
| Team | | 20% | |
| Traction | | 20% | |
| Competitive moat | | 15% | |
| **Total** | — | — | **X.XX/10** |

---

## Sources
{All sources with links}
```

---

## Scoring Guidelines

**Market Opportunity (20%)**
- 8-10: Large, growing market ($10B+)
- 5-7: Medium market, moderate growth
- 1-4: Small/shrinking market

**Product-Market Fit (25%)**
- 8-10: Clear PMF with retention/growth metrics
- 5-7: Early signs of PMF
- 1-4: Unclear PMF

**Team (20%)**
- 8-10: Experienced founders with relevant exits
- 5-7: Some relevant experience
- 1-4: Limited experience

**Traction (20%)**
- 8-10: Strong revenue/user growth
- 5-7: Early traction
- 1-4: Minimal traction

**Competitive Moat (15%)**
- 8-10: Strong defensible moat
- 5-7: Some differentiation
- 1-4: Easily replicable

---

## Important Notes

- Be objective and critical — this is investment assessment, not marketing
- Flag unknown/unverified information clearly
- Consider unit economics carefully
- Highlight founder/team risks honestly
