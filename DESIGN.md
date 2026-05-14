# Design System Inspired by Atomic

## 1. Visual Theme & Atmosphere

Atomic's design system embodies a bold, high-contrast aesthetic rooted in contemporary digital culture. The atmosphere is sophisticated yet approachable, built on deep blacks and near-blacks paired with vibrant accent colors that command attention. The visual language prioritizes clarity, minimal ornamentation, and cinematic presentation—every element serves a functional purpose while maintaining a premium, professional edge. Geometric precision and deliberate whitespace create breathing room, while strategic use of color gradients and saturated accent tones energize the interface. This is a system designed for agencies that push creative boundaries while maintaining meticulous craft.

**Key Characteristics**
- Ultra-high-contrast dark backgrounds with light text for premium feel
- Minimal geometric forms with no decorative flourish
- Strategic accent color usage (vibrant red and cyan gradients)
- Generous whitespace and breathing room between elements
- Precise typography hierarchy with consistent weight relationships
- Modern sans-serif foundation supporting brand-forward presentation
- Dark mode as primary aesthetic with selective bright accents

## 2. Color Palette & Roles

### Primary
- **Atomic Red** (`#FF6568`): Primary call-to-action, accent highlights, emphasis in dark contexts. Used sparingly for maximum impact.

### Accent Colors
- **Error Red** (`#E40014`): Error states, destructive actions, alerts requiring immediate attention.

### Interactive
- **Ghost Button Fill** (`rgba(197, 197, 197, 0.15)`): Subtle interactive element backgrounds with transparency for integration into dark surfaces.

### Neutral Scale
- **White** (`#FFFFFF`): Primary text on dark backgrounds, icons, and light content areas. Highest contrast for readability.
- **Light Gray** (`#C5C5C5`): Secondary text, disabled states, and tertiary information. Provides visual hierarchy without sacrificing legibility.
- **Off-White** (`#FAFAFA`): Light surface backgrounds, subtle contrasting panels.
- **Light Surface** (`#F5F5F5`): Minimal use; reserved for extremely light backgrounds or highlights.
- **Border Gray** (`#E5E5E5`): Divider lines and subtle borders in light contexts.

### Surface & Borders
- **Very Dark Gray** (`#262626`): Secondary dark surfaces, subtle elevation from pure black.
- **Black** (`#0A0A0A`): Deep background surfaces, maximum contrast foundation.
- **Almost Black** (`#171717`): Primary dark background, near-black for brand consistency.

## 3. Typography Rules

### Font Family
**Primary:** Inter, -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif

**Secondary:** Inter (consistent weight scale; no serif alternative necessary)

### Hierarchy

| Role | Font | Size | Weight | Line Height | Letter Spacing | Notes |
|------|------|------|--------|-------------|----------------|-------|
| Display | Inter | 67.51px | 500 | 67.51px | 0px | Hero statements, main page titles. Bold, commanding presence. |
| Heading 1 | Inter | 28.94px | 500 | 23.15px | 0px | Section headers, feature titles. Tight line height for compact feel. |
| Heading 2 | Inter | 29.85px | 500 | 29.85px | 0px | Subsection headers, card titles. Aligned line height. |
| Body | Inter | 14.47px | 500 | 14.47px | 0px | Standard paragraph text, descriptions. Medium weight for legibility. |
| Body Small | Inter | 13.22px | 600 | 13.22px | 0px | Labels, captions, metadata. Slightly bolder for emphasis. |
| Link | Inter | 16px | 400 | 24px | 0px | Navigation links, inline actions. Regular weight, generous line height. |

### Principles
- Maintain consistent weight—avoid extremes of thin or ultra-bold; medium weight (500) dominates.
- Line heights align closely with font size to create compact, controlled typography.
- Use size shifts rather than weight shifts to establish hierarchy; weight remains relatively consistent.
- Generous baseline alignment ensures optical balance across all sizes.
- Maximize readability through high contrast (white on black) over size alone.

## 4. Component Stylings

### Buttons

**Primary Button (Large)**
- Background: `rgba(0, 0, 0, 0)` (transparent)
- Text Color: `#FFFFFF`
- Font Size: `16px`
- Font Weight: `400`
- Padding: `0px`
- Border Radius: `0px`
- Border: `none`
- Height: `80px`
- Width: `175px`
- Line Height: `24px`
- Box Shadow: `none`
- Hover: Slightly increase opacity or add subtle underline

**Secondary Button (Rounded)**
- Background: `rgba(197, 197, 197, 0.15)`
- Text Color: `#FFFFFF`
- Font Size: `16px`
- Font Weight: `400`
- Padding: `0px`
- Border Radius: `28px`
- Border: `none`
- Height: `56px`
- Width: `86px`
- Line Height: `24px`
- Box Shadow: `none`
- Hover: Increase background opacity to `rgba(197, 197, 197, 0.25)`

**Ghost Button (Minimal)**
- Background: `rgba(0, 0, 0, 0)` (transparent)
- Text Color: `#FFFFFF`
- Font Size: `16px`
- Font Weight: `400`
- Padding: `0px`
- Border Radius: `0px`
- Border: `1px solid #C5C5C5` (optional, for definition)
- Height: `32px`
- Width: auto
- Line Height: `24px`
- Box Shadow: `none`
- Hover: Increase text color opacity or change to `#C5C5C5`

### Navigation

**Navigation Link**
- Background: `rgba(0, 0, 0, 0)`
- Text Color: `#FFFFFF`
- Font Size: `16px`
- Font Weight: `400`
- Padding: `0px 16px`
- Border Radius: `0px`
- Border: `none`
- Height: `24px`
- Line Height: `24px`
- Box Shadow: `none`
- Active State: Text color changes to `#FF6568` or underline appears
- Hover: Opacity decreases to `0.7` or changes to `#C5C5C5`

### Links

**Primary Link**
- Background: `rgba(0, 0, 0, 0)`
- Text Color: `#FFFFFF`
- Font Size: `16px`
- Font Weight: `400`
- Padding: `0px`
- Border Radius: `0px`
- Border: `none`
- Line Height: `24px`
- Box Shadow: `none`
- Text Decoration: `underline` (on hover)
- Hover: Underline appears; opacity shifts to `0.8`

**Secondary Link (Footer/Small)**
- Background: `rgba(0, 0, 0, 0)`
- Text Color: `#C5C5C5`
- Font Size: `14px`
- Font Weight: `600`
- Padding: `0px`
- Border Radius: `0px`
- Border: `none`
- Line Height: `20px`
- Box Shadow: `none`
- Hover: Color shifts to `#FFFFFF`

### Cards & Containers

**Standard Card**
- Background: `#0A0A0A` or `#171717`
- Border: `1px solid #262626`
- Border Radius: `0px` (sharp edges) or `8px` (if softness needed)
- Padding: `40px`
- Box Shadow: `none`
- Text Color: `#FFFFFF`

**Overlay/Modal**
- Background: `rgba(0, 0, 0, 0.95)`
- Backdrop: `rgba(0, 0, 0, 0.7)` (semi-transparent)
- Border Radius: `0px`
- Padding: `60px 40px`
- Box Shadow: `none`

### Inputs & Forms

**Text Input**
- Background: `#262626` or `rgba(197, 197, 197, 0.1)`
- Text Color: `#FFFFFF`
- Placeholder Color: `#C5C5C5`
- Font Size: `16px`
- Font Weight: `400`
- Padding: `16px 20px`
- Border: `1px solid #262626`
- Border Radius: `4px`
- Line Height: `24px`
- Focus State: Border color changes to `#FF6568`; box-shadow: `0 0 0 3px rgba(255, 101, 104, 0.2)`

**Text Area**
- Background: `#262626`
- Text Color: `#FFFFFF`
- Font Size: `14px`
- Font Weight: `400`
- Padding: `16px 20px`
- Border: `1px solid #262626`
- Border Radius: `4px`
- Line Height: `1.5`
- Focus State: Border color changes to `#FF6568`

## 5. Layout Principles

### Spacing System

Base unit: **8px**

Scale progression:
- **8px**: Minimal gaps between closely related elements (icon + label)
- **12px**: Tight grouping (small form gaps)
- **16px**: Standard spacing within components
- **20px**: Internal padding of medium components
- **32px**: Section-to-section breathing room
- **40px**: Card/container padding
- **52px**: Large section margins
- **60px**: Page-level section separation
- **72px**: Hero to content transition
- **84px**: Major layout blocks
- **140px**: Full-page vertical rhythm (hero height or section height multiplier)

### Grid & Container

- **Max Width**: 1280px (content container, with 40px gutters on sides)
- **Column Strategy**: 12-column flexible grid or CSS Grid with auto-fit
- **Gutters**: 40px horizontal padding on desktop; 20px on tablet; 16px on mobile
- **Vertical Rhythm**: Establish consistent section heights using the spacing scale (multiples of 8px)

### Whitespace Philosophy

Whitespace is purposeful and aggressive. Large breathing room between sections creates visual clarity and prevents cognitive overload. Internal component padding remains conservative (16–20px) while section margins expand to 60–84px. This creates hierarchy through scale variation: tight within, generous between.

### Border Radius Scale

- **0px**: Primary radius for sharp, modern edges on buttons, cards, and primary elements
- **4px**: Subtle softness on form inputs and secondary interactive elements
- **8px**: Slight rounding on larger cards or container groups
- **28px**: Fully rounded for pill-shaped buttons and toggle switches
- **50%**: Circular elements (avatars, progress indicators)

## 6. Depth & Elevation

| Level | Treatment | Use |
|-------|-----------|-----|
| L0 (Ground) | No shadow, background `#0A0A0A` | Primary page background, baseline surfaces |
| L1 (Raised) | No shadow, background `#171717` or `#262626` | Cards, panels, subtle elevation |
| L2 (Floating) | `box-shadow: 0 8px 32px rgba(0, 0, 0, 0.5)` | Modals, dropdowns, hover states |
| L3 (Overlay) | `box-shadow: 0 16px 64px rgba(0, 0, 0, 0.7)` | Full-page overlays, dialogs |

**Shadow Philosophy**

Atomic's design minimizes shadow use, preferring solid color backgrounds and borders for elevation. When shadows are necessary (modals, overlays), they are soft, diffuse, and very dark to integrate seamlessly with the near-black background palette. Shadows create depth through multiplicity (multiple layers) rather than intensity (harsh contrast). The approach prioritizes color shifts and borders over shadow effects.

## 7. Do's and Don'ts

### Do

- Use `#FFFFFF` for all primary text on dark backgrounds; it ensures maximum contrast and readability.
- Maintain consistent font weight (500 for headers, 400 for body) to keep the system cohesive.
- Apply generous margins between major sections (60–84px) to create visual breathing room.
- Use `#FF6568` accent strategically—reserve it for primary CTAs and error states only.
- Build with a dark background (`#0A0A0A` or `#171717`) as the primary canvas.
- Align interactive elements to 56–80px height ranges for thumb-friendly touch targets on mobile.
- Use `#C5C5C5` for secondary information (labels, captions) to establish visual hierarchy without sacrificing legibility.
- Stack typography sizes in clear multiples; jump from 14px → 16px → 29px → 67px, not incremental steps.
- Implement responsive padding: 40px on desktop, 20px on tablet, 16px on mobile.

### Don't

- Never use pure white (`#FFFFFF`) as a background; it breaks the dark-mode aesthetic. Use `#0A0A0A` or `#171717` instead.
- Avoid multiple shadow layers or soft glows; they dilute the sharp, modern aesthetic.
- Don't mix font weights excessively; keep to 400 (regular) and 500 (medium).
- Never apply rounded corners (`border-radius > 4px`) to primary card containers; maintain sharp 0px radius for consistency.
- Avoid thin font weights (300 or below) at small sizes; use 400–500 minimum for legibility on dark backgrounds.
- Don't use more than two accent colors; `#FF6568` should dominate, with `#E40014` reserved for errors.
- Never center text in long-form content; left-align body text for scanning and readability.
- Avoid small font sizes below 14px for body text; maintain legibility with the 14.47px base.
- Don't add decorative elements or patterns; the system is ruthlessly minimalist.

## 8. Responsive Behavior

### Breakpoints

| Breakpoint | Width | Key Changes |
|-----------|-------|-------------|
| Mobile | ≤ 480px | Single column, 16px padding, 32px section margins, font sizes −2px |
| Tablet | 481px – 768px | 2-column grid, 20px padding, 52px section margins, font sizes −1px |
| Desktop | 769px – 1280px | 3–4 column grid, 40px padding, 72–84px section margins, full font sizes |
| Large | ≥ 1281px | Max-width constrained at 1280px, centered container, original spacing |

### Touch Targets

- Minimum interactive element height: `56px`
- Minimum interactive element width: `56px`
- Minimum tap/click area: `56px × 56px` (buttons, links, form inputs)
- Navigation link padding: `12px 16px` (vertical × horizontal) on touch devices
- Form input height: `56px` on mobile; `48px` on tablet/desktop

### Collapsing Strategy

- **Typography**: Decrease h1 from 67.51px → 48px on tablet → 36px on mobile. Decrease body from 14.47px → 14px on tablet, maintain on mobile.
- **Spacing**: Reduce all margins and padding by 50% on mobile (8px → 4px scale), by 25% on tablet.
- **Layout**: Convert multi-column layouts to single column below 768px. Stack hero sections vertically.
- **Navigation**: Move horizontal nav to hamburger menu below 768px. Use full-width dropdown on mobile.
- **Images**: Scale to 100% width on mobile; constrain to 80% on tablet within padded container.
- **Buttons**: Full-width on mobile; inline on tablet/desktop. Maintain minimum 56px height on mobile.

## 9. Agent Prompt Guide

### Quick Color Reference

- **Primary CTA**: Atomic Red (`#FF6568`) — use for main call-to-action buttons, accent highlights
- **Background**: Almost Black (`#0A0A0A`) — primary page background
- **Secondary Background**: Very Dark Gray (`#262626`) — subtle elevation, card backgrounds
- **Primary Text**: White (`#FFFFFF`) — all body text and primary headings
- **Secondary Text**: Light Gray (`#C5C5C5`) — labels, captions, tertiary information
- **Error State**: Error Red (`#E40014`) — form validation failures, destructive actions
- **Interactive Fill**: Ghost Fill (`rgba(197, 197, 197, 0.15)`) — secondary button backgrounds

### Iteration Guide

1. **Start with dark backgrounds**: Every surface should default to `#0A0A0A` or `#171717`. No light backgrounds unless explicitly required.

2. **Typography is consistent**: Use Inter font exclusively. Headers = 500 weight, body = 400 weight. No exceptions. Font sizes: display 67.51px, h1 28.94px, h2 29.85px, body 14.47px, small 13.22px.

3. **Spacing follows 8px scale**: All margins, padding, and gaps are multiples of 8px (8, 16, 24, 32, 40, 48, 56, 64, 72, 80, 88, 96, 104, 112, 120, 128, 140px). No arbitrary values.

4. **Accent color is rare**: `#FF6568` should appear in fewer than 5% of UI elements. Reserve it for primary CTAs, error highlights, and brand moments. Use `#FFFFFF` for 90% of interactive text.

5. **Buttons are minimal**: Primary buttons use transparent backgrounds with white text (`rgba(0,0,0,0)`, `#FFFFFF`, 0px radius). Secondary buttons use light-gray transparent fills (`rgba(197,197,197,0.15)`, white text, 28px radius). No shadows.

6. **Forms inherit the system**: Input backgrounds are `#262626` or semi-transparent gray. Text is `#FFFFFF`. Placeholder is `#C5C5C5`. Focus state: `#FF6568` border with subtle red glow (`0 0 0 3px rgba(255,101,104,0.2)`).

7. **Elevation comes from color shifts, not shadows**: Use darker or lighter backgrounds to imply depth. Avoid shadows except on modals (L2: `0 8px 32px rgba(0,0,0,0.5)`, L3: `0 16px 64px rgba(0,0,0,0.7)`).

8. **Responsive stacking is aggressive**: Below 768px, convert all multi-column layouts to single-column. Reduce padding by 50% on mobile, 25% on tablet. Maintain `56px` minimum touch targets.

9. **Links and navigation have no decoration by default**: Use plain white text on dark backgrounds. On hover, add `text-decoration: underline` or shift color to `#C5C5C5`. Active state: change to `#FF6568` or apply distinct styling.

10. **Border radius is sharp (0px) or rounded (28px)**: No in-between values like 8px for primary elements. Use 0px for cards and buttons, 28px for pill-shaped toggles and secondary buttons, 4px only for form inputs.