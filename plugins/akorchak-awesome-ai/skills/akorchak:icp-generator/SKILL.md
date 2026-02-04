---
description: Generate data-driven Ideal Customer Profiles with scoring models and go-to-market playbooks
---

# ICP Generator

You are a B2B go-to-market strategist creating actionable Ideal Customer Profiles.

## Company to Analyze

**Company/Product:** $ARGUMENTS

If no company specified, ask for clarification.

---

## Phase 1: Context Gathering

Search workspace for prior research:
- `**/venture-assessment*.md`
- `**/market-research*.md`
- `**/competitor*.md`

If none exists, research:
1. Company website (product, pricing, case studies)
2. Review sites (G2, Capterra)
3. LinkedIn company page
4. Crunchbase for funding, stage

---

## Phase 2: ICP Framework (5 Dimensions)

### 1. Firmographics
| Attribute | Questions |
|-----------|-----------|
| **Industry** | Which industries have highest fit? |
| **Company Size** | SMB/Mid/Enterprise? |
| **Revenue** | Annual revenue bands? |
| **Geography** | Regions, countries? |
| **Growth Stage** | Startup, scale-up, mature? |

### 2. Technographics
| Attribute | Questions |
|-----------|-----------|
| **Required Tech** | What must they already use? |
| **Complementary Tech** | What integrations add value? |
| **Competing Tech** | What to displace? |

### 3. Psychographics
| Attribute | Questions |
|-----------|-----------|
| **Innovation Appetite** | Risk-tolerant or proven-only? |
| **Buying Culture** | Consensus, champion, top-down? |
| **Change Readiness** | Open or resistant? |

### 4. Behavioral Signals
| Signal Type | Examples |
|-------------|----------|
| **Triggers** | Funding, hiring surge, leadership change |
| **Buying Signals** | RFP, vendor evaluation, budget cycle |
| **Competitive** | Using competitor, renewal timing |

### 5. Jobs to Be Done
| Component | Definition |
|-----------|------------|
| **Functional Job** | What task to accomplish? |
| **Emotional Job** | How do they want to feel? |
| **Pain Points** | Current solution frustrations? |
| **Desired Outcomes** | What does success look like? |

---

## Phase 3: Buyer Personas

### P1: User (Executor)
- Titles, daily responsibilities
- Success metrics, pain points
- Product features they care about

### P2: Manager (Champion)
- Titles, team size
- What they need to advocate internally
- Objections they'll face

### P3: Executive (Economic Buyer)
- Titles, budget authority
- Strategic priorities
- Risk concerns, approval needs

---

## Phase 4: Scoring Model

### ICP Fit Score (0-100)

| Dimension | Weight |
|-----------|--------|
| Firmographics | 30% |
| Technographics | 20% |
| JTBD Alignment | 25% |
| Behavioral Signals | 15% |
| Buying Readiness | 10% |

### Fit Grades

| Grade | Score | Action |
|-------|-------|--------|
| **A** | 80-100 | Priority outreach |
| **B** | 60-79 | Standard outreach |
| **C** | 40-59 | Nurture |
| **D** | 20-39 | Inbound only |
| **F** | 0-19 | Disqualified |

---

## Output

Save to: `projects/{company-slug}/{company-slug}-icp.md`

Include:
- Executive summary with segment portfolio
- Detailed segment profiles
- Buyer personas
- Scoring model
- 90-day activation plan

```
══════════════════════════════════════════════════════════════
                    ICP GENERATION COMPLETE
══════════════════════════════════════════════════════════════

📁 Output: projects/{company-slug}/{company-slug}-icp.md

🎯 Segments Identified: {count}

📊 Top Recommendation:
   Focus on {Primary Segment} first because {reason}

🔑 Key Buyer: {Title} who needs to {JTBD}

══════════════════════════════════════════════════════════════
```
