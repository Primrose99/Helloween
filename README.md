# 🎃 HELLOWEEN RADIO

> *Where Every Night Is Halloween*

A 24/7 Halloween-themed internet radio station website. Built with vanilla HTML, CSS, and JavaScript. No frameworks, no build tools — just upload and it works.

**Live site:** [https://primrose99.github.io/Helloween](https://primrose99.github.io/Helloween)

---

## 🔮 Features

- 🎧 Live stream player (plug in any Shoutcast / Icecast / Zeno.fm stream URL)
- 📻 Animated audio visualizer
- 🧟 Now Playing display with rotating song history ("Crypt of Sounds")
- 🦇 Floating Halloween particle effects
- 👻 Fully responsive — works on mobile
- ⚡ Zero dependencies, loads instantly

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/primrose99/Helloween.git
cd Helloween
```

### 2. Add your stream URL
Open `index.html` and find this line:
```html
<source src="YOUR_STREAM_URL_HERE" type="audio/mpeg"/>
```
Replace with your actual radio stream. Free stream hosting options:
- [Zeno.fm](https://zeno.fm) — free tier available
- [Radio.co](https://radio.co) — free trial
- [Shoutcast](https://shoutcast.com) — classic option
- [Icecast](https://icecast.org) — open source, self-hosted

### 3. Update the song history
Find the `songs` array in `index.html` and update with your playlist:
```javascript
const songs = [
  { title:"Your Song", artist:"Artist Name", time:"NOW", emoji:"🎃" },
];
```

### 4. Test locally
Open `index.html` in your browser — no server needed.

---

## 🌐 Deploy to GitHub Pages (free hosting)

1. Push your code to this repo
2. Go to **Settings → Pages**
3. Under Source: select `main` branch → `/ (root)` → **Save**
4. Live at `https://primrose99.github.io/Helloween` in ~60 seconds

---

## 📁 File Structure

```
Helloween/
├── index.html   ← The entire site (one file!)
└── README.md    ← This file
```

*Built with [Claude AI](https://claude.ai) · Hosted on GitHub Pages*
