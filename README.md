# Steve's Customer Route Planner

Interactive map for planning customer site visits across Australia, built for Bullivants.

## Features

- **Interactive Map**: Click customer markers to build routes
- **Hover Tooltips**: See distance to Bullivants branch and other sites in the same state
- **Route Optimisation**: Auto-optimise using nearest-neighbour algorithm
- **Overnight Suggestions**: Get accommodation recommendations for long trips
- **State Filtering**: Focus on specific regions
- **Drag & Drop**: Manually reorder stops

## Deployment to Vercel

### Option 1: Vercel CLI (Recommended)

```bash
# Install Vercel CLI
npm i -g vercel

# Deploy
cd steve-route-planner
vercel

# Follow prompts, then for production:
vercel --prod
```

### Option 2: GitHub + Vercel

1. Push this folder to a GitHub repository
2. Go to [vercel.com](https://vercel.com)
3. Click "New Project"
4. Import your GitHub repo
5. Vercel auto-detects static site, click "Deploy"

### Option 3: Drag & Drop

1. Go to [vercel.com](https://vercel.com)
2. Drag the `steve-route-planner` folder onto the page
3. Done!

## Files

- `index.html` - Complete standalone application
- `vercel.json` - Vercel deployment configuration

## Customer Data

18 customer sites across 5 states:
- **VIC**: Brooklyn, Sea Lake, Birchip, Charlton, Dimboola
- **SA**: Maitland, Pinnaroo, Mallala, Crystal Brook  
- **NSW**: Kooragang Island, Narrabri, Nyngan, Narromine, West Wyalong, Oaklands, Walgett
- **QLD**: The Gums, Talwood

## Branches

- Melbourne
- Adelaide
- Newcastle
- Wollongong
- Brisbane
