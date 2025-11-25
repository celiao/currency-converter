# BRL to USD Currency Converter - Web App

A beautiful, production-ready React website for converting Brazilian Reals (BRL) to US Dollars (USD) with live exchange rates.

## 🌐 Live Demo

Visit the live app: [GitHub Pages URL will be here after deployment]

## Features

- 💱 **Live Exchange Rates** - Fetches real-time BRL to USD rates from ExchangeRate-API
- 💰 **Bi-directional Conversion** - Convert from BRL to USD or USD to BRL
- 🎨 **Beautiful UI** - Modern glassmorphism design with Tailwind CSS
- 📱 **Fully Responsive** - Works perfectly on mobile, tablet, and desktop
- ⚡ **No Build Required** - Standalone HTML file that runs directly in the browser
- 🔄 **Auto-refresh** - Manual refresh button to get latest exchange rates
- 🎯 **Production Ready** - Optimized for performance and user experience

## How to Run

### Option 1: Using Python HTTP Server

```bash
cd currency-converter-standalone
python3 -m http.server 8000
```

Then open http://localhost:8000 in your browser.

### Option 2: Open Directly

Simply open `index.html` in any modern web browser. The app will work without a server.

### Option 3: Using Live Server (VS Code)

1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## Technology Stack

- **React 18** - UI framework (loaded via CDN)
- **Tailwind CSS** - Utility-first CSS framework (loaded via CDN)
- **ExchangeRate-API** - Free currency exchange rate API
- **Vanilla JavaScript** - No build tools required

## Design Features

- Gradient background with emerald/teal theme
- Glassmorphism card effect with backdrop blur
- Smooth animations and transitions
- Hover effects and focus states
- Accessible form inputs with proper labels
- Icon-based visual feedback
- Professional color palette

## API Integration

The app uses the free tier of [ExchangeRate-API](https://open.er-api.com):
- Endpoint: `https://open.er-api.com/v6/latest/BRL`
- No API key required
- Falls back to default rate (0.20) if API is unavailable

## Browser Support

Works in all modern browsers:
- Chrome/Edge 90+
- Firefox 88+
- Safari 14+

## File Structure

```
currency-converter-standalone/
├── index.html          # Complete standalone app
└── README.md          # This file
```

## Production Deployment

You can deploy this to any static hosting service:

- **Netlify**: Drag and drop the folder
- **Vercel**: Deploy via CLI or GitHub
- **GitHub Pages**: Push to a repository and enable Pages
- **AWS S3**: Upload and enable static website hosting
- **Cloudflare Pages**: Connect your repository

No build step is required - just upload the `index.html` file!
