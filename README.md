<div align="center">

# 🔼 PayUp

A PayPal like web app built using the MERN stack.

</div>

<br>

## 🧰Tech used

- 💻Frontend
  - React
  - React Router
  - TypeScript
  - Shadcn UI
  - TailwindCSS
- 🗃 Backend
  - Express.js
  - Mongoose
  - Zod

## 🛠 Setup locally

**Prerequisite:** 

1. **Clone the project**

```bash
git clone https://github.com/DhirajMohata/payup
```

2. **Navigate to project directory**

```bash
cd payup
```

3. **Navigate to backend directory and install the dependencies**

```bash
cd backend
pnpm install
```

4. **Create a .env file with the following variables and add your credentials**

```bash
touch .env
```

```bash
MONGO_URL="YOUR_MONGO_URL_HERE"
PORT=5001
FRONTEND_URL="http://localhost:5173"
JWT_SECRET="YOUR_SUPER_SECRET_CODE_HERE"
```

5. **Start the server**

```bash
npm run server
```

6. **Navigate to frontend directory and install the dependencies**

```bash
cd frontend
pnpm install
```

7. **Create a .env file with the following variables and add your credentials**

```bash
touch .env
```

```bash
VITE_API_BASE_URL="YOUR_BACKEND_URL_HERE"
```

8. **Start the frontend**

```bash
npm run dev
```