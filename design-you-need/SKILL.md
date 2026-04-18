---
name: design-you-need
description: |
  Frontend design superpower for AI coders. Produces production-quality,
  non-slop frontends. Use PROACTIVELY when building, revamping, redesigning,
  or fixing any frontend UI — landing pages, SaaS, e-commerce, portfolios,
  dashboards, or any web interface. Detects and eliminates AI slop patterns.
argument-hint: <task-type> [create|revamp|fix-slop|redesign]
risk: unknown
source: custom
---

# Frontend Design Superpower

Expert-level frontend design skill derived from forensic analysis of 399 award-winning Dribbble web design projects. Produces frontends that look designer-crafted, not AI-generated.

## Use this skill when

- Building any frontend from scratch (landing page, SaaS, e-commerce, portfolio, dashboard)
- Revamping or redesigning an existing UI
- Fixing AI-generated "slop" — generic, template-looking interfaces
- Reviewing frontend code for design quality
- Choosing color palettes, typography, layout patterns, or animation strategies

## Task Types

### `/design-you-need create <category>`
Build a new frontend from scratch with designer-level craft.

### `/design-you-need revamp`
Analyze existing code and upgrade it to high-craft quality.

### `/design-you-need fix-slop`
Detect AI slop patterns and systematically eliminate them.

### `/design-you-need redesign`
Complete redesign — new aesthetic direction with implementation plan.

---

## Core Design Intelligence

### Aesthetic Signatures (from 399 projects)

| Aesthetic | Count | When to use |
|-----------|-------|-------------|
| **dark-luxury** | 98 | Premium brands, crypto, automotive, luxury goods |
| **warm-minimal** | 94 | E-commerce, food, wellness, real-estate |
| **minimal-corporate** | 64 | SaaS, fintech, corporate, B2B |
| **bold-expressive** | 31 | Agency, portfolio, creative brands |
| **organic-natural** | 28 | Food, wellness, beauty, eco-brands |
| **dimensional-layered** | 28 | Tech products, AI products, innovative brands |
| **editorial** | 26 | Fashion, luxury, portfolio, cultural brands |
| **glassmorphism** | 16 | Dashboards, crypto, AI tools |
| **retro-modern** | 8 | Food, creative, nostalgic brands |
| **neo-brutalist** | 2 | Experimental, artistic portfolios |

### Hero Layout Patterns

| Pattern | Count | Best for |
|---------|-------|----------|
| **layered** | 118 | Premium feel — z-index stacking, overlapping elements |
| **left-right** | 81 | Product showcases, SaaS — text + visual split |
| **centered** | 81 | Bold statements, event pages, luxury brands |
| **full-bleed** | 54 | Photography-heavy, travel, real-estate |
| **split-50-50** | 37 | E-commerce, comparison, dual-focus pages |

### Color Strategy

| Type | Count | Rule |
|------|-------|------|
| **neutral-plus-accent** | 255 | 90% neutral palette + ONE accent color for CTAs only |
| **dark-theme** | 68 | #0A-#15 range backgrounds, not pure #000 |
| **analogous** | 46 | Adjacent hue families for warmth/cohesion |
| **monochromatic** | 24 | Single hue at varying lightness — ultimate sophistication |

---

## The Anti-Slop Rulebook

**87 out of 399 projects were flagged as slop.** These are the patterns that make frontends look AI-generated:

### Slop Red Flags — NEVER do these:

1. **Lorem ipsum or placeholder text** — Even "User1341398" repeated testimonials
2. **Generic stock photos** with no brand-specific treatment or art direction
3. **Inconsistent spacing** — No vertical rhythm, random padding values
4. **Template section ordering** — hero → features → pricing → testimonials → FAQ without variation
5. **Gradient CTA buttons** with no design system justification — the Canva/PSD default
6. **Decorative 3D blobs/shapes** that serve no compositional purpose
7. **Excessive color shifts** between sections with no cohesive palette
8. **Typography chaos** — 3+ competing typefaces with no hierarchy logic
9. **Cookie-cutter cards** — White rectangles with no shadow hierarchy or hover refinement
10. **Badge/pill labels** like "Project Overview", "Our Services" — Behance template tropes
11. **Countdown timers** and fake urgency — direct-response clichés
12. **Unrelated images** mixed into the project — portfolio padding
13. **AI-generated imagery** with telltale glossy renders and impossible patterns
14. **Watermark-style background text** used as lazy decorative filler
15. **Generic nav labels**: HOME, ABOUT, SERVICES, CONTACT with no personality

### What High-Craft Projects Do Instead (288 scored 7+):

1. **Intentional constraint** — Limit to 2 fonts, 1 accent color, one layout grid
2. **Photography as color palette** — Extract tones from hero image for entire UI
3. **Typographic scale contrast** — 120px headlines vs 12px labels creates hierarchy WITHOUT color
4. **One bold moment** — A single extraordinary visual element > ten generic sections
5. **Restraint IS luxury** — Asymmetric whitespace > ornate decoration
6. **Custom everything** — 312/399 projects use custom components, not libraries
7. **Section rhythm** — Alternate dark/light, wide/narrow, image-left/image-right
8. **Decorative elements with purpose** — noise-texture for warmth, gradient-overlay for depth, not random blobs
9. **Micro-interactions that reward** — Card hover lift translateY(-4px), CTA arrow translateX on hover
10. **Letter-spacing on uppercase** — Always 0.05-0.2em tracking on uppercase text

---

## Typography System

### Heading Fonts (top performers)
- **Playfair Display** / similar transitional serif — luxury, editorial, fashion
- **Inter / SF Pro Display** — clean tech, SaaS, corporate
- **Custom serif** — unique brand identity
- **Cormorant Garamond** — organic luxury, warm-minimal
- **Neue Montreal / Satoshi** — modern geometric, dark-luxury

### Body Fonts
- **Inter** — universal workhorse, pair with any display font
- **DM Sans** — slightly warmer than Inter, good for friendly brands
- **Plus Jakarta Sans** — modern SaaS aesthetic
- **Manrope** — geometric with personality

### Typography Rules
- Hero headline: **48-160px** depending on layout (bigger = bolder statement)
- Body text: **14-16px**, line-height **1.5-1.7**
- Uppercase labels: **11-13px** with **letter-spacing: 0.1-0.2em**
- Section headings: **32-48px** with **-0.02em** letter-spacing
- Stats/numbers: **56-140px** bold — biggest typographic contrast element
- Max body width: **640-720px** — never wider for readability

---

## Layout & Spacing System

### Section Spacing
- Between major sections: **80-160px** padding
- Within sections: **40-60px** gaps
- Card gaps: **16-24px**
- Container max-width: **1200-1440px** centered

### Grid Patterns
- **Asymmetric splits**: 40/60 or 55/45 — never perfectly centered (breaks template feel)
- **Bento grid**: CSS Grid with `grid-template-areas` for dashboard-style layouts
- **3-column flush**: Equal columns with generous gutters
- **Offset stacking**: Images overlapping by 20-40px with subtle box-shadows

### Decorative Elements (ranked by usage)
1. **watermark-text** (22) — Oversized faded text behind sections
2. **gradient-overlay** (20) — On hero images for text contrast
3. **radial-glow** (15) — Colored light bloom behind key elements
4. **glass-card** (14) — `backdrop-filter:blur(12px)` + rgba borders
5. **noise-texture** (12) — SVG filter or background-image for warmth
6. **gradient-blob** (11) — Blurred colored orbs for depth
7. **concentric-circles** (8) — Behind CTAs or feature highlights
8. **marquee-ticker** (7) — CSS translateX infinite for social proof
9. **grid-lines** (7) — Subtle background grid for structure feel

---

## Frontend Stack (what the best projects use)

### Frameworks
- **Next.js**: 85 projects — the default choice
- **Framer**: 30 — for marketing/portfolio sites
- **React**: 25 — when Next.js isn't needed
- **Webflow**: 23 — for no-code marketing sites

### CSS
- **Tailwind**: 166 projects — dominant approach
- **CSS Modules**: alongside Tailwind for complex components
- **Vanilla CSS/Sass**: 14 — for maximum control

### Animation
- **Framer Motion**: 161 — scroll reveals, page transitions, layout animations
- **GSAP**: 37 — complex timeline animations, ScrollTrigger
- **CSS-only**: 43 — transitions, simple hover states

### Components
- **Custom**: 312/399 — high-craft projects build their own
- **shadcn/ui + Radix**: 28 — when using a library, this is the choice

### Icons
- **Phosphor**: 32 — modern, consistent weight system
- **Lucide**: 26 — clean, minimal icon set
- **Custom SVG**: 47 — unique brand iconography

---

## Key CSS Techniques

```css
/* Pill buttons — most popular CTA style */
border-radius: 9999px;

/* Hero image darkening */
background: linear-gradient(to bottom, transparent 40%, rgba(0,0,0,0.8)), url(hero.jpg);
background-size: cover;

/* Glass card effect */
backdrop-filter: blur(12px);
background: rgba(255,255,255,0.05);
border: 1px solid rgba(255,255,255,0.1);

/* Avatar stack */
.avatar { margin-left: -8px; position: relative; }
.avatar:nth-child(1) { z-index: 3; }

/* Noise texture overlay */
.noise::after {
  content: '';
  position: absolute; inset: 0;
  background-image: url("data:image/svg+xml,...");
  opacity: 0.03;
  pointer-events: none;
}

/* Marquee ticker */
@keyframes marquee { from { transform: translateX(0); } to { transform: translateX(-50%); } }
.ticker { animation: marquee 30s linear infinite; }

/* Uppercase label system */
.label { font-size: 11px; text-transform: uppercase; letter-spacing: 0.15em; }

/* Card hover lift */
.card { transition: transform 200ms, box-shadow 200ms; }
.card:hover { transform: translateY(-4px); box-shadow: 0 12px 40px rgba(0,0,0,0.15); }

/* Scroll reveal with IntersectionObserver */
.reveal { opacity: 0; transform: translateY(20px); transition: all 0.6s ease; }
.reveal.visible { opacity: 1; transform: none; }

/* Text behind image (background-clip trick) */
.hero-text {
  font-size: 200px;
  background-image: url(hero.jpg);
  background-clip: text;
  -webkit-background-clip: text;
  color: transparent;
}

/* Section alternation with CSS custom properties */
section:nth-child(odd) { --bg: #fafafa; --text: #111; }
section:nth-child(even) { --bg: #111; --text: #fafafa; }
```

---

## Interaction Patterns

### Essential (implement on every project)
1. **Scroll-triggered section reveals** — fade-up on IntersectionObserver or Framer Motion `whileInView`
2. **CTA hover** — background-color transition 200ms + arrow translateX
3. **Card hover lift** — translateY(-4px) + shadow increase

### Elevated (for score 7+ projects)
4. **Smooth page transitions** — Framer Motion AnimatePresence
5. **Parallax hero** — subtle translateY on scroll for depth
6. **Carousel** — 3 visible cards, center full opacity, sides scale(0.85) + blur(3px)
7. **Stat counter** — countUp.js or Framer Motion on viewport entry
8. **Magnetic cursor** — cursor follows with spring physics near CTAs
9. **Horizontal scroll section** — transform: translateX bound to scroll progress

---

## Mobile-First & Responsive Design

**MANDATORY: Every UI MUST work flawlessly on mobile.** Build mobile-first, then enhance for desktop. Never ship a layout that breaks on small screens.

### Core Mobile Rules

1. **Viewport meta** — Always include `<meta name="viewport" content="width=device-width, initial-scale=1">` — without this, nothing else matters
2. **Touch targets** — Minimum 44×44px for all interactive elements (buttons, links, inputs). 48px preferred. Never stack tiny links
3. **No horizontal scroll** — If anything overflows-x on mobile, it's broken. Use `overflow-x: hidden` on body as safety, but fix the root cause
4. **Font minimum 16px** — Body text below 16px is unreadable on mobile. Inputs below 16px trigger iOS zoom. Headlines scale down: desktop 80-160px → mobile 32-56px
5. **Thumb-friendly zones** — Primary CTAs in the bottom 60% of screen. Nav hamburger top-right. Avoid top-left actions on mobile
6. **Stack grids on mobile** — Desktop 3-4 column grids → single column or 2-col max on mobile. Use `grid-template-columns: repeat(auto-fit, minmax(280px, 1fr))`
7. **Hamburger nav on mobile** — Full horizontal nav breaks below 768px. Collapse to hamburger with full-screen or slide-in overlay menu
8. **Adequate spacing** — Touch elements need 8px+ gap between them. Cards need 16px+ margin on mobile. Sections need 48px+ vertical padding
9. **Images must be responsive** — `max-width: 100%; height: auto;` on all images. Use `srcset` for performance. Hero images: `object-fit: cover` with fixed aspect ratio
10. **Hide non-essential on mobile** — Decorative elements, parallax, complex animations, horizontal scroll sections — hide or simplify on mobile with `@media (max-width: 768px)`

### Responsive Breakpoints

```css
/* Mobile-first approach — base styles ARE mobile styles */

/* Tablet */
@media (min-width: 768px) {
  /* 2-column grids, larger typography, side-by-side layouts */
}

/* Desktop */
@media (min-width: 1024px) {
  /* Full grid layouts, max-width containers, hover interactions */
}

/* Large desktop */
@media (min-width: 1440px) {
  /* Max-width 1200-1400px container, larger hero text */
}
```

### Mobile UX Patterns

- **Sticky mobile CTA** — Fixed bottom bar with primary action button on mobile (e-commerce, SaaS)
- **Bottom sheet** — Slide-up panels for filters, options, details instead of modals
- **Swipe gestures** — Carousels, image galleries, card stacks should support touch swipe
- **Collapsible sections** — Accordion pattern for FAQ, features, specs on mobile
- **Skeleton loading** — Show content placeholders during load, especially on slower mobile connections
- **Safe areas** — Respect `env(safe-area-inset-*)` for notch/rounded-corner devices

### Mobile Typography Scale

| Element | Desktop | Mobile |
|---------|---------|--------|
| Hero headline | 80-160px | 32-56px |
| Section heading (h2) | 32-48px | 24-32px |
| Subheading (h3) | 24px | 20px |
| Body text | 16-18px | 16px (never less) |
| Labels | 11-12px | 12px (never less) |

---

## User Color Preference

**When the user provides a preferred color, ALWAYS use it — but apply color theory to build a proper palette around it.**

### How to Handle User-Specified Colors

1. **User's color = primary accent** — The color they provide becomes THE accent color used for CTAs, links, active states, and key highlights
2. **Apply accent restraint** — From `references/color-theory.md`: 9 out of 10 top-scoring projects use accent on less than 10% of the page. The user's color should NOT flood the UI
3. **Build the full palette around it:**
   - **Background**: Choose neutral that complements — warm accent → warm off-white (#FAF8F5); cool accent → cool white (#F8F9FA); dark theme → #0A-#15 range
   - **Text**: High contrast against background — dark on light (#111-#333), light on dark (#E5-#FFF)
   - **Neutral scale**: 4-5 shades from background to border: bg → surface → border → muted-text → text
   - **Accent variants**: Generate 3 variants of user's color — light (tinted, for backgrounds/badges), base (for CTAs), dark (for hover states)
   - **Semantic colors**: Success green, error red, warning amber — adjust warmth/coolness to match the accent's temperature
4. **Contrast pairs** — Ensure accent on background passes WCAG AA (4.5:1 for text, 3:1 for large text). If user's color fails contrast, use it for fills/borders and use white/dark text ON it
5. **Reference**: Always consult `references/color-theory.md` for palette construction patterns from 9/10 scoring projects

### Example: User says "use blue"

```
Accent: #2563EB (blue-600)
Accent light: #DBEAFE (blue-100, for badges/highlights)
Accent dark: #1D4ED8 (blue-700, for hover)
Background: #FAFBFC (cool neutral)
Surface: #F1F5F9 (slate-100, for cards)
Border: #E2E8F0 (slate-200)
Text: #0F172A (slate-900)
Muted text: #64748B (slate-500)
```

---

## Workflow: Create from Scratch

When building a new frontend:

1. **Pick aesthetic** — Match category to aesthetic from the table above
2. **Set constraints first** — Choose: 1 display font, 1 body font, 1 accent color, max 5 neutral tones. **If user provided a color**, follow the User Color Preference rules above
3. **Hero first** — The hero determines everything. Pick pattern (layered/centered/left-right), set headline size, establish spacing scale
4. **Build mobile-first** — Start with mobile layout (single column, stacked), then enhance for tablet/desktop
5. **Build section rhythm** — Alternate: dark/light, image-left/image-right, full-width/contained
6. **Typography scale** — Set the full scale: hero (80-160px desktop / 32-56px mobile) → h2 (32-48px / 24-32px) → h3 (24px / 20px) → body (16px) → label (12px uppercase)
7. **Color extraction** — If using photography, extract palette from hero image
8. **Component system** — Build cards, buttons, inputs as custom components with consistent radius/shadow/spacing. All touch targets ≥ 44px
9. **Animations last** — Add scroll reveals, hover states, transitions after layout is solid. Respect `prefers-reduced-motion`
10. **Run Verification Checklist** — MANDATORY: Run through every check in the Verification Checklist section below before shipping

## Workflow: Fix AI Slop

When fixing an AI-generated frontend:

1. **Audit** — Read all frontend code, identify which of the 15 slop patterns are present
2. **Constrain the palette** — Reduce to max 5 colors: 2-3 neutrals + 1-2 accents. **If user provided a color**, follow User Color Preference rules
3. **Fix typography** — Remove extra fonts, establish clear hierarchy with size contrast
4. **Fix spacing** — Replace random padding with consistent scale (16/24/32/48/64/80/120px)
5. **Fix mobile** — Ensure all layouts stack on mobile, touch targets ≥ 44px, no horizontal overflow
6. **Replace generic sections** — Break the hero→features→pricing→testimonials template
7. **Add intentional decoration** — Replace random blobs with purposeful noise-texture, gradient-overlays, or watermark-text
8. **Add micro-interactions** — Card hover lift, CTA arrow animation, scroll reveals
9. **Custom components** — Replace any generic cards/buttons with styled versions
10. **Run Verification Checklist** — MANDATORY: Run through every check in the Verification Checklist section before shipping

## Workflow: Revamp Existing UI

1. **Screenshot + audit** — Identify the current aesthetic and what's working vs weak. Check mobile responsiveness
2. **Pick upgrade path** — Same aesthetic but refined, or shift to a new one
3. **Typography upgrade** — Usually the highest-impact single change. Ensure mobile scale (see Mobile Typography Scale)
4. **Spacing cleanup** — Increase whitespace, add vertical rhythm consistency
5. **Color refinement** — Reduce palette, increase contrast, add one premium accent. **If user provided a color**, follow User Color Preference rules
6. **Mobile fix** — Ensure all layouts are responsive, touch targets ≥ 44px, grids stack properly
7. **Hero redesign** — Upgrade layout pattern, add overlap/layering
8. **Animation layer** — Add scroll reveals and hover polish. Respect `prefers-reduced-motion`
9. **Component elevation** — Upgrade cards, buttons, forms with shadow/radius refinement
10. **Run Verification Checklist** — MANDATORY before shipping

## Workflow: Complete Redesign

1. **Analyze current** — What category, who's the audience, what's the content structure
2. **Research** — Open `references/design-recipes.md` for category-specific recipes
3. **New aesthetic direction** — Pick from aesthetic table, justify the shift
4. **Design tokens** — Define full system: colors, typography, spacing, radius, shadows. **If user provided a color**, follow User Color Preference rules
5. **Hero concept** — Sketch the hero approach, this drives everything
6. **Section architecture** — Plan 6-8 sections with intentional rhythm
7. **Build mobile-first** — Start with mobile layout (single column, stacked), then enhance for tablet/desktop per Mobile-First rules
8. **Polish pass** — Animations, hover states, transitions, decorative elements. Respect `prefers-reduced-motion`
9. **Run Verification Checklist** — MANDATORY before shipping

---

## Verification Checklist

**MANDATORY: Run this checklist after EVERY build, revamp, fix, or redesign. Do NOT ship without passing all checks.**

### Mobile & Responsive (must pass ALL)

- [ ] **Viewport meta tag** present in `<head>`
- [ ] **No horizontal scroll** on any screen width (320px to 1440px+)
- [ ] **All touch targets ≥ 44px** — buttons, links, inputs, nav items
- [ ] **Body text ≥ 16px** on mobile — check inputs too (iOS zoom issue)
- [ ] **Grid stacks properly** — multi-column layouts collapse to 1-2 columns on mobile
- [ ] **Nav collapses** to hamburger/menu below 768px
- [ ] **Images responsive** — no images overflow container, all have max-width: 100%
- [ ] **Hero readable on mobile** — headline doesn't overflow, CTA is visible without scrolling
- [ ] **Spacing adequate** — no cramped touch targets, no text hitting screen edges
- [ ] **Test at 320px, 375px, 768px, 1024px, 1440px** — nothing breaks at any width

### UX & Usability

- [ ] **Primary CTA visible** within first viewport on both mobile and desktop
- [ ] **Clear visual hierarchy** — user can identify the most important element in 2 seconds
- [ ] **Consistent spacing scale** — not random padding values (use 8/16/24/32/48/64/80/120px)
- [ ] **Readable contrast** — text passes WCAG AA (4.5:1 body, 3:1 large text)
- [ ] **Focus states** — all interactive elements have visible focus indicators for keyboard nav
- [ ] **Loading states** — skeleton screens or spinners for async content
- [ ] **Error states** — form fields have clear error messaging

### Anti-Slop Check

- [ ] **No generic section ordering** — hero→features→pricing→testimonials without variation
- [ ] **No gradient CTA buttons** without design system justification
- [ ] **No more than 2 fonts** — one display, one body
- [ ] **No more than 5 colors** — 2-3 neutrals + 1-2 accents
- [ ] **No decorative blobs** without compositional purpose
- [ ] **No placeholder text** — Lorem ipsum, generic testimonials, stock copy
- [ ] **Custom components** — cards, buttons, nav are styled, not default/library defaults

### Color Palette Verification

- [ ] **Accent used sparingly** — less than 10% of page surface (CTAs, links, key highlights only)
- [ ] **If user specified a color** — it IS the primary accent, palette built around it per color theory rules
- [ ] **Neutral consistency** — background, surface, border, text all from same temperature family
- [ ] **Dark theme check** — if dark, background is #0A-#15 range, NOT pure #000000

### Performance Basics

- [ ] **Images optimized** — WebP/AVIF format, proper srcset, lazy-loaded below fold
- [ ] **Fonts loaded efficiently** — `font-display: swap`, preload critical fonts, max 2-3 font files
- [ ] **Animations respect preferences** — `@media (prefers-reduced-motion: reduce)` disables motion

---

## Category-Specific Guidance

**IMPORTANT: When working on a specific category, ALWAYS read the full category reference file for complete recipes.**

Each category has a dedicated file with ALL project recipes, scores, designers, aesthetics, and core lessons:

| Category | File | Projects |
|----------|------|----------|
| E-commerce | `references/e-commerce.md` | 67 |
| Agency | `references/agency.md` | 44 |
| Landing Page | `references/landing-page.md` | 37 |
| Fintech | `references/fintech.md` | 26 |
| SaaS | `references/saas.md` | 22 |
| AI Product | `references/ai-product.md` | 20 |
| Real Estate | `references/real-estate.md` | 18 |
| Travel | `references/travel.md` | 18 |
| Corporate | `references/corporate.md` | 18 |
| Healthtech | `references/healthtech.md` | 18 |
| Crypto/Web3 | `references/crypto-web3.md` | 17 |
| Automotive | `references/automotive.md` | 15 |
| Fitness | `references/fitness.md` | 15 |
| Food | `references/food.md` | 14 |
| Portfolio | `references/portfolio.md` | 14 |
| Edtech | `references/edtech.md` | 11 |
| Dashboard | `references/dashboard.md` | 9 |
| Marketplace | `references/marketplace.md` | 4 |
| Devtool | `references/devtool.md` | 3 |
| Other | `references/other.md` | 9 |

Additional reference files:
- `references/design-recipes.md` — 40 highest-scoring recipes (score 9/10) with full design + dev recipes + steal-these lists
- `references/anti-slop-rules.md` — Complete slop evidence database (20 slop + 30 craft examples with detailed evidence)
- `references/category-playbooks.md` — Summary playbooks with top aesthetics and best recipes per category

### Quick Cheat Sheet
- **E-commerce**: warm-minimal or dark-luxury, product photography as hero, asymmetric grid, hover-zoom on products
- **SaaS/Fintech**: minimal-corporate, dashboard mockup in hero, bento grid features, trust badges
- **Agency/Portfolio**: bold-expressive or editorial, oversized typography, horizontal scroll, case study grid
- **AI Product**: dimensional-layered or glassmorphism, gradient mesh bg, glass cards, animated orbs
- **Real Estate**: warm-minimal or dark-luxury, full-bleed photography, serif headlines, map integration
- **Travel/Food**: organic-natural or warm-minimal, photography-driven, earth tones, editorial layout
- **Crypto/Web3**: dark-luxury or glassmorphism, neon accents, glass cards, 3D elements
- **Healthtech**: warm-minimal or minimal-corporate, trust-building, clean data viz, accessibility
- **Automotive**: dark-luxury, cinematic photography, wide hero, speed-inspired motion
- **Fitness**: bold-expressive, high-energy colors, action photography, strong CTAs
- **Dashboard**: dark-luxury or glassmorphism, data density, warm accents as light sources
- **Portfolio**: editorial or bold-expressive, typography-driven, asymmetric layouts, case study focus

---

## Design Rules Deep-Dive References

**IMPORTANT: For any design decision, consult the relevant deep-dive reference file.** These contain the full patterns extracted from all 399 projects, not summaries.

### Design System References

| Topic | File | What's inside |
|-------|------|---------------|
| **Color Theory** | `references/color-theory.md` | Color modes, accent rules from all 9/10 projects, craft insights, complete palettes with hex + role + why, contrast pairs |
| **Typography** | `references/typography-rules.md` | 50 font pairing logics with reasoning, 60 special effects, full type scales from 9/10 projects |
| **Animation** | `references/animation-patterns.md` | 1913 interactions categorized: scroll, hover, entrance, page transition, micro-interactions |
| **Components** | `references/component-patterns.md` | Button CSS (pill/rounded/square), card patterns, nav patterns, footer patterns — all with actual CSS |
| **Layout & Visuals** | `references/layout-visuals.md` | Grid systems, hero eye-flow patterns, section types, decorative elements with CSS, shadow patterns, imagery approaches |
| **Anti-Slop** | `references/anti-slop-rules.md` | 20 slop examples + 30 craft examples with detailed evidence |

### When to read which reference:

- **Choosing colors?** → Read `color-theory.md` first — accent rules and craft insights will prevent slop
- **Setting up typography?** → Read `typography-rules.md` — pair logics explain WHY fonts work together
- **Adding animations?** → Read `animation-patterns.md` — categorized by scroll/hover/entrance/transition
- **Building components?** → Read `component-patterns.md` — real button/card/nav CSS from top projects
- **Designing layout?** → Read `layout-visuals.md` — hero patterns, grid systems, decorative CSS
- **Fixing slop?** → Read `anti-slop-rules.md` — evidence-based detection patterns
- **Working on a category?** → Read the specific category file (e.g., `e-commerce.md`) for all recipes

---

## When NOT to Use This Skill

- Backend API development
- DevOps/infrastructure work
- Database design
- Non-visual CLI tools
