# 🌐 EventSphere Project Workspace

Welcome to the **EventSphere** repository. This is a task management and smart event hosting application.

The codebase is organized as follows:

*   **[`management/`](file:///D:/Hanzala/task%20management/management)**: The core Next.js application, including the front-end components, back-end API routes, custom Socket.io server, database schemas, and configuration files.

---

## 🚀 Quick Start Guide

To get the application up and running on your local machine:

### 1. Prerequisites
Make sure you have [Node.js](https://nodejs.org/) installed (v18+ recommended) and a running instance of [MongoDB](https://www.mongodb.com/).

### 2. Install Dependencies
Navigate into the application directory and install the required npm packages:
```bash
cd management
npm install
```

### 3. Environment Setup
Create a `.env.local` file inside the `management` folder:
```env
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_super_secret_jwt_key
```
*(If no environment variables are defined, the app will fall back to `mongodb://localhost:27017/eventsphere` and a default development JWT key).*

### 4. Run the Application
To enable full real-time Socket.io and dashboard features, launch the custom server:
```bash
npm run server
```

The application will start and be available at: **http://localhost:3000**

---

For more details on features, components, and project architecture, please refer to the inner **[management/README.md](file:///D:/Hanzala/task%20management/management/README.md)**.
