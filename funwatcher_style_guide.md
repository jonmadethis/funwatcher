# 🎨 FunWatcher Style Guide

## 1. Brand Voice & Identity

- **Tone**: Fast, alert-driven, confident, sharp  
- **Audience**: Crypto traders, blockchain researchers, DeFi participants  
- **Brand Values**: Speed, accuracy, visibility, discovery  

---

## 2. Color Palette

| Name                | Hex        | Use Case |
|---------------------|------------|----------|
| FunWatcher Coral    | `#FF6B6B`  | Alerts, highlights, warnings  
| Sunset Peach        | `#FFB997`  | Badges, secondary accents  
| Deep Charcoal       | `#1C1C1C`  | Dark backgrounds  
| Neon Azure          | `#00BFFF`  | Links, hover states  
| Cloud Gray          | `#CFCFCF`  | Text and muted UI elements  
| Snek Gold           | `#FFD93D`  | Key stats, feature emphasis  
| Aloe Mint           | `#B2F2BB`  | Status indicators (Live)  
| Primary Gradient    | `linear-gradient(135deg, #00F5C0, #A950FF)` | Hero and button backgrounds  

---

## 3. Typography

- **Font**: Inter (via Google Fonts)
- **Font Weights**: 400, 500, 600, 700
- **Sizes**:
  - Body: `text-base`
  - Headings: 
    - H1: `text-6xl` (landing), `text-2xl` (subpages)
    - H2: `text-4xl`
    - H3: `text-2xl`
  - Labels: `text-xs` or `text-sm`
- **Line Height**: `leading-relaxed` or `leading-snug`

---

## 4. Layout Guidelines

- **Container Width**: `max-w-7xl mx-auto px-4`
- **Spacing**:
  - Section padding: `py-16` or `py-20`
  - Element spacing: `gap-4`, `space-y-4`, `mb-8`
- **Grid**:
  - Desktop: `grid-cols-3` or `grid-cols-4`
  - Mobile: Responsive-first layouts

---

## 5. UI Components

### 🔘 Buttons

- **Primary**:
  - `bg-funwatcher-primary text-funwatcher-charcoal`
  - Effects: `hover:scale-105`, `btn-glow`

- **Secondary**:
  - `border-2 border-peach text-peach`
  - Hover: `bg-peach text-charcoal`

### ✅ Status & Tags

- **Badges**:
  - `bg-gradient-to-r from-gold to-peach`
  - `text-charcoal px-2 py-1 rounded-full text-xs`

- **Live Dot**:
  - `w-2 h-2 rounded-full bg-mint animate-pulse`

---

## 6. Data Tables

- **Row Colors**: `bg-gray-900` / `bg-gray-800` alternating
- **Header**: `bg-gray-800 text-white`
- **Text**: `text-sm`, `text-left`, `px-4 py-3`
- **Hover**: `hover:bg-gray-700 transition`

---

## 7. Forms & Inputs

- **Input Fields**:
  - `bg-white/95`, `rounded-2xl`, `text-funwatcher-charcoal`
  - Focus Ring: `focus:ring-funwatcher-primary/30`

- **Live Icons**:
  - Green check / Red X shown via `#emailIcon` on input

---

## 8. Visual Effects

- **Floating Elements**: `animate-float`
- **Glow Pulse**: `pulse-glow`, `pulse-number`
- **Slide Animations**: `slide-up`, `slideInGlow`
- **Backdrop Glass**: `glass-effect` = `backdrop-filter: blur(10px)` + white overlay

---

## 9. Accessibility & Semantics

- Use `aria-label`, `alt`, and `role` attributes for accessibility
- Use semantic HTML5 (`<section>`, `<main>`, `<header>`, `<nav>`)
- All links should have `hover:underline` and `focus-visible:ring-*`

---

## 10. Tailwind Conventions

- Prefix all custom classes with `funwatcher-`
  - e.g. `text-funwatcher-coral`, `bg-funwatcher-mint`
- Extract repeatable styles into utility classes:
  - `.btn-primary`, `.stats-card`, `.metadata-tag`

---
