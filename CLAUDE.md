# Vibology Brand Identity

## Design Philosophy

As your expert graphic designer and brand innovator, I approach Vibology's visual identity with the precision of sacred geometry and the subtlety of light through a prism. This brand lives at the intersection of mystical depth and contemporary sophistication — **The Observatory principle**: instruments calibrated to multiple spectra, reflecting light through iridescent precision rather than bright proclamation.

## Brand Essence

**Vibology** integrates five symbolic instruments (Astrology, Human Design, Personal Mythos, Tarot, The Astrolabe) into a unified framework. The visual identity must:

- **Balance mysticism with modernity** - Not New Age cliché, not sterile corporate
- **Convey precision and depth** - Technical rigor meets symbolic wisdom
- **Feel both intimate and cosmic** - Personal navigation through universal patterns
- **Express dimensionality** - Multiple systems, multiple layers, one coherent whole
- **Radiate subtle luminosity** - Iridescence without garishness, soap bubble quality

**Core Metaphor**: The dodecahedron — twelve pentagonal faces representing sacred geometry, the five-instrument integration, and the multifaceted nature of consciousness.

---

## Visual Identity System

### Logo

**Primary Mark**: Dodecahedron wireframe + "Vibology" wordmark

**Design Details**:
- **Dodecahedron**: Thick visible edges, thinner dotted hidden edges (dimensional depth)
- **Wordmark**: Clean, contemporary typography with dimensional letterforms
- **Gradient**: Vertical flow — Cyan → Lavender → Pearl
- **Scale**: 114×114 unit icon paired with wordmark at consistent proportion

**Logo Files**:
- `logo-iridescent.svg` - Wordmark only (primary use)
- `icon-iridescent.svg` - Dodecahedron icon (1600×1600, apps/favicon)
- `logo-combined.svg` - Combined mark (special applications)
- `logo.png` / `logo.pdf` - Export formats for print/compatibility

**Usage Guidelines**:
- Minimum size: 32px height for wordmark, 24px for icon
- Clear space: 0.5× the height of the mark on all sides
- Always use on neutral backgrounds (white, very light gray, dark navy/black)
- Never distort, rotate, or apply filters to the logo

### Color Palette

**Iridescent Spectrum** (Primary Brand Colors):

| Color | Hex | RGB | Usage |
|-------|-----|-----|-------|
| **Cyan** | `#9DD8F7` | 157, 216, 247 | Gradient start, accent highlights |
| **Lavender** | `#B8A5E5` | 184, 165, 229 | Primary brand color, gradient middle |
| **Pink** | `#F7C4D8` | 247, 196, 216 | Soft accent, gradient flow |
| **Pearl** | `#E8F5FF` | 232, 245, 255 | Gradient end, light backgrounds |
| **Pink Bright** | `#FFB3D9` | 255, 179, 217 | Hover states, call-to-action |

**Dimensional Depth** (Highlight Gradient):
- Darker Cyan: `#7AC5E8` (122, 197, 232)
- Deep Lavender: `#8B7DB8` (139, 125, 184)
- Deep Pink: `#C97FA8` (201, 127, 168)

**Supporting Colors**:
- **Deep Indigo**: `#2D3561` - Text on gradient backgrounds, strong contrast
- **Twilight Navy**: `#1a1d2e` - Dark backgrounds, depth
- **Pure White**: `#FFFFFF` - Clean space, clarity
- **Warm Amber** (legacy): `#B86810` - Used sparingly if needed for warmth

### Gradient Patterns

**Primary Gradient** (Logo, buttons, accents):
```
linear-gradient(180deg,
  #9DD8F7 0%,    /* Cyan */
  #B8A5E5 35%,   /* Lavender */
  #E8F5FF 100%   /* Pearl */
)
```

**Extended Flow** (Backgrounds, large surfaces):
```
linear-gradient(135deg,
  #9DD8F7 0%,    /* Cyan */
  #B8A5E5 35%,   /* Lavender */
  #F7C4D8 70%,   /* Pink */
  #E8F5FF 100%   /* Pearl */
)
```

**Dimensional Depth** (Middle letterforms, "olo" in logo):
```
linear-gradient(180deg,
  #7AC5E8 0%,    /* Darker Cyan */
  #8B7DB8 50%,   /* Deep Lavender */
  #C97FA8 100%   /* Deep Pink */
)
```

### Typography

**Primary Font Family**: Cabin (clean, modern, readable)
- **Headings**: Cabin Bold (700)
- **Body**: Cabin Regular (400)
- **Emphasis**: Cabin Medium (500)

**Secondary/Code**: System monospace stack
- SF Mono, Menlo, Monaco, Consolas

**Hierarchy**:
- H1: 48px/56px Bold
- H2: 36px/44px Bold
- H3: 28px/36px Bold
- H4: 24px/32px Medium
- Body: 18px/28px Regular
- Small: 14px/20px Regular

### Visual Effects

**Iridescent Glow** (Soft):
```css
box-shadow:
  0 0 20px rgba(157, 216, 247, 0.3),  /* Cyan */
  0 0 40px rgba(184, 165, 229, 0.2),  /* Lavender */
  0 0 60px rgba(247, 196, 216, 0.1);  /* Pink */
```

**Iridescent Glow** (Strong - Hover states):
```css
box-shadow:
  0 0 30px rgba(157, 216, 247, 0.5),
  0 0 60px rgba(184, 165, 229, 0.3),
  0 0 90px rgba(247, 196, 216, 0.2);
```

**Shimmer Animation**:
```css
@keyframes iridescent-shimmer {
  0% { background-position: 0% 50%; }
  50% { background-position: 100% 50%; }
  100% { background-position: 0% 50%; }
}

/* Apply to gradients with background-size: 200% 200% */
animation: iridescent-shimmer 6s ease-in-out infinite;
```

**Hover Enhancement**:
- Shimmer overlay sweep (left to right, 0.6s)
- Enhanced box-shadow with iridescent glow
- Subtle scale transform (1.02-1.05)

---

## Design Principles

### 1. Restraint Over Excess

**Philosophy**: Iridescence should be sophisticated, not garish. Think soap bubble quality, pearl nacre, holographic subtlety — not rainbow explosion or disco ball.

**Application**:
- Use gradients on focal points (logo, primary CTA, key accents)
- Large text blocks: solid colors, not gradients
- Backgrounds: mostly solid with subtle gradient overlays
- Animations: gentle, purposeful, never distracting

### 2. Dimensional Depth

**Philosophy**: Vibology navigates multiple systems simultaneously. The visual language should express layers, dimensions, and depth.

**Application**:
- Dodecahedron icon shows both visible and hidden edges
- Gradient shifts create perceived depth (darker = receding, lighter = advancing)
- Drop shadows and glows create atmospheric layering
- Overlapping elements with transparency

### 3. Sacred Geometry Meets Contemporary Design

**Philosophy**: Honor the esoteric roots while remaining contemporary and accessible.

**Application**:
- Geometric precision (dodecahedron, circular geometry, constellation patterns)
- Clean, minimal layouts (not ornate or baroque)
- Modern typography (not mystical script fonts)
- Technical accuracy meets symbolic meaning

### 4. Light as Information

**Philosophy**: The Observatory metaphor — instruments reveal what's already present by refraction and precision.

**Application**:
- Iridescent effects as "light through a prism"
- Dark backgrounds let light elements glow
- Negative space as important as positive
- Subtle luminosity suggests insight and clarity

### 5. Cohesion Across Systems

**Philosophy**: Five instruments, one unified voice.

**Application**:
- Consistent visual language across all touchpoints
- Logo, website, app, print materials share the same iridescent palette
- Icon system uses dodecahedron geometry as base
- Typography and spacing systems remain constant

---

## Brand Applications

### Business Cards

**Specifications**:
- **Size**: 3.5" × 2" (standard US) or 85mm × 55mm (EU)
- **Paper**: Premium uncoated stock with soft-touch finish (suggests tactility)
- **Finish**: Spot UV on logo for dimensional effect

**Front**:
- Centered logo (iridescent gradient)
- Deep twilight navy background (`#1a1d2e`)
- Optional: subtle constellation pattern in background (5% opacity)

**Back**:
- Name + title (Cabin Bold)
- Contact info (Cabin Regular)
- Website URL
- QR code linking to vibology.com (optional)
- Same twilight background or pearl white for contrast

**Pro Tip**: Consider holographic foil stamping for the logo on premium cards — physical iridescence to match digital identity.

### Signage

**Materials**:
- Acrylic with LED edge-lighting (dodecahedron glows)
- Brushed aluminum with printed/etched logo
- Fabric banners for events (full-color iridescent print)

**Considerations**:
- Logo must remain legible at distance
- High contrast needed for readability
- Pearl/white version on dark navy for maximum visibility
- Avoid complex gradients on small signage (under 12" wide)

### Social Media Assets

**Profile Images**:
- Dodecahedron icon (icon-iridescent.svg)
- Square crop: 1024×1024px minimum
- Ensure icon remains centered and visible on both light and dark platforms

**Cover Images** (Facebook, LinkedIn, etc.):
- Twilight navy background with iridescent gradient overlay
- Logo positioned left or center
- Tagline option: "Five Instruments. One Voice."
- Dimensions vary by platform (use templates)

**Post Graphics**:
- Use pearl/white backgrounds with lavender accents for light mode feeds
- Use twilight navy backgrounds with iridescent elements for dark/moody aesthetic
- Maintain generous white space
- Typography: Large Cabin Bold headlines, Cabin Regular body

### Presentation Templates

**Slide Deck**:
- Title slide: Full iridescent gradient background with logo
- Content slides: White background, lavender accents, minimal iridescent touches
- Section dividers: Twilight navy with gradient overlay
- Footer: Small logo + slide number

**Print Collateral** (Brochures, Zines, Guides):
- Cover: Full-color iridescent gradient with logo
- Interior: Clean white pages with lavender section headers
- Pull quotes: Lavender background with deep indigo text
- Iconography: Geometric shapes derived from dodecahedron

### Packaging (if applicable)

**Considerations**:
- Box/envelope: Twilight navy with iridescent logo foil stamp
- Interior: Pearl or soft lavender tissue paper
- Stickers/seals: Dodecahedron icon in holographic material
- Thank you cards: Minimal design with handwritten note space

---

## Design Workflow

### Creating New Brand Assets

**1. Research & Concept**
- Understand the purpose and audience
- Identify which brand elements are most appropriate (logo, icon, colors, etc.)
- Sketch rough layouts and compositions
- Consider how the asset fits into the broader brand ecosystem

**2. Design Iteration**
- Start with established brand elements (don't reinvent)
- Apply design principles (restraint, depth, geometry, light, cohesion)
- Create 2-3 variations for review
- Ensure accessibility (contrast, legibility, color blindness considerations)

**3. Review & Refinement**
- Present options with rationale for design choices
- Gather feedback on effectiveness and aesthetic appeal
- Refine based on input
- Prepare final files in appropriate formats

**4. Production & Delivery**
- Export files in required formats (SVG, PNG, PDF, print-ready)
- Provide usage guidelines for new assets
- Archive source files in this repo with clear naming
- Update brand documentation if new patterns emerge

### File Naming Conventions

- `logo-[variant]-[format].[ext]` - e.g., `logo-iridescent-horizontal.svg`
- `icon-[variant]-[size].[ext]` - e.g., `icon-iridescent-512.png`
- `business-card-[side]-[version].[ext]` - e.g., `business-card-front-v2.pdf`
- `social-[platform]-[type].[ext]` - e.g., `social-instagram-profile.png`

### Version Control

- Commit completed assets with clear messages
- Use branches for experimental designs
- Tag major brand updates (e.g., `v2.0-iridescent-launch`)
- Archive superseded assets in `.archive/` folder (not in repo root)

---

## Brand Innovation

### Exploring New Directions

While maintaining the core iridescent identity, we can innovate in:

**1. Animated Branding**
- Logo animation for video intros (dodecahedron rotates, iridescent shimmer flows)
- Micro-interactions for web/app (buttons shimmer on hover, transitions flow like light)
- Loading states that reflect the Observatory metaphor (calibrating instruments)

**2. Extended Color Palette**
- Introduce complementary warm tones (amber, gold) sparingly for depth
- Seasonal variations (winter: cooler blues, summer: warmer pinks)
- Dark mode optimization (deeper twilight, stronger glows)

**3. Iconography System**
- Derive icon set from dodecahedron geometry
- Each of the five instruments gets a geometric symbol
- Consistent line weight and iridescent gradient treatment

**4. Typography Enhancements**
- Custom ligatures or modifications to Cabin for wordmark
- Alternate headline font for specific contexts (still modern, complementary to Cabin)
- Dimensional typography experiments (3D extrusion with gradient)

**5. Physical Manifestations**
- Holographic materials for print collateral
- LED-backlit signage that creates real iridescence
- Embroidered logo on apparel (metallic thread gradient)

### Innovation Guidelines

**Do**:
- Experiment boldly with new applications
- Push the boundaries of the iridescent aesthetic
- Create variations that enhance the core identity
- Test new ideas in low-stakes contexts first (social posts, internal docs)

**Don't**:
- Abandon the core palette without strong rationale
- Create designs that feel disconnected from the established identity
- Over-animate or add unnecessary effects
- Forget accessibility in pursuit of visual wow-factor

---

## Technical Specifications

### Digital Export Settings

**Web**:
- SVG: Native format, optimize with SVGO
- PNG: 2x resolution for retina displays (e.g., 256×256 for 128px display)
- WebP: For performance-critical applications
- Favicon: 16×16, 32×32, 48×48, 192×192, 512×512 (PNG)

**Print**:
- PDF: Press-ready with bleed and crop marks
- EPS/AI: Vector source files for print vendors
- CMYK conversion: Test iridescent gradients in print gamut (may need adjustment)
- Resolution: 300dpi minimum for raster elements

### Color Management

- **Color Space (Digital)**: sRGB
- **Color Space (Print)**: CMYK (with spot color options for logo foil stamping)
- **Gradient Banding**: Use high bit-depth exports (16-bit PNG, high-quality PDF)
- **Accessibility**: Maintain WCAG AA contrast ratios (4.5:1 for text, 3:1 for UI elements)

---

## Brand Assets Inventory

### Current Files

**Logos**:
- `logo-iridescent.svg` - Primary wordmark
- `logo-combined.svg` - Dodecahedron + wordmark
- `logo.svg` / `logo.png` / `logo.pdf` - Export formats

**Icons**:
- `icon-iridescent.svg` - Primary dodecahedron (1600×1600)
- `icon-transparent.svg` - Transparent background variant
- `icon.svg` - Base geometric version
- `icon-new.svg` - Alternative variant
- `icon.pxd` - Pixelmator source file

**Documentation**:
- `IRIDESCENT-IMPLEMENTATION.md` - Technical implementation notes
- `CLAUDE.md` - This brand guide

### Needed Assets

**Priority 1** (Essential):
- [ ] Business card designs (front/back)
- [ ] Email signature template
- [ ] Letterhead/stationery template
- [ ] Social media profile/cover templates

**Priority 2** (Soon):
- [ ] Presentation deck template
- [ ] Brochure/one-sheet design
- [ ] Icon set (five instruments + common UI icons)
- [ ] App icon variants (macOS, iOS if applicable)

**Priority 3** (Eventually):
- [ ] Signage designs (physical office/event)
- [ ] Apparel mockups (t-shirts, hoodies)
- [ ] Packaging designs (if offering physical products)
- [ ] Animated logo (for video/web intros)

---

## Collaboration & Feedback

### Working with Me

As your brand designer, I bring:
- **Expert eye for composition, color, and typography**
- **Deep understanding of the Vibology philosophy and five-instrument framework**
- **Ability to balance aesthetic beauty with functional clarity**
- **Commitment to innovation within cohesive brand guidelines**

### Providing Feedback

**Helpful**:
- "The gradient feels too strong here — can we soften the transition?"
- "This doesn't feel mystical enough — needs more depth/atmosphere"
- "The text is hard to read on this background — needs better contrast"

**Less Helpful**:
- "Make it pop" (what aspect? color? size? contrast?)
- "I'll know it when I see it" (give me direction to iterate toward)
- "Can we try every color combination?" (too broad, no constraints)

**Best**:
- Share visual references that resonate
- Describe the feeling/impression you want to create
- Point to specific elements that work or don't work
- Trust the design process and established brand guidelines

---

## Related Repositories

- **vibology-website** - Web implementation of brand identity
- **vibology-app** - macOS application design (uses brand assets)
- **the-ephemeris** - Content that informs brand voice and philosophy

---

*"The Observatory principle: instruments calibrated to multiple spectra, reflecting light through iridescent precision rather than bright proclamation."*
