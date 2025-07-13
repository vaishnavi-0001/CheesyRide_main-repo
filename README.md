
# 🚗🧀 **CheesyRide — My Microservices Delivery Platform**

Hey there! 👋
Welcome to **CheesyRide** — my personal project where I explored **microservices**, **TypeScript**, and the **MERN stack**.
This repo is like a **map** 🗺️ for all the services I built, what each does, and the tools behind them.

---

## 🗂️ **Modules & Details**

---

### 🎨 [**client-ui**](https://github.com/vaishnavi-0001/client-ui.git) *(Private)*

**Frontend | React + TypeScript**

**Role:**
Customer-facing web app — place orders, browse the catalog, and track deliveries.

**Tech & Tools:**

* **Framework:** React + TypeScript
* **Styling:** Styled Components
* **API:** Axios for HTTP requests
* **Testing:** Jest, React Testing Library
* **CI/CD:** GitHub Actions (lint, build checks)
* **Containerization:** Docker

---

### 🛒 [**order-service**](https://github.com/vaishnavi-0001/order-service.git) *(Public)*

**Backend | Node.js + TypeScript**

**Role:**
Handles order creation, updates, and syncing with other services.

**Tech & Tools:**

* **Backend:** Express.js + TypeScript
* **Database:** TypeORM with PostgreSQL or MongoDB
* **API Docs:** Swagger/OpenAPI
* **Testing:** Jest, Supertest
* **CI/CD:** GitHub Actions
* **Containerization:** Docker

---

### 🗂️ [**CheesyRide\_Admin\_Dashboard**](https://github.com/vaishnavi-0001/CheesyRide_Admin_Dashboard.git) *(Public)*

**Admin Panel | React + TypeScript**

**Role:**
Admins can manage orders, inventory, and see stats with graphs.

**Tech & Tools:**

* **Framework:** React + TypeScript
* **Data Viz:** Recharts
* **Auth:** Admin login with RBAC
* **Testing:** Jest
* **CI/CD:** GitHub Actions
* **Containerization:** Docker

---

### 📚 [**CheesyRide-catalog**](https://github.com/vaishnavi-0001/CheesyRide-catalog.git) *(Public)*

**Catalog Service | Node.js + TypeScript**

**Role:**
Manages product listings, stock availability, and real-time updates.

**Tech & Tools:**

* **Backend:** Express.js + TypeScript
* **Database:** MongoDB
* **API Testing:** Postman collections
* **Testing:** Jest
* **CI/CD:** GitHub Actions
* **Containerization:** Docker

---

### 🔗 [**CheesyRide-Service**](https://github.com/vaishnavi-0001/CheesyRide-Service.git) *(Public)*

**Core Orchestrator | Node.js + TypeScript**

**Role:**
Connects all microservices — API gateway, authentication, and logging.

**Tech & Tools:**

* **API Gateway:** Express + custom middleware
* **Auth:** JWT-based authentication
* **Logging:** Winston logger
* **Testing:** Jest
* **CI/CD:** GitHub Actions
* **Containerization:** Docker, Docker Compose for local orchestration

---

### ⚙️ [**CheesyRide-mern-app-template**](https://github.com/vaishnavi-0001/CheesyRide-mern-app-template.git) *(Private)*

**Boilerplate | MERN + TypeScript**

**Role:**
Starter kit for building new microservices — saves setup time with consistent structure.

**Tech & Tools:**

* **Stack:** MongoDB, Express, React, Node.js (MERN)
* **TypeScript:** Fully configured out-of-the-box
* **Linting:** ESLint + Prettier
* **Testing:** Jest basic setup
* **Containerization:** Dockerfile included
* **CI/CD:** Starter GitHub Actions workflow

---

## 💡 **What I Learned**

✅ Breaking big features into **independent services**
✅ Using **TypeScript** for backend & frontend
✅ Writing **automated tests** for API & UI
✅ Building **CI/CD pipelines** with **GitHub Actions**
✅ Packaging everything with **Docker** for local & production

---

## 🚀 **How to Run It**

1. Clone each service repo using the links above.
2. Follow each service’s README for setup (env vars, DB, etc.).
3. Use **Docker Compose** to spin up multiple services at once.
4. Access the client at `localhost` and test it end-to-end! 🎉

---

## 🎯 **Why I Built This**

I wanted to learn **real-world system design** — not just theory, but actually building, testing, containerizing, and deploying a multi-service application.

---

## 🤝 **Connect With Me**

Got ideas, suggestions, or feedback?
Open an issue in any repo — or just reach out! I’d love to keep improving CheesyRide and collaborating with other builders. 🚀

---

**Thanks for checking out CheesyRide! 🧀🚗✨**

---
