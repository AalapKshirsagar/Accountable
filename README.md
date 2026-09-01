# Accountable  - Taxi Driver Work Tracker

 **The Story:** My mom is a taxi driver in Antwerp. For years, she tracked her shifts, trips, and earnings with **Excel spreadsheets and paper notes**. No real-time tracking. Lost data. Hours lost trying to remember what happened last week. I built this to fix that.
 
**Accountable** is a full-stack web app that lets drivers like her:
- ✅ Log in and see today's activity instantly
- ✅ Add trips in seconds (pickup → dropoff → fare)
- ✅ View all trips by date or week
- ✅ Auto-calculate daily earnings
- ✅ Search history (when did I take that airport run?)
- ✅ Works on phone or desktop
No spreadsheets. No paper. Just simple, real-time tracking.
 
## 🛠 Tech Stack
 
**Frontend:** React 18 + Vite + Tailwind CSS (responsive, fast)  
**Backend:** Java 17 + Spring Boot 3.2 + PostgreSQL (robust, scalable)  
**Authentication:** JWT tokens (secure)  
**Deployment:** Vercel (frontend) + Railway/Render (backend)
 
**Status:** MVP (Minimum Viable Product) — Core features working, ship-ready
 
---
 
## ✨ Features (What Drivers See)
 
### Frontend (React)
- **Login/Register** — Simple email + password setup
- **Dashboard** — Today's trips at a glance, total earnings
- **Add Trip** — Form with pickup, dropoff, distance, fare (30 seconds)
- **Trip History** — All trips with date filter
- **Search** — Find trips by date range or location
- **Start/End Shift** — One-click shift management
- **Responsive** — Works on phone, tablet, desktop
### Backend (Spring Boot)
- JWT authentication (secure, stateless)
- Auto-calculated earnings per day/shift
- Trip count tracking
- Date range filtering
- Data persistence in PostgreSQL
