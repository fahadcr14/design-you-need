# Fintech — Design Playbook

**26 projects analyzed | 21 scored 7+ | Avg: 7.0/10**

## Category Overview

**Aesthetics that work:** dark-luxury (9), minimal-corporate (7), warm-minimal (6), dimensional-layered (2), organic-natural (1)
**Color strategy:** neutral-plus-accent (18), dark-theme (5), analogous (2), complementary (1)
**Color mode:** mixed (12), light (9), dark (5)
**Hero patterns:** centered (11), left-right (9), split-50-50 (2), layered (2)
**Frameworks:** Next.js or Framer (9), Next.js (9), Next.js or Webflow (2), React or Next.js (2)
**Animation:** Framer-Motion (14), Framer-Motion or GSAP (4), CSS-only (3)
**Heading fonts:** Playfair Display or similar transitional serif (5), Custom serif (2), IBM Plex Serif (2), Inter or SF Pro Display (2)
**Body fonts:** Inter or DM Sans (12), Inter (5), Inter or similar geometric sans-serif (2), Inter or system sans-serif (2)

## Color Rules

- **[9]** No bright accent at all — entire palette is neutral, trust is built through restraint not color pops
- **[8]** Teal reserved exclusively for interactive elements — buttons, selected states, progress dots. Never decorative.
- **[8]** Green CTA used only on primary actions and active states; lime reserved for app UI elements
- **[8]** Green used only for interactive elements and brand marks — max 5% of surface area
- **[8]** Green reserved for brand mark, badges, and primary interactive elements only
- **[8]** Green used only for active/success states; cyan for interactive; purple for brand moments — never competing
- **[8]** Green reserved for announcement bar, badges, status indicators, and illustration accents — never backgrounds
- **[8]** Purple accent reserved for interactive elements and brand marks; warm gradient for decorative backgrounds only
- **[8]** Green used sparingly — badges, CTAs, icons, numbered indicators only; never floods a section
- **[8]** Pink used only for CTAs — 2 instances max, high scarcity = high impact
- **[8]** Gold used sparingly in data elements only; cyan reserved exclusively for app dark UI
- **[7]** Bronze/tan used only for CTAs and section labels — max 5% of surface area
- **[7]** Purple used for interactive elements and key visual moments only — never floods a section
- **[7]** Green reserved exclusively for interactive elements (toggle, checkmarks, badges) — never decorative
- **[7]** Red used only for CTAs, active toggles, totals, and the 'Instantly' keyword — max 10% of surface area

### Color Craft Insights
- **[9]** The warm-cool gray tension (#CDBFB6 warm vs #354648 cool) creates visual richness without any chromatic color — extremely disciplined palette that most designers would break by adding a blue or green accent
- **[8]** The burgundy (#8B6B67) presentation backgrounds are a masterclass in brand extension — they create a third emotional register beyond dark/light that feels premium without competing with the UI palette
- **[8]** The warm off-white (#F5F3EE) instead of pure white is what makes the green palette feel organic rather than corporate — a senior-level color temperature decision
- **[8]** The green is desaturated enough to feel institutional rather than startup-y — a senior move that avoids the 'fintech green' cliché
- **[8]** The dark-to-light mode switch between integration diagram and tools grid creates a natural content hierarchy break — dark = conceptual overview, light = actionable detail
- **[8]** Three distinct accent colors mapped to three different product contexts (green=crypto, cyan=cards, purple=management) creating implicit product differentiation within one portfolio
- **[8]** The moss green palette avoids the typical fintech neon-green trap — these are desaturated, earthy greens that feel institutional rather than crypto-bro
- **[8]** The warm-to-cool gradient direction (left-to-right) mirrors the reading flow, subtly guiding the eye from content to product imagery
- **[8]** The entire palette has a green undertone even in the neutrals (#C3C6B8, #E8E8E4) creating chromatic unity that most designers miss — it's not just 'gray + green accent' but a fully harmonized warm-green neutral system
- **[8]** The blue-to-light gradient creates a natural reading gravity pulling eye downward; yellow headline breaks the gradient at the exact visual center creating a focal anchor

## Color Palettes

### AI-powered deal document analysis for private capital Example (neutral-plus-accent / mixed)
- `#11191A` — **bg-primary-dark** — Near-black with blue undertone conveys institutional trust and depth
- `#354648` — **surface-dark** — Teal-tinged dark gray bridges the architectural imagery to the UI
- `#5D6463` — **text-secondary** — Muted enough to create hierarchy without disappearing
- `#798285` — **text-tertiary** — Cool mid-gray for de-emphasized but readable content
- `#AAA8A6` — **decorative-muted** — Warm-neutral gray adds subtle warmth to prevent clinical feel
- `#CDBFB6` — **accent-warm** — Sandstone warmth echoes concrete photography palette
- `#FFFFFF` — **bg-primary-light** — Maximum contrast for readability and clean wireframe state

### SME business lending marketplace and comparison platform Example (neutral-plus-accent / mixed)
- `#040607` — **bg-primary-dark** — Creates premium authority and cinematic drama for brand storytelling pages
- `#ECECEE` — **bg-primary-light** — Clean neutral for task-focused UI — reduces cognitive load during form completion
- `#42B676` — **accent-cta** — Teal-green signals growth/money/go — perfect fintech CTA color without being aggressive
- `#35453E` — **surface-card** — Warm dark green-grey bridges the black and teal, adds depth without harshness
- `#8B6B67` — **decorative** — Adds warmth and sophistication to brand collateral — prevents cold sterility
- `#BCBCBF` — **text-secondary** — Sufficient contrast on dark without the harshness of pure white body text

### Personal finance management mobile app with bank aggregation Example (analogous / light)
- `#091710` — **text-primary** — Deep forest green-black conveys financial stability without harsh pure black
- `#1B5E3B` — **accent-cta** — Deep green signals money, growth, and trust — core fintech psychology
- `#B1CA27` — **accent-secondary** — Lime-chartreuse adds energy and modernity, prevents stodgy bank feel
- `#AEEDFD` — **bg-hero** — Light cyan evokes open sky, freshness, and calm optimism
- `#F5F3EE` — **bg-primary** — Warm off-white feels premium and organic vs sterile pure white
- `#9FB8A6` — **surface-card** — Sage green bridges the bold accents with neutral backgrounds
- `#425825` — **decorative** — Olive-forest green grounds the organic landscape metaphor
- `#914B47` — **decorative** — Complementary warm tone adds depth to predominantly cool palette

### AI investment intelligence terminal for institutional capital markets Example (neutral-plus-accent / mixed)
- `#030704` — **bg-primary** — Conveys institutional authority and premium positioning — Bloomberg-coded
- `#115713` — **accent-cta** — Deep forest green signals money, growth, and financial prosperity without being garish
- `#548035` — **decorative** — Bridges the dark bg and bright accent, adds organic depth
- `#F0F1F0` — **bg-secondary** — Warm neutral white avoids clinical sterility, feels approachable
- `#5E615E` — **text-secondary** — Soft gray maintains readability without harsh contrast on light backgrounds
- `#A9AEA9` — **text-tertiary** — Establishes clear typographic hierarchy through value contrast

### AI investment intelligence platform for institutional portfolio management Example (dark-theme / dark)
- `#040505` — **bg-primary** — Dark base conveys institutional seriousness and premium positioning
- `#338863C` — **accent-cta** — Green signals financial growth, money, and positive returns — core fintech semiotics
- `#69BF71` — **accent-secondary** — Provides luminance contrast against dark bg for key interactive elements
- `#3D3D3D` — **surface-card** — Subtle elevation from bg-primary without breaking dark theme cohesion
- `#B0B0B0` — **text-secondary** — Sufficient contrast on dark without harsh white glare
- `#FFFFFF` — **text-primary** — Maximum contrast for hierarchy anchors
- `#E5E6E6` — **surface-light** — Mode switch creates visual rhythm and section differentiation

### Multi-product fintech UI/UX design system by Arounda agency Example (dark-theme / dark)
- `#020409` — **bg-primary** — Near-black creates premium depth and makes card imagery pop
- `#2A4245` — **surface-card** — Dark teal-gray adds warmth to prevent cold sterility
- `#7FE660` — **accent-cta** — High-energy green signals growth/money in fintech context
- `#56D6DA` — **accent-secondary** — Cyan provides cool tech feel and strong contrast on dark
- `#6074DD` — **accent-tertiary** — Purple conveys premium/trust in financial products
- `#FFFFFF` — **text-primary** — Maximum contrast for critical financial information
- `#A2A3B0` — **text-secondary** — Reduced contrast for hierarchy without disappearing
- `#38455E` — **border-subtle** — Barely visible separation maintains clean dark aesthetic

### AI portfolio intelligence and quantitative risk engine for investment professionals Example (dark-theme / dark)
- `#040604` — **bg-primary** — Near-black conveys institutional seriousness and premium positioning
- `#2A8730` — **accent-cta** — Green signals growth/money/positive returns — core fintech semiotics
- `#195C1D` — **accent-dark** — Adds depth to green palette without neon cheapness
- `#F7F8F7` — **text-primary** — Slightly warm white reduces harshness on dark backgrounds
- `#9DA29D` — **text-secondary** — Creates readable secondary hierarchy without competing with headlines
- `#5B5B5A` — **surface-card** — Neutral gray keeps data-heavy cards from feeling cluttered
- `#89A76D` — **decorative** — Desaturated green bridges the accent and neutral tones

### AI-powered personal finance mobile app Example (analogous / light)
- `#0E0D0F` — **text-primary** — Near-black provides maximum contrast and authority for financial content
- `#7B5CF5` — **accent-cta** — Purple signals innovation and premium positioning in fintech
- `#C9A8F0` — **decorative** — Soft lavender bridges the warm-cool palette and adds approachability
- `#F7DEA3` — **decorative-warm** — Gold/peach warmth counters cold fintech stereotype, implies prosperity
- `#F1EEEE` — **bg-primary** — Warm off-white avoids clinical feel of pure white
- `#959595` — **text-secondary** — Muted gray for hierarchy without harshness
- `#1E1B2E` — **surface-dark** — Deep navy-black for premium app interface feel
- `#FF6B35` — **accent-rating** — Orange stars pop against neutral palette for social proof emphasis

## Typography

- **[9] Inter or similar geometric sans-serif (p + Same family — single-font syst**: Single typeface at multiple weights creates cohesion appropriate for institutional finance — no decorative fonts needed
- **[8] Custom serif — likely Playfair Display o + Inter or similar geometric san**: High-contrast serif headlines convey financial authority while geometric sans body ensures digital readability — classic fintech pairing
- **[8] Playfair Display or similar transitional + Inter or DM Sans — geometric s**: Elegant serif headlines convey financial prestige while clean sans body ensures readability and modern feel — classic luxury-meets-tech pairing
- **[8] Serif — likely Playfair Display or DM Se + Inter or DM Sans (geometric sa**: Serif headlines evoke Wall Street Journal authority while sans body ensures digital readability — classic finance editorial pairing
- **[8] IBM Plex Serif — humanist serif + Inter — geometric sans-serif**: Serif headings convey institutional authority while Inter body ensures digital readability — classic finance-meets-tech pairing
- **[8] Poppins — geometric sans-serif (confirme + Poppins — same family, lighter**: Single-family system using weight contrast (Regular/Medium/Semibold) for hierarchy — clean and scalable for product UI
- **[8] IBM Plex Serif — humanist serif + Inter — geometric sans-serif**: Serif headlines create editorial authority while Inter body ensures clean data readability; DM Mono for labels adds terminal credibility
- **[8] Playfair Display or similar transitional + Inter or DM Sans — geometric s**: Serif italic headlines create editorial elegance while sans-serif body ensures fintech credibility and readability
- **[8] Inter or similar geometric sans-serif, p + Inter — humanist neo-grotesque**: Single-family system with weight/size contrast creates clean institutional feel appropriate for finance
- **[8] Clash Display or similar geometric displ + Inter or DM Sans — regular wei**: Ultra-bold geometric display creates impact while neutral body font ensures readability — classic fintech pairing

### Typography Effects
- **[8]** Oversized stat numbers (£50k, 6+, 120+) used as visual anchors — font-size scaling with viewport
- **[8]** Italic serif on 'Bankyz' in feature heading — brand emphasis via font-style:italic
- **[8]** Large BANKYZ wordmark in footer — oversized display, likely SVG or font-size:~120px
- **[8]** Monospace uppercase for announcement bar and section labels — letter-spacing: 0.1em
- **[8]** Case study italic serif for process annotations (Low + Medium, High Fidelity)
- **[8]** Monospace uppercase for category labels — font-family: monospace; text-transform: uppercase; letter-spacing: 0.1em
- **[8]** Uppercase hero text on crypto landing — text-transform:uppercase with letter-spacing:0.05em
- **[8]** Font preview panel showing 6 typeface variants as selectable tiles — custom component
- **[8]** Monospace uppercase tracking for data labels (DM Mono, letter-spacing: 0.1em)
- **[8]** Large watermark text in background of hero mockup photo (opacity ~0.08, mix-blend-mode)

## Hero Patterns

- **[9] layered** (AI-powered deal document analysis for private capi): Floating annotations mid-page → massive headline bottom-left → subhead/CTA bottom-right
- **[8] full-bleed** (SME business lending marketplace and comparison pl): Badge→Headline→Team silhouette photo→Nav CTA
- **[8] centered** (Personal finance management mobile app with bank a): Badge → headline → subhead → CTAs → phone mockup with hills
- **[8] left-right** (AI investment intelligence terminal for institutio): Badge→Headline→Subhead→CTAs→Product screenshot below
- **[8] centered** (AI investment intelligence platform for institutio): INTEGRATIONS badge → headline → subhead → CTA button → diagram below
- **[8] left-right** (Multi-product fintech UI/UX design system by Aroun): Headline→chart widget→CTA→article section
- **[8] left-right** (AI portfolio intelligence and quantitative risk en): PRODUCT badge → serif headline → subhead → CTA → dashboard mockup below
- **[8] left-right** (AI-powered personal finance mobile app): Badge→Headline→CTAs→Phone mockup with hand→Stats bar
- **[8] centered** (AI investment intelligence terminal for institutio): Badge→Headline→Subhead→CTAs→Logo trust bar→Product screenshot
- **[8] layered** (Digital neobank with social features and event net): Yellow headline → woman's face → credit cards → stats badges → chart card

## Card & Component Patterns

- **[9]** Large rounded-16px cards, glassmorphic overlay on photo state, clean white on wireframe state, ~32px padding, inner nested card with rounded-12px for text content
- **[8]** Team member cards — light grey bg (#f5f5f5), ~12px radius, ~24px padding, headshot top, name/title below, LinkedIn icon, no hover visible
- **[8]** Bento-grid cards with 12-16px radius, ~20-24px padding, green/sage/white fills, some with rounded photo crops, no visible hover in static
- **[8]** White bg, 12-16px radius, 24-32px padding, subtle box-shadow, product UI screenshots embedded — used for features and data layer sections
- **[8]** Light bg cards in tools grid — ~8px radius, ~24px padding, icon+category-tag+title+description layout, subtle border, 3-column grid
- **[8]** Dark surface #1a1f2e, border-radius:16px, 24px padding, subtle 1px border rgba(255,255,255,0.06), no hover lift visible, inner content uses 12-16px gaps
- **[8]** Dark surface (#1a1a1a), 12px radius, 24-32px padding, dashed border on feature cards, alternating image-left/image-right layout
- **[8]** Floating UI cards with 12-16px radius, white bg, subtle shadow, 16-20px padding — used as overlaid spend-overview and transaction cards on phone mockup
- **[8]** Light bg (#F5F5F3), 12-16px radius, 24-32px padding, subtle 1px border, no hover visible, contains UI preview images + title + description
- **[8]** Glassmorphic with ~20px radius, ~32px padding, frosted white bg rgba(255,255,255,0.85), subtle shadow, no hover visible
- **[8]** Feature cards with light background (#F6F6F5), ~16px radius, ~32px padding, subtle border or shadow, chart/graph content inside
- **[7]** White/cream bg, no border-radius or subtle 4px, ~24px padding, navy 'Learn More' button at bottom, property image top, structured data fields below — clean and data-dense
- **[7]** Rounded-16px, white or #ECE7FA bg, 24px padding, subtle box-shadow (0 2px 12px rgba(0,0,0,0.06)), no hover animation visible, flex column layout with icon top
- **[7]** Dark surface cards (#1a1a1a est.), 8-12px radius, 32px padding, subtle 1px border rgba(255,255,255,0.08), no hover effect visible, vertical stack layout
- **[7]** White cards, border-radius ~16px, padding ~24-32px, no hover effect visible, stacked vertical layout with subtle box-shadow

### Buttons

- **primary / text-link**: `text-decoration with arrow entity →`
- **ghost / text-link**: `font-weight:600 with inline arrow`
- **primary / pill**: `border-radius: 999px; background: #42B676`
- **secondary / pill**: `border: 1px solid rgba(255,255,255,0.3); border-radius: 999px`
- **ghost / pill**: `border: 1px solid #ddd; border-radius: 999px`
- **primary / pill**: `background-color + border-radius:24px + arrow icon`
- **secondary / pill**: `border:1px solid + border-radius:24px`
- **ghost / pill**: `transparent bg, subtle border`
- **primary / rounded-8**: `background-color: #115713; border-radius: 8px`
- **secondary / rounded-8**: `border: 1px solid rgba(255,255,255,0.3); backdrop-filter: none`
- **ghost / rounded-8**: `border: 1px solid #ccc; color: #030704`
- **primary / rounded-8**: `border: 1px solid rgba(255,255,255,0.3); background: transparent`
- **secondary / rounded-8**: `border: 1px solid #333`
- **ghost / rounded-8**: `border: 1px solid #ccc on light bg`
- **primary / pill**: `background-color with border-radius:22px`
- **secondary / pill**: `border:1px solid with transparent bg`
- **ghost / rounded-8**: `backdrop-filter:blur with rgba background`
- **primary / rounded-8**: `background: white; color: black; border-radius: 6px`
- **ghost / rounded-8**: `border: 1px solid rgba(255,255,255,0.3)`
- **primary / pill**: `background: #0E0D0F; border-radius: 24px; with arrow icon`
- **secondary / pill**: `border: 1px solid #0E0D0F; border-radius: 24px; with play icon`
- **nav-cta / pill**: `background: #0E0D0F; border-radius: 20px; circle arrow icon appended`
- **primary / rounded-8**: `background-color with border-radius: 6-8px`
- **secondary / rounded-8**: `border: 1px solid + transparent background`
- **badge / pill**: `border-radius: 999px + small padding + green background`
- **primary / pill**: `border-radius:24px; background:#E84B8A`
- **secondary / pill**: `border:1px solid rgba(255,255,255,0.3); backdrop-filter:blur(8px)`
- **ghost / pill**: `backdrop-filter:blur(10px); background:rgba(255,255,255,0.15)`

## Animation & Interaction

- **[9]** scroll-state-transition: photo→wireframe hero morph → Framer-Motion or GSAP ScrollTrigger
- **[9]** hover-arrow-slide: CTA arrows animate right on hover → CSS transform
- **[9]** parallax-subtle: floating annotations move at different scroll speeds → transform3d
- **[9]** fade-in-sections: content cards fade up on scroll entry → IntersectionObserver + opacity/translateY
- **[9]** glassmorphic-hover: card overlay opacity shifts on hover → backdrop-filter transition
- **[8]** Form step transitions — slide/fade between wizard steps → Framer-Motion AnimatePresence
- **[8]** Chip-select toggle — teal fill on selection with smooth background transition → CSS transition
- **[8]** Currency input formatting — real-time £ formatting as user types → React controlled input
- **[8]** Mobile menu expand — full-screen dark overlay with staggered link reveals → GSAP or Framer-Motion
- **[8]** Stat counter animation — numbers count up on scroll into view → Intersection Observer + requestAnimationFrame
- **[8]** Scroll-triggered section fade-in → Framer-Motion or GSAP ScrollTrigger
- **[8]** Tab switching on features section → state toggle with content crossfade
- **[8]** Hover card lift on bento items → transform:translateY(-4px) + box-shadow transition
- **[8]** CTA button arrow animation → translateX on hover
- **[8]** Phone mockup parallax scroll → subtle translateY offset on scroll
- **[8]** scroll-fade — section content fades up on viewport entry → Framer-Motion useInView
- **[8]** hover-button-fill — secondary buttons fill on hover → CSS transition on background-color
- **[8]** announcement-bar-dismiss — X button removes banner → React state toggle with height animation
- **[8]** logo-bar-scroll — possible infinite scroll marquee → CSS animation or Framer-Motion
- **[8]** product-demo-parallax — browser frame slight parallax on scroll → transform: translateY with scroll listener
- **[8]** Tab category filtering → fade/slide card transitions → Framer-Motion AnimatePresence
- **[8]** FAQ accordion expand/collapse → height animation → Radix Accordion + CSS transition
- **[8]** Scroll-triggered section reveals → fade-up on intersection → Framer-Motion whileInView
- **[8]** Diagram node hover → subtle scale + glow increase → CSS transform + box-shadow transition
- **[8]** Load More button → progressive card reveal → client-side pagination with motion
- **[8]** Card carousel with left/right arrow navigation → Framer-Motion AnimatePresence
- **[8]** Scale/rotate sliders updating card preview in real-time → React state + CSS transform
- **[8]** Font selector grid with live preview panel → controlled component state
- **[8]** Image thumbnail selection with active border highlight → CSS :checked pseudo-class or React state
- **[8]** Account pill selector at bottom → toggle state with transition
- **[8]** scroll-reveal on feature cards → Framer-Motion or Intersection Observer
- **[8]** dashboard-mockup-entrance — fade-up with staggered card reveals → GSAP/Framer-Motion
- **[8]** hover-state on feature chips/tags → background-color transition
- **[8]** announcement-bar dismiss → CSS transition on height/opacity
- **[8]** nav-dropdown on Products → transform: translateY with opacity transition
- **[8]** Scroll-triggered stat counter animation — Framer Motion or GSAP ScrollTrigger
- **[8]** Floating card entrance with staggered fade-up — Framer Motion variants
- **[8]** Logo bar infinite scroll marquee — CSS animation or Swiper
- **[8]** CTA hover scale + arrow animation — CSS transition
- **[8]** Phone mockup parallax on scroll — Framer Motion useScroll
- **[8]** scroll-fade-in — sections reveal on scroll → Framer-Motion or Intersection Observer
- **[8]** hover-button-fill — outline buttons fill on hover → CSS transition
- **[8]** announcement-banner-dismiss — close button on top banner → state toggle
- **[8]** tab-switching — Data/Intelligence/Decision layer tabs → React state + CSS transitions
- **[8]** product-screenshot-carousel — dot indicators suggest slide navigation → Framer-Motion or Embla
- **[8]** 3D objects floating/bobbing → Framer-Motion animate with y oscillation
- **[8]** Scroll parallax on hero layers → GSAP ScrollTrigger or Framer-Motion useScroll
- **[8]** Card hover lift → transform:translateY(-4px) + box-shadow increase
- **[8]** Nav pill slide → CSS transition on background position
- **[8]** Stats counter animation → countUp.js or Framer-Motion useInView
- **[8]** scroll-fade-in sections → Framer-Motion or Intersection Observer
- **[8]** parallax-clouds on final CTA → CSS transform:translateY with scroll listener
- **[8]** hover-button-darken → CSS transition on background-color
- **[8]** device-mockup-float → subtle CSS animation translateY loop
- **[8]** email-input-focus-expand → CSS transition on width/border-color
- **[7]** CTA button outline-to-fill hover → CSS transition
- **[7]** Portfolio carousel with arrow navigation → JS carousel or Swiper
- **[7]** Load More button for portfolio grid → JS pagination or infinite scroll
- **[7]** Scroll-based section reveals → IntersectionObserver or CSS scroll-animation
- **[7]** Nav hamburger toggle on mobile → JS click handler with CSS transform

## Decorative Elements

- **gradient-overlay** at Hero bottom third: `linear-gradient with transparent-to-dark`
- **glass-card** at Foundations text overlay on image: `backdrop-filter: blur() with semi-transparent bg`
- **border-glow** at Card edges on dark state: `border with rgba white + subtle box-shadow`
- **drop-shadow** at Entire hero card container: `box-shadow with large spread, low opacity`
- **teal-gradient-wave** at Mobile menu footer, dark sections: `background: linear-gradient or SVG path with gradient fill`
- **diagonal-stripes** at Brand presentation tablet mockup: `CSS linear-gradient repeating or SVG`
- **concentric-circles** at Burgundy presentation background: `border: 1px solid rgba() with border-radius: 50%`
- **venetian-blind-photography** at Hero backgrounds (story + team pages): `Full-bleed background-image with overlay`
- **3D green hills landscape** at Hero bottom, wrapping phone mockup: `Positioned PNG/WebP with z-index layering over gradient bg`
- **Soft cyan gradient** at Hero background: `background: linear-gradient(to bottom, #AEEDFD, #F5F3EE)`
- **Rounded photo crops** at Steps section, feature tabs: `border-radius:16px + overflow:hidden + object-fit:cover`
- **Green tinted card fills** at Bento feature grid: `background-color with opacity variations`
- **radial-gradient-glow** at Hero background — green glow emanating from center-left: `radial-gradient with multiple color stops`
- **grid-overlay** at Visible in wireframe shots — dotted column guides: `background-image: repeating-linear-gradient`
- **gradient-fade** at Dark-to-light section transition: `linear-gradient on section backgrounds`
- **browser-chrome-frame** at Product demo section: `border-radius + box-shadow + traffic-light dots`
- **gradient-overlay** at Hero top section: `background: linear-gradient(180deg, #17541B 0%, #040505 100%)`
- **grid-lines** at Integration diagram background: `background-image with repeating-linear-gradient or SVG grid pattern`
- **dashed-borders** at Category labels around diagram nodes: `border: 1px dashed rgba(255,255,255,0.2); border-radius`
- **glow** at Central Arbitra logo icon: `box-shadow: 0 0 40px rgba(105,191,113,0.3)`
- **radial-glow** at Behind card preview center: `radial-gradient with large spread`
- **green-ambient-glow** at Crypto landing left side: `radial-gradient or box-shadow with large blur`
- **glass-card-borders** at Card containers throughout: `border:1px solid rgba(255,255,255,0.08)`
- **purple-gradient-bg** at ManageIT mobile background: `linear-gradient from purple to lavender`
- **card-perspective-stack** at Behind main credit card: `transform:perspective() rotateY() with stacked z-index`
- **gradient-atmosphere** at Hero background, green-to-black ambient glow: `radial-gradient or background-image`
- **dashed-border-frames** at Feature card containers and dashboard preview: `border: 1px dashed; with border-radius`
- **watermark-text** at Background of hero photo — large 'Arbitra' text: `opacity: 0.05; mix-blend-mode: overlay`
- **dot-connectors** at Between feature cards in vertical flow: `border-left: 2px dashed; or SVG path`
- **warm-to-cool gradient** at Hero background: `linear-gradient or radial-gradient with multiple color stops`
- **purple-lavender gradient** at Hero right side bleed: `background: linear-gradient`
- **floating UI cards** at Over phone mockup: `position: absolute with box-shadow and transform`
- **3D glass cube** at Brand identity collateral: `3D render, not CSS`
- **purple duotone** at Brand photography (image 4): `mix-blend-mode or filter: hue-rotate`
- **browser-chrome-frame** at Product screenshot wrapper: `border-radius + box-shadow + pseudo-element for traffic lights`
- **announcement-banner** at Top of page: `fixed/sticky positioning + background-color + text-align: center`
- **numbered-indicators** at How it works tabs: `flexbox + counter or manual numbering + green accent circle`
- **3D coin with dollar sign** at Inline with headline, top-right area: `position:absolute with z-index layering`
- **3D flower/gem icon** at Inline with BANKING text: `position:absolute`
- **Radial glow** at Behind woman cutout, warm orange tint: `radial-gradient or box-shadow with large spread`
- **Gradient background** at Full hero section: `linear-gradient(to bottom, #03328C, #BCD0DD)`
- **Frosted glass cards** at Value prop and chart cards: `backdrop-filter:blur(20px); background:rgba(255,255,255,0.8)`

## Design Recipes

### Score 9/10 — dimensional-layered — AI-powered deal document analysis for private capital

**Design Recipe:** Use a 7-stop neutral palette from #11191A through #CDBFB6 to #FFFFFF with zero chromatic accents. Set hero H1 at 76px bold Inter/Söhne with -0.02em tracking, body at 17px regular with 1.6 line-height. Hero is full-viewport with architectural photography, bottom gradient overlay (transparent to #11191A over 40% height), and glassmorphic text cards (backdrop-filter: blur(20px), bg rgba(255,255,255,0.08), border 1px rgba(255,255,255,0.12), border-radius 12px). Cards float on page with 16px border-radius and box-shadow 0 24px 64px rgba(0,0,0,0.1). Section numbers in 60px light weight gray (#AAA8A6). All CTAs are text links with → arrows, no filled buttons.

**Dev Recipe:** Next.js + Tailwind CSS + Framer Motion. Use ScrollTrigger or scroll-timeline for the photo-to-wireframe state transition (cross-fade background images while maintaining DOM structure). Implement backdrop-filter glassmorphism for overlay cards, CSS custom properties for the 7-color neutral token system, and IntersectionObserver for section entrance animations.

**Core Lesson:** A restrained all-neutral palette with conceptually aligned photography can create more brand authority than any gradient or accent color ever could.

**Steal These:**
- Architectural photography as structural-clarity brand metaphor
- Photo-to-wireframe scroll transition showing design intentionality
- All-neutral palette with warm-cool gray tension for depth without color
- Floating contextual annotations on hero image as storytelling device
- No filled buttons anywhere — text-link CTAs with arrows convey confidence

**Weaknesses:** Hero floating annotations may feel orphaned without clear visual connection to content below, Two-column hero bottom (headline left, description right) creates competing reading paths, No visible mobile adaptation — the dense layered hero will need significant rethinking for small screens

---

### Score 8/10 — dark-luxury — SME business lending marketplace and comparison platform

**Design Recipe:** Use #040607 dark backgrounds with a high-contrast transitional serif (Playfair Display 700, -0.02em tracking) at 56-72px for hero headlines in white. Pair with Inter 400/500 at 14-16px for body. Reserve a single teal accent (#42B676) exclusively for pill-shaped CTAs (border-radius: 999px, height: 40px, padding: 0 24px) and selected form states — never decorative. Light pages use #ECECEE backgrounds with white card surfaces (border-radius: 12px, padding: 32px, box-shadow: 0 2px 8px rgba(0,0,0,0.06)). Section spacing 96-120px, 8px base grid. Team cards in 3-column grid with grey headshots.

**Dev Recipe:** Next.js 14 with App Router for multi-page SSR, Tailwind CSS with custom dark/light theme tokens, Framer Motion for page transitions and form wizard step animations. Key challenges: multi-step form wizard with Zod validation, Intl.NumberFormat for currency input, and Intersection Observer for stat counter scroll triggers.

**Core Lesson:** Dual-mode design (dark cinematic for brand storytelling, light clean for functional UI) creates emotional separation that makes both modes more effective than either alone.

**Steal These:**
- Single teal accent reserved ONLY for interactive elements — creates instant visual affordance
- Cinematic silhouette team photo as hero — far more compelling than individual headshots grid
- Multi-step form wizard with chip-select buttons instead of dropdowns — reduces friction
- Badge/label above headline ('OUR TEAM') in uppercase small text with border — instant context
- Dark mode for storytelling, light mode for task completion — emotional UX architecture

**Weaknesses:** Mobile navigation uses + icon instead of hamburger — unconventional, may confuse users, Form wizard card could use more visual progress indication beyond small 1/3 text, About/story page left-aligned text block feels text-heavy without visual breaks or pull quotes

---

### Score 8/10 — organic-natural — Personal finance management mobile app with bank aggregation

**Design Recipe:** Use #091710 dark forest for text, #1B5E3B for CTAs, #B1CA27 lime for accent cards, #AEEDFD cyan for hero sky gradient fading to #F5F3EE warm white. Pair Playfair Display (regular, 56-64px headlines) with Inter (16px body). Build on 12-col grid at 1200px max-width with 80-120px section gaps. Pill-shaped buttons (border-radius:24px, 48px height). Bento feature grid with mixed card sizes using 12-16px radius and sage/green fills. Hero is centered text above a 3D organic landscape PNG wrapping a phone mockup.

**Dev Recipe:** Next.js + Tailwind CSS + Framer Motion for scroll animations. Use CSS Grid with grid-template-areas for the bento section, z-index layering for the hero landscape compositing, and IntersectionObserver-driven fade-ups. Self-host the 3D hills as optimized WebP with responsive srcset.

**Core Lesson:** A single bold visual metaphor (growth = green hills) carried consistently through every section creates more brand memorability than ten generic features

**Steal These:**
- 3D organic landscape as hero visual instead of generic gradients or blobs
- Warm off-white (#F5F3EE) background instead of pure white for organic warmth
- Pill-shaped nav container grouping links visually
- Bento grid with mixed green-tinted card fills for feature showcase
- Oversized brand wordmark in dark footer as visual anchor

**Weaknesses:** Bento feature grid is dense and some cards have small text that may be hard to scan quickly, The steps section photos feel generic compared to the distinctive hero — could use the same 3D style, Tab section (Connect/Understand/Improve) content area feels sparse relative to the rest of the page's visual richness

---

### Score 8/10 — dark-luxury — AI investment intelligence terminal for institutional capita

**Design Recipe:** Use #030704 dark background for hero with a radial-gradient glow of #115713→#548035 positioned center-left at 40% opacity. Set headings in DM Serif Display bold at 56-64px with -0.02em letter-spacing, body in Inter 16px #5E615E on #F0F1F0 light sections. 12-column grid at 1200px max-width, 80px vertical padding between sections expanding to 120px for major transitions. Cards use white bg, 12px border-radius, 24px padding, box-shadow: 0 4px 24px rgba(0,0,0,0.06). Green accent (#115713) appears ONLY on primary CTAs, brand marks, and active states — never decorative fills.

**Dev Recipe:** Next.js 14 + Tailwind CSS + shadcn/ui for base components, Framer Motion for scroll-triggered section reveals. Key: use CSS radial-gradient for hero glow (no images), filter:grayscale(1) on logo bar, and a reusable Section wrapper component with configurable dark/light theme prop that handles the gradient transitions.

**Core Lesson:** In fintech, restraint with color builds more trust than vibrancy — one desaturated green (#115713) used sparingly on a near-black (#030704) canvas communicates institutional credibility better than any gradient explosion.

**Steal These:**
- Desaturated forest green as sole accent on near-black — instant institutional credibility
- Browser chrome frame around product demo with traffic-light dots — makes screenshots feel alive
- Monospace uppercase for section labels (/ FEATURES, / HOW IT WORKS) — editorial authority
- Three-column 'stack' diagram (Data Layer → Intelligence Layer → Decision Layer) for explaining AI pipeline
- Announcement bar with monospace text and dismiss X — creates urgency without being obnoxious

**Weaknesses:** Hero text is left-aligned but product screenshot sits below rather than beside — wastes right-side real estate on desktop, Logo bar brands are likely aspirational — could undermine trust if discovered; use 'Built for teams at' framing instead, The dark-to-light transition between hero and features lacks a clear visual device — needs a stronger section divider or gradient fade

---

### Score 8/10 — dark-luxury — AI investment intelligence platform for institutional portfo

**Design Recipe:** Dark base #040505 with green gradient header (#17541B → #040505). Headlines in IBM Plex Serif bold white, body in Inter regular #B0B0B0. Monospace uppercase #69BF71 for section labels (12px, letter-spacing 0.1em). Cards on light sections use #F5F5F5 bg with 8px radius and 24px padding. Category tabs with underline active state. Hub diagram uses CSS grid background lines at ~60px intervals with dashed-border category nodes. 80-120px section spacing. Buttons are ghost/outline style with 1px borders, never solid fills.

**Dev Recipe:** Next.js + Tailwind + Radix UI primitives (Accordion, Tabs, DropdownMenu). Framer Motion for scroll-triggered reveals and tab content transitions. SVG grid pattern for diagram background, CSS Grid for node positioning with absolute-positioned connecting lines. Google Fonts for IBM Plex Serif + Inter.

**Core Lesson:** Restrained color accent on a dark theme creates premium authority — green used ONLY for brand mark, badges, and one CTA creates a clear visual hierarchy without noise.

**Steal These:**
- Monospace uppercase green labels as section identifiers — creates systematic visual language
- Dark-to-light section mode switch to separate conceptual from actionable content
- Hub-and-spoke diagram with dashed-border category labels floating around central brand node
- Tab-filtered integration grid with icon + category tag + title + description card pattern
- Announcement banner with monospace text and dismissible X — creates urgency without disruption

**Weaknesses:** Hub diagram may be difficult to make responsive — likely needs complete mobile redesign as a stacked list, Light tools section feels slightly disconnected from the dark theme — transition could be smoother, FAQ section visible in sidebar appears generic — could benefit from more visual integration with the dark theme

---

### Score 8/10 — dark-luxury — Multi-product fintech UI/UX design system by Arounda agency

**Design Recipe:** Use Poppins font family across all weights (400/500/600) on a near-black base (#020409). Build card surfaces at #1a1f2e with 1px rgba(255,255,255,0.06) borders and 16px border-radius. Apply three accent colors mapped to function: #7FE660 for active/success, #56D6DA for interactive/links, #6074DD for brand/premium. Space with 24px base unit, 48px between sections. Add depth with radial-gradient ambient glows (accent color at 10% opacity, 400px spread) behind focal elements. Keep text hierarchy to just 3 levels: white semibold headings, white medium labels, #A2A3B0 regular body.

**Dev Recipe:** React + Tailwind with custom CSS properties for the 5-color token system. Use Framer Motion for card carousel and slider-driven transforms. Build the card customizer as a compound component with useReducer for scale/rotate/font/image state, applying CSS transform:scale() rotate() to a positioned background-image in real-time.

**Core Lesson:** Dark fintech UI earns trust through functional detail — real controls, real data, real interactions — not just moody gradients

**Steal These:**
- Vertical sidebar nav with green active-state bar indicator — simple but effective
- Card background image picker with scale/rotate sliders for real-time customization
- Font selector as a 2x3 grid of styled 'Aa' tiles with live preview panel adjacent
- Account selector as horizontal pills showing masked card number + currency
- Ambient radial glow behind hero element instead of traditional drop shadows

**Weaknesses:** Four different product contexts in one showcase dilutes the narrative — feels like a portfolio dump rather than cohesive case study, Crypto landing page green glow is heavy-handed compared to the refined dashboard — inconsistent craft level, No visible responsive/mobile adaptation of the dashboard — the mobile screens are entirely different products

---

### Score 8/10 — dark-luxury — AI portfolio intelligence and quantitative risk engine for i

**Design Recipe:** Use #040604 dark background with #F7F8F7 text, accent sparingly with moss green #2A8730. Set headlines in IBM Plex Serif Bold at 56-64px with tight letter-spacing, body in Inter Regular 16px, and all data labels in DM Mono uppercase 12px with 0.12em tracking. Feature sections alternate image-left/image-right in a Z-pattern on a 12-col grid with 120px section gaps. Cards use dark surfaces (#1A1A1A) with 12px radius and optional dashed borders (1px dashed rgba(255,255,255,0.15)). Green is reserved for announcement bars, status badges, and small accent moments — never large surfaces.

**Dev Recipe:** Next.js + Tailwind CSS with Google Fonts (IBM Plex Serif, Inter, DM Mono). Use Framer Motion for scroll-triggered section reveals with staggered children. Dashboard preview is a positioned container with overflow-hidden and multiple absolutely-placed card components styled with dark theme tokens.

**Core Lesson:** A 3-font system (serif for authority, sans for clarity, mono for data) can single-handedly establish a fintech brand's credibility without any gimmicks

**Steal These:**
- Triple-font system: serif headlines + sans body + mono data labels
- Dashed-border containers for dashboard preview framing
- Feature chips/tags below each feature description for quick scanning
- Green announcement bar with monospace uppercase text
- Z-pattern alternating feature cards with embedded UI screenshots

**Weaknesses:** Dashed border motif could feel repetitive if used on every section, Dashboard preview is dense — may overwhelm on smaller screens without careful responsive handling, No visible social proof, testimonials, or trust signals — critical gap for a fintech product

---

### Score 8/10 — warm-minimal — AI-powered personal finance mobile app

**Design Recipe:** Use #0E0D0F near-black for text, #F1EEEE warm off-white background, and a hero gradient from #F7DEA3 (peach-gold) through #C9A8F0 (lavender) to #9B66A4 (muted purple). Pair Playfair Display bold italic for headline emphasis lines with Inter/DM Sans regular for body. Pill-shaped buttons (border-radius: 24px) in solid black with white text and arrow-up-right icons. Hero is left-text/right-imagery at roughly 45/55 split, with phone mockups overlaid by floating white cards (border-radius: 12px, subtle shadow). Stats row uses 48px bold numbers separated by 1px vertical dividers. Maintain 80-100px section spacing on an 8px grid.

**Dev Recipe:** Next.js + Tailwind CSS + Framer Motion for scroll-triggered animations. Use next/image for optimized phone/hand photography composites, CSS linear-gradient for hero background, and position:absolute layering for floating UI cards over device mockups. Intersection Observer for stat counter animations.

**Core Lesson:** Warm gradients and serif typography can make fintech feel human and approachable without sacrificing professionalism.

**Steal These:**
- Peach-to-purple warm gradient replacing typical cold fintech blue
- Serif italic for emotional headline words mixed with sans-serif for factual ones
- Real hand photography holding phone instead of flat device mockups
- Arrow-up-right icon as consistent brand motif across logo, buttons, and cards
- Stats row with bold numbers + vertical pipe dividers for quick credibility scanning

**Weaknesses:** Hero right side is visually congested — phone mockup + hand + floating cards + gradient all compete, The 'Next-Gen AI Finance Hub' badge feels generic and adds little value, Logo bar companies appear fictional (Acme Corp, Hexsmith) — undermines trust signals in a fintech context

---

### Score 8/10 — minimal-corporate — AI investment intelligence terminal for institutional capita

**Design Recipe:** Use #0F110E dark hero with #FFFFFF text at 48-56px bold Inter. Accent with #374633 forest green on badges (pill shape, 28px height) and CTAs only. Light sections use #E8E8E4 warm off-white. Section labels in monospace uppercase 12px with wide letter-spacing prefixed by '/'. 3-column feature grid with 12px radius cards, 1px #C3C6B8 border, 24px padding. Product screenshots wrapped in browser chrome frames (3 colored dots, rounded corners, subtle shadow). Logo bar at 60% opacity grayscale. 80-120px between sections, 8px base spacing unit.

**Dev Recipe:** Next.js + Tailwind CSS with custom color tokens extending the green-neutral palette. Use Framer-Motion for scroll-triggered section reveals, Embla Carousel for product screenshot slider, and CSS custom properties for dark/light section theming. Key CSS: filter:grayscale(1) for logos, font-family:monospace for labels, box-shadow for card depth.

**Core Lesson:** In B2B fintech, showing the actual product UI as the hero visual is more persuasive than any illustration or abstract graphic — it simultaneously demonstrates capability and builds trust.

**Steal These:**
- Monospace uppercase section labels with '/' prefix — instant editorial sophistication
- Product dashboard screenshots as hero imagery instead of abstract illustrations
- Green-tinted neutral palette where even grays carry the brand hue
- Numbered tab system for 'how it works' that breaks complex architecture into digestible layers
- Dual-model comparison cards (GPT-4 vs Perplexity) showing AI transparency as a feature

**Weaknesses:** Feature grid section (6 cards) risks visual monotony — varying card sizes or adding a featured/large card would improve hierarchy, No visible social proof beyond logos — testimonials or case study metrics would strengthen conversion, Dark-to-light section transitions feel abrupt — a gradient or transitional element between hero and content sections would smooth the flow

---

### Score 8/10 — dimensional-layered — Digital neobank with social features and event networking

**Design Recipe:** Use Clash Display Black at 120-140px in uppercase #F1DA1E on a linear-gradient(180deg, #03328C 0%, #1457AB 40%, #BCD0DD 100%) background. Layer a cutout photo at z-index:2 with the headline split across z-index:1 and z-index:3 so the person weaves through the text. Add 2-3 Spline/Blender 3D objects (metallic purple/pink, ~64px) positioned inline with text gaps. Bottom cards use backdrop-filter:blur(20px) with background:rgba(255,255,255,0.85) and border-radius:20px. CTAs are pill-shaped #E84B8A with 24px radius. Keep stats minimal with avatar stacks and 3D icon accents.

**Dev Recipe:** Next.js + Tailwind + Framer-Motion. Hero requires absolute positioning grid with 5+ z-index layers; use CSS clip-path or manual z-index orchestration for text-behind-photo effect. Spline viewer or pre-rendered WebP for 3D objects with Framer-Motion float animations. Backdrop-filter for glass cards.

**Core Lesson:** Z-index layering of photography with oversized typography creates dimensional drama that flat layouts cannot achieve — the key is having elements both behind AND in front of the photo.

**Steal These:**
- Yellow uppercase headline weaving behind a photo cutout — instant visual drama
- 3D objects placed in text gaps replacing letters (coin replacing O in OF)
- Glassmorphic value-prop card overlapping the hero photo at bottom
- Avatar stack + large stat number as lightweight social proof
- Pink CTA pill on blue gradient — complementary color pop for conversion

**Weaknesses:** Hero composition is extremely fragile for responsive — will break below 1024px without complete redesign, 3D icons trend is aging fast — may feel dated within 12 months, The four screenshots are clearly different projects stitched together as a portfolio case, not a cohesive product system

---

### Score 8/10 — warm-minimal — Invite-only wealth management for high achievers

**Design Recipe:** Use #F6F6F5 off-white on #D4C4A8 sand outer background. Set headlines in Playfair Display Regular at 56-64px with -0.02em tracking, body in DM Sans 16px #161514. Section spacing 120-160px. Inline email+CTA pill combo with 6px radius, dark fill button. Full-bleed cinematic photography (marble, clouds, golden hour) as section dividers. Reserve #D1A756 gold for data accents only. App UI uses #1A2E2E dark teal with #00E5CC cyan for charts. Device mockups at slight perspective angle with natural shadows.

**Dev Recipe:** Next.js or Astro with Tailwind CSS, custom CSS properties for warm/dark theme sections. Framer Motion for scroll-triggered fade-ins and parallax cloud section. Self-host Playfair Display + DM Sans via next/font.

**Core Lesson:** Warmth and restraint together create more perceived luxury than dark-and-gold maximalism — the sand background does more brand work than any gradient ever could.

**Steal These:**
- Sand/parchment outer background wrapping white content cards — instant warmth upgrade
- Dual color worlds (warm light landing + dark teal app) unified by gold accent thread
- Uppercase wide-tracked eyebrow labels above serif headlines for hierarchy
- Inline email input with embedded CTA button as single pill-shaped unit
- Full-bleed cinematic photography as section dividers instead of decorative blobs

**Weaknesses:** Center-aligned body text in the mission section gets hard to read at longer paragraph lengths — left-align would improve scanability, The vintage illustration asset sheet feels disconnected from the landing page's photographic direction — unclear how they integrate, App suite section cramming phone + laptop mockups creates visual density that fights the generous whitespace rhythm elsewhere

---

### Score 7/10 — minimal-corporate — Private equity investment management firm website

**Design Recipe:** Use Playfair Display bold for headings at 48-56px on a warm off-white (#E8E7DF) background, Inter regular 15-16px for body in #444A51. Navy (#1B2B4B) for hero/nav/footer backgrounds with white text. Uppercase letter-spaced (2-3px) section labels in 12px semibold as wayfinding. Bronze/tan (#907066) ONLY for CTA borders and key accent moments. Create a 45-degree diamond crosshatch SVG pattern in semi-transparent navy as your signature decorative element, placed at section transitions and hero corners. Alternate sections between cream and white backgrounds. All buttons are outlined with 1.5px borders, filling solid on hover. 80-100px vertical section padding, 1200px max-width container.

**Dev Recipe:** Next.js or Astro for multi-page SSG with Tailwind CSS for utility-first styling. Use CSS custom properties for the 3-color palette, create the diamond pattern as an inline SVG with opacity:0.1 positioned absolutely. Swiper.js for portfolio carousel, IntersectionObserver for scroll-triggered fade-ins. Google Fonts: Playfair Display 700 + Inter 400/500/600.

**Core Lesson:** In finance/institutional design, restraint IS the design — a tight 3-color palette (deep navy #1B2B4B, warm cream #E8E7DF, bronze accent #907066) with one signature decorative motif creates more authority than any amount of visual complexity.

**Steal These:**
- Warm cream (#E8E7DF) instead of pure white — instantly elevates any corporate design
- Diamond crosshatch pattern as a repeating brand texture element across sections
- Uppercase letter-spaced micro-labels above every section heading for clear wayfinding
- Outlined CTA buttons that fill on hover — feels premium and restrained
- Structured property cards with labeled data fields (Strategy, Location, Units, Price) — shows domain expertise

**Weaknesses:** About page is text-heavy with insufficient visual breaks — the mission/values section needs more breathing room or visual hierarchy, Portfolio cards are data-dense but visually repetitive — varying card sizes or a featured property would add rhythm, Mobile responsive version shows the hero CTA as full-width outlined button which loses the premium feel of the desktop version

---

### Score 7/10 — warm-minimal — AI personal finance tracker with spending insights and smart

**Design Recipe:** Use #FFFFFF background with #0C0D11 text and #554CC1 as sole accent. Pair a modern display serif (Clash Display from Fontshare, 700 weight) for headlines with Inter/DM Sans 400 for body at 16px. Set headlines at 56-64px with -0.02em tracking. Use italic serif for 2-3 key accent words per section. Create a full-width marquee band in #554CC1 with outlined white text at 120px+. All cards use 16px border-radius, 24px padding, subtle shadow. Section badges are pill-shaped with emoji + text. Spacing: 80-100px between sections, 8px base grid. Max-width 1200px container.

**Dev Recipe:** Next.js + Tailwind CSS + Framer Motion. Use CSS keyframes for infinite marquee, -webkit-text-stroke for outlined text, Framer Motion for scroll-triggered reveals and phone mockup parallax. Self-host Clash Display via @font-face, load Inter from Google Fonts.

**Core Lesson:** A single well-chosen accent color (warm purple) applied with discipline across a white canvas creates more brand impact than a complex multi-color palette

**Steal These:**
- Italic serif accent words within sans-serif headlines for instant sophistication
- Full-width marquee brand ticker as visual section divider — breaks monotony of stacked sections
- Phone mockup overlapping the marquee band — creates depth without complex 3D
- Avatar stack + large stat number as compact social proof in hero
- Consistent pill-shaped section labels with emoji prefix as wayfinding elements

**Weaknesses:** Hero layout is extremely common left-text/right-mockup pattern — consider asymmetric or centered hero for differentiation, Right sidebar section (visible in screenshot 1) feels cramped and disconnected from main page flow — information density too high, No visible micro-interactions or hover states on feature cards — feels static for an AI product that should feel alive

---

### Score 7/10 — dark-luxury — AI portfolio intelligence for institutional investors

**Design Recipe:** Use #040504 dark background with #D4D4D4 text and a single dark forest green (#0F4C11) accent reserved ONLY for interactive/confirmation elements (toggles, checkmarks, badges). Set headings in Inter Semibold 56px with -0.02em tracking, section labels in 12px uppercase with 3px letter-spacing. Build 3-column plan cards with 1px rgba(255,255,255,0.08) borders, 32px internal padding, and clear visual separation between INCLUDES (access items with gray icons) and FEATURES (capability items with green checkmarks). Add a comparison table on a slightly lighter surface (#f5f5f5) with alternating row hints and sticky left labels.

**Dev Recipe:** Next.js + Tailwind + shadcn/ui for toggle, table, and badge primitives. Use CSS Grid for the comparison table with position:sticky on the first column, Framer Motion for the billing toggle price-swap animation, and a radial-gradient pseudo-element for the green corner glow.

**Core Lesson:** In enterprise fintech, information architecture IS the design — separating 'what you get access to' from 'what the product can do' is more valuable than any visual flourish.

**Steal These:**
- INCLUDES vs FEATURES separation in pricing cards — brilliant UX distinction
- Dark forest green (#0F4C11) as sole accent — avoids cheap fintech green
- Uppercase tracked section labels (PRICING, COMPARE PLAN) for institutional authority
- Comparison table as separate section below cards — reduces cognitive load per section
- Save 10% badge on billing toggle — small green pill creates urgency without being aggressive

**Weaknesses:** No visible CTA buttons on individual plan cards — users need a clear 'Get Started' per plan, Enterprise 'Custom Contract' card lacks differentiation — should have visual emphasis or different treatment, Green gradient glow in top-right feels disconnected from content — decorative without purpose

---

### Score 7/10 — warm-minimal — Subscription tracking and expense management SaaS

**Design Recipe:** Use Inter font family at weights 400/600/700. Background: #F3F3F4 for cards, #E85E57 coral for showcase wrapper. All cards: white, 16px border-radius, 24-32px padding, subtle shadow (0 4px 16px rgba(0,0,0,0.06)). Single accent: #F8231D for pill buttons (24px radius, 44px height), active toggles, and monetary totals. Text hierarchy: #0B0D14 for headlines, #444B5A for body, #747988 for captions. Spacing: 16px base unit, 32px between card sections, 8px between list items. Step indicator as a pill badge with light gray background and 12px rounded corners.

**Dev Recipe:** Next.js + Tailwind CSS with a multi-step form using React context for state persistence. Custom toggle component with CSS transitions, Framer Motion for step transitions (AnimatePresence with slide variants), and a systematic design token file mapping the coral/gray palette to Tailwind config.

**Core Lesson:** A single bold accent color (#F8231D coral-red) on a near-white (#F3F3F4) surface creates both visual hierarchy and brand identity when applied with strict discipline — only on CTAs, key data points, and one headline keyword.

**Steal These:**
- Coral (#E85E57) background behind white cards — instant visual richness with zero complexity
- Red accent only on actionable elements and key financial figures — creates scannable hierarchy
- Step X of Y pill badge in top-right — lightweight progress indication without a full stepper
- Subscription list with monthly totals in red — makes the 'aha moment' visually obvious
- Back button as outline pill + Next as solid pill — clear primary/secondary action pairing

**Weaknesses:** Portfolio mixes 3+ unrelated projects (fintech, NFT, analytics dashboard) — lacks focused narrative, Image 1 is cropped/cut off on the left — sloppy presentation that undermines the work, No empty states, error states, or edge cases shown — feels like happy-path-only design

---

### Score 7/10 — dark-luxury — Digital banking card and payment platform

**Design Recipe:** Use #050505 dark sections alternating with #F8F7F7 light sections on a #F5BE9B warm peach ambient background. Headlines in Playfair Display Bold 64-72px with #DD543C orange italic on 1-2 keywords per heading. Body in Inter 16px #584844. CTAs are #DD543C solid pills with white text. Cards use #1A1A1A with 12px radius. Maintain 100-120px section gaps. Place 5% opacity brand watermark text at 15vw behind hero. Stack 3D credit card mockups with perspective transforms at -15deg Y rotation.

**Dev Recipe:** Next.js + Tailwind CSS with Framer-Motion for scroll reveals and 3D card transforms. Use CSS perspective/rotateY for card stacks, IntersectionObserver for section animations, and radial-gradient on body for warm ambient glow. Google Fonts: Playfair Display + Inter.

**Core Lesson:** Selective color highlighting on individual keywords within headlines creates instant visual hierarchy and brand voice without needing complex layouts.

**Steal These:**
- Orange italic keyword highlighting within dark serif headlines — instant editorial authority
- Brand name watermark at massive scale behind hero at 3-5% opacity
- Warm peach ambient page background that softens dark/light section transitions
- 3D stacked credit card mockups with perspective tilt as hero visual
- Mixing stat counters ($5B+, 120+, 15M+) throughout page as trust anchors between content sections

**Weaknesses:** Section structure is predictable — hero/stats/features/logos/testimonials/pricing follows every fintech template, The additional screenshots (smart home app, affiliate tool) suggest this is a portfolio piece with inconsistent focus, Some body copy feels placeholder-quality ('Trusted by million of satidified users' has a typo)

---

### Score 7/10 — minimal-corporate — Personal finance budget management dashboard with AI assista

**Design Recipe:** Use Inter at 14px body / 28-32px h1 / 48px stat numbers on #F4F3F7 background. Cards are white (#FFFFFF) with 16px border-radius, 24px padding, box-shadow: 0 1px 4px rgba(27,26,30,0.08). Primary accent #3E27E7 only on CTAs and active nav items. Horizontal top nav with 8 items, 40px height links. 12-col grid at 1200px max-width, 24px gutters. Stat cards in 3-col row, charts below in 2:1 ratio. Sidebar settings pages use vertical tab nav left, content right. Dark mobile variant uses #1C1C1E bg with glassmorphic balance card (rgba(255,255,255,0.08) bg + backdrop-filter: blur(20px)).

**Dev Recipe:** Next.js App Router + Tailwind CSS + shadcn/ui for inputs/modals/tabs. Recharts for line/bar/donut charts, custom SVG for credit gauge. Framer Motion for modal transitions and page animations. Use CSS custom properties for light/dark theme toggle.

**Core Lesson:** Comprehensive screen coverage with consistent components builds more credibility than one flashy hero screen — show the boring settings pages too.

**Steal These:**
- AI assistant chat page with suggestion chips below greeting — great onboarding pattern
- Glassmorphic balance card on dark mobile with metallic gradient hint
- Credit score gauge with multi-color gradient arc (green→blue→pink→red)
- Generate Custom Report modal with format toggles (PDF/Excel/CSV/HTML)
- Payment Distribution donut chart paired with summary stats on scheduled payments page

**Weaknesses:** Purple accent is safe but generic — every other fintech dashboard uses violet/indigo, No empty states, error states, or loading skeletons shown — incomplete design system, Real estate dashboard variant feels disconnected from Finexa brand — portfolio padding rather than product depth

---

### Score 7/10 — dark-luxury — Personal and business finance management dashboard SaaS

**Design Recipe:** Use #070505 base with #1A1412 card surfaces, #E23710 orange-red for all CTAs and active states, #9D9B99 warm gray for body text on dark. Pair Playfair Display italic for emotional headline words with Inter/DM Sans regular for everything else. Cards get 16px radius, 1px rgba(255,255,255,0.06) borders, 24px internal padding. Section spacing at 80-100px, hero uses centered layout with pill badge above headline, dual pill CTAs below. Dashboard mockup screenshot anchors the hero with slight perspective tilt.

**Dev Recipe:** Next.js + Tailwind CSS with custom dark theme tokens. Use Framer Motion for scroll-triggered section reveals, Embla Carousel for testimonials, and a CSS custom property system for the warm-dark palette. Key: radial-gradient overlays on hero image, consistent 1px border cards, and toggle component for pricing.

**Core Lesson:** Warm accent colors on dark themes create approachable luxury — avoid cold blues for fintech differentiation.

**Steal These:**
- Serif italic for emotional keywords in sans-serif headings — instant personality
- Warm brown radial gradient over hero photo instead of plain dark overlay
- Orange dot + pill badge pattern for section labels (◉ Why Choose Us)
- Dashboard mockup as hero social proof — shows product immediately
- Stat counters (50M+, 4.9, 120+) beside feature description for credibility

**Weaknesses:** Mountain landscape hero is generic and disconnected from fintech product — a custom illustration or abstract would be stronger, Too many sections create scroll fatigue — could consolidate features + built-for into one, Pricing card hierarchy is weak — Pro plan 'recommended' badge needs more visual differentiation beyond a small label

---

### Score 7/10 — neo-brutalist — Multi-currency e-wallet for global freelancers and remote te

**Design Recipe:** Use #EAE9DA warm cream as primary bg, #030303 for all text, #FDD800 yellow for CTAs/accents/highlight sections. Set headings in an ultra-condensed grotesque (Tusker Grotesk 900 or Dharma Gothic E Bold) at 72-96px uppercase with -0.02em tracking. Body in Inter/DM Sans 14-16px regular. 12-col grid at 1200px max-width. Alternate sections between cream, dark (#1A1A1A), white, and yellow backgrounds. Use pill-shaped buttons (border-radius: 999px) with yellow fill. Add subtle noise texture to cream sections at 3% opacity. Feature cards: white bg, 12px radius, 1px #E0E0E0 border, 24px padding, yellow numbered circle badges.

**Dev Recipe:** Next.js + Tailwind CSS with custom color tokens (cream-50, yellow-500, dark-900). Self-host the display font via @font-face. Use Framer Motion for scroll-triggered section reveals with staggerChildren. Swiper.js for testimonial carousel with scroll-snap fallback.

**Core Lesson:** A restricted 3-color palette (cream + black + one saturated accent) with an ultra-condensed display typeface can make a fintech brand feel bold and distinctive without any gradients or complex illustration work.

**Steal These:**
- Cream (#EAE9DA) background instead of white — instantly warmer and more premium
- Ultra-condensed uppercase headlines as the primary brand differentiator
- Yellow numbered circle badges as a consistent wayfinding system across all sections
- Dark/cream/yellow section alternation rhythm for visual pacing
- Transaction list card with real brand logos (Dribbble, Figma) to make the product feel tangible

**Weaknesses:** Benefit cards all have identical placeholder text ('No hidden fees vs unpredictable bank charges') — breaks immersion and looks unfinished, Flag row and some sections feel slightly generic/template-like without unique illustration or motion, Mobile layout (screenshot 3) compresses the card mockup awkwardly — needs dedicated mobile composition

---

### Score 7/10 — warm-minimal — Global payment processing SaaS for modern businesses

**Design Recipe:** Use #F3F4F2 warm off-white background, #15130D near-black text, #3ED21B vivid green for CTAs and one headline word highlight only. Set headings in Clash Display Bold at 56-64px with -0.02em tracking, body in Inter 16px/1.6. Cards get 16px radius, 24px padding, #F3F4F2 or #BDCFA9 backgrounds. Alternate sections between white, muted sage green, vibrant green, and dark backgrounds. Scatter 3D rendered money/wallet objects around hero with absolute positioning and slight rotation. Pill-shaped buttons with 999px radius, 44px height. 80-120px between sections, 1200px max-width container.

**Dev Recipe:** Next.js + Tailwind CSS with custom color tokens (off-white, near-black, vivid-green, sage). Use Framer Motion for scroll-triggered fade-ups on sections, CSS transforms for 3D object positioning, and a responsive grid that hides decorative objects below 768px.

**Core Lesson:** A single vibrant accent color (#3ED21B) on a warm neutral base (#F3F4F2, #15130D) creates more brand distinction than a complex multi-color palette

**Steal These:**
- Green accent on only one word in the hero headline for instant eye-catch
- Warm off-white (#F3F4F2) instead of pure white for approachable fintech feel
- 3D rendered money objects scattered casually around hero for playful authority
- Alternating section background colors (white→sage→green→dark) for visual rhythm
- Giant watermark brand name in footer as subtle brand reinforcement

**Weaknesses:** Section flow is predictable — follows standard SaaS template ordering without surprise, 3D decorative objects may cause responsive headaches and add page weight, The chatbot.ai project in image 4 shares similar structural DNA suggesting formulaic approach

---

### Score 7/10 — warm-minimal — Personal finance dashboard SaaS with budgeting and cash flow

**Design Recipe:** Use #F5F2F1 warm off-white background, #090909 near-black headlines at 48-56px bold Inter/DM Sans with -0.02em tracking, #545A56 warm gray body at 16px/1.6. Accent everything with #CA3929 terracotta on pill CTAs (border-radius: 999px, 44px height) and chart highlights. Cards are pure white with 16px radius, 24px padding, and box-shadow: 0 4px 24px rgba(0,0,0,0.05). Add radial-gradient peach glows (#E5B6AE at 30% opacity) behind hero and key sections. Section spacing 100px, 12-col grid at 1200px max-width. Feature cards in 2x2 grid, workflow steps in 3-col with numbered badges.

**Dev Recipe:** Next.js + Tailwind CSS with custom warm color tokens, Framer Motion for scroll-triggered section reveals and card hover lifts. Build the dashboard mockup as a static component with CSS Grid for stat cards and use Recharts or Chart.js for the embedded visualizations with the terracotta color scheme.

**Core Lesson:** A single warm accent color (#CA3929 terracotta) applied consistently across CTAs, data visualizations, and decorative glows can unify an entire fintech landing page and differentiate it from the blue-dominated competition.

**Steal These:**
- Warm terracotta accent in fintech instead of default blue — instant differentiation
- Avatar stack + star rating + member count as compact social proof badge above headline
- Full-fidelity dashboard mockup as hero visual instead of abstract illustrations
- Radial peach glow behind key sections for warmth without clutter
- Numbered step cards (01, 02, 03) with coral accent numbers for workflow explanation

**Weaknesses:** Section structure is very standard SaaS template — hero, logos, features, why-us, steps, testimonials, CTA — no surprising layout moments, The dashboard mockup, while detailed, is static and could benefit from subtle animation to feel alive, Body text color (#545A56) could be slightly darker for better accessibility on the warm background

---

### Score 5/10 — dark-luxury — Forex/CFD online trading brokerage

**Design Recipe:** Use TT Firs Neue (or Outfit/Inter as free alt) bold italic at 56px white on near-black #0E0304 hero with subtle grid overlay in #561113. Accent everything actionable in #E51938 red pills. Transition from dark hero to #F4F4FC light section using overlapping cards with 16px radius, white bg, subtle shadow. Ticker bar sits at hero bottom with dark semi-transparent bg. Feature cards in 3-col grid with mixed content types (promo gradient card, image card, device mockup card). Brand logos on dotted world map SVG.

**Dev Recipe:** Next.js + Tailwind CSS with Swiper.js for hero carousel, custom marquee component for ticker (CSS animation or GSAP), countdown timer via useEffect/setInterval. Self-host TT Firs Neue via @font-face, use CSS custom properties for the red/dark palette.

**Core Lesson:** A strong typographic hero treatment can carry a design even when imagery is generic — invest in headline styling over stock photos.

**Steal These:**
- Bold italic headline on dark cinematic hero — instant energy
- Ticker bar overlapping hero-to-content transition zone
- Red gradient promo card with countdown creating urgency within card grid
- Mixed card types in same row (promo, editorial, product) for visual variety
- Warm-tinted blacks (#0E0304) instead of pure black for premium dark themes

**Weaknesses:** Placeholder/identical ticker data destroys trust — use realistic varied values, Stock imagery (runner, car, businessman) is forex-broker-template-tier — custom photography or 3D would differentiate, Body text too small and low-contrast in card descriptions — bump to 16px minimum

---

### Score 5/10 — minimal-corporate — Venture capital investment firm for Latin American startups

**Design Recipe:** Use #0E2156 deep navy for dark sections and #F2F5FE cool white for light sections. Pair Playfair Display (bold, -0.5px tracking) for headlines with Inter (400/500, 16px, 1.6 line-height) for body. 12-col grid at 1200px max-width, 80px section padding. Pill buttons at 44px height with #1E3989 fill. Cards at 12px radius with 24px padding and subtle 4px shadow. Uppercase 12px tracked labels above every section heading. Alternate light/dark section backgrounds for rhythm.

**Dev Recipe:** Next.js + Tailwind CSS with Google Fonts (Playfair Display + Inter). Use Swiper.js for testimonial carousel, native details element for FAQ accordion, and Framer Motion for scroll-triggered fade-ins. Simple responsive grid with Tailwind breakpoints.

**Core Lesson:** Corporate trust requires more than just navy blue — differentiation within the finance aesthetic demands at least one unexpected brand element

**Steal These:**
- Numbered step cards for process visualization — clean 2x2 grid with colored index badges
- Uppercase tracked section labels as pre-headings for wayfinding
- Alternating light/dark section backgrounds to create visual rhythm
- Testimonial cards with integrated video play button and star ratings
- Pill-shaped CTA with arrow icon for directional affordance

**Weaknesses:** Zero brand differentiation — could be any of 10,000 finance sites; needs a unique color accent or visual motif, Generic stock-style illustration adds no brand value — custom photography or branded 3D would elevate significantly, The companion designs (IG, OpenRouter, Litecoin) show range but also suggest surface-level exploration rather than deep craft on any single project

---

### Score 5/10 — minimal-corporate — BNPL installment payments app for Latin American market

**Design Recipe:** Use deep forest green #05471B as primary brand with emerald #0FA958 gradient for hero. White #FFFFFF cards on #F9FAF9 background. Single sans-serif font (Inter/Satoshi) at 48px bold hero, 36px bold section heads, 15px regular body. 12-col grid at 1100px max-width. Hero: left-aligned white text on green gradient, right side lifestyle photo with transparent background. Floating white download bar with 16px border-radius overlapping hero bottom by ~40px. 3-column feature cards in a rounded container with 32px padding, 16px radius, light gray fill.

**Dev Recipe:** Next.js + Tailwind CSS with custom color tokens for the green palette. Key techniques: CSS Grid for feature cards, negative translate-y for the floating download bar overlap, linear-gradient background on hero section, and object-fit cover with transparent PNG for the lifestyle photo composite.

**Core Lesson:** Brand photography with color-coordinated wardrobe instantly elevates even a template layout — invest in imagery before fancy UI.

**Steal These:**
- Color-coordinated model wardrobe matching brand palette
- Floating app-download bar bridging hero and content sections
- Pill-shaped nav links creating soft, approachable navigation
- QR code + app store badges dual download pattern
- Rounded outer page container creating a card-like viewport feel

**Weaknesses:** Zero visual differentiation from Klarna/Afterpay — no brand personality beyond green, Feature section is the most generic 3-column icon-title-description pattern possible, No CTA button in the hero — massive conversion miss for a BNPL product

---

### Score 4/10 — minimal-corporate — Buy now pay later installment payments for emerging markets

**Design Recipe:** Use #0D6B4B deep green as hero bg with lifestyle photography composited right, white headline in geometric bold sans at 48px. Body sections on #FBFBFB with #F5F5F5 cards at 16px radius. Feature trio in 3-col grid with 24px green line icons. Accordion pattern for product features with image panel right. FAQ section with single-open accordions separated by 1px #E5E5E5 borders. Dark green #1A3D2E banner sections for CTAs.

**Dev Recipe:** Next.js with Tailwind CSS, custom accordion component with useState toggle, sticky nav with scroll listener for bg change. Hero needs object-fit:cover on photo with absolute positioning for text overlay.

**Core Lesson:** Cloning a successful product teaches layout patterns but contributes nothing to a portfolio — always add your own design POV

**Steal These:**
- App download bar with QR code + store badges as persistent conversion element
- Accordion + image panel pattern for multi-product feature showcase
- Country flag selector in nav for multi-market fintech
- Feature trio with icon-top cards as trust-building section
- Dark-bg CTA banner breaking up white sections for rhythm

**Weaknesses:** Blatant Tabby.ai clone with no original design contribution — 'Labby' name is embarrassing, Body copy still references 'Tabby' — sloppy find-and-replace execution, No secondary accent color creates visual monotony — everything is green or gray, Stock photography feels generic — no brand-specific illustration or visual system

---

### Score 3/10 — minimal-corporate — Tax planning advisory landing page

**Design Recipe:** Use #3B5998 steel-blue full-bleed background with a white rounded card (border-radius:16px, padding:60px 80px, max-width:1200px) centered on page. Set headline in Montserrat Black 64px uppercase #1B2A4A with tight letter-spacing:-2px. Place a solid #E8A838 CTA button (padding:16px 40px, border-radius:4px, font:18px uppercase white). Right column holds a flat-style SVG illustration at ~500px wide. Nav is right-aligned uppercase 16px bold with 40px gaps.

**Dev Recipe:** Static HTML/CSS or Next.js single page with Tailwind. Flexbox 2-col hero, SVG illustration as img, Google Fonts Montserrat. No libraries needed — pure CSS handles everything here.

**Core Lesson:** A stock illustration cannot substitute for actual design — the illustration IS the design here, and everything else is filler.

**Steal These:**
- White card floating on colored background creates instant depth with zero effort
- Navy+gold palette reliably signals financial trust
- Uppercase black-weight headline demands attention immediately
- Constraining content to a card creates natural visual boundaries
- Gold accent reserved exclusively for actionable/monetary elements

**Weaknesses:** No body copy, subheadline, or supporting content — headline alone doesn't convert, Stock illustration is generic and used on thousands of competing sites, Fourth screenshot is unrelated — project lacks coherence and narrative

---

## Slop Patterns to Avoid

### Score 5/10
- Stock photo runner with motion blur feels generic and overused in forex marketing
- Red sports car hero image is a cliché wealth/speed metaphor in forex
- Promo code card with countdown timer is a dark-pattern conversion tactic
- Ticker bar uses placeholder data (4492.31 repeated identically across all pairs)
- Typography hierarchy in hero is decent with italic serif creating distinction

### Score 3/10
- Stock vector illustration used as hero — zero custom art
- Generic nav labels: HOME, ABOUT, INFO, CONTACT
- Fourth screenshot is completely unrelated Google SGE illustration — incoherent project
- No real content, body copy, or value proposition beyond headline
- Color palette is the default navy+gold stock illustration palette, not a deliberate brand choice

### Score 5/10
- Generic illustration style seen on hundreds of Dribbble shots — stock-like flat character art
- Color palette is safe navy-blue-corporate with zero brand distinction
- Layout follows exact template pattern: hero → about → process → testimonials → logos → FAQ → footer
- The companion screenshots (IG trading, OpenRouter, Litecoin) suggest this is a multi-project portfolio dump, not deep single-project work
- Typography hierarchy is competent but unremarkable — no custom type treatment

### Score 5/10
- Generic 3-column feature cards with stock icon treatment
- Hero is a standard left-text/right-photo split with no creative tension
- App download bar is a cookie-cutter pattern with no brand personality
- Typography hierarchy is competent but unremarkable — no custom type treatment
- Color palette is safe single-green with no secondary accent exploration

### Score 4/10
- Near-identical clone of Tabby.ai — layout, sections, accordion pattern, hero composition all match
- Brand name 'Labby' is literally 'Tabby' with one letter changed
- Copy references 'Tabby' directly in body text — lazy find-and-replace missed
- Generic stock photography with no unique brand illustration system
- Color palette and section ordering directly lifted from source
