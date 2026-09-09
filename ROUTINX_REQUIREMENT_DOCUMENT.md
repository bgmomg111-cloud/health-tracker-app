# RoutinX: Comprehensive Product Requirement Document (PRD) & Specification
**Project Name:** RoutinX Daily Tracker & Expense Manager  
**Version:** 2.5.0  
**Document Status:** Complete & Production-Ready  

---

## 1. Executive Summary & Vision Statement
RoutinX is a next-generation web application combining daily routine logging, expense tracking (food, drinks, travel, trekking, shopping), hydration & workout monitoring, and community wellness sharing into a single immersive 3D dashboard.

---

## 2. Key Modules & Functional Requirements

### 2.1 User Authentication & 2FA Security
- **Multi-Mode Access:** Google OAuth 2.0 and instant Guest Access mode.
- **Two-Factor Authentication (2FA):** Biometric and TOTP cryptographic authentication for financial privacy.
- **Zero-Knowledge Architecture:** Strict privacy controls with client-side encrypted local storage.

### 2.2 Financial & Expense Tracking (3D Light Blue & White Theme)
- **Categorized Transaction Logging:** Food & Dining, Beverages, Travel & Commute, Outdoor/Trekking Gear, Shopping.
- **Budget Control:** Real-time daily budget ceiling, spending percentages, and threshold alerts.
- **Savings Goals:** Visual progress indicators for monthly and quarterly targets.
- **Bank Synchronization:** Secure simulated API connection for automatic reporting.

### 2.3 Habit & Routine Streaks (3D Soothing Green & White Theme)
- **Circular Progress Rings:** SVG vector dashoffset gauge showing daily habit completion.
- **Glowing 3D Streak Flames:** Consecutive-day streak counters.
- **Automated Web Notifications:** Daily reminders for meditation, hydration, and meal times.

### 2.4 Hydration & Meal Tracking Module
- **Preset Quick-Sips:** 1-tap logging for 150ml, 250ml, 500ml, 750ml with custom goal targets.
- **Unit Conversion:** Fluid Ounces (oz) and Milliliters (ml) support.

### 2.5 Community Yoga, Fitness & Live Advice Chat (3D Warm Orange & White Theme)
- **Community Yoga Classes:** Live session signups (Vinyasa, Yin Yoga, Power Flow) with automatic calorie logging.
- **Live Peer Advice Chat:** Ask questions, share routine tips, and receive advice with  ✓ Helpful badges.
- **AI Wellness Advisor Bot:** Instant conversational responses to hydration, workout, and habit inquiries.

### 2.6 Immersive 3D Graphics & GSAP Parallax Animation
- **Startup Animation:** Dark-to-light radiant 3D logo expansion transition.
- **Dynamic 3D Canvas:** Three.js wave particle grids and interactive floating wireframe meshes responding to scroll parallax and cursor motion.

---

## 3. Technology Stack & Implementation
- **Frontend Framework:** React 18 + Vite (SPA)
- **3D Graphics & Animation:** Three.js + GSAP 3 (ScrollTrigger, Timelines)
- **Styling:** Modular Glassmorphism & Neon Glow Design System (Dark/Light themes)
- **Data Persistence:** LocalStorage / IndexedDB with JSON Export & Synchronization
