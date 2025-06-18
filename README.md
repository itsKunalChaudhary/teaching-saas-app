# 🧠 LMS SaaS Platform with AI Voice Agents

Build a full-featured LMS SaaS application from scratch using **Next.js**, **Supabase**, **Clerk**, **Stripe**, and **Vapi**. This platform supports secure authentication, AI voice tutoring, subscriptions, and real-time learning—all wrapped in a modern, scalable architecture.

---

## 🤖 Introduction

This project enables you to build and deploy a real-time teaching platform with:

- User authentication
- Subscription and payment management
- Interactive, AI-driven voice tutoring sessions

AI vocal agents powered by **Vapi** enhance the learning experience by delivering human-like voice interactions.

If you encounter bugs or need help, join our [Discord community](https://discord.com) with **50k+ developers** sharing knowledge and support.

---

## ⚙️ Tech Stack

- **Next.js** – React framework with SSR, SSG, and API routes.
- **Supabase** – Realtime backend with auth, DB, and storage.
- **Clerk** – Authentication, user management, and billing.
- **Stripe** – Subscription and payment processing.
- **Vapi** – Voice AI platform for conversational agents.
- **Sentry** – Monitoring and error tracking.
- **shadcn/ui** – UI components built on Radix UI + Tailwind CSS.
- **Tailwind CSS** – Utility-first CSS framework.
- **TypeScript** – Strongly typed JavaScript for scalable dev.
- **Zod** – Type-safe schema validation.

---

## 🔋 Features

✅ **AI Voice Agents** – Practice with voiced AI tutors  
✅ **Authentication** – Google login, email/password via Clerk  
✅ **Billing & Subscriptions** – Stripe-powered plan control  
✅ **Bookmarks & History** – Save tutors & revisit past sessions  
✅ **Reusable Components** – Clean, maintainable codebase  
✅ **Create Your Tutor** – Customize your own AI assistant  
✅ **Responsive Design** – Works across all devices  
✅ **Real-time Backend** – Supabase for live sync & storage  
✅ **Modern UI** – Powered by shadcn/ui & Tailwind CSS  
✅ **Scalable Framework** – Built on Next.js  
✅ **Smart Search** – Discover tutors with filters and keywords

---

## 🤸 Quick Start

Follow these steps to get the project up and running on your local machine.

### 🔧 Prerequisites

Ensure you have:

- Git
- Node.js
- npm

### 📥 Clone the Repository

```bash
git clone https://github.com/adrianhajdin/saas-app.git
cd saas-app
````
### 📦 Install Dependencies
````
npm install
````
### ⚙️ Environment Setup
````
# Sentry
SENTRY_AUTH_TOKEN=

# Vapi
NEXT_PUBLIC_VAPI_WEB_TOKEN=

# Clerk
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=
CLERK_SECRET_KEY=
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_IN_FALLBACK_REDIRECT_URL=/
NEXT_PUBLIC_CLERK_SIGN_UP_FALLBACK_REDIRECT_URL=/

# Supabase
NEXT_PUBLIC_SUPABASE_URL=
NEXT_PUBLIC_SUPABASE_ANON_KEY=
````

💡 Replace placeholders with real credentials from: Supabase, Clerk, Sentry, and Vapi.

### ▶️ Run the Development Server
````
npm run dev
````
Visit http://localhost:3000 to start exploring!

