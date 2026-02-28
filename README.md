# Clean Room 3D Layout — Molding Operations

Interactive 3D visualization of ISO Class 8 clean room facility layout.

## Quick Deploy

### 1. GitHub
```bash
# Create repo on GitHub, then:
git init
git add .
git commit -m "Initial: 3D clean room layout"
git branch -M main
git remote add origin https://github.com/YOUR_USER/cleanroom-3d-layout.git
git push -u origin main
```

### 2. Vercel
1. Go to [vercel.com](https://vercel.com) and sign in with GitHub
2. Click **"Add New Project"**
3. Import your `cleanroom-3d-layout` repo
4. Framework Preset: **Other**
5. Build Command: leave empty
6. Output Directory: `.`
7. Click **Deploy**

Your site will be live at `https://cleanroom-3d-layout.vercel.app` (or similar).

## Features
- 7 injection molding machines (6×400T + 1×300T)
- Resin & Chiller room with feeder systems and piping
- Mobile gantry crane with 16-cavity mold
- Quality room with 2× OGP vision systems
- Ground floor supersack resin supply system
- Interactive 3D controls (rotate, zoom, pan)
- Hover tooltips on all equipment
- Responsive design
