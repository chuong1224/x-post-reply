---
name: x-post-reply
version: 1.1.0
description: >-
  Kich hoat khi user muon viet reply cho post tren X (Twitter), tra loi comment
  tren X, phan hoi bai dang mang xa hoi. BAT CU KHI NAO user noi: viet reply cho
  post nay, reply cai nay, tra loi comment nay, reply X, viet comment cho post,
  help me reply, reply to this post, write a reply, draft reply, reply tweet nay,
  tra loi tweet. Vi du: user paste noi dung post roi goi viet reply la skill tu
  dong phan tich va xuat reply chuan. Khong kich hoat khi user chi hoi kien thuc
  ve X, yeu cau viet caption moi, hoac khong co post cu the duoc paste vao.
---

## Muc dich
Tao reply ngan gon (1-2 cau, duoi 25 tu), than thien, dung tone cho post tren X —
chu yeu AI art, milestone, greeting, engagement question. Ket qua phai cam giac tu nhien,
co tinh ca nhan, khong generic.

## Workflow chinh

### Buoc 1 — Xac dinh loai post
Doc post/comment duoc cung cap → phan loai vao 1 trong 5 loai sau:

| Loai | Dau hieu nhan biet |
|------|-------------------|
| A — Milestone | "followed", "+1", follower count, "thank you for 100/1k..." |
| B — Art + Question | "would you...?", "come closer?", "step in?", hinh anh co prompt |
| C — Morning/Greeting | "good morning", "GM", loi chuc, motivational message |
| D — Simple Compliment | "love this", "fire", emoji only, "beautiful", "stunning" |
| E — Thank You Reply | commenter noi "thank you", "thanks for...", "appreciate it" |

### Buoc 2 — Chon template
Ap dung template tuong ung voi loai da xac dinh:

| Loai | Template chuan |
|------|---------------|
| A | "Thank you! [emoji] [detail nho] — let's keep growing together! [emoji]" |
| B | "Thank you! [emoji] [acknowledge 1 visual detail] — [playful line]. [emoji]" |
| C | "Good morning! [emoji] [comment on vibe/message] [emoji]" |
| D | "Thank you! [emoji] [acknowledge compliment] — more [subject] coming! [emoji]" |
| E | "You're welcome! [emoji] [warm line] — onward! [emoji]" |

### Buoc 3 — Them specificity
Xac dinh 1 chi tiet cu the tu post goc:
- Chi tiet visual: "teal corset", "light through wings", "golden armor"
- Cam xuc/vibe: "uplifting message", "gentle energy", "bold energy"
- Con so/su kien: "+47", "100 followers", "first post"

→ Chen chi tiet nay vao template, thay the placeholder.

### Buoc 4 — Chon emoji
Dung dung 1-2 emoji phu hop tone:

| Tone | Emoji phu hop |
|------|--------------|
| Warm / appreciative | 😊 💙 💚 🤗 |
| Hype / energy | 🔥 ✨ 💫 |
| Art / ethereal | 🪡 👑 🌟 |
| Playful | 😄 😏 |

### Buoc 5 — Trim va check
- Dem tu: phai duoi 25 tu
- Kiem tra: co dung ten/detail khong? Co generic khong?
- Neu generic → quay Buoc 3, them 1 detail hon

### Buoc 6 — Output
Xuat 1 reply duy nhat, san sang copy/paste len X.
Neu user muon options → xuat 2-3 bien the ngan.

---

## Gotchas

| # | Van de hay gap | Cach xu ly |
|---|---------------|------------|
| 1 | Reply qua chung ("Nice post!") khong co hook | Bat buoc phai chen 1 chi tiet tu post goc vao reply |
| 2 | Reply qua dai (3+ cau) | Cat con 1-2 cau, gioi han 25 tu — khong ngoai le |
| 3 | Dung sai emoji (too many or mismatch tone) | Max 2 emoji, chon theo bang tone o Buoc 4 |
| 4 | Nham loai post — Loai B bi xu ly nhu Loai D | Loai B PHAI co playful line, Loai D chi can thank + forward note |
| 5 | Quen forward-looking ending | Ket thu phai mo ("more coming", "onward", "let's keep growing") |
| 6 | User paste nhieu comments cung luc | Xu ly tung comment rieng, xuat tung reply co danh so |
| 7 | Post bang tieng Viet hoac ngon ngu khac | Van reply bang English tru khi user yeu cau cu the ngon ngu khac |
| 8 | YAML frontmatter loi malformed | Description phai dung ">-" folded scalar, khong dung quotes bao ngoai, khong de chuoi xuong dong tu do |

---

## Vi du thuc te

| Post goc | Reply chuan |
|----------|------------|
| "Just hit 100 followers!" | "Thank you! 😊 100 and counting — let's keep growing together! 🔥" |
| "Would you step closer to her? 👁️" [art post] | "Thank you! 😊 The light through those wings makes it hard to resist — stepping in! ✨" |
| "Good morning everyone! Stay blessed 🌸" | "Good morning! 🪡 Such a warm and uplifting energy — love it! ✨" |
| "This is fire 🔥" | "Thank you! 😊 Glad the energy hits — more queens coming! 🔥" |
| "Thanks for the follow!" | "You're welcome! 🤗 Happy to be here — onward! 🔥" |