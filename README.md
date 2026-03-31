<div align="center">

<br/>

[![Typing SVG](https://readme-typing-svg.herokuapp.com?font=JetBrains+Mono&weight=600&size=22&pause=1000&color=9B87F5&center=true&vCenter=true&width=700&lines=Hey%2C+I'm+Thulunga+%F0%9F%91%8B;Product+Engineer+%7C+Full-Stack+Developer;Building+real+systems%2C+not+demos;Consistency+over+Talent+%F0%9F%94%A5)](https://git.io/typing-svg)

<br/>

[![Profile Views](https://komarev.com/ghpvc/?username=thulunga&label=Profile+Views&color=7c5cbf&style=flat-square)](https://github.com/thulunga)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-thulunga-0a66c2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/thulunga/)
&nbsp;
[![Email](https://img.shields.io/badge/Email-thulunga.tb%40gmail.com-ea4335?style=flat-square&logo=gmail&logoColor=white)](mailto:thulunga.tb@gmail.com)

</div>

---

## 🧠 About Me

- 👨‍💻 **Software Developer I** at **SOTI Inc.** - Promoted from Associate Developer → Developer I · MVP Nominee-2x
- 🎓 **B.Tech in Computer Science** - NIT Calicut
- 🌏 From **BTR, Assam** - Northeast India
- 🚀 Actively building and shipping **[StoreBanao](https://storebanao.in)** - a live, production SaaS product
- ⚙️ I care about systems that scale, clean architecture, and product-first engineering

---

## 🚀 Featured Project - StoreBanao

<div align="center">

[![Live](https://img.shields.io/badge/🟢%20Live%20at-storebanao.in-5ddba8?style=for-the-badge)](https://storebanao.in)

</div>

> A **multi-vendor e-commerce SaaS platform** for local Indian sellers - built, deployed, and actively maintained. Focused on empowering small businesses, especially from Northeast India.

**What makes it real:**
- 🏪 Vendor-specific subdomains - `vendor.storebanao.in`
- 🔐 Clerk-powered seller authentication with webhook integration
- 📦 Full product & order management system
- 💳 Billing system - Manual UPI billing (live) → Razorpay subscriptions (in progress)
- 🖼️ Cloudinary image CDN with `q_auto` / `f_auto` optimization
- 📧 Transactional emails via Resend
- 📊 Admin dashboard with analytics

### Architecture

```
Next.js 14 (App Router)   →   Node.js / Express API
         ↓                            ↓
    Clerk (Auth)              PostgreSQL via Prisma
         ↓                            ↓
   Cloudinary (Images)          Railway (DB Host)
         ↓
Vercel (Frontend)  +  Railway (API)
```

**Key decisions:**
- **Turborepo monorepo** - clean multi-package separation from day one
- **PostgreSQL over NoSQL** - relational integrity + ACID compliance
- **Clerk webhooks** - required explicit `isWebhookRoute` check before domain rewrite in middleware
- **Cloudinary `public_id` stored in DB** - enables image cleanup on product deletion

---

## 🧰 Tech Stack

**Frontend**

![Next.js](https://img.shields.io/badge/Next.js_14-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178c6?style=flat-square&logo=typescript&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-0f172a?style=flat-square&logo=tailwindcss&logoColor=38bdf8)
![React](https://img.shields.io/badge/React-20232a?style=flat-square&logo=react&logoColor=61dafb)

**Backend**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2d3748?style=flat-square&logo=prisma&logoColor=white)

**Auth · Storage · Payments · Email**

![Clerk](https://img.shields.io/badge/Clerk-6c47ff?style=flat-square&logo=clerk&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448c5?style=flat-square&logo=cloudinary&logoColor=white)
![Razorpay](https://img.shields.io/badge/Razorpay-02042b?style=flat-square&logo=razorpay&logoColor=3395ff)
![Resend](https://img.shields.io/badge/Resend-000000?style=flat-square)

**Infra & Tooling**

![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white)
![Turborepo](https://img.shields.io/badge/Turborepo-EF4444?style=flat-square&logo=turborepo&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=thulunga&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d0d14&title_color=9b87f5&icon_color=5ddba8&text_color=c8c6e0" height="165"/>
&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=thulunga&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d0d14&title_color=9b87f5&text_color=c8c6e0" height="165"/>

<br/><br/>

<img src="https://streak-stats.demolab.com?user=thulunga&theme=tokyonight&hide_border=true&background=0d0d14&ring=9b87f5&fire=5ddba8&currStreakLabel=c8c6e0" />

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=thulunga&theme=tokyo-night&hide_border=true&bg_color=0d0d14&color=9b87f5&line=5ddba8&point=f5c77e" />

</div>

---

## 🎯 Currently Working On

| What | Status |
|---|---|
| StoreBanao - B1 Billing (Manual UPI) | 🔨 In Progress |
| StoreBanao - Razorpay Subscriptions | 📋 Planned (Month 2) |
| thulunga.com - Dev journal & system design blog | 🏗️ Building |
| CodeTalks - AI-powered dev tooling | 💡 Early Stage |

---

## ⚡ Philosophy

> *"Consistency beats talent. Systems beat motivation. Execution beats ideas."*

---

<div align="center">

⭐ *Building in public - this is just the beginning.*

</div>
