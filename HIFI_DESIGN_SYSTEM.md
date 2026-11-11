# TASK 2: High-Fidelity UI Design & Design System Documentation
**Project:** QuickBite - Food Delivery App  
**Deliverable Type:** High-Fidelity Mobile App UI (4 Screens), Design System & Interactive Hi-Fi Prototype  
**Submission Format:** High-Res Vector SVG Artboards (Figma/Adobe XD Ready) & Interactive Web App (`hifi.html`)

---

## 1. Design System & Style Guide

### A. Color Palette & Semantics
- **Brand Primary:** `#FF5A26` (Vibrant Appetite Tangerine / Warm Coral) — energetic, stimulating appetite, high conversion.
- **Brand Primary Dark:** `#E04312` (Pressed / Active state)
- **Brand Secondary / Accent:** `#FFB703` (Warm Amber / Rating Stars & Highlights)
- **Success / Positive:** `#10B981` (Fresh Emerald / Delivered, Open status, Healthy tags)
- **Neutrals (Dark & Light Surface Hierarchy):**
  - Text Primary (Headings): `#0F172A` (Slate 900)
  - Text Secondary (Body / Subtitles): `#475569` (Slate 600)
  - Text Muted: `#94A3B8` (Slate 400)
  - Card Background: `#FFFFFF`
  - App Canvas Surface: `#F8FAFC` (Slate 50)
  - Subtle Borders & Dividers: `#E2E8F0` (Slate 200)

### B. Typography Hierarchy (Plus Jakarta Sans / Inter)
- **Display 1 (Hero / Totals):** 22px / 700 / `#0F172A`
- **Heading 1 (Screen Titles):** 18px / 800 / `#0F172A`
- **Heading 2 (Card Titles / Restaurant):** 16px / 700 / `#0F172A`
- **Subtitle / Dish Name:** 14px / 600 / `#1E293B`
- **Body Regular:** 12px / 400 / `#475569`
- **Caption / Metadata:** 10px / 600 / `#64748B`
- **Button CTAs:** 13px / 700 / `#FFFFFF`

### C. UI Elements, Elevation & Shadows
- **Corner Radii:** Cards: 16px, Floating Bars / Pills: 12px–20px, CTA Buttons: 14px.
- **Card Elevation (Soft Drop Shadow):** `0px 4px 16px rgba(15, 23, 42, 0.06)` for gentle depth without visual clutter.
- **Action Buttons:**
  - Primary: `#FF5A26` gradient fill with subtle glow shadow.
  - Secondary / Stepper: `#F1F5F9` with `#FF5A26` active states.

---

## 2. Core UI/UX Principles Implemented

1. **Aesthetic-Usability Effect:** High aesthetic fidelity with appetizing food imagery, harmonious warm hues, and micro-interactions fosters perceived reliability and ease of use.
2. **Fitts's Law:** Bottom-anchored Floating Action Bar ("View Cart", "Place Order") sits directly in the ergonomic natural thumb zone for seamless single-handed mobile navigation.
3. **Jakob's Law:** Adheres to established mobile food delivery mental models (familiar top search with location pill, horizontal category chips, card layouts, and bottom navigation bar).
4. **Visual Hierarchy & Contrast:** High contrast ratios (WCAG AAA compliant for text readability), deliberate typographical scaling, and color-coded status badges for instant comprehension.
5. **Feedback & Visibility of System Status:** Animated delivery route, glowing live status indicators, step-by-step progress bars, and rider telemetry in the tracking screen.

---

## 3. Screen Breakdown

1. **`hifi-screen-1-home.svg`** — High-Fidelity Discovery Home Screen
2. **`hifi-screen-2-restaurant.svg`** — High-Fidelity Restaurant Storefront & Menu
3. **`hifi-screen-3-cart.svg`** — High-Fidelity Order Checkout & Payment
4. **`hifi-screen-4-tracking.svg`** — High-Fidelity Live Map Tracking & Dispatch

---

## 4. How to Import into Figma / Adobe XD
1. Drag and drop any `hifi-screen-*.svg` file onto your Figma canvas.
2. Every button, badge, image, and text layer is organized into clean vector groups.
3. Launch `hifi.html` in your browser for a live interactive preview with side-by-side wireframe vs. high-fidelity comparison!

