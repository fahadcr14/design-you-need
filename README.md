<div align="center">

# design-you-need
<img width="1280" height="640" alt="social-preview" src="https://github.com/user-attachments/assets/c9f4f9a8-1076-48a1-923a-8f5b7f5d164e" />

### Stop shipping AI slop. Start shipping designs that look like a human made them.

A skill for AI coding tools that replaces every generic, template-looking frontend with production-quality design — derived from forensic analysis of award-winning Dribbble projects.

Works with **Claude Code** | **Cursor** | **Windsurf** | **Cline** | **Roo Code** | **Copilot** | **any AI coding tool**

---

**The problem**



https://github.com/user-attachments/assets/859677cb-4f56-466a-824a-aeddf5de1219

<sub>AI builds frontends that all look the same — gradient buttons, decorative blobs, lorem ipsum energy, template section ordering. We call this <b>slop</b>.</sub>

---

**The fix**


https://github.com/user-attachments/assets/fee170b9-f2d7-4d03-af75-dd5c293b0744

<sub>Same prompt. Same AI. But now it knows what high-scoring designers actually do — and what slop projects get wrong.</sub>

</div>

---

## What is this?

AI coding tools are incredible at writing code — but terrible at design. Every frontend they generate looks the same: the same hero layout, the same gradient buttons, the same card grids, the same soul-less "modern" aesthetic.

**design-you-need** fixes this. It's a skill that injects real design intelligence — extracted from studying actual designer-crafted, award-winning projects — directly into your AI coding workflow.

It knows:
- Which **aesthetic signature** fits your project category
- Which **hero layout pattern** creates the right visual impact
- The **slop red flags** that make frontends look AI-generated
- The **craft principles** that separate great design from generic output
- **Typography pairings**, **color theory**, **animation patterns**, **component CSS** — all backed by data, not vibes

---

## Install

### Claude Code

```bash
claude install-skill https://github.com/fahadcr14/design-you-need
```

### Cursor

Add to your project's `.cursor/rules/` directory:

```bash
# Clone and copy into your project
git clone https://github.com/fahadcr14/design-you-need.git
cp -r design-you-need/design-you-need/ .cursor/rules/design-you-need/
```

Or add the SKILL.md content as a **User Rule** in Cursor Settings → Rules.

### Windsurf

Add to your project's `.windsurfrules` or rules directory:

```bash
git clone https://github.com/fahadcr14/design-you-need.git
cp -r design-you-need/design-you-need/ .windsurf/rules/design-you-need/
```

### Cline / Roo Code

Add as a **custom instruction** or drop into your project's rules directory:

```bash
git clone https://github.com/fahadcr14/design-you-need.git
# Cline
cp -r design-you-need/design-you-need/ .cline/rules/design-you-need/
# Roo Code
cp -r design-you-need/design-you-need/ .roo/rules/design-you-need/
```

### GitHub Copilot

Add as a **custom instruction file** in your project:

```bash
git clone https://github.com/fahadcr14/design-you-need.git
cp -r design-you-need/design-you-need/ .github/copilot-instructions/design-you-need/
```

### Any other AI coding tool

The skill is plain Markdown. Copy the `design-you-need/` folder into wherever your tool reads custom instructions, rules, or system prompts from.

---

## Usage

The skill activates **proactively** whenever you're building frontend UI. You can also invoke it directly:

```
/design-you-need create landing-page
```

### Commands

| Command | What it does |
|---------|-------------|
| `/design-you-need create <category>` | Build a new frontend from scratch with designer-level craft |
| `/design-you-need revamp` | Analyze existing code and upgrade it to high-craft quality |
| `/design-you-need fix-slop` | Detect AI slop patterns and systematically eliminate them |
| `/design-you-need redesign` | Complete redesign with new aesthetic direction |

### Supported categories

E-commerce, SaaS, Agency, Landing Page, Fintech, AI Product, Real Estate, Travel, Corporate, Healthtech, Crypto/Web3, Automotive, Fitness, Food, Portfolio, Edtech, Dashboard, Marketplace, Devtool — and more.

---

## The Research

This skill isn't based on opinions. It's based on a structured analysis of award-winning Dribbble projects, each scored 1-10 on design quality. The gap between high-craft and slop is systematic and teachable.

<table>
<tr>
<td width="50%">

#### Slop projects do this

- Gradient CTA buttons with no design system
- 3+ competing typefaces
- Random decorative 3D blobs
- Generic stock photos, no art direction
- Template ordering: hero → features → pricing → FAQ
- Badge/pill labels like "Our Services"
- Cookie-cutter white cards
- Inconsistent spacing everywhere

</td>
<td width="50%">

#### High-craft projects do this

- 2 fonts max, 1 accent color, one layout grid
- Typography contrast (120px headlines vs 12px labels)
- Photography as the color palette source
- One bold visual moment > ten generic sections
- Custom components, not library defaults
- Section rhythm: dark/light, wide/narrow alternation
- Micro-interactions that reward (hover lift, arrow slide)
- Intentional decorative elements (noise, glow, not blobs)

</td>
</tr>
</table>

### Aesthetic signatures

| Aesthetic | Best for |
|-----------|----------|
| **dark-luxury** | Premium brands, crypto, automotive |
| **warm-minimal** | E-commerce, food, wellness |
| **minimal-corporate** | SaaS, fintech, B2B |
| **bold-expressive** | Agency, portfolio, creative |
| **organic-natural** | Food, wellness, eco-brands |
| **dimensional-layered** | Tech products, AI, innovative brands |
| **editorial** | Fashion, luxury, cultural brands |
| **glassmorphism** | Dashboards, crypto, AI tools |
| **retro-modern** | Food, creative, nostalgic brands |
| **neo-brutalist** | Experimental, artistic |

---

## What's inside

```
design-you-need/
  SKILL.md                              # Core skill (the brain)
  references/
    anti-slop-rules.md                  # Slop + craft examples with evidence
    design-recipes.md                   # Highest-scoring recipes with full breakdowns
    category-playbooks.md               # Best aesthetics + recipes per category
    color-theory.md                     # Palettes, accent rules, contrast pairs
    typography-rules.md                 # Font pairings + special effects
    animation-patterns.md               # Interactions categorized by type
    component-patterns.md               # Button, card, nav, footer CSS
    layout-visuals.md                   # Grid systems, hero patterns, decorative CSS
    e-commerce.md                       # E-commerce project recipes
    agency.md                           # Agency project recipes
    landing-page.md                     # Landing page recipes
    fintech.md                          # Fintech recipes
    saas.md                             # SaaS recipes
    ai-product.md                       # AI product recipes
    ... and 14 more category files
```

---

## How it works

1. **You say** "build me a landing page for my AI startup"
2. **The skill picks** the right aesthetic, hero pattern, color strategy, typography pairing, and animation approach
3. **It builds mobile-first**, with proper responsive breakpoints, touch targets, and stacking
4. **It runs a verification checklist** — checks across mobile, UX, anti-slop, color, and performance
5. **You get** a frontend that looks like you hired a designer — not like you typed "make it modern" into an AI

### The anti-slop engine

Every time the skill generates or reviews frontend code, it checks against known slop red flags. If it detects generic gradient buttons, template section ordering, typography chaos, or any of the other patterns — it fixes them before you ever see slop output.

---

## Before & After

### Before (vanilla AI output)
- Generic hero with gradient blob background
- 3-column feature cards, all identical white rectangles
- "HOME | ABOUT | SERVICES | CONTACT" nav
- Random padding, no rhythm, 4 different fonts

### After (with design-you-need)
- Layered hero with photography-extracted color palette
- Asymmetric bento grid with shadow hierarchy and hover lift
- Custom nav with personality and intentional labels
- Consistent spacing scale, 2 fonts, 1 accent color

---

## FAQ

**Does this work with my AI coding tool?**
Yes. It works with Claude Code, Cursor, Windsurf, Cline, Roo Code, GitHub Copilot, and any tool that supports custom instructions or rules. It's just Markdown files.

**Do I need design experience?**
No. The skill handles design decisions for you. Just describe what you're building.

**Can I customize the aesthetic?**
Yes. Tell the skill your preferred color, aesthetic direction, or reference a specific style — it will adapt and build a proper palette around your choice.

**What about existing projects?**
Use `fix-slop` to detect and eliminate slop patterns, or `revamp` to upgrade the overall design quality.

---

## Contributing

The reference files are the heart of this skill. To improve them:

1. Find an award-winning web design project
2. Analyze it using the scoring criteria in `references/anti-slop-rules.md`
3. Add it to the relevant category file with a full md sub skill
4. Submit a PR

---

## License

MIT

---

<div align="center">

**Built by me who got tired of AI making every website look the same.**

*Award-winning designs analyzed. Slop patterns identified. Craft lessons extracted. Now it's a skill.*

</div>
