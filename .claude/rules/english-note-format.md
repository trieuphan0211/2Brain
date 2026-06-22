# Rule: English Note Format

## Purpose

Ensure every note in the English section has consistent metadata for searching, filtering, and review.

## Rule

Every markdown file created or moved into `D:\2Brain\english\` MUST include YAML frontmatter at the top with at least these fields:

```yaml
---
title: "Short descriptive title"
date: YYYY-MM-DD
topic: [Vocabulary | Grammar | Listening | Reading | Writing | Speaking | MockTest | ErrorLog | StudyPlan]
tags:
  - english
  - <subtag>
status: [Active | Reviewing | Mastered | Archived]
---
```

### Field Guidelines

- `title`: clear and concise, e.g., "Environment Vocabulary" or "Past Simple Rules"
- `date`: creation date in `YYYY-MM-DD` format
- `topic`: pick the single best category
- `tags`: always include `english`; add a subtag such as `vocabulary/environment`, `grammar/tenses`, `writing/task2`, etc.
- `status`:
  - `Active` — currently learning
  - `Reviewing` — revisiting
  - `Mastered` — confident
  - `Archived` — no longer relevant

## Automatic Behavior

When creating a new note in `english/`, always:
1. Add the YAML frontmatter before any other content.
2. Use the current date unless the user specifies otherwise.
3. Set `status: Active` by default.
