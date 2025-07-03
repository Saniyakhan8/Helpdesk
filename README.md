# 🧩 WeAnalyz Helpdesk UI

This project is built as part of the **ReactJS Internship Assignment** for **WeAnalyz Technologies Pvt. Ltd.** It replicates the provided Figma mockup into a functional React (Next.js) frontend interface.

---

## 🔗 Live Demo

Hosted on **Vercel**:  
👉 [https://weanalyz-helpdesk.vercel.app](https://weanalyz-helpdesk.vercel.app)

---

## 📌 Features Implemented

- 🧭 Sidebar navigation (Dashboard, Create Ticket, My Tickets, My Profile)
- 📊 Dashboard with live ticket status cards
- 📝 Ticket creation form (Create New Ticket)
- 📋 View & update ticket list (My Tickets)
- 👩‍💼 User profile (My Profile)
- 🎨 Fully responsive layout with TailwindCSS
- ✨ Basic animations for a modern UI

---

## 🛠️ Tech Stack

| Tool/Library   | Purpose                             |
|----------------|-------------------------------------|
| Next.js (App Router) | React framework with routing |
| Tailwind CSS   | Styling and layout system           |
| TypeScript     | Type-safe development               |
| Vercel         | Deployment platform                 |

---

## 📁 Folder Structure

weanalyz-working-template/
├── app/
│ ├── layout.tsx # Shared layout with Sidebar
│ ├── page.tsx # Dashboard page
│ ├── globals.css # Tailwind base styles
│ ├── new-ticket/ # Create ticket page
│ ├── tickets/ # My Tickets page
│ ├── profile/ # Profile page
├── components/
│ ├── Sidebar.tsx # Sidebar navigation
│ ├── StatCard.tsx # Dashboard statistic card
│ ├── TicketTable.tsx # Ticket listing table
├── tailwind.config.js # Tailwind setup
├── postcss.config.js # PostCSS for Tailwind
├── package.json # Project metadata and dependencies

yaml
Copy
Edit

---

## 🚀 Getting Started

To run this project locally:

### 1. Clone the repo

```bash
git clone https://github.com/your-username/weanalyz-helpdesk.git
cd weanalyz-helpdesk
2. Install dependencies
npm install
3. Start development server
npm run dev
Open http://localhost:3000 to view it in your browser.

