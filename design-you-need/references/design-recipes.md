# Top Design Recipes — Score 7+

40 highest-scoring design recipes from 399 analyzed projects.

## Maria Eli: Fused Identities — Artist Portfolio (9/10)
**Aesthetic:** editorial | **Category:** portfolio

**Design Recipe:** Use #FFFAE6 warm cream background with #C72920 vermillion red exclusively for headlines and one circular CTA element. Set display type at 120-160px in a geometric sans (Roc Grotesk or Neue Haas Grotesk Bold) with deliberate mixed uppercase/lowercase (lowercase 'i' in otherwise uppercase words). Body text in 12-14px same family regular weight in near-black #090104. Layout on asymmetric grid with 60-100px section gaps, images bleeding into text zones with z-index overlap. All photography treated with warm sepia desaturation. Maximum 3 elements per section.

**Dev Recipe:** Next.js + GSAP ScrollTrigger + CSS Grid with named areas for overlapping layouts. Self-host a geometric sans via @font-face, use clip-path for diamond masks, filter:sepia(0.3) saturate(0.8) for image treatment, and clamp() for fluid display typography scaling.

**Core Lesson:** A single bold typographic decision (mixed-case letterforms) can carry an entire brand identity when paired with extreme color restraint.

**Steal These:**
- Mixed uppercase/lowercase in display type as brand signature
- Single red circle as the only CTA — impossible to miss
- Warm cream (#FFFAE6) instead of white for gallery-paper sophistication
- Text overlapping photography for editorial depth without shadows
- Vertical nav list tucked to the side — minimal but accessible

---

## Diligence Infrastructure for Private Capital (9/10)
**Aesthetic:** dimensional-layered | **Category:** fintech

**Design Recipe:** Use a 7-stop neutral palette from #11191A through #CDBFB6 to #FFFFFF with zero chromatic accents. Set hero H1 at 76px bold Inter/Söhne with -0.02em tracking, body at 17px regular with 1.6 line-height. Hero is full-viewport with architectural photography, bottom gradient overlay (transparent to #11191A over 40% height), and glassmorphic text cards (backdrop-filter: blur(20px), bg rgba(255,255,255,0.08), border 1px rgba(255,255,255,0.12), border-radius 12px). Cards float on page with 16px border-radius and box-shadow 0 24px 64px rgba(0,0,0,0.1). Section numbers in 60px light weight gray (#AAA8A6). All CTAs are text links with → arrows, no filled buttons.

**Dev Recipe:** Next.js + Tailwind CSS + Framer Motion. Use ScrollTrigger or scroll-timeline for the photo-to-wireframe state transition (cross-fade background images while maintaining DOM structure). Implement backdrop-filter glassmorphism for overlay cards, CSS custom properties for the 7-color neutral token system, and IntersectionObserver for section entrance animations.

**Core Lesson:** A restrained all-neutral palette with conceptually aligned photography can create more brand authority than any gradient or accent color ever could.

**Steal These:**
- Architectural photography as structural-clarity brand metaphor
- Photo-to-wireframe scroll transition showing design intentionality
- All-neutral palette with warm-cool gray tension for depth without color
- Floating contextual annotations on hero image as storytelling device
- No filled buttons anywhere — text-link CTAs with arrows convey confidence

---

## AMARI: Luxury Riverside Residences (9/10)
**Aesthetic:** organic-natural | **Category:** real-estate

**Design Recipe:** Use a warm monochromatic brown palette (#26150D to #F3F0EB) with zero accent colors — let imagery provide all contrast. Set hero type in a high-contrast didone serif at 120px+ with 0.15em letter-spacing, uppercase, light weight. Layer the logotype behind a full-bleed organic image (flower, fabric, water). Keep body copy centered, max-width 640px, in the same serif at 18px light weight with 1.6 line-height. Use generous 120-160px section padding. Frame gallery images with a thick 40px brown (#493122) border. Buttons are outline-only with uppercase tracking.

**Dev Recipe:** Build in Framer for native animation support. Hero flower effect needs either a custom WebGL shader (Three.js + image displacement) or a clip-path stagger array animated with Framer-Motion. Use self-hosted premium serif (Freight Display or similar). Image carousel via Framer's native scroll components with overflow clipping and a CSS-bordered wrapper.

**Core Lesson:** A single extraordinary visual moment (the animated flower) does more for luxury perception than ten generic sections of content

**Steal These:**
- Motion-trail image effect as hero centerpiece — one image, infinite drama
- Complete absence of accent color — letting photography be the only contrast
- Thick colored frame border around gallery images for editorial gravitas
- Flanking taglines ('Eternal beauty' left, 'by the river' right) around central logotype
- Building render breaking the section boundary — image bleeds between content zones

---

## Editorial Skincare Web Explorations with Golden Canyon Grid (9/10)
**Aesthetic:** editorial | **Category:** e-commerce

**Design Recipe:** Use #E6EAEB cool off-white background with #221B15 warm-black text. Set headlines in a high-contrast Didone serif (Playfair Display/Freight Display) at 72-80px regular weight with tight tracking (-0.02em). Body in 14px geometric sans (Inter/Helvetica Neue). Split layout 45% text left / 55% image right on a golden ratio grid. Navigation uses 13px uppercase tracking (0.15em) with em-dash separators. Add thin geometric diamond overlays in #B5C8BC at 30% opacity behind hero image. Bottom ticker bar with brand values connected by horizontal rules. Zero shadows, zero gradients, zero bright colors — let product photography be the only saturation.

**Dev Recipe:** Next.js with CSS Grid named template areas for the asymmetric split. GSAP for carousel transitions and SplitText headline animations. Custom SVG diamond shapes positioned with absolute/relative layering. Self-host a premium Didone serif; pair with system sans-serif for performance.

**Core Lesson:** True editorial luxury design uses mathematical grid systems (golden ratio) to create asymmetric layouts that feel intentional rather than random — the grid is invisible but its harmony is felt

**Steal These:**
- Em-dash separators between nav items instead of pipes or spacing
- Slide counter (01/02/03/04) with vertical rule as editorial pagination
- Bottom ticker bar with brand values as a footer alternative
- Diamond/rhombus geometric overlays on hero imagery
- Using product photography as the ONLY color accent in an otherwise neutral palette

---

## Interval. Cafe Brand Identity. Typography Layouts & Visuals. (9/10)
**Aesthetic:** neo-brutalist | **Category:** food

**Design Recipe:** Use a high-contrast transitional serif (Noe Display or Freight Display Bold) in ALL CAPS at 80-120px for headlines on a 3-column flush grid. Background palette: #0B0805 black, #FDF2EB warm cream, #634940 coffee brown, #AAA394 warm gray, #F41B00 pure orange-red used on max 15% of surfaces. Set data/labels in 7-9px uppercase monospace (GT America Mono) with wide letter-spacing. Internal tile padding 24-32px. Zero border-radius everywhere. Let type overflow and crop at tile edges. Every color must reference coffee: black=espresso, brown=bean, cream=milk, orange=heat.

**Dev Recipe:** CSS Grid with grid-template-columns: repeat(3, 1fr) and gap:0 for the specimen layout. Self-host display serif + monospace fonts. Use CSS custom properties for the 5-color token system. Overflow:hidden on each grid cell enables the cropped-type effect. For applied hero pages, use object-fit:cover with a linear-gradient overlay.

**Core Lesson:** Constraint breeds distinction — limiting yourself to uppercase type, a 3-column grid, and 5 earth tones forces every decision to carry maximum weight.

**Steal These:**
- Using product parameters (ratios, temps, times) as typographic content — turns data into design
- Flush modular grid with zero gaps — tiles feel like a unified system, not separate cards
- Single accent color (orange) used at <20% frequency for maximum visual punch
- Mixing serif display type with monospace data labels within one composition
- Micro-captions at 7-9px as compositional texture — not meant to be read, meant to be felt

---

## PAWS & CO. — Luxury Pet Hotel Website (9/10)
**Aesthetic:** editorial | **Category:** landing-page

**Design Recipe:** Use #F1E5D6 warm cream background framed by #050407 dark border (16-24px). Set headlines in Playfair Display Black 900 uppercase at 120-160px with -2px letter-spacing in #1A1A3E navy. Overlay a brush script font in #E2180B coral at 80-100px with slight rotation (-8deg). Place a cutout product/hero image breaking through the headline using z-index stacking (text layer 1, image layer 2, remaining text layer 3). Add a rounded coral (#E2180B) rectangle behind the image. Use DM Sans or Inter for body at 16-18px. CTAs are pill-shaped (#E2180B solid, 999px radius). Feature pills use outline style with line icons. Keep max 3 accent color touchpoints per viewport.

**Dev Recipe:** Build in Next.js + Framer-Motion with Tailwind CSS. Hero requires absolute positioning with 4+ z-index layers — use a grid container with overlapping grid-row/grid-column placements. GSAP ScrollTrigger for parallax depth on the hero image. Self-host Playfair Display + a brush script like Playlist or Sacramento.

**Core Lesson:** Depth through z-index layering of photography and typography creates editorial magazine-quality web design that no flat layout can match.

**Steal These:**
- Dark matted frame border around entire page — instant gallery/editorial elevation
- Hero image breaking through headline text via z-index layering
- Mixing uppercase serif + lowercase script overlay for brand personality contrast
- Coral background shape behind cutout image — simple but creates dimensional depth
- Avatar stack with hand-drawn squiggle underline — adds organic warmth to social proof

---

## Illustrated Animated Map of Kyiv, Ukraine. Landing Page. (9/10)
**Aesthetic:** retro-modern | **Category:** travel

**Design Recipe:** Use a warm parchment background (#D8D4C8). Set the hero title in a condensed black hand-drawn sans-serif at 120px+ centered on the page. Arrange 15-20 isometric illustrated landmarks in an oval ring around the title with ~50px gaps. Use a strict 6-color palette: black outlines (#090909), gold accents (#D09F41), Ukrainian blue (#4291CB), brick red (#C6380B), forest green (#3A7A3A), warm gray (#4F4C3E). All labels in hand-written cursive at 12-16px, rotated to follow their landmark. Below the fold, render a full pannable illustrated map with metro lines as colored SVG paths.

**Dev Recipe:** React + GSAP ScrollTrigger for hero animations, custom pan/zoom canvas (or react-zoom-pan-pinch) for the map viewport. SVG landmarks individually exported, positioned absolutely on a large canvas element. Use Lottie for complex landmark animations, CSS transforms for hover interactions. Lazy-load off-screen landmarks with IntersectionObserver.

**Core Lesson:** Illustration-first design with a constrained color palette and consistent visual language can create an experience no template or stock imagery could ever match.

**Steal These:**
- Radial landmark arrangement around centered title as hero pattern
- Consistent isometric angle across all illustrated elements for visual unity
- Limited illustrator's palette (6-7 colors) applied across 50+ unique drawings
- Hand-written labels rotated to follow their subject — adds organic warmth
- Color-coded metro lines as navigational wayfinding on the illustrated map

---

## The new illustrations for the Skretting company (Calendar 2026) (9/10)
**Aesthetic:** editorial | **Category:** corporate

**Design Recipe:** Use a strict 3-tone system: brand red #DC2926 for all human elements (hands, uniforms, action), cool blue-gray #A7AAB8 for environments and backgrounds, warm pink-white #FEEEEE as the base tone. Apply grain/noise texture at 15-30% opacity across all surfaces for analog warmth. Compose scenes with extreme foreground close-ups (hands at work) against panoramic mid/backgrounds. Reserve pure white #FFFFFF for narrative focal objects (lab coats, product bags). Use atmospheric perspective by desaturating and lightening distant elements toward the pink-white base. Typography is minimal — one high-contrast serif at display scale only.

**Dev Recipe:** For web presentation: Next.js with CSS Modules, responsive <picture> elements with art-directed crops at 3 breakpoints, GSAP ScrollTrigger for panel-by-panel reveal animations, WebP/AVIF with high-quality fallbacks to preserve grain texture detail.

**Core Lesson:** A ruthlessly restricted color palette (one warm accent + one cool neutral + tinted white background) can unify wildly different scenes into a cohesive brand system while creating a powerful semantic layer where color = meaning.

**Steal These:**
- Semantic color coding — red = human agency, gray = environment — creates subconscious narrative
- Extreme close-up hands as foreground framing device for panoramic scenes
- Grain/noise texture applied with varying density to create depth hierarchy
- Pink-tinted white (#FEEEEE) instead of pure white for warmth without sacrificing brightness
- Consistent limited palette across diverse scenes creates instant brand recognition

---

## The XIX — Cinematic 3D Website & Promo Animation (9/10)
**Aesthetic:** dark-luxury | **Category:** agency

**Design Recipe:** Full-bleed dark canvas (#040A11) with cinematic 3D scene as hero. Nav: transparent overlay, logo left, centered links in 16px light-weight geometric sans, outline button right. Typography: ultra-wide letter-spacing (0.3em) uppercase headings in 72px weight-200 Eurostile/Microgramma variant, silver-white (#C3C5D1). Accent color (#10D94E neon green) exists ONLY in the 3D scene lighting — never in UI elements. Bottom-anchored title block with subtitle in 18px uppercase tracking. Pagination counter bottom-right. Everything breathes — 40px+ nav padding, dramatic negative space around text.

**Dev Recipe:** React + @react-three/fiber + @react-three/drei for 3D scene, GSAP ScrollTrigger for scroll-driven camera animation, post-processing with UnrealBloomPass for neon glow. CSS: minimal overlay system with position:fixed, z-index layering, backdrop-filter:none to keep transparency clean over WebGL canvas.

**Core Lesson:** Let the 3D content BE the design — restrain the UI to transparent overlays with ultra-light typography so the visual spectacle speaks for itself

**Steal These:**
- Screen-within-3D-scene as meta-commentary on the product's capability
- Color accent existing only in 3D lighting, never in UI chrome
- Ultra-wide letter-spacing (0.3em+) on thin-weight uppercase for luxury feel
- Pagination counter as minimal scroll progress indicator
- Transparent nav over full-bleed 3D — no header background needed

---

## Mertana - Ski Brand (9/10)
**Aesthetic:** dark-luxury | **Category:** e-commerce

**Design Recipe:** Use #030404 background with #FEFEFE text and a single deep red (#C41E1E at 60% opacity) accent ONLY for labels. Set hero type at 15vw in a bold geometric grotesk (Neue Montreal Bold), layer a full-bleed action photo ON TOP of the type using z-index. All section labels: 11px uppercase, 0.12em letter-spacing, red. Body text in 15px regular weight warm gray (#C0BBB9). Cards: 1px border rgba(255,255,255,0.08), 4px radius, 24px padding. Category images desaturated. Spacing between sections: 120px minimum. Grid: 12-col with 24px gutters, max-width 1200px.

**Dev Recipe:** Next.js + Tailwind CSS with custom dark theme tokens. GSAP ScrollTrigger for hero parallax layering and section reveals. CSS Grid with named areas for the asymmetric category gallery. Self-host the display font, use CSS clamp() for responsive hero type scaling from 60px mobile to 200px desktop.

**Core Lesson:** Restraint IS luxury — one accent color at 2% coverage, one font family, and letting photography do the emotional heavy lifting creates more authority than any gradient or animation ever could.

**Steal These:**
- Hero type layered BEHIND the subject image — instant premium feel
- Red accent at <2% surface area — only section labels and active states
- Asymmetric image grid where one card spans 2 rows to break monotony
- Uppercase micro-labels with extreme letter-spacing as section identifiers
- Grayscale category images that likely reveal color on hover

---

## Fourmeta website: Future-ready digital experience (9/10)
**Aesthetic:** dark-luxury | **Category:** agency

**Design Recipe:** Start with #030504 dark background. Use PP Editorial New (or similar high-contrast Didone) at 72-80px for headlines, mixing italic and roman in the same line for rhythm. Body in Neue Haas Grotesk at 16px. Accent palette: #275131 for blocks, #B5CEB6 for badges, one salmon #F2C4B8 surprise element. Build hero as full-viewport with cinematic background image, large serif headline overlapping a 3D device mockup. Below hero, use asymmetric bento grid (CSS Grid with mixed span:2 and span:1 cells, 24px gap, 12px border-radius). Navigation: logo left, text links center, white pill CTA right. Mobile: collapse to single column, add sticky bottom bar with hamburger + 'Free Consultation' pill.

**Dev Recipe:** Next.js 14 with App Router for SSR blog pages + GSAP ScrollTrigger for scroll animations + Spline or pre-rendered 3D mockups. CSS Modules or Sass for scoped dark-theme styles; CSS Grid for bento layout; backdrop-filter:blur for floating glass badges; self-host PP Editorial New via @font-face with font-display:swap.

**Core Lesson:** Restraint in a dark theme — let one accent color family (sage-to-forest green) and one premium serif do all the heavy lifting instead of piling on effects.

**Steal These:**
- Italic/roman mixing in a single headline for editorial rhythm without using bold
- Salmon/pink badge as lone warm accent against cool dark-green palette — instant eye magnet
- Environmental mockup photography (subway poster, laptop on velvet) for case study presentation
- Sticky mobile bottom bar with hamburger + CTA pill — solves mobile nav + conversion in one component
- Awards section as structured table with year column, uppercase labels, and external arrows — clean credibility

---

## Product for a Productivity Product ✦ Daylier (9/10)
**Aesthetic:** dark-luxury | **Category:** dashboard

**Design Recipe:** Use #080808 background with #1A1A1E card surfaces (16px radius, 1px border at rgba(255,255,255,0.06)). Accent exclusively with #B08E3F gold and #A35004 deep amber — apply as radial-gradient light sources inside cards, never as flat fills. Typography: Inter or SF Pro, warm-white #FBFAF8 for primary text, #909191 for secondary. Large metrics at 48px bold. Cards at 20px padding with 16px gaps. Embed cinematic warm-graded photography inside select cards with overflow:hidden. Navigation uses pill-shaped outline buttons. Timeline uses horizontal CSS Grid with task pills as positioned elements.

**Dev Recipe:** Next.js + Tailwind + Framer Motion. Use Recharts or Visx for the bar/bubble charts with custom amber theming. Timeline is a CSS Grid with 13 equal columns (8AM-8PM) where task blocks span columns via grid-column. Cards use relative positioning with absolutely-placed gradient overlays (radial-gradient(circle at 30% 70%, rgba(163,80,4,0.6), transparent 70%)).

**Core Lesson:** A single warm accent color (amber/gold) used as a simulated light source within dark cards creates an emotional, premium atmosphere that transforms a utilitarian dashboard into something people want to look at.

**Steal These:**
- Photography embedded inside metric cards with warm color grading as data visualization enhancement
- Amber radial glow as simulated light source inside dark cards
- Date circle component with gold border and stacked day/month
- Timeline Gantt-style task pills with inline priority color dots
- Motivational toast ('Keep it going!') with checkmark icon as positive reinforcement UX

---

## Stormie - Art Director Website Portfolio (9/10)
**Aesthetic:** editorial | **Category:** portfolio

**Design Recipe:** Use #190200 dark warm-brown as outer frame, #F5EDE4 warm cream as centered content panel (~85% width), #2D1A0E for all text. Pair Playfair Display Bold Italic at 72px for name with a heavy grotesque sans (900 weight, uppercase, tight tracking) at 80px for role title. All functional text in Space Mono 11-12px uppercase with wide letter-spacing and bracket notation [LIKE THIS]. Asymmetric image grid: two images left-clustered with one smaller image far-right, generous 200px+ whitespace between grid and text. Thin 1px horizontal rules with small circle start-markers as section dividers. Background photography in warm amber/red tones bleeds behind the cream panel on scroll via fixed positioning.

**Dev Recipe:** Framer or Next.js + GSAP ScrollTrigger for parallax layering. Structure as position:fixed dark background with full-bleed image, then scrolling cream panel with higher z-index and margin:auto. Use Google Fonts Playfair Display + Space Mono, CSS text-align:justify for monospace blocks, and intersection observer for section reveal animations.

**Core Lesson:** Let photography carry the color — restrict your UI palette to warm neutrals and let curated imagery be the only source of vibrancy.

**Steal These:**
- Bracket notation [MENU] [CONTACT US] as a typographic system for interactive elements
- Warm-shifted black (#190200) instead of pure #000 for cohesive warmth
- Photography bleeding behind content panel via fixed/sticky layering
- Mixed serif-italic + sans-bold within a single headline for editorial rhythm
- Thin horizontal rule with dot marker as elegant section divider

---

## Origin creative landing page (9/10)
**Aesthetic:** dark-luxury | **Category:** agency

**Design Recipe:** Start with #040509 dark base. Build a vertical atmospheric gradient: #040509 → #0D235B → #20496F → light blue haze at ~40% page height, add subtle radial glow center-right. Use PP Editorial New italic at 80-96px for h1, Neue Montreal 14px/regular for body. Accent only with #6D9F30 chartreuse on 1-2 keywords per section and active pill states. Section labels use [ BRACKETED UPPERCASE ] at 12px/wide-spacing. Place 4-point star SVGs at grid intersections. Portfolio in bento grid with mixed card sizes. Footer: clip a 20vw 'origin' wordmark at bottom edge.

**Dev Recipe:** Next.js 14 + Framer Motion for scroll-triggered reveals + GSAP ScrollTrigger for parallax gradient layers. Tailwind with custom theme extending colors (#040509, #0D235B, #6D9F30). Self-host PP Editorial New and Neue Montreal. CSS Grid with named areas for bento portfolio section.

**Core Lesson:** Restraint with accent color (chartreuse on 2-3 words per section) creates 10x more impact than flooding the palette — the dark void makes every green word feel electric.

**Steal These:**
- Bracketed section labels [ THE PROCESS ] as a consistent typographic system
- Chartreuse green used only on 1-2 words per section for surgical emphasis
- Atmospheric sky gradient as full-page background creating natural depth zones
- Numbered navigation items (01 HOME, 02 SERVICES) adding editorial structure
- Giant clipped wordmark in footer creating a spatial 'ground plane' effect

---

## XIX3D Website — Cinematic 3D Animation (9/10)
**Aesthetic:** dark-luxury | **Category:** agency

**Design Recipe:** Dark base #020A0E with full-viewport 3D renders as backgrounds. Typography: light-weight geometric sans in uppercase with 0.3-0.4em letter-spacing for hero titles at 80-100px, #BBE8F1 color. Navigation: 2 ghost links top-right, logo top-left, all at 14px regular weight with rgba(255,255,255,0.6). Each portfolio section gets its own color world — teal-blue for automotive, lavender-pink for crypto, warm cream for e-commerce. Pagination bottom-right as '4/4' at 14px uppercase with 'SCROLL DOWN' label. Zero decorative UI elements — all visual interest comes from the 3D content itself.

**Dev Recipe:** Next.js with GSAP ScrollTrigger for full-viewport snap-scrolling between portfolio sections. Each section is 100vh with object-fit:cover background imagery, position:absolute text overlays with mix-blend-mode:normal. Use CSS custom properties to swap color themes per section. Preload hero images, lazy-load subsequent sections, use will-change:transform on scroll-animated elements.

**Core Lesson:** When your work IS the product, make the UI invisible — full-bleed visuals with whisper-thin typography creates a gallery experience that elevates every piece

**Steal These:**
- Wireframe ghost overlay on solid 3D model — shows process AND creates visual drama
- Ultra-wide letter-spacing (0.4em) on single-word hero titles for cinematic weight
- Per-project color palettes within one portfolio site — each piece gets its own world
- Neon light poles as practical scene lighting that doubles as compositional framing devices
- Minimal pagination '4/4' with scroll prompt — just enough UI to guide without cluttering

---

## Golf Club Landing Page Design (9/10)
**Aesthetic:** editorial | **Category:** landing-page

**Design Recipe:** Use a high-contrast transitional serif like Freight Display or Playfair Display at 120-140px for hero headlines in italic, paired with 11px uppercase wide-tracked sans-serif (Neue Haas Grotesk) for navigation and labels. Background palette: #14140E for dark sections, #F5F2ED for light sections, #423B30 for body text — zero bright accents. Full-bleed editorial photography with warm natural grading as hero, overlaid with white serif text bottom-left. Create a vision section on cream background with 6-8 small photos (100-200px) scattered asymmetrically using absolute positioning at varied coordinates, centered quote in 36-42px serif. Section spacing 120-160px minimum. Course detail as a floating white card (~600px wide, no border-radius) centered over aerial drone photography.

**Dev Recipe:** Next.js with GSAP ScrollTrigger for parallax collage and scroll-based reveals. Self-host premium serif font, use CSS custom properties for the warm neutral palette. SVG textPath for the rotating circular badge. Key challenge is the scattered photo section — use a container with position:relative and each photo absolutely positioned with GSAP ScrollTrigger scrub for independent parallax speeds.

**Core Lesson:** True luxury is communicated through restraint — no bright accents, no gradients, no gimmicks. Let typography scale, photography quality, and whitespace do the heavy lifting.

**Steal These:**
- Oversized italic serif headline at 120px+ over full-bleed photography — instant editorial authority
- Scattered asymmetric photo collage with parallax as a vision/about section pattern
- Rotating circular text badge as a subtle interactive CTA element
- All-uppercase 11px wide-tracked sans for nav creates extreme scale contrast with serif headlines
- Floating information card overlaid on aerial/drone photography for data presentation

---

## Case Study: Landing Page for Creator Growth Platform (9/10)
**Aesthetic:** bold-expressive | **Category:** agency

**Design Recipe:** Use a heavy condensed italic display font (Druk Wide or Tusker Grotesk) in all-caps white with -webkit-text-stroke on a blue-to-light-blue gradient hero (#1352AB → #B8D4E8). Body on warm cream #F7F6EC. Accent only in #FF0900 for CTAs and stat sections. Photos masked in mixed shapes (ovals via border-radius:50% 50%, rounded-rects at 24px, circles) arranged in asymmetric bento grids with 16-24px gaps. Add rotated sticker-label text blocks (transform:rotate(-3deg to -8deg)) with solid color backgrounds in blue/black/red. Nav links wrapped in parentheses. Section spacing at 120-160px. Stats section full-width red background with oversized italic numbers.

**Dev Recipe:** Build in Next.js or Framer with Tailwind CSS for utility-first spacing and responsive grid. Use GSAP ScrollTrigger for section reveals and stat counters, Embla Carousel for testimonials, clip-path and overflow:hidden for photo masks, and self-host the display font. Key CSS: grid-template with named areas for bento layouts, transform:rotate for stickers, -webkit-text-stroke for outline headlines.

**Core Lesson:** Constraining to 3 bold colors (red #FF0900, blue #1352AB, cream #F7F6EC) on black creates maximum visual impact — the discipline of the palette lets the typography and photo treatments do the heavy lifting

**Steal These:**
- Parenthesized nav links — (ABOUT) (CASES) — subtle editorial detail that adds personality
- Mixed-shape photo masking grid — oval + rounded-rect + circle in one composition
- Sticker/stamp rotated text labels as decorative brand vocabulary elements
- Sky-gradient hero that transitions from deep blue to light blue mimicking real photography
- Red stats section as a full-bleed color break between cream content sections

---

## Fourmeta services, but make them feel alive (9/10)
**Aesthetic:** dimensional-layered | **Category:** agency

**Design Recipe:** Start with #060606 full-bleed dark canvas. Add a subtle radial-gradient warm glow (#2A1A15 center fading to black) behind the focal area. Create service cards at ~280x420px with 12px border-radius, each with its own dominant color (deep green #224837, coral red #E84B3C, soft purple #B8A5D0, teal #7EC8C8). Position cards in a 3D carousel using CSS perspective: 1200px with varying rotateY(-15deg to 15deg) and translateZ values. Use a condensed bold serif (Playfair Display Black) at 36px for card titles, Inter 13px 400 for nav. Nav is fixed with pill-outline CTA (1px white border at 40% opacity, 20px radius). Add 0 20px 60px rgba(0,0,0,0.5) shadows on cards for float effect.

**Dev Recipe:** Next.js + GSAP ScrollTrigger + Three.js (or pure CSS transforms if simpler). Use Lenis for smooth scroll, GSAP for carousel rotation interpolation on scroll. Cards as absolutely positioned divs with transform-style: preserve-3d inside a perspective container. Self-host fonts, use CSS custom properties for card theme colors.

**Core Lesson:** Transform mundane content (a services list) into a spatial experience by giving each item physical presence and depth in 3D space

**Steal These:**
- 3D carousel for services instead of boring grid — each card tilted at unique angle
- Warm radial glow behind dark content creates stage-lighting atmosphere
- Superscript counters on nav links showing project counts per category
- Custom cursor pill that contextually changes label ('Keep scrolling')
- Each service card is itself a mini-portfolio showing actual work samples

---

## Baumkontrolle im Netz - Web Design (8/10)
**Aesthetic:** organic-natural | **Category:** corporate

**Design Recipe:** Use #050A06 deep forest dark as primary bg, #F6F4EA warm cream for all text, #699554 muted forest green for card surfaces, and #9AF712 electric lime ONLY for CTAs and key headings. Set headings in a high-contrast serif (DM Serif Display) at 48-56px bold with tight letter-spacing, body in DM Sans 16-18px regular at 1.6 line-height. Hero is full-viewport with a moody portrait photo overlaid with dark gradient, headline bottom-left, dual pill CTAs (solid lime + outline lime). Section spacing 100px+, pill buttons at border-radius:9999px height 44px. Add organic SVG blob shapes in lime green as decorative background elements, and use a subtle leaf-vein SVG pattern on lighter sections.

**Dev Recipe:** WordPress with Elementor/ACF or Webflow for CMS flexibility; custom CSS with CSS custom properties for the 8-color palette; Intersection Observer for scroll-triggered fade-ins; SVG blobs positioned absolutely with z-index layering behind content containers.

**Core Lesson:** When your brand IS nature, extract your entire palette from the literal environment — bark, moss, lichen, new growth — and let that discipline unify everything.

**Steal These:**
- Forest-ecosystem color extraction method — every hex maps to a real natural element
- Electric lime (#9AF712) on near-black — maximum pop with organic credibility
- Watercolor podcast illustration style — hand-crafted feel in a digital context
- Circular badge logo with silhouette — works at any size, stamps authority
- Organic blob shapes as device mockup backgrounds — adds life to standard presentations

---

## Epitope — Biotech Visual Identity (8/10)
**Aesthetic:** minimal-corporate | **Category:** healthtech

**Design Recipe:** Use a monochromatic teal palette: #354B4A for text, #45827D for accents, #A9D3D5 for decorative, #FEFEFE for backgrounds. Set Inter or SF Pro at 68px bold tight-tracked for H1, 44px bold for H2, 17px regular for body. Wrap entire page in a rounded container (border-radius: 20px) with a soft box-shadow to create a device-like frame. Feature cards in a 2-column CSS Grid with 24px gap, white fill, 16px radius, 36px padding, thin #E5EFF0 border. All buttons are pills (border-radius: 999px) — primary dark-filled, secondary outline with arrow icons.

**Dev Recipe:** Next.js + Tailwind CSS with CSS custom properties for the teal HSL scale. Spline or pre-rendered 3D for the hero protein visual, Framer Motion for scroll-triggered card reveals, and a sticky nav with backdrop-filter:blur(12px).

**Core Lesson:** A single-hue monochromatic palette with a bespoke hero visual that literally represents your product's core concept creates more brand impact than any multi-color scheme.

**Steal These:**
- Page-as-device: rounded outer container with diffused shadow creates premium framing
- Monochromatic palette from a single hue at 5+ lightness stops
- Hero visual that IS the product concept (protein shapes = protein analysis)
- Pill badges with emoji/icon + label as section identifiers on cards
- Em-dash as typographic divider between headline column and body column

---

## Kaisen Ramen — Motion-Driven Landing Page 🍜 (8/10)
**Aesthetic:** dimensional-layered | **Category:** food

**Design Recipe:** Use deep crimson #8B1A1A background with seigaiha wave SVG pattern at 5-8% opacity. Apply radial vignette darkening edges to #3A1010. Set a custom geometric Japanese-inspired display font at 120px/900-weight in #F1F0EB for the hero title. Layer 5+ z-index planes: background → wooden tray prop (curved, warm #A68759 tones) → flanking product bowls at 30% scale → hero bowl at 60% scale centered → text overlay → decorative props (chopsticks rotated ±30deg, chili peppers). CTA is pill-shaped #A68759 solid fill with uppercase text. Keep nav to two corner icons in subtle bordered squares.

**Dev Recipe:** Next.js + GSAP (ScrollTrigger + SplitText) for motion orchestration. Use absolute positioning within a relative full-viewport container for the layered composition. Self-host the display font, use CSS custom properties for the red palette, and implement the seigaiha as an inline SVG pattern-fill at low opacity. Responsive strategy: completely restructure to vertical stack on mobile with reduced prop elements.

**Core Lesson:** Dimensional layering of real product photography with cultural texture patterns creates immersive food experiences that flat layouts cannot achieve

**Steal These:**
- Seigaiha wave pattern as subtle cultural texture on solid color backgrounds
- Curved wooden tray as a compositional device creating depth behind the hero product
- Japanese-inspired geometric Latin letterforms with torii-gate-style crossbars
- Asymmetric prop placement (chopsticks, chilies) to break rigid symmetry
- Gold/amber #A68759 as the sole interactive color against deep red — instant CTA visibility

---

## Fine Dine Club Website | Selected Screens (8/10)
**Aesthetic:** dark-luxury | **Category:** crypto-web3

**Design Recipe:** Use #060606 pure black backgrounds with #334A3A dark olive panels for content sections. Set headlines in a high-contrast didone serif (Cormorant Garamond 400) at 72-96px in #B4925B gold, always uppercase with 0.15em letter-spacing. Body text in geometric sans (Jost 300) at 15px in #B2ABA5. Section numbers in 13px with wide tracking. Create a signature motif — semicircular arc in thin gold stroke — and repeat it across hero slides. Use full-bleed food photography with chiaroscuro lighting. FAQ sections use 30/70 split with sidebar navigation featuring a horizontal line indicator for active state. Accordion items separated by 1px #B2ABA520 borders with thin + icons.

**Dev Recipe:** Next.js with GSAP for marquee scrolling, hero slider transitions, and ScrollTrigger parallax. Use CSS Modules or Sass for scoped styling. SVG for the semicircular arc motif and circular text indicator. Swiper.js for the hero carousel with custom GSAP-powered transitions. Self-host premium serif font, optimize food photography with next/image and blur placeholders.

**Core Lesson:** In dark luxury design, restraint with gold accents and letting exceptional photography breathe creates more impact than decorative excess

**Steal These:**
- Marquee text header with overlapping photography for section intros
- Semicircular arc as a repeating brand motif overlaying hero imagery
- Circular radial 'SCROLL' text indicator as a custom scroll affordance
- Ornamental divider with centered circle between headline and body
- Numbered section indicators (01, 02) in small muted type as editorial pacing device

---

## Modern Minimalist Blockchain UI (8/10)
**Aesthetic:** dimensional-layered | **Category:** crypto-web3

**Design Recipe:** Use #DCEDF4 cool off-white content panel inset within a viewport-spanning mesh gradient border cycling through #130BA8 → #C84C1C → #EEB630 → #8078BC. Set headlines in a condensed black-weight grotesque (Clash Display 900) at 72-80px uppercase with -0.02em tracking. Body in Inter 400 at 15px, #0A0413 text. Hero splits 45/55 left-right with text left, oversized 3D asset right that bleeds past container edge via overflow:visible. CTA button is #EEB630 solid fill with #0A0413 text, 48px height, 8px radius. Stats use 32px bold monospace numbers with 13px regular labels. Maintain 80-100px section spacing on 8px grid.

**Dev Recipe:** Next.js + Tailwind + Framer Motion. Pre-render 3D coin in Blender with HDRI lighting and chromatic aberration, export as WebP with alpha. Use conic-gradient on a fixed full-viewport wrapper for the border effect, position the content panel with margin:20px and border-radius:24px. Framer Motion for staggered hero entrance and scroll-triggered stat counters.

**Core Lesson:** A single hero-grade 3D asset with intentional color bleed can unify an entire page's color system and create premium perception

**Steal These:**
- Mesh gradient page border that frames content like a gallery piece
- 3D asset light leak that intentionally breaks its container boundary
- Gold CTA on cool palette — instant visual hierarchy win
- Dark pill scroll indicator with bounce animation — elegant wayfinding
- Film-strip texture detail on 3D coin adding analog warmth to digital asset

---

## MVRDP — Architectural Visualization Concept (8/10)
**Aesthetic:** minimal-corporate | **Category:** agency

**Design Recipe:** Use a single grotesque sans-serif family (Neue Haas Grotesk Display or Helvetica Now) across all text. Background #FFFFFF, text #181D1D, surfaces #F5F5F0, borders #D2D2D2 — zero chromatic color. Hero: 180-220px uppercase bold letterforms with a photorealistic image layered behind at z-index:-1. Section spacing 100-120px. Accordion services with 01/XX numbering left-aligned, pill-shaped category tags at ~12px uppercase. Stats in 56-64px black weight. All CTAs are black pill buttons with white text. Footer uses a 3-column link grid with 10-11px uppercase category headers.

**Dev Recipe:** Webflow or Next.js with GSAP ScrollTrigger for section reveals and accordion animations. Tailwind with custom config for the tight color palette, CSS Grid for stats row, flexbox for nav and logo bar. Key technique: hero uses absolute-positioned image behind a large text element with careful z-index stacking.

**Core Lesson:** When your product IS visual (architecture renders), strip everything else to monochrome and let the imagery be the only source of color and richness.

**Steal These:**
- Oversized brand name as hero with architectural imagery bleeding through/behind
- Numbered accordion for service categories with expand/collapse and inline image
- Complete absence of color accent — letting photography be the only warmth
- Uppercase wide-tracked micro-labels (OUR TEAM, FIND YOUR SOLUTION) as section wayfinders
- Contact section with large serif-weight headline left, minimal underline-only form fields right

---

## ARCILLA: Luxury Residential Masterpiece (8/10)
**Aesthetic:** warm-minimal | **Category:** real-estate

**Design Recipe:** Use a warm monochromatic palette extracted from terracotta: bg #F5EDE6, text #A7814B, deep accent #543625, hero sky #E1EAF5. Set the hero headline in a high-contrast didone serif (Cormorant Garamond Light) at 120-140px uppercase with 0.05em letter-spacing. All supporting text in a geometric sans at 12-13px uppercase with 0.2em letter-spacing. Layout is asymmetric 40/60 text-image splits with 120px+ section padding. Use only one or two CTA buttons per viewport — extreme restraint. Gallery uses 3 overlapping images with 20-40px offset stacking and subtle box-shadows.

**Dev Recipe:** Framer or Next.js with Framer Motion for scroll-triggered parallax and fade reveals. Self-host premium serif font, use CSS custom properties for the terracotta palette, implement intersection observer for staggered text animations, and use transform3d for GPU-accelerated parallax on the gallery stack.

**Core Lesson:** Let the physical product's material palette become the entire digital color system — when the website looks like it's made of the same clay as the building, brand coherence is effortless.

**Steal These:**
- Sampling the color palette directly from the product's physical materials
- Oversized ultra-light serif headline against photorealistic architectural render
- Porsche 911 in the render as aspirational lifestyle anchoring without saying a word
- Three overlapping images at different depths creating a physical collage feel
- Using the sky color from the hero render as the actual hero background — seamless bleed

---

## Clearing. – Visual Identity (8/10)
**Aesthetic:** dark-luxury | **Category:** saas

**Design Recipe:** Start with a dark base (#080705). Source or commission a single cinematic photograph with warm subject (terracotta #572A0F) against dark teal sky (#1A2F2F). Apply heavy film grain overlay. Use a single geometric sans (Inter, 400/500 weights). Set hero headline at 72-80px medium weight, white, bottom-left aligned. Wrap the entire hero in a container with 16px border-radius and overflow:hidden. Add a bottom gradient overlay (transparent → rgba(8,7,5,0.8)) for text. Keep all UI chrome monochrome — white text, white pill buttons, gray secondary text (#A2A2A2). Tags use small symbolic icons. Feature cards repeat the photographic treatment with 20px radius on dark backgrounds.

**Dev Recipe:** Build in Next.js or Framer with Tailwind dark theme. Use CSS pseudo-elements for noise/grain overlay (tiny noise.svg tiled at 5% opacity), linear-gradient overlays on hero via bg-gradient-to-t. GSAP ScrollTrigger for parallax on the hero image. Framer Motion for section entrance animations.

**Core Lesson:** One extraordinary image with perfect color grading can replace an entire design system's worth of decorative elements — invest in art direction, not UI ornamentation.

**Steal These:**
- Rounded hero container with overflow:hidden — breaks the typical full-bleed monotony
- Deriving entire color palette from a single photograph for perfect cohesion
- Film grain texture adding analog warmth to a digital product
- Motion-blurred figure as brand metaphor for deliberate forward movement
- Monochrome UI chrome letting photography be the only color source

---

## Herbal therapist website (8/10)
**Aesthetic:** organic-natural | **Category:** healthtech

**Design Recipe:** Use #F8F6EE warm cream background with #091523 deep navy accent panels. Set headings in Playfair Display bold italic at 28-32px, body in a readable serif at 16px with #4E5843 color. Create a services section as a navy (#091523) panel with 1px inset border in #A8ADA1, containing oval-masked (clip-path:ellipse(48% 50%)) botanical illustrations on cream backgrounds. Use pill-shaped buttons (border-radius:20px) in both solid navy and outline variants. Maintain 80-100px section spacing with generous 1.6 line-height. Source botanical illustrations from public domain archives for authenticity.

**Dev Recipe:** WordPress with custom theme or Webflow; vanilla CSS with CSS custom properties for the 8-color palette; clip-path for oval masks; careful absolute positioning for oversized botanical illustrations with overflow:hidden on parent containers. Google Fonts Playfair Display for headings.

**Core Lesson:** Curated vintage illustration systems can replace photography entirely and create stronger brand identity than stock photos ever could.

**Steal These:**
- Oval-masked vintage botanical illustrations as service category icons on contrasting dark panel
- Deep navy panel with subtle inset border frame for visual gravitas
- Hippocrate quote as hero headline — authority borrowing from historical figure
- Warm parchment cream (#F8F6EE) instead of pure white for organic warmth
- Oversized botanical illustration bleeding off the hero section edge for dynamic composition

---

## Luméa Design Studio (8/10)
**Aesthetic:** editorial | **Category:** agency

**Design Recipe:** Use #F5E6D0 warm parchment background with #110A06 near-black text and #D94B1A burnt vermillion as sole accent (5% surface max). Set hero headline in Playfair Display Bold at 140-180px with -0.02em tracking, add one italic word in vermillion at ~100px for typographic tension. Layout is asymmetric CSS Grid with 60/40 splits, 120-160px section gaps, and oversized decorative serif numerals at 300px/0.06 opacity as background texture. All imagery warm-toned with natural light, zero border-radius, 16px grid gaps. Navigation is minimal serif at 14px with vermillion underline on active state.

**Dev Recipe:** Build in Next.js or Framer with GSAP ScrollTrigger for scroll-based type reveals and staggered image entrances. Use CSS Grid with named template areas for asymmetric layouts, CSS custom properties for the 3-color palette, and self-hosted Playfair Display with font-display: swap.

**Core Lesson:** A single accent color used with extreme restraint on a warm neutral base creates more visual impact than any complex palette ever could

**Steal These:**
- Single italic word in accent color within a bold serif headline — instant brand signature
- Oversized low-opacity background numerals as decorative depth layer
- Warm parchment background that makes interior photography feel native
- Questionnaire page with full-bleed color block split — turns a form into an experience
- Catalogue filter bar with color dots + text tags as horizontal scrollable strip

---

## Architecture Studio Website — Modern Web Design Concept (8/10)
**Aesthetic:** dark-luxury | **Category:** agency

**Design Recipe:** Dark background #000000, white text #FFFFFF, single orange accent #FF5A1F reserved exclusively for CTAs. Use a black-weight condensed grotesque (Druk Wide, Tungsten Black, or similar) at 12-15vw for the hero wordmark, positioned absolute overlapping a full-bleed architectural image. All navigation in pill-shaped buttons (border-radius:9999px) with 1px white borders at ~40px height, arranged in a fixed bottom bar. Project info in a dark glass card (backdrop-filter:blur(12px), rgba(0,0,0,0.65), border-radius:16px, ~20px padding). Body text in uppercase geometric sans at 11-14px with 0.1em letter-spacing. Section spacing is dramatic — hero takes 100vh, nav compressed to ~60px bar.

**Dev Recipe:** Next.js + GSAP for scroll-driven wordmark animations and project transitions. Self-host display font, use CSS custom properties for the 3-color system, backdrop-filter for glass cards, position:fixed for bottom nav, clamp() for responsive wordmark scaling.

**Core Lesson:** One oversized typographic element with intentional overlap creates more brand impact than any amount of decorative complexity.

**Steal These:**
- Bottom-anchored pill-button navigation bar instead of top nav
- Brand wordmark as massive overlay bleeding across hero image
- Dark glass info card floating over full-bleed imagery
- Orange accent used on exactly 2-3 elements site-wide
- Uppercase wide-tracked small text for all utilitarian labels

---

## Formula - the tech behind peace of mind (8/10)
**Aesthetic:** dark-luxury | **Category:** saas

**Design Recipe:** Use #030303 page bg with #1A1A1A rounded (16px radius) content containers. Set headlines in Playfair Display Regular at 64px #FAFAFA, body in Inter 20px #9B9B9B. Product grid: 6 equal columns with 32px gaps, center-aligned. Product images should be 3D renders on transparent bg with consistent studio lighting from upper-left. Status text in italic for future dates. Section padding: 80px top, 60px bottom. Keep accent color (#A67940) to less than 5% of visible surface.

**Dev Recipe:** Next.js + Tailwind with custom dark theme tokens (--bg-base: #030303, --bg-surface: #1A1A1A, --text-primary: #FAFAFA, --text-muted: #9B9B9B). CSS Grid for product layout with auto-fit minmax(180px, 1fr). Framer Motion for staggered scroll-reveal on product cards with 0.1s delay between items.

**Core Lesson:** Dark UI gains sophistication through layered near-black surfaces (#030303 outer, #1A1A1A inner) rather than flat black — this single technique separates amateur dark themes from professional ones.

**Steal These:**
- Two-tier dark background layering for depth without borders
- Serif headline on dark bg for instant premium feel
- Product availability status as simple italic text — honest and elegant
- Consistent 3D render lighting direction across all product shots
- Generous vertical spacing between headline and content grid for dramatic pacing

---

## WSI Website Design (8/10)
**Aesthetic:** dark-luxury | **Category:** corporate

**Design Recipe:** Use #050712 as primary dark bg, #0A1E5C for elevated dark surfaces, #F5F7FA for light sections, and #1A6FE8 exclusively for CTAs. Set Inter at 300 weight for hero headlines (48-56px), 600 for h3 labels (24px), 400 for body (16px). Use 120px section padding, 16px border-radius on all cards, pill-shaped buttons (border-radius: 999px) at 40px height. Alternate dark navy and light gray sections. Place 3D device mockups as hero visuals with real UI screenshots inside. Use uppercase 12px letter-spaced labels (tracking: 0.1em) for section eyebrows.

**Dev Recipe:** Next.js with Tailwind CSS, custom components (no UI lib needed), GSAP for scroll-triggered animations and 3D mockup reveals, self-hosted Inter font. Key: CSS custom properties for dark/light section theming, radial-gradient pseudo-elements for glow effects, CSS 3D transforms or pre-rendered Blender mockups for device presentations.

**Core Lesson:** A ruthlessly disciplined monochromatic palette (all navy shades) with a single blue accent can make even industrial B2B feel premium — constraint is the luxury.

**Steal These:**
- Monochromatic navy palette with single blue accent — extreme color discipline
- 3D device mockups showing real product UI as hero visuals instead of abstract illustrations
- Stats bar with oversized numbers + small unit labels as visual proof points
- Alternating dark/light sections creating natural content rhythm
- Radiating line pattern behind CTA sections adding subtle energy without distraction

---

## FundOnion — Web Design. Main Pages & Digital Experience Design (8/10)
**Aesthetic:** dark-luxury | **Category:** fintech

**Design Recipe:** Use #040607 dark backgrounds with a high-contrast transitional serif (Playfair Display 700, -0.02em tracking) at 56-72px for hero headlines in white. Pair with Inter 400/500 at 14-16px for body. Reserve a single teal accent (#42B676) exclusively for pill-shaped CTAs (border-radius: 999px, height: 40px, padding: 0 24px) and selected form states — never decorative. Light pages use #ECECEE backgrounds with white card surfaces (border-radius: 12px, padding: 32px, box-shadow: 0 2px 8px rgba(0,0,0,0.06)). Section spacing 96-120px, 8px base grid. Team cards in 3-column grid with grey headshots.

**Dev Recipe:** Next.js 14 with App Router for multi-page SSR, Tailwind CSS with custom dark/light theme tokens, Framer Motion for page transitions and form wizard step animations. Key challenges: multi-step form wizard with Zod validation, Intl.NumberFormat for currency input, and Intersection Observer for stat counter scroll triggers.

**Core Lesson:** Dual-mode design (dark cinematic for brand storytelling, light clean for functional UI) creates emotional separation that makes both modes more effective than either alone.

**Steal These:**
- Single teal accent reserved ONLY for interactive elements — creates instant visual affordance
- Cinematic silhouette team photo as hero — far more compelling than individual headshots grid
- Multi-step form wizard with chip-select buttons instead of dropdowns — reduces friction
- Badge/label above headline ('OUR TEAM') in uppercase small text with border — instant context
- Dark mode for storytelling, light mode for task completion — emotional UX architecture

---

## [Case Study] B2B Website Design for Clearbit (8/10)
**Aesthetic:** glassmorphism | **Category:** saas

**Design Recipe:** Use a navy-to-periwinkle analogous palette: #111437 text, #2F3BDD CTA, #8D71EB→#5BC4F0 gradient decoratives, #F5F6FC page bg. Set Inter at 700/64px headlines with -0.02em tracking, 400/17px body at 1.6 line-height. Build hero as left-aligned text (60%) with product screenshot (40%) inside a frosted glass container (backdrop-filter:blur(20px), bg:rgba(245,246,252,0.85), border-radius:20px) floating over a purple-blue gradient or 3D abstract background. Cards use white fill, 1px #B6C0F2 border, 14px radius, 28px padding in a CSS Grid bento layout. Space sections at 100px gaps on an 8px base unit.

**Dev Recipe:** Next.js + Tailwind CSS with custom color tokens for the blue-purple scale. Use Framer Motion for scroll-triggered card reveals, CSS backdrop-filter for the glass hero container, CSS Grid with named areas for the bento layout, and a repeating radial-gradient for the dot pattern texture.

**Core Lesson:** A single-hue-family palette (blue 230°-270°) at 6+ saturation/lightness levels creates effortless cohesion — you never need more than one color family if you master tonal range

**Steal These:**
- Frosted glass content container floating over abstract 3D background — instant premium depth
- Dot-grid pattern as subtle texture behind product screenshots — adds visual interest without competing
- Bento-grid with asymmetric card sizes showing different product features — more engaging than uniform cards
- Single analogous color family at 6+ tonal variations — cohesion without monotony
- Real product UI screenshots with slight perspective transform as hero visual — more credible than illustrations

---

## Finance SaaS Landing Page | Finance App (8/10)
**Aesthetic:** organic-natural | **Category:** fintech

**Design Recipe:** Use #091710 dark forest for text, #1B5E3B for CTAs, #B1CA27 lime for accent cards, #AEEDFD cyan for hero sky gradient fading to #F5F3EE warm white. Pair Playfair Display (regular, 56-64px headlines) with Inter (16px body). Build on 12-col grid at 1200px max-width with 80-120px section gaps. Pill-shaped buttons (border-radius:24px, 48px height). Bento feature grid with mixed card sizes using 12-16px radius and sage/green fills. Hero is centered text above a 3D organic landscape PNG wrapping a phone mockup.

**Dev Recipe:** Next.js + Tailwind CSS + Framer Motion for scroll animations. Use CSS Grid with grid-template-areas for the bento section, z-index layering for the hero landscape compositing, and IntersectionObserver-driven fade-ups. Self-host the 3D hills as optimized WebP with responsive srcset.

**Core Lesson:** A single bold visual metaphor (growth = green hills) carried consistently through every section creates more brand memorability than ten generic features

**Steal These:**
- 3D organic landscape as hero visual instead of generic gradients or blobs
- Warm off-white (#F5F3EE) background instead of pure white for organic warmth
- Pill-shaped nav container grouping links visually
- Bento grid with mixed green-tinted card fills for feature showcase
- Oversized brand wordmark in dark footer as visual anchor

---

## UNUS Landing page 3D web design and icons (8/10)
**Aesthetic:** dimensional-layered | **Category:** crypto-web3

**Design Recipe:** Use #FAFCFD background with #090B0D headlines in Inter Bold at 56-64px with -0.02em tracking. Body text in #3B4254 Inter Regular 15px/1.6. Cards: white surface, 12px radius, 1px #E8EBF0 border, 24px padding, box-shadow 0 4px 24px rgba(0,0,0,0.04). Hero: centered text above a 3D phone mockup rendered in Blender with blue (#4EBBEA) accent lighting on a perspective grid. Section spacing 100-120px. Feature icons: 3D metallic gold + glass renders at 64px. Comparison table with brand blue (#4558A3) column highlight. Max-width 1200px, 12-col grid, 24px gutters.

**Dev Recipe:** Next.js + Tailwind CSS + Framer Motion for scroll animations. 3D assets as optimized WebP with srcset for responsive. GSAP ScrollTrigger for parallax phone mockup. Intersection Observer for staggered section reveals. Use next/image for automatic optimization of heavy 3D render PNGs.

**Core Lesson:** Let premium 3D renders do the heavy lifting while keeping the page layout surgically clean — the contrast between rich visuals and minimal structure creates perceived luxury

**Steal These:**
- Perspective grid background behind hero product mockup — adds spatial depth without complexity
- Emoji inline with headlines as visual anchors (🔴📊) — cheap but effective attention markers
- Problem→Solution→How→Comparison narrative flow — textbook conversion architecture
- Unified 3D material language (gold + glass + chrome) across all icons for brand cohesion
- Feature comparison table with highlighted brand column — direct competitive positioning

---

## Zyron – Athletic Gear Website (8/10)
**Aesthetic:** bold-expressive | **Category:** e-commerce

**Design Recipe:** Use a condensed italic black sans-serif (Tusker Grotesk or Dharma Gothic) at 90-100px uppercase for hero headlines on a warm gray (#DFDCE1) background. Pair with deep navy (#0D0F3B) for nav and text, royal blue (#161AA6) and burnt orange (#F47030) for accent cards. Set body in DM Sans 15px regular. Build an asymmetric 3-zone layout: left text column (40%), center athlete cutout (35% overlapping both zones), right product sidebar (25%). Use 16px border-radius on cards, pill-shaped buttons with 9999px radius, and 8px base spacing unit. Tags use pill outlines with 1px border.

**Dev Recipe:** Next.js + Tailwind CSS with custom font-face for condensed italic display font. Use CSS Grid with template-areas for the asymmetric hero, Framer Motion for staggered headline entrance and scroll-based parallax on the athlete image. Key challenge is the z-index stacking context for the overlapping cutout — use a dedicated stacking layer with pointer-events:none on decorative overflow.

**Core Lesson:** A single bold condensed italic typeface at massive scale can carry an entire hero section when paired with a well-composed cutout image that creates diagonal energy across the layout

**Steal These:**
- Condensed italic uppercase headline at massive scale for instant athletic energy
- Athlete cutout overlapping multiple content zones creating depth without 3D
- Complementary blue/orange feature cards at bottom creating color tension
- Pill-shaped tag system with plus icon for category browsing
- Product sidebar with floating images that break card boundaries

---

## Fourmeta: Conversion-driven website design (8/10)
**Aesthetic:** editorial | **Category:** agency

**Design Recipe:** Use PP Editorial New (or Playfair Display as fallback) for headlines at 72-96px regular weight on #FEFEFE white, paired with Söhne/Inter for body at 16px in #060E07 near-black. Set hero text centered with mixed italic spans for emphasis. Section spacing at 120-160px. Service cards at 400px wide with muted pastel fills (#C8D5C0 sage, #F0D0C0 blush) in horizontal scroll. Use #00E85F electric green ONLY for small badges and one showcase section. Navigation in 11px uppercase wide-tracked sans-serif with pill-outline CTA. Team grid uses square headshots with 4px-radius colored corner badges.

**Dev Recipe:** Next.js 14 with App Router, self-hosted commercial fonts via next/font, GSAP with ScrollTrigger for horizontal carousel pinning and text split animations, CSS Modules with custom properties for the color system. Key: implement scroll-snap-type: x mandatory on service carousel with GSAP pin fallback for desktop.

**Core Lesson:** Typography IS the design — when your type system is strong enough (dramatic scale contrast, mixed serif/sans, decorative punctuation), you need almost nothing else.

**Steal These:**
- Parenthetical date treatment (20...19) as oversized decorative typography
- Mixed italic serif words within sans-serif headlines for selective emphasis
- Muted pastel-coded service category cards (each service gets its own color)
- Team headshots with small colored role-indicator badges at corner
- Using copyright symbols and asterisks as typographic decoration in headlines

---

## Mindbloom — Self-Development App & Learning Platform (8/10)
**Aesthetic:** organic-natural | **Category:** edtech

**Design Recipe:** Start with a warm cream background (#F9F6F1) framed by a dark indigo border (#2F2456, ~20px). Use a high-contrast transitional serif (PP Editorial New or Freight Display) at 80-96px for headlines with italic emphasis on key phrases, paired with Inter/DM Sans at 16px for body. Build an asymmetric hero: oversized botanical illustration bleeding off the left edge (40% width), headline + CTA centered-right. Pill-shaped buttons in near-black (#0A0C1A) with generous 16px 48px padding. Category tags as outlined pills with 1px border. Overlap a device mockup into the next section for depth. Keep shadows minimal, let the illustration color palette (lavender #9A98B4, coral #C64744, peach #F1BCA0) do the decorative work.

**Dev Recipe:** Next.js + Tailwind CSS with custom design tokens for the warm palette. Self-host PP Editorial New, use Framer Motion for scroll-triggered parallax on botanical SVGs and staggered text reveals. Export illustrations as optimized WebP with SVG noise overlays for the grain texture effect.

**Core Lesson:** Custom illustration as brand DNA — when your visual identity IS the design (not decoration), everything else falls into place around it.

**Steal These:**
- Dark frame border around entire page — instant premium feel with one CSS property
- Italic serif on specific words within headline for semantic emphasis
- Botanical illustration bleeding off canvas edge — breaks the grid, adds organic energy
- Overlapping avatar stack + large stat number as compact social proof
- Warm cream + indigo + coral palette — distinctive alternative to typical tech blue

---

## Wearable Tech Landing Page (8/10)
**Aesthetic:** warm-minimal | **Category:** e-commerce

**Design Recipe:** Use #F5F5F5 warm off-white background with #0C0B07 near-black text. Single sans-serif font (Inter 400/600) with 56px hero heading at -0.02em tracking. Hero: full-bleed nature photography with product composited at 40% from top, floating data card with backdrop-filter:blur(20px) and rgba(255,255,255,0.85) background positioned right. Feature grid: 2x2 cards with 48px dark rounded-square icon containers (#1A1A1A, 12px radius), 24px card padding, 16px card radius. Product collection: 3-column grid with #F0F0F0 card backgrounds, 16px radius, centered product images. Section spacing 100px, inner padding 24px, 8px base unit throughout.

**Dev Recipe:** Next.js 14 + Tailwind CSS + Framer Motion for scroll animations. Use next/image for hero composite optimization, CSS backdrop-filter for data card glass, SVG stroke-dasharray for progress arcs, and IntersectionObserver-triggered stagger animations on feature cards.

**Core Lesson:** Let product photography and data visualizations carry the color story — restraint in the UI palette makes the content feel more premium and trustworthy.

**Steal These:**
- Nature-composite hero with floating data card overlay — bridges organic and tech
- Dark rounded-square icon containers for feature grid — instant visual consistency
- No brand accent color — letting imagery be the color
- Body Report score card as hero social proof — shows product value immediately
- Phone mockup with real data widgets (sleep, biological age) as feature proof

---

## AI Travel Landing Page | Smart Trip Planning Website (8/10)
**Aesthetic:** dark-luxury | **Category:** travel

**Design Recipe:** Use #0D0603 as primary dark bg, #B54919 as warm atmospheric gradient accent (radial-gradient at section edges), #FFFFFF for all text on dark. Set hero as full-viewport cinematic photo with 60% bottom gradient overlay from transparent to #0D0603. Typography: Arabic display font at 56-64px bold for h1, 16-18px regular for body, massive 140px+ for footer brand. Pill buttons with 9999px radius, white fill on dark. Vertical sidebar nav on the reading-start side. Phone mockups at ~15° perspective tilt. Section rhythm alternates dark-photo → light-neutral (#E6E6E6) → dark-photo. 80-120px vertical section spacing.

**Dev Recipe:** Next.js with Tailwind CSS + RTL plugin (tailwindcss-rtl), Framer Motion for scroll-triggered reveals and parallax. Use next/image with priority loading for hero, CSS radial-gradient overlays via absolute-positioned pseudo-elements, and CSS perspective transforms for phone mockups. Google Fonts Tajawal for Arabic type.

**Core Lesson:** Let your color palette tell the story of the place — desert warmth (#B54919 → #5A230E → #0D0603) creates emotional context that no stock photo alone can achieve.

**Steal These:**
- Warm radial gradient at hero edges mimicking golden hour light
- Vertical sidebar navigation instead of horizontal top bar — unique for landing pages
- Massive Arabic display typography as footer anchor — turns brand name into architecture
- Avatar stack with count badge as lightweight social proof
- Alternating dark cinematic / light clean sections for visual rhythm

---
