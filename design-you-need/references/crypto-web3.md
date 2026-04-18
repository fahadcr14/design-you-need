# Crypto Web3 — Design Playbook

**17 projects analyzed | 12 scored 7+ | Avg: 6.6/10**

## Category Overview

**Aesthetics that work:** dark-luxury (9), dimensional-layered (4), playful-startup (1), warm-minimal (1), minimal-corporate (1)
**Color strategy:** dark-theme (9), neutral-plus-accent (6), analogous (1), monochromatic (1)
**Color mode:** dark (9), light (6), mixed (2)
**Hero patterns:** centered (8), left-right (6), layered (2), full-bleed (1)
**Frameworks:** Next.js (6), Next.js or React (2), React (1), Next.js or Nuxt (1)
**Animation:** Framer-Motion (10), GSAP (2), CSS-only (1)
**Heading fonts:** Inter or SF Pro Display (3), Custom serif (2), Custom display serif (1), Custom condensed grotesque (1)
**Body fonts:** Inter (5), Inter or DM Sans (3), Inter or similar geometric sans-serif (2), Sans-serif (1)

## Color Rules

- **[8]** Gold reserved for headlines, numbering, and interactive elements only — never backgrounds
- **[8]** Gold used only on CTA and coin glow — max 5% surface area
- **[8]** Blue accent used sparingly in 3D renders and UI elements; page itself stays nearly monochrome
- **[8]** Purple accent reserved for interactive elements, headings, and key UI highlights — maybe 15% of surface area
- **[8]** Orange-red reserved for CTAs, badges, and ambient glows only — never for body text
- **[7]** Blue used for all interactive elements and one major section break; restrained elsewhere
- **[7]** Blue accent reserved for CTAs and interactive card borders only
- **[7]** Teal reserved for interactive elements only; green for decorative atmosphere; gold for monetary values
- **[7]** Teal used sparingly on card bottom gradients, 3D elements, and floating sphere — never overwhelming
- **[7]** Blue accent reserved for CTAs and hero background only; icons get unique colors
- **[7]** Teal reserved strictly for interactive elements and key badges — maybe 5% of surface area
- **[7]** Green used only for interactive/positive states — Buy, active filters, positive %, chart accent. Never decorative fill.

### Color Craft Insights
- **[8]** The olive-green (#334A3A) FAQ panel breaks the monotony of pure black while maintaining the dark palette — prevents visual fatigue across long scrolls
- **[8]** The outer page border gradient mirrors the coin's chromatic aberration — the entire page IS the brand's color system radiating from the product
- **[8]** The palette is intentionally restrained on the page surface to let the 3D renders carry all the color energy — smart separation of information layer vs visual layer
- **[8]** The outer page wrapper uses a desaturated lavender (#C5C0D8) creating a 'device frame' effect that makes the dark UI feel like a premium product floating in space
- **[8]** The warm-tinted neutrals (#D1D3CC, #615D49) prevent the cold sterility typical of dark crypto sites — everything feels heated, volcanic
- **[7]** The blue gradient on the blockchain section acts as a palate cleanser in an otherwise relentlessly dark page — smart pacing
- **[7]** The entire palette is a monochromatic blue-gray ramp — no competing hues — letting the 3D gold/silver coins be the only warm elements, creating natural focal points
- **[7]** The green atmospheric glow is applied as large radial gradients at ~30% opacity, creating depth without competing with game thumbnails — smart restraint for a casino UI
- **[7]** The green-black (#0E1B1A) instead of pure black creates tonal harmony with the teal accent — everything feels like one color family
- **[7]** The sky photograph as hero background is unusual for crypto — it softens the typically cold fintech aesthetic while the white cards floating over it create a cloud/trust metaphor

## Color Palettes

### NFT-gated luxury private dining club Example (dark-theme / dark)
- `#060606` — **bg-primary** — Pure black creates maximum luxury contrast and lets food photography pop
- `#334A3A` — **surface-card** — Dark olive-green evokes fine dining tablecloths and natural sophistication
- `#B4925B` — **accent-cta** — Warm gold signals luxury, exclusivity, and premium membership value
- `#B2ABA5` — **text-secondary** — Warm gray maintains readability without harsh white-on-black contrast
- `#A36132` — **decorative** — Copper-amber bridges gold accents with photography's warm tones
- `#6F7F85` — **text-tertiary** — Cool gray provides hierarchy depth without competing with gold

### DeFi stablecoin protocol landing page Example (neutral-plus-accent / light)
- `#0A0413` — **text-primary** — Near-black with purple undertone ties to crypto/tech identity
- `#130BA8` — **decorative** — Deep blue signals trust and financial stability
- `#EEB630` — **accent-cta** — Gold = value/wealth, creates urgency against cool palette
- `#DCEDF4` — **bg-primary** — Cool off-white feels cleaner than pure white, reduces eye strain
- `#C84C1C` — **decorative** — Orange-red adds energy and draws eye to hero illustration
- `#8078BC` — **decorative** — Muted purple bridges the deep blue and warm tones
- `#DDE1A9` — **decorative** — Lime-yellow adds unexpected freshness to the palette
- `#200A53` — **surface-card** — Dark purple maintains brand while differentiating from pure black

### Smart agent-powered multi-chain crypto wallet with tokenized stock trading Example (neutral-plus-accent / light)
- `#FAFCFD` — **bg-primary** — Near-white with cool tint creates clinical fintech trust
- `#090B0D` — **text-primary** — Near-black provides maximum contrast and authority
- `#3B4254` — **text-secondary** — Softened dark for comfortable reading without harshness
- `#4558A3` — **accent-cta** — Deep blue signals financial trust and security
- `#4EBBEA` — **accent-secondary** — Cyan-blue adds tech-forward energy to 3D renders
- `#9BB8D5` — **decorative** — Muted blue-gray for depth without distraction
- `#9EA1AC` — **text-muted** — Neutral gray for tertiary information hierarchy
- `#A5DAF0` — **decorative** — Light cyan creates ethereal tech atmosphere in renders

### DeFi transaction platform with portfolio analytics Example (monochromatic / dark)
- `#05040B` — **bg-primary** — Near-black creates premium crypto atmosphere and maximizes contrast for data
- `#8670EE` — **accent-cta** — Purple signals innovation and premium positioning in fintech
- `#2D274F` — **surface-card** — Mid-dark purple creates layered depth without breaking dark theme
- `#B1B0D0` — **text-secondary** — Lavender-gray provides readable contrast on dark without harsh white
- `#FFFFFF` — **text-primary** — Maximum contrast for critical information hierarchy
- `#9595B1` — **text-tertiary** — Muted tone for supporting information

### AI crypto portfolio tracker and wallet management Example (dark-theme / dark)
- `#000000` — **bg-primary** — Pure black maximizes contrast and creates premium depth for glowing elements
- `#D5340C` — **accent-cta** — High-energy red-orange signals urgency and action, stands out on black
- `#A61503` — **accent-secondary** — Deeper red creates atmospheric depth without competing with primary CTA
- `#5C0D02` — **decorative** — Dark maroon creates volcanic ambient light effect
- `#D1D3CC` — **text-primary** — Warm off-white is easier on eyes than pure white on dark backgrounds
- `#615D49` — **text-secondary** — Low-contrast warm gray for secondary information hierarchy

### Multi-chain mobile crypto wallet with fiat card Example (dark-theme / dark)
- `#010206` — **bg-primary** — Near-black creates premium fintech feel and makes blue accents pop
- `#1456E2` — **accent-cta** — Trust-signaling blue, standard fintech confidence color
- `#3BB8F5` — **accent-gradient-light** — Lighter blue adds energy and prevents monotone blue palette
- `#F9F9FA` — **text-primary** — Near-white for maximum readability on dark backgrounds
- `#1A2040` — **surface-card** — Elevated dark surface creates depth without breaking dark theme
- `#384D54` — **text-secondary** — Reduced contrast for secondary information hierarchy
- `#0B54B0` — **decorative** — Mid-blue bridges dark bg to bright accent creating depth

### AI-powered omnichain DeFi wallet Example (neutral-plus-accent / light)
- `#FBFCFE` — **bg-primary** — Near-white with cool tint creates clean, trustworthy fintech feel
- `#040506` — **text-primary** — Near-black provides maximum readability without harsh pure black
- `#314457` — **text-secondary** — Desaturated blue-gray softens hierarchy while maintaining legibility
- `#4669A3` — **accent-cta** — Mid-blue conveys trust and financial stability
- `#50A9D3` — **accent-highlight** — Lighter blue adds energy and draws attention to interactive elements
- `#94B6D8` — **decorative** — Muted blue ties 3D renders to the UI color system
- `#1A1D2E` — **bg-footer** — Dark navy grounds the page and creates visual closure

### Crypto casino and sports betting platform Example (dark-theme / dark)
- `#050905` — **bg-primary** — Deep black maximizes contrast for vibrant game thumbnails and green accents
- `#0D1B14` — **surface-card** — Slightly lifted dark green-black creates depth without breaking dark theme
- `#13581D` — **decorative** — Green mid-tone bridges dark bg to bright accents, creates casino-table association
- `#32BEBE` — **accent-cta** — Cyan/teal pops maximally against dark green — high visibility for CTAs
- `#38B435` — **accent-secondary** — Reinforces brand identity through the mascot's magical green energy
- `#F5C842` — **accent-tertiary** — Gold = money/wealth, universal casino signifier
- `#FFFFFF` — **text-primary** — Maximum readability on dark backgrounds
- `#8B7F87` — **text-secondary** — Muted gray for secondary info hierarchy

## Typography

- **[8] Custom serif — likely Cormorant Garamond + Light-weight sans-serif — like**: High-contrast serif headlines evoke editorial luxury while geometric sans body ensures digital readability — classic fine-dining menu pairing
- **[8] Custom condensed grotesque — likely Clas + Inter or DM Sans — geometric s**: Ultra-bold condensed display creates dramatic contrast against lightweight proportional body, classic Web3 hierarchy
- **[8] Inter or SF Pro Display — geometric sans + Inter — humanist sans-serif**: Single font family at different weights creates cohesion; geometric forms match the precision of 3D renders
- **[8] Neue Haas Grotesk — neo-grotesque sans-s + Neue Haas Grotesk — same famil**: Single-family system using weight contrast (Regular/Medium/Semibold) for hierarchy — clean and systematic for data-heavy fintech
- **[8] Clash Display or similar geometric displ + Inter or DM Sans — geometric s**: Display serif headlines create editorial gravitas while clean sans body ensures readability at small sizes
- **[7] Custom display serif-sans hybrid (possib + Inter or similar geometric san**: Decorative display font for brand personality on hero, clean sans for readability everywhere else
- **[7] Inter or SF Pro Display — geometric sans + Inter — humanist sans-serif**: Single font family at different weights creates cohesion; geometric forms match the tech/fintech positioning
- **[7] Inter or Poppins — geometric sans-serif, + Inter — humanist sans-serif**: Single font family at varying weights keeps the dense dashboard readable while bold weights create hierarchy
- **[7] Custom serif — likely Recoleta or simila + Inter or similar geometric san**: Soft serif headline adds warmth and authority while geometric sans body ensures readability — classic editorial contrast
- **[7] Instrument Serif or similar modern serif + Inter or SF Pro — geometric sa**: Serif headlines add editorial gravitas to a crypto product, while sans body keeps UI elements clean and functional

### Typography Effects
- **[8]** FAQ marquee text at ~180px with image overlapping — z-index layering, mix-blend-mode potential
- **[8]** Oversized serif headlines cropped by viewport edges — overflow:hidden on container
- **[8]** Circular radial text 'SCROLL' indicator — CSS transform:rotate with SVG textPath or JS animation
- **[8]** Oversized condensed NEXA wordmark acts as visual anchor — font-weight:900 + letter-spacing:-0.02em
- **[8]** Emoji inline with headlines (🔴 stop sign, 📊 chart) for visual punctuation — standard unicode rendering
- **[8]** Subtle purple-to-white gradient on hero headline — background-clip:text with linear-gradient
- **[8]** Mixed serif/sans in headlines — some words appear in serif while others in sans within same heading, creating editorial rhythm
- **[7]** Hero 'Onyx Finance' uses mixed serif italic + sans-serif letterforms — likely custom SVG or variable font axis manipulation
- **[7]** ABOUT US and PEOPLE TRUST US use all-caps extended tracking display treatment — letter-spacing: 0.1em
- **[7]** Bold keywords in hero description paragraph for selective emphasis

## Hero Patterns

- **[8] full-bleed** (NFT-gated luxury private dining club): Center food image → headline text → EXPLORE CTA → PREV/NEXT navigation
- **[8] left-right** (DeFi stablecoin protocol landing page): 3D coin → NEXA headline → subhead → CTA → stats bottom-right
- **[8] centered** (Smart agent-powered multi-chain crypto wallet with): Headline text → 3D phone mockup center → Visa card detail → tokenized stocks callout below
- **[8] centered** (DeFi transaction platform with portfolio analytics): badge→headline→subhead→CTA button→overlapping cards below→side stats
- **[8] centered** (AI crypto portfolio tracker and wallet management): Badge→Headline→CTA button→Phone mockup→Floating cards
- **[7] centered** (Multi-chain mobile crypto wallet with fiat card): Title → description → CTA button → phone mockup
- **[7] centered** (AI-powered omnichain DeFi wallet): 3D coins center → headline → subtext → CTA buttons
- **[7] left-right** (Crypto casino and sports betting platform): STAY UNTAMED badge → $20,000 headline → Registration CTA → Viking character → Cashback card
- **[7] centered** (Layer-1 blockchain infrastructure platform): headline → subhead → CTAs → 3D sculpture → product cards
- **[7] left-right** (Self-custody crypto wallet with DeFi swap and port): Headline → product UI cards → CTAs → trust badges below

## Card & Component Patterns

- **[8]** n/a — content uses full-width panels and inline sections instead
- **[8]** Light surface cards with 12-16px radius, subtle 1px border (#E8EBF0), 24px padding, soft box-shadow on hover
- **[8]** Glassmorphic dark cards, border-radius: 16-20px, 24px padding, subtle 1px border rgba(255,255,255,0.08), backdrop-filter: blur(20px), layered overlap composition
- **[8]** Dark glass cards, ~12-16px radius, 1px border rgba(255,255,255,0.08), ~24px padding, subtle inner glow on some, bento-grid layout with varied spans
- **[7]** Dark surface #1A2040, ~16px radius, ~32px padding, subtle 1px border with blue-tinted glow, rounded-corner highlight on top-left
- **[7]** Rounded-16px, white surface, light border #E8EDF2, 24px padding, subtle shadow on hover, horizontal scroll layout for feature cards
- **[7]** Game cards: 8px radius, no padding (full-bleed thumbnail), overlay text at bottom with gradient scrim, ~160x200px, hover likely scale(1.05) with glow
- **[7]** 3-column product cards, ~16px radius, ~24-32px padding, light teal-tinted bg with subtle border, bottom gradient edge in teal, active/hover state inverts to dark bg (#0E1B1A) with white text, arrow icon bottom-right
- **[7]** White bg, border-radius:12-16px, 24px padding, subtle box-shadow, no hover lift visible, clean internal layout with dividers
- **[7]** Dark surface (#1A1A1A-#1E1E1E), border-radius: 16px, padding: 24px, subtle 1px border rgba(255,255,255,0.06), no hover lift visible, internal layouts vary per widget type
- **[7]** Dark surface #0D1A15 approx, border-radius 12-16px, 16px padding, subtle 1px border rgba(255,255,255,0.06), no hover effect visible

### Buttons

- **ghost / square**: `border-bottom with transition-width`
- **secondary / pill**: `border: 1px solid with background-color transition`
- **primary / rounded-8**: `background:#EEB630; color:#0A0413; border-radius:8px; font-weight:600`
- **secondary / rounded-8**: `background:#0A0413; color:#fff; border-radius:6px`
- **primary / rounded-8**: `border-radius: 8px; background: #4558A3`
- **ghost / rounded-8**: `border: 1px solid #3B4254`
- **primary / pill**: `border: 1px solid #8670EE; border-radius: 24px`
- **secondary / rounded-8**: `backdrop-filter: blur(12px); background: rgba(134,112,238,0.15)`
- **ghost / pill**: `border: 1px solid rgba(255,255,255,0.2)`
- **cta-circle / circle-64**: `border-radius: 50%; background: #fff; box-shadow: 0 8px 32px rgba(134,112,238,0.3)`
- **primary / pill**: `background: #D5340C; border-radius: 24px`
- **ghost / pill**: `border: 1px solid rgba(255,255,255,0.2); border-radius: 18px`
- **primary / pill**: `border-radius: 28px; background: #1456E2`
- **secondary / pill**: `border: 1px solid #fff; background: transparent; border-radius: 26px`
- **primary / pill**: `border-radius: 24px; background: #4669A3`
- **secondary / pill**: `border: 1.5px solid #314457; background: transparent`
- **primary / rounded-8**: `border: 1px solid #32BEBE; color: #32BEBE`
- **secondary / rounded-8**: `background: #32BEBE; color: #050905`
- **ghost / rounded-8**: `border: 1px solid rgba(255,255,255,0.2)`
- **primary / rounded-8**: `background-color: #0E1B1A; border-radius: 8px; color: white`
- **secondary / rounded-8**: `border: 1px solid #0E1B1A; border-radius: 8px; background: transparent`
- **primary / rounded-8**: `background-color with border-radius:8px`
- **secondary / rounded-8**: `border:1px solid with transparent bg`
- **ghost / rounded-8**: `border:1px solid #ddd`

## Animation & Interaction

- **[8]** Hero slide transitions with PREV/NEXT — GSAP or Swiper.js with custom fade/scale
- **[8]** FAQ accordion expand/collapse with +/- rotation — GSAP or CSS max-height transition
- **[8]** Marquee text infinite horizontal scroll — GSAP ScrollTrigger or CSS keyframe animation
- **[8]** Circular SCROLL indicator rotation — CSS animation: rotate infinite linear
- **[8]** Sidebar FAQ category switch with line indicator slide — CSS transition on ::before pseudo-element
- **[8]** scroll-indicator-bounce → CSS @keyframes or Framer-Motion animate
- **[8]** hero-entrance-stagger → Framer-Motion variants with staggerChildren
- **[8]** stat-counter-animate → useInView + animated number increment
- **[8]** coin-parallax → scroll-driven subtle Y-translate on 3D asset
- **[8]** nav-cta-hover → scale(1.02) + box-shadow transition
- **[8]** scroll-fade — sections fade up on scroll entry → Intersection Observer or Framer Motion
- **[8]** parallax-depth — 3D phone mockup subtle parallax on scroll → GSAP ScrollTrigger
- **[8]** hover-card-lift — feature cards lift with shadow increase → CSS transition
- **[8]** step-reveal — how-it-works steps animate sequentially → staggered Framer Motion
- **[8]** comparison-table-highlight — UNUS column highlighted on scroll into view → CSS + IO
- **[8]** Card hover lift with shadow intensify → Framer-Motion whileHover scale + boxShadow
- **[8]** Circle button hover fill → CSS transition background-color 300ms
- **[8]** Scroll-triggered card entrance → Framer-Motion viewport animation with stagger
- **[8]** Nav arrow carousel slide → Framer-Motion AnimatePresence with slide variants
- **[8]** Stats counter animation → countUp.js or Framer-Motion useMotionValue
- **[8]** scroll-reveal fade-up on sections → Framer-Motion viewport triggers
- **[8]** floating-card parallax in hero → scroll-linked transform
- **[8]** logo-ticker infinite scroll → CSS animation translateX loop
- **[8]** accordion expand/collapse in FAQ → Framer-Motion AnimatePresence
- **[8]** button hover brightness/scale → CSS transition
- **[7]** Crypto ticker horizontal auto-scroll → CSS animation or Framer Motion marquee
- **[7]** Floating crypto coins subtle bob → CSS keyframe translateY loop
- **[7]** Section scroll-reveal fade-up → Framer Motion or Intersection Observer
- **[7]** CTA button hover glow → box-shadow transition on :hover
- **[7]** Card border glow on hover → opacity transition on pseudo-element gradient
- **[7]** scroll-fade-in sections → Framer-Motion + IntersectionObserver
- **[7]** horizontal-card-carousel swipe → CSS scroll-snap or Embla
- **[7]** accordion-faq expand/collapse → Framer-Motion AnimatePresence
- **[7]** nav-blur-on-scroll → backdrop-filter triggered by scroll position
- **[7]** hover-card-lift on feature cards → transform: translateY(-4px) + box-shadow transition
- **[7]** Game card hover scale + glow border — transform:scale(1.05) + box-shadow:0 0 20px rgba(50,190,190,0.3) via CSS transitions
- **[7]** Hero carousel auto-slide — Framer-Motion or Swiper.js with fade/slide transitions
- **[7]** Winner ticker auto-scroll — CSS marquee animation or requestAnimationFrame horizontal translate
- **[7]** Sidebar icon hover tooltip — CSS :hover + ::after pseudo-element or Radix Tooltip
- **[7]** Deposit button pulse — CSS keyframe animation with box-shadow glow
- **[7]** card-hover-invert → dark bg fill with color transition, Framer-Motion or CSS transition
- **[7]** floating-sphere-animation → subtle Y-axis oscillation, CSS @keyframes or Framer-Motion
- **[7]** scroll-fade-in → cards and sections fade up on scroll, IntersectionObserver or Framer-Motion whileInView
- **[7]** nav-dropdown → expand on hover/click with opacity transition
- **[7]** button-hover → subtle scale or background darken, CSS transition
- **[7]** Card entrance on scroll → Framer-Motion or IntersectionObserver fade-up
- **[7]** Tab switching on Buy/Sell → state toggle with transition
- **[7]** Range slider drag → input[type=range] with JS value binding
- **[7]** CTA hover → background-color transition 200ms
- **[7]** Percentage button selection → active state toggle
- **[7]** Scroll-reveal on card sections → Framer Motion or Intersection Observer
- **[7]** CTA hover brightness/scale → CSS transition
- **[7]** Stat counter animation on scroll → countUp with useInView
- **[7]** Nav link hover underline → CSS pseudo-element transition
- **[7]** Card hover subtle border glow → border-color transition to teal at low opacity
- **[7]** Segmented control slide → translateX pill animation, CSS transition or Framer Motion
- **[7]** Time range filter tap → chart data reload with crossfade, native animation
- **[7]** Candlestick hover/tap → price tooltip appears at data point, gesture handler
- **[7]** Bottom tab bar → icon scale + color change on active, spring animation
- **[7]** Case study scroll → likely fade-in-up on sections, Intersection Observer + CSS

## Decorative Elements

- **Semicircular arc** at Hero slides overlaying food imagery: `SVG path or border-radius with clip-path, possibly with backdrop-filter for glass effect`
- **Horizontal marquee** at FAQ section header: `CSS animation translateX infinite loop or GSAP horizontal scroll`
- **Circular radial text** at Bottom-right scroll indicator: `SVG textPath with CSS animation rotate`
- **Ornamental divider** at Between headline and body text: `Pseudo-elements with border and centered circle`
- **Smoke/steam photography** at Hero concept slide: `Photographic — not CSS generated`
- **mesh-gradient-border** at Full page outer border/background: `background: conic-gradient or mesh-gradient with border-image`
- **prismatic-light-leak** at Emanating right from 3D coin: `Baked into 3D render, possibly composited with mix-blend-mode:screen`
- **scroll-pill** at Bottom center: `border-radius:999px; background:#200A53; animation:bounce`
- **film-strip-detail** at Right edge of coin: `Part of 3D asset — adds analog/physical texture`
- **perspective-grid** at Behind phone mockup hero: `CSS perspective transform or 3D-rendered background`
- **ambient-glow** at Around 3D objects: `Baked into 3D render, possibly enhanced with box-shadow/filter:blur`
- **subtle-noise** at Background texture: `background-image SVG noise filter`
- **light-rays** at Top of hero section: `Baked into 3D scene render`
- **radial-glow** at Hero background center: `radial-gradient with purple-to-transparent`
- **glass-cards** at Product showcase overlapping hero bottom: `backdrop-filter: blur(20px); background: rgba(13,12,25,0.7)`
- **outer-frame** at Page wrapper/border: `Lavender background with rounded-corner inner dark container, border-radius: ~24px`
- **circle-nav-buttons** at Left and right of hero: `border-radius: 50%; border: 1px solid rgba(255,255,255,0.15); backdrop-filter: blur(8px)`
- **cosmic-orb** at Transaction modal center: `3D render composited as image, box-shadow glow overlay`
- **radial-glow** at Hero background, feature card backgrounds: `radial-gradient with large spread from #5C0D02 to transparent`
- **ambient-light** at Bottom of hero, card corners: `Pseudo-element with radial-gradient and mix-blend-mode:screen`
- **glass-border** at All cards and sections: `border: 1px solid rgba(255,255,255,0.06)`
- **outer-container-border** at Full page wrapper: `Rounded container with subtle border creating page-within-page effect`
- **noise-texture** at Subtle across dark surfaces: `background-image SVG noise filter at low opacity`
- **gradient-glow** at Hero background center: `radial-gradient or positioned pseudo-element with blur`
- **3D-chain-links** at Between sections, left-aligned: `positioned PNG/WebP with z-index layering`
- **floating-crypto-coins** at Hero flanks (Bitcoin, Ethereum icons): `absolute positioning, possibly CSS animation float`
- **card-border-glow** at About Us feature cards: `border-image or pseudo-element gradient border with border-radius`
- **3d-coin-scene** at hero background, feature cards, pillar sections: `positioned 3D renders as background images or WebGL canvas`
- **reflective-ground-plane** at hero 3D scene: `3D render with planar reflection in Blender/C4D`
- **light-gradient-wash** at section backgrounds: `radial-gradient with low opacity blue`
- **watermark-typography** at footer: `oversized text with low opacity, mix-blend-mode or opacity: 0.05`
- **green-radial-glow** at Top-right corner, hero background, page edges: `radial-gradient with large spread, mix-blend-mode:screen`
- **green-energy-vfx** at Mascot character hands, swirling around game cards: `Composited in illustration, not CSS`
- **star-particles** at Hero banner background: `Background image or canvas particles`
- **glass-border** at Main content container has subtle border glow: `border: 1px solid rgba(50,190,190,0.15); backdrop-filter possible`
- **3d-sculpture** at Hero center below CTAs: `positioned img/canvas with z-index layering`
- **floating-teal-sphere** at Left of 3D sculpture: `absolute positioning, likely CSS animation float`
- **gradient-wash** at Hero background cream-to-teal: `radial-gradient or layered linear-gradients`
- **teal-gradient-edge** at Bottom of product cards: `border-image or pseudo-element with linear-gradient`
- **glass-card-borders** at Product card outlines: `border: 1px solid rgba(58,110,102,0.2)`
- **sky-photo** at Hero right half: `background-image with object-fit:cover, clipped to section`
- **light-blue-tint** at Alternating feature sections: `background-color on section`
- **dark-banner** at NFT section, product showcase strip: `background:#1a1a2e with white text`

## Design Recipes

### Score 8/10 — dark-luxury — NFT-gated luxury private dining club

**Design Recipe:** Use #060606 pure black backgrounds with #334A3A dark olive panels for content sections. Set headlines in a high-contrast didone serif (Cormorant Garamond 400) at 72-96px in #B4925B gold, always uppercase with 0.15em letter-spacing. Body text in geometric sans (Jost 300) at 15px in #B2ABA5. Section numbers in 13px with wide tracking. Create a signature motif — semicircular arc in thin gold stroke — and repeat it across hero slides. Use full-bleed food photography with chiaroscuro lighting. FAQ sections use 30/70 split with sidebar navigation featuring a horizontal line indicator for active state. Accordion items separated by 1px #B2ABA520 borders with thin + icons.

**Dev Recipe:** Next.js with GSAP for marquee scrolling, hero slider transitions, and ScrollTrigger parallax. Use CSS Modules or Sass for scoped styling. SVG for the semicircular arc motif and circular text indicator. Swiper.js for the hero carousel with custom GSAP-powered transitions. Self-host premium serif font, optimize food photography with next/image and blur placeholders.

**Core Lesson:** In dark luxury design, restraint with gold accents and letting exceptional photography breathe creates more impact than decorative excess

**Steal These:**
- Marquee text header with overlapping photography for section intros
- Semicircular arc as a repeating brand motif overlaying hero imagery
- Circular radial 'SCROLL' text indicator as a custom scroll affordance
- Ornamental divider with centered circle between headline and body
- Numbered section indicators (01, 02) in small muted type as editorial pacing device

**Weaknesses:** FAQ sidebar navigation may confuse users — active state line is subtle and categories lack clear visual hierarchy, Gold text on dark olive-green (#B4925B on #334A3A) may fail WCAG AA contrast in some instances, Mobile layout wraps FAQ categories into inline flow which loses the structured sidebar navigation — could use tabs instead

---

### Score 8/10 — dimensional-layered — DeFi stablecoin protocol landing page

**Design Recipe:** Use #DCEDF4 cool off-white content panel inset within a viewport-spanning mesh gradient border cycling through #130BA8 → #C84C1C → #EEB630 → #8078BC. Set headlines in a condensed black-weight grotesque (Clash Display 900) at 72-80px uppercase with -0.02em tracking. Body in Inter 400 at 15px, #0A0413 text. Hero splits 45/55 left-right with text left, oversized 3D asset right that bleeds past container edge via overflow:visible. CTA button is #EEB630 solid fill with #0A0413 text, 48px height, 8px radius. Stats use 32px bold monospace numbers with 13px regular labels. Maintain 80-100px section spacing on 8px grid.

**Dev Recipe:** Next.js + Tailwind + Framer Motion. Pre-render 3D coin in Blender with HDRI lighting and chromatic aberration, export as WebP with alpha. Use conic-gradient on a fixed full-viewport wrapper for the border effect, position the content panel with margin:20px and border-radius:24px. Framer Motion for staggered hero entrance and scroll-triggered stat counters.

**Core Lesson:** A single hero-grade 3D asset with intentional color bleed can unify an entire page's color system and create premium perception

**Steal These:**
- Mesh gradient page border that frames content like a gallery piece
- 3D asset light leak that intentionally breaks its container boundary
- Gold CTA on cool palette — instant visual hierarchy win
- Dark pill scroll indicator with bounce animation — elegant wayfinding
- Film-strip texture detail on 3D coin adding analog warmth to digital asset

**Weaknesses:** 'Lunch App' instead of 'Launch App' — embarrassing typo undermines credibility, Feature section below fold feels generic and underdeveloped compared to hero quality, Body copy uses title case inconsistently ('The Stablecoin For DeFi') — should commit to sentence case or title case

---

### Score 8/10 — dimensional-layered — Smart agent-powered multi-chain crypto wallet with tokenized

**Design Recipe:** Use #FAFCFD background with #090B0D headlines in Inter Bold at 56-64px with -0.02em tracking. Body text in #3B4254 Inter Regular 15px/1.6. Cards: white surface, 12px radius, 1px #E8EBF0 border, 24px padding, box-shadow 0 4px 24px rgba(0,0,0,0.04). Hero: centered text above a 3D phone mockup rendered in Blender with blue (#4EBBEA) accent lighting on a perspective grid. Section spacing 100-120px. Feature icons: 3D metallic gold + glass renders at 64px. Comparison table with brand blue (#4558A3) column highlight. Max-width 1200px, 12-col grid, 24px gutters.

**Dev Recipe:** Next.js + Tailwind CSS + Framer Motion for scroll animations. 3D assets as optimized WebP with srcset for responsive. GSAP ScrollTrigger for parallax phone mockup. Intersection Observer for staggered section reveals. Use next/image for automatic optimization of heavy 3D render PNGs.

**Core Lesson:** Let premium 3D renders do the heavy lifting while keeping the page layout surgically clean — the contrast between rich visuals and minimal structure creates perceived luxury

**Steal These:**
- Perspective grid background behind hero product mockup — adds spatial depth without complexity
- Emoji inline with headlines as visual anchors (🔴📊) — cheap but effective attention markers
- Problem→Solution→How→Comparison narrative flow — textbook conversion architecture
- Unified 3D material language (gold + glass + chrome) across all icons for brand cohesion
- Feature comparison table with highlighted brand column — direct competitive positioning

**Weaknesses:** Heavy reliance on 3D renders means slow load times without aggressive optimization — needs skeleton loading states, Typography is safe/generic — Inter is ubiquitous in Web3; a distinctive display font would add personality, The right-side mobile/scroll view shows cramped text at smaller breakpoints — responsive typography needs work

---

### Score 8/10 — dark-luxury — DeFi transaction platform with portfolio analytics

**Design Recipe:** Start with #05040B background inside a #C5C0D8 lavender outer frame (24px padding, 24px border-radius). Use Neue Haas Grotesk exclusively — semibold 48px for h1 with subtle purple-to-white gradient, regular 16px #B1B0D0 for body. Accent everything with #8670EE at 15% usage. Build hero as centered text with a badge pill above, flanked by stat counters. Below the CTA, overlap 3 glass cards (backdrop-filter: blur(20px), background: rgba(13,12,25,0.7), border: 1px solid rgba(255,255,255,0.08), border-radius: 20px) at staggered depths using translateY and z-index. Add radial purple glow (radial-gradient(circle at 50% 40%, rgba(134,112,238,0.15), transparent 60%)) behind the hero.

**Dev Recipe:** Next.js + Tailwind CSS + Framer-Motion. Self-host Neue Haas Grotesk via @font-face. Use CSS backdrop-filter for all glass effects, Framer-Motion for scroll-triggered card entrances with staggerChildren: 0.15, and CSS custom properties for the purple color scale. The outer frame is a simple wrapper div with bg-lavender padding around the dark inner container.

**Core Lesson:** Depth through layered glass cards at different z-levels creates more visual interest than any single hero image ever could

**Steal These:**
- Lavender outer frame wrapping dark UI — instant premium 'device showcase' feel
- Circular arrow navigation buttons with glass fill flanking hero content
- Three overlapping glass cards at hero bottom creating product depth
- Single-font system (3 weights) for entire crypto platform — clean and systematic
- Stat counters positioned as floating sidebar elements beside centered hero text

**Weaknesses:** Hero headline gradient is subtle to the point of being barely visible — could be more intentional, The Cryptify green variant (image 3) feels like a reskin rather than a distinct design — reduces perceived originality, Mobile app screens (image 4) use a different visual language (solid purples, white cards) that doesn't fully cohere with the glass-dark web design

---

### Score 8/10 — dark-luxury — AI crypto portfolio tracker and wallet management

**Design Recipe:** Start with #000000 background. Use #D5340C for CTAs and badges only. Create depth with radial-gradient(ellipse at center, #5C0D0280 0%, transparent 70%) placed behind key sections. All cards get background rgba(255,255,255,0.03) with border 1px solid rgba(255,255,255,0.06) and border-radius 16px. Typography: mixed serif (Clash Display) and sans (Inter) within headings at 56-64px, body at 16px in #D1D3CC. Wrap entire page in a rounded-corner container (border-radius ~20px) with 1px border to create a contained, premium feel. Bento grid: CSS Grid with auto-fill, mixing 1-col and 2-col span cards.

**Dev Recipe:** Framer for rapid deployment or Next.js + Framer Motion + Tailwind CSS for custom build. Use CSS Grid for bento layouts, radial-gradient pseudo-elements for ambient glows, and intersection-observer-triggered fade-up animations. Self-host Clash Display + Inter fonts.

**Core Lesson:** Ambient colored light on pure black creates more depth and atmosphere than any amount of gradients on gray backgrounds

**Steal These:**
- Volcanic radial glow system — warm dark reds emanating from behind content
- Page-within-page container with rounded border creating premium framing
- Floating UI component cards flanking a centered phone mockup in hero
- Mixed serif/sans words within the same headline for editorial rhythm
- Section label badges with sparkle icon + pill shape as consistent wayfinding

**Weaknesses:** Feature section screenshots look like generic Webflow/Figma UI — not clearly Cryonix product screens, Some floating cards in hero may cause responsive layout headaches on tablets, Color palette is essentially two-tone (black + orange-red) which limits visual variety in longer pages

---

### Score 7/10 — dark-luxury — Multi-chain mobile crypto wallet with fiat card

**Design Recipe:** Use #010206 near-black background with #1A2040 card surfaces. Primary accent #1456E2 for CTAs, secondary lighter blue #3BB8F5 for gradients. Hero: centered layout, 80-96px display font mixing serif italics with geometric sans (try Clash Display), phone mockup below CTA. Cards: 16px radius, 1px gradient border (#1456E2→transparent), 32px padding. Break monotony with one full-width #3BB8F5 gradient section. Section spacing 100-120px. Pill buttons 56px height with full border-radius.

**Dev Recipe:** Next.js + Tailwind CSS with custom color tokens. Use Framer Motion for scroll reveals and floating coin animations. Gradient card borders via pseudo-element technique (::before with gradient bg, slightly larger than card, masked by card's own bg). Marquee ticker with CSS animation or react-fast-marquee.

**Core Lesson:** In dark-theme designs, one bold contrasting color section (the blue blockchain grid) prevents visual fatigue and creates memorable rhythm.

**Steal These:**
- Mixed serif-italic + sans-serif hero headline for brand distinctiveness
- Full-width bright blue section as dark-theme palate cleanser
- Gradient border glow on dark cards for premium feel without heavy shadows
- 3D rendered chain links as thematic decorative elements between sections
- Horizontal crypto logo ticker strip for social proof of supported chains

**Weaknesses:** About Us asymmetric card layout (1 right + 2 below) feels unbalanced — a 3-column grid would be cleaner, Hero description text is too small relative to the massive headline — hierarchy jump is too steep, 3D chain assets feel disconnected from the flat UI — style mismatch between rendered 3D and clean 2D interface

---

### Score 7/10 — dimensional-layered — AI-powered omnichain DeFi wallet

**Design Recipe:** Use #FBFCFE background with #040506 headings in Inter Bold 48px tight-tracked, body in #314457 Inter Regular 16px. Cards are white with 16px radius, 1px #E8EDF2 border, 24px padding. CTAs are pill-shaped 44px height — primary filled #4669A3, secondary outlined. Hero is centered text over a 3D scene of metallic coins on a reflective plane with cool ambient lighting. Section spacing 64-80px. Footer flips to #1A1D2E dark with 4-column links and oversized watermark letters at 5% opacity. Accent blue (#50A9D3) appears only on interactive borders and active states.

**Dev Recipe:** Next.js 14 + Tailwind CSS + Framer Motion for scroll animations. 3D assets either as optimized static images with subtle CSS parallax, or Spline embeds for hero only. Use Embla Carousel for horizontal feature scroll, and a custom accordion with AnimatePresence for FAQ.

**Core Lesson:** In crypto/fintech, restraint in color (monochromatic cool palette) paired with one premium visual element (3D metallic renders) creates more trust than flashy gradients and neon

**Steal These:**
- Monochromatic blue-gray palette letting 3D gold coins be the only warm accent
- Reflective ground plane in hero 3D scene creating depth without complexity
- Dark footer with oversized watermark brand letters as decorative element
- Horizontal scrolling feature cards with product mockup + description pairs
- Dual CTA pattern: outline 'Launch app' + filled 'Learn more' creating clear hierarchy

**Weaknesses:** Hero headline 'Your DeFi, Supercharged' is generic crypto copywriting — needs differentiation, 3-column pillar section with floating coins is visually heavy and may cause layout shift on slower connections, FAQ section feels templated and disconnected from the premium 3D aesthetic above it

---

### Score 7/10 — dark-luxury — Crypto casino and sports betting platform

**Design Recipe:** Start with #050905 pure dark background. Build content panels on #0D1B14 with 1px borders at rgba(50,190,190,0.1). Apply large radial-gradient glows using #13581D at 30-40% opacity in corners. Use #32BEBE exclusively for CTAs and interactive elements. Use #F5C842 for monetary values. Set game cards in a 6-column grid at 8px radius with full-bleed thumbnails and bottom gradient-scrim text overlays. Left sidebar as 60px icon rail. Hero section splits 60/40 with bold uppercase headline at 36px and character illustration bleeding right.

**Dev Recipe:** Next.js 14 + Tailwind CSS + Framer Motion. Use CSS custom properties for the green glow theme. Swiper.js for hero carousel, WebSocket for live winner ticker, CSS Grid for responsive game layouts with aspect-ratio:3/4 on cards.

**Core Lesson:** A single branded character/mascot with a consistent color story (green energy + gold accents) can transform a generic dark dashboard into a memorable product identity.

**Steal These:**
- Winner ticker strip with game icon + avatar + payout amount as social proof
- Green atmospheric radial glows creating volumetric depth on dark backgrounds
- Icon-only sidebar rail that maximizes content area while keeping navigation accessible
- Game card overlay typography with gradient scrim + provider label hierarchy
- Branded mascot character composited over UI as presentation device

**Weaknesses:** Including an unrelated Nexa blockchain project in the same case study dilutes the narrative, All winner amounts showing identical $1520.00 reveals placeholder data — hurts credibility, Typography is functional but generic — no display font personality for the brand name or section headers

---

### Score 7/10 — warm-minimal — Layer-1 blockchain infrastructure platform

**Design Recipe:** Use #F5F3EF warm cream background with #0E1B1A green-black text. Pair a soft display serif (Recoleta/Fraunces at 64-72px bold) with Inter 16px regular body. Accent sparingly with #3A6E66 teal on card bottom-edge gradients and decorative 3D elements. Cards: light teal-tinted (#ACCECB at 10% opacity) backgrounds, 16px radius, 1px subtle border, with a dark-invert hover state. Center-aligned hero with generous 80-100px vertical spacing. Max-width body text at ~600px.

**Dev Recipe:** Next.js + Tailwind CSS with custom color tokens for the warm-teal palette. Use Framer-Motion for card hover state transitions (background/color interpolation), floating sphere keyframes, and scroll-triggered fade-ins. Self-host the serif font, integrate 3D as optimized WebP/AVIF with absolute positioning and negative margins for section overlap.

**Core Lesson:** Warm neutrals + institutional serif typography can make crypto/Web3 feel trustworthy and premium instead of speculative and hype-driven

**Steal These:**
- Warm cream background instead of white for crypto — instant trust upgrade
- Dark card invert on hover/active state — elegant interaction pattern
- Teal gradient bottom-edge on cards — subtle brand reinforcement without overwhelming
- 3D sculpture with marble + gold materials — bridges finance and tech aesthetics
- Green-tinted black (#0E1B1A) instead of pure black — tonal harmony with accent

**Weaknesses:** Only hero + cards visible — needs more sections for a complete landing page (stats, partners, testimonials), Card text for 'Core' appears truncated/poorly formatted compared to siblings — inconsistent content treatment, The 3D illustration, while beautiful, may cause performance issues and is hard to make responsive without awkward cropping

---

### Score 7/10 — minimal-corporate — Self-custody crypto wallet with DeFi swap and portfolio anal

**Design Recipe:** Use #FFFFFF base with #070708 text. Hero: serif headlines (Instrument Serif, 64-72px, regular weight) left-aligned on left half, sky-blue photograph (#40A6D5 tones) on right half with 2-3 white product UI cards (border-radius:16px, box-shadow:0 8px 32px rgba(0,0,0,0.1)) overlapping at different z-levels. Section spacing 100-120px. Feature sections alternate between white and #F7FAFC backgrounds, using 2-column layouts with text left + UI mockup right (then reversed). Dark (#1A1A2E) accent sections for variety. CTAs: #070708 solid fill, 8px radius, 44px height. Body text in Inter 16px/#39404D. Overline labels in 12px uppercase with 2px letter-spacing.

**Dev Recipe:** Next.js + Tailwind CSS with custom serif font via next/font. Use Framer Motion for scroll-triggered card entrances. Hero requires CSS Grid with overlapping positioned children; product UI cards are static components with absolute positioning inside a relative container clipped with overflow-hidden.

**Core Lesson:** Embedding real product UI as hero visuals builds more credibility than abstract illustrations — show the actual interface to sell trust.

**Steal These:**
- Serif headlines in a crypto/fintech context — instant editorial authority
- Sky photograph as hero background instead of typical dark gradients
- Floating overlapping product UI cards as social proof of real functionality
- Italic serif for mid-page section headlines as pacing change
- Stats bar with large numbers + small labels for credibility anchoring

**Weaknesses:** Feature section layout becomes repetitive — text+card, text+card pattern needs more variation, The sky photo feels slightly disconnected from crypto brand narrative — could be more intentional, Mobile responsive stacking likely loses the overlapping card depth effect entirely

---

### Score 7/10 — dark-luxury — Web3 team finance dashboard with budgeting and payment track

**Design Recipe:** Background #020202, card surfaces #141414 with 1px border rgba(255,255,255,0.06) and 16px radius. Accent #03CE98 ONLY on primary CTAs, badges, and stat numbers — never on large areas. Inter font: h1 at 52px/bold, body at 15px/regular in #98A4A3, headings in #F6F6F6. 100px section spacing, 1200px max-width, 24px gutters. Hero: centered text with floating product widget cards arranged in a loose 3-4 column bento below. Add a faint radial teal glow (5% opacity, 600px radius) behind the hero headline.

**Dev Recipe:** Next.js + Tailwind with custom dark theme tokens. Framer Motion for scroll-triggered card reveals and stat counters. CSS Grid for the bento widget layout with responsive reflow. Use CSS custom properties for the teal accent to enable easy theming.

**Core Lesson:** A single neon accent on near-black creates instant premium fintech feel — but only if you restrict it to <5% of surface area

**Steal These:**
- Floating dashboard widget cards as hero social proof instead of a single screenshot
- Teal accent restricted to interactive elements only — extreme discipline
- Promo banner above nav for urgency without cluttering hero
- Payment list with real app icons (Slack, Figma) for instant relatability
- Earnings card with dollar amount as a trust/value signal

**Weaknesses:** Stats section (110+, 30+, 48+) is generic SaaS template filler — needs more specific proof, Hero subtext is small and low-contrast, may get skipped entirely, Widget card arrangement could feel chaotic on tablet breakpoints without careful responsive work

---

### Score 7/10 — dark-luxury — Mobile crypto wallet and exchange app with candlestick chart

**Design Recipe:** Start with #030505 pure dark background. Use #0AA567 teal-green ONLY for CTAs, active states, and positive values. Create card surfaces at #0D1A15 with 1px borders at rgba(255,255,255,0.06) and 12-16px border-radius. Set typography in Inter or SF Pro: prices at 28px bold white, section headers at 20px semibold, labels at 12px medium in #0AA567 or #8A8F98. Use 16px base spacing unit. Segmented controls get a sliding pill with #174838 active background. Candlestick charts use #0AA567 for bullish, #B83111 for bearish candles.

**Dev Recipe:** React Native with react-native-svg for charts (or lightweight-charts for web). Tailwind with custom dark theme tokens for the case study site. Key: use CSS custom properties for the 3-tier dark palette (bg → surface → elevated) and a single --accent-green variable that drives all interactive color.

**Core Lesson:** In dark financial UIs, a single accent color (#0AA567 green) used exclusively for interactive and positive-state elements creates instant visual hierarchy without any additional decoration.

**Steal These:**
- Green accent used ONLY for interactive/positive states — zero decorative green
- Three-tier dark surface system: #030505 → #0D1A15 → #174838 for depth
- Cinematic gloved-hand mockup photography for premium product presentation
- Ruler/measurement-style divider pattern in case study metadata section
- Price tooltip as floating pill badge anchored to chart data point

**Weaknesses:** Y-axis labels all show identical '88040.71' values — obvious placeholder data undermines credibility, Case study page large watermark logo behind content adds visual noise without purpose, Design follows crypto app conventions too closely — could differentiate more from Coinbase/Trust Wallet patterns

---

### Score 6/10 — dark-luxury — Crypto trading dashboard with swap/exchange and portfolio an

**Design Recipe:** Use #040915 base with #1C2F54 card surfaces and 1px rgba(255,255,255,0.06) borders. Single accent: #9CFC01 neon green for CTAs and positive values only. Inter font at 14px body / 36px display numbers / 12px captions. 12-col grid at 1200px max-width, 60/40 main-sidebar split. Cards: 12px radius, 24px padding, backdrop-filter: blur(16px). Red #EA3123 for negative values. All secondary text in #A4A0AB. 8px base spacing unit.

**Dev Recipe:** Next.js + Tailwind CSS with CSS custom properties for dark theme tokens. Use lightweight-charts for TradingView-style candlesticks, Radix UI for dropdowns/popovers, Framer Motion for swap toggle and tab transitions. Key CSS: backdrop-filter blur on cards, box-shadow glow on accent buttons, font-variant-numeric: tabular-nums for financial figures.

**Core Lesson:** A single high-contrast neon accent color on a deep dark canvas can carry an entire financial UI's visual identity — but only if every other element stays neutral.

**Steal These:**
- Neon green (#9CFC01) on near-black — instant fintech premium feel
- Swap widget layout with inline max-balance and currency dropdown
- Ticker strip with pair icons and colored price change indicators
- Time interval pills with active state highlight circle
- Layered card hierarchy using only opacity differences on same hue

**Weaknesses:** Placeholder/repeated data (0.3191 everywhere) destroys credibility — always use realistic mock data, Mixing unrelated products (crypto + HR) in one case study signals portfolio padding, not depth, Generic 3D coin renders add no information — replace with actual token logos or data visualizations

---

### Score 5/10 — dark-luxury — Crypto trading app and exchange platform UI collection

**Design Recipe:** Dark trading app: Use #0A0A0A background with #1A1A1A card surfaces, 1px #222 borders, SF Pro Display at 36px bold for balance display, 14px regular for asset names. Green #00C853 for gains, red #FF1744 for losses — never decorative, only semantic. Tab bar with 12px pill indicators. Asset rows: 72px height, 16px horizontal padding, logo left (32px circle), name + % stacked, prices right-aligned in monospace. Sparkline chart as thin 2px SVG stroke with orange-to-yellow gradient. Wrap everything in a realistic iPhone mockup shot in low-key lighting for portfolio presentation.

**Dev Recipe:** React Native with react-native-svg for sparklines, styled-components with a dark theme object. Landing pages in Next.js + Tailwind with framer-motion for scroll animations. Use recharts or lightweight-charts for trading data visualization.

**Core Lesson:** Moody mockup photography can elevate mediocre UI, but repeated placeholder data instantly destroys credibility — always populate with realistic, varied content.

**Steal These:**
- Semantic-only color usage — green/red exclusively for financial indicators
- Low-key photography mockup presentation style for portfolio pieces
- Compact asset row layout with logo + name + % change + bid/ask prices
- Tab bar with icon + label for market category filtering
- Monospace font for price data to maintain column alignment

**Weaknesses:** Identical placeholder data across all asset rows destroys believability, Four completely unrelated projects shown together with no design system cohesion, ZenCall serif typography clashes with the fintech dark-mode identity of other screens, Byte Exchange 3D rocket is a generic stock asset that adds no brand value

---

### Score 5/10 — dimensional-layered — Crypto cashback rewards and trading platform ecosystem

**Design Recipe:** Use #040507 dark base with cyan #00D4FF accent for trading screens; #F5F0FA lavender-white with #5233D8 purple accent for consumer crypto. Headlines in Clash Display 700 at 64-80px with -0.02em tracking. Pill buttons at 48px height with 24px border-radius. 80-120px section spacing. Add one serif-italic accent word in purple per hero. Present in 3D perspective mockups using 15° Y-rotation and 10° X-rotation on a crumpled paper or solid mint background.

**Dev Recipe:** Build in Next.js with Tailwind CSS and GSAP ScrollTrigger for 3D parallax mockup presentation. Use CSS perspective transforms for the tilted screen effect, backdrop-filter for glass elements, and radial-gradient layering for ambient glow effects on the dark theme.

**Core Lesson:** Presentation packaging (3D mockups, layered depth) can elevate average designs but cannot substitute for a unified design system and original thinking

**Steal These:**
- Single italic-serif accent word in contrasting color within sans-serif headline
- 3D perspective tilted mockup presentation with overlapping screens
- Stat counters with + prefix and colored numbers below hero
- Vertical rotated scroll indicator text as navigation hint
- Dual-tone CTA: icon circle + text label in pill button

**Weaknesses:** Four disconnected design systems presented as one project — no brand cohesion, Stock 3D rocket illustration screams template; custom illustration would differentiate, ZenCall monospace typography choice fights readability for style points

---

### Score 4/10 — playful-startup — Meme coin token launch landing page

**Design Recipe:** Use #FFEFB4 warm cream background with #3D5A80 steel-blue display serif headlines at 72px black weight. Dark nav bar at #4A5568 with rounded-12 container, 60px height. Orange gradient CTA (#E89B0F to #D4880A) at 44px height, rounded-8. Place 3D mascot right-side at ~500px wide, overlapping into a hand-illustrated border scene that covers the bottom 35% of viewport. Outer page background #4A5568 slate with floating decorative elements (bubbles, seaweed) creating a window-into-world effect.

**Dev Recipe:** Next.js + Tailwind + wagmi for wallet connection. Layer coral reef PNGs with absolute positioning and z-index stacking. Use CSS keyframe animations for floating bubbles. Key challenge is responsive image layering — use srcset and clamp() for fluid sizing.

**Core Lesson:** Thematic illustration borders can create immersive worlds, but only if every element (type, color, mascot) is crafted to the same quality level

**Steal These:**
- Illustrated border that bleeds off-screen creating an immersive world frame
- Dark nav bar floating over light content as a grounding anchor
- Warm cream background instead of typical dark crypto aesthetic — feels friendlier
- 3D mascot overlapping the illustration layer for depth
- Outer background color creating a viewport-within-viewport framing effect

**Weaknesses:** Typo in primary CTA destroys credibility — 'Bay' instead of 'Buy', Only hero section visible — no tokenomics, roadmap, or trust-building content, Subhead text too small and low-contrast — fails accessibility

---

### Score 4/10 — tech-futuristic — Meme coin presale with gamified NFT marketplace

**Design Recipe:** Start with #020408 deep black background. Use #1B2646 navy for card surfaces with 1px #079EA0 teal borders and box-shadow: 0 0 12px rgba(7,158,160,0.35) for glow. Headlines in #FDFBFC near-white with text-shadow: 0 0 20px rgba(45,192,196,0.5). Body text in #A7DBE4 desaturated teal at 14-16px. Pill buttons with #079EA0 solid fill, 24px border-radius, 44px height. Use a decorative serif/script for brand name, geometric sans (Poppins/Inter) for everything else. Section spacing 80-100px, card padding 24px, 12px border-radius on cards.

**Dev Recipe:** React/Next.js with Tailwind CSS, ethers.js or wagmi for wallet connect, Swiper for carousels, CountUp.js for stat animations. Key CSS: extensive use of box-shadow with teal rgba values, backdrop-filter:blur(10px) on card overlays, layered background-images with gradient overlays for hero sections.

**Core Lesson:** A single accent color on dark backgrounds creates instant mood but becomes monotonous without a secondary accent or tonal variation

**Steal These:**
- Teal glow border system on dark cards — simple but effective depth cue
- Stats bar with large numbers in bordered containers as trust signals
- Fantasy/illustrated hero background with gradient fade to content
- Minting progress cards with numbered steps as visual roadmap
- Community section with social icon row as clear engagement CTA

**Weaknesses:** Lorem ipsum throughout — signals unfinished concept work, not production design, One-note visual system — teal glow on everything creates visual fatigue, Analytics dashboard inclusion is portfolio padding — completely different product/audience

---

## Slop Patterns to Avoid

### Score 4/10
- Typo in CTA: 'Bay $Crab' instead of 'Buy $Crab'
- 3D crab mascot is stock/AI-generated — generic Blender-style render
- Underwater scene is a flat illustration pasted behind with no parallax or depth integration
- Nav items have inconsistent spacing and generic font choices
- Social icons (X, Telegram) are tiny afterthoughts with no hover states visible

### Score 5/10
- Placeholder data repeated identically across asset rows (1960.68/1960.95 for Apple, Gold, Netflix)
- ZenCall page feels like a completely different project jammed in — no cohesion
- Byte Exchange uses generic 3D rocket illustration — stock asset
- Equinox landing page has inconsistent spacing and cramped feature cards
- Mockup photography is polished but masks shallow UI detail

### Score 6/10
- Mixed unrelated products (crypto + HR app) in one case study — portfolio padding
- Placeholder data everywhere: 0.3191 repeated across all pairs, identical market values
- Generic 3D renders (green coins) feel stock/AI-generated
- HR mobile screens have zero connection to crypto product — filler screens
- Candlestick chart is decorative, not data-accurate (volume bars missing, axis inconsistent)

### Score 5/10
- Generic 3D rocket illustration is stock/template territory
- Inconsistent design language across the 4 screens — feels like separate projects bundled
- Bitago hero typography mixing serif italic 'Cashback' with sans feels unresolved
- ZenCall has nicer restraint but the crumpled paper mockup presentation is a Dribbble cliché
- Equinox dark trading dashboard is competent but extremely derivative of every crypto landing page

### Score 4/10
- Lorem ipsum placeholder text visible in multiple screens
- Inconsistent typography hierarchy across sections
- Generic 3D mascot characters (AI-generated Monzter blobs)
- Teal glow borders on every card — one-trick visual system
- Dashboard screen (analytics) is completely unrelated to crypto theme — portfolio padding
