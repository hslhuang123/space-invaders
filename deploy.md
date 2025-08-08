# Deployment Guide

## GitHub Pages Setup

1. Create GitHub repository:
```bash
# Already done - repository initialized locally
git remote add origin https://github.com/YOURUSERNAME/space-invaders.git
git branch -M main
git push -u origin main
```

2. Enable GitHub Pages:
   - Go to Settings → Pages
   - Source: Deploy from branch
   - Branch: main
   - Your game will be at: https://YOURUSERNAME.github.io/space-invaders/

## Alternative Deployments

### Netlify Drop
1. Go to https://netlify.com/drop
2. Drag space-invaders.html file
3. Get instant URL

### Surge.sh
```bash
npm install -g surge
surge space-invaders.html
```

### Vercel
1. Go to vercel.com
2. Import from GitHub or upload file
3. Get instant deployment

## File Structure
```
space-invaders/
├── space_invaders.html  (main game file)
├── README.md           (project description)
└── deploy.md          (this file)
```