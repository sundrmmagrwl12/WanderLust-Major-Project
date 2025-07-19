# WanderLust 🌍

**WanderLust** is a full-stack dynamic **travel booking website** designed for discovering, listing, and reserving travel stays and experiences. It allows users to explore available destinations, make bookings, submit reviews, and manage their travel plans — all in one place.

---

## 🚀 Key Features

- User registration and authentication
- Create, update, and delete listings
- Image uploads via Cloudinary
- Interactive map integration with Leaflet
- Booking system with date validation
- Review and rating functionality
- Email notifications and PDF generation for bookings
- Clean and responsive UI

---

## 🛠️ Tech Stack

- **Backend:** Node.js, Express.js, MongoDB, Mongoose
- **Frontend:** HTML, CSS, EJS (Embedded JavaScript Templates)
- **Authentication:** Passport.js (Session-based login system)
- **File Handling:** Multer, Cloudinary
- **Mapping & Geo:** Mapbox/Leaflet.js
- **Utilities:** PDFKit, Nodemailer

---

## 📂 Folder Structure Overview

- `/routes` – All route files (users, listings, bookings, reviews)
- `/models` – Mongoose schemas for MongoDB
- `/controllers` – Route handler logic
- `/views` – EJS templates for dynamic HTML rendering
- `/public` – Static files (CSS, JS, images)
- `/middleware` – Custom middleware for validation and access control
- `/utils` – Utilities (mailer, PDF generator, cleanup scripts)

---

## 💻 Setup Instructions

1. **Clone the repository**
   ```bash
   git clone <your_repo_url>
   cd WanderLust
