# 📨 WhatsApp Business Inbox – Self-Hosted & Extendable

A modern, self-hosted **WhatsApp Cloud API** inbox platform built for businesses who want full control of their customer communications. Designed to support **multiple agents**, link chats to **your own database**, and adapt easily to your workflow.

> Built with 💻 Next.js + Node.js/Express + PostgreSQL  
> Deployed via Docker 🐳 | 100% yours — no vendor lock-in.

---

## ⚙️ Features

✅ Official WhatsApp Cloud API integration  
✅ Multi-agent login system  
✅ Real-time chat inbox and message view  
✅ Chat history linked to customers  
✅ PostgreSQL database (no Supabase dependency)  
✅ Fully Dockerized (easy to deploy anywhere)  
✅ Extendable: orders, jobs, templates, media, analytics

---

## 🧱 Tech Stack

| Layer       | Tech            |
|-------------|-----------------|
| Frontend    | Next.js, React, TailwindCSS |
| Backend     | Node.js, Express |
| Database    | PostgreSQL       |
| Auth (Basic)| JWT / Custom     |
| Deployment  | Docker, Docker Compose |
| Messaging   | WhatsApp Cloud API (Meta Graph API) |

---

## 🚀 Quick Start

### 🔐 Prerequisites

- WhatsApp Cloud API account
- Your Meta `Access Token`, `Phone Number ID`
- A VPS (e.g., Afrihost) with Docker installed

### 🛠️ Setup Instructions

1. **Clone the repository**

```bash
git clone https://github.com/your-username/whatsapp-inbox.git
cd whatsapp-inbox
