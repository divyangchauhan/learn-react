# Chirp - Social Media App

A social media application built for learning React.js, featuring a modern monorepo architecture.

## Architecture

This project uses a pnpm monorepo structure with:

- **Frontend**: React.js with Vite (`apps/frontend`)
- **Backend**: NestJS (`apps/backend`)

## Getting Started

### Prerequisites

- Node.js >= 18.0.0
- pnpm >= 8.0.0

### Installation

```bash
# Install all dependencies
pnpm install
```

### Development

```bash
# Run both frontend and backend concurrently
pnpm dev

# Or run individually:
pnpm dev:frontend  # React frontend on http://localhost:5173
pnpm dev:backend   # NestJS backend on http://localhost:3000
```

### Build

```bash
# Build frontend
pnpm build:frontend

# Build backend
pnpm build:backend
```

## Project Structure

```
chirp-monorepo/
├── apps/
│   ├── frontend/          # React + Vite frontend
│   └── backend/           # NestJS backend
├── package.json           # Root package.json
├── pnpm-workspace.yaml    # Workspace configuration
└── README.md
```

## Learning Goals

This project is designed for learning React.js fundamentals through building a social media application called "Chirp".
