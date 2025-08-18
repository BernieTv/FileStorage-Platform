<img src="https://res.cloudinary.com/bekzod-tiny-house/image/upload/v1755504867/Screenshot_from_2025-08-18_13-13-06_udlvmy.png" alt="Project Banner" />

<br/>

# 🌟 FileStorage Platform

A **next‑gen cloud storage solution** where speed, security, and simplicity collide. 🚀 Built with the **MERN Stack**, this platform lets you upload, manage, and share files effortlessly while packing in serious power with AWS S3, JWT auth, analytics, and a slick modern UI. Perfect for devs, teams, or anyone who vibes with **secure & scalable file management**.

---

## 🗝️ Key Features: 👇

- 🔐 Authentication (Email + Password with JWT)
- 📊 Analytics & Charts for Storage Insights
- 📤 Multiple File Uploads
- ☁️ AWS S3 Integration for Secure & Scalable Storage
- 💾 Storage Tracking for Each User
- 📚 Bulk File Download as Zip
- 📦 TypeScript SDK Published to npm
- 🔑 API Key Authentication for Secure Access
- 📅 Pagination & File Search
- 📝 Logging with Logtail
- 🚀 Deployment Ready
- 🌐 Built with MERN Stack (Node.js, MongoDB, React 19)
- 🎨 Styled with Tailwind v4 & Shadcn/ui

---

## 🛠️ Tech Stack

- **Frontend:** React 19, TypeScript, TailwindCSS v4, Shadcn/ui, Vite
- **Backend:** Node.js, Express.js, TypeScript, MongoDB, JWT, Passport.js
- **Cloud & Storage:** AWS S3
- **Logging & Monitoring:** Logtail
- **State Management:** Redux Toolkit
- **Package Management:** npm

---

## 📂 Simplified Project Structure

```
.
├── backend         # Node.js + Express API
│   ├── src
│   │   ├── config       # Configurations (DB, AWS, JWT, etc.)
│   │   ├── controllers  # API Controllers
│   │   ├── middlewares  # Authentication & Error Handling
│   │   ├── models       # MongoDB Models
│   │   ├── routes       # API Routes (Internal & Public)
│   │   ├── services     # Business Logic
│   │   ├── utils        # Helper Functions
│   │   └── validators   # Request Validators
│   └── tsconfig.json
│
├── client          # React Frontend
│   ├── src
│   │   ├── app          # Redux & API Client
│   │   ├── components   # UI Components
│   │   ├── features     # Feature Modules (Auth, Files, Analytics)
│   │   ├── layouts      # Page Layouts
│   │   ├── pages        # Page-Level Components
│   │   ├── routes       # Routing Config
│   │   └── hooks        # Custom Hooks
│   └── vite.config.ts
│
├── sdk             # TypeScript SDK Published to npm
├── README.md       # Documentation
```

---

## ⚙️ Environment Variables

### Backend (`.env`)

```
PORT=5000
NODE_ENV=development
MONGO_URI=your_mongo_connection_string
JWT_SECRET=your_jwt_secret
JWT_EXPIRES_IN=1d
LOG_LEVEL=info
LOGTAIL_SOURCE_TOKEN=your_logtail_token
LOGTAIL_INGESTING_HOST=your_logtail_host
AWS_ACCESS_KEY=your_aws_key
AWS_SECRET_KEY=your_aws_secret
AWS_REGION=your_aws_region
AWS_S3_BUCKET=your_bucket_name
ALLOWED_ORIGINS=http://localhost:5173
```

### Frontend (`.env`)

```
VITE_BASE_API_URL=http://localhost:5000/api
VITE_API_URL=http://localhost:5000
VITE_REDUX_PERSIST_SECRET_KEY=your_secret_key
```

---

## 🚀 Installation & Setup

Clone the repository:

```bash
git clone https://github.com/BernieTv/FileStorage-Platform.git
cd FileStorage-Platform
```

### Backend Setup

```bash
cd backend
npm install
npm run dev
```

### Frontend Setup

```bash
cd client
npm install
npm run dev
```

---

💡 Designed for **builders and creators**, this platform turns file storage into a smooth, secure, and scalable experience ✨.
