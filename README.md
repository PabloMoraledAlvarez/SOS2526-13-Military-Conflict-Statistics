# SOS2526-13

## 📌 Project Overview

**SOS2526-13** is a full-stack web application developed as part of the **Service-Oriented Systems** course at the **University of Seville**.

The project analyzes the relationship between **military expenditure, arms exports, military personnel, and armed conflicts** through a set of REST APIs and a web-based frontend.

The application follows a service-oriented architecture, with independently developed API services integrated into a common frontend.

---

## 👥 Team

* **Camila España Vildoso** — [GitHub](https://github.com/Camiev04)
* **Claudia Páez Sollo** — [GitHub](https://github.com/Clapaesol)
* **Pablo Moraleda Álvarez** — [GitHub](https://github.com/PabloMoraledAlvarez)

---

## 🎯 Project Description

Our project analyzes the relationship between **military expenses, arms exports, military personnel, and conflicts**.

The application provides access to several REST API versions and a frontend that allows users to interact with and visualize the available data.

Each team member was responsible for the development of one of the main API services, while the complete system was integrated into a single full-stack application.

---

## 🛠️ Technologies

The project was developed using the following technologies:

* **JavaScript** — Application logic and API development
* **Svelte** — Frontend components and user interface
* **Vue.js** — Frontend development
* **HTML5** — Application structure
* **CSS3** — Styling and responsive design
* **REST APIs** — Service-oriented communication
* **Node.js** — Backend environment
* **Render** — Main deployment platform
* **Railway** — Additional full-stack deployment

---

## 🏗️ Architecture

The application is structured around a set of RESTful services. Each API provides access to a specific dataset related to military and conflict statistics.

```text
                    ┌─────────────────────┐
                    │      Frontend       │
                    │  Svelte / Vue.js    │
                    │     HTML / CSS      │
                    └──────────┬──────────┘
                               │
                               ▼
                 ┌─────────────────────────┐
                 │       REST APIs          │
                 ├─────────────────────────┤
                 │ Military Statistics     │
                 │ Conflict Statistics     │
                 │ Arms Export Statistics  │
                 └────────────┬────────────┘
                              │
                              ▼
                     ┌────────────────┐
                     │     Datasets   │
                     └────────────────┘
```

The APIs expose their functionality through REST endpoints and provide documentation for interacting with each service.

---

## 🚀 Live Application

**Main deployment:**

https://sos2526-13.onrender.com

**Alternative Railway deployment:**

https://sos2526-13-production.up.railway.app

**Railway Exportations Statistics page:**

https://sos2526-13-production.up.railway.app/exportations-stats

---

## 🔌 APIs

### Military Statistics

Developed by **Camila España Vildoso**.

* **v1:** https://sos2526-13.onrender.com/api/v1/military-stats
* **Documentation:** https://sos2526-13.onrender.com/api/v1/military-stats/docs

### Conflict Statistics

Developed by **Pablo Moraleda Álvarez**.

* **v2:** https://sos2526-13.onrender.com/api/v2/conflict-stats
* **v1:** https://sos2526-13.onrender.com/api/v1/conflict-stats
* **v2 Documentation:** https://sos2526-13.onrender.com/api/v2/conflict-stats/docs
* **v1 Documentation:** https://sos2526-13.onrender.com/api/v1/conflict-stats/docs

### Arms Export Statistics

Developed by **Claudia Páez Sollo**.

* **v2:** https://sos2526-13.onrender.com/api/v2/exportations-stats
* **v1:** https://sos2526-13.onrender.com/api/v1/exportations-stats
* **v2 Documentation:** https://sos2526-13.onrender.com/api/v2/exportations-stats/docs
* **v1 Documentation:** https://sos2526-13.onrender.com/api/v1/exportations-stats/docs

---

## 📚 API Documentation

All API services include dedicated documentation pages describing their available endpoints and operations.

| Service                | Version | Documentation                                                              |
| ---------------------- | ------- | -------------------------------------------------------------------------- |
| Military Statistics    | v1      | [API Docs](https://sos2526-13.onrender.com/api/v1/military-stats/docs)     |
| Conflict Statistics    | v1      | [API Docs](https://sos2526-13.onrender.com/api/v1/conflict-stats/docs)     |
| Conflict Statistics    | v2      | [API Docs](https://sos2526-13.onrender.com/api/v2/conflict-stats/docs)     |
| Arms Export Statistics | v1      | [API Docs](https://sos2526-13.onrender.com/api/v1/exportations-stats/docs) |
| Arms Export Statistics | v2      | [API Docs](https://sos2526-13.onrender.com/api/v2/exportations-stats/docs) |

---

## 🌐 Deployment

The system was deployed using different cloud platforms as part of the course deployment activities.

### Render

The main application is available at:

https://sos2526-13.onrender.com

### Railway

An additional full-stack deployment was created using Railway:

https://sos2526-13-production.up.railway.app

This deployment was developed as an additional contribution by **Claudia Páez Sollo**.

---

## 📂 Repository

The complete source code is available on GitHub:

https://github.com/gti-sos/SOS2526-13

---

## 💻 Local Development

To run the project locally, clone the repository and install the required dependencies.

```bash
git clone https://github.com/gti-sos/SOS2526-13.git
cd SOS2526-13
npm install
```

Then start the application using the project's configured development command:

```bash
npm run dev
```

The exact commands may vary depending on the frontend or service being executed.

---

## 📖 Academic Context

This project was developed for the **Service-Oriented Systems (Sistemas Orientados a Servicios)** course at the **University of Seville** during the **2025/2026 academic year**.

The main objective was to apply concepts related to:

* RESTful API design
* Service-oriented architectures
* API versioning
* Frontend-backend integration
* Data analysis and visualization
* Cloud deployment
* Collaborative software development
* API documentation

---

## 📄 License

This project was developed for academic purposes as part of the Service-Oriented Systems course at the University of Seville.
