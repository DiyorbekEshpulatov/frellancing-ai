# FreelanceAI Platform

AI agentlar yordamida freelance ishlarni avtomatlashtirish platformasi.

## Agentlar
- 📱 SMM Agent — Instagram, Telegram postlari
- ✍️ Copywriter — Reklama matnlari
- 🌐 Tarjimon — Ko'p tillarda tarjima
- 📧 Email Agent — Biznes xatlar
- 🎨 Dizayn Brief — Kreativ yo'nalish
- 📄 Taklif Yozuvchi — Freelance proposal
- 🔍 SEO Agent — SEO maqolalar
- 🎬 Video Skript — YouTube/Reels
- 💬 Chatbot Javoblari — Support matnlar
- 📋 CV / Rezyume — Karera hujjatlari

## Vercel'ga Deploy qilish

### 1-usul: GitHub orqali (tavsiya)

1. [github.com](https://github.com) da yangi repo yarating
2. Bu fayllarni repo'ga yuklang
3. [vercel.com](https://vercel.com) ga kiring → "New Project"
4. GitHub repo'ni ulang → Deploy bosing
5. 1 daqiqada tayyor!

### 2-usul: Vercel CLI

```bash
npm i -g vercel
cd freelance-ai-platform
vercel
```

### 3-usul: Drag & Drop

1. [vercel.com/new](https://vercel.com/new) ga kiring
2. Bu papkani drag & drop qiling
3. Deploy!

## Ishlatish

1. Saytni oching
2. "API Kalit" tugmasini bosing
3. [console.anthropic.com](https://console.anthropic.com) dan API kalit oling
4. Kalitni kiriting → Saqlang
5. Agent tanlang → So'rov yozing → Ishga tushiring!

## Texnologiyalar

- Pure HTML/CSS/JS (framework yo'q)
- Claude API (Anthropic)
- LocalStorage (kalit xavfsiz saqlash)
