🚀 Nosu-AI

Nosu-AI is an AI-powered web application built with Next.js 14, TypeScript, TailwindCSS, and Supabase.
It provides intelligent chat support, hospital/staff management, and an admin panel, designed to enhance productivity in healthcare and enterprise environments.

📂 Project Structure
Nosu-Ai-main/
│── Nosu-AI/                # Main Next.js App
│   ├── app/                # Pages & API routes
│   ├── components/         # Reusable UI & features
│   ├── public/             # Static assets
│   ├── supabase.sql        # Database schema
│   ├── package.json        # Dependencies
│   └── tsconfig.json       # TypeScript config
│── README.md               # Project documentation

✨ Features

🔐 Authentication system (login & register with password strength validation)

💬 AI Chat & Direct Chat (powered by API routes)

🏥 Hospital & Staff Management modules

🎨 Beautiful UI with TailwindCSS + shadcn components

⚡ Fast API routes using Next.js App Router

📊 Admin Dashboard for managing hospital data

🌙 Light/Dark Mode Toggle with theme provider

🛠️ Tech Stack

Frontend: Next.js 14 (App Router), TypeScript, TailwindCSS, shadcn/ui

Backend: Next.js API Routes, Supabase (SQL database)

Authentication: Supabase Auth

Styling: TailwindCSS, Framer Motion animations

🚀 Getting Started
1️⃣ Clone the Repository
git clone https://github.com/<your-username>/Nosu-Ai.git
cd Nosu-Ai/Nosu-AI

2️⃣ Install Dependencies
npm install

3️⃣ Configure Environment

Create a .env.local file in the root of Nosu-AI and add:

NEXT_PUBLIC_SUPABASE_URL=your-supabase-url
NEXT_PUBLIC_SUPABASE_ANON_KEY=your-supabase-anon-key

4️⃣ Run Development Server
npm run dev


Your app will be available at:
👉 http://localhost:3000

🏥 Modules Overview

Landing Page → Hero, Features, Testimonials, Footer

Auth Pages → Register, Login with validation

Admin Dashboard → Manage hospitals, staff, chats

Chat System → Smart AI chat & direct messaging
