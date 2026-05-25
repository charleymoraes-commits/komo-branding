# Komo Design System

> **Own The Moment** — AI-powered design system for Komo's engagement platform.

---

## Color Palette

### Primary Gradient
The signature Komo gradient flows from left to right across all branded materials:

```
#009EE0 (Cyan Blue)
  ↓
#7430FE (Purple)
  ↓
#CD29FE (Hot Pink)
  ↓
#F87128 (Energetic Orange)
```

### Core Colors

| Color | Hex | Usage |
|-------|-----|-------|
| **Cyan Blue** | `#009EE0` | Primary, CTAs, accents |
| **Deep Purple** | `#7430FE` | Gradients, highlights |
| **Hot Pink** | `#CD29FE` | Accent, gradients |
| **Orange** | `#F87128` | Energy, accents, hover states |
| **Yellow Accent** | `#F1E52C` | K badge, decorative dots |

### Neutral Colors

| Color | Hex | Light Mode | Dark Mode |
|-------|-----|-----------|-----------|
| **Pure White** | `#FFFFFF` | Background | Text |
| **Light Gray** | `#F5F5F5` | Surfaces | — |
| **Medium Gray** | `#E0E0E0` | Borders | — |
| **Dark Gray** | `#666666` | Text | — |
| **Pure Black** | `#09090E` | — | Background |
| **Dark Surface** | `#1A1A21` | — | Cards/Surfaces |

---

## Typography

### Font Families

**Headlines & Bold Text:** `Poppins`
- ExtraBold (800) — Hero headlines, section titles
- SemiBold (600) — Subheadings, emphasis
- Regular (400) — Navigation, labels

**Body & Descriptions:** `Figtree`
- Regular (400) — Body copy, descriptions
- Medium (500) — Emphasized body text

### Scale

| Style | Font | Size | Weight | Usage |
|-------|------|------|--------|-------|
| **H1 (Hero)** | Poppins | 60–80px | ExtraBold | Page titles, main headlines |
| **H2 (Section)** | Poppins | 36–48px | SemiBold | Section headers, feature titles |
| **H3 (Subsection)** | Poppins | 24–32px | SemiBold | Subheadings |
| **Body Large** | Figtree | 18px | Regular | Prominent body text |
| **Body Regular** | Figtree | 16px | Regular | Standard paragraph text |
| **Body Small** | Figtree | 14px | Regular | Secondary text, captions |
| **Label** | Poppins | 12px | SemiBold | Tags, labels, eyebrows (UPPERCASE) |
| **Caption** | Figtree | 12px | Regular | Fine print, metadata |

---

## Spacing System

All spacing is based on an 8px grid for consistency and scalability.

| Token | Size | Usage |
|-------|------|-------|
| `xs` | 4px | Micro spacing, icon gaps |
| `sm` | 8px | Tight spacing, internal padding |
| `md` | 16px | Standard padding, component spacing |
| `lg` | 24px | Section spacing, card margins |
| `xl` | 32px | Large section spacing |
| `2xl` | 48px | Full-screen section gaps |

---

## Components

### Buttons

#### Primary Button
```
Background: Linear gradient (#009EE0 → #7430FE)
Text: White, Poppins SemiBold, 14px
Padding: 12px 24px
Border Radius: 8px
Hover: Brightness +10%, shadow lift
```

#### Secondary Button
```
Background: Transparent
Border: 2px solid #009EE0
Text: #009EE0, Poppins SemiBold, 14px
Padding: 12px 24px
Border Radius: 8px
Hover: Background #009EE0, text white
```

#### Ghost Button
```
Background: Transparent
Text: #666666 (light mode) / #B0B0B0 (dark mode)
Border: None
Padding: 12px 24px
Hover: Text color #009EE0
```

### Cards

```
Background: #FFFFFF (light) / #1A1A21 (dark)
Border: 1px solid #E0E0E0 (light) / #2A2A30 (dark)
Border Radius: 12px
Padding: 24px
Shadow: 0 2px 8px rgba(0,0,0,0.1) (light) / none (dark)
Hover: Border color → gradient start (#009EE0)
```

### Input Fields

```
Background: #F5F5F5 (light) / #0F0F14 (dark)
Border: 1px solid #E0E0E0 (light) / #2A2A30 (dark)
Border Radius: 8px
Padding: 12px 16px
Font: Figtree Regular, 14px
Focus: Border → #009EE0, shadow: 0 0 0 3px rgba(0,158,224,0.1)
```

### Tags & Labels

```
Background: #F5F5F5 (light) / #1A1A21 (dark)
Border: 1px solid #E0E0E0 (light) / #2A2A30 (dark)
Border Radius: 6px
Padding: 4px 12px
Font: Poppins, 12px, SemiBold, uppercase
Color: #666666 (light) / #B0B0B0 (dark)
```

---

## Theme Modes

### Light Mode
```
Background: #FFFFFF
Surface: #F5F5F5
Border: #E0E0E0
Text Primary: #1A1A1A
Text Secondary: #666666
Text Tertiary: #999999
Accent: #009EE0
```

### Dark Mode
```
Background: #09090E
Surface: #1A1A21
Surface Secondary: #0F0F14
Border: #2A2A30
Text Primary: #FFFFFF
Text Secondary: #B0B0B0
Text Tertiary: #808080
Accent: #009EE0
```

---

## Logo Usage

### Logo Variants

| Variant | File | Usage |
|---------|------|-------|
| **Logo + Slogan (White)** | `Komo_main_version_white.svg` | Dark backgrounds, hero sections |
| **Logo + Slogan (Black)** | `Komo_main_version_black.svg` | Light backgrounds |
| **Logo Only (White)** | `Komo_logo_white.svg` | Dark backgrounds, compact layouts |
| **Logo Only (Black)** | `Komo_logo_black.svg` | Light backgrounds, compact layouts |
| **Symbol (Icon)** | `Komo_symbol.svg` | Favicon, app icon, small mark |

### Logo Rules

✅ **DO:**
- Use white logo on dark backgrounds
- Use black logo on light backgrounds
- Maintain minimum safety margin (equal to width of "K")
- Scale proportionally

❌ **DON'T:**
- Rotate or tilt the logo
- Apply non-brand colors or gradients
- Place tagline above logotype
- Use blue dot inside K badge (must be black)
- Apply to busy backgrounds without contrast

---

## Animations & Interactions

### Transition Timing
```
Fast (UI feedback):      0.15s – 0.2s  (cubic-bezier(0.4, 0, 0.2, 1))
Standard (navigation):   0.3s          (cubic-bezier(0.4, 0, 0.2, 1))
Slow (emphasis):         0.5s          (cubic-bezier(0.4, 0, 0.2, 1))
```

### Common Interactions
- **Hover**: Slight scale (1.02–1.05) + color shift
- **Focus**: 3px accent border + shadow
- **Active**: Darker shade + lifted shadow
- **Disabled**: 50% opacity + cursor not-allowed

---

## Accessibility

### Color Contrast
- Text on colored backgrounds: Minimum **4.5:1 WCAG AA**
- UI elements: Minimum **3:1 WCAG AA**
- Primary gradient on white: Use overlays or text stroke for accessibility

### Typography
- Minimum font size: **14px** for body text
- Line height: **1.5** for body, **1.2** for headings
- Letter spacing: **–0.5px** on headlines (tight), **0px** on body

### Interactive Elements
- Minimum touch target: **44px × 44px**
- Focus indicators always visible (no `outline: none`)
- Keyboard navigation fully supported

---

## Usage Guidelines

### Hero Sections
Use gradient backgrounds with white text. Gradient direction: left to right or top-right bloom.

### Feature Lists
Poppins SemiBold headlines + Figtree Regular descriptions. Use bullet points or numbered lists.

### CTAs
Always use primary gradient button. Label with action verb + outcome (e.g., "Get Design System").

### Consistency
All components use the 8px grid. Spacing, sizing, and alignment follow multiples of 8px.

---

## Quick References

**Brand Tagline:** "Own The Moment"

**Primary CTA:** Gradient button (#009EE0 → #7430FE → #F87128)

**Secondary CTA:** Cyan outline button (#009EE0)

**Gradient Direction:** Left to right (or top-right bloom for full-screen backgrounds)

**Default Border Radius:** 8px (buttons/inputs), 12px (cards)

**Dark Background:** `#09090E`

**Dark Surface:** `#1A1A21`

---

**Built for Komo Technologies**  
*Last updated: 2026*  
For updates and full branding assets, visit [komo.tech](https://komo.tech)
