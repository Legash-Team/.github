### Frontend Repository: https://github.com/Legash-Team/Frontend
---
### Mobile Repository: https://github.com/Legash-Team/Mobile
---
### Backend Repository: https://github.com/Legash-Team/Backend

## Deployed Frontend: https://legash-ob55.onrender.com
## Deployed Backend: https://backend-3avt.onrender.com
## Mobile: https://github.com/Legash-Team/Mobile/releases/download/v1.0.0/app-release.apk (on mobile phone)

# Legash — Smart Blood Donation Management System

## About Legash

Legash is a Smart Blood Donation Management System designed to improve the coordination of blood donation activities and blood supply management by connecting donors, hospitals, and blood centers through a centralized digital platform.

The system provides tools for managing donor information, coordinating blood requests, monitoring hospital blood inventory, and supporting communication between healthcare facilities and donors.

Legash aims to make blood donation management more organized, accessible, and efficient by bringing the main participants and workflows together in one platform.

---

## The Problem

Blood donation and supply management involve several participants and time-sensitive activities. Without effective coordination, it can be difficult to:

- Identify eligible donors when blood is needed.
- Coordinate blood requests between hospitals and blood centers.
- Keep track of available blood inventory.
- Maintain accurate donor and donation records.
- Communicate important updates to donors and healthcare facilities.

Legash addresses these challenges through a centralized system that supports donor coordination, inventory management, and communication.

---

## Legash Project Team

The Legash project was developed by a team of engineers working across backend, web frontend, mobile, and cloud infrastructure.

| Team Member | CTC ID | Role | Main Contribution |
|---|---|---|---|
| Firaol Abera | CTC-777-26 | Full-Stack & Cloud Gateways Lead | Led full-stack architecture, notification pipelines, email and push notifications, media integration, event publishing, and Docker infrastructure. |
| Estifanos | CTC-1038-26 | Backend Core & Clinical Business Logic | Worked on blood compatibility matching, the 90-day donation eligibility rule, donor Short IDs, hospital intake, donation records, and automated testing. |
| Eyerusalem Gebrat | CTC-4210-26 | Backend Core & Inter-Facility Logistics | Worked on blood center requisition workflows, donation record APIs, modular backend routing, hospital stock analytics, and blood center onboarding. |
| Hanan Seid Mohammed | CTC-3381-26 | Web Frontend Lead & Design Systems | Led the React and TypeScript frontend architecture, dashboard design, localization, hospital records, donor intake, and role-based access control. |
| Enkumariam Dejene Tegen | CTC-551-26 | Web Applications Engineer | Worked on hospital registration, onboarding, blood stock management, blood requisitions, facility profiles, and frontend layout components. |
| Firaol Tsegaye | CTC-7007-26 | Mobile Subsystem Engineer | Worked on Flutter donor onboarding, profile Short ID display, event feed and event details, media playback, and network error handling. |
| Falmi Abdi | CTC-927-26 | Mobile Subsystem Engineer | Worked on Afaan Oromoo localization, nearby blood center discovery, distance calculations, donor statistics, and notification center functionality. |

---

## Project Submission

The following materials provide the project documentation, presentation, and demonstration.

| Submission Material | Link |
|---|---|
| 5-Minute Video Presentation | [Watch Video Presentation](https://www.awesomescreenshot.com/video/58110191?key=7341965dd94802f257e42297911a68dd) |
| Project Documentation (PDF) | [View Project PDF](https://drive.google.com/file/d/1UQ9ReVdnV4jWBQgBATKns4FrPhaQ2jI6/view?usp=sharing) |
| Presentation Slides (PPT) | [View Presentation Slides](https://drive.google.com/file/d/1KYYxhYRr9DFj5DdxEt2iCY3pu8kyvK1W/view?usp=sharing) |

---

## Main Features

### Donor Management

- Donor registration and profile management.
- Unique donor Short ID identification.
- Donation history and donation record tracking.
- Donation eligibility management, including the 90-day donation recovery period.

### Blood Compatibility and Donor Matching

- ABO and Rh blood group compatibility checking.
- Donor eligibility consideration.
- Location-based donor and blood center discovery.
- Support for identifying suitable donors for blood requests.

### Hospital Management

- Hospital registration and onboarding.
- Blood inventory management across ABO/Rh blood groups.
- Blood requisition submission and management.
- Donation intake and donor history records.
- Inventory monitoring and stock analytics.

### Blood Center Coordination

- Blood center registration and onboarding.
- Coordination of blood supply requests between hospitals and blood centers.
- Blood center information and operational workflows.

### Notifications and Communication

- Transactional email notifications.
- Firebase Cloud Messaging push notifications.
- Mobile notification center.
- Community updates and event information.

### Events and Community

- Blood donation event publishing.
- Event and community feed.
- Event media support.
- Donor-facing event information through the mobile application.

### Multilingual and Location-Based Support

- Multilingual web and mobile interfaces.
- English, Amharic, and Afaan Oromo support across the relevant application interfaces.
- Nearby blood center discovery using location information.

---

## Platform Architecture

Legash is organized into three repositories, each responsible for a different part of the platform.

| Component | Technology | Responsibility |
|---|---|---|
| Backend | Node.js, Express.js, MongoDB, Mongoose | REST API, authentication, business logic, database operations, and integrations |
| Web Application | React, TypeScript, Vite | Web dashboards, user interfaces, and hospital and administrative workflows |
| Mobile Application | Flutter, Dart | Donor-facing mobile experience, onboarding, notifications, and location-based services |