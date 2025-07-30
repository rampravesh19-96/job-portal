# How to Setup & Run this Project

## 🛠️ Prerequisites

### ❖ Install Node.js (Skip if already installed)
1. Visit the official Node.js website.
2. Download the Node.js installer.
3. Run the installer and follow the setup instructions.

> **Note**: Always start the **Server** before running the **Client**.

---

## ⚙️ Server Setup

1. Open the project folder in **VS Code**.
2. Setup **MongoDB** and obtain your `MongoURI`.
3. Setup **Cloudinary** for image hosting.
4. Setup **Clerk** for user authentication.
5. (Optional) Setup **Sentry** for error monitoring.
6. Push the project to GitHub.
7. Deploy the backend to a hosting platform to obtain your backend URL.
8. Configure **Clerk Webhooks** with your backend URL and redeploy the backend.

> ✅ Make sure the server is deployed and running in the background before starting the client.

---

## 💻 Client Setup

1. Open the client folder in the integrated terminal.
2. Install dependencies:
   ```bash
   npm install
