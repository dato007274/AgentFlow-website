# AgentFlow Website

## Critical files — always include in git commits
- `index.html` — the entire landing page (single file)
- `dc53e34b754bf0b0b781ebaad54ded58_1_1776496291_9089.mp4` — scroll-driven hero video, MUST be committed and pushed

## Never commit
- `.claude/` — Claude Code internal files (already in .gitignore)

## Deployment
- Hosted on Vercel
- GitHub repo: https://github.com/dato007274/AgentFlow-website
- Vercel auto-deploys on push to `main`
- The MP4 video must be present in the repo root for the hero animation to work
