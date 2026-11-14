<div align="center">

# Mawid

### Node.js / Express event application

![Node.js](https://img.shields.io/badge/NODE.JS-BACKEND-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/EXPRESS-WEB_APPLICATION-111827?style=for-the-badge&logo=express)
![MySQL](https://img.shields.io/badge/MYSQL-DATABASE-4479A1?style=for-the-badge&logo=mysql&logoColor=white)

</div>

---

## Overview

**Mawid** is a Node.js / Express application experiment in the event domain. It explores server-rendered pages, relational database connectivity, session handling and basic production-minded middleware.

The project is useful for comparing the patterns of the **Node.js ecosystem** with a background in **PHP / Laravel**.

## Stack verified from `package.json`

| Responsibility | Package |
| --- | --- |
| Web server | Express 5 |
| View templates | EJS |
| Database connectivity | mysql2 |
| Sessions | express-session, express-mysql-session |
| Password utilities | bcrypt |
| Validation | Zod |
| Security headers | Helmet |
| Request limits | express-rate-limit |
| Logging | Pino, pino-http |
| Development runner | nodemon |

## Engineering goals

- Organize Express routes and reusable middleware.
- Handle session-backed user flows.
- Apply validation and useful errors to incoming data.
- Access relational data via MySQL.
- Build towards observable and security-conscious application behavior.

> Package presence demonstrates declared dependencies, not that every corresponding feature is fully integrated. Prisma was explored separately; it is not listed in this repository's inspected package manifest.

## Run locally

Prerequisites: Node.js, npm and a MySQL instance as needed by the application.

```bash
git clone https://github.com/Rakan-osama/Mawid.git
cd Mawid
npm install
npm run dev
```

The configured development command runs `nodemon src/index.js`. Database configuration, environment variables and setup steps depend on the application implementation. Do not commit credentials.

## Roadmap

Expand domain documentation, tests, database setup notes and feature walkthroughs as the implementation progresses.

## Author

[Rakan Osama](https://github.com/Rakan-osama) · [LinkedIn](https://www.linkedin.com/in/rakan-osama/) · [Email](mailto:rakanosama.dev@gmail.com)
