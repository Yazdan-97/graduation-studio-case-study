# 🎓 Graduation Studio

**A full-stack web platform for graduation event planning and management.**  
*Previously known as Graduation Planner.*

[🌐 Live Platform](https://4zelei.com) · [📂 Public Case Study](https://github.com/Yazdan-97/graduation-studio-case-study)

## Overview

Graduation Studio is a production-deployed web application designed to simplify how graduation celebrations are explored, planned, and managed. It brings user-facing event planning workflows and administrative operations into a single platform.

The project has evolved since its initial release, including a refreshed identity and ongoing refinements to its user experience and interface. This repository documents the product, technical approach, and development work. **It is a public case study, not an open-source release of the application code.**

## Key capabilities

### User experience

- Explore event plans and package details.
- Browse published event samples.
- Check date availability using an interactive calendar.
- Register and sign in to a user account.
- Submit event requests and manage reservation-related activity.
- Access account settings and profile management.
- Use the platform across desktop and mobile screens.

### Administration

- Manage users and administrative access.
- Create and update event plans, samples, and site content.
- Review and manage incoming requests and reservations.
- Monitor request status and reservation availability.
- Configure website content and system settings.

### Application foundations

- Authentication and session management.
- Role-based access control and protected administrative routes.
- Server-side application logic and authorization.
- Relational data modeling and database access.
- Responsive interface and maintainable application components.

## Technology stack

| Layer | Technologies |
| --- | --- |
| Frontend | Next.js, React, TypeScript, Tailwind CSS |
| Backend | Next.js / Node.js, server-side application logic |
| Database | PostgreSQL, Prisma ORM |
| Development | Git, GitHub, npm |

## High-level architecture

```text
Browser / Responsive UI
         |
         v
Next.js + React (TypeScript)
         |
         v
Application Logic + Authentication + Authorization
         |
         v
       Prisma ORM
         |
         v
       PostgreSQL
```

This diagram is a high-level conceptual overview, not an exhaustive infrastructure diagram.

## My contributions

I worked on the platform across the product lifecycle, including:

- Responsive UI implementation and iterative visual improvements.
- Reusable frontend components and interactive event-planning workflows.
- Server-side application logic and administrative functionality.
- Authentication, role-based authorization, and protected user journeys.
- Database design and integration with Prisma and PostgreSQL.
- Deployment, production maintenance, and ongoing refinements.

## Visual walkthrough

The latest public-facing experience can be explored on the [live website](https://4zelei.com).

**Screenshot refresh:** This case study originally included screenshots of the earlier interface. New screenshots of the current Graduation Studio design should replace those assets before a visual gallery is republished here.

Suggested gallery images to capture and add:

1. `screenshots/01-homepage-desktop.png` — hero section and primary navigation
2. `screenshots/02-availability-calendar.png` — event availability workflow
3. `screenshots/03-event-plans.png` — packages and plan comparison
4. `screenshots/04-authentication.png` — login/account experience
5. `screenshots/05-mobile-experience.png` — mobile responsive layout
6. `screenshots/06-user-dashboard.png` — user account dashboard (with demo data)
7. `screenshots/07-admin-dashboard.png` — administration view (with demo data)

> Privacy note: Use synthetic/demo data for all dashboard captures; avoid displaying real customer information, email addresses, or tokens.

## Current status

**Live and evolving.** Graduation Studio continues to be refined as product and operational needs change.

## Source code and confidentiality

The production application's source code is **private** due to project ownership and confidentiality considerations. This public repository is a portfolio case study containing project information and visual documentation; it does **not** contain the complete application source code.

---

**Live:** https://4zelei.com  
**Project identity:** Graduation Studio (formerly Graduation Planner)
