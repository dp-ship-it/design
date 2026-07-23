# Claude Code Skills

This directory vendors the **UI/UX Pro Max** skill package.

- Source: https://github.com/nextlevelbuilder/ui-ux-pro-max-skill
- Version: 2.11.0 · License: MIT (see `../../LICENSE`)

## Installed skills

| Skill | Purpose |
|-------|---------|
| `ui-ux-pro-max` | Core design intelligence: searchable database of 84 styles, 192 palettes, 74 font pairings, UX guidelines, and charts across 22 tech stacks. |
| `design` | End-to-end design: brand identity, logos, CIP mockups, HTML slides, banners, icons, social images. |
| `design-system` | Token architecture (primitive→semantic→component), component specs, slide generation. |
| `ui-styling` | shadcn/ui + Tailwind UI construction, dark mode, canvas-based visuals. |
| `brand` | Brand voice, visual identity, messaging frameworks, asset management. |
| `banner-design` | Social/ad/web/print banners with multiple art directions. |
| `slides` | Strategic HTML presentations with Chart.js and design tokens. |

Claude Code discovers these automatically via each subdirectory's `SKILL.md`.
Invoke one with `/ui-ux-pro-max` (or any skill name), or let Claude pick it up
from context when a design task matches its description.

To update, re-copy `.claude/skills/` from the upstream repo at the desired tag.
