# 🔗 LnkShrt — URL Shortener & Analytics Platform

A full-stack URL shortening platform that allows users to create, manage, and analyze short links with detailed click analytics.

## 🚀 Live Demo

**Website:** https://utpx.in

---

## ✨ Features

* 🔗 Create short URLs
* 📊 Click analytics
* 🌍 Visitor country tracking
* 📱 Device & browser tracking
* 🔗 Referral/source tracking
* 📈 Link performance statistics
* 🏷️ UTM campaign tracking
* 🔐 Password-protected links
* ⏳ Link expiration
* 🎯 Custom domains
* 📱 QR code generation
* 👤 User authentication
* ⚡ Redis caching
* 💳 Donation/payment integration

---

## 🛠️ Tech Stack

### Frontend

* Next.js
* React
* TypeScript
* Tailwind CSS
* Redux Toolkit
* Axios

### Backend

* Node.js
* Express.js
* TypeScript
* REST API
* JWT Authentication
* Zod

### Database & Infrastructure

* PostgreSQL
* Prisma ORM
* Redis
* Neon PostgreSQL
* Redis Cloud

### Deployment & Tools

* Vercel
* Render
* Cloudflare
* GitHub
* Postman
* Docker

---

## 📂 Repositories

The frontend and backend are maintained as separate repositories.

### 🎨 Frontend

👉https://github.com/Utpalsonowal7/nextjsUrl

Built with Next.js, TypeScript and Tailwind CSS.

### ⚙️ Backend

👉 https://github.com/Utpalsonowal7/link-shortner-backend

REST API built with Node.js, Express, Prisma and PostgreSQL.

---

## 🏗️ Architecture

```text
                    ┌──────────────────┐
                    │     Frontend     │
                    │    Next.js       │
                    │   TypeScript     │
                    └────────┬─────────┘
                             │
                             │ REST API
                             ▼
                    ┌──────────────────┐
                    │      Backend     │
                    │ Node.js + Express│
                    └────────┬─────────┘
                             │
                 ┌───────────┴───────────┐
                 ▼                       ▼
          ┌──────────────┐       ┌──────────────┐
          │  PostgreSQL  │       │    Redis     │
          │    Prisma    │       │    Cache     │
          └──────────────┘       └──────────────┘
```

---

## 📊 Analytics

The platform tracks information about link visits, including:

* Total clicks
* Unique visitors
* Country
* Device
* Browser
* Operating system
* Referral source
* UTM parameters
* Link performance

---

## 🔐 Security

* JWT-based authentication
* Password-protected links
* Input validation with Zod
* Secure password handling
* Protected API routes
* Environment-based configuration

---

## 🎯 Project Goals

This project was built to explore and implement real-world full-stack concepts such as:

* REST API architecture
* Database design
* Authentication & authorization
* Caching with Redis
* Analytics systems
* Custom domain handling
* DNS configuration
* Cloud deployment
* Scalable database queries

---

## 📌 Project Status

🚧 **Actively developed**

New features and improvements are continuously being added.

---

## 👨‍💻 Author

**Utpal Sonowal**

Full-Stack Developer | JavaScript | TypeScript | Next.js | Node.js

* GitHub: [@Utpalsonowal7](https://github.com/Utpalsonowal7)
* LinkedIn: YOUR_LINKEDIN_URL

---

⭐ If you find this project interesting, consider giving it a star!
