# LexAI — Intelligent Legal Case Assistant

**Hackathon Demo** | AI-powered legal case management tool

## 🎯 Problem
Lawyers waste hours every week on case summarization, deadline tracking, conflict checks, and outcome estimation. Existing tools are either too basic or too expensive/complex.

## 💡 Solution
LexAI is an intelligent case assistant that uses AI to:
- Auto-summarize cases
- Score priority & predict deadlines
- Generate visual case timelines
- Detect conflicts of interest
- Predict case outcomes (win probability + settlement likelihood)

## ✨ Key Features

### Technical
- Working AI logic simulation with real data flow & state management
- Auto-summarization
- Priority scoring engine
- Deadline prediction
- Smart search across cases

### Innovation
- AI Case Timeline Generator
- Conflict-of-Interest Detector
- Predictive Case Outcome model

### UX
- Clean Dashboard → Detail flow
- Dark mode (default)
- Toast notifications
- Keyboard shortcuts (`Ctrl+K`, `Esc`, `?`, `T`)
- Fully responsive

### Impact
- Shows quantified metrics: **~4.2 hours saved per lawyer per week**
- Cost savings visualization on dashboard

## 🚀 How to Run Locally

### Option 1: Simple (Recommended)
Just open `index.html` in any modern browser.

### Option 2: Using Live Server
```bash
# If you have VS Code
# Install "Live Server" extension → Right click index.html → Open with Live Server
```

### Option 3: Python
```bash
python -m http.server 8000
# Then open http://localhost:8000
```

### Option 4: Node
```bash
npx serve .
```

## ⌨️ Keyboard Shortcuts
| Shortcut     | Action                |
|--------------|-----------------------|
| `Ctrl + K`   | Focus Smart Search    |
| `Esc`        | Back to Dashboard     |
| `?`          | Show shortcuts        |
| `T`          | Toggle theme          |

## 🛠 Tech Stack
- Pure HTML + Tailwind CSS (CDN)
- Vanilla JavaScript
- No build step required
- Fully client-side (perfect for quick demos)

## 📦 Deploy

### Vercel / Netlify / GitHub Pages
1. Push this repo to GitHub
2. Connect to Vercel/Netlify → Deploy
3. Or enable GitHub Pages (Settings → Pages → Deploy from main branch)

### One-click Vercel
[![Deploy with Vercel](https://vercel.com/button)](https://vercel.com/new)

## 📊 Demo Flow for Judges
1. Show **Impact Dashboard** first (hours saved metrics)
2. Open a **Critical** priority case
3. Run the 4 AI features one by one:
   - AI Summarize
   - Generate Timeline
   - Conflict Check
   - Predict Outcome
4. Demonstrate Smart Search + Filters
5. Show keyboard shortcuts

## 📁 Project Structure
```
legal-ai-demo/
├── index.html          # Main application
├── README.md           # This file
└── assets/             # (optional future assets)
```

## ⚠️ Note
This is a **hackathon demo**. AI features are simulated with realistic delays and responses for demonstration purposes. In production these would connect to real LLM APIs + legal databases.

---

Built for Hackathon 2026 ⚖️
