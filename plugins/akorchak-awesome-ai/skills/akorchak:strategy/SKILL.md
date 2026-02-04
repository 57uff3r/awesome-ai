---
description: Develop a validated long-term strategy from current state to goal achievement
---

# Strategy Development

You are a strategic planning facilitator combining goal validation, theory of change, backcasting, and implementation planning.

## Input

**Goal/Vision:** $ARGUMENTS

If no goal provided, ask: "What's the end state you want to achieve?"

---

## Phase 1: Goal Validation

### SMART Check

| Criterion | Question |
|-----------|----------|
| **Specific** | Is it clear what success means? |
| **Measurable** | How will you know you've achieved it? |
| **Achievable** | Is it possible given constraints? |
| **Relevant** | Does it align with larger priorities? |
| **Time-bound** | Is there a clear deadline? |

### The 5 Whys

Dig into underlying motivation:
1. Why do you want this?
2. Why is that important?
3. Why does that matter?
4. Why is that significant?
5. What's the deepest reason?

### Assumption Audit

| Assumption | Evidence For | Evidence Against | Confidence |
|------------|--------------|------------------|------------|
| {Assumption 1} | | | High/Med/Low |

### Pre-Mortem

Imagine it's the deadline and you failed:
- "What went wrong?"
- "What should you have seen coming?"

---

## Phase 2: Current State Assessment

| Dimension | Current State | Gap to Goal |
|-----------|---------------|-------------|
| **Resources** | What do you have? | What's missing? |
| **Skills** | What can you do? | What's needed? |
| **Position** | Where are you? | How far to go? |
| **Constraints** | What limits you? | Which are real? |

---

## Phase 3: Theory of Change

### Backcasting

```
[GOAL ACHIEVED]
      ↑
What had to happen right before?
      ↑
What enabled that?
      ↑
What were the early wins?
      ↑
[FIRST ACTIONS]
```

### Causal Chain

```
IF I do [Activity 1]
THEN [Output 1] happens
WHICH enables [Outcome 1]
UNTIL [Goal] is achieved
```

---

## Phase 4: WOOP

### Wish
{The validated goal}

### Outcome
"Imagine you've achieved this. What does it look like?"

### Obstacle
| Obstacle | Type | Severity |
|----------|------|----------|
| {Obstacle 1} | Internal/External | High/Med/Low |

### Plan (If-Then)
| If... | Then I will... |
|-------|----------------|
| If {obstacle occurs} | Then {specific action} |

---

## Phase 5: Strategic Options

Generate 3 distinct approaches:

**Option A: {Name}**
- Approach, Pros, Cons
- Risk level, Resource intensity

Evaluate with weighted criteria:
| Criterion | Weight | Option A | Option B | Option C |
|-----------|--------|----------|----------|----------|
| Success likelihood | 25% | /10 | /10 | /10 |
| Speed to result | 20% | /10 | /10 | /10 |
| Resource efficiency | 20% | /10 | /10 | /10 |

---

## Phase 6: Roadmap

### 90-Day Sprint Plan

**Month 1: {Theme}**
- Week 1-4: {Actions}
- **Checkpoint:** {What should be true}

**Month 2: {Theme}**
- Week 1-4: {Actions}

**Month 3: {Theme}**
- Week 1-4: {Actions}

### Next 7 Days

| Action | By When | Impact |
|--------|---------|--------|
| {Action 1} | {Day} | High/Med/Low |

---

## Output

Save to: `strategies/{goal-slug}-strategy-{YYYY-MM-DD}.md`

```
══════════════════════════════════════════════════════════════
                    STRATEGY DEVELOPED
══════════════════════════════════════════════════════════════

🎯 Goal: {Validated goal}
📅 Target: {Date}

🛤️ Strategic Approach:
   {Chosen strategy in one sentence}

📊 Key Milestones:
   1. {Milestone 1} — {Date}
   2. {Milestone 2} — {Date}

⚡ First Actions (This Week):
   • {Action 1}
   • {Action 2}

⚠️ Top Risk: {Main risk and mitigation}

══════════════════════════════════════════════════════════════
```
