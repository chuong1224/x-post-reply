# x-post-reply

[![Version](https://img.shields.io/badge/version-1.0.0-blueviolet)](https://github.com/chuong1224/x-post-reply)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/chuong1224/x-post-reply/blob/main/LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/chuong1224/x-post-reply)](https://github.com/chuong1224/x-post-reply/commits/main)
[![Grok Skill](https://img.shields.io/badge/Grok-Custom_Skill-9B59B6)](https://github.com/chuong1224/x-post-reply)
[![Stars](https://img.shields.io/github/stars/chuong1224/x-post-reply?style=social)](https://github.com/chuong1224/x-post-reply/stargazers)

**Grok Skill** for generating short, natural, personalized replies to X (Twitter) posts and comments.

## Overview

This skill activates when you want to reply to a post on X, reply to comments, or engage with social media posts. Trigger phrases include: “viet reply cho post nay”, “reply to this post”, “help me reply”, “draft reply”, etc.

Just paste the post content and say "viet reply" or similar — the skill analyzes and outputs a ready-to-post reply.

**Not triggered** for general X knowledge questions, new caption requests, or without a specific post pasted.

## Purpose

Create concise replies (1-2 sentences, under 25 words), friendly, matching the tone of the X post — mainly for AI art, milestones, greetings, engagement questions. Results feel natural, personal, and non-generic.

## Repository Contents

- `SKILL.md` — Full skill specification: classification workflow (5 types: Milestone, Art+Question, Greeting, Compliment, Thank You), templates, specificity rules, emoji guide, gotchas, and real examples.
- `README.md` — This file.
- `LICENSE` — MIT License

## How to Use

1. In Grok chat, paste a post/comment from X.
2. Say one of the trigger phrases like "viet reply cho post nay", "reply to this post", or "help me reply".
3. Get a ready-to-copy reply (or request 2-3 variants).

## Examples

See `SKILL.md` for detailed examples:
- Milestone: follower counts
- Art posts with questions
- Morning/Greeting messages
- Simple compliments
- Thank you replies

## Gotchas & Best Practices

- Always include **1 specific detail** from the original post (visual, vibe, or number).
- Keep replies **under 25 words** (1-2 sentences).
- End with a **forward-looking phrase** (“more coming”, “onward”, “let’s keep growing”).
- Use **max 2 emojis**, chosen by tone.
- For Vietnamese posts, still reply in English unless user requests otherwise.

---

*Skill version: 1.0.0*  |  Repo: https://github.com/chuong1224/x-post-reply

Created for custom Grok use — fork, adapt, and improve!