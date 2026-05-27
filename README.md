# StudyStream

A collaborative web platform designed for curated educational study, allowing users to save, organize, and annotate video content.

**Note:** This repository is an independent fork of the original group project developed for [Course/University Name].

## Project Overview
StudyStream serves as a centralized hub for managing study resources. By leveraging the YouTube IFrame API, the application enables seamless video embedding and organization, helping students maintain focus by minimizing the distractions inherent in the standard YouTube interface.

## Technologies Used
* **Frontend:** React.js, Tailwind CSS
* **Backend:** Node.js, Express
* **Database:** MongoDB (Mongoose)
* **API:** YouTube IFrame API
* **Deployment:** Vercel (Frontend), Render (Backend)

## My Contributions
As a primary developer on this project, I was responsible for the end-to-end design and implementation of core features, including:

* **UX/UI Design:** Created initial wireframes and design prototypes in Figma to establish the platform's user flow and interface before development.
* **Backend Development:** Engineered the complete backend logic for the "Notes" and "Saved Content" modules, including designing database schemas and developing robust API controllers.
* **API Integration & Testing:** Implemented and performed comprehensive testing of the backend API endpoints to ensure data integrity and secure communication.
* **Deployment & DevOps:** Orchestrated the production deployment for both the frontend (Vercel) and backend (Render) infrastructures.

## Getting Started
To run this project locally:

1. Clone the repository:
   `git clone https://github.com/Surash124/StudyStream.git`
2. Install dependencies:
   `npm install`
3. Configure your `.env` file with the required `MONGODB_URI` and API keys.
4. Start the application:
   `npm run dev`

---
*Developed as a collaborative project.*# StudyStream

A collaborative web platform designed for curated educational study, allowing users to save, organize, and annotate video content.

**Note:** This repository is an independent fork of the original group project developed for [Course/University Name].

## Project Overview
StudyStream serves as a centralized hub for managing study resources. By leveraging the YouTube IFrame API, the application enables seamless video embedding and organization, helping students maintain focus by minimizing the distractions inherent in the standard YouTube interface.

## Technologies Used
* **Frontend:** React.js, Tailwind CSS
* **Backend:** Node.js, Express
* **Database:** MongoDB (Mongoose)
* **API:** YouTube IFrame API
* **Deployment:** Vercel (Frontend), Render (Backend)

## My Contributions
As a primary developer on this project, I was responsible for the end-to-end design and implementation of core features, including:

* **UX/UI Design:** Created initial wireframes and design prototypes in Figma to establish the platform's user flow and interface before development.
* **Backend Development:** Engineered the complete backend logic for the "Notes" and "Saved Content" modules, including designing database schemas and developing robust API controllers.
* **API Integration & Testing:** Implemented and performed comprehensive testing of the backend API endpoints to ensure data integrity and secure communication.
* **Deployment & DevOps:** Orchestrated the production deployment for both the frontend (Vercel) and backend (Render) infrastructures.

## Getting Started
To run this project locally:

1. Clone the repository:
   `git clone https://github.com/Surash124/StudyStream.git`
2. Install dependencies:
   `npm install`
3. Configure your `.env` file with the required `MONGODB_URI` and API keys.
4. Start the application:
   `npm run dev`

---
*Developed as a collaborative project.*

# Project Summary: StudyStream (MERN)

A full-stack platform for curated educational YouTube videos with study-focused features.

## Core Features
* **Video Hub**: Distraction-free embedded player, search, and categorization.
* **Study Tools**: Timestamped notes, watch history, and "Watch Later" saved lists.
* **Engagement**: Q&A threads per video.
* **Admin Panel**: CRUD operations for video management with role-based access control.

## Technical Stack
| Layer | Technology |
|---|---|
| **Frontend** | React 18, Vite, Tailwind CSS |
| **Backend** | Node.js, Express |
| **Database** | MongoDB (Mongoose) |
| **Auth** | JWT (HTTP-only cookies + Bearer token) |

## Key Logic
* **Auth**: `protect` middleware for logged-in status; `adminOnly` for sensitive endpoints.
* **Notes**: Automatically sorted by video timestamp.
* **History**: Refreshes timestamps on repeat views instead of duplicating entries.
* **Security**: Passwords hashed with `bcryptjs`; admin permissions enforced server-side.