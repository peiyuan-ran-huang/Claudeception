---
name: [descriptive-kebab-case-name]
description: |
  [REQUIRED: Precise description that enables semantic matching. Include:
  (1) What problem this solves
  (2) Specific trigger conditions - exact error messages, symptoms, scenarios
  (3) Key technologies/frameworks involved
  Use phrases like "Use when:", "Helps with:", "Solves:"]
author: Claude Code
version: 1.0.0
date: YYYY-MM-DD
---

# [Skill Name - Human Readable Title]

## Problem

[Clear, concise description of the problem this skill addresses. 
What pain point does this solve? Why is it non-obvious?]

## Context / Trigger Conditions

[When should this skill be activated? Be specific:]

- [Exact error message 1]
- [Exact error message 2]
- [Observable symptom or behavior]
- [Environmental condition (framework, tool, platform)]

## Solution

[Step-by-step instructions to resolve the problem]

### Step 1: [First Action]

[Detailed instructions with code examples if applicable]

```language
// Example code
```

### Step 2: [Second Action]

[Continue with clear, actionable steps]

### Step 3: [Third Action]

[Include alternatives or variations if relevant]

## Design Rules

[Design principles guiding correct use and future maintenance of this skill.
Answer: "Why is it designed this way? What must not change in future edits?"
For simple skills (single error fix): 1-2 rules suffice.
For complex workflow skills: 3-10 rules covering key design invariants.]

- [Rule 1: Core design principle and rationale]
- [Rule 2: Key invariant that must be preserved]

## Failure Modes

[Known scenarios where this skill may produce incorrect or misleading results.
Answer: "When might this skill give a wrong answer?"
Minimum: 1 starter entry for any new skill; append more as usage reveals new failures.]

- **[Failure mode 1]**: [symptom] → [mitigation]

## Verification

[How to confirm the solution worked:]

1. [Verification step 1]
2. [Verification step 2]
3. [Expected outcome]

## Example

**Scenario**: [Concrete example of when this skill applies]

**Before**:
```
[Error message or problematic code]
```

**After**:
```
[Fixed code or successful output]
```

## Notes

[Important caveats, edge cases, and related considerations:]

- [Caveat 1]
- [Related skill or documentation link]
- [Known limitation]
- [When NOT to use this skill]

---

<!-- 
Extraction Checklist (remove before saving):
- [ ] Name is descriptive and uses kebab-case
- [ ] Description includes specific error messages/symptoms
- [ ] Problem is clearly stated
- [ ] Trigger conditions are specific and searchable
- [ ] Solution is step-by-step and actionable
- [ ] Code examples are complete and tested
- [ ] Verification steps are included
- [ ] Example is concrete and realistic
- [ ] Notes cover edge cases and caveats
- [ ] Design Rules contain substantive design principles (not just placeholders)
- [ ] Failure Modes list at least one known failure scenario with mitigation
- [ ] No sensitive information (credentials, internal URLs)
-->
