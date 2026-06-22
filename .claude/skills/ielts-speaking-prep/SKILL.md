---
name: ielts-speaking-prep
description: Generate a speaking cue card and model answer for IELTS Speaking Part 2, with Part 3 follow-ups.
version: 1.0.0
author: Claude
---

# Skill: ielts-speaking-prep

## When to Use

Use this skill when the user wants speaking practice material. Examples:
- "Give me a cue card about travel"
- "I want speaking practice"
- "/ielts-speaking-prep"

## Steps

1. Ask for a topic, or generate one randomly from common IELTS themes.
2. Create a cue card note at `D:\2Brain\english\04_Skills\Speaking\Part_2_Cue_Cards\<Topic>_Cue_Card.md`.
3. Include:
   - The cue card prompt (4 bullet points)
   - A 1-minute planning notes section
   - A model answer at Band 5.0 level (about 150–200 words, ~2 minutes when spoken)
   - Useful phrases/connectors
   - 3 Part 3 discussion questions with brief model answers
4. Update `D:\2Brain\english\04_Skills\Speaking\MOC_Speaking.md` to link to the new cue card.
5. Suggest the user record themselves and add notes to the file.

## Model Answer Guidelines

- Use simple, natural sentences.
- Include personal examples.
- Use basic connectors: because, so, but, however, also, for example.
- Aim for 150–200 words.

## Output Format

```markdown
---
title: "Describe a memorable journey"
date: 2026-06-20
topic: Speaking
tags:
  - english
  - speaking/part2
status: Active
---

# Cue Card: A Memorable Journey

## Prompt

Describe a memorable journey you have taken.
You should say:
- where you went
- who you went with
- what you did there
- and explain why it was memorable

## 1-Minute Planning Notes

- Where: Da Lat, 2023
- Who: my best friend
- What: visited waterfalls, drank coffee, rode motorbike
- Why: first trip without family, beautiful weather

## Model Answer

Last year, I went to Da Lat with my best friend...

## Useful Phrases

- I would like to talk about...
- The reason I remember it is...
- It was a great experience because...

## Part 3 Questions

1. Do you think traveling is important for young people?
2. ...
```
