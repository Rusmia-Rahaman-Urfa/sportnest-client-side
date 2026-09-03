# 🏟️ SportNest - Sports Facility Booking Management System

A modern, responsive, and full-stack sports facility booking platform built with Next.js, Better Auth, Tailwind CSS, Node.js, and MongoDB. SportNest allows sports enthusiasts to discover, reserve, and manage bookings for various venues (football turfs, badminton courts, swimming pools, tennis courts, etc.) seamlessly.

---

## 🔗 Project Links

* **Live Demo:** [SportNest Live Site](https://sportnest-client-psi.vercel.app/) 
* **Client Repository:** [GitHub Client Repo](https://github.com/Rusmia-Rahaman-Urfa/sportnest-client-side) 
* **Server Repository:** [GitHub Server Repo](https://github.com/Rusmia-Rahaman-Urfa/sportnest-backend-server) 

---

## 🎯 Purpose & Overview

The primary goal of **SportNest** is to streamline sports reservation management for both facility owners and sports enthusiasts. Facilities can showcase their available time slots, capacities, pricing, and locations, while users can seamlessly search, filter, and book facilities in real time without hassle.

---

## ✨ Key Features

### 🌐 Landing Page & Public Navigation
* **Responsive Landing Page:** Includes an engaging hero banner, featured facilities, and dedicated static sections for user guidance.
* **Public All Facilities Page:** Browsable venue directory accessible to all visitors.
* **Facility Search & Filter:** Search venues by name and filter listings by sport type in real time.
* **Facility Details Page:** In-depth view showcasing venue attributes, pricing, available slots, and booking interfaces.
* **Theme Toggle:** Built-in theme switcher supporting light and dark modes.
* **Framer Motion Animations:** Smooth page transitions, card hover effects, and UI animations.
* **Recruiter-Friendly UI:** Clean, modern, accessible design with custom non-default loading and 404 Not Found pages.

### 🔐 Better Auth Authentication
* **Multi-Method Login:** Support for Email/Password registration/login and Google OAuth integration via Better Auth.
* **Private Route Protection:** Route guards that restrict unauthorized access to booking systems and management portals.

### 👤 Booking & User Dashboard
* **Interactive Booking System:** Date picker and real-time time slot selection with automatic price calculation.
* **My Bookings Page:** Dashboard for users to track reserved venues and booking statuses.
* **Cancel Booking:** Option to cancel active reservations with an interactive confirmation prompt.
* **Toast Notifications:** Instant feedback via toast alerts for all success and error actions using Sonner.

### 🏢 Facility Management (Owner Features)
* **Add Facility Form:** Form for authenticated owners to list new venues with automatic owner email binding.
* **Manage My Facilities:** Centralized portal for facility owners to view and maintain listed properties.
* **Edit & Delete Capabilities:** Full CRUD functionality allowing owners to modify venue details or safely delete listings.

---

## Technologies Used

- Next.js
- React
- Tailwind CSS
- HeroUI
- Better Auth
- MongoDB
- Framer Motion
- React Hot Toast
- Lucide React
- React Icons
- Next Themes

---

## 📦 NPM Packages Used

- `next`
- `react`
- `react-dom`
- `better-auth`
- `@better-auth/mongo-adapter`
- `@heroui/react`
- `@heroui/styles`
- `framer-motion`
- `next-themes`
- `mongodb`
- `react-hot-toast`
- `lucide-react`
- `react-icons`
- `axios`
- `tailwindcss`
- `eslint`

---

## Environment Variables

Create a `.env.local` file in the client project and add:

```env
NEXT_PUBLIC_SERVER_URL=your_server_url
BETTER_AUTH_URL=your_client_url
BETTER_AUTH_SECRET=your_better_auth_secret
MONGODB_URI=your_mongodb_connection_string
GOOGLE_CLIENT_ID=your_google_client_id
GOOGLE_SECRET=your_google_client_secret

























