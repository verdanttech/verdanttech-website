# VerdantTech Website — Claude Code Rules

## Repo
- Version B only. Version A is frozen — do not touch.
- Local path: /Users/arikgriffin/Dev/verdanttech-website-b/
- Branch: version-b
- Remote: git@github.com:verdanttech/verdanttech-website.git

## Git Rules
- NEVER use --force or --force-with-lease on this repo under any circumstances
- If a push is rejected, always resolve with: git pull origin version-b
- Standard push command: git -C /Users/arikgriffin/Dev/verdanttech-website-b/ add -A && git commit -m "message" && git push origin version-b
- CNAME file must always be present in repo root — do not delete it

## Build
- Single index.html — all CSS and JS inline, no build step
- No dependencies except Google Fonts
- Assets in /assets/ directory (if present)

## Constraints
- Never use the word "fractional"
- Never use "we" or "our" — one person practice
- Never modify Version A
- SVG coordinate computation: always compute in Python before writing prompts — never compute parametric geometry directly
- Icon fixes: one Claude Code prompt per file — never batch multiple icon fixes
