# 🫓 Gio's Kitchen — Food Ordering Web App

A mobile-first food ordering web application built from scratch, currently live and serving customers in Wayne, Nebraska.

🌐 **Live site:** [eatgioskitchen.com](https://eatgioskitchen.com)
📸 **Instagram:** [@eatgioskitchen](https://instagram.com/eatgioskitchen)

---

## 📋 Project Overview

Gio's Kitchen is a fully functional late-night food ordering platform built for a Caribbean food business operating Thursday–Saturday, 8PM–2AM in Wayne, Nebraska. The project covers end-to-end product development — from brand identity and UI design to deployment, order routing, real-world customer use, and a full owner management dashboard.

---

## ✨ Features

**Customer Side**
- Full menu with item variants and dynamic pricing
- Live shopping cart — add, remove, adjust quantities in real time
- Combo deal that auto-builds cart (2 Cheese Pastels + Nachos)
- Nachos customization — choose chips (Doritos or Tortilla) and toppings (Pico de Gallo, Pepper, Sour Cream)
- Island Chicken Leg — choose style (Plain or With Homemade Bread) and dip (Ranch, Sweet Chili, BBQ)
- Tip selection ($1, $2, $3, $5 or custom amount)
- Special requests / order notes field
- Pickup time field and delivery request option
- Payment selection — Venmo, Cash App, or Cash on Pickup
- Unique order confirmation number (GK-XXXX format)
- Post-order confirmation screen with payment deep links
- Customer receipt sent to email automatically

**Owner Dashboard (dashboard.html)**
- Password-protected login with SHA-256 hashing
- Kitchen Open/Closed toggle (syncs across all devices via JSONBin)
- Taking Orders toggle (pause/resume orders instantly)
- Under Construction banner toggle
- Per-item sold out toggles with low stock warning
- Tonight's stats — Total Orders, Pending, Ready, Revenue
- Full order management — view, filter, mark Ready/Completed
- Last refresh time indicator
- Print order ticket button
- Auto-refreshes every 30 seconds

**Order Routing**
- SMS order sent directly to owner's phone with full order details
- Simultaneous email notification via EmailJS to owner's Gmail
- Customer receipt email sent automatically if customer provides email
- All orders saved to Supabase database in real time
- Orders include: name, contact, pickup time, delivery request, items, tip, notes, total, payment method, order number

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Fonts | Google Fonts (Bebas Neue, Inter) |
| Hosting | Netlify (eatgioskitchen.com) |
| Backup | GitHub Pages |
| Domain | Custom domain via Netlify DNS |
| Database | Supabase (PostgreSQL) |
| Email | EmailJS (owner notification + customer receipt) |
| Status Sync | JSONBin.io (cross-device open/closed state) |
| Ordering | Native SMS (sms: protocol) |
| Payments | Venmo & Cash App deep links |

---

## 📱 How It Works

1. Customer visits **eatgioskitchen.com** on their phone
2. Browses the menu and adds items to cart with customizations
3. Selects payment method and optionally adds a tip
4. Enters name, contact info, pickup time, and any notes
5. Hits "Place Order"
6. SMS fires to owner's phone with full order details
7. EmailJS simultaneously sends order email to owner's Gmail
8. Order saved to Supabase database instantly
9. Customer receives receipt email (if email provided)
10. Confirmation screen shows order number and payment info
11. Owner manages orders via dashboard.html

---

## 🍽️ Menu

| Item | Variants | Price |
|---|---|---|
| 🫓 Brazilian Pastel | Cheese | $2 |
| 🫓 Brazilian Pastel | Meat / Chicken | $3 |
| ✨ Golden Bites | Cheese | $2 |
| ✨ Golden Bites | Ham & Cheese | $3 |
| 🧀 Nachos | Chips + Meat + Cheese (base) | $4 |
| 🧀 Nachos | With 2+ toppings | $5 |
| 🍗 Island Chicken Leg | Plain | $3.50 |
| 🍗 Island Chicken Leg | With Homemade Bread | $5 |
| 🌙 Late Night Combo | 2 Cheese Pastels + Nachos | $7 |

---

## 🎨 Design Decisions

- **Dark theme** — optimized for late-night mobile use
- **Caribbean color palette** — blue, green, and gold reflecting Curaçao roots
- **Bebas Neue + Inter** — bold display font paired with clean body text
- **Mobile-first layout** — designed for phone screens, works on desktop too
- **No frameworks** — pure HTML/CSS/JS for fast load times and zero dependencies
- **No traditional backend** — SMS + EmailJS handle order delivery natively

---

## 🔐 Owner Dashboard

Access via `giphel01-debug.github.io/gios-kitchen/dashboard.html`

Password-protected with SHA-256 hashed credentials.

**Features:**
- Toggle kitchen Open/Closed (syncs across all devices via JSONBin)
- Toggle Taking Orders on/off
- Toggle Under Construction banner
- Mark individual menu items as Sold Out or Running Low
- View and manage all orders with status tracking
- Track nightly revenue

---

## 📊 Business Context

| Detail | Info |
|---|---|
| Business type | Late-night food pop-up |
| Location | Wayne, Nebraska |
| Hours | Thu–Sat, 8PM–2AM |
| Cuisine | Caribbean (Curaçao-inspired) |
| Launch date | August 2026 (Fall semester) |
| Order method | SMS + email notification, in-person pickup |
| Payment | Venmo / Cash App / Cash |

---

## 🚀 Deployment

```
Domain:        eatgioskitchen.com
Hosting:       Netlify
Backup:        GitHub Pages (giphel01-debug.github.io/gios-kitchen)
SSL:           Let's Encrypt (auto)
Database:      Supabase (PostgreSQL)
Email:         EmailJS
Status Sync:   JSONBin.io
```

---

## 🗺️ Roadmap

- [ ] Cloudflare email forwarding (info@eatgioskitchen.com)
- [ ] Google Business Profile verification
- [ ] QR code flyer for campus marketing
- [ ] Supabase real-time order updates
- [ ] Customer order tracking page
- [ ] Weekly revenue charts

---

## 👤 Author

**Gionny Phelipa**
MS Information Technology — Wayne State College
GitHub: [@giphel01-debug](https://github.com/giphel01-debug)
Email: eatgioskitchen@gmail.com

---

## 📌 Key Learnings

- Designing mobile-first UI without a CSS framework
- Implementing native SMS deep links for order routing
- Integrating EmailJS for dual email notifications (owner + customer)
- Real-time order database with Supabase (PostgreSQL)
- Cross-device state management using JSONBin REST API
- Third-party payment app deep links (Venmo, Cash App)
- Password-protected admin dashboard with SHA-256 hashing
- Deploying a production web app with custom domain and SSL
- Building a complete product from brand identity to live customer use
