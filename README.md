[README.md](https://github.com/user-attachments/files/27324818/README.md)
# ArchRender — Zone-Based Prompt Engineer

A standalone web app for architects to generate precise AI rendering prompts
by painting material zones over a base Rhino/sketch image.

## What it does

1. Upload a Rhino screenshot or architectural sketch
2. Paint zones on the image (wall, floor, window, facade, etc.)
3. Assign materials, finishes, and colour tones to each zone
4. Set global lighting and atmosphere
5. Generate a precise, zone-aware prompt for Midjourney / DALL·E / Stable Diffusion

## Deploy to Vercel (free, no coding needed)

### Option A — Drag & Drop (easiest)
1. Go to https://vercel.com and sign up free
2. Click "Add New Project"
3. Drag the entire `arch-render-tool` folder into the upload area
4. Click Deploy — your site is live in ~30 seconds

### Option B — GitHub (recommended for updates)
1. Create a free GitHub account at github.com
2. Create a new repository called `arch-render-tool`
3. Upload the files (index.html + vercel.json)
4. Go to vercel.com → Import Git Repository → select your repo
5. Deploy — Vercel auto-deploys on every update

## API Key Setup
- Get your free Anthropic API key at: https://console.anthropic.com
- When you open the app, paste your key into the modal
- The key is stored in your browser only (never sent anywhere except Anthropic)

## Files
- `index.html` — The entire application (self-contained)
- `vercel.json` — Deployment config for Vercel

## Usage tips
- Use a Rhino wireframe or line drawing for best results
- Paint zones generously — overlap is fine
- The more specific your material notes, the better the prompt
- Try Midjourney first — best for architectural aesthetics
