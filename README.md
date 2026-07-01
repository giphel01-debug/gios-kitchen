# 🫓 Gio's Kitchen — Food Ordering Web App

A mobile-first food ordering web application built from scratch and deployed to production.

🌐 **Live site:** [eatgioskitchen.com](https://eatgioskitchen.com)
📸 **Instagram:** [@eatgioskitchen](https://instagram.com/eatgioskitchen)

---

## 📋 Project Overview

Gio's Kitchen is a fully functional food ordering platform built end-to-end — from UI design and branding to backend integration, order routing, and a custom owner management dashboard. The app is live and currently serving real customers.

---

## ✨ Features

**Customer Side**
- Mobile-first responsive design
- Dynamic menu with item variants and real-time pricing
- Live shopping cart with quantity controls
- Item customization (fillings, toppings, dips, styles)
- Tip selection and special order notes
- Multiple payment options with deep-link integration
- Unique order confirmation numbers
- Automated customer email receipts

**Owner Dashboard**
- Password-protected login with SHA-256 hashing
- Real-time kitchen status controls synced across all devices
- Per-item availability management
- Live order queue with status tracking
- Nightly revenue stats
- Print order tickets

**Order System**
- SMS order routing to owner's phone
- Dual email notifications via EmailJS (owner + customer)
- Real-time order storage in PostgreSQL database
- Cross-device status sync via REST API

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Database | Supabase (PostgreSQL) |
| Email | EmailJS |
| Hosting | Netlify |
| Domain | Custom domain with SSL |
| State Sync | JSONBin REST API |
| Payments | Third-party payment app integration |
| Version Control | Git / GitHub |

---

## 🚀 Deployment

- Hosted on **Netlify** with automatic HTTPS
- Custom domain with DNS configuration
- Database hosted on **Supabase** (cloud PostgreSQL)
- Zero-downtime deploys via drag-and-drop or GitHub

---

## 📌 Key Learnings

- Mobile-first UI design without CSS frameworks
- Native SMS deep links for order routing
- Dual EmailJS integration for automated notifications
- PostgreSQL database design and REST API integration
- Cross-device state management
- SHA-256 password hashing in the browser
- End-to-end product development from concept to production

---

## 👤 Author

**Gionny Phelipa**
MS Information Technology — Wayne State College
GitHub: [@giphel01-debug](https://github.com/giphel01-debug)
Email: eatgioskitchen@gmail.com

