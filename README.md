# x-post-reply

[![Version](https://img.shields.io/badge/version-1.0.0-blueviolet)](https://github.com/chuong1224/x-post-reply)
[![License](https://img.shields.io/github/license/chuong1224/x-post-reply)](https://github.com/chuong1224/x-post-reply/blob/main/LICENSE)
[![Grok Skill](https://img.shields.io/badge/Grok-Custom_Skill-9B59B6)](https://github.com/chuong1224/x-post-reply)
[![Last Commit](https://img.shields.io/github/last-commit/chuong1224/x-post-reply)](https://github.com/chuong1224/x-post-reply/commits/main)
[![GitHub Repo stars](https://img.shields.io/github/stars/chuong1224/x-post-reply?style=social)](https://github.com/chuong1224/x-post-reply/stargazers)

**Grok Skill** for generating short, natural, personalized replies to X (Twitter) posts and comments.

---

## English

### Overview

This skill activates when you want to reply to a post on X, reply to comments, or engage with social media posts. Trigger phrases include: “viet reply cho post nay”, “reply to this post”, “help me reply”, “draft reply”, etc.

Just paste the post content and say "viet reply" or similar — the skill automatically analyzes and outputs a ready-to-post reply.

**Not triggered** for general X knowledge questions, new caption requests, or without a specific post pasted.

### Purpose

Create concise replies (1-2 sentences, under 25 words), friendly, matching the tone of the X post — mainly for AI art, milestones, greetings, engagement questions. Results feel natural, personal, and non-generic.

### Repository Contents

- `SKILL.md` — Full skill specification: classification workflow (5 types: Milestone, Art+Question, Greeting, Compliment, Thank You), templates, specificity rules, emoji guide, gotchas, and real examples.
- `README.md` — This file (bilingual).
- `LICENSE` — MIT License

### How to Use

1. In Grok chat, paste a post/comment from X.
2. Say one of the trigger phrases like "viet reply cho post nay", "reply to this post", or "help me reply".
3. Get a ready-to-copy reply (or request 2-3 variants if you want options).

### Examples

See `SKILL.md` for detailed examples:
- Milestone replies (e.g. follower count)
- Art posts with engagement questions
- Morning / Greeting messages
- Simple compliments
- Thank you replies

### Gotchas & Best Practices

- Always include **1 specific detail** from the original post (visual element, vibe, or number).
- Keep replies **under 25 words** (1-2 sentences max).
- End with a **forward-looking phrase** (“more coming”, “onward”, “let’s keep growing”).
- Use **max 2 emojis**, tone-appropriate.
- For Vietnamese posts, still reply in English unless the user specifically requests Vietnamese.

### Version History

| Version | Date       | Changes                                      |
|---------|------------|----------------------------------------------|
| 1.0.0   | 2026-05-07 | Initial release with full workflow, 5-type classification, templates, gotchas, and real examples |

---

## Tiếng Việt

### Tổng quan

Skill này được kích hoạt khi bạn muốn viết reply cho bài đăng trên X, trả lời comment, hoặc tương tác với các bài đăng mạng xã hội. Các cụm từ kích hoạt bao gồm: “viet reply cho post nay”, “reply to this post”, “help me reply”, “draft reply”, v.v.

Chỉ cần paste nội dung post rồi nói “viet reply” hoặc tương tự — skill sẽ tự động phân tích và xuất ra reply sẵn sàng đăng.

**Không kích hoạt** khi bạn chỉ hỏi kiến thức chung về X, yêu cầu viết caption mới, hoặc không có post cụ thể được paste vào.

### Mục đích

Tạo các câu reply ngắn gọn (1-2 câu, dưới 25 từ), than thiện, phù hợp với tone của bài đăng trên X — chủ yếu dành cho AI art, milestone, lời chào, câu hỏi tương tác. Kết quả phải cảm giác tự nhiên, có tính cá nhân, không generic.

### Nội dung Repository

- `SKILL.md` — Định nghĩa đầy đủ của skill: workflow phân loại 5 loại post, templates, quy tắc thêm chi tiết, hướng dẫn emoji, gotchas và ví dụ thực tế.
- `README.md` — File này (song ngữ).
- `LICENSE` — Giấy phép MIT

### Cách sử dụng

1. Trong chat Grok, paste bài đăng/comment từ X.
2. Nói một trong các cụm từ kích hoạt như “viet reply cho post nay”, “reply to this post”, hoặc “help me reply”.
3. Nhận được reply sẵn sàng copy (hoặc yêu cầu 2-3 biến thể nếu muốn).

### Ví dụ

Xem `SKILL.md` để có các ví dụ chi tiết:
- Reply cho milestone (số follower)
- Art post có câu hỏi tương tác
- Lời chào sáng / Morning greeting
- Lời khen đơn giản
- Reply cảm ơn

### Lưu ý & Thực tṅn tốt nhất

- Luôn chèn **1 chi tiết cụ thể** từ post gốc (yếu tố thị giác, vibe hoặc con số).
- Giới hạn reply **dưới 25 từ** (tối đa 1-2 câu).
- Kết thúc bằng câu mang tính **tiếp nối** (“more coming”, “onward”, “let’s keep growing”).
- Sử dụng **tối đa 2 emoji**, phù hợp với tone.
- Với post tiếng Việt, vẫn reply bằng tiếng Anh trừ khi người dùng yêu cầu cụ thể bằng tiếng Việt.

### Lịch sử phiên bản

| Phiên bản | Ngày       | Thay đổi                                      |
|---------------|-------------|--------------------------------------------------|
| 1.0.0         | 2026-05-07  | Phát hành đầu tiên với đầy đủ workflow, phân loại 5 loại, templates, gotchas và ví dụ thực tế |

---

*Skill version: 1.0.0*  |  Repo: https://github.com/chuong1224/x-post-reply  |  Licensed under [MIT](LICENSE)

Tạo ra cho người dùng Grok tùy chỉnh — fork, chỉnh sửa và cải tiến thêm!