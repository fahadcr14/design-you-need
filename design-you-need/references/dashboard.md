# Dashboard — Design Playbook

**9 projects analyzed | 4 scored 7+ | Avg: 6.3/10**

## Category Overview

**Aesthetics that work:** minimal-corporate (3), dark-luxury (3), warm-minimal (2), glassmorphism (1)
**Color strategy:** neutral-plus-accent (6), dark-theme (3)
**Color mode:** light (5), mixed (3), dark (1)
**Hero patterns:** n/a (6), layered (1), left-right (1), centered (1)
**Frameworks:** React or Next.js (4), React (3), React Native or Flutter (1), Next.js or React (1)
**Animation:** Framer-Motion (5), CSS-only (1), Framer-Motion or React Native Reanimated (1)
**Heading fonts:** Inter or SF Pro Display (4), Inter or SF Pro (2), SF Pro Display / Inter (1), SF Pro Display or Inter (1)
**Body fonts:** Inter (3), Inter or SF Pro (2), Inter or SF Pro Text (1), SF Pro Text / Inter (1)

## Color Rules

- **[9]** Gold used sparingly on interactive elements, chart data, and date indicators — never as large fills
- **[7]** Purple used only for interactive/active elements — nav highlight, CTAs, checkboxes, breadcrumb links
- **[7]** Blue accent reserved for active states and primary CTAs only — max 5% of surface area
- **[7]** Green reserved for positive actions and ready states; yellow for pending; red only for cancel/high priority

### Color Craft Insights
- **[9]** The amber glow inside cards mimics real light photography — it's not a flat overlay but a radial gradient that fades naturally, creating depth that feels physical
- **[7]** The warm-purple-tinted white (#FBFAFD) instead of pure white creates subtle brand cohesion — everything feels 'on brand' without being obvious
- **[7]** The orange/teal chart palette avoids red/green colorblind issues while maintaining clear income vs expense distinction
- **[7]** The pending order card (John Doe) gets a yellow-green gradient border that breaks the uniform grid — smart visual priority escalation

## Color Palettes

### Personal productivity tracker with focus analytics and daily planning Example (dark-theme / dark)
- `#080808` — **bg-primary** — Deep black maximizes contrast for data readability and creates premium feel
- `#1A1A1E` — **surface-card** — Slightly elevated from pure black to create layered depth without harshness
- `#B08E3F` — **accent-primary** — Amber/gold conveys achievement, warmth, and premium status against dark backgrounds
- `#A35004` — **accent-warm** — Creates the signature warm-light-source effect inside metric cards
- `#FBFAF8` — **text-primary** — Warm white avoids clinical feel, maintains the cozy-premium atmosphere
- `#909191` — **text-secondary** — Sufficient contrast for secondary info without competing with primary content
- `#3E3E42` — **border-subtle** — Barely visible structure that organizes without cluttering

### Sales intelligence CRM with lead enrichment and outreach automation Example (neutral-plus-accent / light)
- `#FBFAFD` — **bg-primary** — Near-white with slight warm-purple tint creates cohesion with accent
- `#141414` — **text-primary** — Near-black for maximum readability without harsh pure black
- `#6D388B` — **accent-cta** — Purple signals premium/intelligence — differentiates from blue SaaS crowd
- `#EDE0FF` — **surface-highlight** — Light purple tint for selected state without overwhelming
- `#5B5858` — **text-secondary** — Muted gray for hierarchy without disappearing
- `#A6A2AA` — **text-tertiary** — Subtle delineation for low-priority information

### Agency finance management dashboard Example (neutral-plus-accent / light)
- `#EEEFF2` — **bg-primary** — Warm gray creates depth without harshness, separates cards from canvas
- `#FFFFFF` — **surface-card** — Pure white cards pop against gray bg, clean data presentation
- `#0F0F0F` — **text-primary** — Near-black for maximum readability on financial data
- `#014B93` — **accent-cta** — Deep blue conveys financial trust and authority
- `#0B41F2` — **accent-secondary** — Brighter blue for interactive state differentiation
- `#32A2B7` — **decorative** — Teal contrasts orange income line for clear data separation
- `#C55807` — **decorative** — Warm orange for positive income — optimistic, attention-grabbing
- `#51555B` — **text-secondary** — Muted gray for secondary info hierarchy
- `#B1B6B6` — **text-tertiary** — Light gray for lowest-priority text
- `#4CAF50` — **status-success** — Universal green for positive status confirmation

### Restaurant order management SaaS Example (neutral-plus-accent / light)
- `#F9F9F9` — **bg-primary** — Warm off-white reduces eye strain during long shifts
- `#FFFFFF` — **surface-card** — Clean white cards pop against warm background for scanability
- `#1A1919` — **text-primary** — Near-black provides strong contrast without harshness
- `#3F952C` — **accent-cta** — Green signals completion/action, natural restaurant association
- `#698F22` — **accent-secondary** — Olive-green reinforces organic/food brand identity
- `#E8A020` — **status-warning** — Yellow/amber signals attention needed without alarm
- `#D4552A` — **status-danger** — Red for destructive actions and urgent priority
- `#C0CAA8` — **decorative** — Muted sage bridges white and green palette

## Typography

- **[9] SF Pro Display or Inter — geometric sans + SF Pro Text or Inter — humanis**: Single family at different weights creates clean hierarchy without visual noise in a data-dense dashboard
- **[7] Inter or SF Pro — geometric sans-serif + Inter or SF Pro — same family**: Single font family with weight variation keeps data-dense UI clean and scannable
- **[7] Inter or SF Pro Display — geometric sans + Inter — humanist geometric san**: Single font family with weight variation creates cohesion appropriate for data-dense dashboards
- **[7] Inter or SF Pro — geometric sans-serif + Inter or SF Pro — geometric sa**: Single font family with weight variation keeps the dense data UI clean and scannable.

### Typography Effects
- **[9]** Large metric numbers (1h 25m, 88%) use bold weight with warm color to create focal points — font-weight + color contrast
- **[7]** Dollar cents rendered in lighter weight/smaller size for visual hierarchy on stat values
- **[7]** Monospace-style treatment on TABLE NO and RIDER labels — letter-spacing: 1-2px, uppercase, font-weight: 500

## Hero Patterns

- **[9] left-right** (Personal productivity tracker with focus analytics): Headline 'Stay on Track Today' → Keep it going badge → Customize button
- **[7] n/a** (Sales intelligence CRM with lead enrichment and ou): Sidebar active state → breadcrumb → action bar → table data top-down
- **[7] n/a** (Agency finance management dashboard): Welcome text → stat cards → earning chart → transactions table
- **[7] n/a** (Restaurant order management SaaS): Page title → filter tabs → first order card (Emily Johnson) → scan right across row

## Card & Component Patterns

- **[9]** Dark surface (#1A1A1E), 16px radius, 20px padding, subtle 1px border rgba(255,255,255,0.06), no hover visible — some cards contain embedded photography with warm color grading
- **[7]** White bg, border-radius: 16px, padding: 24px, subtle box-shadow 0 1px 3px rgba(0,0,0,0.06), no hover effect visible, clean internal layout
- **[7]** White bg, border-radius: 12px, padding: 20px, 1px border #E8E8E8, pending card gets colored border-left or full border highlight, consistent internal layout: avatar+name+status → metadata → line items → total → actions

### Buttons

- **primary / pill**: `border: 1px solid rgba(255,255,255,0.3); border-radius: 999px`
- **secondary / rounded-8**: `backdrop-filter: blur(10px); background: rgba(255,255,255,0.08)`
- **ghost / pill**: `border: 1px solid #3E3E42`
- **primary / rounded-8**: `background-color with border-radius: 8px`
- **secondary / rounded-8**: `border: 1px solid with transparent bg`
- **ghost / rounded-8**: `Reveal email/phone inline buttons with icon prefix`
- **primary / rounded-8**: `background-color with border-radius: 8px`
- **secondary / rounded-8**: `border: 1px solid with transparent bg`
- **ghost / rounded-8**: `Top Up/Transfer/Request action buttons`
- **primary / rounded-8**: `background-color with border-radius: 8px`
- **secondary / rounded-8**: `border: 1px solid with transparent bg`
- **danger / rounded-8**: `linear-gradient orange-to-red for cancel on pending cards`
- **ghost / rounded-8**: `border: 1px solid #ddd`

## Animation & Interaction

- **[9]** Pagination arrows on daily goals → slide transition, Framer-Motion
- **[9]** Pause button on Deep Work card → timer state toggle with animation
- **[9]** Timeline task pills → likely draggable/resizable, custom drag handler or dnd-kit
- **[9]** Metric cards → hover subtle lift/glow intensification, CSS transition
- **[9]** Chart bars → hover tooltip with exact values, CSS/JS
- **[7]** Row hover highlight → CSS :hover background-color
- **[7]** Checkbox bulk select → React state with indeterminate header checkbox
- **[7]** Reveal email/phone click → API call with loading state
- **[7]** Sidebar nav active state → React Router with active class
- **[7]** Cmd+K search shortcut → Command palette modal
- **[7]** Chart tooltip on hover — Recharts/Chart.js custom tooltip component
- **[7]** Sidebar nav active state with pill background transition — CSS transition
- **[7]** Monthly/Yearly toggle with dot indicator slide — CSS transform + transition
- **[7]** Three-dot menu on stat cards — dropdown on click, likely Radix Popover
- **[7]** Credit card stack hover to fan out — CSS transform + transition
- **[7]** Tab filter switching with active underline animation → CSS transition
- **[7]** Card hover subtle lift/shadow increase → transform: translateY(-2px) + box-shadow transition
- **[7]** Status badge pulse animation on new orders → CSS @keyframes pulse
- **[7]** Grid/list view toggle → layout transition with Framer-Motion layoutId
- **[7]** Pagination page change with card fade-in → opacity + translateY stagger

## Decorative Elements

- **amber-glow** at Inside Deep Work and Attention Quality cards: `radial-gradient with warm amber, possibly mix-blend-mode: screen`
- **dashed-line** at Focus Stability chart threshold line: `border-style: dashed or SVG stroke-dasharray`
- **card-border-glow** at Subtle warm border on metric cards: `box-shadow: 0 0 20px rgba(176,142,63,0.1)`
- **bar-chart-glow** at Focus Stability amber bars: `box-shadow on individual bars or filter: drop-shadow`
- **sidebar-active-pill** at Active nav item: `border-radius with background-color`
- **table-row-dividers** at Between each row: `border-bottom: 1px solid`
- **header-checkbox-fill** at Select-all checkbox: `accent-color or custom checkbox with bg-fill`
- **sparkline-bar-chart** at Total Balance stat card: `SVG or canvas mini-chart`
- **sparkline-area** at Monthly Income stat card: `SVG path with fill-opacity`
- **gauge-arc** at Monthly Expenses stat card: `SVG stroke-dasharray arc`
- **barcode-progress** at Daily Limits section: `Repeating vertical bars with varying opacity`
- **colored-status-dot** at Before status badge text: `::before pseudo-element with border-radius: 50%`
- **gradient-border** at Pending order card (John Doe): `border-image or box-shadow with gradient, possibly outline with offset`
- **gradient-bg** at Support help widget bottom-left: `linear-gradient with border-radius`

## Design Recipes

### Score 9/10 — dark-luxury — Personal productivity tracker with focus analytics and daily

**Design Recipe:** Use #080808 background with #1A1A1E card surfaces (16px radius, 1px border at rgba(255,255,255,0.06)). Accent exclusively with #B08E3F gold and #A35004 deep amber — apply as radial-gradient light sources inside cards, never as flat fills. Typography: Inter or SF Pro, warm-white #FBFAF8 for primary text, #909191 for secondary. Large metrics at 48px bold. Cards at 20px padding with 16px gaps. Embed cinematic warm-graded photography inside select cards with overflow:hidden. Navigation uses pill-shaped outline buttons. Timeline uses horizontal CSS Grid with task pills as positioned elements.

**Dev Recipe:** Next.js + Tailwind + Framer Motion. Use Recharts or Visx for the bar/bubble charts with custom amber theming. Timeline is a CSS Grid with 13 equal columns (8AM-8PM) where task blocks span columns via grid-column. Cards use relative positioning with absolutely-placed gradient overlays (radial-gradient(circle at 30% 70%, rgba(163,80,4,0.6), transparent 70%)).

**Core Lesson:** A single warm accent color (amber/gold) used as a simulated light source within dark cards creates an emotional, premium atmosphere that transforms a utilitarian dashboard into something people want to look at.

**Steal These:**
- Photography embedded inside metric cards with warm color grading as data visualization enhancement
- Amber radial glow as simulated light source inside dark cards
- Date circle component with gold border and stacked day/month
- Timeline Gantt-style task pills with inline priority color dots
- Motivational toast ('Keep it going!') with checkmark icon as positive reinforcement UX

**Weaknesses:** Timeline task blocks may overlap on smaller screens — needs responsive collapse strategy, Focus Stability chart is visually rich but the dashed threshold line label ('Peak: 11 am') could be clearer, The 'Add Widget' and 'Customize' buttons feel disconnected from the main content — could benefit from a more integrated placement

---

### Score 7/10 — minimal-corporate — Sales intelligence CRM with lead enrichment and outreach aut

**Design Recipe:** Use #FBFAFD background, #141414 text, #6D388B purple accent only on active/interactive states, #EDE0FF for selected surfaces. Inter font at 14px regular for data, 12px semibold uppercase for section labels, 14px medium for nav items. Sidebar 260px wide with 16px padding, nav items 40px tall with 8px border-radius active pill. Table rows 50px tall, 1px #E8E8E8 dividers, 32px circular avatars. Action bar buttons 36px tall with 1px borders and 8px radius. Keep everything flat — no shadows, no gradients, no decoration.

**Dev Recipe:** Next.js + shadcn/ui + Tailwind CSS with Lucide icons. Use TanStack Table for sortable/filterable data table with row selection, shadcn Command for search palette, and React context for sidebar navigation state.

**Core Lesson:** In data-heavy dashboards, restraint IS the design — let the data breathe with consistent spacing, minimal color, and accent only on interactive elements

**Steal These:**
- Purple-tinted white (#FBFAFD) as base instead of pure white for subtle brand warmth
- Uppercase letter-spaced section labels in sidebar for clear nav grouping
- Reveal email/phone inline CTAs as monetization pattern in lead tables
- Credits display in top bar showing unlimited email/phone as trust signal
- Indeterminate checkbox header state for bulk selection UX

**Weaknesses:** No empty states, loading states, or error states shown — real product needs these, Table lacks column resize, horizontal scroll indicator, or density toggle for power users, Color palette is safe to the point of being forgettable — nothing distinguishes it from dozens of similar tools

---

### Score 7/10 — minimal-corporate — Agency finance management dashboard

**Design Recipe:** Use Inter font at 28px/semibold for headings, 14px/regular for body, on #EEEFF2 page background with #FFFFFF cards at border-radius: 16px and box-shadow: 0 2px 8px rgba(0,0,0,0.04). Fixed 260px sidebar with #014B93 active pill states. Stat cards in a 4-column grid with 24px gaps, each containing a unique sparkline visualization. Chart uses #C55807 for income and #32A2B7 for expenses with dashed #EEEFF2 grid lines. All interactive elements use 8px border-radius, and the spacing system follows an 8px base unit throughout.

**Dev Recipe:** Next.js + Tailwind CSS + shadcn/ui for base components, Recharts for the earning summary chart with custom tooltip, Lucide icons throughout. Key CSS: grid-template-columns for dashboard layout, transform stack for credit card overlap, and consistent rounded-2xl (16px) on all card surfaces.

**Core Lesson:** In data dashboards, varying the visualization type per metric (bar, line, gauge, area) communicates data character better than repeating one chart style.

**Steal These:**
- Different sparkline chart type per stat card — bar, area, gauge, line
- Barcode-style progress bar for daily limits — visually unique
- Referral widget in sidebar bottom with copy+share actions
- Credit card stack with realistic branding and slight rotation offset
- Keyboard shortcut badge (⌘K) integrated into search bar

**Weaknesses:** Right sidebar (Cards/Daily Limits/Upcoming) feels cramped — too many widgets competing for ~280px width, Transaction table lacks pagination, sorting indicators, or row hover states, No dark mode variant shown despite being expected in modern fintech dashboards

---

### Score 7/10 — warm-minimal — Restaurant order management SaaS

**Design Recipe:** Use Inter font at 28px/bold for page titles, 18px/semibold for card names, 14px/regular for body, 11px/uppercase/wide-spaced for labels. Background #F9F9F9, cards #FFFFFF with 12px radius and 1px #E8E8E8 border. 3-column CSS grid with 16px gaps. Status colors: green #3F952C (ready), amber #E8A020 (pending), orange #D97706 (preparing), gray #6B7280 (served). Sidebar 200px wide with #FFFFFF bg. Primary CTA buttons use #1A1919 fill with white text, 8px radius. Highlight urgent cards with colored border or gradient outline to break visual uniformity.

**Dev Recipe:** Next.js + Tailwind + shadcn/ui for tabs, badges, buttons, cards. Use React Query for real-time order polling, CSS Grid for card layout, and Framer Motion for status transition animations and layout shifts.

**Core Lesson:** In data-dense operational dashboards, color-coded status systems with consistent card layouts let users triage information at a glance without reading.

**Steal These:**
- Gradient border highlight on pending/urgent order cards to draw attention within uniform grid
- Uppercase wide-spaced labels (TABLE NO, RIDER, PRIORITY) as visual anchors in dense cards
- Color-coded priority chips (High=red, Medium=yellow, Low=green) next to status badges
- Support help widget with gradient background pinned to bottom-left corner
- Grid/list view toggle paired with local search and filter button in toolbar

**Weaknesses:** All order cards have identical height regardless of content — could cause awkward whitespace with varying item counts, Cancel Order button styling inconsistent — gradient red on pending card but plain outline on others, unclear hierarchy, No empty states, loading states, or error handling visible — production would need these

---

### Score 6/10 — dark-luxury — Multi-concept mobile UI showcase: productivity task manager,

**Design Recipe:** Use #0A0A0A background with #D6DD07 chartreuse accent at 5% surface area max. Set cards at rgba(255,255,255,0.06) with 1px border at rgba(255,255,255,0.08) and 16px border-radius. Typography: SF Pro Display Bold 32px for headings, SF Pro Text Regular 14px for body, all white (#FFFFFF) on dark. Bottom tab bar: 4 icons at 24px, active = accent circle fill behind icon. Spacing: 16px base unit, 24px between card sections, 12px internal card padding. Progress bars use repeating-linear-gradient(45deg, accent 25%, transparent 25%) pattern.

**Dev Recipe:** React Native with NativeWind (Tailwind for RN), react-native-reanimated for 3D card transforms and progress animations, react-native-svg for circular progress rings. Key: use Animated.View with perspective/rotateX/rotateY for the floating card splash, and stroke-dasharray SVG technique for all progress indicators.

**Core Lesson:** A cohesive accent color strategy on a dark background can carry an entire app's visual identity — but only if the accent is used with surgical restraint on CTAs and active states, never as decoration.

**Steal These:**
- Diagonal-stripe pattern on progress bars for visual texture differentiation
- Avatar stack with +N counter as compact team indicator
- Week-strip calendar with single accent-filled circle on active day
- Glass-card overlay at bottom of full-bleed hero image for text legibility
- Circular progress rings with percentage labels for multi-metric dashboards

**Weaknesses:** Four unrelated app concepts dilute portfolio impact — one deeply explored concept would be stronger, Stock photography makes every screen feel like a template rather than a real product, Chartreuse/lime accent on dark is the most overused mobile UI trend of 2024-2025 — zero differentiation

---

### Score 6/10 — minimal-corporate — Contract lifecycle management for freelancers and SMBs

**Design Recipe:** Use #FFFFFF content cards on #F2F3F6 background. Sidebar 240px with #514EB2 active pill (border-radius 8px, bg opacity 0.1 with solid left border). Body text in Inter 14px #1A1A2E, labels in 13px #7391C7. Metadata rows use icon + label + colon + value pattern at 40px row height. Status stepper uses #3DAA42 green chevron shapes with white text 13px semibold. Tabs are 13px medium with 2px bottom border on active. Cards use 1px #E5E7EB border, 12px radius, 16px padding. Keep spacing at 8px base unit, 24px between sections, 32px between major zones.

**Dev Recipe:** Next.js App Router + Tailwind CSS + shadcn/ui for tabs, inputs, and buttons. Status stepper needs custom component with CSS clip-path: polygon() for chevron shapes — each segment is a div with calculated clip points. Use Lucide icons throughout.

**Core Lesson:** In data-heavy dashboards, the status visualization component is your single biggest opportunity to differentiate — invest design effort there while keeping everything else clean and scannable.

**Steal These:**
- Chevron-shaped status pipeline stepper with green completed states and checkmark icons
- Search input with ⌘K keyboard shortcut badge positioned inside the field
- Metadata rows with icon + label + colon separator + bold value — extremely scannable
- Recently Opened section in sidebar for quick document access
- Trial banner with gradient left accent border — subtle urgency without being aggressive

**Weaknesses:** Party info columns use identical dummy data for both parties — looks unfinished and undermines credibility, 9 tabs is a lot — horizontal scrolling will be needed on smaller screens, consider a dropdown overflow pattern, The background gradient blobs (screenshot 1) feel disconnected from the otherwise corporate-clean aesthetic — pick a lane

---

### Score 5/10 — glassmorphism — CRM dashboard with financial tracking and team collaboration

**Design Recipe:** Use #03050F base with card surfaces at rgba(19,33,90,0.35) and 1px borders at rgba(255,255,255,0.08). Accent everything interactive with #0889EF cyan. Set Inter at 13-14px body, 28-32px stats. Cards get border-radius:12px with 20-24px padding. Sidebar fixed at 240px with icon+label nav items spaced 44px apart. Background needs 2-3 large radial-gradient blobs in #0F32A9 and #064EC3 with heavy blur. Main container gets backdrop-filter:blur(20px).

**Dev Recipe:** React + Tailwind with CSS custom properties for theming. Use backdrop-filter:blur(20px) on the main panel, Recharts for bar/donut charts, and a CSS transition on the sidebar width for collapse. Theme toggle swaps a data-theme attribute on root.

**Core Lesson:** Glassmorphism on dark backgrounds requires visible contrast between glass layers — without it, the effect disappears and you just have dark cards on a dark background.

**Steal These:**
- Collapsible sidebar with icon-only mode and smooth width transition
- Credit card widget with toggle switch for card type selection
- Donut chart with centered percentage label for file storage
- Cyan-only accent color discipline across all interactive elements
- Dark/light theme as a portfolio presentation strategy showing versatility

**Weaknesses:** Placeholder data everywhere destroys credibility — use realistic varied content, Glassmorphism is invisible in dark mode — increase card bg opacity or add stronger borders, Typo in hero heading 'Welcom' signals unfinished work — always proofread

---

### Score 5/10 — dark-luxury — Luxury automotive sales admin panel with companion mobile ap

**Design Recipe:** Start with #08090A background, #1A1D21 card surfaces with 16px border-radius and no borders. Use Inter font family: 36px bold for stat numbers, 14px regular for labels, all in #FFFFFF or #A1A4A8. Apply #FCAB16 gold accent ONLY to active states and positive metrics. Stat cards follow icon-top-right + title + large-number + sparkline-bottom-right pattern at ~230x140px. Sidebar is 220px fixed with 14px nav items and a 32px-tall active pill in #4039F0 with 8px radius. Charts use yellow/gold line strokes on transparent dark backgrounds.

**Dev Recipe:** React + Tailwind + shadcn/ui for the component base, Recharts or Nivo for all chart types including the area chart and bar chart. Use CSS custom properties for the dark theme tokens and Framer Motion for chart mount animations and tooltip transitions.

**Core Lesson:** A restrained dark palette with a single warm accent color (gold) creates more luxury perception than adding more colors or effects.

**Steal These:**
- Gold-on-black accent strategy — single warm color on deep dark creates instant luxury
- Sparkline inside stat cards — adds trend context without taking extra space
- Grouped sidebar sections with category labels (MAIN MENU / SETTINGS)
- Segmented control with pill-shaped active indicator for chart time filters
- Stat card layout pattern: title + icon top row, big number + sparkline bottom row

**Weaknesses:** Bubble chart for brand performance is unreadable — overlapping circles with no axis convey no real data insight, Four unrelated projects in one shot signals quantity-over-quality portfolio padding, No responsive consideration — dashboard would collapse badly below 1200px without significant rework

---

### Score 5/10 — warm-minimal — AI contract lifecycle management SaaS

**Design Recipe:** Use #F5F6F7 page bg with #FFFFFF cards. Sidebar 260px wide, #FFFFFF bg, nav items with Lucide icons at 14px Inter Medium, active state in #4A6CF7 with filled icon. Stat cards stacked vertically at ~200px wide with 16px padding, 12px border-radius, tinted backgrounds (#E8F5E9, #FFF9C4, #FBE9E7, #FFCDD2) each with 1px border matching tint. Large stat numbers at 48px Inter Bold. Main content area uses a hero panel with purple-pink gradient (linear-gradient(135deg, #E8D5F5, #F5D0E8, #D5DAF5)) containing white cards for steps. Data table below with 14px body text, sort carets on headers, status dots (green #10B981, orange #F59E0B, red #EF4444).

**Dev Recipe:** Next.js + Tailwind + shadcn/ui for table, search (cmdk), checkbox, dropdown-menu. Use Lucide icons throughout. Key CSS: gradient background on hero section with backdrop-blur on overlaid cards, CSS Grid for step cards row, sticky sidebar with flex-col justify-between for nav-top and settings-bottom.

**Core Lesson:** Semantic color-coding on dashboard cards (green=new, yellow=attention, red=urgent) creates instant scanability without requiring users to read labels.

**Steal These:**
- Color-coded stat cards mapping urgency levels to pastel tints
- ⌘K search shortcut badge inside search input
- AI chatbot tooltip bubble anchored to avatar
- 3-step onboarding cards overlaid on gradient background
- Sidebar with bottom-anchored user profile and settings

**Weaknesses:** Copy has grammar errors ('what ever it's') — undermines professionalism, AI sparkle orb is generic 2024 slop — adds no real brand identity, Left stat column and right hero panel have no clear visual relationship — feels like two separate pages stitched together

---

## Slop Patterns to Avoid

### Score 5/10
- Typo in 'Welcom' — unshipped, unreviewed
- All chat entries are identical 'Alamorty' with same message — pure placeholder
- All task items are identical 'Develop a game interface' — no real data thinking
- Light mode variant is just color swap with no layout adaptation
- Background 3D blobs are generic Spline/Blender assets with no brand connection

### Score 6/10
- Four completely unrelated app concepts bundled as one project — portfolio padding
- Generic stock imagery throughout (basketball players, model faces, kids fashion)
- Yellow accent on dark = overused Dribbble trend with no brand rationale
- Skincare app uses identical soft-beige palette seen in hundreds of Behance shots
- Progress bars with diagonal stripe pattern are decorative but not functional

### Score 5/10
- Four completely unrelated projects bundled as one shot — classic portfolio padding
- Bubble chart for 'Top Performing Brands' is decorative nonsense — overlapping circles with no axis or scale
- Inconsistent design systems across screens — dark dashboard vs light mobile apps share zero DNA
- Generic stat cards with sparklines are template-tier — no unique data visualization thinking
- Energy app and learning app feel like separate Dribbble shots stapled together for volume

### Score 5/10
- Generic AI sparkle icon with gradient blob — overused 2024 trope
- Color-coded stat cards feel like a template pattern with no real data hierarchy logic
- Step 1-2-3 onboarding cards are extremely generic with placeholder copy
- Typography grammar errors ('what ever it's digital or analog')
- Purple-pink gradient hero section is decorative but purposeless
