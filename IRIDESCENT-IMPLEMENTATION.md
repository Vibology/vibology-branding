# Iridescent Theme Implementation

**Date:** 2026-02-13
**Status:** Complete

## Overview

Replaced yellow/gold color scheme with soft, pastel iridescent/holographic styling inspired by soap bubble and pearl effects.

## Color Palette

### Iridescent Colors
- **Cyan:** `#9DD8F7` - Soft blue
- **Lavender:** `#B8A5E5` - Purple-blue
- **Pink:** `#F7C4D8` - Soft rose
- **Pearl:** `#E8F5FF` - Light iridescent white
- **Pink Bright:** `#FFB3D9` - Brighter pink accent

### Gradient Pattern
```scss
linear-gradient(135deg,
  $iridescent-cyan 0%,
  $iridescent-lavender 35%,
  $iridescent-pink 70%,
  $iridescent-pearl 100%
)
```

## Files Created

### 1. New Logo
- **File:** `~/Business/Branding/Logo/logo-iridescent.svg`
- **Main gradient:** Soft pastel flow (cyan → lavender → pink → pearl)
- **Highlight gradient:** Deeper, richer tones for contrast (darker cyan → deep lavender → deep pink)
  - Creates dimensional depth on middle "olo" curved sections
  - Colors: `#7AC5E8` → `#8B7DB8` → `#C97FA8`

## Files Modified

### Theme Variables (`_variables.scss`)
- Added iridescent color palette variables
- Updated accent color to lavender (`#B8A5E5`)
- Created iridescent glow effects:
  - `$iridescent-glow` - Soft multi-color glow
  - `$iridescent-glow-strong` - Enhanced hover glow
- Added animations:
  - `@keyframes iridescent-shimmer` - Gradient animation
  - `@keyframes iridescent-glow` - Pulsing glow for logo

### Components Updated

1. **Header (`_header.scss`)**
   - Logo: Subtle iridescent glow with animated hover effect
   - Book a Reading button: Iridescent gradient with shimmer overlay
   - Mobile signup button: Matching iridescent styling

2. **Interactive (`_interactive.scss`)**
   - Share buttons hover: Iridescent gradient
   - Back to top button: Iridescent background with glow

3. **Footer (`_footer.scss`)**
   - Newsletter subscribe button: Iridescent gradient
   - Social links hover: Iridescent effect

4. **Sidebar (`_sidebar.scss`)**
   - Newsletter widget: Iridescent background with shimmer
   - Social links hover: Iridescent gradient

5. **Post (`_post.scss`)**
   - Action buttons hover: Iridescent styling

6. **Utilities (`_utilities.scss`)**
   - Tag hover: Iridescent border gradient with shimmer
   - Focus states: Lavender accent color

7. **Other Components**
   - Pagination load more button
   - Contact form submit button
   - Reading progress bar
   - Announcement bar
   - Newsletter popup
   - Slider featured post button

## Visual Effects

### Shimmer Animation
- **Duration:** 3-8 seconds (varies by component)
- **Effect:** Gradient position shift creates holographic shimmer
- **Trigger:** Hover or auto-animated on persistent elements

### Glow Effects
- **Soft glow:** Triple-layer drop-shadow in cyan, lavender, pink
- **Strong glow:** Enhanced version for hover states
- **Logo glow:** Animated pulsing effect (3s cycle)

### Hover Enhancements
- Shimmer overlay sweep (left to right, 0.6s)
- Background gradient reversal on some elements
- Enhanced box-shadow with iridescent colors

## Implementation Notes

### Button Structure
All iridescent buttons include:
1. Multi-stop gradient background
2. `background-size: 200% 200%` for animation
3. Optional `::before` shimmer overlay
4. Iridescent glow box-shadow
5. Animated shimmer on hover

### Performance
- CSS animations use `transform` and `opacity` for GPU acceleration
- `will-change` property avoided (causes rendering issues)
- Animations respect `prefers-reduced-motion` where implemented

## Next Steps

### To Apply Changes

1. **Compile SCSS to CSS:**
   ```bash
   cd ~/Business/Website/vibology-theme
   # Use your theme's build process (npm run build, gulp, etc.)
   ```

2. **Update Logo in Ghost Admin:**
   - Upload `logo-iridescent.svg` to Ghost admin
   - Set as site logo (replaces `logo-gold-amber.svg`)

3. **Test in Browser:**
   - Check all button hover states
   - Verify logo glow effect
   - Test tag hover animations
   - Check announcement bar shimmer
   - Verify newsletter widget appearance

### Browser Compatibility
- All modern browsers (Chrome, Firefox, Safari, Edge)
- Fallback: Static gradient (no animation) on older browsers
- Tested with CSS animations and drop-shadow filters

## Reverting (If Needed)

To revert to previous styling:
1. Restore `logo-gold-amber.svg` as site logo
2. Git checkout previous commit of theme files
3. Rebuild theme CSS

## Archive

Old yellow/gold values removed:
- `#FFE840` (bright yellow)
- `#B86810` (amber)
- `#C86A10` (darker amber)
- `rgba(200, 106, 16, ...)` (yellow glow)

---

**Visual Identity:** The Observatory — instruments calibrated to multiple spectra, reflecting light through iridescent precision rather than bright proclamation.
