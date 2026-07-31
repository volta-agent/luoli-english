# ✨ Luo Li English ✨

三年级下册英语词汇学习应用 · Luo Li English 魔法主题

A magical English vocabulary learning app for 3rd graders with the
Luo Li English theme — night-sky magic, butterflies, flower petals and
fairy spirits!

## Features

- 🃏 **魔法卡片 Flashcards** — tap to flip, auto-play pronunciation
- 🎯 **仙法测验 Quiz** — multiple choice, EN↔中文 directions
- 🧩 **灵犀配对 Match** — pair English ↔ Chinese with 3 difficulty levels + undo
- 📖 **词汇宝典 Word List** — browse by unit ("契约") with mastery tracking & tricky-word review
- 🔊 **Audio Pronunciation** — Edge TTS (Ana + Xiaoxiao voices), word + example sentence
- 🌙 **Dual Theme** — magical night-sky mode & fairy-palace light mode
- 🌐 **Bilingual UI** — Chinese/English toggle
- 💾 **Progress Tracking** — mastery, score, streak calendar (localStorage)
- 🎉 **Transformation celebrations** — 罗丽魔法! confetti with butterflies & sparkles

## Content

Vocabulary from 《义务教育教科书 英语 三年级下册》(外语教学与研究出版社 2024)
"Words and expressions" section — **200 words** with example sentences:

| Unit | Theme | Words |
|------|-------|-------|
| 1 | Animal friends 动物朋友 | 24 |
| 2 | Know your body 认识身体 | 24 |
| 3 | Yummy food 美味食物 | 70 |
| 4 | What's your hobby? 我的爱好 | 29 |
| 5 | What time is it? 现在几点了 | 19 |
| 6 | A great week 快乐一周 | 34 |

**Total: 200 words · 800 audio files**

## Usage

Simply open `index.html` in any browser — no installation needed!
Works offline after first load (all assets are local).

## Regenerating audio

```bash
python3 generate_audio.py   # needs: pip install edge-tts
```

## Deploy to GitHub Pages

1. Copy the contents of `deploy/` to a repo
2. Settings → Pages → deploy from `main` branch

## Tech Stack

- Plain HTML/CSS/JavaScript (no frameworks, no build step)
- Edge TTS for audio generation
- localStorage for progress saving

## License

MIT — for personal/educational use.
