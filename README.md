# x-post-reply

[![Version](https://img.shields.io/badge/version-1.1.0-blueviolet)](https://github.com/chuong1224/x-post-reply)
[![License](https://img.shields.io/github/license/chuong1224/x-post-reply)](https://github.com/chuong1224/x-post-reply/blob/main/LICENSE)
[![Grok Skill](https://img.shields.io/badge/Grok-Custom_Skill-9B59B6)](https://github.com/chuong1224/x-post-reply)
[![Last Commit](https://img.shields.io/github/last-commit/chuong1224/x-post-reply)](https://github.com/chuong1224/x-post-reply/commits/main)
[![GitHub Repo stars](https://img.shields.io/github/stars/chuong1224/x-post-reply?style=social)](https://github.com/chuong1224/x-post-reply/stargazers)

**Grok Skill** for generating short, natural, personalized replies to X (Twitter) posts and comments.

---

## English

### Overview

This skill activates when you want to reply to a post on X, reply to comments, or engage with social media posts. Trigger phrases include: “viet reply cho post nay”, “reply to this post”, “help me reply”, “draft reply”, etc.

Just paste the post content and say “viet reply” or similar — the skill automatically analyzes and outputs a ready-to-post reply.

**Not triggered** for general X knowledge questions, new caption requests, or without a specific post pasted.

### Purpose

Create concise replies (1-2 sentences, under 25 words), friendly, matching the tone of the X post — mainly for AI art, milestones, greetings, engagement questions. Results feel natural, personal, and non-generic.

### Repository Contents

- `SKILL.md` — Full skill specification (v1.1.0): classification workflow (5 types), templates, specificity rules, emoji guide, gotchas, and real examples.
- `README.md` — This file (bilingual).
- `LICENSE` — MIT License

### How to Use

1. In Grok chat, paste a post/comment from X.
2. Say one of the trigger phrases like “viet reply cho post nay”, “reply to this post”, or “help me reply”.
3. Get a ready-to-copy reply (or request 2-3 variants).

### Examples

See `SKILL.md` for detailed examples:
- Milestone replies (follower counts)
- Art posts with engagement questions
- Morning / Greeting messages
- Simple compliments
- Thank you replies

### Gotchas & Best Practices

- Always include **1 specific detail** from the original post.
- Keep replies **under 25 words**.
- End with a **forward-looking phrase**.
- Use **max 2 emojis**, tone-appropriate.
- For Vietnamese posts, reply in English unless Vietnamese is specifically requested.
- YAML frontmatter: Use `>-` for multi-line description to avoid parsing errors.

### Version History

| Version | Date       | Changes                                      |
|---------|------------|----------------------------------------------|
| 1.1.0   | 2026-05-08 | Improved YAML frontmatter handling + new gotcha about description formatting |
| 1.0.0   | 2026-05-07 | Initial release with full workflow, 5-type classification, templates, gotchas, and examples |

---

## Tiếng Việt

### Tổng quan

Skill này được kích hoạt khi bạn muốn viết reply cho bài đăng trên X, trả lời comment, hoặc tương tác với các bài đăng mạng xã hội. Các cụm từ kích hoạt bao gồm: “viet reply cho post nay”, “reply to this post”, “help me reply”, v.v.

Chỉ cần paste nội dung post rồi nói “viet reply” — skill sẽ tự động phân tích và xuất ra reply sẵn sàng đăng.

**Không kích hoạt** khi chỉ hỏi kiến thức chung về X hoặc yêu cầu viết caption mới.

### Mục đích

Tạo các câu reply ngắn gọn (1-2 câu, dưới 25 từ), than thiện, phù hợp tone bài đăng trên X — chủ yếu cho AI art, milestone, lời chào, câu hỏi tương tác. Kết quả tự nhiên, có tính cá nhân.

### Nội dung Repository

- `SKILL.md` — Định nghĩa đầy đủ của skill (v1.1.0)
- `README.md` — File này (song ngữ)
- `LICENSE` — Giấy phép MIT

### Cách sử dụng

1. Paste bài đăng/comment từ X vào Grok.
2. Nói các cụm từ kích hoạt như “viet reply cho post nay”.
3. Nhận reply sẵn sàng copy (hoặc yêu cầu 2-3 biến thể).

### Ví dụ

Xem `SKILL.md` để có các ví dụ chi tiết.

### Lưu ý quan trọng

- Luôn chèn **1 chi tiết cụ thể** từ post gốc.
- Giới hạn dưới **25 từ**.
- Kết thúc bằng câu mang tính tiếp nối.
- Tối đa **2 emoji**.
- Với post tiếng Việt: reply bằng tiếng Anh (trừ khi được yêu cầu).
- YAML frontmatter: Dùng `>-` cho description nhiều dòng.

### Lịch sử phiên bản

| Phiên bản | Ngày       | Thay đổi                                      |
|---------------|-------------|--------------------------------------------------|
| 1.1.0         | 2026-05-08  | Cải thiện xử lý YAML frontmatter + thêm gotcha mới |
| 1.0.0         | 2026-05-07  | Phát hành đầu tiên                                |

---

*Skill version: 1.1.0*  |  Repo: https://github.com/chuong1224/x-post-reply  |  Licensed under [MIT](LICENSE)

Tạo bởi N0v4Ph4n cho Grok users