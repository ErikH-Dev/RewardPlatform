# InnoVactions Rewards Platform

*Project completed in Spring of 2025 for the company Innovactions.*

InnoVactions Reward Platform is a SaaS platform that enables users to earn rewards by completing surveys, games, and testing software. The system supports user registration, secure login, survey participation, rewards management, and payout processing with a focus on usability, scalability, and compliance.

![InnoVactions Architecture](./assets/RewardPlatform-mockup.png)

## Overview

The platform connects users, companies, and administrators, providing distinct interfaces for creating, completing, and managing surveys and rewards. It supports multi-language UI, optimized for desktop and mobile, and scalability up to thousands of concurrent users. Integral security features include GDPR compliance, end-to-end encryption, and secure payment processing.

## Key Features

- User registration, login (Keycloak, social login, SSO)
- Browse, filter, and complete surveys and games
- Real-time leaderboards tracking user rewards
- Companies can create/manage surveys and view analytics
- Admin moderation of users, surveys, and payments
- Reward redemption options (Stripe, PayPal)
- Secure payout approval workflow
- Scalable, distributed architecture with optimized DB queries
- CI/CD via Docker and Jenkins for seamless deployment

## Architecture and Workflow

- Angular frontend serving all user roles with responsive design
- Java Spring Boot microservices implementing core business logic
- Microsoft SQL Server and MongoDB as the primary datastores
- RabbitMQ for asynchronous, decoupled communication
- Auth via Keycloak ensuring secure session management
- Docker containers deployed and orchestrated via Jenkins CI/CD pipeline

## User Roles

| Role      | Description                                              |
|-----------|----------------------------------------------------------|
| Users     | Complete surveys and games, track rewards, redeem points|
| Companies | Create/manage surveys, monitor participation and payouts |
| Admins    | Moderate platform content, prevent fraud                 |

## Development & Compliance

Built using Agile Scrum methodology with bi-weekly sprint cycles and continuous stakeholder feedback. Compliance with GDPR and security best practices ensured throughout development. Regular retrospectives support ongoing process improvements.

## Contact

For questions or access to documentation, please contact the project owner.