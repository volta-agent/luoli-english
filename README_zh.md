# ✨ Luo Li English ✨

基于 Luo Li English 魔法主题的三年级下册英语词汇学习应用。

## 功能

- 🃏 **魔法卡片** — 点击翻牌，自动播放发音
- 🎯 **仙法测验** — 英译中 / 中译英 选择题
- 🧩 **灵犀配对** — 英语 ↔ 中文配对游戏，三档难度，支持撤销
- 📖 **词汇宝典** — 按单元（契约）浏览，掌握程度追踪 + 薄弱词复习
- 🔊 **标准发音** — 单词 + 例句（微软 Edge TTS，安娜 + 晓晓音色）
- 🌙 **双主题** — 魔法夜空 / 仙境白昼
- 🌐 **双语界面** — 中文 / English 切换
- 💾 **学习进度** — 掌握度、仙力得分、连续星光（本地保存）
- 🎉 **变身庆祝** — "罗丽魔法！" 蝴蝶与星光彩带

## 内容

取材自《义务教育教科书 英语 三年级下册》（外语教学与研究出版社 2024）
"Words and expressions" 板块，**共 200 词 + 例句 + 800 个音频文件**：

| 单元 | 主题 | 词数 |
|------|------|------|
| 1 | Animal friends 动物朋友 | 24 |
| 2 | Know your body 认识身体 | 24 |
| 3 | Yummy food 美味食物 | 70 |
| 4 | What's your hobby? 我的爱好 | 29 |
| 5 | What time is it? 现在几点了 | 19 |
| 6 | A great week 快乐一周 | 34 |

## 使用

直接用浏览器打开 `index.html` 即可，无需安装。

## 重新生成音频

```bash
python3 generate_audio.py   # 需要: pip install edge-tts
```

## 部署到 GitHub Pages

把 `deploy/` 目录内容推送到仓库，在 Settings → Pages 选择分支发布即可。

## 技术栈

- 纯 HTML/CSS/JavaScript，无框架无构建
- Edge TTS 生成音频
- localStorage 保存进度
