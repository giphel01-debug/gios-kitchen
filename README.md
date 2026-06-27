# 🫓 Gio's Kitchen — Food Ordering Web App

A mobile-first food ordering web application built from scratch, currently live and serving customers in Wayne, Nebraska.

🌐 **Live site:** [eatgioskitchen.com](https://eatgioskitchen.com)
📸 **Instagram:** [@eatgioskitchen](https://instagram.com/eatgioskitchen)

---

## 📋 Project Overview

Gio's Kitchen is a fully functional late-night food ordering platform built for a Caribbean food business operating Thursday–Saturday, 8PM–2AM in Wayne, Nebraska. The project covers end-to-end product development — from brand identity and UI design to deployment, order routing, and real-world customer use.

---

## ✨ Features

**Customer Side**
- Full menu with item variants and dynamic pricing
- Live shopping cart — add, remove, adjust quantities in real time
- Combo deal that auto-builds cart (2 Pastels + Nachos)
- Pickup time field and delivery request option
- Payment selection — Venmo, Cash App, or Cash on Pickup
- Unique order confirmation number (GK-XXXX format)
- Post-order confirmation screen with payment deep links
- Customer receipt sent to email automatically

**Owner Side**
- Password-protected owner panel
- Open/Closed toggle with real-time cross-device sync via JSONBin
- Per-item sold out toggles — mark individual items unavailable instantly
- Dynamic hours badge updates (green/red) based on kitchen status
- Closed banner visible to customers when kitchen is off

**Order Routing**
- SMS order sent directly to owner's phone with full order details
- Simultaneous email notification via EmailJS to owner's Gmail
- Customer receipt email sent automatically if customer provides email
- All orders include: name, contact, pickup time, delivery request, items, total, payment method, order number

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Fonts | Google Fonts (Bebas Neue, Inter) |
| Hosting | Netlify |
| Domain | Custom domain via Netlify DNS |
| Email | EmailJS (owner notification + customer receipt) |
| Status Sync | JSONBin.io (cross-device open/closed state) |
| Ordering | Native SMS (sms: protocol) |
| Payments | Venmo & Cash App deep links |

---

## 📱 How It Works

1. Customer visits **eatgioskitchen.com** on their phone
2. Browses the menu and adds items to cart
3. Selects payment method (Venmo, Cash App, or Cash)
4. Enters name, contact info, and pickup time
5. Hits "Place Order"
6. SMS fires to owner's phone with full order details
7. EmailJS simultaneously sends order email to owner's Gmail
8. Customer receives receipt email (if email provided)
9. Confirmation screen shows order number and payment info
10. Customer pays via Venmo/Cash App or cash on pickup

---

## 🍽️ Menu

| Item | Variants | Price |
|---|---|---|
| 🫓 Brazilian Pastel | Cheese | $2 |
| 🫓 Brazilian Pastel | Meat / Tuna | $3 |
| ✨ Golden Bites | Cheese | $2 |
| ✨ Golden Bites | Ham & Cheese | $3 |
| 🧀 Nachos | Chips + Meat + Cheese | $4 |
| 🍗 Island Chicken Leg | Caribbean herbs & spices | $3.50 |
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

## 🔐 Owner Panel

Access via `eatgioskitchen.com/#owner` with password authentication.

**Features:**
- Toggle kitchen Open/Closed (syncs across all devices via JSONBin)
- Mark individual menu items as Sold Out
- Status changes reflect instantly for all customers

---

## 📊 Business Context

| Detail | Info |
|---|---|
| Business type | Late-night food pop-up |
| Location | Wayne, Nebraska |
| Hours | Thu–Sat, 8PM–2AM |
| Cuisine | Caribbean (Curaçao-inspired) |
| Order method | SMS + email notification, in-person pickup |
| Payment | Venmo / Cash App / Cash |

---

## 🚀 Deployment

Deployed via **Netlify** with automatic HTTPS and custom domain DNS configuration.

```
Domain:     eatgioskitchen.com
Hosting:    Netlify
SSL:        Let's Encrypt (auto)
Email:      EmailJS
Sync:       JSONBin.io
```

---

## 🗺️ Roadmap

- [ ] Supabase integration for real-time order database
- [ ] Live order dashboard for owner
- [ ] Order history and nightly revenue tracking
- [ ] Customer order cancellation
- [ ] QR code flyer for campus marketing

---

## 👤 Author

**Gionny Phelipa**
MS Information Technology — Wayne State College
GitHub: [@giphel01-debug](https://github.com/giphel01-debug)
Email: giphel01@gmail.com

---

## 📌 Key Learnings

- Designing mobile-first UI without a CSS framework
- Implementing native SMS deep links for order routing
- Integrating EmailJS for dual email notifications (owner + customer)
- Cross-device state management using JSONBin REST API
- Third-party payment app deep links (Venmo, Cash App)
- Password-protected admin panel with localStorage persistence
- Deploying a production web app with custom domain and SSL
- Building a complete product from brand identity to live customer use
