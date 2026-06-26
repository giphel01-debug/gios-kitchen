# 🫓 Gio's Kitchen — Food Ordering Web App

A mobile-first food ordering web application built from scratch, currently live and serving customers in Wayne, Nebraska.

🌐 **Live site:** [eatgioskitchen.com](https://eatgioskitchen.com)

---

## 📋 Project Overview

Gio's Kitchen is a fully functional food ordering platform designed for a late-night Caribbean food business operating Thursday–Saturday, 8PM–2AM. The project covers end-to-end product development — from brand identity and UI design to deployment and real-world customer use.

---

## ✨ Features

- **Full menu with item variants** — customers select fillings/styles per item
- **Live shopping cart** — add, remove, adjust quantities in real time
- **SMS order integration** — order details sent directly to the kitchen via text
- **Payment selection** — Venmo, Cash App, or Cash on Pickup
- **Confirmation screen** — displays payment usernames and deep-links to payment apps
- **Mobile-first design** — optimized for phone screens
- **Custom domain** — deployed at eatgioskitchen.com via Netlify

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Fonts | Google Fonts (Bebas Neue, Inter) |
| Hosting | Netlify |
| Domain | Custom domain via Netlify DNS |
| Ordering | Native SMS (sms: protocol) |
| Payments | Venmo & Cash App deep links |

---

## 📱 How It Works

1. Customer visits **eatgioskitchen.com** on their phone
2. Browses the menu and adds items to cart
3. Selects a payment method (Venmo, Cash App, or Cash)
4. Enters their name and places order
5. Their texting app opens with the full order pre-filled
6. Confirmation screen shows payment info and links
7. Kitchen receives the text and prepares the order

---

## 🎨 Design Decisions

- **Dark theme** — optimized for late-night mobile use
- **Caribbean color palette** — blue, green, and gold to reflect the brand's Curaçao roots
- **Bebas Neue + Inter** — bold display font paired with clean body text
- **No frameworks** — pure HTML/CSS/JS for fast load times and zero dependencies
- **No backend needed** — SMS protocol handles order delivery natively

---

## 📊 Business Context

| Detail | Info |
|---|---|
| Business type | Late-night food pop-up |
| Location | Wayne, Nebraska |
| Hours | Thu–Sat, 8PM–2AM |
| Menu | Brazilian Pastels, Golden Bites, Nachos |
| Order method | SMS + in-person pickup |
| Payment | Venmo / Cash App / Cash |

---

## 🚀 Deployment

Deployed via **Netlify** with automatic HTTPS and custom domain DNS configuration.

```
Domain:     eatgioskitchen.com
Hosting:    Netlify
SSL:        Let's Encrypt (auto)
```

---

## 👤 Author

**Gionny Phelipa**
MS Information Technology — Wayne State College
GitHub: [@giphel01-debug](https://github.com/giphel01-debug)

---

## 📌 Key Learnings

- Designing mobile-first UI without a CSS framework
- Implementing native SMS deep links for order routing
- Integrating third-party payment app deep links (Venmo, Cash App)
- Deploying a production web app with custom domain and SSL
- Building a complete product from brand identity to live deployment
