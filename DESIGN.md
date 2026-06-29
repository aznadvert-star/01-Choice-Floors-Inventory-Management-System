---
name: Premium Wholesale Utility
colors:
  surface: '#f7fafb'
  surface-dim: '#d7dadb'
  surface-bright: '#f7fafb'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f1f4f5'
  surface-container: '#ebeeef'
  surface-container-high: '#e5e9ea'
  surface-container-highest: '#e0e3e4'
  on-surface: '#181c1d'
  on-surface-variant: '#42474c'
  inverse-surface: '#2d3132'
  inverse-on-surface: '#eef1f2'
  outline: '#72787d'
  outline-variant: '#c2c7cc'
  surface-tint: '#416277'
  primary: '#001b29'
  on-primary: '#ffffff'
  primary-container: '#0a3144'
  on-primary-container: '#7899b0'
  inverse-primary: '#a9cbe3'
  secondary: '#7b5800'
  on-secondary: '#ffffff'
  secondary-container: '#fdc656'
  on-secondary-container: '#735200'
  tertiary: '#001a31'
  on-tertiary: '#ffffff'
  tertiary-container: '#002f52'
  on-tertiary-container: '#4a99e5'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#c6e7ff'
  primary-fixed-dim: '#a9cbe3'
  on-primary-fixed: '#001e2d'
  on-primary-fixed-variant: '#284a5e'
  secondary-fixed: '#ffdea4'
  secondary-fixed-dim: '#f4be4e'
  on-secondary-fixed: '#261900'
  on-secondary-fixed-variant: '#5d4200'
  tertiary-fixed: '#d1e4ff'
  tertiary-fixed-dim: '#9dcaff'
  on-tertiary-fixed: '#001d35'
  on-tertiary-fixed-variant: '#00497c'
  background: '#f7fafb'
  on-background: '#181c1d'
  surface-variant: '#e0e3e4'
  vault-navy: '#0A3144'
  accent-gold: '#FFC857'
  action-blue: '#0170B9'
  surface-gray: '#F4F7F8'
  border-subtle: '#D1D9DD'
  text-main: '#1A2024'
typography:
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Hanken Grotesk
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Hanken Grotesk
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
    letterSpacing: 0.05em
  button-text:
    fontFamily: Hanken Grotesk
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.02em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  unit: 4px
  gutter: 16px
  margin-mobile: 16px
  margin-desktop: 32px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 24px
---

## Brand & Style

This design system is engineered for **Wholesale Vault**, a mobile-first extension designed to bridge the gap between heavy-duty inventory management and a premium b2b shopping experience. The brand personality is **Professional, Trustworthy, and Efficient**. It moves away from the consumer-facing warmth of Choice Floors towards a high-performance, utility-driven aesthetic.

The visual style is **Corporate / Modern** with a focus on high-information density. It utilizes a clean, structured layout with sharp functional triggers to ensure contractors and project managers can navigate thousands of SKUs with zero friction. The experience should feel like a high-end tool—robust, responsive, and authoritative.

Key design principles include:
- **Efficiency First**: Mobile interactions are optimized for one-handed use in warehouses or on job sites.
- **Visual Authority**: Use of deep architectural blues to instill a sense of permanence and reliability.
- **Tactile Precision**: Interactive elements have clear hit states and purposeful feedback, reflecting the physical nature of flooring and stairways.

## Colors

The palette is anchored by **Vault Navy**, a deep, sophisticated blue that represents the "Vault" and the brand's established heritage. **Accent Gold** is used surgically for high-priority calls to action, such as "Request Quick Quote," ensuring these buttons are the most visible elements on any screen.

**Color Usage Guidelines:**
- **Primary (Navy)**: Used for headers, primary navigation, and structural backgrounds to ground the mobile experience.
- **Secondary (Gold)**: Reserved exclusively for primary conversion points and critical status indicators.
- **Tertiary (Action Blue)**: Used for secondary functional actions like "Add to List" or "View Specs" to differentiate from the main quote path.
- **Neutral**: A cool-toned light gray background prevents screen fatigue and keeps the product grids looking crisp and modern.

## Typography

This design system employs **Hanken Grotesk** as the primary typeface. It is a sharp, contemporary neo-grotesque that offers exceptional legibility in dense data environments. Its geometry feels engineered and precise, aligning with the "Wholesale Vault" narrative.

For technical data—such as SKU numbers, dimensions, and inventory counts—the system uses **JetBrains Mono**. This monospaced font provides a clear visual distinction between descriptive text and hard data, reducing cognitive load during inventory management tasks.

**Typographic Principles:**
- **Contrast**: Bold weights are used for product titles to ensure they stand out in grid views.
- **Data Clarity**: Use the `label-code` style for all technical specifications to create a "spec-sheet" feel.
- **Vertical Rhythm**: Tight line-heights are maintained to maximize the amount of information visible on mobile screens without sacrificing readability.

## Layout & Spacing

The design system utilizes a **4px base grid** to ensure mathematical consistency across all components. For mobile, a **4-column fluid grid** is used with 16px margins, while desktop layouts transition to a **12-column fixed grid** (max-width 1280px).

**Layout Logic:**
- **Product Grids**: On mobile, use a 2-column "card" layout to balance image visibility with scroll efficiency.
- **Data Entry**: Forms use a single-column stack on mobile to ensure input fields are large enough for easy tapping.
- **Safe Areas**: Maintain a minimum 16px "safe zone" from the edges of the device to prevent accidental touches and ensure visual breathing room.

## Elevation & Depth

To maintain a "premium and structured" feel, depth is conveyed through **Tonal Layers** and **Low-contrast outlines** rather than heavy shadows. This keeps the interface feeling fast and digital-native.

- **Surface Levels**: The main background uses the Neutral shade. Cards and content containers use Pure White (#FFFFFF) to pop against the background.
- **Outlines**: Use 1px solid borders (#D1D9DD) for cards and input fields to define boundaries without adding visual weight.
- **Interactive Depth**: Only the primary "Request Quick Quote" button and active modals utilize a soft, diffused shadow (10% opacity Vault Navy) to indicate they are the highest level in the visual hierarchy.

## Shapes

The design system adopts a **Soft (0.25rem)** roundedness profile. This subtle rounding strikes a balance between the industrial, "hard" nature of construction materials and the modern, user-friendly nature of a high-end mobile app.

- **Standard Elements**: 4px radius (Buttons, Input Fields, Chips).
- **Large Containers**: 8px radius (Product Cards, Modals).
- **Search Bars**: 24px (Pill-shaped) to distinguish the search utility from static content.

## Components

### Buttons
- **Primary (Request Quick Quote)**: Solid Accent Gold background with Vault Navy text. Always full-width on mobile.
- **Secondary**: Vault Navy background with White text. Used for "Add to Project."
- **Tertiary/Ghost**: 1px Vault Navy border with Vault Navy text. Used for "View Details" or "Cancel."

### Data Entry & Search
- **Searchable Grids**: Features a sticky search bar at the top with a "Filter" icon. Search results update in real-time.
- **Input Fields**: Labeled clearly with Hanken Grotesk Medium. Use JetBrains Mono for numeric inputs (dimensions, quantity).
- **Image Upload**: A dedicated "Vault Drop" component. A dashed-border container with a large "+" icon and "Upload Job-site Photo" label.

### Product Cards
- **Grid Card**: Top-half image (aspect ratio 4:3), bottom-half text containing Product Name, SKU (monospaced), and a prominent "Quick Quote" button.
- **List View**: Horizontal layout for dense inventory lists, prioritizing SKU and Stock Status over large imagery.

### Chips & Status
- **Stock Status**: "In Stock" (Green tint), "Low Stock" (Gold tint), "Special Order" (Blue tint).
- **Material Tags**: Small, neutral-colored chips to identify "Hardwood," "Laminate," "Vinyl," etc.

### Form Inputs
- **Numeric Steppers**: Large "+" and "-" buttons flanking the quantity input for easy adjustment on-site.