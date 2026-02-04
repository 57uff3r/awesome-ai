---
description: Validate that all marketplace skills are documented in README
---

# Validate Docs

Check that all skills in the marketplace are properly documented in README.md.

## Instructions

1. **Find all skills** in `plugins/akorchak-awesome-ai/skills/` by looking for `SKILL.md` files

2. **Extract skill info** from each SKILL.md frontmatter (`description:` field)

3. **Read README.md** and verify each skill has:
   - [ ] Section header with skill name
   - [ ] Description
   - [ ] Usage example

4. **Output validation report:**

```
══════════════════════════════════════════════════════════════
              MARKETPLACE DOCUMENTATION VALIDATION
══════════════════════════════════════════════════════════════

Skills found: X
Documented:   Y
Missing:      Z

✓ akorchak:thinking-session
  - In README: ✓
  - Description: ✓
  - Usage: ✓

✗ akorchak:new-skill
  - In README: ✗ MISSING

══════════════════════════════════════════════════════════════
```

5. **If issues found**, provide template:

```markdown
### /akorchak:skill-name

**Brief description**

{Detailed explanation}

**Usage:**
\`\`\`
/akorchak:skill-name [arguments]
\`\`\`
```

## Run from repo root
