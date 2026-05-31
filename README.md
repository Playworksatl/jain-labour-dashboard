# Jain Labour Dashboard

A live intelligence dashboard for the Jain project, published via GitHub Pages.

**Live URL:** https://Playworksatl.github.io/jain-labour-dashboard/

## How to Update the Dashboard

Run these commands in Terminal whenever you make changes to the HTML file:

cd /Users/michelleaudas/labour-market-intelligence/dashboard/
cp jain_labour_dashboard.html index.html
git add index.html && git commit -m "Update dashboard" && git push

When prompted for a password, right-click in Terminal and select Paste to enter your GitHub Personal Access Token. The token will not appear visually — just press Enter after pasting.

Changes go live within 60–90 seconds.

## GitHub Token

- Stored securely (not in this file)
- Found at: GitHub → Settings → Developer Settings → Personal Access Tokens
- Required scope: repo
- If your token expires, generate a new classic token with the repo scope checked

## File Structure

| File | Purpose |
|---|---|
| jain_labour_dashboard.html | Master source file — edit this one |
| index.html | Copy of above — served by GitHub Pages |
| README.md | This file |
