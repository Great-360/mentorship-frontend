# 🌱 FocusFlow — Personal Focus & Burnout Tracker

FocusFlow is a lightweight, responsive, and minimalist web application designed to help students and knowledge workers track their study or work sessions, monitor focus levels, and understand mental energy dynamics over time.

By shifting the focus from **how long** you work to **how well** you work, FocusFlow encourages self-reflection, helps identify cognitive fatigue early, and builds sustainable, burnout-free productivity habits.

---

## 🚀 Features

### Core Productivity System (MVP)
* **Dynamic Session Timer:** Start, stop, and track real-time focus windows with an elegant active-state UI.
* **Contextual Session Types:** Categorize your effort into distinct high-impact states: `📚 Study`, `🧠 Deep Work`, or `📖 Reading`.
* **Post-Session Energy Tracking:** Log your post-work mental capacity using a localized 1–5 qualitative scaling metric immediately upon session completion.
* **Live Dashboard Metrics:** Monitor key indicators in real-time:
    * **Total Focus Time** (Aggregated into total daily minutes).
    * **Session Counters** (Total focus blocks executed today).
    * **Average Energy Level** (Calculated dynamic average of your cognitive stamina).

### Extended Architecture Features
* **Interactive Energy Profile Chart:** Visualizes your last 8 sessions inside a CSS-driven profile graph, tracking your burnout trends across the day.
* **Recent Activity Logs:** A scrollable live history timeline detailing session types, explicit end-timestamps, and exact durations.
* **Dynamic Streak Retention Engine:** Tracks consecutive daily activity and builds discipline over time.
* **Fluid Dark Mode Support:** Seamless toggling between clean high-contrast light environments and low-strain dark interfaces.
* **Local Infrastructure Autonomy:** Fully standalone client-side tracking with local storage permanence, secure JSON configuration file exports, and system data restoration capabilities.

---

## 🛠️ Architecture & Tech Stack

FocusFlow is architected to require zero configuration, compilation, or web servers. It executes directly in any modern desktop or mobile browser.

* **Markup Language:** HTML5 (semantic, accessible document structure).
* **Styling Engine:** Tailwind CSS (loaded asynchronously via optimized CDN, customized with modern slate and brand-emerald design guidelines).
* **Logic Runtime:** Vanilla JavaScript (ES6+). Handles asynchronous event listening, intervals, standard object mutation tracking, structural UI rendering, and localized JSON file operations.
* **Data Persistence Layer:** Web Storage API (`localStorage`).

---

