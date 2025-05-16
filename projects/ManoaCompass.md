---
layout: project
type: project
image: img/ManoaCompassSignUp.jpeg
title: "Manoa Compass"
date: 2025
published: true
labels:
summary: "Manoa Compass is a web application built to help University of Hawaiʻi at Mānoa students discover and engage with campus clubs and events. The platform aggregates information from official university sources and user submissions, providing a unified directory of student organizations and a personalized feed of upcoming events."
---
Manoa Compass: Project Overview & Reflection
Project Overview
Manoa Compass is a web application built to help University of Hawaiʻi at Mānoa students discover and engage with campus clubs and events. The platform aggregates information from official university sources and user submissions, providing a unified directory of student organizations and a personalized feed of upcoming events.

Key features include:

Onboarding flow to capture user interests

Recommendation engine using LLM-based content classification (Gemini API) and rule-based logic

Club and event directories with search and filtering

Event RSVP system with calendar integration

Admin dashboard for content management and data import/scraping

The application is built with Next.js and React-Bootstrap for the frontend, Prisma with PostgreSQL for data management, and is deployed on Vercel. Content classification for recommendations is powered by Google’s Gemini API.

My Contributions
UI/UX Design:
Led the design of user interfaces and user experience across the application, focusing on clear navigation, responsive layout, and visual consistency. Designed onboarding, dashboards, directories, and detail pages.

Database Design:
Developed the relational data model in Prisma, defining schemas for users, clubs, events, RSVPs, and categories. Prioritized normalization and maintainability to support robust querying and feature growth.

Architectural Design:
Established the overall technical architecture for the project, including patterns for API structure, integration of external APIs (LLM, scraping), and serverless deployment.

Dashboard Implementation:
Built the main user dashboard, which aggregates personalized club and event recommendations and RSVPs, integrating backend recommendation logic with frontend display.

Development Planning:
Authored the technical planning, project timeline, and task breakdown, enabling the team to coordinate effectively and progress in parallel.

What I Learned
End-to-End Product Development:
This project reinforced the need to balance user experience, technical constraints, and scalability. Every decision—from schema to page layout—impacts the usability and maintainability of the final product.

Architectural Decision-Making:
Making design choices to support performance and maintainability (e.g., pre-classifying content with the LLM, designing for serverless deployment) was essential. Planning for future extensibility shaped everything from the API to the data model.

Modern Full-Stack Tooling:
Working with Next.js (App Router), React-Bootstrap, Prisma, and Vercel provided practical experience with a modern stack. Handling issues like DB connections in serverless contexts, and managing deployments and environment variables, highlighted the realities of production web apps.

LLM Integration in Production:
Integrating the Gemini API for text classification introduced new engineering challenges: prompt design, output normalization, handling edge cases, and batching API calls. These skills are directly applicable to building AI-powered features in other contexts.

Security and Access Control:
Implementing admin controls and role-based permissions required thinking beyond basic authentication, including route protection and safe API design.

Designing for Real Users:
Building robust onboarding, error handling, and thoughtful UI states (empty/search results, loading, etc.) emphasized the importance of resilience and user-centered design.

Source Code

https://github.com/manoa-compass/manoa-compass-code

View the source code and learn more about the project.
