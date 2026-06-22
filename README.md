# 2Brain — IELTS Academic Second Brain

Vault Obsidian dùng để ôn thi **IELTS Academic**.

- **Trình độ hiện tại:** khoảng Band 3.0
- **Mục tiêu:** Band 5.0
- **Ngày thi:** 20 tháng 7
- **Thở lượng học mỗi ngày:** 3 tiếng tập trung

---

## Triết lý

1. **Ghi → Sắp xếp → Ôn lại.** Mỗi từ mới, lỗi sai hay ý tưởng đều cần được ghi vào đúng thư mục, liên kết với các ghi chú liên quan, và xem lại đều đặn.
2. **Giải thích phù hợp Band 5.0.** Ngắn gọn, rõ ràng, không dùng ngôn ngữ quá phức tạp.
3. **Tiến bộ từng ngày.** Hoàn thành tốt từng phần nhỏ quan trọng hơn ghi chú hoàn hảo.

---

## Cấu trúc thư mục

```
english/
├── 00_Inbox/           # Ghi nhanh, chưa xử lý (xử lý trong 24h)
├── 01_Study_Plan/      # Lịch học, lịch hàng ngày, theo dõi tiến độ
├── 02_Vocabulary/      # Từ vựng theo chủ đề và theo band
├── 03_Grammar/         # Ngữ pháp và bài tập
├── 04_Skills/          # Chiến thuật Listening, Reading, Writing, Speaking
├── 05_Error_Log/       # Lỗi cá nhân và cách sửa
├── 06_Mock_Tests/      # Kết quả và phân tích bài thi thử
└── 07_Templates/       # Mẫu ghi chú Obsidian
```

> Tất cả nội dung học tiếng Anh đều nằm trong `english/`. Chỉ có `00_Inbox` là ngoại lệ để ghi nhanh.

---

## Cách dùng

### Hàng ngày

1. Mở `english/01_Study_Plan/Daily_Schedule.md` để xem nhiệm vụ hôm nay.
2. Học theo chủ đề đã lên lịch.
3. Ghi lại từ mới, lỗi sai, hoặc mẫu câu hay vào đúng thư mục.
4. Cuối buổi, chạy **daily review** để ôn lại và cập nhật tiến độ.

### Khi cần ghi nhanh

- Cho nội dung chưa biết để đâu vào `english/00_Inbox/`.
- Trong vòng 24h, di chuyển nội dung đó vào thư mục đúng và thêm YAML frontmatter.

### Các skill hỗ trợ

| Skill | Dùng khi nào |
|-------|--------------|
| `/ielts-vocab` | Tạo ghi chú từ vựng theo chủ đề |
| `/ielts-essay-feedback` | Nhận feedback bài Writing Task 2 |
| `/ielts-speaking-prep` | Tạo cue card và câu trả lờI mẫu Speaking Part 2 |
| `/ielts-study-tracker` | Cập nhật tiến độ học hàng ngày |

---

## Quy tắc ghi chú

Mọi file markdown trong `english/` đều cần có YAML frontmatter:

```yaml
---
title: "Tiêu đề ngắn gọn"
date: 2026-06-22
topic: [Vocabulary | Grammar | Listening | Reading | Writing | Speaking | MockTest | ErrorLog | StudyPlan]
tags:
  - english
  - <subtag>
status: [Active | Reviewing | Mastered | Archived]
---
```

- `status: Active` — đang học
- `status: Reviewing` — đang ôn lại
- `status: Mastered` — đã thuộc
- `status: Archived` — không còn cần thiết

---

## Daily Review

Cuối mỗi buổi học, nên chạy review gồm:

1. **Kiểm tra Error Log:** xem lại 3–5 lỗi gần nhất trong `english/05_Error_Log/MOC_Errors.md`.
2. **Ôn từ vựng:** quiz 5 từ ngẫu nhiên từ `english/02_Vocabulary/`.
3. **Cập nhật tiến độ:** dùng skill `ielts-study-tracker`.
4. **Ưu tiên ngày mai:** chọn 1 kỹ năng yếu nhất hoặc ghi chú `Active` cũ nhất để tập trung.

---

## Mục tiêu 30 ngày

Xem chi tiết lộ trình trong `english/01_Study_Plan/IELTS_30_Day_Plan.md`.

---

*Chúc may mắn — tiến bộ từng ngày!* 🎯
