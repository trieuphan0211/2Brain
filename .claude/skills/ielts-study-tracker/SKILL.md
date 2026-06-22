---
name: ielts-study-tracker
description: Update the daily progress tracker and suggest tomorrow's study focus.
version: 1.0.0
author: Claude
---

# Skill: ielts-study-tracker

## When to Use

Use this skill at the end of a study session. Examples:
- "Update my progress"
- "I studied 3 hours today"
- "/ielts-study-tracker"

## Steps

1. Read `D:\2Brain\english\01_Study_Plan\Progress_Tracker.md`.
2. Ask the user (or infer from recent activity):
   - Date
   - Hours studied
   - Grammar topic studied (if any)
   - New vocabulary count
   - Vocabulary review count
   - Listening practice (yes/no + section)
   - Reading practice (yes/no + passage count)
   - Writing practice (yes/no + task)
   - Speaking practice (yes/no + part)
   - Mock test taken (yes/no + test name)
   - Confidence level 1–5
   - Notes
3. Append a new row to the tracker table.
4. Calculate:
   - Days remaining until July 20
   - Total hours studied so far
   - Weakest skill (lowest confidence or least practice)
5. Suggest tomorrow’s priority based on the weakest skill or the 30-day plan.
6. Update the tracker file.

## Output Format

Append a markdown table row like:

```markdown
| 2026-06-20 | 3.0 | Present Simple | 15 | 30 | Part 1 | 1 passage | Task 1 overview | Part 1 intro | Diagnostic test | 3 | Felt tired but finished listening |
```

Then add a short summary:

```markdown
## Summary

- Days until exam: 30
- Total hours studied: 3.0
- Weakest skill: Writing
- Tomorrow's priority: Complete Writing Task 1 overview note and write 1 sentence for each chart type.
```

## Notes

- Always preserve the existing table header.
- If the user skips a day, mark it as `0` hours and note the reason.
- Keep the summary encouraging and specific.
