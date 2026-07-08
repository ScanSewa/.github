<!-- SEO: ScanSewa — AI-powered restaurant POS, billing, ERP, inventory, QR ordering & hotel/hospitality management software. Cloud POS for restaurants, cafés, bars and hotels across Asia and worldwide. A Lacspace product. -->

<div align="center">

<a href="https://scansewa.com">
  <img alt="ScanSewa — AI-powered POS, ERP and hospitality management platform" src="https://capsule-render.vercel.app/api?type=waving&color=0:6C2BD9,100:9333EA&height=220&section=header&text=ScanSewa&fontSize=76&fontColor=ffffff&animation=fadeIn&fontAlignY=40&desc=AI-Powered%20POS%20%C2%B7%20ERP%20%C2%B7%20Hospitality%20Platform&descAlignY=62&descSize=18" width="100%"/>
</a>

<br/>

<a href="https://readme-typing-svg.demolab.com">
  <img alt="What ScanSewa does" src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=22&pause=1000&color=9333EA&center=true&vCenter=true&width=820&height=50&lines=%F0%9F%8D%BD%EF%B8%8F++Smart+POS+%26+billing+for+restaurants+%26+caf%C3%A9s;%F0%9F%8F%A8++All-in-one+hospitality+%26+hotel+management;%F0%9F%93%B1++Order+from+any+table+with+a+QR+scan;%F0%9F%93%8A++AI+insights%3A+sales%2C+cost+%26+profit+in+real+time;%E2%98%81%EF%B8%8F++One+cloud.+Every+device.+Always+in+sync." />
</a>

<br/><br/>

[![Website](https://img.shields.io/badge/Visit-scansewa.com-6C2BD9?style=for-the-badge&logo=googlechrome&logoColor=white)](https://scansewa.com)
[![Book a Demo](https://img.shields.io/badge/Book%20a-Demo-9333EA?style=for-the-badge&logo=rocket&logoColor=white)](https://scansewa.com)
[![Contact](https://img.shields.io/badge/Contact-info.scansewa@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:info.scansewa@gmail.com)

<sub>⚡ Built across **Asia** · Serving businesses **worldwide** 🌏 · A **[Lacspace](https://lacspace.com)** product</sub>

</div>

---

## 🌟 What is ScanSewa?

**ScanSewa** is an **AI-powered business-management platform** that runs an entire food & hospitality operation from one cloud system — **billing, orders, kitchen, menu, inventory, staff, customers, and hotel rooms** — synced in real time across every screen.

One café or a hundred-room hotel, ScanSewa replaces a drawer full of disconnected tools with **one login, one dashboard, everything in sync.**

<div align="center">

**`Scan`** → **`Order`** → **`Fire to Kitchen`** → **`Bill & Pay`** → **`Auto-deplete Stock`** → **`See Profit`** — live.

</div>

---

## 🧩 One ecosystem, every surface

> A complete infrastructure — web dashboards, native mobile apps, and a real-time multi-tenant cloud — engineered as one product family.

### 🖥️ Web Dashboards
| Product | Built for | Highlights |
|---|---|---|
| 🍽️ **ERP Dashboard** | Restaurants & cafés | Fast billing, orders, tables, menu, **inventory + recipes**, purchases, expenses, sales & profit — a focused, restaurant-only ERP |
| 🏨 **Panel Dashboard** | Hospitality & hotels | The full hospitality suite — POS + **rooms, front-desk, housekeeping, bookings**, add-on modules & multi-outlet control |
| 🛠️ **Master Panel** | ScanSewa operators | Vendor onboarding, subscriptions, plans, add-on approvals & platform-wide control |

### 📱 Mobile Apps
| App | Built for | Highlights |
|---|---|---|
| 🧾 **POS Master** | Owners & cashiers | A full POS in your pocket — billing, orders, KOT printing & live dashboards |
| 🧑‍🍳 **Captain** | Waiters & riders | Take table orders and manage deliveries from the floor |
| 📲 **Customer App** | Diners & guests | QR-code menu, self-ordering & live order tracking |

### ⚙️ Cloud Infrastructure
A **multi-tenant, real-time API** (Socket.IO) that powers every dashboard and app — secure per-vendor isolation, live order & stock sync, and a modular add-on engine (Loyalty, Finance, CRM, Integrations, Developer API).

---

## 🗺️ How it all connects

```mermaid
flowchart TB
    subgraph WEB["🖥️  Web Dashboards"]
        ERP["🍽️ ERP Dashboard<br/><sub>Restaurants</sub>"]
        PANEL["🏨 Panel Dashboard<br/><sub>Hospitality</sub>"]
        MASTER["🛠️ Master Panel<br/><sub>Admin</sub>"]
    end
    subgraph APP["📱  Mobile Apps"]
        POS["🧾 POS Master"]
        CAP["🧑‍🍳 Captain"]
        CUST["📲 Customer App<br/><sub>QR Ordering</sub>"]
    end
    API{{"⚙️ ScanSewa Cloud API<br/><sub>multi-tenant · real-time</sub>"}}
    DB[("🗄️ Database")]
    ERP --> API
    PANEL --> API
    MASTER --> API
    POS --> API
    CAP --> API
    CUST --> API
    API <--> DB
    API -. "🔔 live orders & stock" .-> WEB
    API -. "🔔 live sync" .-> APP

    classDef api fill:#6C2BD9,stroke:#4C1D95,color:#fff;
    classDef store fill:#9333EA,stroke:#6C2BD9,color:#fff;
    class API api;
    class DB store;
```

---

## ✨ Why teams choose ScanSewa

- 🤖 **AI-powered insights** — turn every sale into decisions: revenue, cost, margin & trends at a glance
- ⚡ **Real-time everything** — orders, stock and payments sync live across POS, kitchen and phones
- 📦 **Inventory that tracks itself** — sales auto-deplete raw materials through recipe links
- 🧩 **Modular add-ons** — switch on Loyalty, Finance, CRM, Integrations & Developer API as you grow
- 🖨️ **Kitchen-ready** — KOT/KDS, thermal printing and table management out of the box
- ☁️ **Cloud-native & multi-device** — nothing to install; open a browser or the app and go
- 🔒 **Secure by design** — strict per-vendor data isolation on a multi-tenant core

---

## 🛠️ Engineering

<div align="center">

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)
![Expo](https://img.shields.io/badge/Expo-000020?style=flat-square&logo=expo&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)

</div>

---

<div align="center">

## Ready to modernize your restaurant, café or hotel?

### **[🌐 scansewa.com](https://scansewa.com)** &nbsp;·&nbsp; **[🚀 Book a Demo](https://scansewa.com)** &nbsp;·&nbsp; **[✉️ info.scansewa@gmail.com](mailto:info.scansewa@gmail.com)**

<br/>

<img alt="A Lacspace product — AI software built across Asia for the world" src="https://capsule-render.vercel.app/api?type=waving&color=0:9333EA,100:6C2BD9&height=120&section=footer&text=A%20Lacspace%20Product&fontSize=22&fontColor=ffffff&fontAlignY=72" width="100%"/>

<sub>© 2026 **ScanSewa** · Built by **[Lacspace Corporation](https://lacspace.com)** · AI-powered software, from Asia to the world 🌏</sub>

</div>

<!-- keywords: restaurant POS software, cloud billing system, restaurant ERP, QR code ordering, hotel management system, hospitality PMS, KOT KDS, inventory management, recipe costing, waiter app, kitchen display system, multi-tenant SaaS, restaurant management software Asia -->
