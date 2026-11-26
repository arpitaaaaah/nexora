# LPU Campus Room Availability & Booking Portal

A single-page, client-side web application built for **Lovely Professional University (LPU)** (Department of Computer Science & Engineering, Section K3P26SP) to manage classroom allocations, live room schedules, and campus facility support tickets using pure HTML5, CSS3, and Vanilla JavaScript.

---

## Features

* **Role-Based Portal Authentication:** Separate login workflows and dedicated workspaces for **Students** and **Admins/Coordinators**, including 1-click demo login buttons and session persistence.
* **Live Dashboard Metrics:** Real-time counters for Total Campus Rooms, Available Rooms, Pending Bookings, and Open Support Tickets.
* **Room & Lab Catalogue:** Filter classrooms, computer labs, and seminar halls by room type, availability status (`Available` / `Occupied`), or search keyword, plus a live campus timetable overview.
* **Smart Booking Validation:**
  * **Capacity Check:** Prevents bookings where expected attendees exceed room seating capacity.
  * **Clash Prevention:** Blocks duplicate or overlapping bookings for the same room, date, and time slot.
* **Classroom Support Ticketing:** Allows students to report projector, lab PC, Wi-Fi, electrical, or furniture issues with `Normal` or `Urgent` priority.
* **Admin Approval & Real-Time Availability Sync:** Approving a booking automatically marks the room as `Occupied`, updates its scheduled window, and decrements the `Available Rooms` counter across sessions via `localStorage`[cite: 1].

---

## Tech Stack

* **Frontend:** HTML5, CSS3 (Custom Properties, CSS Grid, Flexbox), Vanilla JavaScript (ES6+)
* **Icons & Typography:** Font Awesome 6, Google Fonts (`Plus Jakarta Sans` & `Inter`)
* **Storage:** Browser `localStorage` (zero backend dependencies)[cite: 1]

---

## Demo Credentials

| Role | Username / ID | Password |
| :--- | :--- | :--- |
| **Student** | `student` (or any 6–10 digit Reg. No.) | `student123` |
| **Admin** | `admin` | `admin123` |[cite: 1]

---

