# Food — Design Playbook

**14 projects analyzed | 6 scored 7+ | Avg: 6.1/10**

## Category Overview

**Aesthetics that work:** warm-minimal (4), dark-luxury (2), organic-natural (2), retro-modern (2), minimal-corporate (1)
**Color strategy:** neutral-plus-accent (10), analogous (2), monochromatic (1), dark-theme (1)
**Color mode:** light (8), mixed (4), dark (2)
**Hero patterns:** left-right (3), centered (3), layered (3), split-50-50 (3)
**Frameworks:** HTML or Webflow (3), React or Next.js (3), React (2), Tilda (1)
**Animation:** CSS-only (3), GSAP or Framer-Motion (3), CSS-only or GSAP (2)
**Heading fonts:** Playfair Display or similar transitional serif (2), Playfair Display or similar serif (2), Playfair Display or similar high-contrast serif (1), Custom geometric display (1)
**Body fonts:** Inter or similar geometric sans-serif (4), Same family lighter weight for 'JAPANESE' subhead and 'KARA TORI' (1), Light-weight sans-serif, possibly Montserrat or Lato (1), Roboto (1)

## Color Rules

- **[9]** Orange used in exactly 2 of 12 tiles — ~16% presence, maximum impact through scarcity
- **[8]** Gold/amber used only for interactive elements (CTA, arrows) and the wooden tray — creates clear action hierarchy
- **[8]** Burnt sienna used only for CTAs and section labels — max 3-4 instances per viewport
- **[7]** Gold used exclusively for interactive elements, cultural symbols, and section dividers — never as background fill
- **[7]** Orange used for primary actions and hero headline only — disciplined
- **[7]** Lime gradient confined to bottom 25% of card as action zone only

### Color Craft Insights
- **[9]** The palette is literally derived from coffee — black (espresso), browns (beans), beige (crema), cream (milk), orange (heat) — every color has a semantic reason to exist
- **[8]** The seigaiha wave pattern at ~5% opacity on the red creates texture without competing with food photography — masterful restraint
- **[8]** The two-tone background (white left / cream right) in the hero creates depth without any shadows or gradients — pure color field separation
- **[7]** The gold palette maps to actual autumn leaf colors (紅葉/kōyō), making the brand color semantically meaningful rather than arbitrary luxury gold
- **[7]** The cream-to-black section transitions via organic wave shapes create a visual 'scoop' metaphor — the palette literally tastes like chocolate and vanilla
- **[7]** The gradient doesn't just decorate — it functionally separates read-zone from act-zone, a smart UX decision

## Color Palettes

### Specialty cafe brand identity with brutalist typography system Example (neutral-plus-accent / mixed)
- `#0B0805` — **text-primary** — Maximum contrast and authority — anchors the brutalist aesthetic
- `#FDF2EB` — **bg-primary** — Warm off-white evokes parchment/cream — softer than pure white, coffee-adjacent warmth
- `#F41B00` — **accent-cta** — High-energy signal color — draws eye to key data points, evokes heat/espresso crema
- `#634940` — **surface-card** — Coffee-bean brown — grounds the palette in the product itself
- `#A48E7C` — **surface-secondary** — Transitional tone between dark and light — adds depth without competing
- `#AAA394` — **surface-tertiary** — Neutral breathing room in the grid composition
- `#D9C4B3` — **decorative** — Latte-milk tone — literal color reference to the product
- `#B24A33` — **accent-secondary** — Earthier variant of the accent — adds sophistication to the orange

### Japanese ramen restaurant e-commerce landing page Example (analogous / dark)
- `#8B1A1A` — **bg-primary** — Deep crimson evokes Japanese lacquerware, appetite stimulation, and cultural authenticity
- `#5F2F23` — **bg-secondary** — Adds depth and grounds the composition in warmth
- `#A4330B` — **decorative** — Bridges the deep red and warm amber tones
- `#A68759` — **accent-cta** — Warm gold/amber contrasts red, suggests premium quality and warmth
- `#F1F0EB` — **text-primary** — Off-white avoids harsh contrast, feels warmer than pure white
- `#000000` — **surface-card** — Anchors the dimensional elements and creates depth

### Michelin-star fine dining restaurant with halal focus Example (neutral-plus-accent / light)
- `#120906` — **text-primary** — Near-black with warm brown undertone avoids harsh contrast, feels organic
- `#A0592D` — **accent-cta** — Burnt sienna evokes warmth, spice, earthiness — perfect for terroir concept
- `#F7F5F1` — **bg-primary** — Warm off-white mimics aged paper, elevates editorial feel
- `#FFFFFF` — **surface-card** — Pure white creates subtle depth contrast against cream
- `#D0BDA7` — **decorative** — Warm taupe bridges the cream and brown palette
- `#5D4234` — **text-secondary** — Dark brown for secondary hierarchy without black harshness
- `#C19860` — **decorative** — Gold-brown signals luxury without being gaudy
- `#E8E5E1` — **border** — Barely-there lines create structure without visual weight

### Luxury Japanese fine dining restaurant with chef's table and private dining Example (neutral-plus-accent / mixed)
- `#060403` — **bg-primary** — Deep near-black creates luxury atmosphere and makes gold pop dramatically
- `#BA8F46` — **accent-cta** — Gold connotes premium quality and Japanese autumn leaves (kōyō meaning)
- `#E4E3E4` — **text-primary-light** — Warm off-white avoids harsh contrast while maintaining readability
- `#FFFFFF` — **bg-secondary** — Creates breathing room and contrast rhythm between dark sections
- `#4C341A` — **surface-card** — Warm brown bridges black and gold, adds depth to dark sections
- `#996819` — **accent-secondary** — Darker gold for depth and interactive state differentiation

### DTC artisan ice cream e-commerce Example (neutral-plus-accent / mixed)
- `#F1E9D5` — **bg-primary** — Warm cream evokes vanilla/dairy, feels nostalgic and appetizing
- `#070505` — **bg-secondary** — Maximum contrast against cream, creates dramatic section breaks
- `#F2961F` — **accent-cta** — Orange triggers appetite and energy — classic food marketing psychology
- `#C07791` — **decorative** — Adds playful femininity and variety to the warm palette
- `#5F2A1F` — **text-secondary** — Chocolate brown reinforces ice cream theme while maintaining readability
- `#FC2807` — **decorative** — Cherry-red accent adds energy and mimics sauce/topping

### Restaurant order management POS card component Example (neutral-plus-accent / light)
- `#FFFFFF` — **bg-primary** — Clean canvas for data-heavy content
- `#080808` — **text-primary** — Maximum readability for kitchen staff scanning quickly
- `#A9D23C` — **accent-cta** — Fresh, energetic lime signals action readiness and food freshness
- `#E1F4A2` — **surface-card** — Softens the lime accent into a gradient zone
- `#AAAAA9` — **text-secondary** — De-emphasizes metadata without hiding it
- `#E86830` — **decorative** — Orange signals urgency/attention for pending status
- `#E85050` — **decorative** — Red for high priority — universal urgency signal
- `#51643C` — **surface-card** — Muted olive de-emphasizes destructive action

## Typography

- **[9] Custom serif — likely a modified Noe Dis + Monospaced system font for dat**: High-contrast serif for emotional impact paired with monospace for technical data creates the tension between ritual and precision that defines the brand.
- **[8] Custom geometric display — Japanese-insp + Same family lighter weight for**: Single typeface family maintains cultural cohesion; geometric angles echo Japanese calligraphy strokes translated to Latin letterforms
- **[8] Playfair Display or similar transitional + Inter or similar geometric san**: High-contrast serif for editorial gravitas paired with clean sans for modern readability — classic luxury editorial formula
- **[7] Playfair Display or similar high-contras + Inter or similar geometric san**: High-contrast serif for elegance and editorial authority paired with clean sans for modern readability — mirrors the 'modern Japanese' brand positioning
- **[7] Custom retro display — likely Groovy or  + Serif — likely a transitional **: Groovy display for emotional punch paired with readable serif for credibility — retro meets editorial
- **[7] Inter or SF Pro — geometric sans-serif + Monospace for labels (likely S**: Monospace labels evoke receipt/ticket authenticity while sans-serif items stay readable at speed

### Typography Effects
- **[9]** Oversized type cropped by tile edges — overflow:hidden on grid cells
- **[9]** Mixed serif + monospace within single compositions — CSS font-family switching per span
- **[9]** Registered trademark ® and ™ symbols used as design elements at display scale
- **[9]** Italic serif in Hapr mockup — elegant contrast to the brutalist specimen tiles
- **[8]** Headline has subtle text-shadow for depth against busy food imagery
- **[8]** Letters have custom ligatures — the 'M' in RAMEN has a torii-gate-inspired crossbar
- **[8]** Slight 3D/emboss effect on headline via layered shadows
- **[8]** Old-style numerals in stat figures — font-feature-settings: 'onum'
- **[8]** Em-dash decorative line before labels — pseudo-element with border-top
- **[7]** Kanji watermark (紅葉) at ~200px behind hero text — opacity ~0.3, gold fill, likely positioned absolute with z-index layering

## Hero Patterns

- **[9] full-bleed** (Specialty cafe brand identity with brutalist typog): Top-left INTERVAL logo → center headline → CTA button → bottom contact bar
- **[8] layered** (Japanese ramen restaurant e-commerce landing page): KAISEN RAMEN title → center ramen bowl → KARA TORI label → BUY NOW CTA → flanking bowls
- **[8] split-50-50** (Michelin-star fine dining restaurant with halal fo): Food photo → 'TWO MICHELIN STARS' label → 'Obsession, Plated.' headline → body copy
- **[7] centered** (Luxury Japanese fine dining restaurant with chef's): Kanji watermark → KŌYŌ logo → tagline → CTA button
- **[7] centered** (DTC artisan ice cream e-commerce): HAPPINESS headline → IN EVERY BITE → subtext → SHOP NOW CTA → character cards below
- **[7] n/a** (Restaurant order management POS card component): Avatar→Name→Pending badge→Line items→Total→Start Preparing CTA

## Card & Component Patterns

- **[9]** Modular color-blocked tiles — 0px radius, ~20-32px internal padding, no hover effect (static specimen), flush grid layout
- **[8]** Stat cards in 2x2 bento grid, hairline 1px borders, ~40px padding, no radius, no shadow, no hover — pure editorial
- **[7]** Dark cards with ~12px radius, ~24px padding, subtle border or shadow, image top + text bottom layout, hover likely slight lift with box-shadow
- **[7]** Rounded-16px cards with colored backgrounds (yellow/pink/orange), phone-frame mockup style in hero, product cards with image + text + CTA in grid section, ~16px padding
- **[7]** White card, border-radius ~20px, padding ~24px, box-shadow soft, gradient bottom section with overflow hidden

### Buttons

- **primary / pill**: `border-radius:24px; background:#4A4AE8 (Chumakov) or #634940 (Hapr)`
- **secondary / rounded-8**: `border:1px solid; background:transparent`
- **primary / pill**: `border-radius:24px; background:#A68759; text-transform:uppercase`
- **ghost / square**: `border:2px solid rgba(255,255,255,0.3); backdrop-filter:blur`
- **primary / rounded-4**: `background-color with transition`
- **ghost / rounded-4**: `border 1px solid with hover background`
- **primary / rounded-4**: `background: #BA8F46; color: #060403; font-weight: 600`
- **secondary / rounded-4**: `border: 1px solid #BA8F46; color: #BA8F46`
- **ghost / rounded-4**: `border: 1px solid rgba(255,255,255,0.3)`
- **primary / rounded-8**: `background-color:#F2961F; border:2px solid #070505; border-radius:8px; text-transform:uppercase; font-weight:600`
- **secondary / rounded-8**: `background with semi-transparent olive overlay on gradient`
- **primary / pill**: `background: #1A1A1A, border-radius: 24px, white text`

## Animation & Interaction

- **[9]** Tile hover-reveal of micro-data labels → CSS opacity transition
- **[9]** Scroll-triggered tile entrance animations → GSAP stagger or Framer Motion
- **[9]** Hero parallax on applied mockup pages → CSS transform:translateY with scroll listener
- **[9]** Nav background blur on scroll → backdrop-filter:blur with scroll threshold
- **[8]** Carousel arrows suggest horizontal product slider — Framer-Motion or GSAP
- **[8]** Entrance animation: bowls slide/scale in from edges with stagger — GSAP timeline
- **[8]** Headline likely animates letter-by-letter or with clip-path reveal — GSAP SplitText
- **[8]** Parallax depth on scroll — bowls at different scroll speeds — GSAP ScrollTrigger
- **[8]** Hover on CTA: scale + warm glow box-shadow — CSS transition
- **[8]** Scroll-triggered section fade-in → Intersection Observer or Framer Motion whileInView
- **[8]** Nav link hover underline → CSS border-bottom transition
- **[8]** CTA button hover darken → CSS background-color transition 200ms
- **[8]** Form input focus → border-bottom color change transition
- **[8]** Image hover subtle scale → CSS transform: scale(1.02) with overflow:hidden on parent
- **[7]** scroll-fade-in sections → Framer-Motion or Intersection Observer
- **[7]** hero-parallax background image → transform: translateY with scroll listener
- **[7]** nav-darken-on-scroll → classList toggle with scroll threshold
- **[7]** button-hover-fill → transition: background-color 0.3s ease
- **[7]** card-hover-lift → transform: translateY(-4px) + box-shadow transition
- **[7]** Card carousel horizontal scroll → scroll-snap or Swiper.js
- **[7]** Wavy section reveal on scroll → GSAP ScrollTrigger or Intersection Observer
- **[7]** CTA button hover state → background darken + subtle scale transform
- **[7]** Navigation arrow click → carousel slide transition
- **[7]** Splash elements parallax on scroll → transform:translateY with scroll listener
- **[7]** Card hover lift → transform: translateY(-2px) + shadow increase, CSS transition
- **[7]** Button press → scale(0.97) active state, CSS
- **[7]** Status badge pulse → animation on the orange dot, CSS keyframes

## Decorative Elements

- **color-blocked tiles** at Typography specimen grid: `CSS Grid with background-color per cell`
- **dark overlay on hero image** at Chumakov mockup: `background: linear-gradient or rgba overlay`
- **warm vignette** at Hapr mockup edges: `radial-gradient or box-shadow:inset`
- **seigaiha-wave-pattern** at Full background overlay: `background-image repeating SVG pattern at low opacity`
- **wooden-boat-tray** at Behind center bowl, curving upward: `Positioned PNG/WebP with z-index layering`
- **chopsticks** at Bottom-left and bottom-right: `Absolute positioned, rotated via transform:rotate()`
- **chili-peppers** at Bottom-right decorative: `Absolute positioned PNG`
- **grilled-meat** at Bottom-left decorative: `Absolute positioned PNG`
- **radial-vignette** at Background edges: `radial-gradient overlay darkening edges`
- **hairline-borders** at Grid cell divisions throughout entire layout: `border: 1px solid with low-opacity color`
- **em-dash-line** at Before section labels like 'TWO MICHELIN STARS': `::before pseudo-element with width + border-top`
- **dual-background** at Hero split — white left, cream right: `CSS Grid with different background-color per cell`
- **kanji-watermark** at Hero center, behind logo: `position: absolute; opacity: 0.3; font-size: ~200px; color: #BA8F46; z-index: 0`
- **dark-vignette** at Hero image overlay: `background: radial-gradient(ellipse, transparent 30%, rgba(0,0,0,0.7) 100%)`
- **faded-kanji-bg** at Reservation section right side: `opacity: 0.05; position: absolute; right: 0`
- **warm-spotlight** at Mockup presentation image: `radial-gradient warm light from top`
- **liquid-splash** at Hero top-center (red), hero left (caramel), hero right (chocolate): `position:absolute with PNG/SVG overlays, z-index layering`
- **wavy-divider** at Between hero and dark section, between dark and cream sections: `SVG path or clip-path:polygon with custom bezier curves`
- **watermark-text** at Behind character card photos: `position:absolute; opacity:0.15; font-size:oversized; z-index:0`
- **dashed-dividers** at Between header/meta, meta/items, items/total: `border-style: dashed; border-color with low opacity`
- **gradient-zone** at Bottom 30% of card: `linear-gradient(to bottom, transparent, #E1F4A2, #A9D23C)`
- **dot-grid-background** at Page background behind card: `radial-gradient repeating pattern or SVG background-image`

## Design Recipes

### Score 9/10 — neo-brutalist — Specialty cafe brand identity with brutalist typography syst

**Design Recipe:** Use a high-contrast transitional serif (Noe Display or Freight Display Bold) in ALL CAPS at 80-120px for headlines on a 3-column flush grid. Background palette: #0B0805 black, #FDF2EB warm cream, #634940 coffee brown, #AAA394 warm gray, #F41B00 pure orange-red used on max 15% of surfaces. Set data/labels in 7-9px uppercase monospace (GT America Mono) with wide letter-spacing. Internal tile padding 24-32px. Zero border-radius everywhere. Let type overflow and crop at tile edges. Every color must reference coffee: black=espresso, brown=bean, cream=milk, orange=heat.

**Dev Recipe:** CSS Grid with grid-template-columns: repeat(3, 1fr) and gap:0 for the specimen layout. Self-host display serif + monospace fonts. Use CSS custom properties for the 5-color token system. Overflow:hidden on each grid cell enables the cropped-type effect. For applied hero pages, use object-fit:cover with a linear-gradient overlay.

**Core Lesson:** Constraint breeds distinction — limiting yourself to uppercase type, a 3-column grid, and 5 earth tones forces every decision to carry maximum weight.

**Steal These:**
- Using product parameters (ratios, temps, times) as typographic content — turns data into design
- Flush modular grid with zero gaps — tiles feel like a unified system, not separate cards
- Single accent color (orange) used at <20% frequency for maximum visual punch
- Mixing serif display type with monospace data labels within one composition
- Micro-captions at 7-9px as compositional texture — not meant to be read, meant to be felt

**Weaknesses:** Applied mockups (Chumakov, Hapr) feel like generic portfolio padding — they don't showcase the INTERVAL identity itself in real contexts like packaging, signage, or menu design, Micro-caption text at 7-9px is illegible and purely decorative — could carry meaningful brand information instead, No demonstration of the identity at smaller scales (mobile, social, app icon) — unclear how the system scales down

---

### Score 8/10 — dimensional-layered — Japanese ramen restaurant e-commerce landing page

**Design Recipe:** Use deep crimson #8B1A1A background with seigaiha wave SVG pattern at 5-8% opacity. Apply radial vignette darkening edges to #3A1010. Set a custom geometric Japanese-inspired display font at 120px/900-weight in #F1F0EB for the hero title. Layer 5+ z-index planes: background → wooden tray prop (curved, warm #A68759 tones) → flanking product bowls at 30% scale → hero bowl at 60% scale centered → text overlay → decorative props (chopsticks rotated ±30deg, chili peppers). CTA is pill-shaped #A68759 solid fill with uppercase text. Keep nav to two corner icons in subtle bordered squares.

**Dev Recipe:** Next.js + GSAP (ScrollTrigger + SplitText) for motion orchestration. Use absolute positioning within a relative full-viewport container for the layered composition. Self-host the display font, use CSS custom properties for the red palette, and implement the seigaiha as an inline SVG pattern-fill at low opacity. Responsive strategy: completely restructure to vertical stack on mobile with reduced prop elements.

**Core Lesson:** Dimensional layering of real product photography with cultural texture patterns creates immersive food experiences that flat layouts cannot achieve

**Steal These:**
- Seigaiha wave pattern as subtle cultural texture on solid color backgrounds
- Curved wooden tray as a compositional device creating depth behind the hero product
- Japanese-inspired geometric Latin letterforms with torii-gate-style crossbars
- Asymmetric prop placement (chopsticks, chilies) to break rigid symmetry
- Gold/amber #A68759 as the sole interactive color against deep red — instant CTA visibility

**Weaknesses:** Responsive breakpoints will be painful — this layout essentially needs a mobile-specific redesign, not just reflow, Text over busy food photography could have legibility issues without careful shadow/overlay management, Only hero section visible — unclear if the dimensional approach sustains through a full page scroll

---

### Score 8/10 — editorial — Michelin-star fine dining restaurant with halal focus

**Design Recipe:** Use #F7F5F1 warm cream and #FFFFFF white as alternating bento cell backgrounds on a CSS Grid with 1px #E8E5E1 borders. Set Playfair Display at 64px regular weight for h1 with -0.02em letter-spacing, pair with a geometric sans at 11px uppercase 0.15em tracking for labels. Apply #A0592D burnt sienna ONLY to CTA text and section label accents. Maintain 80-100px section padding, 60ch max body width, and use old-style numerals (font-feature-settings: 'onum') for all stat figures.

**Dev Recipe:** Next.js + Tailwind CSS with CSS Grid for bento layouts using grid-template-areas. Use Framer Motion for scroll-triggered fade-ins with staggerChildren. Self-host Playfair Display and Inter, enable OpenType features via @font-face descriptors.

**Core Lesson:** Restraint IS luxury — hairline borders and whitespace communicate more exclusivity than any gradient or animation ever could.

**Steal These:**
- Em-dash prefix before uppercase section labels as a wayfinding device
- 2x2 stat grid with old-style numerals and uppercase spaced captions
- Dual-tone bento cells (white vs cream) for hierarchy without shadows
- Beverage menu as horizontal ruled list with serif item names and right-aligned prices
- B&W team portraits with script-style name labels underneath

**Weaknesses:** Headphone image in team section is clearly placeholder stock — breaks the otherwise cohesive food narrative, No visible hover states or interaction cues in the static comp — could feel dead in production, Mobile version loses the bento grid magic and becomes a standard single-column stack

---

### Score 7/10 — dark-luxury — Luxury Japanese fine dining restaurant with chef's table and

**Design Recipe:** Use #060403 dark background with #BA8F46 gold accent at 15% usage ratio. Pair Playfair Display Bold for headings with Inter Regular for body at 16px/1.6. Alternate sections between dark (#060403) and white (#FFFFFF) backgrounds at 100px vertical padding. Place a large cultural watermark element at 30% opacity behind hero text using absolute positioning. All CTAs are solid gold (#BA8F46) with dark text, 44px height, 4px border-radius, 0.3em letter-spacing on uppercase labels. Cards use 12px radius with 24px internal padding on dark surfaces.

**Dev Recipe:** React + Tailwind CSS with CSS custom properties for the dark/light section theming. Use Framer Motion for scroll-triggered section reveals and GSAP ScrollTrigger for hero parallax. Self-host Playfair Display and Inter, implement the reservation form with React Hook Form + a date picker like react-day-picker styled to match the gold accent system.

**Core Lesson:** Cultural authenticity in decorative elements (meaningful kanji, semantically-linked color palette) transforms generic luxury into genuine brand identity.

**Steal These:**
- Kanji watermark behind hero text for cultural depth without clutter
- Gold accent used ONLY for interactive elements and cultural symbols — never decorative fill
- Alternating dark/light section rhythm that prevents visual fatigue
- Uppercase wide-tracked tagline beneath logo for premium positioning
- Faded cultural symbol repeated in reservation section background for visual continuity

**Weaknesses:** Dark-gold luxury restaurant aesthetic is well-trodden territory — risks feeling like a premium template, Body text on dark sections could benefit from slightly larger size (16px+) for accessibility, The long single-page scroll with 9+ sections may cause engagement drop-off — consider multi-page architecture for production

---

### Score 7/10 — retro-modern — DTC artisan ice cream e-commerce

**Design Recipe:** Use #F1E9D5 cream background with #070505 dark sections separated by organic SVG wave dividers. Set hero headline in a heavy 70s-style display font (try 'Oleo Script Swash Caps' or 'Lobster Two') at 100-120px in #F2961F orange for line 1 and #070505 black for line 2, both uppercase. Cards use 16px border-radius with solid color fills (#F2961F yellow, #C07791 pink, #F2961F orange). CTA buttons are #F2961F with 2px dark border and 8px radius. Add liquid splash PNGs (caramel, chocolate, berry) as absolute-positioned decorative elements at hero edges. Body text in a transitional serif at 16px in #5F2A1F.

**Dev Recipe:** Build with Next.js + Tailwind CSS, use Swiper.js for the card carousel, inline SVGs for wavy section dividers with viewBox manipulation, and GSAP ScrollTrigger for parallax splash elements. Self-host the retro display font and use CSS scroll-snap as a fallback for the carousel.

**Core Lesson:** A bold retro display font paired with a disciplined 3-color palette (cream/black/orange) can carry an entire brand identity without needing complex layouts

**Steal These:**
- Two-tone headline technique: first line in accent color, second line in black — instant hierarchy
- Organic wave dividers between contrasting sections instead of hard edges
- Liquid splash photography as decorative framing elements
- Color-coded card system where each card color maps to an emotion word
- Watermark oversized text behind photos for layered depth

**Weaknesses:** AI-generated people photos are detectable and reduce brand authenticity — use real photography, Lower page sections (product grid, testimonial) feel less polished than the hero — inconsistent craft level, Footer is generic and doesn't carry the retro personality established above

---

### Score 7/10 — warm-minimal — Restaurant order management POS card component

**Design Recipe:** White card (#FFFFFF) with 20px border-radius and soft shadow on a dot-grid background (#E8E8E8 dots on #F0F0F0). Use Inter Bold 24px for names, monospace uppercase 12px letter-spacing:2px for labels (TABLE NO, PRIORITY, TOTAL). Dashed dividers at #DEDEDD. Orange (#E86830) for status badges with 1.5px border and dot indicator. Bottom 30% fades via linear-gradient from white through #E1F4A2 to #A9D23C. Primary CTA is #1A1A1A pill button, secondary is semi-transparent olive (#51643C at 60% opacity) rounded button. Line items use flexbox with quantity, name, and right-aligned price.

**Dev Recipe:** React + Tailwind. Build as a single OrderCard component with props for customer, items, status, priority. Use bg-gradient-to-b for the footer zone, border-dashed for dividers, and a simple flex layout for line items. Avatar with rounded-lg overflow-hidden.

**Core Lesson:** Use color zones (gradient transitions) to functionally separate information from action areas within a single card

**Steal These:**
- Gradient action zone separating data from buttons
- Monospace uppercase labels for receipt authenticity
- Dashed dividers mimicking real ticket paper
- Orange dot + border status badge pattern
- Muted olive for secondary/destructive button to de-emphasize it

**Weaknesses:** Cancel Order button blends into gradient — needs more visual distinction for a destructive action, TABLE NO: 00 is placeholder data that undermines the presentation, The HR SaaS landing page (image 4) is completely unrelated and confuses the project narrative

---

### Score 6/10 — dark-luxury — Upscale cocktail bar and European restaurant

**Design Recipe:** Use #02070C pure black background with #E8E4D8 warm cream text (never pure white). Set headlines in Playfair Display Bold at 64-72px with tight tracking, uppercase. CTA buttons in #2D5A3D forest green, 48px height, 14px uppercase letter-spacing:3px. Split hero 50/50 with dramatically lit food photography. Break monotony with a full-width #1A3A2A green section featuring single-weight cream line illustrations at corners. Keep nav to logo + 2 text links max.

**Dev Recipe:** Build with Astro or Next.js for static speed. Use Tailwind with dark theme defaults, Google Fonts Playfair Display + Inter. Key CSS: full-viewport hero with object-fit:cover, absolute-positioned SVG decorative illustrations, section background-color transitions.

**Core Lesson:** Dark luxury food sites live or die by photo quality and color restraint — two colors max, let the food do the talking

**Steal These:**
- Warm cream (#E8E4D8) instead of white on dark backgrounds
- Italic ampersand as typographic personality in logo
- Forest green CTA section as dramatic palette break from black
- Hand-drawn line illustrations as decorative texture on solid color
- Minimal nav with language toggle — just 2 text links

**Weaknesses:** Hero layout is generic 50/50 split — no spatial tension or asymmetry, Only two sections visible — needs more content depth to feel like a real site, CTA consultation section feels like designer self-promo, not restaurant content — breaks immersion

---

### Score 6/10 — organic-natural — Artisanal coffee brand e-commerce and café website

**Design Recipe:** Use #f5f2eb warm off-white background, #3e2312 espresso brown for headings and nav, #dfcebe latte for buttons and accents, #000000 for alternating dark sections. Set Notable (Google Fonts) for H1-H2 at 48-96px uppercase with letter-spacing:0.15em. Use Yanone Kaffeesatz for subheads at 24-32px. Roboto 16px/1.6 for body. Create hero with stacked text: first line solid fill, subsequent lines -webkit-text-stroke:2px #3e2312 with color:transparent, decreasing opacity 0.6→0.3. Scatter 15-20 coffee bean SVGs with position:absolute and random rotations. Alternate sections between light (#f5f2eb) and dark (#000) backgrounds with 100px vertical padding. Buttons: #dfcebe fill, 12px uppercase text, 4px radius, 40px height.

**Dev Recipe:** Build with Next.js or Astro for static generation. Use Tailwind with custom color tokens (espresso, latte, parchment, charcoal). Google Fonts for Notable + Yanone Kaffeesatz + Roboto. GSAP ScrollTrigger for section reveals and bean parallax. SVG sprites for bean decorations positioned with absolute/random transforms.

**Core Lesson:** A restricted earth-tone palette drawn from the product itself creates instant brand recognition without needing a single logo.

**Steal These:**
- Stacked fill→outline→ghost text cascade for hero typographic depth
- Entire color palette derived from the product itself (espresso, latte, cream, parchment)
- Scattered thematic SVG decorations (beans) creating organic texture on clean backgrounds
- Dark/light section alternation creating visual rhythm and content hierarchy
- Dashed-border stitching detail on promotional banner adding tactile craft feel

**Weaknesses:** Body text too small in several areas (12-14px) — hurts readability and accessibility, Layout is conventional vertical stack with no asymmetry or spatial surprise, Blog cards and product cards share nearly identical structure — needs more component differentiation

---

### Score 6/10 — retro-modern — Street food truck single-page website

**Design Recipe:** Use #F5E6C8 cream background with #E8960A mustard-orange CTAs and #3D2066 deep purple contrast sections. Set headlines in Luckiest Guy (Google Fonts) with white text-stroke outlines, body in Inter 16px. Create retro concentric arc decorations using nested divs with border-radius in red (#D9470D), orange (#F4A623), and yellow (#E8960A) at ~40px stroke width. Add wavy SVG dividers between sections. Use a subtle repeating food-icon SVG pattern at 5% opacity on the background. Polaroid-style image cards with 8px white border and 2-5deg rotation. Section spacing ~80px.

**Dev Recipe:** Build in Astro or Next.js with Tailwind for utility classes plus custom CSS for the retro stripe arcs (nested absolutely-positioned divs with border-radius) and SVG wave dividers. Use GSAP ScrollTrigger for section reveals and CSS keyframe animation for the sponsor ticker marquee.

**Core Lesson:** A committed decorative motif (retro stripes) repeated consistently across sections can create a strong brand identity even with simple layouts

**Steal These:**
- Retro concentric stripe arcs as corner decorations — instant personality
- Orange highlight block behind key text with slight rotation for emphasis
- Purple sections breaking up warm cream creates dramatic rhythm
- Polaroid-style tilted photo cards for gallery sections
- Food icon line-art as subtle repeating background texture

**Weaknesses:** Stock photos undermine the brand — needs real food truck photography, Case study presentation images (hatched clouds, process diagram) feel disconnected from the actual web design, Spacing and alignment inconsistencies between sections — some areas feel cramped while others are loose

---

### Score 5/10 — organic-natural — Online food delivery ordering platform

**Design Recipe:** Use #014420 deep green as sole accent on white #F2F8F6 background. Pair Playfair Display italic serif (56px hero, 36px sections) with Inter/Poppins 14-16px body. Pill-shaped CTAs at 44px height with full border-radius. 12px radius white cards with subtle 4px box-shadow. 80-100px section spacing. Hero is 60/40 split with text left, cutout photo right, 2-3 floating badge cards positioned absolutely. Category navigation as horizontal pill tabs. Food photography should be warm-toned on dark wooden surfaces.

**Dev Recipe:** Next.js + Tailwind CSS with custom green color tokens. Swiper.js for menu card carousel, Framer Motion for scroll-triggered fade-ins. PNG cutout hero image with absolute-positioned floating card components.

**Core Lesson:** A strong single-color identity (deep green) can carry an entire food brand when paired with warm photography and clean whitespace.

**Steal These:**
- Deep forest green as single brand color across all interactive elements
- Floating UI cards in hero to show product features contextually
- Avatar stack with 'Our Foodies' social proof in hero
- Category pill tabs with icon + label for menu filtering
- Phone mockup in CTA section showing actual app interface

**Weaknesses:** Lorem ipsum everywhere destroys credibility — always use realistic copy, Hero woman stock photo is overused in food delivery designs — use brand photography or illustration, Body text too small and too gray — increase to 16px minimum with darker color for accessibility

---

### Score 5/10 — warm-minimal — Grocery delivery & shopping list management app

**Design Recipe:** Use #FAFAF8 warm white background, #CB4E1C orange for all CTAs and active states, #291B0F warm brown for text, #72B958 green for health/fresh indicators. Set headings in SF Pro Display Bold at 28/22/18px scale, body at 15px regular. Cards get 16px border-radius, 16px padding, warm shadow (0 4px 12px rgba(41,27,15,0.08)). Category chips are pill-shaped with 20px radius, 36px height, 1px gray border inactive, solid orange active. Bottom tab bar uses 4 icons at 24px with orange fill for active state. Promotional banners use golden-yellow (#D4C14E) backgrounds with 20px radius.

**Dev Recipe:** React Native with Expo, using react-native-reanimated for micro-interactions, @shopify/flash-list for product grids, react-native-snap-carousel for banners. Style with NativeWind (Tailwind for RN) using a warm color token system.

**Core Lesson:** Commit to ONE concept and execute it deeply — four shallow explorations are worth less than one polished, complete app flow.

**Steal These:**
- Orange-only accent rule — every interactive element shares one warm orange, creating instant learnability
- Promotional banner carousel with rounded corners and golden-yellow background for deals
- Shopping list cards with colored left-edge backgrounds (green, peach, mint) for visual categorization
- Product card layout with rating badge top-right, price bottom-left, add-button bottom-right
- Category chips with icon prefix for scannable horizontal browsing

**Weaknesses:** Four unrelated app domains in one project destroys portfolio credibility — pick one and go deep, Stock photography with no consistent treatment or color grading — images feel randomly sourced, The skincare and basketball screens share orange accent but nothing else — no design system coherence

---

### Score 5/10 — warm-minimal — Restaurant aggregator food delivery platform

**Design Recipe:** Use Playfair Display Bold at 56px for hero headlines on a warm off-white (#FBF5F6) background. Hero section gets a radial gradient from #F2B031 center to #FBF5F6 edges. Primary CTA is #D13E28 pill buttons, nav CTA is #150D0B pill. Three-column how-it-works cards use progressive warm fills: #F7E44D (yellow), #F5A66B (orange), #F2BDD4 (pink), each with 16px radius and a right-aligned 32px black icon. Body text in Inter 16px #150D0B. Restaurant cards are white with 12px radius, image-top layout, cuisine tags as small pills below image. Maintain 80px section gaps and 1200px max-width container with a subtle 40px-blur box-shadow wrapper.

**Dev Recipe:** Next.js + Tailwind CSS with custom color tokens for the warm palette. Use Swiper.js for testimonial carousel, CSS Grid auto-fit for restaurant cards, and position absolute for hero image overlap. Google Fonts for Playfair Display + Inter.

**Core Lesson:** Warm color temperature (golden yellows, soft pinks) instantly makes food-related designs feel appetizing — temperature matters more than hue.

**Steal These:**
- Golden radial gradient hero background for food/warmth associations
- Progressive warm color coding for sequential step cards (yellow→orange→pink)
- Serif headlines + sans body pairing to elevate a commodity service
- Red CTA on warm yellow background creates strong but harmonious contrast
- Content wrapper with subtle box-shadow creates page-within-page depth

**Weaknesses:** Copy-paste error: step cards 1 and 3 have identical body text — destroys credibility, Hero stock photo is generic and used across hundreds of food delivery concepts, No micro-interactions, empty states, or loading patterns shown — feels static and incomplete

---

### Score 4/10 — warm-minimal — Premium specialty coffee brand e-commerce landing page

**Design Recipe:** Use #F5E6D3 cream background, #532617 dark brown for headings in Playfair Display Bold at 36px, #9C603C for solid CTA buttons with 8px radius. Body text in Inter Regular 14px #605650. Hero is 60/40 split with text-left, product-image-right using transparent PNG cutouts. Product cards are white (#FFF) with 12px radius, 16px padding, subtle shadow. Section spacing 80px. Services use 3-column icon grid with outline illustrations.

**Dev Recipe:** Build with Next.js or plain HTML + Tailwind CSS for rapid prototyping. Use Google Fonts (Playfair Display + Inter), position:absolute for decorative bean elements, CSS Grid for product cards and testimonials, flexbox for hero split layout.

**Core Lesson:** A monochromatic warm palette can carry a food/beverage brand, but you need at least one surprise element to avoid looking like a template.

**Steal These:**
- Monochromatic brown palette mapped directly to product color
- Transparent PNG product hero image floating over solid background
- Outline icon style for services matching the brand warmth
- Login outline + Signup filled button pairing in nav
- Cream background instead of white for warmth

**Weaknesses:** Lorem ipsum placeholder text destroys credibility — always use real or realistic copy, Floating coffee beans are random decoration with no compositional grid or rhythm, Mobile responsive version just shrinks desktop — nav wraps instead of collapsing to hamburger menu

---

### Score 3/10 — minimal-corporate — Modern restaurant website with online booking and menu showc

**Design Recipe:** Use #012D85 navy for headings with Playfair Display bold italic at 42px, pair with Inter 14px regular #0D0B0B body text on #FCFDFD white. Hero is 60/40 split — left text block with two pill CTAs (dark solid + blue outline, 44px height, 24px radius), right side features a 20px-radius rounded image with a 50%-radius circular food plate overlapping at top-right. Dish cards use circular images at ~160px diameter with small blue price badges positioned top-right, sitting on light gray rounded containers. Scatter hand-drawn botanical SVG illustrations at 10% opacity as background texture.

**Dev Recipe:** Static HTML/CSS or Next.js static export with Tailwind. Use CSS Grid for hero split, position: absolute for overlapping food images, Google Fonts for Playfair Display + Inter. Key challenge is the image collage — use a relative container with absolute-positioned children and z-index stacking.

**Core Lesson:** Good food photography can carry a mediocre layout, but typos and placeholder text instantly destroy credibility.

**Steal These:**
- Circular food image overlapping a rounded-rect restaurant interior photo — creates depth cheaply
- Navy + white + blue accent palette for food — unusual but works
- Hand-drawn botanical line art as subtle background texture
- Price badge as small circle overlapping dish image top-right
- Dual CTA pattern: dark solid pill + blue outline pill side by side

**Weaknesses:** Typo in heading ('Wecome') and lorem ipsum text destroy professionalism — always proofread, Problems/Solutions slide uses clashing red/green/blue colors and adds no design value to the case study, No mobile responsive views shown — critical gap for a restaurant site where most users browse on phones

---

## Slop Patterns to Avoid

### Score 4/10
- Floating coffee beans are a cliché stock decoration with no compositional logic
- Lorem ipsum placeholder text visible in Services and Testimonials sections
- Star ratings use inconsistent half-star rendering
- Product cards lack visual refinement — basic white rectangles with no shadow hierarchy
- Navigation doesn't collapse to hamburger on mobile — just shrinks and wraps awkwardly

### Score 3/10
- Typo 'Wecome' in hero heading — unreviewed
- Lorem ipsum placeholder text still present in dishes section
- Problems/Solutions slide is generic UX-process filler with mismatched color scheme (red/green Christmas palette)
- Background 'FOOD' / 'SPECIAL' / 'RESTAURANT' watermark text is a Behance presentation cliché
- Inconsistent mockup devices — iMac vs laptop vs different monitor

### Score 5/10
- Generic lorem ipsum placeholder text throughout
- Stock photo of woman eating pizza feels templated
- Category icons are basic and inconsistent in style
- Floating UI elements (cheese burger card, delivery badge) feel forced/decorative
- Footer is bare-minimum 4-column template layout

### Score 5/10
- Four completely unrelated app concepts bundled as one project — grocery, skincare AI, basketball streaming, kids fashion
- Inconsistent design systems across screens — orange accent is shared but everything else diverges
- Stock photography with no cohesive art direction or custom treatment
- Generic component patterns copied across domains without adaptation
- Watermark 'AI Wired' visible on skincare screens suggesting AI-generated mockup

### Score 5/10
- Generic stock photo of delivery guy used as hero — no custom photography or illustration
- Step cards (Select/Find/Wait) use identical copy for cards 1 and 3 — clear copy-paste error
- Color-coded step cards (yellow/orange/pink) feel arbitrary with no systematic logic
- Testimonial section is boilerplate with generic names and identical review structure
- Typography hierarchy is decent but serif headings + sans body is the safest possible choice
