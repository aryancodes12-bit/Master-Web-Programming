# Master Web Programming & Universal Full-Stack Architecture 🚀

A comprehensive, exam-ready study guide, syllabus, and interactive architecture visualizer for Web Programming and Full-Stack Application Development.

---

## 📌 Contents & Structure

### 1. **Universal Full-Stack Architecture (The Master Model)**
- **Reusable Blueprint:** Designed for Library Management, Student Management, Hospital Management, Employee Management, Inventory Management, and E-commerce.
- **Database Design:** Relational entity modeling (Users, Books, Students, Transactions) with 1-to-many relationship mapping.
- **REST API Design:** Industry-standard endpoints (`GET`, `POST`, `PUT`, `DELETE`).
- **Backend Folder Structure:** Standard enterprise MVC layout (`routes/`, `controllers/`, `middleware/`, `config/`).
- **8-Step Request Lifecycle:** From frontend `fetch()` to Express routes, middleware, controllers, MySQL database queries, and JSON DOM rendering.
- **The Ultimate Exam Diagram & Model Theory Answer.**

---

### 2. **Part A: Server-Side Programming (Node.js + Express.js)**
1. Client-Side vs Server-Side Execution
2. Node.js & V8 Engine Fundamentals
3. Node.js Architecture (The Event Loop, Libuv Thread Pool, Non-blocking I/O)
4. Key Features of Node.js
5. NPM (Package Manager, `package.json` vs `package-lock.json` vs `node_modules/`)
6. Modules (Built-in, Third-Party, User-Defined)
7. File System (`fs`) Operations (Read, Write, Append, Delete)
8. Native HTTP Server Creation
9. Express.js Web Framework
10. REST Routing & HTTP Verbs (GET, POST, PUT, DELETE)
11. Middleware Pipeline & Interceptors (`next()`, `express.json()`)
12. Request / Response Handling (`req.params`, `req.query`, `req.body`)
13. Server-Side Template Engines (EJS, Pug, Handlebars)
14. RESTful API Principles & CRUD Mapping
15. Complete In-Memory Express REST API Server
16. Centralized Error Handling & HTTP Status Codes (200, 201, 400, 401, 403, 404, 500)
17. MySQL Database Connectivity with `mysql2`

---

### 3. **Part B: Server-Side Scripting (PHP + MySQL)**
18. Introduction to PHP & Server-Side Processing Flow
19. Syntax & Dynamic Typing
20. Data Types & Operators
22. Control Structures (`if/else`, `for`, `while`)
23. Functions & Array Types (Indexed vs Associative)
25. Form Handling: Security & Differences between `GET` and `POST`
26. Session Management (`session_start()`, `$_SESSION`)
27. Sessions vs Cookies Comparison
28. File Handling (`fopen`, `fread`, `fwrite`, `fclose`)
29. Error & Exception Handling (`try...catch`, `throw new Exception`)
30. MySQL Connection via `mysqli`
31. Full CRUD Operations in PHP & MySQL
32. Security Best Practices: SQL Injection Prevention with **Prepared Statements** & **Password Hashing** (`password_hash()`)

---

### 4. **Part C: Full-Stack Web Application Development**
33. Full Stack Overview (Frontend + Backend + Database)
34. 3-Tier Architecture (Client Tier → Business Logic Tier → Database Tier)
35. Frontend-Backend Integration via `fetch()` and JSON
36. Authentication (Identity) vs Authorization (Permissions)
37. State Management in Stateless HTTP (JWT vs Sessions)
38. Full CRUD Request Flow
39. Deployment Fundamentals & Environment Isolation (`.env`, `process.env`)
40. Git Version Control Workflow (`init`, `add`, `commit`, `push`)
41. Testing (Unit, Integration, API, E-2-E) & Debugging
42. Top 10 Web Application Security Best Practices

---

### 5. **Question Bank Solutions (QB Sol: Q1–Q50)**
- **Module 1 (Node.js & Express.js - Q1–Q25):** Event loop concurrent request handling, Core vs Third-party modules, Bearer token authorization middleware, `req.params` vs `req.query`, Express vs native HTTP, Database connection pools, Centralized error handling, and Module 1 Master Map.
- **Module 2 (PHP & MySQL - Q26–Q50):** Multidimensional arrays + foreach, `$_GET` vs `$_POST`, Cookie lifecycle & security flags, Type declarations & default parameters, `include` vs `require`, Structured exceptions, Secure login pipeline with `password_verify()` and prepared statements, 5-stage file upload security validator, SQLi/XSS/CSRF/Session hijacking defenses, and MySQLi vs PDO comparison matrix.

---

### 6. **Visual Diagrams & Interactive Gallery**
- **2 Vector Blueprints (SVG):**
  - `fullstack-architecture.svg`
  - `fullstack-workflow-detailed.svg`
- **22 High-Resolution Visual Slides:** Extracted and categorized modules with an interactive fullscreen lightbox zoom viewer and layout toggles (Grid, Flow, Compact).

---

## 💻 How to View Locally

Simply open `index.html` in any modern web browser:

```bash
# Double-click index.html or launch with Python:
python -m http.server 8080
```
Then visit `http://localhost:8080` in your browser.
