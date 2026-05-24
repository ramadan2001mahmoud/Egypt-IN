# ERP System - Enterprise Resource Planning

نظام ERP متكامل للمؤسسات يشمل المحاسبة والمخزون ونقطة البيع.

## Features

- 🔐 Authentication & Authorization (JWT)
- 📊 Interactive Dashboard
- 📦 Inventory Management
- 🛒 Point of Sale (POS)
- 💰 Accounting System
- 👥 Customers & Suppliers Management
- 👔 Employees Management
- 📈 Reports (PDF/Excel)
- 🌙 Dark Mode Support
- 🇸🇦 Arabic RTL Support
- 📱 Responsive Design

## Tech Stack

**Frontend:** React, Vite, TailwindCSS, Zustand, Axios, Recharts, Framer Motion

**Backend:** Node.js, Express.js, PostgreSQL, Prisma, JWT, Socket.io

## Installation

```bash
# Clone repository
git clone https://github.com/yourusername/erp-system.git
cd erp-system

# Install dependencies
npm run install-all

# Setup database
cd server
npx prisma generate
npx prisma migrate dev

# Run development
npm run dev
