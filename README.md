<div align="center">

# design-you-need

### Stop shipping AI slop. Start shipping designs that look like a human made them.

A [Claude Code](https://docs.anthropic.com/en/docs/claude-code) skill that replaces every generic, template-looking frontend AI builds with production-quality design — derived from forensic analysis of **399 award-winning Dribbble projects**.

---

**The problem**

https://github.com/user-attachments/assets/placeholder-ai-slop

https://github.com/user-attachments/assets/placeholder-fix-ai-slop

> After you push to GitHub, drag-and-drop `assets/ai_slop.mp4` and `assets/fix_ai_slop.mp4` into the README editor to get permanent video URLs. Replace the placeholder links above with those URLs.

<sub><b>ai_slop.mp4</b> — AI builds frontends that all look the same. Gradient buttons, decorative blobs, template ordering. This is <b>slop</b>.</sub>
<br>
<sub><b>fix_ai_slop.mp4</b> — Same prompt. Same AI. But now it knows what 288 high-scoring designers actually do.</sub>

</div>

---

## What is this?

AI coding tools (Claude, Cursor, Copilot, etc.) are incredible at writing code — but terrible at design. Every frontend they generate looks the same: the same hero layout, the same gradient buttons, the same card grids, the same soul-less "modern" aesthetic.

**design-you-need** fixes this. It's a Claude Code skill that injects real design intelligence — extracted from studying 399 actual designer-crafted projects — directly into your AI coding workflow.

It knows:
- Which of **10 aesthetic signatures** fits your project category
- Which of **5 hero layout patterns** creates the right visual impact
- The **15 slop red flags** that make frontends look AI-generated
- The **10 craft principles** that separate a score-9 project from a score-4
- **Typography pairings**, **color theory**, **animation patterns**, **component CSS** — all backed by data, not vibes

---

## Install

```bash
# Install via Claude Code CLI
claude install-skill https://github.com/<your-username>/design-you-need
```

Or manually — copy the `design-you-need/` folder into your Claude Code skills directory:

```bash
cp -r design-you-need/ ~/.claude/skills/design-you-need
```

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

This skill isn't based on opinions. It's based on a structured analysis of **399 Dribbble projects**, each scored 1-10 on design quality.

### What we found

**288 projects scored 7+** (high craft). **87 were flagged as slop.** The gap between them is systematic and teachable.

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
- Custom components (312 out of 399 projects)
- Section rhythm: dark/light, wide/narrow alternation
- Micro-interactions that reward (hover lift, arrow slide)
- Intentional decorative elements (noise, glow, not blobs)

</td>
</tr>
</table>

### Aesthetic signatures (from all 399 projects)

| Aesthetic | Projects | Best for |
|-----------|----------|----------|
| **dark-luxury** | 98 | Premium brands, crypto, automotive |
| **warm-minimal** | 94 | E-commerce, food, wellness |
| **minimal-corporate** | 64 | SaaS, fintech, B2B |
| **bold-expressive** | 31 | Agency, portfolio, creative |
| **organic-natural** | 28 | Food, wellness, eco-brands |
| **dimensional-layered** | 28 | Tech products, AI, innovative brands |
| **editorial** | 26 | Fashion, luxury, cultural brands |
| **glassmorphism** | 16 | Dashboards, crypto, AI tools |
| **retro-modern** | 8 | Food, creative, nostalgic brands |
| **neo-brutalist** | 2 | Experimental, artistic |

---

## What's inside

```
design-you-need/
  SKILL.md                              # Core skill (the brain)
  references/
    anti-slop-rules.md                  # 20 slop + 30 craft examples with evidence
    design-recipes.md                   # 40 highest-scoring recipes (score 9/10)
    category-playbooks.md               # Best aesthetics + recipes per category
    color-theory.md                     # Palettes, accent rules, contrast pairs
    typography-rules.md                 # 50 font pairings + 60 special effects
    animation-patterns.md               # 1,913 interactions categorized
    component-patterns.md               # Button, card, nav, footer CSS
    layout-visuals.md                   # Grid systems, hero patterns, decorative CSS
    e-commerce.md                       # 67 project recipes
    agency.md                           # 44 project recipes
    landing-page.md                     # 37 project recipes
    fintech.md                          # 26 project recipes
    saas.md                             # 22 project recipes
    ai-product.md                       # 20 project recipes
    ... and 14 more category files
```

**Total reference material**: ~1.5MB of structured design intelligence across 30 files.

---

## How it works

1. **You say** "build me a landing page for my AI startup"
2. **The skill picks** the right aesthetic (dimensional-layered), hero pattern (layered), color strategy (neutral + one accent), typography pairing, and animation approach
3. **It builds mobile-first**, with proper responsive breakpoints, touch targets, and stacking
4. **It runs a verification checklist** — 30+ checks across mobile, UX, anti-slop, color, and performance
5. **You get** a frontend that looks like you hired a designer — not like you typed "make it modern" into an AI

### The anti-slop engine

Every time the skill generates or reviews frontend code, it checks against the 15 slop red flags. If it detects generic gradient buttons, template section ordering, typography chaos, or any of the other patterns — it fixes them before you ever see slop output.

---

## Examples

### Before (vanilla AI output)
- Generic hero with gradient blob background
- 3-column feature cards, all identical white rectangles
- "HOME | ABOUT | SERVICES | CONTACT" nav
- Random padding, no rhythm, 4 different fonts

### After (with design-you-need)
- Layered hero with photography-extracted color palette
- Asymmetric bento grid with shadow hierarchy and hover lift
- Custom nav with personality and intentional labels
- Consistent 8px spacing scale, 2 fonts, 1 accent color

---

## FAQ

**Does this work with any AI coding tool?**
It's a Claude Code skill, so it works with Claude Code (CLI, VS Code, JetBrains). The reference files could theoretically be adapted for other tools.

**Do I need design experience?**
No. The skill handles design decisions for you. Just describe what you're building.

**Can I customize the aesthetic?**
Yes. Tell the skill your preferred color, aesthetic direction, or reference a specific style — it will adapt.

**What about existing projects?**
Use `/design-you-need revamp` or `/design-you-need fix-slop` to upgrade existing frontends.

---

## Contributing

The reference files are the heart of this skill. To improve them:

1. Find an award-winning web design project
2. Analyze it using the scoring criteria in `references/anti-slop-rules.md`
3. Add it to the relevant category file with a full recipe
4. Submit a PR

---

## License

MIT

---

<div align="center">

**Built by someone who got tired of AI making every website look the same.**

*399 projects analyzed. 87 slop patterns identified. 288 craft lessons extracted.*

</div>
