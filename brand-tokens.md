# Mareluna Brand Tokens

## Colors

| Token | Value | Used in |
|-------|-------|---------|
| `--blu-night` | `#080f3d` | body background, hero overlay, mobile nav overlay |
| `--blu` | `#1a2fa0` | about section radial gradient |
| `--blu-deep` | `#0e1a6b` | gradient layer |
| `--blu-light` | `#2a45c8` | gradient layer |
| `--bianco` | `#ffffff` | primary text, nav logo, hamburger lines |
| `--oro` | `#c9a84c` | gold accent — CTA border, nav hover, prices, badges, eyebrows, divider |
| `--oro-light` | `#e0c878` | progress bar end, gradient highlight |
| `--oro-pale` | `#f0dfa0` | hero quote highlighted words |
| `--teal` | `#2a6e80` | progress bar start |
| `--bg-overlay` | `rgba(8,15,61,0.92)` | hero image overlay |
| *(unnamed)* | `#050c28` | footer background, QR section background |
| *(unnamed)* | `#0a1240` | menu section background |
| *(unnamed)* | `#0d1855` | about section gradient end |
| *(unnamed)* | `#25d366` | WhatsApp float button |

### Hex Palette Summary

```
#080f3d   body / hero overlay (darkest navy)
#050c28   footer / QR section (deepest navy)
#0a1240   menu section
#0d1855   about section end
#0e1a6b   --blu-deep
#1a2fa0   --blu
#2a45c8   --blu-light
#2a6e80   --teal
#c9a84c   --oro (gold accent)
#e0c878   --oro-light
#f0dfa0   --oro-pale
#ffffff   --bianco (text)
#25d366   WhatsApp green
```

---

## Typography

**Google Fonts import:**
```
Cormorant Garamond: ital,wght@0,300;0,400;0,600;0,700;1,300;1,400
Cinzel: wght@400;600
Jost: wght@200;300;400;500
```

### Font Roles

| Role | Family | Weight | Style |
|------|--------|--------|-------|
| Display / headings | Cinzel | 400, 600 | normal |
| Body / UI | Jost | 200–500 | normal |
| Serif / quotes / menu items | Cormorant Garamond | 300, 400, 600 | normal + italic |

### Specific Sizes & Spacing

| Element | Font | Size | Weight | Letter-spacing |
|---------|------|------|--------|----------------|
| Hero title (MARELUNA) | Cinzel | `clamp(3.5rem, 9vw, 7rem)` | 400 | `8px` |
| Hero subtitle (italic tagline) | Cormorant Garamond | `clamp(0.9rem, 2vw, 1.2rem)` | 300 italic | `4px` |
| Hero badge (e.g. "BELVEDERE MARITTIMO · CALABRIA") | Jost | `0.68rem` | — | `5px` |
| Hero quote | Cormorant Garamond | `clamp(1rem, 2.2vw, 1.45rem)` | 300 italic | — |
| Section eyebrow (e.g. "CHI SIAMO") | Jost | `0.65rem` | 300 | `6px` |
| Section title (h2) | Cinzel | `clamp(1.8rem, 3.5vw, 2.8rem)` | 400 | `2px` |
| Nav logo text | Cinzel | `1.1rem` | 600 | `3px` |
| Nav links | Jost | `0.72rem` | 300 | `3px` |
| Menu item name | Cormorant Garamond | `1.05rem` | 600 | — |
| Menu item price | Jost | `0.95rem` | 300 | — |
| Tab buttons | Jost | `0.65rem` | 300 | `3px` |
| Footer logo name | Cinzel | `1rem` | — | `3px` |
| Footer address | Jost | `0.73rem` | 300 | `1px` |
| Footer copyright | Jost | `0.65rem` | 300 | `2px` |

---

## Logo

**File:** `assets/logo.png` (208 KB, PNG with transparency)

The logo is embedded as a base64 PNG in `index.html` (`const logoDataURL`).
Extracted copy saved at `assets/logo.png`.

Usage contexts:
- Hero: `width: 420px` (max `85vw`), `drop-shadow(0 0 40px rgba(201,168,76,0.25))`
- Nav: `width: 42px height: 42px`, `filter: brightness(1.1)`
- About section: `width: 75%` of container, `drop-shadow(0 0 40px rgba(201,168,76,0.2))`
- Footer: `width: 36px`

---

## Other Design Details

- **Border radius:** `2px` (about logo frame) — otherwise mostly square/sharp edges
- **Transitions:** `0.3s` default, `0.4s` for CTA hover, `0.5s` for nav
- **Section padding:** `100px 50px` desktop, `70px 25px` mobile
- **Max content width:** `1100–1200px`
- **Progress bar:** `linear-gradient(90deg, #2a6e80, #c9a84c, #e0c878)`, height `2px`
- **QR section background:** `#050c28` with `border-top: 1px solid rgba(201,168,76,0.1)`
