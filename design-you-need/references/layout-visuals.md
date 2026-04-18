# Layout, Spacing & Visual Elements

## Grid System (from 399 projects)
- **12-col, ~1200px max-width, ~24px gutter**: 202/399 (51%) — THE standard
- **12-col, ~1280px**: 7 — slightly wider for agency/portfolio
- **12-col, ~1140px**: 6 — tighter for content-heavy
- **Asymmetric within grid**: common in 8+ score projects

## Hero Eye Flow Patterns
How users scan the hero — from 9/10 projects:

- **[9] Maria Eli: Fused Identities — Artist Portfolio**: Name 'MARiA ELi' top-right → portrait left → tagline 'Layered Realities' → red dot CTA
- **[9] Diligence Infrastructure for Private Capital**: Floating annotations mid-page → massive headline bottom-left → subhead/CTA bottom-right
- **[9] AMARI: Luxury Riverside Residences**: Flower motion trail → AMARI logotype center → 'Eternal beauty' left → 'by the river' right → 'COMING SOON' bottom
- **[9] Editorial Skincare Web Explorations with Golden Canyon Grid**: Headline 'Essential by Design' → face/eye in photo → '01' counter → 'Explore Collection' CTA → bottom bar
- **[9] Interval. Cafe Brand Identity. Typography Layouts & Visuals.**: Top-left INTERVAL logo → center headline → CTA button → bottom contact bar
- **[9] PAWS & CO. — Luxury Pet Hotel Website**: ELITE PETS RETREAT headline → Dalmatian face → coral background shape → left body copy → CTA button → feature pills
- **[9] Illustrated Animated Map of Kyiv, Ukraine. Landing Page.**: KYIV title center → surrounding landmark ring clockwise → down arrow
- **[9] The new illustrations for the Skretting company (Calendar 2026)**: Giant '2026' top-right → Skretting logo → red-gloved hand with test tubes → panoramic scene bottom-left to right
- **[9] The XIX — Cinematic 3D Website & Promo Animation**: 3D car center-right → screen-within-scene left → XIX 3D title bottom-center → scroll down bottom-right
- **[9] Mertana - Ski Brand**: Giant 'Mertana' type → skier action shot → 'Experience Consistency Quality Dedication' → bottom tagline
- **[9] Fourmeta website: Future-ready digital experience**: headline-serif→laptop-mockup→service-badge-bottom-right→nav
- **[9] Product for a Productivity Product ✦ Daylier**: Headline 'Stay on Track Today' → Keep it going badge → Customize button
- **[9] Stormie - Art Director Website Portfolio**: Stormie italic → ART DIRECTOR bold → [SINCE 2012] → nav corners
- **[9] Origin creative landing page**: Headline 'The Divinity of Purpose' → hero photo of man → ORG© brand mark → 'Get in touch' CTA
- **[9] XIX3D Website — Cinematic 3D Animation**: Car center → wireframe ghost → 'STUDIOS' text → 'High Quality Content' → scroll indicator
- **[9] Golf Club Landing Page Design**: Center logo → people in photo → large headline bottom-left → subhead center-bottom
- **[9] Case Study: Landing Page for Creator Growth Platform**: Headline center → subhead → CTA button → photo grid bottom
- **[9] Fourmeta services, but make them feel alive**: Center card (Branding Services) → right card (Design & Animation) → left card (Digital Product Development) → scroll indicator bottom
- **[8] Baumkontrolle im Netz - Web Design**: Portrait face → headline text → CTA buttons
- **[8] Epitope — Biotech Visual Identity**: 3D visual → headline → subhead → CTA
- **[8] Kaisen Ramen — Motion-Driven Landing Page 🍜**: KAISEN RAMEN title → center ramen bowl → KARA TORI label → BUY NOW CTA → flanking bowls
- **[8] Fine Dine Club Website | Selected Screens**: Center food image → headline text → EXPLORE CTA → PREV/NEXT navigation
- **[8] Modern Minimalist Blockchain UI**: 3D coin → NEXA headline → subhead → CTA → stats bottom-right
- **[8] MVRDP — Architectural Visualization Concept**: MVRDP letterforms → architectural render → tagline → service category pills
- **[8] ARCILLA: Luxury Residential Masterpiece**: ARCILLA headline → building render right → 'BY JOE ADSETT' → tagline → CTA button

## Hero Elements (what goes in the hero)

- **headline**: 342 projects
- **subhead**: 277 projects
- **badge**: 99 projects
- **cta-button**: 93 projects
- **cta**: 73 projects
- **image**: 49 projects
- **dual-cta**: 40 projects
- **nav**: 33 projects
- **background-image**: 29 projects
- **stats**: 21 projects
- **hero-image**: 19 projects
- **scroll-indicator**: 16 projects
- **product-image**: 15 projects
- **search-bar**: 14 projects
- **cta-pair**: 13 projects
- **cta-primary**: 13 projects
- **illustration**: 13 projects
- **cta-secondary**: 12 projects
- **logo**: 12 projects
- **video-thumbnail**: 12 projects

## Section Types (what sections do top projects have)

- **hero**: 188
- **footer**: 143
- **nav**: 74
- **testimonials**: 71
- **logo-bar**: 31
- **cta**: 26
- **stats**: 25
- **faq**: 23
- **pricing**: 21
- **services**: 20
- **final-cta**: 17
- **features-grid**: 16
- **cta-banner**: 16
- **why-choose-us**: 14
- **features**: 13
- **about**: 12
- **product-grid**: 11
- **about-stats**: 11
- **contact-form**: 11
- **how-it-works**: 10
- **hero-split**: 9
- **newsletter**: 8
- **team**: 8
- **mission-statement**: 8
- **announcement-bar**: 8
- **testimonial**: 8
- **cta-footer**: 8
- **process**: 6
- **stats-bar**: 6
- **newsletter-cta**: 6

## Decorative Elements with CSS Techniques
From projects scoring 8+:

- **[9] Red circle** at CTA sections, hero badge: `border-radius:50% with solid fill`
- **[9] Overlapping text-on-image** at CTA contact section: `z-index layering, possibly mix-blend-mode:multiply`
- **[9] Diamond/rotated image mask** at Services section behind portrait: `clip-path:polygon or transform:rotate(45deg) with overflow:hidden`
- **[9] gradient-overlay** at Hero bottom third: `linear-gradient with transparent-to-dark`
- **[9] glass-card** at Foundations text overlay on image: `backdrop-filter: blur() with semi-transparent bg`
- **[9] border-glow** at Card edges on dark state: `border with rgba white + subtle box-shadow`
- **[9] drop-shadow** at Entire hero card container: `box-shadow with large spread, low opacity`
- **[9] motion-trail-flower** at Hero — calla lily with vertical slice/stagger animation trail: `WebGL or canvas-based image slicing, possibly Three.js displacement or GSAP stagger with clip-path`
- **[9] brown-frame-border** at Gallery carousel — thick brown border frames the central image: `CSS border or padding with background-color on wrapper`
- **[9] vignette-gradient** at Hero background — radial gradient darkening edges: `radial-gradient or pseudo-element overlay`
- **[9] Diamond/rhombus geometric overlay** at Behind and around hero image: `SVG or CSS clip-path with opacity/mix-blend-mode`
- **[9] Thin vertical rule** at Right side next to slide counter: `border-right or pseudo-element`
- **[9] Em-dash horizontal rules** at Nav separators, bottom ticker connections: `border-top or inline SVG`
- **[9] Four-point star** at Bottom-left above 'Nourishing': `SVG icon or CSS clip-path`
- **[9] Golden Canyon Grid** at Full-page compositional guide: `Design-time only — golden ratio + diagonal intersections`
- **[9] color-blocked tiles** at Typography specimen grid: `CSS Grid with background-color per cell`
- **[9] dark overlay on hero image** at Chumakov mockup: `background: linear-gradient or rgba overlay`
- **[9] warm vignette** at Hapr mockup edges: `radial-gradient or box-shadow:inset`
- **[9] coral-rounded-rectangle** at Behind Dalmatian center-bottom: `border-radius ~24px, background-color, z-index behind image`
- **[9] dark-frame-border** at Entire page perimeter: `body background #050407 with inner container on cream, or border/outline`
- **[9] hand-drawn-squiggle** at Under avatar stack: `SVG inline or background-image`
- **[9] wave-lines** at CTA section (image 2) bottom: `SVG path or CSS border animation`
- **[9] landmark-ring** at Hero — buildings arranged in oval around title: `Absolute positioning or CSS grid with custom placement`
- **[9] metro-lines** at Full map — colored transit lines: `SVG paths with stroke-dasharray animation`
- **[9] trees-parks** at Scattered across map: `SVG sprites or individual positioned elements`
- **[9] grain-noise-texture** at Entire illustration surface, varying density: `n/a — raster illustration technique, stipple/noise brush`
- **[9] atmospheric-haze** at Background mountains, sky, distant elements: `n/a — painted opacity layers`
- **[9] flowing-ribbon-shapes** at Cover — organic flowing forms in sky area: `n/a — illustrated decorative element`
- **[9] Volumetric light beams** at 3D scene — vertical pillars of light: `WebGL/Three.js volumetric fog shader`
- **[9] Neon glow strips** at Floor-level in 3D scene: `Emissive materials + bloom post-processing`
- **[9] Screen-within-scene** at Left side — floating display showing alternate car view: `Render-to-texture or composited plane in 3D`
- **[9] dashed-border-rectangles** at Category gallery placeholder slots: `border-style: dashed with low-opacity stroke`
- **[9] thin-rule-dividers** at Between sections and within grids: `border-top: 1px solid rgba(255,255,255,0.1)`
- **[9] 3D-laptop-mockup** at Hero center: `transform:perspective() rotateY() — likely Three.js or Spline embed`
- **[9] green-fabric-texture** at Hero background: `background-image with overlay gradient`
- **[9] floating-service-badges** at Bottom-right of hero and sections: `position:absolute with backdrop-filter:blur`
- **[9] dark-vignette** at Hero edges: `radial-gradient overlay`
- **[9] amber-glow** at Inside Deep Work and Attention Quality cards: `radial-gradient with warm amber, possibly mix-blend-mode: screen`
- **[9] dashed-line** at Focus Stability chart threshold line: `border-style: dashed or SVG stroke-dasharray`
- **[9] card-border-glow** at Subtle warm border on metric cards: `box-shadow: 0 0 20px rgba(176,142,63,0.1)`
- **[9] bar-chart-glow** at Focus Stability amber bars: `box-shadow on individual bars or filter: drop-shadow`
- **[9] horizontal-rule** at Between hero and portfolio grid, between sections: `border-top with dot/circle start marker`
- **[9] background-bleed-image** at Behind content panel on scroll (screenshot 4): `position:fixed or sticky background with z-index layering`
- **[9] ghost-text-watermark** at Behind/above content panel edge: `Large font-size, opacity near 0, overflow:hidden on parent`
- **[9] cream-panel-frame** at Main content area: `Centered container with margin, background-color on inner div`
- **[9] atmospheric-sky-gradient** at Full page background, hero through mid-sections: `Multi-stop radial/linear gradient with background-attachment`
- **[9] star-sparkle** at Scattered at section transitions and card corners: `SVG or pseudo-element with rotation animation`
- **[9] cross-markers** at Grid intersection points, section dividers: `Pseudo-elements or inline SVG`
- **[9] glow-haze** at Behind CTA section, purple-blue atmospheric glow: `Radial gradient or blurred pseudo-element with mix-blend-mode:screen`
- **[9] noise-texture** at Subtle over gradient backgrounds: `background-image with SVG noise filter, opacity ~0.03`
- **[9] neon-light-poles** at Hero automotive scene flanking car: `3D render element — bloom/glow post-processing`
- **[9] wireframe-ghost** at Overlaid on solid car model: `3D render with wireframe material pass composited`
- **[9] mesh-gradient-bg** at Crypto page background: `Radial gradients or mesh-gradient from lavender to pink`
- **[9] atmospheric-haze** at Hero scene depth: `Volumetric fog in 3D render`
- **[9] soft-shadows** at E-commerce isometric scene: `3D render with area lights creating natural shadow falloff`
- **[9] circular-rotating-text-badge** at Course section bottom-right: `CSS animation rotate + SVG text-on-path`
- **[9] scattered-photo-collage** at Vision section: `Absolute positioning with varied sizes, possibly scroll-triggered parallax`
- **[9] handwritten-signature** at Below vision quote: `SVG or image overlay`
- **[9] Mixed-shape photo masks** at Hero grid, case studies, throughout: `clip-path or border-radius with overflow:hidden — oval, rounded-rect, circle variants`
- **[9] Sticker/stamp text blocks** at About section, bento grid: `transform:rotate, background-color blocks, slight skew, possibly SVG`

## Shadow Patterns
Most top projects use minimal shadows:

- **[9]** None visible — flat editorial approach
- **[9]** Large diffused drop shadows on card containers — ~0 20px 60px rgba(0,0,0,0.12) — soft and expansive
- **[9]** Subtle drop-shadow on outer page container — ~0 8px 32px rgba(0,0,0,0.08)
- **[9]** None visible — completely flat, relies on layering and overlap
- **[9]** None in specimen; subtle ambient in applied mockups
- **[9]** Minimal — subtle on testimonial card, mostly flat with depth from layering
- **[9]** Subtle drop shadows on isometric buildings — ~2px offset, low opacity
- **[9]** Integrated into illustration — no drop shadows, uses value shifts within the limited palette
- **[9]** Realistic PBR shadows from 3D scene — soft ambient occlusion, hard directional from neon sources
- **[9]** Minimal — near zero visible shadows, depth from layering and contrast
- **[9]** Subtle — device mockups have natural shadow from 3D rendering; cards use minimal box-shadow
- **[9]** Minimal — mostly glow-based rather than drop shadows, low intensity
- **[9]** None visible — flat layering through color contrast only
- **[9]** Minimal — ambient glow rather than drop shadows, soft light bloom on images
- **[9]** Realistic 3D-rendered shadows — soft area-light shadows in e-commerce scene, dramatic rim lighting in automotive
- **[9]** Minimal — subtle card shadow on course detail overlay, ~0 4px 20px rgba(0,0,0,0.08)
- **[9]** Minimal to none — flat design with depth from layering and color contrast
- **[9]** Soft diffused — large spread box-shadows on cards to simulate floating in 3D space, ~0 20px 60px rgba(0,0,0,0.5)
- **[8]** Minimal, natural — device mockup shadows only, soft and realistic
- **[8]** Soft diffused, low intensity, ~0 8px 40px rgba(0,0,0,0.06)
- **[8]** Heavy realistic drop-shadows on bowls and props — multi-layer box-shadow or baked into PNGs
- **[8]** Minimal — relies on photographic darkness rather than box-shadows
- **[8]** Minimal — coin has baked ambient occlusion, no CSS box-shadows visible
- **[8]** None visible — completely flat design
- **[8]** Subtle box-shadow on gallery image frames — soft, ~0 4px 20px rgba(0,0,0,0.08)
- **[8]** Minimal — card has subtle box-shadow ~0 4px 24px rgba(0,0,0,0.3)
- **[8]** None visible — flat design with color contrast for depth
- **[8]** None visible — completely flat, relies on color and spacing for hierarchy
- **[8]** Minimal — card may have subtle box-shadow, overall flat dark aesthetic
- **[8]** Subtle ambient on product renders only, no box-shadows on UI

## Imagery Approach

- **[9] Maria Eli: Fused Identities — Artist Portfolio**: Double-exposure / motion-blur fine art photography — warm sepia-toned, desaturated, high-fashion editorial quality
- **[9] Diligence Infrastructure for Private Capital**: Architectural photography — brutalist concrete structures, aerial/dramatic angles, desaturated cool tones, high quality editorial stock or commissioned
- **[9] AMARI: Luxury Riverside Residences**: 3D architectural renders (high-quality CGI) + art-directed calla lily macro photography — both premium quality
- **[9] Editorial Skincare Web Explorations with Golden Canyon Grid**: High-end editorial photography — close-up face with cream mask, tightly cropped, film-like color grading with desaturated tones. Product photography with amber glass bottles, studio-lit
- **[9] Interval. Cafe Brand Identity. Typography Layouts & Visuals.**: Full-bleed photography — concert crowd (Chumakov), interior render (Hapr); high quality, moody lighting, dark overlay treatment
- **[9] PAWS & CO. — Luxury Pet Hotel Website**: High-quality studio pet photography — Dalmatian with luxury collar, cutout/masked with transparent background, professional retouching
- **[9] Illustrated Animated Map of Kyiv, Ukraine. Landing Page.**: 100% custom illustration — no photography on the map itself
- **[9] The new illustrations for the Skretting company (Calendar 2026)**: Custom editorial illustration — full-scene narrative compositions, production quality
- **[9] The XIX — Cinematic 3D Website & Promo Animation**: Real-time 3D render — cinematic quality, PBR materials, volumetric lighting, automotive-grade
- **[9] Mertana - Ski Brand**: High-quality action photography — dramatic lighting, snow particles, dark backgrounds. Hero image is studio-quality with controlled lighting. Category images are desaturated/low-contrast grayscale treatment
- **[9] Fourmeta website: Future-ready digital experience**: High-end photography + 3D device mockups — cinematic lighting, dark moody tones, professional case study screenshots embedded in realistic laptop/phone frames
- **[9] Product for a Productivity Product ✦ Daylier**: Art-directed photography embedded in metric cards — warm amber color grading, cinematic quality, likely stock with heavy post-processing
- **[9] Stormie - Art Director Website Portfolio**: High-end fashion photography — warm cinematic color grading, amber/red tones, editorial quality, likely curated from real shoots
- **[9] Origin creative landing page**: Warm portrait photography — diverse subjects, natural lighting, slightly warm-graded, high quality editorial feel
- **[9] XIX3D Website — Cinematic 3D Animation**: Custom 3D renders — photorealistic automotive with wireframe overlay, isometric e-commerce scene, stylized crypto coins, mobile app UI mockups — all high-fidelity production quality
- **[9] Golf Club Landing Page Design**: High-end editorial photography — lifestyle golf shots with fashion-forward styling, aerial drone course photography, warm natural color grading, magazine-quality
- **[9] Case Study: Landing Page for Creator Growth Platform**: Lifestyle photography of diverse young creators — warm tones, outdoor/natural light, high quality editorial stock or custom shoots, vibrant color grading
- **[9] Fourmeta services, but make them feel alive**: High-quality portfolio mockups composited onto each card — laptop screens, product renders, brand collateral grids — professional photography-grade
- **[8] Baumkontrolle im Netz - Web Design**: Professional portrait photography in natural forest setting — moody, editorial quality, shallow depth of field, warm-cool contrast
- **[8] Epitope — Biotech Visual Identity**: 3D rendered organic protein-like shapes, soft lighting, high quality, bespoke
- **[8] Kaisen Ramen — Motion-Driven Landing Page 🍜**: High-quality food photography — top-down angle, rich saturation, professional lighting with warm tones, likely studio shot with post-processing
- **[8] Fine Dine Club Website | Selected Screens**: Professional Michelin-star food photography — overhead plating shots, smoke/steam effects, moody chiaroscuro lighting, extremely high production value
- **[8] Modern Minimalist Blockchain UI**: 3D rendered coin with chromatic aberration and prismatic light leak — high quality, custom asset
- **[8] MVRDP — Architectural Visualization Concept**: High-end 3D architectural renders — photorealistic, luxury real estate, warm golden-hour lighting, excellent quality
- **[8] ARCILLA: Luxury Residential Masterpiece**: High-end 3D architectural renders — photorealistic CGI with soft golden-hour lighting, lush tropical planting, Porsche 911 as lifestyle signifier. Production quality.
- **[8] Clearing. – Visual Identity**: Fine-art editorial photography — motion-blurred figure in red coat on sand dunes, dark teal sky, heavy film grain, cinematic color grading
- **[8] Herbal therapist website**: Vintage botanical scientific illustrations — high-quality scans/reproductions of 18th-19th century herbarium plates, excellent quality
- **[8] Luméa Design Studio**: High-quality interior photography — warm-toned, natural light, curated to match palette. Mix of real photography and likely AI-generated renders (catalogue kitchens look AI-rendered)
- **[8] Architecture Studio Website — Modern Web Design Concept**: High-quality 3D architectural render — nighttime exterior visualization, professional archviz quality
- **[8] Formula - the tech behind peace of mind**: 3D product renders, dark studio lighting, consistent 3/4 angle, high quality
