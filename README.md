# 🎥 Fac2Fac – Full-Stack Video Conferencing App

**Fac2Fac** is a modern, real-time video conferencing web application inspired by platforms like Zoom and Google Meet. It offers seamless video meetings, screen sharing, authentication, and scheduling — all in one place.

Deployed live at 👉 **[fac2fac.vercel.app](https://fac2fac.vercel.app)**

---

## 🛠 Tech Stack

- **Frontend Framework**: Next.js (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Library**: shadcn/ui
- **Authentication**: Clerk
- **Real-time Video**: getstream + WebRTC
- **Deployment**: Vercel

---

## ✨ Features

- 🔐 **Secure Authentication** (Clerk)
- 🎥 **Real-time Video Conferencing** via WebRTC
- 🔗 **Sharable Meeting Links**
- 📅 **Meeting Scheduler**
- 🧍 **Personal Meeting Room**
- 📁 **Past and Upcoming Meeting Logs**
- 🖥 **Screen Sharing**
- 📱 **Fully Responsive UI**

---

## 🚀 Getting Started Locally

1. **Clone the repository:**
```bash
git clone https://github.com/shubhodeepghosh/Fac2Fac.git
cd Fac2Fac
```

2. **Install dependencies:**
```bash
npm install
```

3. **Add environment variables:**

Create a `.env.local` file in the root:

```env
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your-clerk-key
CLERK_SECRET_KEY=your-secret-key
NEXT_PUBLIC_STREAM_API_KEY=your-getstream-key
STREAM_SECRET_KEY=your-stream-secret
```

4. **Run the development server:**
```bash
npm run dev
```

Then open `http://localhost:3000` in your browser.

---

## 📁 Folder Structure Overview

```
Fac2Fac/
├── app/                  # App Router pages & layouts
├── components/           # All reusable UI components
├── hooks/                # Custom React hooks
├── lib/                  # Utility functions
├── public/               # Static files (icons, images)
├── styles/ or globals.css
├── .env.local            # Local environment secrets
├── tailwind.config.ts    # TailwindCSS config
└── tsconfig.json         # TypeScript config
```

---

## ✅ Project Highlights

- Built with a **production-grade folder structure**
- Focused on **clean UI/UX and performance**
- Uses **latest Next.js 14+ App Router**
- Optimized for **cross-device usage**

---

## 🌐 Live Demo

➡️ [https://fac2fac.vercel.app](https://fac2fac.vercel.app)

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

**Shubhodeep Ghosh**  
🔗 [GitHub – shubhodeepghosh](https://github.com/shubhodeepghosh)

