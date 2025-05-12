# NEU OccuTrack 
A real-time classroom and facility occupancy tracking system for New Era University. This web application enables streamlined room reservations, real-time room status updates, user-role-based access, and centralized announcements for academic institutions.

Built with React.js, Supabase, and Tailwind CSS. Deployed via Lovable.

# 📌 Key Features
🕒 Real-Time Room Status – Instantly view if rooms are occupied, vacant, or under maintenance

📅 Room Reservation & Class Scheduling – Admins, Faculty, and Super Admins can reserve and assign rooms

📢 Announcements Board – Super Admins and Admins can post school-wide messages

🔐 Secure Login – Google Sign-In and Lovable Auth with role-based access

🛠️ Room Maintenance Control – Super Admins can mark rooms as under maintenance

📊 Dashboard Analytics – View room usage statistics and user activity (Admins, Super Admins)

🏢 Room & Building Management – Admin-level tools to configure classrooms and facilities

👥 User Management – Role assignment, account approval, and permission settings

# 🏗️ Tech Stack
Frontend: React.js, Tailwind CSS

Backend: Supabase (PostgreSQL DB, Auth, Realtime)

Authentication: Google Sign-In, Lovable Auth

Deployment: Lovable (Cloud-based hosting)

Version Control: GitHub

# 🌐 Accessing the App
NEU OccuTrack is accessed through your institutional site hosted on Lovable. There is no need to clone or install dependencies locally.

➡️ Visit the deployed site:
🔗 https://occutrack.lovable.app/

# Project Structure
/occutrack
├── public/                     → Static assets (favicon, index.html, etc.)
├── src/                        → Application source code
│   ├── components/             → Reusable React components
│   ├── pages/                  → Route-based views (Dashboard, Login, etc.)
│   ├── services/               → API calls and Supabase logic
│   ├── hooks/                  → Custom React hooks
│   ├── context/                → Auth and role context providers
│   ├── utils/                  → Helper functions and utilities
│   ├── App.tsx                 → Root component
│   └── index.tsx              → Entry point
├── .env                        → Environment variables (not pushed to GitHub)
├── tailwind.config.js          → Tailwind configuration
├── package.json                → Dependencies and scripts
└── README.md                   → Project documentation


👥 Developers
Patrick Ace Galima

Vina Marie Solitario

Kathrine Anne Dato

Ronne Rae Mayuga

Rejina Jackie Ablao



