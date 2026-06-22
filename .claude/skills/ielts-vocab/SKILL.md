---
name: ielts-vocab
description: Generate a structured IELTS vocabulary note for a given topic and save it in the vault.
version: 1.0.0
author: Claude
---

# Skill: ielts-vocab

## When to Use

Use this skill when the user wants to add vocabulary words to their second brain. Examples:
- "Add 20 environment words"
- "Create a vocabulary note for technology"
- "I need vocabulary for IELTS speaking part 2 about travel"

## Steps

1. Ask the user for a topic if not provided.
2. Determine the target band (default Band 4.0–5.0 unless specified).
3. Generate 15–25 words/phrases suitable for that topic and band.
4. Create a new markdown file at `D:\2Brain\english\02_Vocabulary\by_Topic\<Topic>.md`.
5. Use the Vocabulary_Note template format with YAML frontmatter.
6. Include a table: Word | Type | Definition | Example Sentence | Collocations | My Sentence.
7. Add a `## Related` section linking back to `MOC_Vocabulary.md`.
8. Update `D:\2Brain\english\02_Vocabulary\MOC_Vocabulary.md` to link to the new file if not already linked.
9. Confirm the file path and word count to the user.

## Output Format

```markdown
---
title: "Environment Vocabulary"
date: 2026-06-20
topic: Vocabulary
tags:
  - english
  - vocabulary/environment
status: Active
---

# Environment Vocabulary

| Word | Type | Definition | Example Sentence | Collocations | My Sentence |
|------|------|------------|------------------|--------------|-------------|
| pollution | noun | sự ô nhiễm | Air pollution is a serious problem in big cities. | air pollution, water pollution, reduce pollution | |

## Related

- [[MOC_Vocabulary]]
```

## Notes

- Keep definitions and example sentences at Band 5.0 level.
- Prioritize high-frequency IELTS collocations.
- Leave the "My Sentence" column blank for the user to fill in.
