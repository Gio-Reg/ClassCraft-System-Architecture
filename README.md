# ClassCraft: Strategic SaaS Booking & Growth Ecosystem
A production-ready PWA for professional scheduling and developmental tracking.

# 📌 Project Overview
ClassCraft is a full-stack SaaS platform designed to bridge the gap between administrative booking and long-term user development. Currently functioning as a high-performance Booking Suite, the platform is evolving into a comprehensive Growth Tracker through its integrated Logbook system.

This repository serves as the Public Documentation and Architecture Blueprint. The core source code remains private to protect proprietary business logic and security configurations.

# 🏗️ The Roadmap: From Booking to Intelligence
The platform is designed in two primary phases to maximize user value:

# Phase 1 (Current): The Booking Suite
- Streamlined scheduling and resource management.
- Secure user authentication and data persistence.
- Responsive, high-speed UI for real-time management.

# Phase 2 (In Development): The Logbook & Path Tracker
- Transforming booking data into a "Growing Path Tracker."
- Utilizing historical data to visualize progress, milestones, and development trends.
- Architected for future AI integration to provide automated insights into user growth patterns.

# 🛠️ System Architecture
1. Frontend Layer (React & PWA)
Dynamic State Management: Optimized for real-time scheduling updates and persistent UI preferences (Dark Mode).
Modular Component Design: Reusable UI elements for booking cards, delete actions, and logbook entries to ensure a consistent user experience.
Progressive Web App (PWA): Built for mobile-first accessibility, ensuring users can manage bookings and logs on the go.

2. Backend Layer (Python / FastAPI)
Scalable API Design: A RESTful architecture designed to handle complex relationships between bookings, users, and chronological log data.
Data Integrity: Implements rigorous validation to ensure that "Growth Path" data remains accurate over long time horizons.

3. Data Persistence (PostgreSQL)
Relational Schema: Designed for longitudinal data tracking. The database is optimized to query both "snapshot" booking data and "sequential" logbook history.

4. Infrastructure & DevOps
Containerization: Fully Dockerized environment (docker-compose) to ensure environment parity.
SaaS Deployment: Currently hosted on Render with automated CI/CD pipelines, reflecting a modern production workflow.

# 🚀 Engineering Challenges & Solutions
Challenge: Designing for Evolution
Solution: The database and API were architected not just for "appointments," but for "events." By treating every booking as a data point in a user's journey, the transition to a Growth Tracker via the Logbook was a matter of expanding the front-end logic rather than a back-end rewrite.

Challenge: UX for Longitudinal Data
Solution: Creating an interface that handles both immediate needs (booking a slot) and long-term visualization (the logbook). This required a "Clean-Room" UI approach—using a dark theme and high-contrast elements to minimize cognitive load.

# 🔒 Security & Privacy Notice
The primary codebase for ClassCraft is maintained in a private repository. This documentation is provided to demonstrate:

Full-Stack Competency: From database design to PWA deployment.
Product Vision: Moving beyond basic CRUD apps to building tools that track and analyze human growth.
Architectural Rigor: Professional use of Docker, PostgreSQL, and Python in a SaaS context.

# 📬 Contact & Links
Live Application: ClassCraft Beta at https://classcraft-beta.onrender.com/
Developer: Giorgio Regnoli, PhD

LinkedIn: https://www.linkedin.com/in/giorgio-regnoli/
