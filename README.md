# BUILD HOME — Premium Interior Architecture & Residential Design Website

A bespoke, production-ready digital showroom and sales demo engineered for **BUILD HOME**, an interior design practice discovered through Google. Built with **Next.js 16 (App Router)**, **TypeScript**, and **Tailwind CSS v4**.

---

## 🏛️ Project Overview

- **Brand**: BUILD HOME
- **Tagline**: *"Spaces That Feel Like Home."*
- **Creative Direction**: Refined, architectural, warm-minimalist aesthetic inspired by contemporary international monographs (*Kinfolk Gallery*, *Ark Journal*, *Architectural Digest*).
- **Core Conversion Goal**: Establish brand credibility, showcase editorial project photography, clarify services, and generate qualified enquiries via WhatsApp and consultation forms.

---

## 🎨 Design System & Palette

- **Warm Ivory (`#F5F2EC`)**: Primary foundational canvas
- **Soft Cream (`#EAE4DA`)**: Tonal card surfaces, dividers, and structural elevation
- **Charcoal (`#252522`)**: Authoritative typographic contrast & primary CTAs
- **Muted Olive (`#777966`)**: Editorial accents, architectural tags, and active states
- **Warm Taupe (`#B3A394`)**: Micro-borders and stone accents
- **Pure White (`#FFFFFF`)**: Crisp contrast elements and image frames

### Typography
- **Headlines / Display**: `Cormorant Garamond` (editorial serif)
- **Body & Navigation**: `Manrope` (contemporary humanist sans-serif)

---

## 🚀 Key Features & Architectural Sections

1. **Header & Navigation**: Sticky header with smooth backdrop blur on scroll, compact single-line desktop navigation, mobile drawer menu, and a prominent *"Start a Project"* CTA.
2. **Hero Section**: Viewport-stabilized hero with natural daylight photography, 11-word subtext, and clear exploration/consultation actions.
3. **Featured Projects**: Asymmetric editorial grid of 6 conceptual residences with material previews, category filtering, and an interactive **Project Detail Dossier Modal** with high-resolution photo galleries and specifications.
4. **Services Showcase**: Editorial split spread highlighting 6 capabilities (Complete Home Interiors, Living & Bedroom Design, Modular Kitchens, Space Planning, Material Selection, Renovation Styling) with live photo preview and direct service enquiry triggers.
5. **Studio Philosophy**: Narrative on architectural proportion and material honesty paired with a tactile Material Bar (Navona Travertine, Rift-Sawn Oak, Belgian Linen, Patinated Bronze).
6. **Process (01–04)**: Clear methodology (Discover, Design, Refine, Realize) detailing tangible milestone deliverables.
7. **Scope & Timeline Estimator**: Interactive calculator allowing homeowners to select residence typology (2BHK, 3BHK, 4BHK, Villa) and scope depth to view estimated timelines and deliverables.
8. **Trust, Commitments & FAQ**: Transparent architectural standards and expandable consultation FAQs (strictly avoiding fabricated statistics or fake testimonials).
9. **Contact & WhatsApp Conversion**: Complete enquiry form with validation, paired with a prominent Direct WhatsApp consultation desk card.
10. **Floating WhatsApp Desk**: Restrained, non-obtrusive floating desk button with active status pulse.
11. **Legal Modals**: Fully accessible Privacy Policy and Terms of Service dialogs ensuring no broken legal links.

---

## 🛠️ Tech Stack

- **Framework**: [Next.js 16 (App Router)](https://nextjs.org) with Turbopack
- **Language**: TypeScript
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com)
- **Icons**: [Lucide React](https://lucide.dev)
- **Fonts**: Next.js Google Fonts (`Cormorant_Garamond` & `Manrope`)
- **Package Manager**: pnpm

---

## 📦 Getting Started

### 1. Install Dependencies
```bash
pnpm install
```

### 2. Run the Development Server
```bash
pnpm dev
```
Open [http://localhost:3000](http://localhost:3000) with your browser.

### 3. Production Build
```bash
pnpm build
pnpm start
```

---

## ⚙️ Central Business Configuration

All editable studio details, phone numbers, WhatsApp links, and address notes are centralized in:
```
src/config/site.ts
```
To personalize for client onboarding, update `siteConfig.contact`:
- `whatsappNumber`: Business WhatsApp number for direct `wa.me` chat links.
- `phoneDisplay`: Formatted display phone number.
- `email`: Studio contact email.
- `studioHours` & `serviceArea`: Studio consultation details.

---

## 📄 License

Private concept presentation work prepared for **BUILD HOME**. All rights reserved.
