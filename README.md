# MANURR ESSENTIALS (manurrindia.com)

Welcome to the official repository for **MANURR ESSENTIALS** (`manurrindia.com`), a modern, high-converting quick-commerce and multi-category e-commerce web application inspired by Zepto, Blinkit, Amazon, and Flipkart.

![MANURR ESSENTIALS Banner](https://images.unsplash.com/photo-1553279768-865429fa0078?auto=format&fit=crop&w=1200&q=80)

---

## 🚀 Key Features

### 🛒 1. Customer Storefront
- **10-Minute Express Delivery Badge:** Interactive location selector for major Indian cities (Bengaluru, Mumbai, Delhi NCR, Hyderabad, Pune).
- **Real-Time Search & Filtering:** Instant keyword search and category filters (Groceries & Essentials, Electronics, Personal Care, Home & Kitchen, Snacks & Beverages).
- **Dynamic Pricing & Discounts:** INR (`₹`) currency support with MRP strikethroughs and % OFF badges.
- **Slide-Over Cart Drawer:** Free delivery progress bar, GST breakdown, and instant quantity steppers.

### 💳 2. Payment Gateway Integration
- Pre-configured and verified support for **Cashfree Payments** (Primary Live Gateway), **Razorpay**, **Direct Merchant UPI QR**, **PhonePe PG**, **PayU**, and **Stripe**.
- Secure checkout modal dynamically reflecting connected payment methods.

### 🔐 3. Admin Portal (`#admin`)
- **Product & Inventory Manager:** Add new products with custom pricing, delivery SLAs, emoji presets, and **direct local image file uploads (`Choose File`)** or image URLs.
- **Live Inventory Control:** Toggle in-stock status or remove SKUs in real time.
- **Payment Gateway Config:** Manage merchant keys, toggle test/sandbox vs. live environments, and copy webhook endpoints (`https://manurrindia.com/api/v1/payments/webhook`).
- **Live Orders Sync:** View customer orders placed from the storefront instantly.

---

## 🛠️ Tech Stack
- **Frontend:** Single-file architecture (`index.html`) combining HTML5, Tailwind CSS, JavaScript (ES6+), and Lucide icons.
- **State Management:** Persistent local storage engine (`localStorage`) so catalog updates, cart items, and gateway configs survive page reloads.

---

## 📦 Deployment Instructions (Cloudflare Pages / GitHub Pages)

1. Save the application code as **`index.html`** in your repository root.
2. **Cloudflare Pages:** 
   - Go to Cloudflare Dashboard → **Workers & Pages** → **Create application** → **Pages** → **Upload assets**.
   - Drag and drop your `index.html` file and click **Deploy Site**.
   - Link your custom domain `manurrindia.com` under **Custom domains**.
3. **GitHub Pages:**
   - Push `index.html` to your repository's `main` branch.
   - Go to **Settings** → **Pages** → Select `main` branch root folder and save.

---

## 📄 License
© 2026 MANURR ESSENTIALS (`manurrindia.com`). All rights reserved.


Because this project is built as a lightning-fast, self-contained static application, deploying it takes less than 2 minutes:
