## name: x-post-reply
version: 2.0.0
description: “Kich hoat khi user muon viet reply cho post tren X (Twitter), tra loi comment tren X, phan hoi bai dang mang xa hoi. BAT CU KHI NAO user noi: viet reply cho post nay, reply cai nay, tra loi comment nay, reply X, viet comment cho post, help me reply, reply to this post, write a reply, draft reply, reply tweet nay, tra loi tweet. Vi du: user paste noi dung post roi goi viet reply la skill tu dong phan tich va xuat reply chuan. Khong kich hoat khi user chi hoi kien thuc ve X, yeu cau viet caption moi, hoac khong co post cu the duoc paste vao.”

# X Post Reply Skill

**Pattern**: Context-Aware Tool Selection
**Loai Skill**: Business Process Automation
**Muc tieu**: Phan tich loai post → xuat DUNG 1 reply text thuan tuy, san sang copy-paste len X.

-----

## QTTC (Quy Tac Tuyet Doi Khong Vi Pham)

- OUTPUT CHI CO reply text. Khong “Here’s a reply:”, khong giai thich, khong meta comment.
- Ngan: toi da 2 cau, ly tuong duoi 25 tu.
- Tieng Anh tru khi user yeu cau ngon ngu khac.
- Phai nhac den 1 chi tiet cu the tu post goc (khong reply chung chung).

-----

## Workflow (Thuc Hien Theo Thu Tu)

**Buoc 1 — Nhan dien nguon dau vao**

|Dau vao                                |Xu ly                                                 |
|---------------------------------------|------------------------------------------------------|
|User paste noi dung post truc tiep     |Doc noi dung, chuyen Buoc 2                           |
|User paste URL X.com                   |Hoi user paste noi dung post (khong fetch duoc link X)|
|User chi noi “viet reply” khong co post|Hoi: “Ban co the paste noi dung post vao khong?”      |

**Buoc 2 — Phan loai loai post**

|Dau hieu                           |Loai              |Chien luoc reply                                |
|-----------------------------------|------------------|------------------------------------------------|
|Post goc, khong co parent / la root|**Main Post**     |Engage truc tiep noi dung chinh cua post        |
|Post la reply/comment tu nguoi khac|**Reply-to-Reply**|Acknowledge nguoi comment, ngan hon, ca nhan hon|

Neu khong ro → uu tien phan loai la **Reply-to-Reply** (an toan hon).

**Buoc 3 — Xac dinh context type**

|Noi dung post                  |Template ap dung    |
|-------------------------------|--------------------|
|Art / creative showcase        |Art Appreciation    |
|Question / poll / prompt       |Direct Engagement   |
|Milestone / celebration        |Milestone Warmth    |
|Morning greeting / motivation  |Reciprocal Energy   |
|Simple “wow”, “nice”, “love it”|Light Acknowledgment|
|Thank-you / appreciation       |Warm Reciprocation  |

**Buoc 4 — Tao reply**

1. Chon template phu hop (xem bang Templates ben duoi).
1. Chen 1 chi tiet cu the tu post (ten nhan vat, detail artwork, so milestone, v.v.).
1. Them 1–2 emoji phu hop tone.
1. Cat xuong con 1–2 cau ngan.
1. Xuat DUNG reply text, khong them gi.

-----

## Templates Theo Context Type

### Main Post — Art Appreciation

> Compliment 1 chi tiet visual + engage voi cau hoi/prompt neu co.

- “Thank you! 😊 [Specific detail] is stunning — [light engagement with post prompt]. 🔥”
- “The [specific element] in this piece is incredible! ✨ Would love to see more like this.”

### Main Post — Direct Engagement (Question / Poll)

> Tra loi truc tiep, ngan gon, friendly.

- “[Answer]. 😊 [One supporting detail or reaction]. ✨”

### Main Post — Milestone Warmth

> Thank + onward energy.

- “Thank you so much! 😊 [Specific milestone acknowledgment] — onward we go! 🔥”
- “Congrats on [milestone]! 🎉 Really glad to be part of this journey. More wins ahead! ✨”

### Main Post — Morning / Motivation

> Reciprocate energy, khong over-the-top.

- “Good morning! 🪡 [Reflect one word from their message]. Hope your day is just as great! ✨”

### Reply-to-Reply — Light Acknowledgment

> Ngan nhat trong tat ca template. Thuong 1 cau du.

- “Thanks! 😊 [One specific call-out from their comment]. 🔥”
- “Glad you liked it! ☺️ [Optional: one casual follow-up]. ✨”
- “Haha, [echo their tone]! 😄 Appreciate it — more coming soon! ✨”

### Reply-to-Reply — Warm Reciprocation

> Khi ho cam on hoac bieu cam manh.

- “You’re welcome! 🤗 [One genuine note]. 🔥”
- “Means a lot! 😊 Thanks for being here. ✨”

-----

## Do’s & Don’ts

|Do                                       |Don’t                                |
|-----------------------------------------|-------------------------------------|
|Match tone nguoi post (playful → playful)|Output bat cu thu gi ngoai reply text|
|Nhac 1 chi tiet cu the                   |Reply chung chung “Nice post!”       |
|Emoji 1–2 cai, phu hop tone              |Spam emoji                           |
|Reply-to-reply ngan hon Main post        |Lap lai noi dung post goc            |
|Ket thuc open/positive                   |Giai thich tai sao minh viet reply do|

-----

## Gotchas (Loi Thuong Gap — Bat Buoc Doc)

|# |Tinh huong                                      |Xu ly dung                                                             |
|--|------------------------------------------------|-----------------------------------------------------------------------|
|G1|User chi gui URL khong paste noi dung           |Khong guess. Hoi user paste text. X URL khong fetch duoc.              |
|G2|Post bang tieng Viet / ngon ngu khac            |Mac dinh reply tieng Anh tru khi user chi dinh ngon ngu khac           |
|G3|User muon reply cho reply cua chinh minh        |Phan loai la Main Post interaction, khong phai Reply-to-Reply          |
|G4|Post qua ngan (“🔥”) khong co noi dung           |Dung template Light Acknowledgment, chen emoji tuong tu, giu duoi 10 tu|
|G5|User paste nhieu post mot luc                   |Xu ly tung post rieng biet, xuat tung reply rieng biet theo thu tu     |
|G6|Output bat dau bang “Thank you” qua thuong xuyen|Vary opener: “Glad you…”, “So cool…”, “Appreciate it…”, “Haha…”        |
|G7|Emoji khong phu hop (vui ve dung emoji buon)    |Luon match emotional tone cua post goc                                 |
|G8|Reply dai hon 2 cau                             |Cat lai ngay. Neu thieu y → uu tien cau dau tien, bo cau thu 2         |

-----

## Vi Du Thuc Te

**Input**: Post art Phoenix Seraph, caption “Would you kneel? 🔥”
**Type**: Main Post → Art Appreciation + Question
**Output**:

```
Thank you! 😊 The blazing sword and glowing ponytail on the Phoenix Seraph are mesmerizing — I'd kneel without hesitation! 🔥
```

-----

**Input**: Reply comment “Wow ☺️ 👌” tren post art
**Type**: Reply-to-Reply → Light Acknowledgment
**Output**:

```
Thanks! 😊 Glad the Phoenix Seraph caught your eye — the details were fun to craft 🔥
```

-----

**Input**: Post milestone “+500 followers! Thank you all 🙏”
**Type**: Main Post → Milestone Warmth
**Output**:

```
Congrats on 500! 🎉 Really glad to be part of this — more wins ahead! ✨
```

-----

**Input**: Morning post “Good morning everyone! Have a great Sunday ☀️”
**Type**: Main Post → Morning Greeting
**Output**:

```
Good morning! 🪡 Hope your Sunday is just as bright. ✨
```