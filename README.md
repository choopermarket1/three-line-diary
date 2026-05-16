# 오늘의 세 줄 · Three Lines for Today

A cute watercolor-themed 3-line mood diary web app.
귀여운 수채화 컨셉의 3줄 감정 일기 앱.

## Features
- 16 mood emojis with floating animations 🌸
- 3 structured lines: 🌟 Praise / 🔁 Trial & Error / 💡 Insight
- Korean + English language toggle (KO/EN)
- Local-only account system (email + password + contact, stored in browser)
- Watercolor + paper texture aesthetic
- Per-user diary entries (localStorage)

## How to run
Open `index.html` in a browser. No build step needed — uses React via CDN + Babel standalone.

## Tech
- React 18 (UMD)
- Babel Standalone (in-browser JSX)
- Vanilla CSS with SVG noise textures
- Web Crypto API (SHA-256 password hashing)
- localStorage for persistence

## Deploy
Static site — drop on Vercel, Netlify, GitHub Pages, or any static host.
