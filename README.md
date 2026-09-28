# ⚡ Electronic World - Next-Gen E-Commerce Web Application

**Electronic World** is a modern, realistic, full-featured web application for electronic items built with HTML5, CSS3, JavaScript (ES6 Modules), Tailwind CSS, and powered by a live **Supabase PostgreSQL** backend.

---

## 🌟 Key Features

### 🛒 Storefront & Shopping Experience
- **Realistic Modern Design**: Futuristic glassmorphism UI, gradient neon accents, crisp typography, and responsive layouts across mobile, tablet, and desktop.
- **Smooth Animations**: Floating product showcases, card hover elevation & glow effects, slide-over cart drawer transitions, modal popups, and celebration confetti.
- **Dynamic Search & Filtering**: Real-time keyword search, category navigation pills (*Smartphones, Laptops, Audio, Smartwatches, Gaming, Accessories*), interactive price slider ($50 - $4000), and custom sorting options.
- **Product Specs Detail Modal**: Full technical specifications breakdown, stock availability, star ratings, and quick view buttons.
- **Interactive Shopping Cart**: Slide-over drawer with item quantity controls (+/-), automatic subtotal, tax & free shipping calculations.
- **Seamless Checkout Flow**: Complete customer information modal, payment method choice (*Credit Card, PayPal, Apple Pay, Cash on Delivery*), instant order placement, and live receipt generation.
- **Dark & Light Mode**: One-click theme toggle storing user preference.

---

### 🔐 Password-Protected Admin Panel
- **Security Access**: Locked with administrator password authentication (Default Password: `admin123`).
- **Overview Dashboard**: Live statistics counter for Total Products, Customer Orders, Revenue, and Supabase REST status.
- **Product Management (CRUD)**:
  - Add new electronic items with custom title, category, price, stock, image URL, and description.
  - Edit existing product details inline.
  - Delete products from the live catalog.
  - **One-Click Supabase DB Seed**: Instantly seed default real electronic items (*iPhone 16 Pro Max, MacBook Pro M3 Max, Sony WH-1000XM5, Galaxy S24 Ultra, PS5 Slim, Apple Watch Ultra 2*) directly into Supabase.
- **Orders Management**: View customer orders, shipping details, total amount, ordered item lists, and update order status (*Pending, Processing, Shipped, Delivered*).
- **Supabase SQL Generator**: Pre-loaded SQL script and one-click copy button to create tables in the Supabase Dashboard.

---

## 🛠️ Supabase Backend Credentials

Connected to Supabase Project:
- **Project Reference**: `ogftgxlccnjwbcwyxovl`
- **Supabase URL**: `https://ogftgxlccnjwbcwyxovl.supabase.co`
- **Anon Key**: Provided in `supabase-client.js`
- **Publishable Key**: `sb_publishable_KzoA1ctxmBZGr9SOukV3kQ_NtLEfxsR`

---

## 🚀 How to Run Locally

### Option 1: Python Local Server
Run the following command in your terminal:
```bash
python -m http.server 8080
```
Then open `http://localhost:8080` in your web browser.

### Option 2: Live Server (VS Code Extension)
Right click `index.html` in VS Code and click **Open with Live Server**.

---

## 📂 File Structure

```
the boys/
├── index.html          # Main HTML5 document structure
├── styles.css          # Custom glassmorphism, CSS keyframe animations, dark/light theme
├── app.js              # Storefront state, cart, wishlist, product search & checkout logic
├── admin.js            # Password auth, Admin dashboard, product CRUD & order tracking
├── supabase-client.js  # Supabase client SDK initialization & database REST helper APIs
├── schema.sql          # PostgreSQL schema script for Supabase SQL Editor
└── README.md           # Documentation
```
