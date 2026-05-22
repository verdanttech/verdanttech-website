# VerdantTech Website — Claude Code Rules

## Repo
- Version C only. Versions A and B are frozen — do not touch.
- Local path: /Users/arikgriffin/Projects/verdanttech-website-c/
- Branch: version-c
- Live at: verdanttechsolutions.com

## Git Rules
- NEVER use --force or --force-with-lease on this repo under any circumstances
- If a push is rejected, always resolve with: git pull origin version-c
- Standard push command: git -C /Users/arikgriffin/Projects/verdanttech-website-c/ add -A && git commit -m "message" && git push origin version-c
- CNAME file must always be present in repo root — do not delete it

## Build
- Single index.html — all CSS and JS inline, no build step
- No dependencies except Google Fonts
- Assets in /assets/ directory

## Constraints
- Never use the word "fractional"
- Never use "we" or "our" — one person practice
- Never modify Versions A or B
- SVG coordinate computation: always compute in Python before writing prompts — never compute parametric geometry directly
- Icon fixes: one Claude Code prompt per file — never batch multiple icon fixes
