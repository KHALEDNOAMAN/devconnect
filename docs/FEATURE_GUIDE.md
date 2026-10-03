# DevConnect - Feature Guide

## Core Features
| Feature | Description |
|---------|-------------|
| Developer Profiles | Showcase skills, projects, experience |
| Social Feed | Share updates, articles, code snippets |
| Messaging | Real-time chat between developers |
| Job Board | Post and find developer positions |
| Project Collaboration | Find teammates for projects |

## Tech Stack
| Layer | Technology |
|-------|-----------|
| Frontend | React/Next.js + TypeScript |
| Backend | Node.js + Express |
| Database | MongoDB/PostgreSQL |
| Real-time | Socket.io/WebSocket |
| Auth | JWT + OAuth (GitHub, Google) |

## Getting Started
```bash
git clone https://github.com/Hamidooh/devconnect.git
cd devconnect
npm install
cp .env.example .env
npm run dev
```

## API Endpoints
| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/auth/register | Create account |
| POST | /api/auth/login | Login |
| GET | /api/profiles | Browse developers |
| POST | /api/posts | Create post |
| GET | /api/jobs | Browse job listings |