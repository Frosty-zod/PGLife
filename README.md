# 🏠 PGLife

**Internshala Full Stack Web Development Course — Capstone Project**

A PG (Paying Guest) accommodation listing and search platform for students, built as part of the Internshala Full Stack Web Development course.

---

## 🎯 Project Overview
PGLife lets students explore, search, and shortlist PG accommodations across cities. Built end-to-end: database design, PHP backend, AJAX-driven UI, and a React component for the property listing.

## 🛠️ Tech Stack
- **Frontend:** HTML, CSS, Bootstrap 4, JavaScript, React
- **Backend:** PHP (procedural)
- **Database:** MySQL
- **AJAX:** jQuery

## ✅ Features
- Signup / login / logout (AJAX, no page reload)
- City-based search with gender and budget filters
- Property listing (React component) and detail pages with image gallery, amenities, and ratings
- Mark / unmark properties as "interested" (AJAX)
- Responsive design across devices

## 🗄️ Database
Schema: `pglife.sql` (in this repo)
Tables: `users`, `properties`, `cities`, `amenities`, `properties_amenities`, `interested_users_properties`, `testimonials`

## 🚀 Local Setup
1. Clone this repo into your XAMPP `htdocs` folder
2. Create a `pglife` database in phpMyAdmin, import `pglife.sql`
3. In `react-app/`, run `npm install` then `npm run build`
4. Start Apache + MySQL in XAMPP, visit `localhost/PGLife`

## 🔒 Security
SQL queries use prepared statements, passwords are hashed with bcrypt (`password_hash`), and output is escaped to prevent XSS.

## 🌐 Live Demo
 [pglifeweb.infinityfreeapp.com](https://pglifeweb.infinityfreeapp.com)

## 📜 Certificates
- [Internshala Full Stack Web Development Certificate](Full%20Stack%20Web%20Development%20Certificate.pdf)
- NSDC Certificate — coming soon

---
*Built by Abhishek Rawat as part of the Internshala Full Stack Web Development course.*
