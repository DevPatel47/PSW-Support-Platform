# PSW Support Platform

A web platform aimed at **connecting Personal Support Workers (PSWs) with clients** who need their services. The platform is designed to make booking, communication, and service discovery **secure, efficient, and user-friendly**.

---

## Table of Contents

- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Objectives](#objectives)
- [Scope](#scope)
- [High-Level Features](#high-level-features)
- [Completed Steps](#completed-steps)
- [Next Steps](#next-steps)

---

## Project Overview

The demand for Personal Support Workers is growing, but clients often struggle to find reliable PSWs, and PSWs find it hard to reach clients efficiently. This project seeks to **create a centralized platform** addressing this gap.

---

## Problem Statement

There is no easy-to-use, centralized system for connecting PSWs with people who need their services. This leads to inefficiencies, miscommunication, and difficulty in finding trustworthy care.

---

## Objectives

- Build a platform that connects PSWs and clients.
- Allow PSWs to create detailed profiles (skills, availability, experience).
- Allow clients to search, book, and review PSWs.
- Ensure security, accessibility, and usability.

---

## Scope

**In-Scope (Initial Planning / MVP):**

- User authentication (Sign up / Login)
- PSW & Client profile concepts
- Basic booking workflow
- High-level design and documentation

**Out of Scope (Future Enhancements):**

- Payment integration
- Video call support
- Mobile app version

---

## High-Level Features

- User registration & login
- PSW profiles
- Booking system (conceptual)
- Reviews & ratings (conceptual)
- Search & filter PSWs

---

## System Design & Documentation

All detailed project documentation can be found in the `docs/` folder:

- [Project Kickoff](./docs/Project-Kickoff.md)
- [Requirements](./docs/Requirements.md)
- [System Design](./docs/System-Design.md)
- [API Documentation](./docs/API-Documentation.md)
- [User Guide](./docs/User-Guide.md)

---

## Completed Steps

- **Project Kickoff & Planning**
  - Define vision, scope, and target audience.
  - Write Problem Statement & Objectives.
  - Identify main features (booking, profiles, messaging, reviews, etc.).
  - Start SDLC documentation (Project Charter, Feasibility, High-Level Requirements).

- **Requirements Gathering & Documentation**

  - Write Functional & Non-functional requirements.
  - Create Use Case Diagram / User Stories.
  - Define roles (PSW, Client, Admin).
  - Start Database design (ERD) draft.

---

## Next Steps

- **System Design**

  - Finalize ERD & Database schema.
  - Create Architecture Diagram (MERN stack layout).
  - Plan API routes (REST endpoints).
  - Decide UI flow with wireframes (Canva).

- **Backend Setup**

  - Setup Node.js + Express project.
  - Connect to MongoDB (Atlas).
  - Implement User Auth (JWT, bcrypt).
  - Setup models: User, Booking, Services, Reviews.

- **Backend API Development**

  - Build REST APIs for:

    - User registration/login.
    - Booking services.
    - Profile management.
    - Review system.

  - Test with Postman.

- **Frontend Setup**

  - Setup React + Vite project.
  - Configure routing with React Router.
  - Setup UI components (Navbar, Footer, Landing Page).
  - Connect frontend with backend auth.

- **Frontend Feature Development**

  - Build UI for:

    - PSW profiles listing.
    - Booking form & calendar.
    - Reviews section.

  - Fetch & display API data.

- **Integration & Testing**

  - Connect all features end-to-end.
  - Test booking, login, review flows.
  - Debug and fix errors.
  - Add form validation & error handling.

- **Documentation & Final Touches**

  - Write Technical Documentation (API docs, DB schema, architecture).
  - Write User Guide (how clients & PSWs use it).
  - Add small polish: responsive design, better UI.

- **Deployment**
  - Deploy backend on Render.
  - Deploy frontend on Vercel.
  - Final testing.

---
