# 🚀 Bitcoin Real-Time Price Tracker

A clean, minimalist Bitcoin (BTCUSDT) price tracker with real-time updates and 24-hour price chart. Optimized for 24/7 monitoring on mobile devices and desktop browsers.

![Bitcoin Tracker](https://img.shields.io/badge/Bitcoin-Live%20Price-orange?style=for-the-badge&logo=bitcoin)
![WebSocket](https://img.shields.io/badge/WebSocket-Real--time-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

## ✨ Features

- **⚡ Real-Time Price Updates** - WebSocket connection provides instant price changes (multiple updates per second)
- **📊 24-Hour Chart** - Interactive line chart showing last 24 hours of price movement with 1-minute candles
- **🎨 Dynamic Color Coding** - Green for price increases, red for decreases
- **📱 Mobile Optimized** - Responsive design for both portrait and landscape modes
- **🖥️ Fullscreen Mode** - Immersive chart view with auto-hiding controls
- **🔋 Battery Efficient** - Pauses updates when tab is hidden or backgrounded
- **🌐 Zero Backend** - Pure frontend, no server required
- **⚙️ Auto-Reconnect** - WebSocket automatically reconnects if connection drops

## 🎯 Live Demo

**[View Live Demo →](https://foxy1402.github.io/btc-tracker/)**

## 🛠️ Technology Stack

- **HTML5/CSS3/JavaScript** - Pure vanilla JS, no frameworks
- **Chart.js** - Lightweight charting library
- **Binance WebSocket API** - Real-time price streaming
- **Binance REST API** - Historical candlestick data

## 📦 Installation & Deployment

### Option 1: GitHub Pages (Recommended)

1. Fork or clone this repository
2. Go to **Settings** → **Pages**
3. Set source to `main` branch
4. Your site will be live at `https://yourusername.github.io/repo-name`

### Option 2: Netlify Drop

1. Visit [netlify.app/drop](https://app.netlify.com/drop)
2. Drag and drop the `index.html` file
3. Get instant URL (e.g., `crypto-tracker-abc123.netlify.app`)

### Option 3: Local Development

Simply open `index.html` in any modern browser. No build process required!

```bash
git clone https://github.com/yourusername/btc-tracker.git
cd btc-tracker
# Open index.html in your browser
