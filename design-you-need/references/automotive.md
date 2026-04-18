# Automotive — Design Playbook

**15 projects analyzed | 9 scored 7+ | Avg: 6.4/10**

## Category Overview

**Aesthetics that work:** dark-luxury (11), bold-expressive (2), dimensional-layered (1), warm-minimal (1)
**Color strategy:** dark-theme (10), neutral-plus-accent (4), analogous (1)
**Color mode:** dark (9), mixed (4), light (2)
**Hero patterns:** layered (6), full-bleed (5), split-50-50 (2), left-right (1)
**Frameworks:** Next.js or Nuxt (3), Next.js or React (2), React Native or Flutter (2), Framer or Webflow (1)
**Animation:** GSAP (4), CSS-only (3), Lottie or React Native Reanimated (2)
**Heading fonts:** Custom geometric sans (3), SF Pro Display / Inter (2), Inter or similar geometric sans-serif, bold weight (1), Clash Display or similar geometric grotesque (1)
**Body fonts:** Inter or DM Sans (3), SF Pro Text / Inter (2), Same family, lighter weight (2), Inter or system sans-serif, regular weight (1)

## Color Rules

- **[8]** Green used only in 3D scene lighting and subtle UI accents — extremely restrained
- **[8]** Neon accents confined to 3D scene lighting only — text stays neutral white
- **[7]** Lime green used only for CTAs and small highlight text — very disciplined
- **[7]** Lime green used only on primary CTAs and one headline word — max 3-4 instances per viewport
- **[7]** Red used only for CTAs and decorative speed lines — maybe 5% of surface area
- **[7]** Cyan accent reserved for interactive elements, active states, and the charging glow — never decorative fill
- **[7]** Cyan reserved for interactive elements, active states, and energy-related visuals only
- **[7]** Cyan used only for interactive elements (View link), blue reserved for decorative waveform
- **[7]** Orange reserved exclusively for interactive elements and structural accents (left borders) — never decorative fill

### Color Craft Insights
- **[8]** The green accent is threaded through the 3D renders themselves (headlights, grille) rather than applied to UI chrome — the product IS the color story
- **[8]** The color temperature shift from cool cyan (left) to warm green (right) creates directional energy — eye naturally follows the gradient toward the brighter green, pulling attention across the full scene width
- **[7]** The ice-blue (#DCF4FE) wrapper creates a 'floating card' effect for the entire page — unusual and effective for portfolio presentation
- **[7]** The ice-blue (#DEF4FD) light sections create a water-themed throughline that connects the brand metaphor across the entire scroll without being literal
- **[7]** The red glow behind the car creates a subtle halo effect that grounds the vehicle in the composition and adds warmth to an otherwise cold palette
- **[7]** The cyan glow on dark creates an emissive-light effect that mimics actual EV dashboard aesthetics — the color temperature is carefully tuned to feel electric not medical
- **[7]** The cyan accent doubles as a semantic color — it literally represents electricity/energy, making the color system both aesthetic and meaningful
- **[7]** The outer neon purple-blue border glow creates a screen-within-screen framing that mimics an actual Tesla display bezel
- **[7]** The warm amber gradient glow bleeding through the glassmorphic card creates a focal point that draws the eye to the about section — intentional light source design

## Color Palettes

### 3D automotive configurator SaaS for enterprise Example (dark-theme / dark)
- `#03060F` — **bg-primary** — Creates cinematic void that makes 3D renders pop like a showroom
- `#07EC35` — **accent-cta** — Electric green signals tech innovation and energy against dark backdrop
- `#C8CFDD` — **text-primary** — Cool silver-white reads as premium and automotive
- `#5A9ED1` — **decorative** — Cool blue adds depth and cinematic atmosphere
- `#151F56` — **decorative** — Creates depth gradient in the atmospheric lighting
- `#3E599C` — **surface-card** — Bridges dark background to light fog for smooth depth
- `#FFFFFF` — **text-accent** — Maximum contrast for key interactive elements
- `#285151` — **decorative** — Adds color complexity to the dark palette

### 3D custom automotive wheel visualization and enterprise ordering platform Example (dark-theme / dark)
- `#02090A` — **bg-primary** — Deep black creates premium automotive showroom feel and maximizes neon contrast
- `#02961D` — **accent-primary** — Green signals performance, speed, and tech-forward automotive culture
- `#00E5FF` — **accent-secondary** — Cyan provides cool contrast to green, creates sci-fi atmosphere
- `#6C98B7` — **decorative** — Muted blue-gray adds depth without competing with neon accents
- `#FFFFFF` — **text-primary** — Maximum contrast on dark background for readability
- `#CFE0F1` — **text-secondary** — Slightly muted white reduces harshness while maintaining legibility
- `#3F5BB1` — **decorative** — Adds depth to 3D product rendering

### Subscription car wash club with multiple locations Example (dark-theme / mixed)
- `#04080C` — **bg-primary** — Deep navy-black creates premium automotive feel and makes imagery pop
- `#DCF4FE` — **bg-secondary** — Ice-blue evokes water/cleanliness, softens the dark sections
- `#75B750` — **accent-cta** — Lime green signals action and freshness, high contrast against dark
- `#FFFFFF` — **text-primary** — Maximum contrast on dark backgrounds for readability
- `#304F5B` — **surface-card** — Teal-dark bridges the navy and blue palette
- `#9BA5AE` — **text-secondary** — Muted gray for supporting content hierarchy
- `#9CD8FD` — **decorative** — Light sky blue frames the card-like page container

### Subscription car wash chain with multi-location membership Example (dark-theme / mixed)
- `#020609` — **bg-primary** — Deep navy-black evokes nighttime premium car wash atmosphere
- `#B8F030` — **accent-cta** — High-energy lime green screams freshness and pops against dark bg with extreme contrast
- `#DEF4FD` — **bg-secondary** — Ice-blue suggests water/cleanliness, softens the aggressive dark sections
- `#FFFFFF` — **text-primary** — Maximum contrast on dark backgrounds
- `#3E525A` — **text-secondary** — Muted teal-gray maintains water theme while being readable
- `#709BB3` — **decorative** — Mid-tone blue bridges dark and light palette zones
- `#97A1A8` — **surface-card** — Neutral gray for non-competing interface elements

### Luxury executive car rental and chauffeur service Example (dark-theme / dark)
- `#030303` — **bg-primary** — Black conveys luxury, exclusivity, and makes the white car pop dramatically
- `#FD0606` — **accent-cta** — Red signals urgency, speed, and premium automotive energy — Ferrari/motorsport association
- `#AB1D18` — **accent-secondary** — Deeper red adds depth and prevents flat single-tone accent
- `#EBEFEA` — **text-primary** — Off-white is softer than pure white, reduces harshness on dark bg
- `#60645E` — **surface-card** — Mid-gray creates distinct zone without competing with hero
- `#7D847C` — **text-secondary** — Muted tone for less important information hierarchy

### EV charging station finder and session manager Example (dark-theme / dark)
- `#03090B` — **bg-primary** — Deep black creates premium feel and maximizes contrast for glowing elements
- `#214A5C` — **surface-card** — Dark teal provides depth separation without breaking dark theme
- `#3C95BD` — **accent-secondary** — Mid-cyan creates the tech-blueprint aesthetic
- `#4DE8D0` — **accent-cta** — Bright cyan/aqua reads as electric energy — perfect EV metaphor
- `#99A7AB` — **text-secondary** — Muted gray maintains hierarchy without competing with accents
- `#FFFFFF` — **text-primary** — Maximum contrast on dark backgrounds
- `#B6F2BC` — **decorative** — Soft green reinforces eco/EV brand association
- `#C7F2F4` — **decorative** — Light cyan ties to accent palette in ambient presentation bg

### EV charging station finder and session manager Example (dark-theme / dark)
- `#03090B` — **bg-primary** — Near-black creates premium automotive feel and maximizes contrast for glowing elements
- `#1B475B` — **surface-card** — Dark teal adds depth without breaking the dark theme
- `#229DD5` — **accent-cta** — Electric cyan connotes energy, electricity, and EV technology
- `#3EEBD8` — **accent-secondary** — Bright cyan-teal for high-visibility CTAs and navigation paths
- `#A3B3CC` — **text-secondary** — Muted blue-gray maintains readability without competing with accents
- `#FFFFFF` — **text-primary** — Maximum contrast on dark backgrounds for key information
- `#1B6F98` — **decorative** — Mid-tone cyan bridges the gap between dark bg and bright accents

### Voice UI for Tesla in-car AI assistant Example (dark-theme / dark)
- `#040405` — **bg-primary** — Pure dark creates premium automotive feel and maximizes contrast for content
- `#1F1E5D` — **decorative** — Adds depth without competing with content, tech-forward connotation
- `#2592CA` — **accent-cta** — High-energy cyan signals interactivity and futurism
- `#2641AC` — **decorative** — Electric blue reinforces AI/voice technology association
- `#423B3F` — **surface-card** — Warm dark gray separates interactive elements from void
- `#9E9DA1` — **text-secondary** — Muted gray for secondary info hierarchy
- `#F5F5F6` — **text-primary** — Near-white for maximum readability on dark

## Typography

- **[8] Custom geometric sans — likely Neue Mont + Same family, lighter weight — **: Single-family approach keeps focus on the 3D visuals; wide geometric letterforms echo automotive badge typography
- **[8] Custom geometric sans — likely Montserra + Same family, lighter weight — **: Single font family with extreme letter-spacing variation creates hierarchy without needing a second typeface
- **[7] Clash Display or similar geometric grote + Inter or DM Sans — geometric s**: Condensed display font creates impact at large sizes while clean sans body ensures readability at small sizes
- **[7] Custom brush/distressed display — possib + Inter or similar geometric san**: Grunge display creates rebellious energy while clean sans body maintains readability and corporate trust
- **[7] Custom condensed italic sans-serif — pos + Geometric sans-serif — likely **: Condensed italic display creates motorsport energy while clean sans body maintains readability and luxury restraint
- **[7] SF Pro Display / Inter — geometric sans- + SF Pro Text / Inter — humanist**: Single family at different weights maintains clean tech aesthetic while ensuring iOS-native feel
- **[7] SF Pro Display / Inter — geometric sans- + SF Pro Text / Inter — humanist**: Single family at different weights creates clean hierarchy appropriate for data-dense mobile UI
- **[7] Custom geometric sans — likely Tesla's p + Inter or SF Pro — clean geomet**: Both geometric sans but heading is bolder/wider creating hierarchy through weight and scale alone
- **[7] Inter or similar geometric sans-serif —  + Inter or system sans-serif — n**: Single font family at different weights creates cohesion while the dark theme provides all the contrast needed

### Typography Effects
- **[8]** Ultra-wide letter-spacing on ZENO (~0.5em) creating spaced-out luxury feel — letter-spacing CSS
- **[8]** SCROLL DOWN in small-caps tracking — text-transform:uppercase + letter-spacing
- **[8]** Ultra-wide letter-spacing on ENTERPRISE creates cinematic title card feel — letter-spacing CSS property ~0.5em
- **[7]** Water texture fill on 'WASH N' letters — likely background-clip:text with water image or SVG mask
- **[7]** 'LET'S' in lime green italic creates hierarchy break in hero
- **[7]** 'ROLL' in white with slight distressed texture — possibly SVG or masked image
- **[7]** Water/foam texture fill on 'WASH N ROLL' — likely background-clip:text or SVG mask with water photo
- **[7]** Distressed/grunge texture on hero display type — pre-rendered or SVG filter
- **[7]** Car element layered between text layers via z-index stacking
- **[7]** EXECUTIVE RIDE — massive italic display text layered BEHIND car image using z-index stacking, creates depth

## Hero Patterns

- **[8] full-bleed** (3D automotive configurator SaaS for enterprise): 3D cars center → ZENO title bottom-center → subhead → scroll down CTA bottom-right
- **[8] full-bleed** (3D custom automotive wheel visualization and enter): 3D monitor center → neon glow left/right → ENTERPRISE text bottom → nav top-right
- **[7] full-bleed** (Subscription car wash club with multiple locations): Car vortex center → 'WASH N ROLL' text → wave transition bottom-right
- **[7] layered** (Subscription car wash chain with multi-location me): Car center → 'WASH N ROLL' text → 'LET'S' green accent → 'Join Today' CTA top-right
- **[7] layered** (Luxury executive car rental and chauffeur service): Giant EXECUTIVE RIDE text → car image center → SELECT button → booking bar
- **[7] layered** (EV charging station finder and session manager): greeting→search→hero-image→tabs→car-wireframe→stats
- **[7] layered** (EV charging station finder and session manager): greeting→search→charging-station-photo→tabs→car-wireframe
- **[7] split-50-50** (Voice UI for Tesla in-car AI assistant): Tesla logo → TESLA'S AURORA headline → waveform → car → model tabs
- **[7] split-50-50** (Premium auto care and detailing service center): Logo→stats(10,000+)→glassmorphic card headline→orange CTA

## Card & Component Patterns

- **[7]** Testimonial cards: white bg, ~16px radius, ~24px padding, subtle shadow, star ratings top, avatar+name bottom
- **[7]** White bg, ~16px radius, ~24px padding, subtle shadow, clean list layout with checkmarks — used for pricing tiers and testimonials
- **[7]** Dark translucent cards, ~12px radius, 16px padding, subtle border glow, vertical stack layout
- **[7]** Dark glass cards, border-radius ~16px, padding ~16px, subtle 1px border rgba(255,255,255,0.08), no hover effect visible
- **[7]** Dark glass panels, ~12px radius, ~24px padding, semi-transparent bg with backdrop-filter
- **[7]** Pricing cards — dark #1A1A1A bg, 1px border rgba(255,255,255,0.08), ~16px radius, ~32px padding, no hover visible, vertical stack layout

### Buttons

- **primary / rounded-8**: `border: 1px solid rgba(255,255,255,0.5)`
- **ghost / square**: `transparent background`
- **secondary / rounded-8**: `border: 1px solid rgba(255,255,255,0.5)`
- **primary / pill**: `border: 1px solid with lime-green accent pip beside button`
- **secondary / pill**: `Dark outline on light backgrounds`
- **primary / pill**: `border-radius:24px, lime-green bg with dark text, small circle indicator right`
- **secondary / pill**: `border:1px solid dark, transparent bg, circle indicator right`
- **ghost / pill**: `Used for 'View Washes' in pricing cards`
- **primary / rounded-4**: `background: #FD0606; text-transform: uppercase; letter-spacing: 3px`
- **secondary / rounded-4**: `Smaller red solid button for SELECT`
- **ghost / square**: `Hamburger menu icon`
- **primary / rounded-8**: `background-color: #4DE8D0; border-radius: 8px`
- **secondary / rounded-8**: `border: 1px solid rgba(255,255,255,0.3); border-radius: 8px`
- **ghost / pill**: `border: 1px solid #3C95BD; border-radius: 16px`
- **primary / pill**: `background-color with border-radius: 24px`
- **secondary / pill**: `border: 1px solid rgba(255,255,255,0.2)`
- **ghost / rounded-8**: `backdrop-filter: blur() with rgba background`
- **ghost / rounded-8**: `border: 1px solid rgba(255,255,255,0.2)`
- **primary / rounded-8**: `background with subtle gradient`
- **primary / rounded-8**: `background-color: #F7931E; border-radius: 6px`
- **secondary / pill**: `border: 1px solid rgba(255,255,255,0.3); border-radius: 24px; segmented-control pattern`

## Animation & Interaction

- **[8]** hero-carousel-slide — horizontal swipe/scroll with GSAP or Swiper
- **[8]** scroll-triggered-text-reveal — ZENO letters animate in with stagger, GSAP
- **[8]** parallax-depth — cars at different z-depths shift on scroll, GSAP ScrollTrigger
- **[8]** nav-transparency — backdrop-filter:blur on scroll, CSS transition
- **[8]** 3d-configurator — interactive WebGL car rotation/color change on product pages, Three.js
- **[8]** Slide transition between sections → GSAP ScrollTrigger or custom carousel
- **[8]** 3D scene rotation/parallax on mouse move → Three.js camera controls
- **[8]** Neon light intensity animation → WebGL shader or CSS animation
- **[8]** Scroll-down indicator pulse → CSS keyframe animation
- **[8]** Page counter transition → GSAP number morph
- **[7]** Hero text parallax scroll — GSAP ScrollTrigger
- **[7]** Gallery image hover scale — CSS transform:scale(1.05)
- **[7]** Map pin hover tooltip reveal — CSS opacity transition
- **[7]** Wave divider scroll reveal — intersection observer fade
- **[7]** Button hover fill with green accent pip animation — CSS transition
- **[7]** Hero parallax layers — car and text move at different scroll speeds → GSAP ScrollTrigger
- **[7]** Section reveal on scroll — fade-up for cards and headings → IntersectionObserver or GSAP
- **[7]** Button hover — pill fill transition with circle indicator animation → CSS transition
- **[7]** Testimonial carousel — horizontal scroll or auto-slide → Swiper.js or CSS scroll-snap
- **[7]** Gallery hover — image zoom or overlay → CSS transform:scale with overflow:hidden
- **[7]** Car entrance animation — scale + translateX reveal → GSAP timeline
- **[7]** Text reveal — EXECUTIVE RIDE letters stagger in → GSAP SplitText
- **[7]** Speed lines — draw-in from left → CSS animation or GSAP
- **[7]** Booking bar inputs — focus state highlight → CSS :focus-within
- **[7]** Vehicle carousel — SELECT implies multiple cars to swipe → Swiper.js or Framer Motion
- **[7]** tab-filter-switch → horizontal scroll with active state highlight
- **[7]** charging-pulse-animation → concentric rings pulsing outward, Lottie or Reanimated
- **[7]** route-draw-animation → SVG stroke-dashoffset animation on map
- **[7]** bottom-sheet-drag → gesture-driven panel reveal on map screen
- **[7]** real-time-percentage-update → animated number counter for charging %
- **[7]** charging-ring-pulse — concentric circles animate outward during charging — Reanimated/Lottie
- **[7]** tab-switch — filter tabs with active state slide — spring animation
- **[7]** map-route-draw — route line animates along path — SVG stroke-dashoffset
- **[7]** battery-fill — percentage counter increments in real-time — interval-based state update
- **[7]** card-scroll — horizontal scroll for nearest stations — native ScrollView with snap
- **[7]** voice-waveform-animation → Canvas API or Web Audio API visualization
- **[7]** model-tab-switch → car image crossfade with Framer-Motion
- **[7]** hover-tab-highlight → CSS transition on background opacity
- **[7]** car-entrance → GSAP slide-in with volumetric light fade
- **[7]** neon-border-pulse → CSS animation on box-shadow
- **[7]** Scroll-triggered section reveals → Framer-Motion or IntersectionObserver
- **[7]** Stats counter animation on scroll → countUp.js or Framer-Motion animate
- **[7]** Pricing toggle Packages/Services → segmented control with slide indicator
- **[7]** Service accordion expand/collapse → height animation with rotate icon
- **[7]** Hamburger menu open → slide or overlay transition

## Decorative Elements

- **volumetric-fog** at hero floor plane: `3D render composited as background-image or WebGL canvas`
- **glow** at car headlights — green and blue: `baked into 3D render, not CSS`
- **gradient-overlay** at bottom of hero for text legibility: `linear-gradient overlay or composited in render`
- **neon-tube-lights** at Left and right of 3D scene: `3D rendering with emissive materials + bloom post-processing`
- **atmospheric-haze** at Upper background: `Volumetric fog in 3D scene or radial-gradient overlay`
- **color-spill-reflections** at Floor surface under neon tubes: `PBR material reflections in 3D software`
- **green-keyboard-backlight** at Keyboard keys in 3D scene: `Emissive material on 3D model`
- **wave-divider** at Hero bottom, map section bottom: `SVG clip-path or custom shape divider`
- **water-vortex-photo** at Hero background: `Full-bleed background-image with object-fit:cover`
- **dotted-world-map** at Location section: `SVG or canvas dot-matrix map rendering`
- **green-accent-pip** at Next to CTA buttons: `Pseudo-element ::after with background-color and border-radius:50%`
- **text-water-texture** at Hero 'WASH N' letters: `background-clip:text with -webkit-text-fill-color:transparent`
- **Diagonal white shape** at Bottom-right of hero, section transitions: `clip-path or rotated div`
- **Water texture in text** at Hero headline: `background-clip:text or SVG mask`
- **Curved section dividers** at Between light/dark sections: `clip-path:ellipse or SVG path`
- **World map graphic** at Find a Location section bg: `SVG background with opacity`
- **Red speed lines** at Left side behind headline, extending horizontally: `Pseudo-elements or SVG with skewX transform`
- **Red radial glow** at Behind car, center-left: `Radial-gradient or box-shadow on pseudo-element`
- **White angular stripe** at Right edge, mid-section: `Clipped div with skewX or clip-path`
- **Dark vignette** at Edges of hero: `Radial-gradient overlay`
- **concentric-radar-rings** at charging station screen around car: `radial-gradient or SVG circles with opacity animation`
- **cyan-glow** at under charging car, active elements: `box-shadow with large spread + blur, or radial-gradient overlay`
- **wireframe-grid** at EV car visualization: `3D render with wireframe material`
- **route-line** at map screen: `SVG path with stroke-dasharray or Mapbox custom layer`
- **dark-map-tiles** at direction screen: `custom Mapbox/MapLibre dark style`
- **concentric-rings** at Charging screen around car: `border with border-radius: 50% + opacity layers`
- **glow** at Under car on charging screen: `radial-gradient or box-shadow with cyan`
- **route-line** at Map screen: `SVG path with stroke + glow filter`
- **glass-cards** at All card surfaces: `backdrop-filter: blur(20px) + rgba background`
- **neon-border-glow** at outer frame edges: `box-shadow with multiple spread values + border-image or pseudo-element gradient`
- **volumetric-light** at behind car, upper right: `radial-gradient or composited in image`
- **voice-waveform** at center-left panel bottom: `canvas animation or SVG path with glow filter`
- **geometric-wireframe** at top-left corner: `SVG overlay with low opacity`
- **glass-panel** at left content area: `backdrop-filter: blur() + semi-transparent bg`
- **mesh-gradient** at Full background image 1 — teal-to-amber through black: `radial-gradient or background-image mesh`
- **glass-card** at About section overlay on hero: `backdrop-filter: blur(20px); background: rgba(255,255,255,0.08); border: 1px solid rgba(255,255,255,0.12)`
- **amber-glow** at Behind glassmorphic card bottom-right: `radial-gradient positioned pseudo-element`
- **grid-lines** at Visible column guides throughout all sections: `repeating-linear-gradient or pseudo-element borders with rgba(255,255,255,0.05)`

## Design Recipes

### Score 8/10 — dark-luxury — 3D automotive configurator SaaS for enterprise

**Design Recipe:** Use #03060F near-black background with #C8CFDD silver text. Set hero headline in a wide geometric sans (Neue Montreal/PP Neue Machina) at 100-120px, font-weight:300, letter-spacing:0.5em, text-transform:uppercase. Full-viewport hero with cinematic 3D renders as background. Nav: transparent, logo left, 3 links center-left, outline button right with 1px rgba(255,255,255,0.4) border and border-radius:8px. Accent color #07EC35 used ONLY within imagery, never on UI buttons. Bottom of hero: subtle linear-gradient from transparent to rgba(3,6,15,0.8) for text legibility. Slide counter bottom-right in 12px uppercase tracking.

**Dev Recipe:** Next.js 14 + Three.js/React Three Fiber for 3D, GSAP ScrollTrigger for carousel and text reveals, Tailwind CSS for layout utilities. Key: preload 3D assets with suspense boundaries, use draco-compressed glTF models, implement intersection observer for lazy WebGL initialization.

**Core Lesson:** When your product IS visual (3D renders, cars, luxury goods), strip the UI to near-nothing and let the imagery dominate — the restraint IS the design.

**Steal These:**
- Threading accent color through 3D scene lighting rather than UI elements
- Ultra-wide letter-spacing (0.5em) on single-word hero titles for luxury feel
- Slide counter as minimal 2/4 fraction with SCROLL DOWN label — functional yet decorative
- Atmospheric volumetric fog in 3D renders creating natural depth gradient
- Transparent nav with no background — trusting the dark hero to provide contrast

**Weaknesses:** Portfolio includes unrelated screens (e-commerce, crypto, social app) that fragment the automotive story, No visible CTA in hero — relies entirely on scroll prompt which may lose impatient users, Single-slide hero view gives no indication of interactive 3D configurator capability — the core product value is hidden

---

### Score 8/10 — dark-luxury — 3D custom automotive wheel visualization and enterprise orde

**Design Recipe:** Start with #02090A pure dark background. Place a full-viewport 3D scene as hero. Use two vertical neon light sources: cyan #00E5FF left, green #02961D right, casting colored reflections on a dark reflective floor. Product sits center in a monitor mockup. Headline uses geometric sans (Montserrat/Rajdhani) at 120px, font-weight 300, letter-spacing 0.5em, uppercase, white #FFFFFF. Subtitle at 20px, letter-spacing 0.15em. Nav is minimal: logo top-left, two items top-right with outlined button border-radius 8px. Slide counter bottom-right at 24px light weight.

**Dev Recipe:** Next.js + Three.js (react-three-fiber) for 3D scene with GLTF models, emissive neon materials, and PBR floor reflections. GSAP ScrollTrigger for section transitions. Tailwind for minimal UI chrome. Pre-render 3D as video fallback for mobile performance.

**Core Lesson:** Environmental lighting in 3D scenes creates mood that flat design simply cannot — colored light sources that cast realistic spill onto surfaces transform a product showcase into an experience

**Steal These:**
- Dual-colored neon light tubes as environmental lighting creating gradient color spill across scene
- Ultra-wide letter-spacing on hero headline for cinematic title card effect
- Multi-device mockup (monitor + phone + keyboard) as single composed 3D scene rather than separate elements
- Slide counter (3/4) with SCROLL DOWN as subtle navigation affordance
- Minimal nav with only 2 items — forces focus on the visual experience

**Weaknesses:** Heavy 3D scene will have significant load time and poor mobile performance without careful optimization, Single typography trick (wide spacing) — needs more variety for multi-section pages, No visible CTA or conversion path in hero — purely atmospheric, may hurt conversion

---

### Score 7/10 — bold-expressive — Subscription car wash club with multiple locations

**Design Recipe:** Use #04080C dark navy for hero/dark sections, #DCF4FE ice-blue for light sections, #75B750 lime-green strictly for CTAs. Set headings in a condensed black-weight grotesque (Clash Display) at 120px+ hero / 48px sections, all uppercase with -2% letter-spacing. Create wave SVG dividers between dark/light sections using white fill. Float the entire page as a rounded-16px card on the ice-blue background. Use background-clip:text with thematic imagery for hero display text. Gallery images should be slightly rotated (2-3deg) with 12px border-radius and white borders.

**Dev Recipe:** Build in Next.js or Framer with GSAP for hero text reveal and scroll parallax. Use Tailwind for utility styling, custom SVG clip-paths for wave dividers, and CSS background-clip:text for the textured hero typography. Dot-matrix map can be an SVG with interactive Framer Motion tooltips.

**Core Lesson:** A single spectacular hero section can carry an entire design — but every subsequent section must maintain that same level of thematic commitment

**Steal These:**
- Water-texture fill inside hero typography via background-clip:text
- Green accent pip/dot beside CTA buttons as a micro-branding element
- Entire page floating as rounded card on colored background
- Wave SVG dividers as thematic water-themed section transitions
- Aerial overhead car photo as hero — unexpected angle creates intrigue

**Weaknesses:** Comparison table is a SaaS pattern that feels forced for a car wash business, Testimonials section uses generic Rareblocks copy — breaks immersion, Gallery section layout is basic 4-column grid — could use more dynamic masonry or scroll-driven animation to match hero energy

---

### Score 7/10 — bold-expressive — Subscription car wash chain with multi-location membership

**Design Recipe:** Dark navy bg (#020609) with ice-blue (#DEF4FD) alternating sections. Lime green (#B8F030) accent ONLY on primary CTAs and one accent word. Hero: full-viewport aerial water photo, 140px+ distressed uppercase display font with water-texture fill via background-clip:text, car image layered between text layers at z-index 2-3. Pill-shaped buttons with 24px radius, small 12px circle indicator on right edge. Body sections: 1200px max-width, 3-column pricing cards with white bg and 16px radius, diagonal clip-path section dividers at ~5deg. Footer: 4-column dark layout.

**Dev Recipe:** Next.js + Tailwind + GSAP ScrollTrigger for hero parallax. Hero needs absolute-positioned layers: bg-image z-0, back-text z-1, car-image z-2, front-text z-3. Use background-clip:text on headline with water photo background. Clip-path for section dividers. Swiper.js for testimonial carousel.

**Core Lesson:** One extraordinary hero section can carry an entire design — invest 60% of creative energy into the first viewport.

**Steal These:**
- Car physically breaking through headline text via z-index layering
- Water/foam texture as text fill — perfect brand-content integration
- Lime green used on exactly 2-3 elements per viewport for maximum pop
- Pill button with small circle indicator dot — distinctive micro-detail
- Diagonal white shape as hero-to-content transition element

**Weaknesses:** Below-fold sections are generic template blocks that undermine the hero's creativity, Rareblocks template components visible — testimonials and comparison table feel stock, Mobile version compresses the hero composition poorly — text layering loses impact at small sizes

---

### Score 7/10 — dark-luxury — Luxury executive car rental and chauffeur service

**Design Recipe:** Use #030303 black background with #EBEFEA off-white text. Set massive 120-160px italic condensed uppercase display font (try Bebas Neue Pro Italic or Oswald Italic) as background layer. Place high-res product cutout PNG at z-index above text. Add #FD0606 red accent at 5% usage — only CTAs and 2-3 decorative speed lines using 15deg skew. Booking/action bar at bottom in #4A4D48 gray with 3-column grid inputs. All labels uppercase with 3-6px letter-spacing. Radial red glow (#AB1D18 at 40% opacity) behind product center.

**Dev Recipe:** Next.js + Tailwind + GSAP for timeline animations. Hero uses CSS Grid with absolute-positioned layers: bg-text at z-10, red-glow pseudo at z-20, car PNG at z-30, UI overlay at z-40. GSAP ScrollTrigger for entrance sequence, SplitText for headline animation. Booking bar is position:fixed bottom with backdrop-filter:blur.

**Core Lesson:** Layering a product image OVER display typography creates instant cinematic depth and makes the product feel larger than life

**Steal These:**
- Product image layered over massive display text with z-index depth
- Angled red speed-line decorations for automotive energy
- Radial color glow behind hero product to create focal warmth
- Ultra-wide letter-spacing on uppercase labels for luxury feel
- Docked booking bar with icon+label+placeholder input pattern

**Weaknesses:** Only one viewport shown — no responsive or scroll consideration visible, ROMANO branding on car bumper feels like an afterthought/watermark placement, Right-side white angular stripe feels unresolved — doesn't connect to any design system element

---

### Score 7/10 — dark-luxury — EV charging station finder and session manager

**Design Recipe:** Use #03090B deep black background with #214A5C for card surfaces (12px radius, 1px border rgba(60,149,189,0.2)). Accent everything interactive with #4DE8D0 cyan — buttons, active tabs, glow effects. Typography in SF Pro or Inter: headings 28px bold white, stats 24px bold, body 14px #99A7AB. Create depth with box-shadow: 0 0 20px rgba(77,232,208,0.25) on active elements. Map uses custom dark tiles with #1A2A35 roads and cyan route lines. Spacing: 16px horizontal margins, 12px card gaps, 8px base unit.

**Dev Recipe:** React Native with react-native-maps (custom Mapbox dark style), react-native-reanimated for charging animations, @gorhom/bottom-sheet for map panel. Style with a dark theme token system: bg.primary=#03090B, bg.card=#0D1B22, accent=#4DE8D0, text.primary=#FFF, text.secondary=#99A7AB.

**Core Lesson:** Emissive cyan glow on deep black creates an 'electric energy' visual language that perfectly maps to the EV product domain — color metaphor alignment is everything

**Steal These:**
- Wireframe/blueprint car visualization as vehicle status display
- Concentric radar ring animation for active charging state
- Cyan glow-based depth system instead of traditional shadows
- Dark custom map tiles that match the app's color palette
- Three-stat row pattern (time, range, cost) for quick scanning

**Weaknesses:** Second image (pregnancy app) is completely unrelated — dilutes portfolio coherence, Station list cards feel cramped — thumbnail + text + rating needs more breathing room, No empty states, error states, or edge cases shown — production gaps

---

### Score 7/10 — dark-luxury — EV charging station finder and session manager

**Design Recipe:** Start with #03090B background. Use #1B475B for card surfaces with 1px rgba(255,255,255,0.08) borders and 16px border-radius. Apply backdrop-filter: blur(20px) on cards. Single accent #229DD5 for all interactive elements. White (#FFFFFF) for primary text, #A3B3CC for secondary. SF Pro or Inter at 24/18/14/12px scale. 16px horizontal padding, 8px base spacing unit. Glass-morphic search bars with pill shape. Stats in 3-column grid separated by 1px vertical dividers.

**Dev Recipe:** React Native with NativeWind for styling, react-native-maps with custom dark tile layer, Reanimated 3 for charging animations, Lottie for the concentric ring pulse. Key CSS: backdrop-filter blur, radial gradients for glow, rgba borders for glass edges.

**Core Lesson:** In dark UI, a single accent color tied to the product's core concept (cyan = electricity) creates both visual cohesion and semantic meaning

**Steal These:**
- X-ray wireframe car as a real-time battery status visualization
- Concentric ring animation radiating from charging vehicle
- Cyan-only accent system where color = electricity metaphor
- 3-column stat bar with vertical dividers for quick-scan data
- Dark map tiles color-matched to app palette for seamless integration

**Weaknesses:** No bottom navigation bar — unclear how users switch between main sections, The 55.55% charging display feels like placeholder data — real UX would show whole numbers, Station list cards are cut off with no clear scroll affordance — needs peek/shadow hint

---

### Score 7/10 — dark-luxury — Voice UI for Tesla in-car AI assistant

**Design Recipe:** Start with #040405 pure dark bg. Frame entire viewport with 2px border using gradient from #1F1E5D to #7B2FBE with 20px box-shadow glow. Split layout 55/45 — left glass panel (rgba(255,255,255,0.03) bg + backdrop-filter:blur(20px)) overlapping right product image. Use #F5F5F6 for headlines at 48px black weight uppercase, #9E9DA1 for subtitles at 18px regular. Place blue waveform (#2641AC to #6B3FA0) as hero focal point. Bottom tab bar with #423B3F pill backgrounds and #2592CA for active link color.

**Dev Recipe:** Next.js + Tailwind dark theme + Framer Motion for tab transitions and car reveals. Web Audio API with Canvas for real-time waveform viz, GSAP for volumetric light parallax, backdrop-filter for glass panels.

**Core Lesson:** A single animated focal element (the waveform) can anchor an entire concept and make abstract technology feel tangible

**Steal These:**
- Neon gradient border glow as viewport frame — instant premium feel
- Voice waveform as hero visual — makes invisible tech visible
- Glass panel overlapping product photo — creates depth cheaply
- Cyan accent reserved ONLY for interactive elements — disciplined
- Model selector tabs as horizontal scroll nav at bottom

**Weaknesses:** Bottom tabs are cropped/incomplete — unclear full interaction model, Left panel overlap with car image creates awkward mid-zone where car is partially obscured, No clear CTA or user journey — beautiful but where do you click?

---

### Score 7/10 — dark-luxury — Premium auto care and detailing service center

**Design Recipe:** Use #0A0A0A pure dark background with #FFFFFF headlines and #888888 body text. Single accent #F7931E orange for ALL interactive elements and 3px left-border heading accents only. Set up a visible 4-column grid at 1100px max-width with rgba(255,255,255,0.06) column borders. Hero uses a mesh gradient background (#011327 top-left, #843201 bottom-right) with a glassmorphic card (backdrop-filter:blur(20px), rgba(255,255,255,0.08) bg, 1px rgba border). Typography is a single geometric sans at 64px/light for stats, 48-56px/bold for headings, 15px/regular for body. Pricing cards use #1A1A1A surface with subtle borders.

**Dev Recipe:** Build in Next.js or Framer with Tailwind CSS for utility spacing. Use Framer Motion for scroll-triggered reveals and counter animations. Key CSS: backdrop-filter for glass cards, layered radial-gradients for mesh background, CSS Grid for the 4-column visible guide system with border-right on columns.

**Core Lesson:** Restraint with a single accent color on a dark canvas creates more visual impact than a complex palette — let the orange do all the heavy lifting.

**Steal These:**
- Visible grid column guides as a design element — adds intentionality
- Orange left-border accent on section headings — simple but effective hierarchy marker
- Glassmorphic card with ambient glow bleeding through from background gradient
- Stats column with oversized light-weight numbers and thin dividers
- Segmented pill toggle for pricing categories with contained pill indicator

**Weaknesses:** Generic placeholder copy ('Happy Customers', 'Years Experience') — needs real brand voice, Hamburger nav on desktop wastes opportunity for visible navigation links, Service accordion section feels cramped — image and text compete for space in the expanded state

---

### Score 6/10 — dark-luxury — Luxury used car dealership with online inventory and trade-i

**Design Recipe:** Use #070709 dark overlay on full-bleed hero photography, #F7F7F7 light gray page backgrounds, #FFFFFF card surfaces, and #B10809 red exclusively for CTAs and active states. Set typography in Inter at 48/32/20/16/12px scale, all sans-serif. Cards: white, minimal border-radius (2-4px), subtle box-shadow (0 2px 8px rgba(0,0,0,0.08)), image taking 60% of card height. Float the search panel over the hero with negative margin-top ~-60px. Inventory page: 240px fixed sidebar left, 3-column card grid right with 24px gutters. Price badges: absolute positioned red pills on card images.

**Dev Recipe:** Next.js with Tailwind CSS, custom components (no UI lib needed). Use React state or URL search params for inventory filtering, rc-slider for price range, and a simple state machine or useState for the 3-step sell/trade-in wizard. Hero carousel with Embla or Swiper.

**Core Lesson:** In automotive/marketplace design, let the product photography do the heavy lifting — keep the UI chrome minimal and neutral so vehicles are the hero.

**Steal These:**
- Floating search panel overlapping hero-to-content transition — creates visual depth cheaply
- Red price badges on card images — instant scannability for the most important data point
- Filter sidebar with grouped checkboxes + range slider — comprehensive yet not overwhelming
- 3-step wizard with visual stepper for complex forms — reduces cognitive load
- Consistent card layout with tag pills (Petrol, Automatic, Coupe) for quick attribute scanning

**Weaknesses:** Typography is generic — no distinctive type choices or creative sizing to create brand identity, Hero text lacks text-shadow or better contrast treatment — readability depends on image darkness, No microinteractions or animation craft visible — feels static and template-like

---

### Score 6/10 — dark-luxury — Car wash and repair service booking template

**Design Recipe:** Use #000000 backgrounds with #FFFFFF text and #FF7A00 as sole accent — apply orange ONLY to primary CTAs, logo, highlighted headline words, and 3px left-border markers on section headings. Set Inter Display Semibold at 48-56px for H1, Inter Regular 14-16px for body, on a 1440px 12-column grid with 80px margins and 20px gutters. Dark photography with warm desaturated treatment overlaid with linear-gradient(to right, rgba(0,0,0,0.7), transparent) for text legibility. Secondary buttons use 1px white/30% opacity borders on transparent backgrounds.

**Dev Recipe:** Next.js + Tailwind CSS with CSS Grid for the 12/6 column responsive system; use next/image for optimized dark photography with overlay divs using bg-gradient-to-r. Framer Motion for quote popup entrance animation and scroll-triggered nav background blur via backdrop-filter.

**Core Lesson:** A limited dark palette gains sophistication when you derive a desaturated tertiary tone from your accent color (#472C14 from #FF7A00) to bridge the gap between extremes

**Steal These:**
- Orange left-border accent on headings as consistent visual anchor across all pages
- Floating quote/phone CTA popup with glassmorphism on service pages
- Dual CTA pattern: solid primary + outline secondary side by side
- Deriving warm brown (#472C14) from accent orange for tonal depth
- Typewriter cursor underscore after hero headline keyword

**Weaknesses:** Orange-on-black automotive template is extremely common — needs a differentiator, Mobile grid at 6 columns with 16px margins may feel cramped for content-heavy service pages, Blog article page body text appears small and dense — needs better line-height and max-width constraint for readability

---

### Score 5/10 — dimensional-layered — Online car marketplace for new and used vehicles

**Design Recipe:** Use a full-viewport hero with a high-quality outdoor car photograph as background. Overlay 2-3 white cards (#FFFFFF, border-radius:16px, box-shadow: 0 8px 32px rgba(0,0,0,0.1)) positioned at right-center, staggered with 20px offset. Headline at 56px bold dark navy (#1A2B5F) geometric sans-serif (Inter/DM Sans) left-aligned. Pill-shaped CTA at 48px height with navy fill and white text. Use pill tags (border-radius:9999px) with light gray (#F0F0F0) inactive and navy active states. Keep palette to navy + white + natural photo colors only.

**Dev Recipe:** Next.js + Tailwind CSS with a hero section using relative positioning container, absolute-positioned card components with responsive breakpoint adjustments. Framer Motion for card entrance stagger animations and tag toggle micro-interactions.

**Core Lesson:** Layered card compositions over full-bleed photography create instant depth, but without custom imagery and a coherent color system they read as template work.

**Steal These:**
- Cards overlapping a full-bleed hero image for instant visual depth
- Pill-shaped filter tags with dark active state for category switching
- Connector line from card to thumbnail creating visual relationship
- Navy-on-white CTA with arrow icon for clear action hierarchy
- Minimal nav with globe icon language selector pattern

**Weaknesses:** Stock photography destroys brand authenticity — needs custom vehicle shoots or 3D renders, Declared color palette completely mismatches actual design — no reds visible anywhere, Bottom-left card is cut off awkwardly suggesting incomplete responsive consideration

---

### Score 5/10 — dark-luxury — Luxury car rental and browsing mobile app

**Design Recipe:** Use #0A0908 dark backgrounds with #FFFFFF text. Accent with #F5C518 yellow for interactive elements only — borders, toggles, CTAs. Headlines in italic serif (Playfair Display, 32-36px bold italic) on light gradient backgrounds (#E99577 → #72838B peach-to-steel wash). Cards at 16px radius, 16px padding, dark fill. CTA buttons as pills with linear-gradient(90deg, #D5461F, #F5C518). Feature one card with yellow 2px border to create focal hierarchy. Use high-quality dark-lit car photography as hero imagery.

**Dev Recipe:** React Native with custom components, Reanimated for transitions. Dark theme with StyleSheet, linear-gradient via react-native-linear-gradient, backdrop-filter equivalent via BlurView from @react-native-community/blur for glass segmented controls.

**Core Lesson:** Dark luxury UI needs restraint — one strong accent color (gold/yellow) on black with premium photography does 90% of the work

**Steal These:**
- Yellow border highlight on a single featured card to create visual hierarchy
- Wave/organic divider between hero image and content area
- Pill tags with icon+text for metadata (location, seats, price)
- Interior/Exterior glass segmented control pattern
- Gradient CTA button (warm orange → gold) against dark UI

**Weaknesses:** Four unrelated app concepts dilute portfolio impact — pick one and go deep, Italic serif at mobile sizes hurts scannability, Education app illustrations clash violently with the premium aesthetic of other screens

---

### Score 5/10 — warm-minimal — Luxury sports car brand landing page

**Design Recipe:** Use a full-viewport linear-gradient from #FAD9A1 to #F88E29. Set a massive condensed italic headline (~160px, Dharma Gothic or Knockout) in white. Layer a product image over the text using z-index stacking (text z:1, car z:2). Add 12% opacity decorative elements (wheel shapes) as background texture. Place body copy bottom-left in 18px DM Sans white. Use a small info card (border-radius 8px, golden #D4A030 bg) bottom-right with thumbnail + caption. Nav: logo left, 2 links + solid orange CTA button right.

**Dev Recipe:** Next.js + Tailwind CSS with GSAP for entrance animations. Key technique: split hero into 3 z-layers (bg-gradient → headline-text → car-image) using absolute positioning within a relative container; use mask-image on a flipped duplicate for the car reflection effect.

**Core Lesson:** Monochromatic color palettes that match the hero product create instant visual cohesion — let the product define the palette.

**Steal These:**
- Product-color-matched monochromatic gradient background
- Text-behind-product z-index layering for depth
- Faded product detail (wheels) as decorative watermark texture
- Car reflection using flipped + masked duplicate
- Oversized condensed italic display type for automotive energy

**Weaknesses:** White text on mid-orange fails WCAG AA — needs darker gradient or text shadow, Bottom-right card with stock photo feels disconnected from the brand narrative, No clear CTA hierarchy — 'Get a quote' button is tiny and lost in the nav

---

### Score 4/10 — dark-luxury — Luxury car marketplace and community platform

**Design Recipe:** Use #000000 bg with #281E1E card surfaces. Set Bruno Ace for display headings at 32-48px uppercase with 0.05em letter-spacing. Body in Helvetica Neue Light 14-16px #ECECEB. Pill navbar: border-radius 40px, 1px border rgba(255,255,255,0.15), padding 12px 32px. Full-bleed hero with dramatic side-profile car photo, radial vignette overlay, centered ghost CTA button. Product cards: #0A0A0A fill, 1px border #222, 12px radius, 20px padding. Add a proper gold accent #BC944F for CTAs and hover states to break monotony.

**Dev Recipe:** Next.js with Tailwind CSS dark mode. Google Fonts for Bruno Ace + Jura. Use CSS grid for product cards (auto-fill, minmax(280px, 1fr)), intersection-observer for scroll-triggered fade-ins, and CSS custom properties for the dark color tokens.

**Core Lesson:** A dramatic hero can't carry an entire page — every section needs the same level of intentional design

**Steal These:**
- Pill-shaped navbar container floating over dark hero
- Full-bleed dramatic car photography as hero with vignette
- Multicolor gradient accent line as subtle brand element
- Shop-by-brands logo strip for quick brand navigation
- Dark-on-dark card surfaces with minimal borders

**Weaknesses:** Identical placeholder content across cards and testimonials destroys credibility, No clear visual hierarchy between sections — everything same weight, Mobile layout has broken spacing and cramped elements — needs proper responsive grid

---

## Slop Patterns to Avoid

### Score 4/10
- Placeholder testimonials with identical 'User1341398' and same text repeated 3x
- Featured cars section shows same 'Lamborghini Hurricane' card repeated with identical prices
- Inconsistent spacing and alignment across mobile sections
- Generic stock car hero image without custom treatment
- Navbar gradient line decoration feels unfinished — random color stops

### Score 5/10
- Multiple unrelated projects crammed into one portfolio shot (fintech app, shopping app, email dashboard)
- Stock photography of generic SUV on grass — no brand-specific imagery
- Color palette in metadata (#721008 reds) doesn't match actual design (blues/whites)
- Floating card overlays feel templated — no unique interaction concept
- Typography hierarchy is decent but headline kerning is default

### Score 5/10
- Multiple unrelated app concepts crammed into one portfolio post (cars, fitness, solar, education)
- Laurel wreath decoration is a generic Dribbble cliché
- Inconsistent design systems across the 4 app concepts — no unified vision
- Education app uses clip-art-quality illustrations mixed with UI elements
- Solar energy app has genuinely thoughtful data visualization hierarchy

### Score 5/10
- AI-generated car image — lighting inconsistencies on body panels
- Watermark-style wheel graphics as lazy decorative filler
- Generic stock photo of woman in car — no brand cohesion
- Typography clipping behind car is nice concept but poorly masked
- Card in bottom-right feels tacked on, breaks layout logic
