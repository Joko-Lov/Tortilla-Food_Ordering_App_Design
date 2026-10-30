# 🌯 Tortilla — Food Ordering & Rewards App

A clean, mobile-first food ordering app built with an emphasis on seamless user flow, modern UI, and quick navigation. 

This project started as an end-to-end interactive prototype in **Figma**—mapping out every micro-interaction, sheet, and edge case—and was then brought to life in code with the assistance of **Claude**.

---

## 📱 What’s Inside

The app is built around the complete ordering lifecycle, from browsing dishes to checking out and earning loyalty points:

* **Discovery & Home:** Featured promotions (*"Fresh. Californian. Fearless."*), quick-filter food categories, and trending menu picks.
* **Full Menu & Search:** Categorized menus with real-time search, clear pricing, and fast item-level additions.
* **Dish Details & Nutrition:** High-res food views, item descriptions, and quick-glance macro breakdowns (Calories, Protein, Carbs).
* **Native-feel Share Sheets:** Built-in sharing modals for dishes via SMS, social channels, or direct link copying.
* **Cart & Order Summary:** Interactive quantity steppers, itemized breakdowns, calculated delivery fees, and quick checkout.
* **Loyalty & Rewards:** Dedicated rewards hub tracking loyalty points, redeemable vouchers (e.g., *Free Burrito*, *20% Off*), and recent redemption history.
* **User Profile & Account:** Saved delivery addresses, stored payment methods, recent order history, and account settings.

---

## 🛠️ The Workflow: Figma ➔ Code

1. **Design & Prototyping (Figma):**
   * Built modular components, nested auto-layouts, and consistent design tokens (warm terracotta accent palette, rounded corners, clean typographic hierarchy).
   * Wired full navigation noodle architecture—handling bottom tab switches, overlay modals (share dialogs), item detail drill-downs, and checkout paths.

2. **Implementation (Claude + Frontend):**
   * Translated Figma component frames into reusable, modular code components.
   * Preserved UI parity: precise spacing, border radii, layout flow, and bottom-sheet mechanics.
   * State management wired for cart quantity adjustments, running totals, and active tab states.

---

## 🚀 Getting Started

### Prerequisites

Make sure you have Node.js installed on your machine:
```bash
node -v # Recommended: Node 18+
