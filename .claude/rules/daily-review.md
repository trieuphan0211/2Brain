# Rule: Daily Review Ritual

## Purpose

Prevent the vault from becoming a dump and reinforce learning through spaced review.

## Rule

At the end of a session, if the user has created or modified any notes inside `D:\2Brain\english\`, proactively ask:

> "Bạn có muốn chạy daily review không? Mình sẽ kiểm tra error log, ôn lại 5 từ ngẫu nhiên, và cập nhật tiến độ."

If the user agrees, perform or guide them through:

1. **Error Log Check:** Open `english\05_Error_Log\MOC_Errors.md` and review the most recent 3–5 errors.
2. **Vocabulary Review:** Pick 5 random words from `english\02_Vocabulary\` notes and quiz the user.
3. **Progress Update:** Run the `ielts-study-tracker` skill to update `Progress_Tracker.md`.
4. **Tomorrow’s Priority:** Suggest one focus area based on the weakest skill or oldest `Active` note.

## Light Mode

If the user is tired or short on time, offer a "light review":
- 3 random vocabulary words
- 1 error log entry
- Quick progress update
