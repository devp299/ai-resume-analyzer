# CVSmart – AI Resume Analyzer & Application Tracker

Empower your job search with intelligent, real-time resume feedback.

---

CVSmart is an **AI-powered web app** for uploading, analyzing, and tracking resumes—helping you optimize your job applications with instant, actionable feedback. Built using React, TypeScript, Tailwind CSS, and React Router for a seamless user and developer experience.

---

## 🚀 Features

- **AI Resume Analysis:** Upload your resume and get smart feedback in seconds.
- **Application Tracker:** Organize & monitor all your job applications in one dashboard.
- **Instant Feedback:** Receive actionable, AI-powered insights to improve your resume.
- **Modern UI:** Responsive, accessible, and beautiful design powered by Tailwind CSS.
- **TypeScript & Hot Reload:** Type-safe, fast development with Vite and HMR.
- **Production Ready:** SSR, Docker-ready, and fully optimized for deployment.

---

## 📺 Demo

[Watch the project demo on YouTube](https://www.youtube.com/watch?v=ARJ17VOyLfc)

---

## 🛠️ Getting Started

### 1. Installation

Install the dependencies:

```bash
npm install
```

### Development

Start the development server with HMR:

```bash
npm run dev
```

Your application will be available at `http://localhost:5173`.

## Building for Production

Create a production build:

```bash
npm run build
```

## Deployment

### Docker Deployment

To build and run using Docker:

```bash
docker build -t my-app .

# Run the container
docker run -p 3000:3000 my-app
```

The containerized application can be deployed to any platform that supports Docker, including:

- AWS ECS
- Google Cloud Run
- Azure Container Apps
- Digital Ocean App Platform
- Fly.io
- Railway

### DIY Deployment

If you're familiar with deploying Node applications, the built-in app server is production-ready.

Make sure to deploy the output of `npm run build`

```
├── package.json
├── package-lock.json (or pnpm-lock.yaml, or bun.lockb)
├── build/
│   ├── client/    # Static assets
│   └── server/    # Server-side code
```

## Styling

This template comes with [Tailwind CSS](https://tailwindcss.com/) already configured for a simple default starting experience. You can use whatever CSS framework you prefer.

---

Built with ❤️ using React Router.
