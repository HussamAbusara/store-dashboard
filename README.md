<div align="center">

# 🏪 Store Dashboard

**A full-stack store management system with POS, inventory, supplier management, AI integration, and bilingual support.**

![Status](https://img.shields.io/badge/Status-In%20Development-orange?style=flat-square)
![Stack](https://img.shields.io/badge/Stack-React%20%2B%20Node.js%20%2B%20PostgreSQL-blue?style=flat-square)
![i18n](https://img.shields.io/badge/i18n-Arabic%20%2F%20English-green?style=flat-square)
![License](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-red?style=flat-square)

</div>

---

## 📌 Overview

**Store Dashboard** is a comprehensive store management platform built for small to medium-sized businesses. It combines a modern POS system, product & supplier management, AI-powered insights, barcode scanning, and a customer-facing storefront — all within a bilingual (Arabic/English) interface.

> ⚠️ This project is currently **under active development**. Some features may be incomplete or subject to change.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🖥️ **Point of Sale (POS)** | Fast checkout with barcode scanning support |
| 📦 **Product Management** | Add, edit, and track inventory levels and pricing |
| 🏢 **Supplier Management** | Manage supplier contacts, orders, and history |
| 🤖 **AI Integration** | Smart insights and assistance powered by AI |
| 🌐 **Storefront** | Flexible customer-facing online store *(in development)* |
| 🔠 **Bilingual (AR/EN)** | Full Arabic & English support with RTL layout |
| 📊 **Dashboard** | Real-time overview of sales, stock, and performance |
| 🔐 **Authentication** | Secure login and multi-store access control |

---

## 🛠️ Tech Stack

### Frontend
- **React** + **TypeScript** (Vite)
- **i18next** — Arabic/English internationalization with RTL support
- Custom **Barcode Scanner** component

### Backend
- **Node.js** + **Express** + **TypeScript**
- **PostgreSQL** — relational database
- RESTful API architecture
- JWT-based authentication

---

## 📁 Project Structure

```
store-dashboard/
├── frontend/
│   ├── public/locales/          # Translation files (ar / en)
│   └── src/
│       ├── pages/               # Dashboard, POS, Products, Orders...
│       ├── i18n/                # Internationalization setup
│       ├── api.ts               # API client
│       └── BarcodeScanner.tsx   # Barcode input component
│
└── backend/
    └── src/
        ├── auth/                # Authentication logic & routes
        ├── db/                  # DB connection & queries
        ├── pos/                 # POS routes
        ├── stores/              # Store management
        └── suppliers/           # Supplier routes
```

---

## 🚀 Getting Started

### Prerequisites
- Node.js `>= 18`
- PostgreSQL `>= 14`

### Environment Variables

Copy `.env.example` to `.env` and fill in the required values:

```bash
cp backend/.env.example backend/.env
```

### Installation

```bash
# Install backend dependencies
cd backend && npm install

# Install frontend dependencies
cd ../frontend && npm install
```

### Running Locally

```bash
# Start backend
cd backend && npm run dev

# Start frontend (new terminal)
cd frontend && npm run dev
```

---

## 📸 Screenshots

> Coming soon — UI previews will be added once core features are stable.

---

## 🗺️ Roadmap

- [x] Authentication & multi-store support
- [x] Product & inventory management
- [x] POS with barcode scanning
- [x] Supplier management
- [x] AI integration
- [x] Arabic/English bilingual support
- [ ] Customer-facing storefront
- [ ] Sales reports & analytics
- [ ] Mobile-responsive POS view

---

## 📄 License

This project is licensed under **CC BY-NC-ND 4.0** — you may view and share the code with attribution, but may not use it commercially or create derivative works.

---

<div align="center">
  <sub>Built with care — all rights reserved by the author.</sub>
</div>
