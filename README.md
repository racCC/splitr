<img width="2539" height="1291" alt="Screenshot 2025-09-16 203120" src="https://github.com/user-attachments/assets/117bbd41-3cf0-4e88-b533-d6dcc2476270" />


# Splitr💸 AI-Powered Splitwise Clone

A full-stack expense-splitting app inspired by Splitwise — rebuilt with modern tools, AI insights, and automated reminders.

Built using **Next.js 15**, **React 19**, **Convex**, **Clerk**, **Inngest**, **Resend**, **Gemini AI**, **Tailwind CSS**, and **Shadcn UI**.



## ✨ Features

- 🔐 Authentication with **Clerk** (email, password, social logins)
- 👥 Manage **contacts** (individuals & groups)
- 💵 Add **1-on-1** and **group expenses**
- 📊 **Dashboard** with balances and summaries
- 🤝 **Settlements** to clear balances
- ⏰ Automated **payment reminders** via **Inngest + Resend**
- 🤖 Weekly **AI insights** powered by **Gemini**
- 🎨 Modern, accessible UI with **Shadcn UI** + **Tailwind CSS**
- 🌐 Deployed with **Vercel** + serverless backends



## 🛠 Tech Stack

- **Frontend:** Next.js 15 (App Router), React 19  
- **Backend:** Convex (serverless DB & functions)  
- **Auth:** Clerk  
- **Cron / Background jobs:** Inngest  
- **Emails:** Resend  
- **AI:** Gemini API  
- **UI:** Tailwind + Shadcn UI  



## 🚀 Getting Started

### 1. Clone & Install

```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
npm install
```

### 2. Configure Environment

Create a `.env.local` file:

```env
# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_...
CLERK_SECRET_KEY=sk_test_...

# Convex
CONVEX_DEPLOYMENT=dev
CONVEX_AUTH_URL=http://localhost:3000

# Inngest
INNGEST_EVENT_KEY=...
INNGEST_SIGNING_KEY=...

# Resend
RESEND_API_KEY=re_...

# Gemini
GEMINI_API_KEY=AIza...

# App
NEXT_PUBLIC_APP_URL=http://localhost:3000
```

### 3. Run Dev Servers

```bash
# Next.js
npm run dev

# Convex (backend)
npx convex dev

# Inngest (jobs)
npx inngest dev
```





## 📂 Project Structure

```
.
├─ app/                # Next.js routes (App Router)
├─ components/         # UI + shared components
├─ convex/             # Backend functions & schema
├─ inngest/            # Cron + event handlers
├─ hooks/              # Custom React hooks
├─ lib/                # Utils (AI, email, auth helpers)
├─ public/            
└─ README.md
```
---
