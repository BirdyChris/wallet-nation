# Wallet Nation — Brand spec

Updated 2026-07-14 — palette migrated from sage green to neon lime + olive.

## Color tokens

```css
--bg:      #ffffff;             /* white base */
--surface: #fafaf8;             /* near-white */
--fg:      #171717;             /* near-black */
--muted:   #6B7280;             /* gray */
--border:  #E5E7EB;             /* light gray */
--accent:  #C9FA49;             /* neon lime — primary CTAs, highlights, active states */
--deep:    #4B5A34;             /* muted olive — secondary fills, icon chips, hover, gradient depth */
--tint:    #F4F9EE;             /* very light off-white-green — section backgrounds only */
```

## Typography

- **Display**: `'Nunito', 'Quicksand', -apple-system, system-ui, sans-serif` (bold, rounded geometric)
- **Body**: `'Inter', -apple-system, 'Segoe UI', system-ui, sans-serif`

## Button system

| Button | Style |
|---|---|
| Primary | Fill `var(--accent)` (#C9FA49), dark text, hover → `var(--deep)` (#4B5A34) |
| Secondary | Fill `var(--deep)` (#4B5A34), white text, hover → darker olive |

## Partner strip

Full-bleed diagonal gradient band below hero: #C9FA49 → #4B5A34. Displays brand names in dark (#171717) text.

## UI patterns

- Cards: 12px radius, `var(--border)` stroke, soft shadow, white bg
- Section labels: uppercase, `var(--accent)` color, 0.08em letter-spacing
- Nav: sticky, logo left, links center, primary CTA right
- Hero decor: offset card mockup SVG with dark face, #4B5A34 gradient, neon lime corner block