# Marketplace — Design Playbook

**4 projects analyzed | 3 scored 7+ | Avg: 6.8/10**

## Category Overview

**Aesthetics that work:** bold-expressive (1), dark-luxury (1), glassmorphism (1), minimal-corporate (1)
**Color strategy:** neutral-plus-accent (2), dark-theme (1), analogous (1)
**Color mode:** light (2), mixed (1), dark (1)
**Hero patterns:** full-bleed (1), left-right (1), layered (1), split-50-50 (1)
**Frameworks:** Next.js (2), This is a brand guidelines document, likely Figma/Adobe export (1), React Native or Flutter (1)
**Animation:** Framer-Motion (2), none (1), React Native Reanimated or Flutter built-in (1)
**Heading fonts:** Custom script/brush (1), Inter or Poppins (1), SF Pro Display or Poppins (1), Inter or SF Pro (1)
**Body fonts:** Sans-serif geometric (1), Inter (1), SF Pro Text or Inter (1), Inter or SF Pro (1)

## Color Rules

- **[7]** Coral pink is dominant accent (~60% of color usage), others used in equal supporting rotation
- **[7]** Purple accent reserved for interactive elements and single hero keyword — very disciplined
- **[7]** Deep blue used sparingly — only on search title, AI labels, and send CTA

### Color Craft Insights
- **[7]** The 5-color palette is unusually wide but works because each color occupies a distinct hue quadrant (red, blue, yellow, green, black) — essentially a CMYK-inspired pop palette that guarantees any 2-color combo has sufficient contrast
- **[7]** The purple light beam is not just decorative — it creates a natural diagonal leading line from hero text down to the marketplace mockup, guiding the eye through the composition
- **[7]** The muted green-tinted background gradient behind results creates a subtle zone separation from the white chat panel without hard borders — sophisticated spatial hierarchy

## Color Palettes

### Human-only art marketplace opposing AI-generated art Example (neutral-plus-accent / mixed)
- `#050505` — **bg-primary** — Grounds the rebellious palette with authority and contrast
- `#FF4660` — **accent-cta** — Energetic and passionate — signals activism without aggression, youthful rebellion
- `#7373FF` — **decorative** — Creative/artistic connotation, complements coral pink as near-complementary
- `#FFF955` — **decorative** — Adds pop-art energy, high visibility for badges/stamps
- `#AEFF52` — **decorative** — Neon-organic feel, signals freshness and counter-culture edge
- `#F4F4F4` — **bg-primary** — Near-white keeps focus on bold color accents without harsh pure white

### Custom tailoring fashion marketplace Example (dark-theme / dark)
- `#020104` — **bg-primary** — Near-black creates luxury canvas and maximizes contrast for glowing elements
- `#170858` — **bg-secondary** — Adds warmth to black, prevents flat dead-black feel
- `#3819CB` — **accent-cta** — Electric purple signals premium tech-forward brand
- `#7C3AED` — **accent-highlight** — Vibrant purple as primary accent — luxury, creativity, exclusivity
- `#F8F5FB` — **text-primary** — Warm white with slight lavender tint maintains palette cohesion
- `#ABA3B9` — **text-secondary** — Muted lavender-gray for hierarchy without harsh contrast
- `#532716` — **decorative** — Earthy contrast to cool purple palette
- `#98637D` — **decorative** — Bridge between purple brand and warm fashion photography

### AI-assisted B2B product sourcing marketplace Example (neutral-plus-accent / light)
- `#FFFFFF` — **bg-primary** — Clean canvas maximizes product image visibility
- `#030304` — **text-primary** — Maximum readability and authority
- `#061196` — **accent-cta** — Deep blue conveys trust and intelligence — perfect for AI/B2B
- `#666667` — **text-secondary** — Sufficient contrast without competing with headings
- `#DBDBDB` — **border-divider** — Subtle separation without visual noise
- `#F0F7F4` — **bg-secondary** — Adds warmth and differentiates content zones
- `#F5A623` — **decorative** — Universal e-commerce convention for ratings

## Typography

- **[7] Custom script/brush — likely based on Pa + Sans-serif geometric — likely **: Handwritten script conveys human touch and artistry; clean geometric sans provides legibility and modern professionalism for body text
- **[7] Inter or Poppins — geometric sans-serif + Inter — humanist sans-serif**: Single font family at different weights creates clean luxury without competing typefaces.
- **[7] Inter or SF Pro — geometric sans-serif + Inter or SF Pro — same family**: Single-family system keeps the dense UI clean and scannable across chat + commerce contexts.

### Typography Effects
- **[7]** Wide letter-spacing on tagline 'ART BY HUMANS' — CSS letter-spacing: 0.3em
- **[7]** Purple color accent on 'Meets' keyword — color: #7C3AED, draws eye to brand promise
- **[7]** Bold inline emphasis on '71000+' and '4900+' numbers — font-weight:700 within regular text

## Hero Patterns

- **[7] full-bleed** (Human-only art marketplace opposing AI-generated a): Icon → script wordmark → tagline 'ART BY HUMANS'
- **[7] left-right** (Custom tailoring fashion marketplace): Logo→headline 'Meets'→subhead→CTA→marketplace mockup below
- **[7] split-50-50** (AI-assisted B2B product sourcing marketplace): Search title → result count → AI Suggestions label → filter chips → first product card row

## Card & Component Patterns

- **[7]** Color swatch cards — flat, no radius, full-bleed grid, label overlay bottom-left
- **[7]** Product cards with rounded-8, image top, badge overlays (% off, vendor), ~12px padding, subtle dark surface
- **[7]** White bg, 1px light border, 8-12px radius, ~16px padding, product image top 60%, title+price bottom, heart icon top-right of rating row, no visible hover effect

### Buttons

- **primary / pill**: `border: 1px solid #7C3AED; border-radius: 24px`
- **primary / pill**: `background: #3819CB; border-radius: 18px`
- **ghost / pill**: `border: 1px solid rgba(255,255,255,0.2)`
- **primary / pill**: `border-radius:50%, background:#061196`
- **secondary / rounded-8**: `border:1px solid #DBDBDB`
- **ghost / rounded-8**: `border:1px solid #333`

## Animation & Interaction

- **[7]** n/a — static brand guidelines presentation
- **[7]** dropdown-menu-toggle → click avatar reveals menu → Framer-Motion or CSS transition
- **[7]** carousel-slide → auto-play image carousel with dots → Embla or Swiper
- **[7]** category-pill-active → tab switching with underline/fill → state management
- **[7]** cta-arrow-hover → arrow slides right on hover → CSS transform
- **[7]** hero-parallax → light beam subtle parallax on scroll → Framer-Motion useScroll
- **[7]** Chat message streaming — typewriter effect via Framer-Motion or custom interval
- **[7]** AI suggestion action buttons — hover highlight, click triggers new chat message + grid refresh
- **[7]** Filter chip toggle — click adds/removes active state, re-queries products
- **[7]** Heart/wishlist toggle — click fills icon, optimistic UI update
- **[7]** Product card hover — subtle lift or border-color change

## Decorative Elements

- **duotone-overlay** at Hero image: `mix-blend-mode or CSS filter with background-color overlay`
- **brand-personality-sliders** at Brand personality section: `Custom range indicators with SVG/CSS circles on lines`
- **concentric-circles** at Top-left hero background: `SVG or border-radius rings with opacity gradient`
- **purple-light-beam** at Diagonal from top-right through center: `Radial/conic gradient or pseudo-element with blur filter`
- **glow-effect** at Around light beam edges: `box-shadow or filter: blur() on pseudo-element`
- **browser-mockup** at Lower half, nested marketplace preview: `Rounded container with dark chrome, perspective transform slight`
- **gradient-wash** at Behind search results area: `linear-gradient with low-opacity mint/cream tones`
- **sparkle-icon** at AI Suggestions label: `SVG icon inline`
- **colored-top-border** at Second product card has orange/coral top accent border: `border-top:3px solid #coral`

## Design Recipes

### Score 7/10 — bold-expressive — Human-only art marketplace opposing AI-generated art

**Design Recipe:** Use a bold script font (Pacifico/Lobster-weight) for the wordmark in #050505 or white. Primary accent #FF4660 coral pink applied as duotone overlay on photography via mix-blend-mode:multiply. Supporting palette of #7373FF, #FFF955, #AEFF52 used in flat color blocks. Body text in Montserrat/Poppins 15px regular on #F4F4F4 background. Tagline always uppercase with letter-spacing:0.3em. Logo system needs 4 variants: full lockup, horizontal, wordmark-only, icon-only. Section spacing 80-120px. All color usage flat — zero gradients, zero shadows.

**Dev Recipe:** Static site with Astro or Next.js static export. Vanilla CSS or Tailwind with custom color tokens for the 5-brand-color system. Hero duotone via a ::after pseudo-element with background-color:#FF4660 and mix-blend-mode:multiply over a grayscale background-image.

**Core Lesson:** A brand fighting for human creativity must LOOK handmade — the script logotype and hand-drawn icon aren't decorative choices, they're the message itself.

**Steal These:**
- Peace-sign-hand-holding-pencil icon — dual meaning in one symbol
- 5-color pop palette where any 2 colors work together
- Anti-AI badge/stamp system as trust signals for human-made products
- Duotone coral pink hero treatment — instant brand recognition
- 4-tier logo lockup system (full, horizontal, wordmark, icon)

**Weaknesses:** Justified body text creates uneven word spacing — left-align would read better, Brand personality section is generic template filler — sliders add little value, No actual UI/web design shown — this is identity-only, missing the marketplace experience

---

### Score 7/10 — dark-luxury — Custom tailoring fashion marketplace

**Design Recipe:** Start with #020104 background. Use #F8F5FB for text, #7C3AED as sole accent on CTAs and one hero keyword. Set hero headline at 72px bold geometric sans (Inter/Poppins), tight letter-spacing. Place concentric circle SVG decoration top-left at 30% opacity. Add a diagonal purple light beam using a 400px wide conic-gradient element with 80px blur, positioned from top-right to center. Outline pill CTA button with 1px #7C3AED border. Below fold, nest a dark browser mockup (bg #0D0D14, rounded-2xl, 1px border rgba(255,255,255,0.08)) showing the actual product UI.

**Dev Recipe:** Next.js + Tailwind + shadcn/ui for dropdown, pills, search. Purple beam via absolute-positioned div with conic-gradient(from 45deg, transparent, #7C3AED, transparent) and filter:blur(80px). Embla carousel for product slider. Framer Motion for hero text stagger and dropdown animation.

**Core Lesson:** A single dramatic decorative element (the purple light beam) can carry an entire dark layout if the rest stays disciplined and minimal.

**Steal These:**
- Nested browser mockup as hero visual — shows the product without a separate screenshot section
- Single accent-colored word in headline to highlight brand promise
- Diagonal light beam as compositional leading line guiding eye flow
- Concentric circle decoration adding depth without competing with content
- Outline pill CTA on dark backgrounds — elegant and clickable without being heavy

**Weaknesses:** Only hero section visible — no social proof, features, or pricing to validate the marketplace concept, Marketplace mockup text is too small to read at this scale — loses impact, Typography lacks variety — no display/serif contrast to reinforce luxury positioning

---

### Score 7/10 — minimal-corporate — AI-assisted B2B product sourcing marketplace

**Design Recipe:** Use Inter 14px body / 28px bold headings on #FFFFFF base. Left sidebar fixed at 320px with #FFFFFF bg and subtle box-shadow(0 2px 12px rgba(0,0,0,0.08)). Main content area gets a soft linear-gradient(135deg, #F0F7F4, #FFF9F0) background wash. Deep blue #061196 for primary accent — search titles, AI labels, send button only. Product grid: 3 equal columns with 16px gap, cards with border:1px solid #E8E8E8, border-radius:12px, white bg. Filter chips: border:1px solid #DBDBDB, border-radius:20px, padding:8px 16px, 13px text. Star ratings in #F5A623.

**Dev Recipe:** Next.js App Router + Tailwind CSS + shadcn/ui for chips/buttons/cards. Chat panel via Vercel AI SDK with streaming. Product grid with React Query for search state management. Layout: CSS Grid with grid-template-columns: 320px 1fr.

**Core Lesson:** Persistent AI chat as a sidebar co-pilot alongside traditional browse/search creates a powerful hybrid UX that serves both conversational and visual shoppers.

**Steal These:**
- AI chat sidebar as persistent co-pilot alongside traditional product grid
- Contextual AI-generated filter chips that adapt to the search query
- Quick-action suggestion buttons in chat (Find suppliers, Market trends, Compare) as conversation starters
- Subtle gradient background wash to differentiate content zones without hard borders
- Inline bold stats in subtitle (71000+ products, 4900+ suppliers) for instant credibility

**Weaknesses:** Product cards are generic — no supplier info, MOQ, shipping origin that B2B buyers need, Background gradient feels unresolved — the mint-to-cream wash could be more intentional or removed, No visible loading/skeleton states for the AI-triggered product refresh — critical for perceived performance

---

### Score 6/10 — glassmorphism — On-demand home services booking app

**Design Recipe:** Use #95B3B0 sage as app background, #C7A34F amber for all CTAs and discount badges, #2F5850 deep teal for card overlays at 60% opacity with 20px blur. Set heading font to Poppins SemiBold at 28/20/16px scale. Cards get border-radius:16px with 1px rgba(255,255,255,0.3) top border. Bottom tab bar uses same glass treatment. Keep section spacing at 16-20px. Limit amber accent to max 3 touchpoints per screen.

**Dev Recipe:** React Native with expo-blur for BlurView, expo-linear-gradient for header gradients, react-native-reanimated for carousel and transitions. Use a theme provider with the sage-amber-teal palette tokens and a reusable GlassCard component wrapping BlurView + LinearGradient.

**Core Lesson:** Glassmorphism works best when the underlying imagery is controlled — blurred backgrounds need consistent luminosity or the text contrast breaks.

**Steal These:**
- Amber gradient fading from header into sage background — warm welcome feeling
- Discount badge as small pill floating top-left of promo cards
- Location pill integrated into search bar as prefix element
- Service detail screen with full-bleed hero photo and glass overlay bottom sheet
- Premium/Classic toggle tabs with discount callout badge overlapping

**Weaknesses:** White text on glass over varied photos creates inconsistent contrast — needs gradient scrim or darkened blur, Category icons are generic and interchangeable with any service app — no brand identity, The design is indistinguishable from dozens of Dribbble home-service concepts — needs a unique interaction or visual hook

---

## Slop Patterns to Avoid

### Score 6/10
- Glassmorphism applied uniformly without hierarchy purpose — decorative not functional
- Stock photography of cleaning workers feels generic and AI-curated
- Color palette is pleasant but the green-gold combo is trending Dribbble template territory
- Category icons are generic line icons with no brand personality
- The 3-screen flow is coherent but follows every Dribbble home-services template pattern exactly
