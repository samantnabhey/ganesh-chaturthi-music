# गणपती बाप्पा मोरया — Ganesh Chaturthi Music

A minimalist music player for Ganesh Chaturthi celebrations. Stream curated playlists with a beautiful, festive UI.

## Features

- 🎵 **YouTube Music Integration** — Stream any public YouTube Music playlist
- 🎨 **Festive Design** — Orange/gold gradient, smooth animations, mobile-responsive
- 📊 **Live Counter** — Shows how many people are celebrating in real-time
- ⏸️ **Custom Controls** — Play, pause, next, previous, seek, duration
- ☕ **Support Integration** — Built-in donation button (Buy Me a Coffee, UPI, etc.)
- 🚀 **Zero Backend** — Purely static HTML/CSS/JS, deploy anywhere

## Quick Start

### 1. Create Your Ganesh Chaturthi Playlist
- Go to [YouTube Music](https://music.youtube.com)
- Create or find a playlist of Ganesh aartis, bhajans, or DJ remixes
- Copy the playlist ID from the URL: `music.youtube.com/playlist?list=**YOUR_PLAYLIST_ID**`

### 2. Configure
Edit `index.html` and replace:
- Line 289: `const PLAYLIST_ID = '...'` → your playlist ID
- Line 223: The "Open Playlist" button link
- Line 225: Update donation link (Buy Me a Coffee, UPI handler, etc.)
- Line 231: Footer credits with your name/website

### 3. Deploy
Pick your hosting:
- **Vercel** (1 click): Drag & drop `index.html` → live
- **Netlify**: Same process
- **GitHub Pages**: Push repo, enable in settings
- **Custom domain**: Any static host (AWS S3, Cloudflare Pages, etc.)

## Project Structure

```
ganesh-chaturthi-music/
├── index.html          # Main page (all-in-one HTML)
├── README.md           # This file
├── .gitignore          # Git ignore rules
└── ROADMAP.md          # Future features & ideas
```

## Customization

### Colors
- Primary: `#FF6B35` (orange) → change in CSS gradient sections
- Secondary: `#D32F2F` (red) → accent color
- Tertiary: `#FFC107` (gold) → highlight

### Text
- Hero title: Update `<h1>गणपती बाप्पा मोरया</h1>`
- Subtitle: Update `<p>Ganesh Chaturthi Music</p>`
- Footer: Credits and links

### Live Counter
Currently simulated. To add real-time stats:
- Use Firebase Realtime DB for presence
- Set up a simple backend counter endpoint
- Track via Google Analytics event tags

## Browser Support

- ✅ Chrome/Edge 90+
- ✅ Firefox 88+
- ✅ Safari 14+
- ✅ Mobile browsers (iOS Safari, Chrome Android)

## Known Limitations

- YouTube IFrame API has CORS restrictions (no custom track info extraction)
- Playlist must be public on YouTube Music
- Player works in browser only (no native mobile app)

## Roadmap

See [ROADMAP.md](ROADMAP.md) for upcoming features.

## License

MIT — build, share, remix freely.

---

Made with ❤️ for Ganesh Chaturthi celebrations.