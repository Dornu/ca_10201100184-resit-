# 🛒 GoMart - Ghana's Premier E-commerce Platform

[![GitHub Repository](https://img.shields.io/badge/GitHub-GoMart-blue?style=flat-square&logo=github)](https://github.com/Dery001/CA_10201100092.git)
[![Node.js](https://img.shields.io/badge/Node.js-18+-green?style=flat-square&logo=node.js)](https://nodejs.org/)
[![MongoDB](https://img.shields.io/badge/Database-MongoDB-green?style=flat-square&logo=mongodb)](https://mongodb.com/)
[![Next.js](https://img.shields.io/badge/Frontend-Next.js-black?style=flat-square&logo=next.js)](https://nextjs.org/)
## 🌟 Developer
Name: Martin Dery
Roll Number:10201100092
## 🌟 Project Overview

GoMart is an innovative, comprehensive e-commerce platform designed specifically for the Ghanaian market. Built with modern technologies and localized features, it provides a seamless shopping experience with integrated Mobile Money payments, local delivery services, and Ghana-specific business logic.

## 📁 Repository Information

**Repository:** [GoMart E-commerce App](https://github.com/Dery001/CA_10201100092.git)  
**Technology:** Full-stack JavaScript (Node.js + Next.js)  
**Database:** MongoDB Atlas with Prisma ORM

## 🚀 Key Features

### 🇬🇭 Ghana-Focused Features
- **Mobile Money Integration**: MTN Mobile Money, Vodafone Cash, AirtelTigo Money
- **Local Delivery**: Integration with Ghana Post, DHL Ghana, Bolt, Jumia Logistics
- **Regional Support**: Ghana regions (Greater Accra, Ashanti, etc.) and cities
- **Currency**: Ghana Cedi (GHS) as primary currency
- **Local Business Logic**: Tailored for Ghanaian e-commerce needs

### 🛍️ Core E-commerce Features
- Multi-vendor marketplace
- Product catalog with categories
- Shopping cart and checkout
- Order management and tracking
- Customer reviews and ratings
- Vendor management system
- Payment processing
- Shipping and delivery tracking

### 🤖 Innovative Features (Future Phases)
- AI-powered product recommendations
- Voice-enabled search
- AR/3D product preview
- Gamification system with rewards
- Advanced analytics dashboard

## 🏗️ Project Structure

```
EcommerceCloudApp/
├── prisma/                    # Prisma schema and seed files
│   ├── schema.prisma          # Database schema
│   └── seed.ts                # Database seeding script
├── src/                       # Next.js Application
│   ├── app/                   # Next.js App Router
│   │   ├── api/               # API routes
│   │   ├── ui/                # UI pages
│   │   ├── layout.tsx         # Root layout
│   │   └── page.tsx           # Home page
│   ├── components/            # Reusable UI components
│   └── lib/                   # Utility libraries
├── public/                    # Static assets
└── README.md                  # Project documentation
```

## 🛠️ Technology Stack

### Backend (API Routes)
- **Framework**: Next.js API Routes
- **Database**: MongoDB with Prisma ORM
- **Authentication**: JWT (JSON Web Tokens)
- **Validation**: Built-in validation

### Frontend
- **Framework**: Next.js 15 (React 19)
- **Styling**: TailwindCSS
- **State Management**: React Hooks
- **UI Components**: Custom components with Tailwind
- **Notifications**: React Toastify

### Database Schema
- **Customer Management**: User profiles, authentication
- **Product Catalog**: Products, categories, vendors
- **Order Processing**: Orders, order items, payments
- **Shipping**: Delivery tracking, courier management
- **Reviews**: Product ratings and feedback
- **Cart**: Shopping cart functionality

## 🔧 Setup Instructions

### Prerequisites
- Node.js (v18 or higher)
- npm or yarn
- MongoDB Atlas account (or local MongoDB)
- Git

### Clone Repository
```bash
git clone https://github.com/Dery001/CA_10201100092.git
cd ca_10211100297/EcommerceCloudApp
```

### Project Setup

1. **Install dependencies**:
   ```bash
   npm install
   ```

2. **Environment Configuration**:
   Create a `.env` file in the project root with the following variables:
   ```env
   # Database Configuration
   DATABASE_URL="Create a PERSONAL MONGOdb URL"
   
   # JWT Secret (Change in production - use a strong random string)
   # 🛒 GoMart — Ghana's E‑commerce Platform

   [![GitHub Repository](https://img.shields.io/badge/GitHub-GoMart-blue?style=flat-square&logo=github)](https://github.com/Dery001/CA_10201100092.git) [![Next.js](https://img.shields.io/badge/Frontend-Next.js-black?style=flat-square&logo=next.js)](https://nextjs.org/) [![Node.js](https://img.shields.io/badge/Node.js-18+-green?style=flat-square&logo=node.js)](https://nodejs.org/)

   Short, focused README with key sections for developers and maintainers.

   ## Live Demo

   - Live site: **REPLACE_WITH_LIVE_URL**

   > Add the real live URL above (remove the placeholder).

   ## Summary

   GoMart is a modern, Ghana-focused multi-vendor e-commerce platform built with Next.js, Prisma, and MongoDB. It supports local payment methods (Mobile Money), regional delivery options, and vendor management.

   ## Quick Links

   - Repository: https://github.com/Dery001/CA_10201100092.git
   - Local dev: http://localhost:3000

   ## Features

   - Mobile Money integrations (MTN, Vodafone, AirtelTigo)
   - Multi-vendor product catalog
   - Shopping cart, checkout, orders, and reviews
   - Vendor management and order tracking

   ## Project Structure (high-level)

   ```
   EcommerceCloudApp/
   ├─ prisma/           # schema & seed
   ├─ src/              # Next.js app (app router)
   │  ├─ app/           # pages, api routes
   │  ├─ components/    # UI components
   │  └─ lib/           # utilities
   ├─ public/           # static assets
   └─ README.md
   ```

   ## Getting Started (development)

   Prerequisites

   - Node.js v18+ and npm or yarn
   - MongoDB (Atlas or local)

   Steps

   ```bash
   git clone https://github.com/Dery001/CA_10201100092.git
   cd EcommerceCloudApp
   npm install
   ```

   1. Create a `.env` file (see `.env.example` or the `Environment` section below).
   2. Generate Prisma client and push schema:

   ```bash
   npm run db:generate
   npm run db:push
   npm run db:seed    # optional
   ```

   3. Start development server:

   ```bash
   npm run dev
   ```

   The app runs at `http://localhost:3000`.

   ## Environment

   Create a `.env` with values for the following (example):

   ```env
   DATABASE_URL="mongodb+srv://<user>:<pass>@<cluster>/<db>?retryWrites=true&w=majority"
   JWT_SECRET="change-me"
   NEXTAUTH_SECRET="change-me"
   NEXTAUTH_URL="http://localhost:3000"
   ```

   Never commit secrets to the repo. Use `.env.example` as a template.

   ## API (examples)

   - `GET /api/products` — list products
   - `GET /api/products/:id` — product details
   - `POST /api/customers/register` — register customer
   - `POST /api/customers/login` — login

   Refer to the `src/app/api` folder for full route details.

   ## Deployment

   1. Configure production environment variables in your hosting platform.
   2. Build and deploy (Vercel recommended for Next.js):

   ```bash
   npm run build
   npm run start
   ```

   ## Contributing

   1. Fork the repo
   2. Create a feature branch
   3. Open a PR with a clear description and tests if applicable

   ## License

   MIT

   ---

   If you'd like, I can (a) add the actual live URL you mentioned, (b) add a `Live Demo` badge, or (c) create a `.env.example` file. Tell me which. 