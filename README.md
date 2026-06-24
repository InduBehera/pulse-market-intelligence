# Pulse — Market Intelligence Workspace (HTML Wireframe)

Static HTML wireframe of the Pulse Market Intelligence product. Single-file, no build step, deploys to Vercel as-is.

## What's inside

- `index.html` — the complete wireframe with all 15 markets, 4 tabs, signals, charts, and Ask Pulse AI UI
- Filter dropdowns are interactive: Category, Sub-Market, Formulation, Territory, Period

## Deploy to Vercel (60 seconds)

### Option 1 — Drag and drop (no GitHub needed)

1. Go to https://vercel.com/new
2. Scroll down to "Deploy your project" → click "Drag and drop"
3. Drag this folder onto the upload area
4. Click Deploy
5. You get a live URL like `pulse-xyz.vercel.app`

### Option 2 — Via GitHub

```bash
# In this folder
git init
git add .
git commit -m "Pulse HTML wireframe"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/pulse-html.git
git push -u origin main
```

Then on Vercel:
1. New Project → Import the GitHub repo
2. Framework Preset: **"Other"** (it's just HTML)
3. Click Deploy

## What works

- ✅ All 15 markets in Regional Overview
- ✅ Country, Brand, Company, Portfolio Review tabs (Germany)
- ✅ Locked country views with rollout roadmap for non-Germany
- ✅ Signal cards with evidence
- ✅ Performance trend charts
- ✅ Brand pattern detection heatmap
- ✅ Competitor tables
- ✅ Filter dropdowns (Category, Sub-Market, Formulation, Territory, Period)
- ✅ Ask Pulse AI conversational UI (visual only — no real API in this version)

## Notes

This is a static wireframe — all data is hard-coded in the HTML for demo purposes. The Ask Pulse AI shows example conversations but doesn't call a live LLM. For a working AI version with React + Vercel functions + OpenAI, see the React project (`pulse-mvp`).
