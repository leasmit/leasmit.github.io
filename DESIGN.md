# Design System

<!-- impeccable:design-tokens 1 -->

## Design Philosophy

- **Vibe**: Scholarly, modern, oceanic, and legible. Tailored for academic peers and conservation bodies.
- **Palette**: Deep navy body surfaces, oceanic primary blues, and teal accents evoking southern African marine ecosystems and pelagic fieldwork.
- **Contrast Standard**: Strict WCAG AA compliance (4.5:1+ for normal text, 3:1+ for large headings).

---

## Design Tokens

### Color Palette

#### Light Theme
- `--bg-body`: `#f8fafc` (slate-50)
- `--bg-surface`: `#ffffff`
- `--bg-surface-glass`: `rgba(255, 255, 255, 0.92)`
- `--bg-card`: `#ffffff`
- `--bg-card-hover`: `#f1f5f9`
- `--bg-pill`: `#e0f2fe`
- `--text-pill`: `#0369a1`
- `--text-primary`: `#0f172a` (slate-900)
- `--text-secondary`: `#334155` (slate-700)
- `--text-muted`: `#64748b` (slate-500)
- `--primary`: `#0369a1` (sky-700, 4.7:1 contrast on white)
- `--primary-dark`: `#075985` (sky-800)
- `--primary-light`: `#e0f2fe` (sky-100)
- `--accent`: `#0f766e` (teal-700, 4.8:1 contrast on white)
- `--accent-light`: `#ccfbf1` (teal-100)
- `--accent-dark`: `#115e59` (teal-800)
- `--border`: `#e2e8f0` (slate-200)
- `--border-strong`: `#cbd5e1` (slate-300)

#### Dark Theme
- `--bg-body`: `#0b1120`
- `--bg-surface`: `#131d31`
- `--bg-surface-glass`: `rgba(19, 29, 49, 0.92)`
- `--bg-card`: `#162238`
- `--bg-card-hover`: `#1c2b46`
- `--bg-pill`: `#082f49`
- `--text-pill`: `#38bdf8`
- `--text-primary`: `#f8fafc`
- `--text-secondary`: `#cbd5e1`
- `--text-muted`: `#94a3b8`
- `--primary`: `#38bdf8`
- `--primary-dark`: `#0284c7`
- `--primary-light`: `#082f49`
- `--accent`: `#2dd4bf`
- `--accent-light`: `#134e48`
- `--accent-dark`: `#14b8a6`
- `--border`: `#1e293b`
- `--border-strong`: `#334155`

---

## Typography Hierarchy

- **Primary Font**: `Lato` (`'Lato', -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Helvetica Neue", Arial, sans-serif`)
- **Monospaced Font**: `ui-monospace, SFMono-Regular, Menlo, Monaco, Consolas, monospace`
- **Body Line Height**: `1.65` (accessible, comfortable reading rhythm)
- **Headings**:
  - `h1.page-title`: `2.15rem`, weight 800, line-height `1.25`
  - `h2.section-heading`: `1.35rem`, weight 700, line-height `1.3`
  - `h3.card-title` / `h3.timeline-title`: `1.15rem` – `1.25rem`, weight 700, line-height `1.35`
  - Body text (`p`): `1rem`, color `var(--text-secondary)`, line-height `1.65`

---

## Layout & Components

1. **Header & Navigation**:
   - Sticky blur bar (`backdrop-filter: blur(12px)`).
   - Minimal typographic brand without icon for clean academic presentation.
   - Inset container (`max-width: 1160px`).
   - Accessible touch targets (minimum 44px) and clear active indicators.
2. **Badges & Tags (`.badges-row`)**:
   - Horizontally aligned badges with matching 26px height, line-height, and padding.
3. **Cards (`.card`)**:
   - Substantial padding (`1.5rem` minimum, inset children).
   - Subtle border with soft shadow (`0 1px 2px rgba(0,0,0,0.05)`).
   - Hover lift (`transform: translateY(-2px)`).
4. **Timeline (`.timeline`)**:
   - Monospaced year badge for temporal clarity.
   - Generous content box padding (`1.25rem 1.5rem`).
5. **Pills & Badges (`.badge-pill`, `.card-tag`)**:
   - Title case or sentence case (avoids all-caps fatigue).
   - Rounded full pill with matching tinted background.
6. **Print Styles**:
   - Clean black-and-white output with preserved margins and insets.
   - Uncluttered presentation suitable for academic tenure and grant reviews.

