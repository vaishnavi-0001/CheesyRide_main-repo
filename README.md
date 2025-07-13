🚗🧀 CheesyRide — My Microservices Delivery Platform
Hey there! 👋
Welcome to CheesyRide — my personal project where I explored microservices, TypeScript, and the MERN stack. This repo is like the map 🗺️ to all the services I built, with what each does and the tools behind them.

🗂️ Modules & Details


🎨 client-ui (Private)
Frontend | React + TypeScript

Role:
Customer-facing web app — place orders, browse catalog, track deliveries.

Tech & Tools:

**framework: React + TypeScript
**Styling: Styled Components
**API: Axios for HTTP requests
**Testing: Jest, React Testing Library
**CI/CD: GitHub Actions (lint, build checks)
**Containerization: Docker

🛒 order-service (Public)
Backend | Node.js + TypeScript

Role:
Handles order creation, updates, and order state syncing.

Tech & Tools:

Backend: Express.js + TypeScript
Database: TypeORM with PostgreSQL or MongoDB
API Docs: Swagger/OpenAPI
Testing: Jest, Supertest
CI/CD: GitHub Actions
Containerization: Docker

🗂️ CheesyRide_Admin_Dashboard (Public)
Admin Panel | React + TypeScript

Role:
Admins manage orders, inventory, and see stats with graphs.

Tech & Tools:

Framework: React + TypeScript
Data Viz: Recharts
Auth: Admin login with RBAC
Testing: Jest
CI/CD: GitHub Actions
Containerization: Docker

📚 CheesyRide-catalog (Public)
Catalog Service | Node.js + TypeScript

Role:
Manages product listings, availability, and inventory updates.

Tech & Tools:

Backend: Express.js + TypeScript
Database: MongoDB
API Testing: Postman collections
Testing: Jest
CI/CD: GitHub Actions
Containerization: Docker

🔗 CheesyRide-Service (Public)
Core Orchestrator | Node.js + TypeScript

Role:
Connects all microservices — API gateway, auth, logging.

Tech & Tools:

API Gateway: Express + custom middleware
Auth: JWT-based authentication
Logging: Winston logger
Testing: Jest
CI/CD: GitHub Actions
Containerization: Docker, Docker Compose for all-in-one local setup

⚙️ CheesyRide-mern-app-template (Private)
Boilerplate | MERN + TypeScript

Role:
Starter kit for new services — saves setup time.

Tech & Tools:

Stack: MongoDB, Express, React, Node.js (MERN)
TypeScript: Configured out-of-the-box
Linting: ESLint + Prettier
Testing: Jest basic setup
Containerization: Dockerfile included
CI/CD: Starter GitHub Actions workflow

💡 What I Learned
✅ How to break big features into independent services
✅ Using TypeScript for backend & frontend
✅ Writing automated tests for API & UI
✅ Building CI/CD pipelines with GitHub Actions
✅ Packaging everything with Docker

🚀 Run It
Clone each service repo you want to run.

Follow its README for local setup (env vars, DB, etc.).

Use Docker Compose to run multiple services together.

Open the client on localhost — you’re live!

🎯 Why I Built This
I wanted to learn real system design — not just theory but end-to-end development, testing, containerization, and deployment — all in one project.

🤝 Connect With Me
Got ideas, suggestions, or feedback? Open an issue in any repo — or reach out! I’d love to collaborate and improve this further. 🚀

Thanks for checking out CheesyRide! 🧀🚗✨

