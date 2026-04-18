# Real Estate — Design Playbook

**18 projects analyzed | 13 scored 7+ | Avg: 6.9/10**

## Category Overview

**Aesthetics that work:** warm-minimal (7), minimal-corporate (4), dark-luxury (4), glassmorphism (1), organic-natural (1)
**Color strategy:** neutral-plus-accent (16), monochromatic (2)
**Color mode:** light (9), mixed (6), dark (3)
**Hero patterns:** full-bleed (6), layered (6), centered (2), left-right (2)
**Frameworks:** Next.js (5), Next.js or Framer (3), Framer (2), Next.js or React (2)
**Animation:** Framer-Motion (10), CSS-only or Framer-Motion for scroll reveals (2), GSAP or Framer-Motion (2)
**Heading fonts:** Playfair Display or similar transitional serif (3), Inter or DM Sans (2), Playfair Display or similar high-contrast serif (1), Custom display serif/slab (1)
**Body fonts:** Inter or DM Sans (8), Inter or similar geometric sans-serif (2), Light-weight serif (1), Light-weight sans-serif (1)

## Color Rules

- **[9]** No accent color at all — entire palette is tonal brown, accent comes from the white flower and purple jacaranda in imagery
- **[8]** CTA button is the only filled color element — extreme restraint
- **[8]** Blue used only for interactive affordances — arrows, icons, star ratings. Never decorative backgrounds.
- **[8]** Copper used ONLY on 3D letterforms and logo — extremely disciplined, never on buttons or UI chrome
- **[8]** Minimal — warm tones only in annotation lines and arrow icons
- **[8]** Warm brown used only for interactive hotspot elements and dark CTAs — very restrained
- **[8]** Earth tones appear only in photography and 2 small pill CTAs — extremely restrained
- **[7]** Amber used only for CTAs, stat left-borders, and logo — max 5% of surface area
- **[7]** Gold reserved strictly for interactive elements, prices, and brand identity — never decorative fills
- **[7]** Burnt orange used only on featured pricing card border and CTA — extremely restrained
- **[7]** Coral used only for active states and selection checkmarks — max 5% of surface area
- **[7]** Blue dominates nav/filters as solid fills; used sparingly as heart icons and tags on cards
- **[7]** Accent blue used only in background tints and subtle UI elements, never as CTA fill

### Color Craft Insights
- **[9]** The complete absence of a contrasting accent color is a bold choice — the white flower imagery IS the accent, making the visual hierarchy entirely image-driven rather than color-coded
- **[8]** The entire palette is literally sampled from the architectural render — terracotta balconies, pale sky, concrete cream. Zero arbitrary color choices.
- **[8]** The blue accent (#30659F) is desaturated enough to feel architectural rather than tech-startup — a senior move that keeps the palette grounded in the real estate vertical
- **[8]** The warm undertone in every neutral (#110E0C not #000, #F4F2F1 not #FFF) creates cohesion — a senior move that prevents the dark theme from feeling cold or generic
- **[8]** The off-white (#F1F5EF) instead of pure white is key — it keeps the entire palette feeling organic and prevents the dark sections from feeling like generic dark mode
- **[8]** Entire palette is extracted from the hero photography — wood ceiling browns, limestone grays, bay water tones — creating seamless image-to-UI color continuity
- **[8]** The color palette is essentially monochrome + the architecture itself provides all the warmth — the designer trusts the photography completely
- **[7]** The amber accent is warm enough to feel approachable but muted enough to avoid cheapness — it's closer to gold (#E8A030) than orange, which is the right call for a financial consulting brand
- **[7]** The warm-black (#1C1E1B) instead of pure #000 prevents harshness and adds organic warmth that pure black luxury sites miss
- **[7]** The warm-shifted neutrals (#131211 instead of #000, #F4F4F3 instead of #FFF) create cohesion — everything feels like it belongs to the same material palette

## Color Palettes

### Luxury boutique residential development pre-sales Example (monochromatic / mixed)
- `#26150D` — **text-primary** — Deep espresso brown conveys grounded luxury without the cliché of black
- `#493122` — **accent-dark** — Warm chocolate anchors the earthy palette with authority
- `#6B5F55` — **text-secondary** — Muted warmth maintains readability without harshness
- `#8A7C70` — **surface-warm** — Bridges the dark-to-light transition in the hero gradient
- `#AEA9A4` — **decorative** — Neutral warmth for depth without distraction
- `#F3F0EB` — **bg-primary** — Warm off-white feels like natural linen, avoids sterile pure white
- `#FAFAF8` — **bg-outer** — Barely-there warmth creates subtle depth layering

### Luxury boutique apartment pre-sale marketing Example (monochromatic / light)
- `#E1EAF5` — **bg-hero** — Mimics the pale blue sky in the render, creating seamless photo-to-page bleed
- `#F5EDE6` — **bg-primary** — Warm cream evokes clay/terracotta — the building's namesake material
- `#A7814B` — **text-primary** — Terracotta-bronze reads as earthy luxury without the coldness of black
- `#543625` — **accent-cta** — Darker clay tone creates hierarchy while staying in the monochromatic family
- `#251A11` — **text-deep** — Near-black warm brown for maximum readability when needed
- `#D8C6A7` — **decorative** — Mid-tone bridge between cream bg and bronze text
- `#B6B4B3` — **surface-card** — Neutral grey-warm for understated supporting content

### Luxury real estate agency with architecture/interior design services Example (neutral-plus-accent / mixed)
- `#060608` — **bg-primary-dark** — Luxury signifier — black conveys exclusivity and premium positioning
- `#30659F` — **accent-cta** — Trustworthy blue signals reliability in real estate — not too corporate, not too playful
- `#E4E4E4` — **bg-primary-light** — Warm gray avoids sterile white, adds sophistication
- `#414B61` — **text-secondary** — Muted navy-gray maintains readability without harsh contrast
- `#FFFFFF` — **surface-card** — Clean canvas for content-heavy cards
- `#949494` — **text-tertiary** — Establishes clear typographic hierarchy through value contrast

### Luxury property developer corporate brand site Example (neutral-plus-accent / dark)
- `#110E0C` — **bg-primary** — Near-black with warm undertone conveys exclusivity without coldness
- `#3A3533` — **surface-card** — Subtle lift from pure black creates depth layers
- `#9B4B24` — **accent-decorative** — Copper/bronze signals premium craftsmanship and timeless value
- `#F4F2F1` — **text-primary** — Warm white avoids clinical feel, maintains luxury warmth
- `#918A82` — **text-secondary** — Muted warm gray for hierarchy without harshness
- `#FFFFFF` — **bg-secondary** — High contrast against dark sections creates visual punch
- `#8A6758` — **decorative** — Bridges dark bg to bright copper highlight
- `#C9A88A` — **accent-highlight** — Metallic sheen peak for 3D realism

### Luxury sustainable architecture firm portfolio Example (neutral-plus-accent / dark)
- `#080A06` — **bg-primary** — Near-black green creates luxury atmosphere and lets photography breathe
- `#1A2E10` — **bg-secondary** — Reinforces nature/evergreen brand identity without pure black
- `#F1F5EF` — **text-primary** — Warm off-white avoids harsh contrast, feels organic
- `#FFFFFF` — **surface-card** — Clean contrast against dark sections creates visual rhythm
- `#99805A` — **decorative** — Warm brass tone adds material quality — wood/metal association
- `#626359` — **text-secondary** — Muted sage for secondary hierarchy

### Luxury waterfront residential complex marketing Example (neutral-plus-accent / light)
- `#D7DBDF` — **bg-primary** — Cool gray creates calm, premium atmosphere without stark white
- `#171310` — **text-primary** — Warm black feels organic and luxurious vs pure #000
- `#4B4236` — **accent-warm** — Warm brown-gray echoes wood tones in the imagery, grounding the palette
- `#89847C` — **text-secondary** — Mid-tone warm gray for hierarchy without competing
- `#A19E9B` — **surface-muted** — Subtle differentiation layer
- `#FFFFFF` — **surface-card** — Clean contrast against gray background for content elevation

### Luxury minimalist architecture estate curation Example (neutral-plus-accent / mixed)
- `#FEFEFE` — **bg-primary** — Gallery-white lets architecture photography breathe and command attention
- `#060403` — **text-primary** — Near-black provides maximum contrast and editorial authority
- `#534E4F` — **text-secondary** — Warm gray softens reading experience, avoids harsh pure-black fatigue
- `#1A1A1A` — **surface-dark** — Dark sections create dramatic rhythm breaks and elevate white text
- `#BE8D65` — **accent-warm** — Desert-sand tone bridges photography palette into UI, signals warmth and craft
- `#9D603B` — **accent-earth** — Terracotta grounds the luxury in earthiness, avoids cold sterility
- `#989B9A` — **decorative-muted** — Quiet gray for metadata keeps hierarchy clean without competing

### Property tax assessment consulting for BC property owners Example (neutral-plus-accent / mixed)
- `#070B0E` — **bg-primary-dark** — Deep navy conveys authority and institutional trust for financial services
- `#1A2A3A` — **surface-card** — Slightly lighter navy creates depth layers without losing dark theme cohesion
- `#F4F5F7` — **bg-light** — Cool off-white feels professional, avoids stark pure white
- `#E8A030` — **accent-cta** — Warm amber/gold signals premium value and urgency against navy — classic finance pairing
- `#3C3D44` — **text-secondary** — Soft dark gray reduces harshness while maintaining readability
- `#FFFFFF` — **text-on-dark** — Maximum contrast for legibility on dark overlays

## Typography

- **[9] Custom didone serif — likely Freight Dis + Light-weight serif — possibly **: Single type family at different optical sizes creates cohesion; the high-contrast serif mirrors the building's sculptural curves
- **[8] Custom or premium serif — likely Cormora + Light-weight sans-serif — like**: Elegant high-contrast serif for prestige display paired with clean spaced sans for legibility — classic luxury real estate formula
- **[8] Likely a custom or premium serif/sans hy + Geometric sans-serif — likely **: The oversized sans hero contrasts with refined serif accent to balance modernity with heritage — architecture meets tradition
- **[8] Serif — likely Playfair Display or simil + Sans-serif — likely Inter or H**: Didone serif headings signal luxury editorial while clean sans body ensures readability on dark backgrounds
- **[8] Custom condensed serif — likely Playfair + Inter or similar geometric san**: Bold condensed serif for authority and editorial gravitas paired with clean sans for legibility — classic luxury architecture pairing
- **[8] Playfair Display or similar transitional + Inter or DM Sans — geometric s**: Italic serif headline conveys elegance and editorial luxury while sans-serif body ensures modern readability — classic luxury real estate pairing.
- **[8] Neue Haas Grotesk or Helvetica Neue — ne + Same family at lighter weight **: Single-family system at varying weights creates Swiss editorial cohesion while letting scale alone drive hierarchy
- **[7] Playfair Display or similar high-contras + Inter or similar geometric san**: High-contrast serif for authority and tradition paired with clean sans for modern readability — classic law/finance pairing
- **[7] Playfair Display — transitional serif + Inter or DM Sans — geometric s**: Classic serif headlines evoke heritage and prestige while clean sans body ensures modern readability — the luxury editorial standard
- **[7] DM Serif Display or similar transitional + Inter or DM Sans — geometric s**: Serif headlines convey established trust and premium quality; sans body ensures modern readability — classic real estate pairing

### Typography Effects
- **[9]** Oversized AMARI logotype layered behind/through flower image — z-index layering + mix-blend-mode or masking
- **[9]** Motion-trail distortion on flower creates pseudo-typography interaction
- **[8]** Oversized hero headline at ~130px with ultra-thin weight creating dramatic negative space — font-weight:300 + font-size:clamp()
- **[8]** Hero 'schwartz' uses background-clip:text or mix-blend-mode to show image through letterforms — creates transparency/overlay effect
- **[8]** Serif 'estates' in italic positioned as superscript accent — CSS position:absolute offset
- **[8]** Footer email 'hello@schwartz.com' in massive display type — oversized-crop technique
- **[8]** Hero RANGS text uses background-clip:text with architectural photo as fill — creates see-through text effect revealing the building imagery
- **[8]** 3D copper letterforms are rendered assets, not CSS — likely Blender/Cinema4D renders placed as PNGs
- **[8]** Oversized stat numbers at 120px+ create dramatic scale contrast — font-size + font-weight manipulation
- **[8]** WE SHAPE SPACES uses condensed tracking with uppercase for monumental feel — letter-spacing: -0.02em

## Hero Patterns

- **[9] layered** (Luxury boutique residential development pre-sales): Flower motion trail → AMARI logotype center → 'Eternal beauty' left → 'by the river' right → 'COMING SOON' bottom
- **[8] layered** (Luxury boutique apartment pre-sale marketing): ARCILLA headline → building render right → 'BY JOE ADSETT' → tagline → CTA button
- **[8] full-bleed** (Luxury real estate agency with architecture/interi): Giant 'schwartz' text → floating house image → tagline left → category pills bottom → CTA bottom-right
- **[8] full-bleed** (Luxury property developer corporate brand site): RANGS text-fill → PROPERTIES subhead → category links → down arrow
- **[8] full-bleed** (Luxury sustainable architecture firm portfolio): Image center → WE SHAPE SPACES headline → Contact Us CTA → annotation labels
- **[8] split-50-50** (Luxury waterfront residential complex marketing): Headline → hero image → hotspot tooltips → CTAs → feature card bottom-left
- **[8] layered** (Luxury minimalist architecture estate curation): Headline 'The Arts' → hero architecture image → 'Of Living' → tagline → video CTA card
- **[7] full-bleed** (Property tax assessment consulting for BC property): Eyebrow label → large serif headline → body copy right → orange CTA button
- **[7] centered** (Ultra-luxury global real estate brokerage): Gold label → massive headline → subtext → gold CTA button left → outline CTA right
- **[7] left-right** (Home improvement and property management services): Headline → hero image → CTA button → stats row

## Card & Component Patterns

- **[8]** White bg, ~16px radius, ~24px padding, subtle shadow, numbered top-left with icon top-right, hover likely lift/shadow-increase
- **[8]** n/a — sections use full-width image+text blocks, not traditional cards
- **[8]** Project cards — no border-radius, image top + text bottom, ~16px padding, arrow CTA bottom-right, hover likely image zoom
- **[8]** White bg, border-radius ~16px, ~20px padding, subtle box-shadow, contains image thumbnail + stats + description — feature card pattern
- **[8]** Video preview card — white bg, thumbnail left, text right, ~12px radius, 16px padding, shadow-sm, overlaps hero image
- **[7]** Problem card: glassmorphism with backdrop-filter:blur, rounded-16, ~32px padding, frosted border. Solution card: solid dark navy, rounded-16, same padding
- **[7]** Dark surface #2A2C28, 8px radius, 0px padding outside / 16px inside text area, image top with 4px radius, hover likely subtle lift, vertical stack layout
- **[7]** White bg, border-radius ~12-16px, ~24px padding, subtle 1px border or light shadow, service cards have centered icon + title + description
- **[7]** White bg, border-radius ~16px, padding ~16px, subtle shadow, image thumbnails with rounded corners ~12px, checkmark badges top-right
- **[7]** White bg, border-radius: 12px, 0px padding on image / 16px content, subtle box-shadow, image top with badges overlay, price-specs-address-agent stack, heart icon top-right
- **[7]** Property cards with rounded-12 corners, white bg, 16-20px padding, subtle shadow on hover, image-top/info-bottom layout, price badge overlay

### Buttons

- **primary / rounded-8**: `border: 1.5px solid #493122; letter-spacing: 0.2em; text-transform: uppercase`
- **primary / rounded-4**: `background-color with letter-spacing on label`
- **secondary / rounded-4**: `border: 1px solid with transparent bg`
- **primary / pill**: `border: 1px solid currentColor with inline icon`
- **secondary / rounded-8**: `Blue circle arrow button — border-radius:50% on icon container`
- **ghost / n/a**: `text-transform:uppercase; letter-spacing:0.2em`
- **primary / pill**: `border: 1px solid white; border-radius: 999px`
- **secondary / pill**: `border: 1px solid #080A06; border-radius: 999px`
- **ghost / square**: `Arrow icon links with border`
- **primary / pill**: `background:#171310; border-radius:24px; color:white`
- **secondary / pill**: `border:1px solid #A19E9B; border-radius:24px; background:transparent`
- **icon / pill**: `width:44px; border-radius:50%; background:#171310`
- **primary / pill**: `border-radius:50%, white bg with dark text`
- **secondary / pill**: `Small earth-tone pills on image cards`
- **ghost / square**: `Text links with letter-spacing`
- **primary / pill**: `background-color with border-radius:24px`
- **secondary / pill**: `backdrop-filter:blur + semi-transparent bg`
- **nav-cta / pill**: `border:2px solid amber, transparent bg`
- **primary / rounded-4**: `background-color: #C9A84C; color: #1C1E1B`
- **secondary / rounded-4**: `border: 1px solid #C9A84C; color: #C9A84C`
- **ghost / rounded-4**: `border: 1px solid #3D4337; used for filter chips`
- **primary / pill**: `border-radius: 999px with arrow icon left-aligned inside`
- **secondary / pill**: `border: 1px solid #131211`
- **accent / pill**: `background: #AF4824 for featured pricing CTA`

## Animation & Interaction

- **[9]** Flower motion-trail animation on hero load → custom WebGL or Framer-Motion stagger with clip-path
- **[9]** Horizontal image carousel/slider → Framer-Motion drag or scroll-linked transform
- **[9]** Scroll-triggered text fade-in → Framer-Motion whileInView
- **[9]** Parallax depth on building render → scroll-linked translateY at different rates
- **[9]** Button hover fill transition → CSS transition on background-color
- **[8]** Scroll-parallax on gallery images — different translateY speeds per layer — Framer-Motion
- **[8]** Fade-up reveal on text sections — opacity:0→1 + translateY:30→0 on scroll — Framer-Motion
- **[8]** Hero image subtle parallax — background-attachment or transform — Framer-Motion
- **[8]** Button hover state — likely opacity shift or background-color transition — CSS transition
- **[8]** Marquee ticker continuous scroll → CSS animation or GSAP ticker
- **[8]** Testimonial carousel prev/next → Framer-Motion slide transition
- **[8]** Card hover lift → transform:translateY(-4px) + box-shadow increase
- **[8]** CTA arrow hover → scale/rotate micro-animation
- **[8]** Scroll-triggered section reveals → IntersectionObserver + opacity/translateY
- **[8]** Scroll-triggered section fade-in → GSAP ScrollTrigger
- **[8]** 3D letter parallax slight float on scroll → GSAP or CSS transform
- **[8]** Hero text image-fill with possible subtle parallax → background-attachment or JS
- **[8]** Category nav hover states → CSS transitions
- **[8]** Hamburger menu open/close → CSS transform + opacity transition
- **[8]** Stat number count-up on scroll → GSAP ScrollTrigger + countUp
- **[8]** Annotation hotspot pulse animation → CSS keyframes
- **[8]** Project card hover image zoom → transform:scale(1.05) + overflow:hidden
- **[8]** Section fade-in on scroll → Intersection Observer + opacity/translateY
- **[8]** Button hover fill transition → background-color transition 0.3s
- **[8]** Hotspot pulse animation → CSS keyframes or Framer-Motion
- **[8]** Tooltip popover on hotspot click → Framer-Motion AnimatePresence
- **[8]** Image carousel with pagination → Framer-Motion drag or Embla Carousel
- **[8]** Feature card thumbnail strip scroll → scroll-snap-type CSS
- **[8]** Category tab switching → Framer-Motion layout animations
- **[8]** Hero headline staggered reveal → GSAP SplitText or Framer-Motion variants
- **[8]** Scroll-triggered section fade-up → Intersection Observer + opacity/translateY
- **[8]** Testimonial carousel with progress bar → Embla or Swiper with custom pagination
- **[8]** Gallery horizontal scroll with snap → CSS scroll-snap or GSAP ScrollTrigger horizontal
- **[8]** Video card hover → scale transform with box-shadow elevation
- **[7]** scroll-fade-in on stats section — CSS or Framer-Motion
- **[7]** hover-fill on outline nav CTA — CSS transition
- **[7]** parallax-subtle on hero background image — CSS background-attachment or JS
- **[7]** card-hover-lift on service cards — transform:translateY + box-shadow transition
- **[7]** Filter chip toggle — active gold fill swap → CSS transition
- **[7]** Stat counter scroll-in — number count-up animation → Framer Motion / countUp.js
- **[7]** Property card hover — subtle lift or image zoom → transform: translateY(-4px) or scale
- **[7]** City card hover — overlay opacity shift → opacity transition on pseudo-element
- **[7]** Nav active state — gold underline indicator → border-bottom with transition
- **[7]** Stat counter animation on scroll → Framer-Motion useInView + animate
- **[7]** Card hover lift → CSS transform: translateY(-4px) + box-shadow transition
- **[7]** CTA button hover → background-color darken transition 200ms
- **[7]** Gallery images hover → subtle scale(1.02) with overflow:hidden
- **[7]** Scroll-triggered section fade-in → Framer-Motion or Intersection Observer
- **[7]** hotspot-marker-click → popover with room details, Framer-Motion
- **[7]** floor-selector-switch → 3D view transition/crossfade, CSS transition or Three.js camera
- **[7]** card-selection-toggle → checkmark badge appear with scale animation, CSS transform
- **[7]** zoom-controls → 3D viewport scale, Three.js or CSS transform
- **[7]** filter-dropdown-open → slide-down with opacity, Radix Popover
- **[7]** hover-card-lift — subtle translateY(-2px) + shadow increase on property cards, CSS transition
- **[7]** heart-toggle — fill animation on favorite click, CSS or React state
- **[7]** image-carousel — left/right arrows on featured card, likely Swiper.js or Embla
- **[7]** filter-dropdown — click to expand filter options, headless UI or shadcn Select
- **[7]** map-price-hover — price bubble on map corresponds to listing hover, Mapbox/Google Maps SDK

## Decorative Elements

- **motion-trail-flower** at Hero — calla lily with vertical slice/stagger animation trail: `WebGL or canvas-based image slicing, possibly Three.js displacement or GSAP stagger with clip-path`
- **brown-frame-border** at Gallery carousel — thick brown border frames the central image: `CSS border or padding with background-color on wrapper`
- **vignette-gradient** at Hero background — radial gradient darkening edges: `radial-gradient or pseudo-element overlay`
- **overlapping-image-frames** at Gallery section — three images layered with offset positioning: `position:absolute with z-index stacking and transform:translate offsets`
- **bleed-crop** at Hero — building render crops off right edge: `overflow:hidden on container with object-position`
- **marquee-ticker** at Top of page, continuous scroll: `CSS animation: translateX infinite linear, or JS marquee`
- **text-image-blend** at Hero section: `mix-blend-mode or background-clip:text with image background`
- **section-label-dots** at Before section titles: `Pseudo-element ■ square bullet`
- **3D copper letterforms** at Each brand section (R,A,N,G,S): `Positioned PNG/WebP assets, likely with object-fit and z-index layering`
- **Image-filled text** at Hero RANGS headline: `background-clip:text with -webkit-text-fill-color:transparent`
- **Dark overlay on hero** at Hero section: `Linear-gradient overlay or ::after pseudo-element with rgba black`
- **annotation-lines** at Hero image hotspots: `SVG lines with absolute positioning + pseudo-elements`
- **dark-vignette** at Hero and featured project images: `linear-gradient overlay on ::after pseudo-element`
- **dot-markers** at Hero annotation points: `Pulsing circles with border-radius: 50% + animation`
- **interactive-hotspots** at Hero image overlay — 3 anchor points: `position:absolute with tooltip popovers, likely CSS transforms for pulse animation`
- **frosted-tooltip** at Hotspot labels on image: `backdrop-filter:blur + semi-transparent background`
- **rounded-container** at Entire page wrapper: `border-radius:~24px on outer container, overflow:hidden`
- **section-number-index** at Before section titles (001, 003, 007): `Pseudo-element or span with monospace styling`
- **progress-bar** at Testimonial carousel bottom: `Width transition on active state`
- **thin-rule-dividers** at Between sections: `border-top: 1px solid rgba(0,0,0,0.1)`
- **dark-overlay** at Hero and expertise full-bleed sections: `linear-gradient overlay on background-image or ::after pseudo-element with rgba`
- **glassmorphism-card** at Problem card in expertise section: `backdrop-filter:blur(20px) + background:rgba(255,255,255,0.08) + border:1px solid rgba(255,255,255,0.15)`
- **left-border-accent** at Each stat in stats grid: `border-left:3px solid #E8A030`
- **page-wrapper-shadow** at Entire page container on gray bg: `box-shadow or nested container on #DDE0E4 background`
- **dark-gradient-overlay** at Hero image: `linear-gradient overlay on background-image`
- **gold-accent-line** at Below hero center, section dividers: `border-bottom or pseudo-element`
- **horizontal-rule** at Below property prices, section breaks: `border-bottom: 1px solid rgba(255,255,255,0.1)`
- **rounded-corners** at Hero image, all cards, gallery images: `border-radius: 12-20px`
- **warm-bg-tint** at Gallery/about section background: `background-color with warm neutral`

## Design Recipes

### Score 9/10 — organic-natural — Luxury boutique residential development pre-sales

**Design Recipe:** Use a warm monochromatic brown palette (#26150D to #F3F0EB) with zero accent colors — let imagery provide all contrast. Set hero type in a high-contrast didone serif at 120px+ with 0.15em letter-spacing, uppercase, light weight. Layer the logotype behind a full-bleed organic image (flower, fabric, water). Keep body copy centered, max-width 640px, in the same serif at 18px light weight with 1.6 line-height. Use generous 120-160px section padding. Frame gallery images with a thick 40px brown (#493122) border. Buttons are outline-only with uppercase tracking.

**Dev Recipe:** Build in Framer for native animation support. Hero flower effect needs either a custom WebGL shader (Three.js + image displacement) or a clip-path stagger array animated with Framer-Motion. Use self-hosted premium serif (Freight Display or similar). Image carousel via Framer's native scroll components with overflow clipping and a CSS-bordered wrapper.

**Core Lesson:** A single extraordinary visual moment (the animated flower) does more for luxury perception than ten generic sections of content

**Steal These:**
- Motion-trail image effect as hero centerpiece — one image, infinite drama
- Complete absence of accent color — letting photography be the only contrast
- Thick colored frame border around gallery images for editorial gravitas
- Flanking taglines ('Eternal beauty' left, 'by the river' right) around central logotype
- Building render breaking the section boundary — image bleeds between content zones

**Weaknesses:** No visible navigation — users need wayfinding even on teaser sites, Very limited content shown — may feel thin for actual buyers wanting floor plans, pricing, location info, Monochromatic brown risks feeling monotonous on longer pages without strategic image variety

---

### Score 8/10 — warm-minimal — Luxury boutique apartment pre-sale marketing

**Design Recipe:** Use a warm monochromatic palette extracted from terracotta: bg #F5EDE6, text #A7814B, deep accent #543625, hero sky #E1EAF5. Set the hero headline in a high-contrast didone serif (Cormorant Garamond Light) at 120-140px uppercase with 0.05em letter-spacing. All supporting text in a geometric sans at 12-13px uppercase with 0.2em letter-spacing. Layout is asymmetric 40/60 text-image splits with 120px+ section padding. Use only one or two CTA buttons per viewport — extreme restraint. Gallery uses 3 overlapping images with 20-40px offset stacking and subtle box-shadows.

**Dev Recipe:** Framer or Next.js with Framer Motion for scroll-triggered parallax and fade reveals. Self-host premium serif font, use CSS custom properties for the terracotta palette, implement intersection observer for staggered text animations, and use transform3d for GPU-accelerated parallax on the gallery stack.

**Core Lesson:** Let the physical product's material palette become the entire digital color system — when the website looks like it's made of the same clay as the building, brand coherence is effortless.

**Steal These:**
- Sampling the color palette directly from the product's physical materials
- Oversized ultra-light serif headline against photorealistic architectural render
- Porsche 911 in the render as aspirational lifestyle anchoring without saying a word
- Three overlapping images at different depths creating a physical collage feel
- Using the sky color from the hero render as the actual hero background — seamless bleed

**Weaknesses:** Bronze-on-cream text contrast likely fails WCAG AA — needs darker text or lighter bg for body copy, Body text at ~14px light weight is too small and thin for comfortable reading, No visible navigation — fine for a teaser page but problematic if this scales to full site with floorplans/pricing

---

### Score 8/10 — minimal-corporate — Luxury real estate agency with architecture/interior design 

**Design Recipe:** Use #060608 dark and #E4E4E4 warm-gray as alternating section backgrounds. Set hero type at 180-220px lowercase in a geometric sans (Satoshi/Neue Montreal) with mix-blend-mode over a full-bleed architectural photo. Accent with #30659F blue ONLY on interactive elements (arrows, icons). All section labels use 11px uppercase tracking:0.15em with a ■ prefix. Cards are white with 16px radius, 24px padding, numbered 01-04. Stats use 56-64px bold numerals. Footer features an oversized email address at ~80px as the final CTA.

**Dev Recipe:** Build in Next.js with Tailwind CSS and Framer-Motion. Use mix-blend-mode:screen on the hero h1 over a background-image container, CSS keyframes for the marquee ticker, scroll-snap or Embla Carousel for testimonials, and IntersectionObserver-triggered fade-ups for section entrances.

**Core Lesson:** One bold typographic moment (oversized text blended with imagery) can define an entire brand experience when everything else stays disciplined and restrained.

**Steal These:**
- Oversized lowercase brand name with image-blend transparency in hero
- ■ prefix micro-labels for section identification system
- Avatar stack with '+69' count badge for social proof
- Blue accent restricted exclusively to interactive affordances
- Massive email address as footer CTA — turns contact info into design element

**Weaknesses:** Category pill tags at hero bottom feel disconnected — could integrate better with the hero composition, Testimonial section is fairly standard carousel pattern — could push creativity further, Some AI-generated imagery vibes from the architectural photos — real project photography would add authenticity

---

### Score 8/10 — dark-luxury — Luxury property developer corporate brand site

**Design Recipe:** Dark luxury base: bg #110E0C, text #F4F2F1, accent copper #9B4B24-#C9A88A only on decorative 3D letterforms. Hero uses background-clip:text on 120px uppercase serif (Playfair Display Bold) with architectural photo fill. Below hero, alternate 60/40 asymmetric grid sections — left: white bg with 3D copper letter + right: full-bleed photo, then flip. Each section has a dark #3A3533 text panel below with uppercase serif heading ~28px and light sans body ~14px. Letter-spacing 0.2-0.3em on all uppercase text. Section gaps ~80px. Max-width 1200px centered.

**Dev Recipe:** Next.js with GSAP ScrollTrigger for section reveals. CSS Grid with grid-template-columns alternating '2fr 3fr' and '3fr 2fr' per section using nth-child. background-clip:text on hero with high-res architectural photo. 3D letters as optimized WebP assets positioned with object-fit:contain in white containers.

**Core Lesson:** Use your brand name as the structural framework — when content architecture mirrors identity, the entire site becomes a branding exercise, not just a container for information.

**Steal These:**
- Brand name as content architecture — each letter = a section/pillar
- 3D rendered letterforms as section anchors instead of generic icons
- background-clip:text hero with architectural photography fill
- Copper accent used ONLY on letterforms — extreme restraint creates premium feel
- Alternating asymmetric grid that creates visual zigzag rhythm down the page

**Weaknesses:** Body text too small and light-weight for dark backgrounds — readability suffers on long paragraphs, The concept is so tied to a 5-letter name that it's not scalable if brand pillars change, Mobile layout loses the dramatic asymmetric grid impact — sections become generic stacked blocks

---

### Score 8/10 — dark-luxury — Luxury sustainable architecture firm portfolio

**Design Recipe:** Use #080A06 dark green-black as primary background with #F1F5EF warm off-white text. Set hero headlines in a condensed bold serif (try Playfair Display Black or Noto Serif Display) at 96-120px uppercase with -0.02em letter-spacing. Stats use 120-140px regular weight numbers. Body text at 14px in Inter or similar sans. Full-bleed architectural photography with linear-gradient(to bottom, transparent 40%, rgba(8,10,6,0.8)) overlays. Pill-shaped outline buttons with 1px white borders and 999px border-radius at 44px height. 100-120px section gaps. Project cards in CSS Grid with no border-radius.

**Dev Recipe:** Next.js + Tailwind CSS + GSAP ScrollTrigger for stat counters and scroll reveals. Self-host the serif font, use next/image for optimized architectural photography with priority loading on hero. Key CSS: mix-blend-mode for text overlays, CSS Grid with grid-column span for asymmetric project layout.

**Core Lesson:** Massive typographic scale contrast (120px stats vs 12px labels) creates instant visual hierarchy without needing color variation

**Steal These:**
- Annotation hotspots on hero image with pulsing dot markers and connecting lines
- 120px+ stat numbers paired with tiny 11px uppercase labels for extreme scale contrast
- Off-white (#F1F5EF) instead of pure white on dark backgrounds for organic warmth
- Pill outline buttons that feel premium without being heavy
- Dark green-black (#080A06) as a sophisticated alternative to pure black dark mode

**Weaknesses:** Project card section feels slightly generic compared to the hero — could use more asymmetry or hover interactions, The 'Quiet Space' and 'Residential Home' sections feel like separate pages stitched together — visual continuity could be tighter, Small body text at 11-12px on some labels may fail accessibility requirements

---

### Score 8/10 — warm-minimal — Luxury waterfront residential complex marketing

**Design Recipe:** Use #D7DBDF cool-gray page background with #171310 warm-black text and #FFFFFF card surfaces. Set headlines in an italic serif (Playfair Display) at 52px uppercase with tight tracking, body in Inter/DM Sans at 15px. Build an asymmetric 45/55 grid split — left text content with generous 80px padding, right full-bleed architectural photography. All interactive elements use pill shapes (border-radius:24px), cards at 16px radius. Add interactive hotspot overlays on the hero image with frosted-glass tooltip popovers (#4B4236 semi-transparent bg + backdrop-filter). Keep the palette to 5 warm neutrals maximum — no saturated accent colors.

**Dev Recipe:** Next.js + Tailwind CSS + Framer Motion for the interactive hotspot system and page transitions. Use CSS Grid with grid-template-columns: 45fr 55fr for the split layout, position:absolute hotspots on a relative image container with ResizeObserver to maintain positions on resize, and backdrop-filter:blur(12px) for frosted tooltips.

**Core Lesson:** Let the hero imagery dictate your entire color palette — when UI colors are sampled from the photography, the design feels inevitable rather than designed.

**Steal These:**
- Interactive hotspot overlay system turning static hero into explorable space
- Warm-black #171310 instead of pure black for organic luxury feel
- Cool gray #D7DBDF background instead of white — instant premium lift
- Feature card overlapping the hero/content boundary for depth
- Category pill tabs floating over the hero image for contextual navigation

**Weaknesses:** Left content area feels slightly text-heavy — the 'RESIDENTIAL COMPLEX' badge placement is awkward next to the headline, Bottom-left feature card + info panel creates visual density that competes with the hero CTA area, Hotspot system will be challenging to make accessible — needs keyboard navigation and ARIA labels

---

### Score 8/10 — editorial — Luxury minimalist architecture estate curation

**Design Recipe:** Use #FEFEFE white background with #060403 near-black text. Set hero headline in Neue Haas Grotesk Medium at 96-120px with -0.02em tracking, split across a full-bleed architectural photo using CSS Grid overlap. Section labels in 11px uppercase with 0.1em letter-spacing in #989B9A. Body text at 18-20px regular weight, max 65ch measure. Alternate white and #1A1A1A dark sections. Use 80-120px vertical section spacing. Pill buttons at 40px height with full border-radius. Footer text at 180px+ bold uppercase spanning full width.

**Dev Recipe:** Next.js 14 + Tailwind CSS + GSAP ScrollTrigger for scroll animations and horizontal gallery. Self-host Neue Haas Grotesk via @font-face. Use CSS Grid with named areas for hero text-image overlap, Embla Carousel for testimonials, and Intersection Observer for section reveal animations.

**Core Lesson:** Let the architecture speak — restrain your palette to monochrome + earth photography, and use typographic scale contrast (12px labels vs 120px headlines) as your primary design tool

**Steal These:**
- Split headline wrapping around hero image — instant editorial authority
- Numbered section indices (001, 003, 007) as quiet organizational system
- Dark testimonial section as dramatic rhythm break in otherwise white page
- Mega-scale footer copyright text as closing brand statement
- Video preview card overlapping hero boundary — breaks the grid intentionally

**Weaknesses:** Stats section (500+) feels slightly orphaned — needs stronger visual connection to adjacent content, Body text overlay on hero image bottom has legibility risk without careful contrast management, Featured properties gallery thumbnails are quite small — may frustrate users wanting to browse

---

### Score 7/10 — minimal-corporate — Property tax assessment consulting for BC property owners

**Design Recipe:** Use Playfair Display at 56-64px regular weight for H1 on dark navy (#070B0E) backgrounds with white text. Pair with Inter 16px for body. Accent sparingly with warm gold (#E8A030) — only on CTAs (pill shape, border-radius:24px, solid fill) and 3px left-borders on stat items. Sections alternate between full-bleed dark photo backgrounds (with rgba(7,11,14,0.75) overlay) and clean #F4F5F7 light sections. Eyebrow labels always uppercase, 12px, letter-spacing:0.15em, monospace feel. Max-width 1200px container, 80-100px vertical section padding.

**Dev Recipe:** Next.js or Astro static site with Tailwind CSS. Use next/image for optimized hero photos, backdrop-filter:blur(20px) for glass cards, CSS custom properties for the navy/gold theme tokens. Intersection Observer for scroll-triggered fade-ins.

**Core Lesson:** A high-contrast Didone serif at large scale instantly communicates institutional authority — it does more brand work than any illustration or animation could.

**Steal These:**
- Amber/gold left-border on stat numbers — simple but effective hierarchy device
- Problem vs Solution side-by-side cards with glass vs solid treatment to visually encode negative vs positive
- Uppercase monospaced eyebrow labels above every section heading for consistent rhythm
- Pill-shaped CTA buttons with glass secondary variant on dark backgrounds
- Full-bleed photo sections with heavy dark overlay alternating with clean white stat sections

**Weaknesses:** Duplicate 95% stats are clearly placeholder — undermines credibility for a trust-dependent service, CTA button typo 'Asssment' — fatal for a professional consulting firm, Glassmorphism problem card may age poorly and reduces text readability vs a solid dark card

---

### Score 7/10 — dark-luxury — Ultra-luxury global real estate brokerage

**Design Recipe:** Use #1C1E1B (warm black) background with #FFFFFF headlines in Playfair Display at 64-72px, #ABACA9 body text in Inter at 15px, and #C9A84C gold exclusively for CTAs, prices, active states, and brand name. Section spacing 100-120px, card surfaces at #2A2C28 with 8px radius. Uppercase 12px letter-spacing: 0.15em labels above every section heading in gold. Property cards in 3-column grid with full-width images, left-aligned text, metadata in small gray chips, and prices in gold. Footer in 3-column layout with thin border-top separator.

**Dev Recipe:** Next.js App Router with Tailwind CSS, extend theme with custom gold/warm-black tokens. Use next/image for property photos with priority loading on hero. Framer Motion for scroll-triggered stat counters and page transitions. Filter state managed with URL params via useSearchParams for shareable filtered views.

**Core Lesson:** Luxury is communicated through restraint — a single gold accent (#C9A84C) on near-black (#1C1E1B) with generous whitespace does more than any gradient or animation.

**Steal These:**
- Gold-only accent discipline — one color does all the heavy lifting for hierarchy
- Uppercase wide-tracked eyebrow labels above every section heading
- Property metadata as small rounded chips (location pin + sqft icon)
- City cards with property count overlay and bold city name at bottom-left
- Warm-black (#1C1E1B) instead of pure black for approachable luxury

**Weaknesses:** No visible hover states or micro-interactions — feels static for a luxury brand that should feel alive, Property index filter chips lack visual feedback for multi-select states, Featured property page gallery lacks lightbox or zoom — missed opportunity for immersive viewing

---

### Score 7/10 — warm-minimal — Home improvement and property management services

**Design Recipe:** Use DM Serif Display Bold at 56-64px for headlines on #F4F4F3 background with #131211 text. Pair with DM Sans Regular 15-16px for body in #686767. Cards are white (#FFFFFF) with 12-16px border-radius on the warm off-white bg. Single accent color #AF4824 burnt orange used ONLY on one featured element. Hero is 50/50 split with text left, large rounded-corner architectural photo right. Stats row uses 48px bold numbers with 13px gray captions below. Section spacing 80-100px, card padding 24px, 24px grid gutters.

**Dev Recipe:** Next.js + Tailwind CSS with DM Serif Display and DM Sans from Google Fonts. Use CSS Grid for hero split and service card layouts, Framer Motion for scroll-triggered fade-ins and stat counter animations. Custom Tailwind config for the warm neutral palette.

**Core Lesson:** Warm-shifted neutrals (off-black #131211, off-white #F4F4F3, sandy #CDC0AD) create a premium residential feel that pure black/white never achieves

**Steal These:**
- Warm-shifted neutral palette instead of pure black/white
- Pill-shaped CTA with embedded arrow icon
- Stats row as social proof directly in hero section
- Single burnt-orange accent on featured pricing card only
- Serif headlines + sans body for residential premium feel

**Weaknesses:** Hero image is likely AI-generated — real project photography would add authenticity, Service cards section is generic 3x2 grid with no visual differentiation, No visible navigation links — hamburger-only on desktop sacrifices discoverability

---

### Score 7/10 — warm-minimal — Property management dashboard with 3D floor plan visualizati

**Design Recipe:** Use #E6E6E5 warm gray page background with #FFFFFF cards at border-radius: 16px and box-shadow: 0 2px 12px rgba(0,0,0,0.06). Accent sparingly with terracotta #B33C26 for active states only. Set Inter at 14px body / 28px h1 / 22px h2. Navigation uses pill-shaped items (border-radius: 24px, height: 40px) with active fill in coral. Cards use 16px padding, 12px image radius. Floor plan items grid at 3 columns with 16px gap. Keep icon buttons in 36px white circles with 1px #E0E0E0 border. Maintain 24px spacing between major sections.

**Dev Recipe:** Next.js + Tailwind + shadcn/ui for the dashboard shell; Three.js or react-three-fiber for the interactive 3D floor plan viewport with raycasting for hotspot clicks. Framer Motion for panel transitions and micro-interactions on card selection.

**Core Lesson:** A single hero visual element (the 3D isometric view) can anchor an entire dashboard's identity and make utilitarian property management feel premium.

**Steal These:**
- Terracotta coral as the sole accent color against warm neutrals — residential and premium
- Vertical floor selector as floating pills over the 3D viewport
- Circular hotspot markers with plus icons on the 3D render for interactive discovery
- Image cards with coral checkmark badges for selection state — clear and delightful
- Metadata pills (Room type, Size, Flat ID) as inline horizontal tags below section headers

**Weaknesses:** Including 3 unrelated projects (NestFlow, Task Pro, Medical app) in one showcase muddies the narrative, Typography hierarchy is too flat — headings and body are too close in size/weight, The 3D floor plan hotspots lack clear affordance — users may not know they're clickable without onboarding

---

### Score 7/10 — minimal-corporate — Luxury property listing marketplace with agent profiles

**Design Recipe:** Use #0117A1 deep blue for nav/filters/CTAs on #F3F3F9 blue-tinted background. White cards (#FFF) with 12px border-radius, 8px shadow. Inter font: prices at 20px bold #0A0C14, metadata at 14px regular #414450. 3-column grid at 24px gap, 1200px max-width. Featured listing spans full width as 50/50 split (image left, details+map right). Filter bar uses pill chips (border-radius: 20px) in solid blue fill with white text. Agent avatars (32px circle) with name at card bottom. Gold (#FDEBAB) badge for featured properties.

**Dev Recipe:** Next.js App Router with Tailwind CSS and shadcn/ui components. Use Embla Carousel for image sliders, Mapbox GL for map integration, and React Query for listing data fetching. Key CSS: grid-template-columns: repeat(3, 1fr) for cards, aspect-ratio: 16/10 for images, position: relative on card containers for absolute badge positioning.

**Core Lesson:** In data-heavy listing pages, a strong featured/hero card that breaks the grid creates visual hierarchy and guides users to premium content

**Steal These:**
- Featured property hero card with integrated map preview breaking the grid
- AI search vs Classic toggle pills in the search bar
- Agent avatar + title attribution on every property card for trust
- Gold badge system for featured/premium listings
- Blue-tinted page background (#F3F3F9) instead of pure white/gray

**Weaknesses:** Card design is very standard — no hover states or micro-interactions visible to differentiate, Popular Links section is an SEO dump that hurts the visual experience, The portfolio includes unrelated grocery app screens which dilutes the real estate focus

---

### Score 7/10 — warm-minimal — Curated luxury residential real estate and premium rentals

**Design Recipe:** Use #F2F8FB ice-blue background with #0D0D09 near-black text. Set headings in a high-contrast serif (Playfair Display) at 56-64px/bold with 1.05 line-height. Body in Inter 15px/#5C6C77. All interactive elements as pill shapes (border-radius:9999px) with 1px #ddd borders. Hero: full-bleed architectural image with 200px uppercase watermark text at 8% opacity layered behind. Wrap entire page in a container with 16px border-radius. Section spacing 100px. Cards: white, rounded-12, minimal shadow. Never use more than 2 saturated colors.

**Dev Recipe:** Next.js + Tailwind CSS + Framer Motion. Use CSS Grid for hero layer stacking (grid-area:1/1 on all children), next/image for optimized property photos, Framer Motion's useScroll for watermark parallax. Pill buttons via Tailwind's rounded-full with ring utilities for focus states.

**Core Lesson:** Monochromatic restraint in a single color temperature (cool blue-gray) creates more perceived luxury than adding gold or multiple accent colors

**Steal These:**
- Pill-shaped nav items instead of plain text links — adds tactile quality
- Large watermark text behind hero image for editorial depth
- Ice-blue (#F2F8FB) background instead of pure white — instant luxury upgrade
- Rounded outer page container creating a card-like viewport
- Split nav with left-aligned menu pills and right-aligned CTA pills

**Weaknesses:** Watermark 'LUXURY' text is on-the-nose — a more abstract word or pattern would feel less literal, Property listing section (image 4) feels generic compared to the hero's sophistication — needs more design continuity, Multiple unrelated portfolio pieces (agency, eco-home) shown together weaken the luxury real estate brand story

---

### Score 6/10 — minimal-corporate — Premium residential property developer website

**Design Recipe:** Use #303E44 dark teal-navy for nav/footer/accents on #FFFFFF base. Headings in Montserrat Bold uppercase with 2-3px letter-spacing, body in Open Sans Regular 14px #141617. Section labels in 11-12px uppercase #708389 with wide tracking. 80-100px section padding. Full-bleed hero at 80vh with 40% dark gradient overlay left-to-right. Project cards in 3-column grid with images filling cards and white uppercase labels positioned absolute bottom-left. Add subtle organic SVG line patterns at 5% opacity on white sections for texture. Single red #C41E3A accent only on video play buttons.

**Dev Recipe:** Next.js with Tailwind CSS for rapid utility-based styling; Swiper.js for hero and project carousels; AOS or Framer Motion for scroll-triggered reveals; react-hook-form for the meeting scheduler with simple bordered inputs.

**Core Lesson:** In real estate web design, premium photography and restrained color palette do 80% of the work — let the properties sell themselves.

**Steal These:**
- Dark teal-navy nav that feels premium without being generic black
- Section label pattern: small uppercase tracking label above bold heading
- Full-bleed hero with interior photography — sells lifestyle not just buildings
- Organic SVG line patterns as subtle background texture on white sections
- Sparse red accent only on interactive video elements — maximum focal impact

**Weaknesses:** Form design is generic and uninspired — needs custom styling to match premium positioning, Project cards lack hover states or interactive depth — missed engagement opportunity, No distinctive design signature — could be any real estate developer's template

---

### Score 5/10 — glassmorphism — Property marketplace with conversion-focused landing page

**Design Recipe:** Start with a full-bleed architectural photo hero. Apply a left-heavy linear-gradient overlay (rgba(19,19,18,0.75) to rgba(19,19,18,0.15)). Layer a glassmorphic navbar using backdrop-filter:blur(16px) + background:rgba(255,255,255,0.08) + 1px border rgba(255,255,255,0.12). Use #283BD5 exclusively for CTAs and active nav states. Set headlines in a bold sans-serif at 48-56px white, stats at same size with 32px gap between items. Anchor the bottom with a white search card (border-radius:12px, box-shadow:0 8px 32px rgba(0,0,0,0.12)) containing a 4-column CSS Grid of filter inputs at 16px body text.

**Dev Recipe:** Next.js + Tailwind CSS with backdrop-filter utilities enabled. Use Framer Motion for stat counters (useInView trigger, spring animation from 0 to target). Key CSS: hero container with relative positioning, gradient overlay via before pseudo-element, search bar as sticky-bottom card with z-index layering above the blob decorations.

**Core Lesson:** Glassmorphic overlays on photography create instant premium feel, but only if you control the contrast between text and the variable image brightness beneath.

**Steal These:**
- Avatar stack + stat badge as social proof above the headline — immediate trust signal
- Glassmorphic navbar floating over hero photography — premium without heavy design
- Anchored search bar at hero bottom as primary CTA — captures intent immediately
- Three-stat row (quantity, money, satisfaction) as trust trifecta pattern
- Tab switcher (Buy/Rent/Sell) contextualizing the search before user interacts

**Weaknesses:** Display font kerning is broken ('Pro ject') across multiple case study slides — basic QA miss, Dark organic blob shapes in hero corners feel arbitrary and compete with the clean architectural photo, 1-week timeline claim for full UX research + design + testing undermines credibility of the case study narrative

---

### Score 5/10 — warm-minimal — Apartment and property booking marketplace

**Design Recipe:** Use #E8ECF8 lavender as hero card background on a cohesive soft gradient (not random photo). Set headlines in DM Sans Bold 56px #1A1A2E with one keyword in #8B92A8 lighter gray for emphasis. Build a horizontal search bar at 64px height, white bg, border-radius:32px, with 4 filter columns separated by 1px #E5E7EB dividers, each with 12px gray label + 16px semibold value. CTA buttons in #112594 pill shape. Float 2 small property preview cards (120x100px, border-radius:16px) at diagonal corners with 3° rotation. Keep decorative elements to max 2, purposeful ones only.

**Dev Recipe:** Next.js + Tailwind CSS with custom search bar component using flex layout and responsive collapse to stacked on mobile. Use Framer Motion for floating card entrance animations and Lucide icons for the filter bar. backdrop-filter:blur(12px) on the hero container card.

**Core Lesson:** A well-designed search/filter bar can anchor an entire hero section and communicate product value instantly.

**Steal These:**
- Horizontal search filter bar with icon + label + value pattern
- Trust badge pill above headline with star + number + text
- Lavender-blue hero background as alternative to white
- Floating contextual preview cards at hero edges for visual interest
- Single accent color (deep blue) reserved exclusively for actionable CTAs

**Weaknesses:** Copy-paste error 'Fertility Service' destroys credibility — always proof content, Blurred green nature background has no relationship to the lavender UI palette, Decorative sparkle stars are meaningless filler — remove or replace with purposeful elements

---

### Score 5/10 — dark-luxury — Curated luxury property marketplace

**Design Recipe:** Use #0A0A0D dark background with #FCFDFC white text and #9D8C66 desaturated gold as sole accent. Pair Playfair Display (bold, -0.5px tracking) for headlines with Inter (400, 16px) for body. Hero: full-bleed architectural photo with linear-gradient(to top, rgba(10,10,13,0.9), transparent) overlay. Section labels: 12px uppercase Inter, wide letter-spacing (3px), gold color with gold dot ::before. Cards: white bg, 12px radius, 1px #E5E5E5 border, 24px padding. Stats: 52px bold serif numbers in #CFC7AE with dashed gold bottom border. Max-width 1200px, 80px section padding.

**Dev Recipe:** Next.js 14 + Tailwind CSS with custom color tokens (dark: #0A0A0D, gold: #9D8C66, gold-light: #CFC7AE). Use next/image for property photos with priority loading on hero. Framer Motion for scroll-triggered section reveals with staggerChildren. Embla Carousel for testimonials.

**Core Lesson:** A luxury color palette cannot compensate for careless content — placeholder text and duplicate sections instantly destroy the premium illusion

**Steal These:**
- Desaturated gold (#9D8C66) instead of bright gold for luxury — avoids looking cheap
- Floating glassmorphic property card overlaying the hero image
- Uppercase wide-tracked section labels with dot prefix as wayfinding pattern
- Large low-opacity brand watermark in footer for brand reinforcement
- Numbered service cards with gold circle badges for visual scanning

**Weaknesses:** Placeholder body copy from a different industry (online courses) destroys credibility, Duplicate stats and identical service card text show lack of attention to detail, No interactive property search, filtering, or map — missing core real estate UX

---

### Score 5/10 — warm-minimal — Property search aggregator with verified listings

**Design Recipe:** Use #EBE5E6 warm off-white background, #0C0D0B near-black headings in Poppins Bold 52px, #B12E26 red accent on 1-2 words per heading and all CTAs. Pill-shaped buttons (border-radius:999px) at 44px height. Property cards on white with 16px radius and #C9B6B5 blush info strip at bottom. 12-col grid at 1200px max-width, 80px section gaps. Full-viewport hero with lifestyle photo, dark overlay at 40% opacity, left-aligned text, and a white pill search bar floating at bottom-left.

**Dev Recipe:** Next.js + Tailwind CSS with custom color tokens for the warm palette. Use Swiper.js for testimonial carousel, CSS transitions for accordion FAQ, and Framer Motion for scroll-triggered section reveals. Self-host Poppins via next/font.

**Core Lesson:** A warm neutral palette with a single bold accent color can carry an entire real estate brand — but only if content is real and differentiated

**Steal These:**
- Blush-pink (#C9B6B5) info strip on property cards — subtle warmth vs cold gray
- Red accent limited to exactly 1-2 words per section heading for rhythm
- Pill search bar floating over hero image — clear affordance
- Category pills (Rent/Buy/Sell) as tab-like filters above search
- Red circle icon containers for visual consistency across sections

**Weaknesses:** All placeholder data identical — destroys credibility and shows lack of content design thinking, No microinteractions or state design shown — hover, loading, empty states all missing, Hero image dark overlay makes text readable but kills the warm lifestyle mood the image was chosen for

---

## Slop Patterns to Avoid

### Score 5/10
- AI-generated billboard mockup in slide 2 — telltale smooth rendering and generic cityscape
- Generic social proof numbers (750+, 250M+, 99%) feel templated, not data-driven
- Case study structure is formulaic — Problem/Mission/Stats is a Behance template pattern
- Timeline Gantt chart is decorative, not informative — 1 week for full UX process is unrealistic
- Typography inconsistencies — 'Pro ject' has a visible kerning break in the display font across multiple slides

### Score 5/10
- Blurred green nature background feels like random stock photo, no brand connection
- Decorative sparkle/star elements are generic filler with no purpose
- Floating property card thumbnails at edges feel like template decoration
- Summer Sales '10% Off On Fertility Service' — obvious copy-paste error, zero QA
- Dashboard screen (image 3) is a completely different product/style, portfolio padding

### Score 5/10
- Generic stock AI-rendered luxury homes with identical lighting
- Body copy is placeholder — 'Learn highly demanded skills through practical online courses' on a real estate site
- Stats section repeats '120+ Customer satisfaction' twice — copy-paste error
- Services section uses identical 'Property Buying' text for all 4 cards
- Flight booking app included as image 4 — completely unrelated project bundled together

### Score 5/10
- All property cards use identical placeholder data ($67000, SunnyMountain, Downtown New York)
- Generic stock photos throughout service cards
- Repetitive testimonial content with same 4.5 ratings
- No unique visual identity — follows common Dribbble real estate template patterns
- Search bar is decorative, no real interaction design thought
