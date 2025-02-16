# PMT-ERA: Enterprise Ready Agile Project Management Tool

PMT-ERA is a modern, enterprise-grade project management solution designed to help teams streamline their agile workflows, track progress, and deliver successful projects.

## 🚀 Features

- **Project Dashboard**: Get a comprehensive view of all your projects and their current status
- **Task Management**: Create, assign, and track tasks with customizable workflows
- **Agile Boards**: Visualize work progress with Kanban and Sprint boards
- **Team Collaboration**: Built-in tools for team communication and collaboration
- **Time Tracking**: Monitor time spent on tasks and projects
- **Custom Workflows**: Create and customize workflows that match your team's process
- **Reporting & Analytics**: Generate detailed reports and insights about project progress
- **Role-Based Access Control**: Secure, granular control over user permissions

## 🛠 Tech Stack

- Next.js 14 - React Framework
- Bun - JavaScript Runtime & Package Manager
- Appwrite - Backend as a Service (BaaS)
  - Authentication
  - Database
  - Storage
  - Functions
- Hono.js - Lightweight, Ultrafast Web Framework
- Tailwind CSS - Styling
- TypeScript - Programming Language

## 📋 Prerequisites

- Bun >= 1.0.0
- Node.js >= 18.17.0
- Git
- Appwrite Instance (Cloud or Self-hosted)

## 🚦 Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/eranga-dev/pmt-era.git
   cd pmt-era
   ```

2. Install dependencies:
   ```bash
   bun install
   ```

3. Set up your environment variables:
   ```bash
   cp .env.example .env
   ```
   Update the `.env` file with your Appwrite credentials:
   ```
   APPWRITE_ENDPOINT=your-appwrite-endpoint
   APPWRITE_PROJECT_ID=your-project-id
   APPWRITE_API_KEY=your-api-key
   ```

4. Start the development server:
   ```bash
   bun run dev
   ```

Visit `http://localhost:3000` to see the application running.

## 🏗 Project Structure

```
pmt-era/
├── app/             # Next.js app directory
├── components/      # Reusable UI components
├── lib/            # Utility functions and shared logic
├── api/            # Hono.js API routes
├── services/       # Appwrite service integrations
├── public/         # Static files
└── styles/         # Global styles
```

## ⚡ API Architecture

PMT-ERA uses a combination of Hono.js and Appwrite:
- Hono.js handles API routing and middleware
- Appwrite provides:
  - User authentication and management
  - Real-time database operations
  - File storage
  - Serverless functions
  - Team management



---

Built with ❤️ by the PMT-ERA Team