# Devtool — Design Playbook

**3 projects analyzed | 3 scored 7+ | Avg: 7.3/10**

## Category Overview

**Aesthetics that work:** dark-luxury (3)
**Color strategy:** dark-theme (2), neutral-plus-accent (1)
**Color mode:** dark (2), mixed (1)
**Hero patterns:** left-right (1), centered (1), split-50-50 (1)
**Frameworks:** Framer (1), Next.js (1), React or Svelte (1)
**Animation:** Framer-Motion (1), CSS-only (1), Canvas API or p5.js for generative output, CSS-only for UI transitions (1)
**Heading fonts:** Custom serif/display (1), Inter (1), Inter or SF Pro (1)
**Body fonts:** Inter or similar geometric sans-serif (1), Inter (1), Same as heading (1)

## Color Rules

- **[8]** Purple reserved exclusively for primary CTA and chat widget — extremely restrained
- **[7]** Purple used for interactive/highlighted elements only; pink reserved for primary CTA
- **[7]** Purple-orange gradient reserved exclusively for interactive/active elements — sliders, toggles, selected states

### Color Craft Insights
- **[8]** The FAQ list fades out at bottom with opacity mask — clever way to hint at more content without cluttering
- **[7]** The ambient purple-pink glow in the hero bottom-left creates a light source that motivates the 3D blob's purple reflections — unified lighting logic
- **[7]** The orange-to-purple gradient direction on sliders visually maps to value progression — warm=high, cool=low — creating intuitive color-coding

## Color Palettes

### Figma UI kit and design system Example (neutral-plus-accent / mixed)
- `#FFFFFF` — **bg-primary** — Maximum readability for documentation content
- `#060606` — **bg-primary-dark** — True black for OLED-friendly dark theme with premium feel
- `#7F56D9` — **accent-cta** — Purple signals creativity and premium — fits design tool brand
- `#EDEDED` — **surface-divider** — Subtle separation without visual noise
- `#344054` — **text-secondary** — Softer than pure black for comfortable reading
- `#1D2939` — **text-primary-dark** — Elevated surface layer for testimonial section
- `#F9A825` — **decorative** — Gold for trust signals and attention-grabbing alerts

### Web3 smart contract IDE with modular living code system Example (dark-theme / dark)
- `#060306` — **bg-primary** — Near-black creates depth canvas for glowing elements
- `#FDFDFD` — **text-primary** — Maximum contrast on dark for readability
- `#B150D1` — **accent-cta** — Purple signals innovation, creativity, Web3 culture
- `#380DC5` — **decorative** — Deep blue-purple adds dimensional depth to glows
- `#921B46` — **accent-secondary** — Warm pink-red creates urgency and energy contrast
- `#2D134C` — **surface-card** — Dark purple bridges black bg to bright accents
- `#AEA3B3` — **text-secondary** — Warm gray maintains purple tint for cohesion
- `#533A59` — **decorative** — Low-contrast purple for background texture

### Generative visual art tool / image-to-halftone converter Example (dark-theme / dark)
- `#040405` — **bg-primary** — Maximum contrast for creative tool — content is the star
- `#1A1A1E` — **surface-card** — Subtle elevation from base without competing with controls
- `#5824E3` — **accent-cta** — Purple signals creativity and premium tooling
- `#993EA2` — **accent-secondary** — Bridges purple-to-orange creating warm energy
- `#D45A4A` — **accent-warm** — Warm complement to purple creates visual tension and energy
- `#C0C0C2` — **text-primary** — Soft white reduces eye strain in dark UI
- `#59595D` — **text-muted** — Low-contrast for structural elements that shouldn't compete

## Typography

- **[8] Inter — geometric sans-serif + Inter — geometric sans-serif**: Single font family with weight variation creates systematic consistency befitting a design system product.
- **[7] Custom serif/display — likely Playfair D + Inter or similar geometric san**: High-contrast serif headlines create editorial gravitas while sans body ensures technical readability — classic authority pairing
- **[7] Inter or SF Pro — geometric sans-serif + Same as heading — single-famil**: Single font family at different weights maintains tool-like consistency and reduces cognitive load in a dense UI.

### Typography Effects
- **[7]** Italic emphasis on 'stay still.' — font-style:italic for semantic stress
- **[7]** Purple underline/highlight on 'Source' and 'this is The Flow' — likely box-decoration-break with background gradient
- **[7]** Giant watermark 'flusor' text at bottom-right — low opacity, possibly mix-blend-mode:overlay

## Hero Patterns

- **[8] centered** (Figma UI kit and design system): announcement badge → h1 → subtitle → tabs → first FAQ
- **[7] left-right** (Web3 smart contract IDE with modular living code s): 3D blob → headline → breadcrumb → subhead → watermark 'flusor'
- **[7] split-50-50** (Generative visual art tool / image-to-halftone con): Logo→Source panel→Canvas preview→Adjustment sliders→Action bar

## Card & Component Patterns

- **[8]** Testimonial card — dark bg #1D2939, rounded-16, split layout with text left + image right, no visible shadow, internal padding ~48px
- **[7]** Dark surface panels, border-radius ~12px, padding ~16px, no hover effect, stacked vertically with ~12px gap

### Buttons

- **primary / rounded-8**: `background-color with border-radius: 8px`
- **secondary / rounded-8**: `border with transparent background`
- **ghost / rounded-8**: `Show more button with icon, border: 1px solid`
- **primary / pill**: `background: linear-gradient(90deg, #921B46, #B150D1); border-radius: 24px`
- **secondary / pill**: `border: 1px solid rgba(177,80,209,0.4); backdrop-filter: blur(8px)`
- **secondary / rounded-8**: `border: 1px solid rgba(255,255,255,0.1)`
- **ghost / rounded-8**: `background: transparent`
- **action-bar / rounded-8**: `icon + text inline-flex`

## Animation & Interaction

- **[8]** accordion-expand-collapse → CSS transition on max-height, icon rotation
- **[8]** tab-switch → active state border/bg swap, likely client-side filter
- **[8]** show-more-button → reveals hidden FAQ items, smooth scroll or height animation
- **[8]** testimonial-carousel → left/right arrows cycle cards, likely Framer Motion or CSS
- **[8]** chat-widget-open → FAB expands to chat panel, third-party (Intercom-style)
- **[7]** Scroll-triggered section reveals → Framer-Motion viewport animation
- **[7]** 3D blob likely subtle rotation/float → CSS animation or Spline embed
- **[7]** CTA button glow pulse → CSS animation on box-shadow
- **[7]** IDE mockup parallax-float on scroll → Framer scroll transforms
- **[7]** Breadcrumb arrows sequential fade-in → staggered Framer-Motion
- **[7]** Slider drag → real-time canvas update — requestAnimationFrame + Canvas API
- **[7]** Toggle switch animation — CSS transition on transform
- **[7]** Direction picker segment selection — active state gradient pill transition
- **[7]** Upload image → canvas processing pipeline — FileReader + Canvas drawImage
- **[7]** Camera start → getUserMedia stream to canvas — WebRTC API

## Decorative Elements

- **opacity-fade-mask** at bottom of FAQ list: `mask-image: linear-gradient or opacity gradient overlay`
- **announcement-dot** at before banner text: `pseudo-element or inline SVG circle, fill: gold`
- **chat-fab** at bottom-right fixed: `position: fixed, border-radius: 50%, box-shadow`
- **ambient-glow** at hero bottom-left: `radial-gradient with large blur radius`
- **3d-blob** at hero right: `positioned img/canvas, possibly Three.js or static render`
- **watermark-text** at hero bottom-right: `large font-size, opacity: 0.05-0.1, mix-blend-mode`
- **purple-border-glow** at IDE mockup frame: `box-shadow with purple spread + border-image gradient`
- **arc-line** at above feature icons: `SVG path or border-radius on pseudo-element`
- **noise-texture** at subtle across dark bg: `background-image SVG noise filter`
- **halftone-dots** at Canvas preview area: `Canvas API / WebGL generative rendering`
- **gradient-fills** at Slider tracks and active pills: `linear-gradient on pseudo-elements or range track`
- **subtle-borders** at Panel card edges: `border: 1px solid rgba(255,255,255,0.06)`

## Design Recipes

### Score 8/10 — dark-luxury — Figma UI kit and design system

**Design Recipe:** Use Inter at weights 400/500/600 on a pure white (#FFFFFF) or true black (#060606) background. Single accent: #7F56D9 purple, used ONLY on primary CTA. FAQ section: centered h1 at 48px/600, 16px/400 body, accordion items separated by 1px #EDEDED borders with 24px vertical padding each. Tabs: 14px/500 with active state getting a subtle border or bg-fill. Max-width 768px for content column within 1140px container. Testimonial: full-width dark panel #1D2939 with 50/50 grid split. Footer: 5-column link grid at 14px.

**Dev Recipe:** Next.js + Tailwind CSS with dark: variant for theme switching. Custom accordion component using details/summary or controlled state with max-height CSS transitions. Tab filtering with client-side state. Inter from Google Fonts, CSS custom properties for theme tokens.

**Core Lesson:** Restraint IS the design — a single accent color, one font family, and generous whitespace create more authority than decorative complexity ever could.

**Steal These:**
- FAQ list fade-out mask at bottom hinting more content exists
- Announcement badge with gold dot above page title as social proof
- Tab filter above accordion to segment FAQ categories without page reload
- Show more button at bottom instead of pagination for progressive disclosure
- Testimonial section as dark contrast break between light FAQ and dark footer

**Weaknesses:** FAQ content column could be narrower (~640px) for optimal reading line length, No search functionality for FAQs — problematic as list grows, Logo bar lacks visual hierarchy — all logos same size regardless of recognition

---

### Score 7/10 — dark-luxury — Web3 smart contract IDE with modular living code system

**Design Recipe:** Start with #060306 near-black background. Build a purple gradient system from #2D134C → #B150D1 → #921B46. Use a high-contrast serif (Playfair Display or similar) at 64-72px bold for headlines, Inter 16px for body at #AEA3B3. Create a glassmorphic navbar with backdrop-filter:blur(12px) and rgba(6,3,6,0.7) background. Place a radial-gradient glow (purple-pink, 600px radius, 0.3 opacity) in the hero bottom-left. CTA button uses linear-gradient(90deg, #921B46, #B150D1) with pill shape. Add a 3D rendered dark reflective blob with purple subsurface lighting as the hero focal point. Section spacing at 140px. IDE mockup framed with 2px purple border and 30px purple box-shadow glow.

**Dev Recipe:** Framer for rapid prototyping, or Next.js + Framer Motion for production. Use Tailwind dark theme with custom purple palette. Spline or pre-rendered Blender asset for 3D blob. Key CSS: radial-gradient ambient glows, backdrop-filter navbar, box-shadow glow borders, mix-blend-mode watermark text.

**Core Lesson:** A single memorable 3D brand object in the hero can carry an entire page's identity when the color system and lighting logic are unified around it

**Steal These:**
- Breadcrumb concept flow (Tools → Networks → Economies) as a narrative device above the headline
- Giant low-opacity brand watermark text as background texture element
- Purple glowing border on product screenshots to make them pop on dark bg
- Pink-to-purple gradient CTA button as the only warm element — instant focal point
- Unified lighting logic — ambient glow position matches 3D object's light source

**Weaknesses:** Messaging is abstract and buzzwordy — 'code learns to move' needs concrete proof points, The feature icon section at the bottom feels generic compared to the crafted hero, No visible social proof, testimonials, or trust signals — hurts conversion credibility

---

### Score 7/10 — dark-luxury — Generative visual art tool / image-to-halftone converter

**Design Recipe:** Dark bg #040405, card surfaces #1A1A1E with 1px rgba(255,255,255,0.06) borders and 12px radius. All text in #C0C0C2 Inter/system font at 13-14px. Single accent gradient linear-gradient(90deg, #D45A4A, #993EA2, #5824E3) applied ONLY to slider fills, active toggle states, and selected segment pills. Sidebar fixed 320px, 16px internal padding, 12px section gaps. Action bar pinned bottom with icon+label pairs at 12px.

**Dev Recipe:** React + Canvas API (or p5.js) with Zustand for slider state. Tailwind dark theme with CSS custom properties for the gradient accent. Custom range input styling via appearance:none and webkit pseudo-elements. Real-time canvas redraw on state change via useEffect.

**Core Lesson:** In tool UIs, reserve color exclusively for interactive elements — everything else stays monochrome dark, making controls instantly scannable.

**Steal These:**
- Orange-to-purple gradient exclusively on interactive elements — instant visual hierarchy
- Segmented direction picker with gradient active pill
- Consistent panel card system with icon+title headers
- Version badge next to product name for tool credibility
- Bottom action bar with icon+text pairs for primary actions

**Weaknesses:** Typo: 'Thershold' instead of 'Threshold' — undermines polish, Two near-identical sidebar screenshots shown side-by-side add little to the case study presentation, No visible responsive/mobile consideration — tool is desktop-locked

---
