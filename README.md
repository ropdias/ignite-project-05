# Forum App

A sophisticated forum platform built with a stack of powerful technologies including Nest.js, Prisma, Zod, Redis, PostgreSQL, JWT, and Vitest. Leveraging principles from Domain-Driven Design (DDD) and Clean Architecture, it offers a robust and scalable solution for online discussions.

## Key Features

- **Advanced Architecture**: Built upon the principles of Domain-Driven Design (DDD) and Clean Architecture, ensuring maintainability, scalability, and testability of the codebase.
- **Secure Authentication**: Utilizes JSON Web Tokens (JWT) for secure authentication, providing a reliable mechanism for user authentication and authorization.
- **Real-time Notifications**: Includes a sub-domain feature for sending notifications to users when they answer a question or when their answer is chosen as the best for a question, enhancing user engagement and interaction.
- **Data Persistence**: Stores data efficiently using PostgreSQL, ensuring reliability and performance even with large amounts of data.
- **Testing**: Includes comprehensive test coverage with Vitest, ensuring robustness and reliability of the application.
- **Cache Management**: Utilizes Redis for efficient caching, enhancing performance and reducing database load.

## FRs (Functional Requirements)

- [x] It must be possible to register a user;
- [x] It must be possible to authenticate a user;

## BR (Business Requirements)

## NFR (Non-functional requirements)

- [x] User password must be encrypted;
- [x] Application data must be persisted in a PostgreSQL database;
- [x] Every data list must be paginated with 20 itens per page;
- [x] User must be identified by a JWT (JSON Web Token);