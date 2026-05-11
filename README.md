# 🧘 ZenFlow Lofi - Thiền định vô đối

A serene meditation and focus timer web app with lofi vibes, glassmorphism design, and ambient sounds.

## ✨ Features

### 🎯 Core Timer
- **Default 25-minute Pomodoro timer** with circular progress indicator
- Quick preset buttons: 5m, 10m, 15m, 25m, or Custom duration
- Start, Pause, and Reset controls
- Completion notification with gentle sound effect

### 🎵 Ambient Sounds & Music
- **4 ambient sound options** with individual volume controls:
  - 🌧️ Rain
  - 🌊 Ocean waves
  - 🔥 Fireplace
  - ⚪ White noise
- All sounds loop seamlessly and continue after timer completes
- Background music player with volume control

### 🌅 Visual Design
- **Glassmorphism & Neo-brutalism**: Modern frosted glass effect with blur
- **Dark mode** with gradient background
- **Lofi video backgrounds** with 3 preset options
- **Smooth animations** and transitions
- **Responsive design** for desktop and mobile

### ⚙️ Settings
- Change background videos on the fly
- Customizable timer duration
- Volume controls for all audio elements
- Persistent ambient sound customization

### 📱 User Experience
- **Keyboard shortcuts**: 
  - `SPACE` to Start/Pause timer
  - `R` to Reset
- Mobile-optimized controls (tap to show/hide)
- Smooth glassmorphic UI with shadow effects
- Rotating quotes for meditation inspiration

## 🚀 Quick Start

1. Open `index.html` in a modern web browser
2. No installation or build process required - everything runs locally
3. Click "Start" to begin your meditation session
4. Add ambient sounds and music for the perfect zen atmosphere

## 🎨 Design System

### Colors
- Primary: Indigo (`#6366f1`)
- Dark Background: Slate (`#0f172a`, `#1a1f3a`)
- Text: Light Slate (`#e2e8f0`)
- Glassmorphism: `rgba(15, 23, 42, 0.5)` with `backdrop-filter: blur(10px)`

### Typography
- Font: **Inter**, **Poppins** (via Google Fonts)
- Sans-serif, clean, and modern

### Spacing & Radius
- Rounded corners: 8-16px (glassmorphism aesthetic)
- Glass effect blur: 8-10px
- Border opacity: 10% slate-400

## 📁 File Structure

```
├── index.html      # Main HTML with Tailwind CSS
├── app.js          # JavaScript logic (timer, audio, UI)
└── README.md       # This file
```

## 🔧 Technologies Used

- **HTML5** - Semantic markup
- **Tailwind CSS** - Utility-first styling (via CDN)
- **Vanilla JavaScript** - No frameworks required
- **Web Audio API** - Sound effects and audio management
- **CSS Grid & Flexbox** - Responsive layouts
- **Pexels Videos** - Free lofi background videos

## 🎯 How to Use

### Timer
1. Click a preset button (5m, 10m, 15m, 25m) or "Custom"
2. Enter custom time if needed
3. Press "Start" or hit `SPACE`
4. The circular progress bar fills as time counts down
5. When complete, you'll hear a gentle chime notification

### Ambient Sounds
1. Click the emoji button (🌧️ 🌊 🔥 ⚪) to toggle each sound
2. Adjust volume with the slider below
3. Mix multiple sounds for your perfect zen atmosphere
4. Sounds continue playing even after timer completes

### Music
1. Click the play button ▶️ to start background music
2. Adjust volume with the slider
3. Click skip ⏭️ for next track (placeholder - customize with your playlist)

### Background
1. Click ⚙️ Settings in top right
2. Choose from 3 lofi video backgrounds
3. Videos auto-loop for continuous ambiance

## 🌐 Browser Compatibility

- Chrome/Chromium 60+
- Firefox 55+
- Safari 12+
- Edge 79+

**Note:** Autoplay audio requires user interaction first (click Start button).

## 🔊 Audio Sources

- **Ambient sounds**: Mixkit free audio library
- **Music placeholder**: YouTube Lofi Girl stream (customize with your URL)
- **Sound effects**: Generated with Web Audio API

## 📱 Mobile Support

- Tap to show/hide control panels
- Touch-friendly buttons (40x40px minimum)
- Responsive typography scaling
- Maintains all features on small screens

## ✅ Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `SPACE` | Start/Pause timer |
| `R` | Reset timer |

## 🛠️ Customization

### Change Background Videos
Edit the `backgroundVideos` object in `app.js`:
```javascript
const backgroundVideos = {
    1: "YOUR_VIDEO_URL_1",
    2: "YOUR_VIDEO_URL_2",
    3: "YOUR_VIDEO_URL_3"
};
```

### Add More Ambient Sounds
1. Add new sound to `audioSources` object
2. Add HTML button in the Ambient Sounds section
3. Add toggle function in `app.js`

### Customize Quotes
Edit the `state.quotes` array in `app.js` to add your meditation affirmations.

## 🐛 Troubleshooting

**Audio not playing?**
- Check browser's autoplay policy (requires user interaction)
- Try clicking Start button first
- Check browser console for errors

**Video not loading?**
- Verify internet connection
- Try different background option
- Videos are loaded from Pexels CDN

**Mobile controls not showing?**
- Tap the center timer area to toggle controls visibility

## 📝 Notes

- All settings are stored in the `state` object (easily extensible to localStorage)
- Ambient sounds use `<audio>` loops for seamless playback
- Timer uses `setInterval` for reliable counting
- Glassmorphism effect works best on modern browsers

## 🎁 Future Enhancements

- [ ] localStorage persistence (save user preferences)
- [ ] Custom ambient sound upload
- [ ] Pomodoro statistics tracking
- [ ] Dark/Light theme toggle
- [ ] Multiple languages
- [ ] Export meditation sessions to calendar

## 💝 Credits

- Design inspiration: Lofi Girl aesthetics
- Background videos: Pexels
- Audio: Mixkit
- Icons: Unicode emoji
- Fonts: Google Fonts

---

**Made with 🧘 and ✨ for peace and focus.**

*Thiền định là hành trình, không phải đích đến.*
