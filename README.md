# 🛒 FreshTrack — Online Grocery Inventory Management System

A lightweight, browser-based inventory management system designed for grocery stores. Built as a single HTML file — no installation, no backend, no dependencies. Just open and run.

> **Live Demo:** [your-username.github.io/grocery-inventory-system](https://your-username.github.io/grocery-inventory-system)

---

## 📋 Overview

FreshTrack addresses the core challenges faced by grocery retailers: manual stock tracking, poor supplier coordination, reactive restocking, and perishable goods wastage. The system provides real-time visibility into inventory levels, automated low-stock alerts, supplier management, and management reporting — all from a single HTML file.

---

## ✨ Features

### 📊 Dashboard
- Summary metrics: total products, in-stock count, low-stock count, out-of-stock count
- Visual bar chart of stock levels by category
- Real-time alerts panel (critical, warnings, informational)
- Top-moving products table for the current week

### 📦 Inventory Management
- Full product table with SKU, category, quantity, minimum threshold, expiry date, and status
- Colour-coded stock status badges: In Stock / Low Stock / Out of Stock
- Live search and filter by product name or category
- Add new products via a modal form (name, category, SKU, quantity, threshold, expiry, supplier)

### 🤝 Supplier Management
- Supplier directory with contact details, categories supplied, lead times, and delivery status
- Pending reorders tracker with estimated delivery dates
- Supplier status tracking: Active / Delayed

### 🔔 Alerts & Notifications
- Categorised alerts: Critical (out of stock, expiry), Warnings (low stock, delays), Info (order confirmations, audits)
- Alert counts at a glance
- Detailed alert descriptions with recommended actions

### 📈 Reports
Three tabbed report views:
- **Stock Summary** — total SKUs, stock value, average turnover, wastage rate, and per-category fill-rate bars
- **Wastage Log** — monthly log of disposed items with reason and value lost
- **Supplier Performance** — on-time delivery rates and average lead times per supplier

### 👥 User Management
- Role-based user table: Admin, Store Manager, Employee, Supplier
- User status tracking: Active / Pending
- Add new users via modal form

---

## 🚀 Getting Started

### Option 1 — Open locally
1. Download `index.html`
2. Double-click to open it in any modern browser
3. No installation required

### Option 2 — Host on GitHub Pages
1. Create a new GitHub repository (public)
2. Upload `index.html` to the root of the repository
3. Go to **Settings → Pages → Source → Deploy from branch → main**
4. Your system will be live at `https://your-username.github.io/your-repo-name`

---

## 🗂 Project Structure

```
grocery-inventory-system/
│
├── index.html       # Complete application (HTML + CSS + JS in one file)
└── README.md        # Project documentation
```

---

## 🖥 Pages & Navigation

| Page | Description |
|---|---|
| Dashboard | Overview metrics, category chart, alerts, top products |
| Inventory | Searchable product list, stock levels, expiry tracking |
| Suppliers | Supplier directory, lead times, pending reorders |
| Alerts | Categorised notifications and recommended actions |
| Reports | Stock summary, wastage log, supplier performance |
| Users | Role-based user management |

---

## 🛠 Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML5, CSS3, Vanilla JavaScript |
| Styling | CSS custom properties (variables), responsive grid |
| Charts | Pure CSS bar charts |
| Deployment | GitHub Pages (static hosting) |
| Dependencies | None — fully self-contained |

---

## 📐 System Design

This system was designed following the objectives outlined in the system proposal:

- **Automation** — stock status and alerts are computed automatically from quantity vs. threshold values
- **Real-time tracking** — inventory table reflects current stock levels with instant search filtering
- **Supplier integration** — supplier directory links products to suppliers with lead time tracking
- **Reporting** — management reports cover stock fill rates, wastage, and supplier KPIs
- **Role-based access** — user management supports Admin, Manager, Employee, and Supplier roles

---

## 🔮 Roadmap (Future Enhancements)

- [ ] Backend integration (Django / Laravel / Node.js)
- [ ] MySQL / PostgreSQL database connection
- [ ] Barcode scanner support
- [ ] Email and SMS alert notifications
- [ ] CSV/Excel export for reports
- [ ] Multi-branch support
- [ ] Purchase order generation
- [ ] Mobile app (PWA)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

## 🙋 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

*Built with ❤️ for efficient grocery retail management.*
