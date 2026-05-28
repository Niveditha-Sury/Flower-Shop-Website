
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
=======
# 🌸 Blossoms & Pots: Responsive E-Commerce Flower Shop

<img width="1318" height="573" alt="repo1" src="https://github.com/user-attachments/assets/aa7fb611-0a14-4dd9-af88-2206ad7d2b74" />

## 🌟 Project Overview

**Blossoms & Pots** is a modern, feature-rich **e-commerce website** dedicated to selling fresh flowers and unique flower pots. Built with a **mobile-first** approach, the site ensures a **seamless and intuitive browsing experience** across all devices, from desktops to smartphones. The project aims to provide an attractive and efficient digital storefront, blending appealing design with essential e-commerce functionality.

***

## ✨ Key Features

This website is structured into logical, user-friendly sections to maximize conversion and customer engagement:

* **Responsive Header & Navigation:** A **sticky navigation bar** that features a logo, essential links, and interactive icons (Wishlist, Cart, User). On smaller screens, the menu elegantly collapses into a **collapsible dropdown menu** for optimal space utilization.
* **Home/Hero Section:** An inviting landing area featuring a **captivating background image**, a compelling headline, and a clear **Call-to-Action (CTA) button** to guide users to products.
* **About Section:** Builds customer trust by providing detailed information about the shop, including a **video showcase** and a convincing explanation of the shop's value proposition.
* **Icon Section (Key Services):** Highlights essential customer assurances and services, such as: **Free Delivery**, **10-Day Return Policy**, **Exclusive Offers & Gifts**, and **Secure Payment Options**.
* **Products Section:** Showcases the variety of flower pots with clear **discounts**, high-quality images, and interactive controls (Add to Cart, Like, Share).
* **Review Section (Social Proof):** Features authentic **customer testimonials** complete with star ratings to provide social proof and build confidence in product quality.
* **Contact Section:** Provides a straightforward **contact form** for user inquiries, paired with a visually relevant image.
* **Footer:** A comprehensive closing section containing **Quick Links**, **Extra Resources**, **Location information**, **Contact Details**, and visual indicators for **Payment Methods**.

***

## 💻 Technologies Used

| Technology | Purpose |
| :--- | :--- |
| **HTML5** | Provides the core semantic structure and content foundation of the entire website. |
| **CSS** | Handles all aspects of styling, layout, and visual presentation, including advanced **responsive design** via media queries. |
| **Font Awesome** | Used for scalable, high-quality vector icons across the navigation, product cards, and feature sections. |

***

## 🛠️ Getting Started

Follow these steps to set up and run the project locally.

### Prerequisites

You only need a modern web browser installed on your system.

### Installation

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourUsername/flower-shop-ecommerce.git](https://github.com/YourUsername/flower-shop-ecommerce.git)
    ```
    *(Replace the URL above with your actual repository link)*

2.  **Navigate to the project directory:**
    ```bash
    cd flower-shop-ecommerce
    ```

3.  **Open the website:**
    Simply open the main `index.html` file in your preferred web browser.

    ```bash
    # Example commands (may vary by OS)
    open index.html 
    ```

***

## 🤝 Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1.  Fork the Project.
2.  Create your Feature Branch (`git checkout -b feature/NewFeature`).
3.  Commit your Changes (`git commit -m 'feat: Add amazing new feature'`).
4.  Push to the Branch (`git push origin feature/NewFeature`).
5.  Open a Pull Request.

***

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

***



>>>>>>> 3f0cd1d170108548e8f10cb35a67ee4934bdb148
