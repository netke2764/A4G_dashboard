Admin Portal
Overview

Admin portal conference registrations ko view, filter, aur analyze karne ke liye banaya gaya hai. Yeh backend database se real-time data fetch karta hai aur dashboard pe clean UI ke saath display karta hai.

Live URL

Admin Portal: <PLACE YOUR LIVE URL HERE>

Features

Total registrations count

Student registrations count

Professional registrations count

Full table with all submissions

Filter by: All / Student / Professional

Sort by latest registration date

Tech Stack

Frontend: React / Vite / Tailwind (replace if different)

Backend: Node.js + Express

Database: PostgreSQL (replace if different)

Pages
1. Dashboard

Quick stats cards

Auto-refreshing numbers

2. Registrations Table

Columns:

Name

Email

Type

Company (professional only)

Phone

Registration Date

Filter + sort integrated

API Integration

Portal backend se data fetch karta hai using:

Method	Endpoint	Description
GET	/api/stats	Dashboard counts
GET	/api/registrations	Fetch all registrations

(Agar tumhare endpoints alag hai toh replace kar dena.)

Local Setup
cd admin-portal
npm install
npm run dev

Environment Variables
VITE_API_URL=

Folder Structure
admin-portal/
 ├── src/
 │    ├── components/
 │    ├── pages/
 │    ├── api/
 │    └── App.jsx
 └── package.json
