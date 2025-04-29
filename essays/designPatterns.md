---
layout: essay
type: essay
title: "Reflecting on Design Patterns"
# All dates must be YYYY-MM-DD format!
date: 2025-04-28
published: true
labels:

---



Developing robust software is similar to constructing a well-designed city—both require clear structure, thoughtful planning, and established best practices to succeed. In software engineering, these best practices are known as design patterns. Design patterns represent standardized, proven solutions to common challenges in software development. They serve as architectural blueprints that guide developers in creating maintainable, scalable, and efficient systems.

Throughout the development of the Manoa Compass application—an interactive platform designed to help new students at the University of Hawaiʻi at Mānoa connect with campus clubs, events, and peers—several key design patterns naturally emerged through our use of frameworks and libraries such as Next.js, React, Prisma, and NextAuth.

A foundational structure evident in our project is the Model-View-Controller (MVC) pattern. While not explicitly labeled as MVC, the pattern manifested clearly in our architecture: the "Model" comprises the Prisma schema and client, managing data and business logic; the "View" involves React components responsible for rendering the user interface; and the "Controller" includes Next.js API routes and event handlers that mediate user input between the Model and the View. This structured separation enhanced maintainability, making the application easier to extend and debug.

On the data access side, we leveraged the Repository pattern implicitly through Prisma’s Object-Relational Mapping (ORM) capabilities. Prisma simplified database interactions by providing an abstraction layer that mapped our PostgreSQL database to TypeScript objects. Additionally, we applied the Singleton pattern when initializing the Prisma client. By ensuring only one client instance managed database connections, we mitigated the risk of resource exhaustion during development.

Our authentication solution employed the Strategy pattern through NextAuth. This allowed the application to support multiple authentication strategies—Google and credential-based sign-ins—without altering the application's core authentication workflow. Moreover, integration of the Adapter pattern was achieved using NextAuth’s Prisma Adapter, which seamlessly interfaced between NextAuth's authentication system and our Prisma-managed data.

Frontend development in React naturally encouraged the use of component-based architecture, exemplified by modular elements such as cards, event listings, and signup forms. Each component maintained isolated, reusable logic and state, promoting consistency and reusability throughout the application. Controlled components were extensively used for form handling, offering precise state management and enhanced data integrity.

In terms of user experience, we implemented the Wizard pattern to guide new users smoothly through a multi-step registration process, significantly enhancing usability and reducing user friction. Additionally, conditional rendering was systematically employed to display interface elements based on specific application states, such as user authentication status or administrative privileges, further tailoring the user experience.

Finally, our backend was implicitly structured as an API Gateway through Next.js API routes, providing clearly defined endpoints and centralized access control for client-server interactions.

Reflecting on these implementations, it is clear that employing design patterns significantly improved the clarity, scalability, and reliability of the Manoa Compass application. Recognizing and consciously applying these patterns has not only elevated the quality of our codebase but also prepared us to discuss these best practices confidently in technical interviews and professional environments.

Used AI to help write this
