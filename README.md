# x-post-reply

[![Version](https://img.shields.io/badge/version-2.0.0-blueviolet)](https://github.com/chuong1224/x-post-reply)
[![License](https://img.shields.io/badge/license-MIT-green)](https://github.com/chuong1224/x-post-reply/blob/main/LICENSE)
[![Grok Skill](https://img.shields.io/badge/Grok-Custom_Skill-9B59B6)](https://github.com/chuong1224/x-post-reply)
[![Last Commit](https://img.shields.io/github/last-commit/chuong1224/x-post-reply)](https://github.com/chuong1224/x-post-reply/commits/main)
[![GitHub Repo stars](https://img.shields.io/github/stars/chuong1224/x-post-reply?style=social)](https://github.com/chuong1224/x-post-reply/stargazers)

**Grok Skill v2.0.0** — Context-aware tool for generating natural, personalized replies to X (Twitter) posts and comments. Analyzes post type, context, and crafts concise, engaging responses ready to copy-paste.

---

## English

### Overview

This skill activates whenever you want to reply to a post or comment on X. It automatically classifies the post type (Main Post vs Reply-to-Reply), identifies context (art, milestone, greeting, etc.), and generates **exactly one** ready-to-use reply text following strict rules: max 2 sentences, under 25 words ideal, mentions one specific detail from the original post, matches tone, and ends positively.

**Trigger examples:** “viet reply cho post nay”, “reply to this post”, “help me reply”, “draft reply”, “tra loi tweet”

**Not triggered** for general X knowledge questions, caption writing requests, or when no specific post content is provided.

### Key Features
- Strict output: **only** the reply text (no explanations, no “Here’s a reply:”)
- Context-aware templates for Art, Questions, Milestones, Greetings, Acknowledgments, Thank-yous
- Always references **one specific detail** from the original post
- Smart classification: Main Post vs Reply-to-Reply
- Handles edge cases (short posts, multiple posts, non-English, etc.)
- Optimized for high engagement: emotional hooks, questions, positive close

### Workflow Summary
1. Detect input type (direct paste / URL / no content)
2. Classify as Main Post or Reply-to-Reply
3. Identify context type (Art Appreciation, Direct Engagement, Milestone Warmth, etc.)
4. Generate reply using matching template + specific detail + 1-2 emojis
5. Trim to 1-2 short sentences

### Examples
See `SKILL.md` for detailed real-world examples with input → classified type → output reply.

### Gotchas & Best Practices
- Always mention **1 specific detail** (never generic “Nice post!”)
- Keep very short (ideal <25 words, max 2 sentences)
- Match emotional tone and use appropriate emojis (1-2 max)
- For Vietnamese posts: reply in English unless user specifies otherwise
- Output **only** raw reply text

---

## Tiếng Việt

### Tổng quan

Skill này được kích hoạt khi bạn muốn viết reply cho bài đăng hoặc comment trên X. Nó tự động phân loại loại post (Main Post hay Reply-to-Reply), xác định ngữ cảnh (art, milestone, greeting...), và tạo **chính xác 1** câu reply sẵn sàng copy-paste, tuân thủ quy tắc nghiêm ngặt: tối đa 2 câu, lý tưởng dưới 25 từ, nhắc 1 chi tiết cụ thể từ post gốc, phù hợp tone, kết thúc tích cực.

**Các cụm từ kích hoạt:** “viet reply cho post nay”, “reply to this post”, “help me reply”, “draft reply”, “tra loi tweet”

**Không kích hoạt** khi chỉ hỏi kiến thức về X, yêu cầu viết caption, hoặc không có nội dung post cụ thể.

### Tính năng chính
- Output nghiêm ngặt: **chỉ** text reply (không giải thích, không “Here’s a reply:”)
- Template theo ngữ cảnh: Art, Question, Milestone, Greeting, Acknowledgment, Thank you
- Luôn nhắc **1 chi tiết cụ thể** từ post gốc
- Phân loại thông minh: Main Post vs Reply-to-Reply
- Xử lý các tình huống biên (post ngắn, nhiều post, post tiếng Việt...)
- Tối đạ đấu tương tác: hook cảm xúc, câu hỏi, kết thúc tích cực

### Tóm tắt Workflow
1. Nhận diện loại input (paste trực tiếp / URL / không có nội dung)
2. Phân loại Main Post hay Reply-to-Reply
3. Xác định context type (Art Appreciation, Direct Engagement, Milestone Warmth...)
4. Tạo reply theo template phù hợp + chi tiết cụ thể + 1-2 emoji
5. Cắt ngắn còn 1-2 câu

### Ví dụ
Xem `SKILL.md` để có các ví dụ thực tế chi tiết với Input → Loại → Output reply.

### Lưu ý quan trọng
- Luôn nhắc **1 chi tiết cụ thể** (không dùng “Nice post!” chung chung)
- Giữ rất ngắn (lý tưởng <25 từ, tối đa 2 câu)
- Phù hợp tone cảm xúc và dùng emoji thích hợp (1-2 cái)
- Post tiếng Việt: reply tiếng Anh trừ khi user yêu cầu khác
- Output **chỉ** raw reply text

---

*Skill version: 2.0.0*  |  Repo: https://github.com/chuong1224/x-post-reply  |  Licensed under [MIT](LICENSE)

Created for Grok users who want fast, high-quality, on-brand replies on X.