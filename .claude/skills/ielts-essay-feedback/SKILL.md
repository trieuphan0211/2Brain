---
name: ielts-essay-feedback
description: Read a practice IELTS essay from the vault and provide Band 5.0-focused feedback.
version: 1.0.0
author: Claude
---

# Skill: ielts-essay-feedback

## When to Use

Use this skill when the user wants feedback on an IELTS Writing Task 1 or Task 2 practice essay. Examples:
- "Check my essay"
- "Give me feedback on Task 2"
- "/ielts-essay-feedback"

## Steps

1. Ask which essay file to review, or auto-detect the most recently modified file in `D:\2Brain\english\04_Skills\Writing\`.
2. Read the essay and the prompt/question.
3. Provide feedback in a new file named `Essay_Feedback_YYYY-MM-DD.md` in the same folder as the essay.
4. Include the following sections:
   - **Estimated Band Score** (with brief justification)
   - **Task Response** — did they answer the question?
   - **Coherence and Cohesion** — paragraph structure and linking words
   - **Lexical Resource** — vocabulary strengths and simple upgrades
   - **Grammatical Range and Accuracy** — common errors and corrections
   - **Band 5.0 Rewrites** — rewrite 2–3 weak sentences in simpler, correct English
   - **Next Steps** — 2 specific actions for the next essay
5. Link the feedback file back to the original essay.
6. Report the feedback file path to the user.

## Scoring Guidance for Band 5.0

- **Task Response:** Position is clear, some main ideas are relevant, but development may be limited.
- **Coherence:** Basic paragraphing, some linking words, but ideas may not always flow smoothly.
- **Vocabulary:** Adequate for the task, but repetition and awkward word choices are acceptable at this band.
- **Grammar:** Mostly simple sentences, some complex attempts, errors do not seriously impede meaning.

## Output Format

Create a structured markdown file with headings and bullet points. Keep explanations short and actionable.
