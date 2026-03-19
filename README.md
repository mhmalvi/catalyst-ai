# Catalyst AI

A comprehensive AI agent builder and management platform that enables teams to create, deploy, and monitor intelligent automation agents through an intuitive dashboard.

## Features

- **AI Agent Builder** — Create and configure custom AI agents with tailored behaviors and capabilities
- **Task Automation** — Design automated workflows powered by AI agents for repetitive processes
- **Performance Analytics** — Track agent performance with interactive charts and detailed metrics
- **Team Collaboration** — Multi-user workspace with role-based access for collaborative agent management
- **Real-Time Monitoring** — Live dashboards to observe agent activity and system health
- **Agent Management** — Centralized control panel for deploying, pausing, and configuring agents

## Tech Stack

| Component | Technology |
|-----------|------------|
| Framework | Next.js 13 |
| Language | TypeScript |
| Styling | Tailwind CSS |
| UI Components | Radix UI |
| Charts | Recharts |

## Prerequisites

- Node.js 14+
- npm 6+

## Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/mhmalvi/catalyst-ai.git
cd catalyst-ai
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Configure Environment

Create a `.env.local` file with your configuration:

```env
NEXT_PUBLIC_API_URL=your_api_endpoint
```

### 4. Start Development Server

```bash
npm run dev
```

The application will be available at `http://localhost:3000`.

### 5. Build for Production

```bash
npm run build
npm start
```

## Key Modules

| Module | Description |
|--------|-------------|
| Agent Builder | Visual interface for designing AI agent logic and behavior |
| Dashboard | Overview of all agents, tasks, and system-wide metrics |
| Analytics | Performance charts, usage statistics, and trend analysis |
| Team Management | User invitations, role assignments, and access control |
| Monitoring | Real-time agent logs, error tracking, and health indicators |

## License

This project is open source and available under the [MIT License](LICENSE).
