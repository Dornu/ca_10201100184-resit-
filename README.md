# 🛒 GoMart E-commerce Platform

[![GitHub Repository](https://img.shields.io/badge/GitHub-GoMart-blue?style=flat-square\&logo=github)](https://github.com/Dornu/CA_10201100184-resit-.git)
[![Node.js](https://img.shields.io/badge/Node.js-18+-green?style=flat-square\&logo=node.js)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/Database-MongoDB-green?style=flat-square\&logo=mongodb)](https://mongodb.com/)
[![Next.js](https://img.shields.io/badge/Frontend-Next.js-black?style=flat-square\&logo=next.js)](https://nextjs.org/)

## 🌟 Dev

* **Name:** Caleb Abayateye
* **Roll Number:** 10201100184

## 🌟 Overview

GoMart is a Ghana-focused, multi-vendor e-commerce platform delivering seamless shopping experiences. It supports local payment methods (Mobile Money), regional delivery services, vendor management, and is tailored for the Ghanaian market.

## 📁 Repository

* **Repo:** [GoMart E-commerce App](https://github.com/Dornu/CA_10201100184-resit-.git)
* **Tech:** Node.js + Next.js
* **Database:** MongoDB Atlas + Prisma ORM

## 🚀 Key Features

**🇬🇭 Ghana-Specific**

* Mobile Money: MTN, Vodafone, AirtelTigo
* Local delivery: Ghana Post, DHL Ghana, Bolt, Jumia Logistics
* Regional support: Greater Accra, Ashanti, etc.
* Currency: Ghana Cedi (GHS)

**🛍️ Core E-commerce**

* Multi-vendor marketplace & product catalog
* Shopping cart, checkout, orders & tracking
* Customer reviews & ratings
* Vendor management
* Payment processing & delivery tracking

**🤖 Future Features**

* AI product recommendations
* Voice search & AR/3D previews
* Gamification & rewards
* Analytics dashboard

## 🏗️ Project Structure

```
EcommerceCloudApp/
├── prisma/          # Database schema & seed
├── src/             # Next.js app
│   ├── app/         # Pages & API routes
│   ├── components/  # UI components
│   └── lib/         # Utilities
├── public/          # Static assets
└── README.md
```

## 🛠️ Tech Stack

**Backend:** Next.js API Routes, MongoDB + Prisma, JWT auth
**Frontend:** Next.js 15, TailwindCSS, React Hooks, React Toastify
**Database:** Customers, Products, Orders, Shipping, Reviews, Cart

## 🔧 Setup

**Prerequisites:** Node.js v18+, npm/yarn, MongoDB, Git

**Clone Repo:**

```bash
git clone https://github.com/Dornu/CA_10201100184-resit-.git
cd EcommerceCloudApp
```

**Install Dependencies:**

```bash
npm install
```

**Environment:**
Create `.env`:

```env
DATABASE_URL="YOUR_MONGODB_URI"
JWT_SECRET="CHANGE_ME"
NEXTAUTH_SECRET="CHANGE_ME"
NEXTAUTH_URL="http://localhost:3000"
```

**Prisma Setup:**

```bash
npm run db:generate
npm run db:push
npm run db:seed  # optional
```

**Run Development Server:**

```bash
npm run dev
```

Access at `http://localhost:3000`.

## 🔌 API Examples

* `GET /api/products` — List products
* `GET /api/products/:id` — Product details
* `POST /api/customers/register` — Register customer
* `POST /api/customers/login` — Customer login

Full API routes: `src/app/api`

## 🚀 Deployment

1. Configure environment variables in hosting platform
2. Build & start:

```bash
npm run build
npm run start
```

**Recommendation:** Vercel for Next.js

## 🤝 Contributing

1. Fork repo
2. Create feature branch
3. Open PR with description & tests

## 📄 License

MIT

## 🌐 Live Demo

[https://gomartgh.onrender.com/](https://gomartgh.onrender.com/)
