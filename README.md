# YouTube Livestream Embed Viewer

A clean, minimalist YouTube video/livestream player with no clutter. Perfect for monitoring streams in small windows without YouTube's interface.

🔗 **Live Site:** [https://embed-livestream.pages.dev](https://embed-livestream.pages.dev)

---

## ✨ Features

- 🎥 **Clean Player** - Embed any YouTube video or livestream without YouTube's UI
- 📺 **Works with Unlisted Videos** - Supports public, unlisted, and private (with link) content
- 📝 **History Menu** - Automatically saves your last 10 unique links with timestamps
- 🎨 **Neon-Styled UI** - Modern, glowing interface with smooth animations
- 💾 **Local Storage** - History saved privately on your browser (not shared)
- 📋 **Quick Actions** - Copy/Paste links with one click
- ⚡ **Fast & Lightweight** - Just HTML, CSS, and vanilla JavaScript

---

## 🚀 How to Use

1. **Visit the site:** [https://embed-livestream.pages.dev](https://embed-livestream.pages.dev)
2. **Paste a YouTube link** (livestream, video, unlisted, public - anything!)
3. **Click "Load Stream"** - Your video plays instantly
4. **History saved** - Access your recent links anytime from the neon menu

---

## 📖 Examples

Works with any YouTube URL format:

```
https://www.youtube.com/watch?v=VIDEO_ID
https://www.youtube.com/live/VIDEO_ID
https://youtu.be/VIDEO_ID
VIDEO_ID (just the 11-character ID)
```

---

## 🎯 Use Cases

- **Monitor livestreams** in a small window while working
- **Share unlisted videos** without exposing the link publicly (you share the player link + video link separately)
- **Clean viewing experience** without recommendations, comments, or distractions
- **Multi-monitor setups** - keep streams visible on secondary displays

---

## 🔒 Privacy & Security

- ✅ **No tracking** - We don't collect any data
- ✅ **Local storage only** - History saved on your device, never shared
- ✅ **Secure** - Hosted on Cloudflare Pages with HTTPS
- ✅ **Open source** - All code visible in this repository

---

## 🛠️ Tech Stack

- **HTML5** - Structure
- **CSS3** - Neon-styled UI
- **Vanilla JavaScript** - Functionality
- **localStorage** - Client-side history
- **Cloudflare Pages** - Hosting & Analytics

---

## 📊 For Developers

### Local Development

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/embed_livestream.git
   ```

2. Open `index.html` in your browser

3. For unlisted videos, run a local server:
   ```bash
   python -m http.server 8000
   ```
   Then visit: `http://localhost:8000/`

### Deployment

- **Cloudflare Pages** - Auto-deploys from `main` branch
- **GitHub Pages** - Can also be deployed (but no analytics)

---

## 📝 License

MIT License - Feel free to use, modify, and share!

---

## 🤝 Contributing

Issues and pull requests welcome! This is a simple project but open to improvements.

---

## 💡 Tips

- **Unlisted videos:** The video link is never stored in the code - you share it separately for security
- **Small window:** Resize your browser window - the player adapts perfectly
- **Keyboard shortcut:** Press `Enter` after pasting a link to load it instantly
- **Clear history:** Click the red "Clear History" button in the menu

---

Made with 💙 for clean, distraction-free video watching
