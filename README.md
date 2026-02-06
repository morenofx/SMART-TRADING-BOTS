# AutoTrader EA - Website

> Professional landing page for XAU_AutoTrader and BTC_AutoTrader with AI-powered chatbot support.

## 🚀 Deploy to Vercel (5 minutes)

### Step 1: Upload to GitHub

1. Create a new repository on GitHub (e.g., `autotrader-website`)
2. Upload all files from this folder:
   ```
   autotrader-website/
   ├── index.html
   ├── api/
   │   └── chat.js
   ├── images/
   │   ├── XAU_AUTOTRADER.png
   │   └── BTC-COIN.png
   ├── vercel.json
   └── README.md
   ```

### Step 2: Connect to Vercel

1. Go to [vercel.com](https://vercel.com) and sign in with GitHub
2. Click **"Add New Project"**
3. Select your `autotrader-website` repository
4. Click **"Deploy"**

### Step 3: Configure API Key

1. In Vercel dashboard, go to **Settings** → **Environment Variables**
2. Add a new variable:
   - **Name:** `ANTHROPIC_API_KEY`
   - **Value:** `sk-ant-api...` (your Anthropic API key)
3. Click **Save**
4. Go to **Deployments** and click **"Redeploy"**

### ✅ Done!

Your site will be live at `https://your-project.vercel.app`

---

## 📁 File Structure

```
autotrader-website/
├── index.html          # Main page (tech/programmer style)
├── api/
│   └── chat.js         # Serverless API for chatbot
├── images/
│   ├── XAU_AUTOTRADER.png
│   └── BTC-COIN.png
├── vercel.json         # Vercel configuration
└── README.md           # This file
```

## 🔒 Security

- Anthropic API key is hidden server-side
- Users cannot see or access the key
- All AI requests go through `/api/chat`

## 🔗 Product Links

**XAU_AutoTrader (Gold)**
- Buy: https://www.mql5.com/en/market/product/161171
- Signals: https://www.mql5.com/en/signals/2352316

**BTC_AutoTrader (Bitcoin)**
- Buy: https://www.mql5.com/en/market/product/129310
- Signals: https://www.mql5.com/en/signals/2339222

## 📝 Customization

**To modify the website**, edit `index.html`:
- Prices: search for `$30`
- Text: modify HTML directly
- Colors: edit CSS variables in `:root`

**To modify chatbot responses**, edit `api/chat.js`:
- Knowledge base is in the `EA_KNOWLEDGE` variable

---

## 🎨 Design Features

- **Tech/Programmer aesthetic** with monospace fonts
- **Terminal-style** code blocks and UI elements
- **Neon green** accent color (#00FF41)
- **Gold** for XAU product (#FFD700)
- **Orange** for BTC product (#F7931A)
- **Scanline effect** for retro feel
- **Responsive** design for mobile

---

© 2025 Moreno Dainese
