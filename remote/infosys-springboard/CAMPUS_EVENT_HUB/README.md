<div align="center">

<br/>

```
 ██████╗ █████╗ ███╗   ███╗██████╗ ██╗   ██╗███████╗
██╔════╝██╔══██╗████╗ ████║██╔══██╗██║   ██║██╔════╝
██║     ███████║██╔████╔██║██████╔╝██║   ██║███████╗
██║     ██╔══██║██║╚██╔╝██║██╔═══╝ ██║   ██║╚════██║
╚██████╗██║  ██║██║ ╚═╝ ██║██║     ╚██████╔╝███████║
 ╚═════╝╚═╝  ╚═╝╚═╝     ╚═╝╚═╝      ╚═════╝ ╚══════╝

███████╗██╗   ██╗███████╗███╗   ██╗████████╗██╗  ██╗██╗   ██╗██████╗
██╔════╝██║   ██║██╔════╝████╗  ██║╚══██╔══╝██║  ██║██║   ██║██╔══██╗
█████╗  ██║   ██║█████╗  ██╔██╗ ██║   ██║   ███████║██║   ██║██████╔╝
██╔══╝  ╚██╗ ██╔╝██╔══╝  ██║╚██╗██║   ██║   ██╔══██║██║   ██║██╔══██╗
███████╗ ╚████╔╝ ███████╗██║ ╚████║   ██║   ██║  ██║╚██████╔╝██████╔╝
╚══════╝  ╚═══╝  ╚══════╝╚═╝  ╚═══╝   ╚═╝   ╚═╝  ╚═╝ ╚═════╝ ╚═════╝
```

### *The inter-college event platform your campus actually deserves.*

<br/>

[![Status](https://img.shields.io/badge/STATUS-ACTIVE%20DEVELOPMENT-22c55e?style=for-the-badge&labelColor=0f172a)](/)
[![Stack](https://img.shields.io/badge/MERN-FULL%20STACK-20232A?style=for-the-badge&logo=mongodb&logoColor=4DB33D&labelColor=0f172a)](/)
[![Built At](https://img.shields.io/badge/INFOSYS%20SPRINGBOARD-INTERNSHIP%206-0066CC?style=for-the-badge&labelColor=0f172a)](/)
[![License](https://img.shields.io/badge/LICENSE-MIT-f59e0b?style=for-the-badge&labelColor=0f172a)](./LICENSE)

<br/>

> **Most college event systems are a WhatsApp forward and a Google Form.**
> **We built something better.**

<br/>

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind%20CSS-0F172A?style=flat-square&logo=tailwindcss&logoColor=38BDF8)
![Node.js](https://img.shields.io/badge/Node.js-215732?style=flat-square&logo=node.js&logoColor=68A063)
![Express](https://img.shields.io/badge/Express-111111?style=flat-square&logo=express&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-013220?style=flat-square&logo=mongodb&logoColor=4DB33D)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=flat-square&logo=cloudinary&logoColor=white)
![Nodemailer](https://img.shields.io/badge/Nodemailer-EA4335?style=flat-square&logo=gmail&logoColor=white)

</div>

---

## 📚 Table of Contents

1. [🔥 Why CampusEventHub?](#-why-campuseventhub)
2. [🎬 UI Snapshots](#-ui-snapshots)
3. [✨ Features](#-features)
4. [🎭 Roles & Permissions](#-roles--permissions)
5. [🏗️ Architecture](#-architecture)
6. [🛠️ Tech Stack](#-tech-stack)
7. [📂 Folder Structure](#-folder-structure)
8. [🧩 Local Setup](#-local-setup)
9. [🔐 Environment Variables](#-environment-variables)
10. [📡 API Reference](#-api-reference)
11. [🗄️ Database Schema](#-database-schema)
12. [📅 Project Timeline](#-project-timeline)
13. [🔮 Roadmap](#-roadmap)
14. [📊 Project Status](#-project-status)
15. [👥 Developers](#-developers)
16. [📄 License](#-license)

---

## 🔥 Why CampusEventHub?

Events are easy to miss. Posts vanish, forms close, and paper lists disappear.

CampusEventHub makes events visible and manageable. Students can find and sign up. College admins create, approve, and run events without juggling spreadsheets. Superadmins get a single place to review approvals and audit actions.

It’s built for teams that want simple, reliable event workflows — not another chaotic group chat.

Three roles. One platform. No more WhatsApp forwards.

Built during **Infosys Springboard Internship 6**.

---

## 🎬 UI Snapshots

> Screenshots speak louder than docs. Place yours here once the UI is ready.

<br/>

### 🏠 Student Dashboard
<!-- ADD SCREENSHOT: Student dashboard — event discovery & registration view -->
> 📸 **[ Place screenshot here — Student dashboard ]**

<br/>

### 🏫 College Admin Panel
<!-- ADD SCREENSHOT: College admin — event management & registrations table -->
> 📸 **[ Place screenshot here — College admin panel ]**

<br/>

### 🛡️ Superadmin Console
<!-- ADD SCREENSHOT: Superadmin — platform overview, approvals & audit logs -->
> 📸 **[ Place screenshot here — Superadmin console ]**

<br/>

### 📋 Event Detail Page
<!-- ADD SCREENSHOT: Event detail page — description, registration CTA, comments -->
> 📸 **[ Place screenshot here — Event detail page ]**

<br/>

### 💬 Comments & Feedback
<!-- ADD SCREENSHOT: Comments section with pinned replies & feedback ratings -->
> 📸 **[ Place screenshot here — Comments & feedback section ]**

> 💡 *To add screenshots: save images to `docs/screenshots/` and update the paths above with `![Description](./docs/screenshots/your-image.png)`*

---

## ✨ Features

| Feature | Details |
|---|---|
| 🔐 **JWT Auth** | HttpOnly cookie-based auth with email verification and password reset |
| 🏫 **Multi-Tenant** | Each college is fully isolated — its own admins, events, and students |
| 📋 **Event Lifecycle** | Draft → Pending → Approved → Paused / Cancelled with staged update support |
| 🎫 **Waitlist System** | Auto-promotes students when a slot opens — no manual intervention needed |
| 📊 **Role Dashboards** | Separate, purpose-built dashboards for students, college admins, and superadmins |
| 💬 **Comments** | Event-level discussion with pinning, likes, and official admin replies |
| ⭐ **Feedback** | Post-attendance ratings with analytics and moderation |
| 📤 **Export** | Download registration data per event as structured output |
| 🖼️ **Media Uploads** | Cloudinary-backed banner images for events |
| 📧 **Email Notifications** | Transactional emails via Nodemailer for verification, approvals, and updates |
| 🛡️ **Audit Logs** | Full audit trail for every superadmin and college admin action |
| 🔍 **Event Discovery** | Students can browse, filter, and search events across colleges |

---

## 🎭 Roles & Permissions

```
┌─────────────────────────────────────────────────────────┐
│                      SUPERADMIN                         │
│  Platform governance · College & admin approvals        │
│  Global event review · Analytics · Audit logs           │
├─────────────────────────────────────────────────────────┤
│                    COLLEGE ADMIN                         │
│  Create & manage events · Approve student registrations │
│  Track registrations · Mark attendance · View feedback  │
├─────────────────────────────────────────────────────────┤
│                       STUDENT                           │
│  Discover events · Register / Join waitlist             │
│  Track participation · Submit feedback · Comment        │
└─────────────────────────────────────────────────────────┘
```

### Permission Matrix

| Action | Student | College Admin | Superadmin |
|---|:---:|:---:|:---:|
| Browse & register for events | ✅ | ✅ | ✅ |
| Submit feedback & comments | ✅ | ✅ | ✅ |
| Create / manage events | ❌ | ✅ | ✅ |
| Approve registrations & attendance | ❌ | ✅ | ✅ |
| Approve / reject events | ❌ | ❌ | ✅ |
| Approve / reject colleges & admins | ❌ | ❌ | ✅ |
| View audit logs | ❌ | ❌ | ✅ |
| Platform-wide analytics | ❌ | ❌ | ✅ |

---

## 🏗️ Architecture

```
                          ┌─────────────────┐
                          │   React + Vite  │
                          │  (Tailwind CSS) │
                          └────────┬────────┘
                                   │ HTTPS / REST
                          ┌────────▼────────┐
                          │  Express.js API │
                          │   (Node.js)     │
                          └──┬─────────┬───┘
                             │         │
               ┌─────────────▼──┐  ┌───▼──────────────┐
               │   MongoDB       │  │    Cloudinary     │
               │  (Mongoose)     │  │  (Media Storage)  │
               └────────────────┘  └──────────────────┘
                                            │
                                   ┌────────▼───────┐
                                   │   Nodemailer   │
                                   │  (SMTP Email)  │
                                   └────────────────┘
```

**Key Design Decisions:**

- **HttpOnly Cookies** for JWT — not localStorage. XSS can't steal your tokens.
- **Multi-tenant isolation** — every query is scoped to a college. No data bleeds across tenants.
- **Staged event updates** — edits to approved events go into a `pendingUpdate` field and require re-approval, so live events can't be silently mutated.
- **Waitlist automation** — slot opens → next in queue gets notified and auto-promoted. No admin action needed.

---

## 🛠️ Tech Stack

| Layer | Technology | Why |
|---|---|---|
| **Frontend** | React 18 + Vite + Tailwind CSS | Fast DX, instant HMR, utility-first styling |
| **Backend** | Node.js + Express.js | Lightweight, unopinionated, perfect for REST APIs |
| **Database** | MongoDB + Mongoose | Flexible schema for multi-tenant event data |
| **Auth** | JWT + HttpOnly Cookies | Secure, stateless, XSS-resistant |
| **Media** | Cloudinary | CDN-backed image uploads with transformations |
| **Email** | Nodemailer | Transactional email via SMTP |

---

## 📂 Folder Structure

```
CampusEventHub/
├── frontend/                  # React + Vite + Tailwind CSS
│   ├── public/
│   └── src/
│       ├── api/               # Axios config & all API call functions
│       ├── assets/            # Images, icons, logo
│       ├── components/        # Reusable UI — Navbar, Cards, Modals, etc.
│       ├── pages/             # Route-level pages organized by role
│       ├── context/           # Auth context & global state
│       ├── hooks/             # Custom React hooks
│       ├── App.jsx
│       └── main.jsx
│
├── backend/
│   └── src/
│       ├── config/            # DB connection, Cloudinary config
│       ├── controllers/       # Business logic per feature
│       ├── middleware/        # Auth guard, role checks, error handler
│       ├── models/            # Mongoose schemas
│       ├── routes/            # API route definitions
│       └── utils/             # Helpers, email templates
│   └── server.js              # App entry point
│
├── LICENSE
└── README.md
```

---

## 🧩 Local Setup

### Prerequisites

- [Node.js 20+](https://nodejs.org/)
- [npm](https://www.npmjs.com/)
- [MongoDB](https://www.mongodb.com/) — local or Atlas
- [Git](https://git-scm.com/)
- A [Cloudinary](https://cloudinary.com/) account (free tier works)
- An SMTP email account (Gmail with App Password works fine)

---

### Step 1 — Clone the Repository

```bash
git clone https://github.com/springboardmentor212/CampusEventHub_Team4
cd CampusEventHub
```

---

### Step 2 — Create Your Branch

```bash
git checkout -b feature/<your-feature-name>
```

---

### Step 3 — Backend Setup

```bash
cd backend
npm install
```

Create a `.env` file inside `backend/` — see [Environment Variables](#-environment-variables) for the full list.

```bash
npm run dev
```

> ✅ Backend running at `http://localhost:5000`

---

### Step 4 — Frontend Setup

```bash
cd frontend
npm install
```

Create a `.env` inside `frontend/`:

```env
VITE_API_URL=http://localhost:5000/api
```

```bash
npm run dev
```

> ✅ Frontend running at `http://localhost:5173`

---

### Step 5 — Development Workflow

```bash
git add .
git commit -m "feat: your meaningful commit message"
git push origin feature/<your-feature-name>
```

Open a PR from your feature branch → `dev`.

> ⚠️ Always pull latest `dev` or `main` before starting to avoid merge conflicts.

---

## Run with Docker (quick)

We included Dockerfiles for the frontend and backend and a `docker-compose.yml` to run Mongo, the API, and the static site locally.

Quick start (Docker installed):

```bash
docker compose up --build
```

The `DOCKER.md` file has more details on environment variables and debugging.

## CI / CD (brief)

This repo has a GitHub Actions workflow at `.github/workflows/ci.yml`. It runs backend tests, builds the frontend, and builds Docker images. See `CI_CD.md` for how to enable image publishing or extend the pipeline.


## 🔐 Environment Variables

### Backend — `backend/.env`

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secure_secret
NODE_ENV=development
FRONTEND_URL=http://localhost:5173

EMAIL_HOST=smtp.example.com
EMAIL_PORT=587
EMAIL_USER=your_email@example.com
EMAIL_PASS=your_email_password
EMAIL_FROM=your_email@example.com

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

APP_NAME=CampusEventHub
APP_VERSION=1.0.0
```

| Variable | Description |
|---|---|
| `PORT` | Server port (default: `5000`) |
| `MONGO_URI` | MongoDB connection string |
| `JWT_SECRET` | Secret key for signing JWTs — use something long and random |
| `NODE_ENV` | `development` or `production` |
| `FRONTEND_URL` | Frontend origin for CORS |
| `EMAIL_HOST` | SMTP host |
| `EMAIL_PORT` | SMTP port |
| `EMAIL_USER` | Email address used to send |
| `EMAIL_PASS` | Email password or app password |
| `EMAIL_FROM` | Sender display address |
| `CLOUDINARY_CLOUD_NAME` | Your Cloudinary cloud name |
| `CLOUDINARY_API_KEY` | Cloudinary API key |
| `CLOUDINARY_API_SECRET` | Cloudinary API secret |

### Frontend — `frontend/.env`

| Variable | Description |
|---|---|
| `VITE_API_URL` | Base URL for all API calls |

---

## 📡 API Reference

**Base URL (local):** `http://localhost:5000/api`

### Standard Response Format

```json
// Success
{ "success": true, "message": "...", "data": {} }

// Error
{ "success": false, "message": "Something went wrong" }
```

---

### 🔑 Auth — `/api/auth`

<details>
<summary><b>Public Endpoints</b></summary>

| Method | Endpoint | Description |
|---|---|---|
| `POST` | `/register` | Register student or college admin |
| `POST` | `/login` | Sign in, sets HttpOnly cookie |
| `GET` | `/logout` | Clear session |
| `GET` | `/verify-email/:token` | Verify account email |
| `POST` | `/resend-verification` | Resend verification email |
| `POST` | `/request-password-reset` | Send password reset email |
| `POST` | `/reset-password` | Reset password via token |

</details>

<details>
<summary><b>Authenticated Endpoints</b></summary>

| Method | Endpoint | Description |
|---|---|---|
| `GET` | `/profile` | Get current user profile |
| `PUT` | `/profile` | Update profile |
| `PATCH` | `/profile` | Partial profile update |
| `POST` | `/change-password` | Change password |

</details>

<details>
<summary><b>Admin Endpoints</b></summary>

| Method | Endpoint | Description |
|---|---|---|
| `GET` | `/admin/pending-users` | Pending users for superadmin review |
| `GET` | `/admin/all-users` | All users |
| `PATCH` | `/admin/approve-user/:id` | Approve a user |
| `DELETE` | `/admin/reject-user/:id` | Reject a user |
| `POST` | `/admin/create-student` | Create student as admin |
| `GET` | `/college/pending-students` | Pending students for college admin |

</details>

---

### 🏫 Colleges — `/api/colleges`

<details>
<summary><b>Endpoints</b></summary>

| Method | Endpoint | Description |
|---|---|---|
| `GET` | `/` | List all colleges |
| `GET` | `/:id` | Get one college |
| `POST` | `/` | Create a college |
| `PUT` | `/:id` | Update a college |
| `DELETE` | `/:id` | Delete a college |
| `GET` | `/:id/has-active-admin` | Check if college has an active admin |
| `GET` | `/:collegeId/users` | List users for a college |

</details>

---

### 📅 Events — `/api/events`

<details>
<summary><b>Endpoints</b></summary>

| Method | Endpoint | Description |
|---|---|---|
| `GET` | `/` | List events |
| `GET` | `/:id` | Get event details |
| `POST` | `/create` | Create event (college admin only) |
| `GET` | `/my/events` | Get admin's own events |
| `PATCH` | `/:id` | Update event |
| `PATCH` | `/:id/cancel` | Cancel event |
| `PATCH` | `/:id/pause` | Pause event |
| `PATCH` | `/:id/resume` | Resume paused event |
| `DELETE` | `/:id` | Delete event |
| `GET` | `/admin/pending-events` | Events awaiting superadmin review |
| `PATCH` | `/:id/approve` | Approve event |
| `DELETE` | `/:id/reject` | Reject event |

</details>

---

### 🎫 Registrations — `/api/registrations`

<details>
<summary><b>Endpoints</b></summary>

| Method | Endpoint | Description |
|---|---|---|
| `POST` | `/register/:eventId` | Register for event or join waitlist |
| `GET` | `/my` | Get own registrations |
| `GET` | `/:id` | Get a specific registration |
| `PATCH` | `/:id/confirm-waitlist` | Confirm a promoted waitlist spot |
| `DELETE` | `/:id` | Cancel registration |
| `GET` | `/event/:eventId` | List all registrations for an event |
| `GET` | `/event/:eventId/export` | Export registrations |
| `PATCH` | `/:id/approve` | Approve a registration |
| `PATCH` | `/:id/reject` | Reject a registration |
| `PATCH` | `/:id/attendance` | Mark attendance |
| `GET` | `/event/:eventId/waitlist` | Get waitlist for an event |
| `GET` | `/stats/:eventId` | Registration stats for an event |

</details>

---

### 💬 Comments — `/api/comments`

<details>
<summary><b>Endpoints</b></summary>

| Method | Endpoint | Description |
|---|---|---|
| `POST` | `/` | Post a comment |
| `GET` | `/event/:eventId` | Get comments for an event |
| `PATCH` | `/:id/like` | Like / unlike a comment |
| `PATCH` | `/:id/pin` | Pin / unpin a comment |
| `POST` | `/:id/official-reply` | Add an official admin reply |
| `DELETE` | `/:id` | Delete a comment |
| `GET` | `/admin/moderation` | Moderation queue |

</details>

---

### ⭐ Feedback — `/api/feedback`

<details>
<summary><b>Endpoints</b></summary>

| Method | Endpoint | Description |
|---|---|---|
| `POST` | `/` | Submit feedback for an event |
| `GET` | `/event/:eventId` | Get feedback for an event |
| `GET` | `/my` | Get own feedback submissions |
| `GET` | `/admin/analytics` | Platform feedback analytics |
| `GET` | `/college/mine` | College admin feedback view |

</details>

---

### 📊 Dashboards — `/api/dashboards`

<details>
<summary><b>Endpoints</b></summary>

| Method | Endpoint | Description |
|---|---|---|
| `GET` | `/student` | Student dashboard data |
| `GET` | `/college-admin` | College admin dashboard data |
| `GET` | `/super-admin` | Superadmin dashboard data |
| `GET` | `/analytics` | Shared analytics |
| `GET` | `/signals` | Platform signal summary |

</details>

---

## 🗄️ Database Schema

### Relationships

```
College
 ├── Users (students + admins)
 └── Events

User
 ├── Registrations
 ├── Feedback
 ├── Comments
 └── AdminLogs

Event
 ├── Registrations
 ├── Feedback
 └── Comments
```

### Collections Overview

<details>
<summary><b>Users</b></summary>

| Field | Type | Notes |
|---|---|---|
| `username` | String | Unique |
| `email` | String | Unique, used for login |
| `password` | String | Bcrypt hashed |
| `firstName`, `lastName` | String | Display name |
| `role` | String | `student` / `college_admin` / `admin` |
| `college` | ObjectId | Ref → College |
| `isVerified` | Boolean | Email verification status |
| `isApproved` | Boolean | Admin approval status |
| `isActive` | Boolean | Account active state |
| `isBlocked` | Boolean | Moderation flag |

</details>

<details>
<summary><b>Colleges</b></summary>

| Field | Type | Notes |
|---|---|---|
| `name` | String | College full name |
| `code` | String | Short identifier |
| `location` | String | Campus / city |
| `isActive` | Boolean | Tenant active status |

</details>

<details>
<summary><b>Events</b></summary>

| Field | Type | Notes |
|---|---|---|
| `title`, `description` | String | Event content |
| `category`, `location` | String | Metadata |
| `startDate`, `endDate` | Date | Event schedule |
| `maxParticipants` | Number | Capacity cap |
| `status` | String | `draft` / `pending` / `approved` / `paused` / `cancelled` |
| `pendingUpdate` | Mixed | Staged edit payload awaiting re-approval |
| `college` | ObjectId | Ref → College |
| `bannerImage` | String | Cloudinary URL |

</details>

<details>
<summary><b>Registrations</b></summary>

| Field | Type | Notes |
|---|---|---|
| `event` | ObjectId | Ref → Event |
| `student` | ObjectId | Ref → User |
| `status` | String | `approved` / `waitlisted` / `attended` / `cancelled` |
| `waitlistPosition` | Number | Position in queue |

</details>

<details>
<summary><b>Comments</b></summary>

| Field | Type | Notes |
|---|---|---|
| `event` | ObjectId | Ref → Event |
| `author` | ObjectId | Ref → User |
| `content` | String | Comment body |
| `parentComment` | ObjectId | Thread / reply reference |
| `isPinned` | Boolean | Admin-pinned status |
| `likesCount` | Number | Reaction count |

</details>

<details>
<summary><b>Feedback</b></summary>

| Field | Type | Notes |
|---|---|---|
| `event` | ObjectId | Ref → Event |
| `student` | ObjectId | Ref → User |
| `rating` | Number | Numeric score |
| `comment` | String | Written feedback |

</details>

<details>
<summary><b>AdminLogs</b></summary>

| Field | Type | Notes |
|---|---|---|
| `admin` | ObjectId | Ref → User |
| `action` | String | Action performed |
| `targetType` | String | Entity type (event, user, college) |
| `targetId` | ObjectId | Entity reference |
| `details` | Mixed | Structured context / metadata |

</details>

---

## 📅 Project Timeline

```
Phase 1 — Planning & Design          ██████████  ✅ Done
  └─ Requirements, ERD, Figma prototypes, role mapping

Phase 2 — Auth & Multi-Tenancy       ██████████  ✅ Done
  └─ JWT auth, email verification, college isolation, role guards

Phase 3 — Event Lifecycle            ██████████  ✅ Done
  └─ Full CRUD, status machine, staged updates, Cloudinary uploads

Phase 4 — Registrations & Waitlist   ██████████  ✅ Done
  └─ Register, waitlist queue, auto-promotion, attendance marking

Phase 5 — Comments & Feedback        ██████████  ✅ Done
  └─ Threaded comments, pinning, likes, post-event ratings

Phase 6 — Dashboards & Analytics     ██████████  ✅ Done
  └─ Role-specific dashboards, export, audit logs, signal summary

Phase 7 — Testing & Polish           ████░░░░░░  🔄 In Progress
  └─ Edge case fixes, UI polish, error handling, responsive tweaks

Phase 8 — Deployment                 ░░░░░░░░░░  📌 Upcoming
  └─ Production hosting, env hardening, final demo
```

---

## 🔮 Roadmap

Features planned for future iterations beyond the internship scope:

| Feature | Priority | Status |
|---|---|---|
| 🔔 Real-time notifications (Socket.io) | High | 📌 Planned |
| 📱 Mobile-responsive PWA | High | 📌 Planned |
| 🗓️ Calendar integration (Google Calendar sync) | Medium | 📌 Planned |
| 📲 Push notifications | Medium | 📌 Planned |
| 🌐 Public event discovery page (no login required) | Medium | 📌 Planned |
| 📈 Advanced analytics with charts | Medium | 📌 Planned |
| 🤝 Inter-college collaboration events | Low | 💡 Idea |
| 🤖 AI-powered event recommendations | Low | 💡 Idea |
| 🎟️ QR code-based attendance | Low | 💡 Idea |
| 🌍 Multi-language support | Low | 💡 Idea |

---

## 📊 Project Status

```
Overall Completion     ████████████████████░░  ~88%
```

| Module | Status |
|---|---|
| Authentication & Authorization | ✅ Complete |
| Multi-Tenant College Isolation | ✅ Complete |
| Event Lifecycle Management | ✅ Complete |
| Registration & Waitlist System | ✅ Complete |
| Comments & Feedback | ✅ Complete |
| Dashboards (all 3 roles) | ✅ Complete |
| Email Notifications | ✅ Complete |
| Media Uploads (Cloudinary) | ✅ Complete |
| Audit Logs | ✅ Complete |
| Export | ✅ Complete |
| UI Polish & Responsiveness | 🔄 In Progress |
| End-to-End Testing | 🔄 In Progress |
| Production Deployment | 📌 Upcoming |

> **Current Phase:** Final polish, testing edge cases, and preparing for production deployment.

---

## 👥 Developers

Built with 💙 during **Infosys Springboard Internship 6**.

<table>
  <tr>
    <td align="center" width="50%">
      <b>UDAY</b><br/>
      <sub>Frontend Lead · Backend · Architecture · Figma Design</sub><br/><br/>
      Architected the full system — database design, API structure, multi-tenant logic, and the entire frontend. Led Figma prototyping and design decisions from day one.<br/><br/>
      <a href="https://github.com/udaycodespace">
        <img src="https://img.shields.io/badge/GitHub-udaycodespace-181717?style=flat-square&logo=github"/>
      </a>
    </td>
    <td align="center" width="50%">
      <b>Gayatri</b><br/>
      <sub>Backend Developer</sub><br/><br/>
      Contributed to backend development, building out controllers, routes, and data handling for key platform features.<br/><br/>
      <a href="https://github.com/Gayatri-3168">
        <img src="https://img.shields.io/badge/GitHub-Gayatri--3168-181717?style=flat-square&logo=github"/>
      </a>
    </td>
  </tr>
</table>

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](./LICENSE) file for details.

You're free to use, modify, and distribute this project. Attribution is appreciated but not required.

---

<div align="center">

<br/>

*Built with* 💙 *during* **Infosys Springboard Internship 6**

<br/>

![Made with React](https://img.shields.io/badge/Made%20with-React%20%2B%20Node.js-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
&nbsp;
![Powered by MongoDB](https://img.shields.io/badge/Powered%20by-MongoDB-013220?style=for-the-badge&logo=mongodb&logoColor=4DB33D)
&nbsp;
![Built at Infosys](https://img.shields.io/badge/Built%20at-Infosys%20Springboard-0066CC?style=for-the-badge)

<br/>

*⭐ Star this repo if it helped you or inspired you.*

</div>