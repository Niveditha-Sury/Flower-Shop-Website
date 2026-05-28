# 🌸 Blossoms & Pots — Responsive E-Commerce Flower Shop

A premium, modern, and fully responsive e-commerce storefront for a boutique plant and flower shop. Designed with a vibrant, warm aesthetic featuring sleek micro-animations, cohesive color palettes, and fluid layouts for an outstanding desktop and mobile user experience.

![Blossoms & Pots Banner](https://github.com/user-attachments/assets/aa7fb611-0a14-4dd9-af88-2206ad7d2b74)

---

## ✨ Features

- **📱 Fully Responsive Navigation**:
  - Sticky header that anchors cleanly across all devices.
  - Automatically transitions to a mobile navigation drawer below `991px`.
  - Hamburger menu icon smoothly morphs into a close ("X") icon when opened.
  - **Auto-Close UX**: Dropdown menu automatically collapses when any navigation link is clicked, allowing seamless single-page scrolling.
- **🌸 Inviting Hero Section**: Captivating fullscreen introduction highlighting fresh, natural flowers with call-to-action buttons.
- **🎥 Interactive About Portal**: Engaging "Why Choose Us" row featuring handcrafted pot features and a background video container.
- **🚚 Trust Metrics Grid**: Showcases core customer-centric values like free delivery, return policies, special offers, and secure payment processing.
- **🛒 Polished Product Grid**:
  - Features 12 unique products with interactive hover overlay cards.
  - Image hover-zoom effects for premium shopping feel.
  - **Physical Sticker Badges**: Highly visible, modern discount tags (`-10%`, `-15%`) styled with deep drop-shadows and vibrant coral coloring.
- **⭐ Customer Testimonials**: Clean review cards with 5-star FontAwesome ratings and user-specific quotes.
- **✉️ Contact & Support**: Elegant messaging form accompanied by localized visuals.
- **🗺️ Comprehensive Footer**: Quick navigation access, extra account links, address locations, and trust badges.

---

## 🎨 Design System & Color Palette

The user interface uses a curated, cohesive warm HSL color palette tailored to nature and floral aesthetics:

| Role | Color | Hex Code | Usage |
| :--- | :--- | :--- | :--- |
| **Primary Base** | Light Peach / Pink | `#ffc1b4` | Header Background, Card Highlights, Form Containers |
| **Primary Accent** | Coral Red | `#f38c79` | Buttons, Brand Logo, Headings, Discount Stickers |
| **Secondary Accent**| Deep Teal | `#034c53` | Hover Highlight States, High-contrast Icons, Checked states |
| **Text Primary** | Forest Green | `#61836b` | Desktop Nav Links, Footer Links |
| **Background Secondary** | Dusty Rose | `#d4bebe` | Page Icons Section, Product Card Background |

---

## ⚡ Micro-Animations & UX Features

- **Icon Rotation & Scale**: Hovering over header icons or buttons gently scales them up and transitions the color scheme.
- **Menu Sliding Indicator**: Mobile navbar links slide slightly to the right (`padding-left: 2.5rem`) on hover with color-fills for intuitive tap feedback.
- **Product Zoom**: Product cards scale images to `1.1x` smoothly on hover.
- **Close Icon Transition**: Checkbox-controlled hamburger icon switches content unicode dynamically without bloated JavaScript libraries.

---

## 📂 Project Structure

```text
Flower-Shop-Website/
├── index.html            # Main markup page with modern layout & auto-close script
├── styles.css            # Base stylesheet containing the core design system & grid layout
├── mediaqueries.css      # Fluid breakpoints defining tablet and mobile viewport overrides
├── README.md             # Project documentation (this file)
└── images/               # Local assets directory (icons, product photos, cover image)
```

---

## 🚀 Run & Preview Locally

To launch a development server and view the responsive behaviors locally:

### Option A: Using NPM (Recommended)
1. Serve the folder using `npx http-server`:
   ```bash
   npx http-server -p 8000
   ```
2. Open your browser and navigate to **[http://localhost:8000](http://localhost:8000)**.

### Option B: Using Python
1. Serve using Python's built-in HTTP server:
   ```bash
   python -m http.server 8000
   ```
2. Open **[http://localhost:8000](http://localhost:8000)**.

### Option C: File System Direct Launch
- Simply double-click `index.html` inside the root folder to view it directly in your browser.

---

## 📏 Responsive Breakpoints Reference

The stylesheet separates styling concerns across 3 fluid layout tiers:

- **Desktop (`> 991px`)**: Full flex row header, standard spacing, hover transitions.
- **Tablet (`<= 991px`)**: Fixed `6rem` height header, hidden inline menu, collapsible navigation drawer, centered hamburger/logo layout.
- **Mobile (`<= 450px`)**: Compact `5.5rem` height header, reduced brand fonts (`1.8rem`), smaller icon gutters, and scaled headings to match portrait screens.

---

*Created by **Niveditha Sury** | All rights reserved.*
