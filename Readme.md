# Mintlify Website Clone (Desktop Only)

A desktop-only clone of the Mintlify homepage built using pure HTML and CSS.

This project focuses on accurately recreating the layout, typography, spacing system, and visual hierarchy of the original Mintlify website without using JavaScript, TailwindCSS, responsiveness, or animations.

---

## 🚀 Project Overview

This clone replicates the major sections of the Mintlify landing page while maintaining:

- Clean layout structure
- Proper spacing and alignment
- Accurate color system
- Typography consistency
- Component-based section design

The implementation strictly follows the constraint of desktop view only.

---

## 🧱 Sections Recreated

The following sections were recreated from the original Mintlify website:

1. **Sticky Navigation Bar**
   - Logo
   - Navigation links
   - Contact Sales button
   - Start for Free button

2. **Hero Section**
   - Update notification banner
   - Main headline
   - Subtitle
   - Email input field with CTA button
   - Hero product screenshot

3. **Companies Section**
   - Company logos row

4. **Features Section**
   - Feature cards layout
   - Big feature highlight card
   - Label + heading + description structure

5. **Enterprise Section**
   - Enterprise feature descriptions
   - Enterprise highlight banner
   - Statistics section
   - Company logos

6. **Customers Section**
   - Customer testimonial cards
   - Grid layout
   - Navigation buttons

7. **Call-To-Action Section**
   - Dual CTA split layout
   - Icon + heading + description
   - Divider structure

8. **Footer**
   - Multi-column links
   - Social media icons
   - Security badge
   - Status indicator
   - Theme toggle buttons
   - Copyright section

---

## 🎨 Fonts Used

### Primary Font:
**Inter (Variable Font)**

Loaded using `@font-face`:

```css
@font-face {
  font-family: "Inter";
  src: url(/Assets/fonts/Inter-VariableFont_slnt,wght.ttf);
}
```

Font fallback:
```css
"Inter", sans-serif;
```

---

## 🎨 Color Palette

The project uses CSS custom properties (`:root`) for structured theming and easy maintenance.

### Primary Colors
- **Primary Dark (Woodsmoke):** `#08090b`
- **Secondary (White):** `#ffffff`

### Accent Colors
- **Primary Green (Mountain Meadow):** `#18e299`
- **Riptide Green:** `#3f8a62`

### Background Colors
- **Light Background:** `#ffffff`
- **Section Background (Light Gray):** `#f8f8f8`
- **Border Color:** `rgba(0, 0, 0, 0.08)`

### Text Colors
- **Main Text:** `#08090b`
- **Muted Text:** `rgba(62, 61, 61, 0.9)`
- **Footer Muted Text:** `#666`

All colors are managed using CSS variables inside the `:root` selector to ensure consistency and scalability across the entire layout.

---

## 🛠 Technologies Used

- HTML5
- CSS3
- CSS Grid
- Flexbox
- CSS Variables
- Custom Font Loading via `@font-face`

---

## 📌 Constraints Followed

- Desktop-only layout
- No responsiveness implemented
- No JavaScript used
- No TailwindCSS
- No animations
- Images and assets similar to the original design
- Focused on structural and visual accuracy

---


## 🎯 Learning Outcomes

Through this project:

- Strengthened CSS layout fundamentals (Flexbox & Grid)
- Practiced recreating a real SaaS landing page UI
- Improved spacing, alignment, and hierarchy understanding
- Implemented a structured color system using CSS variables
- Learned production-style section-based design

---

## ⚠ Disclaimer

This project is created strictly for educational purposes.  
All design credits belong to the original Mintlify website.

---
