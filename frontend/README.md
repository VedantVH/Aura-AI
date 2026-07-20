# Aura AI — Frontend

This directory contains the Next.js 15 frontend for the **Aura AI** chatbot system.

## Tech Stack

| Technology | Role |
| :--- | :--- |
| Next.js 15 (App Router) | UI framework and routing |
| Tailwind CSS | Utility-first styling |
| Framer Motion | Spring-physics animations |
| TypeScript | Type-safe development |

## Local Development

```bash
npm install
npm run dev
```

The development server starts at [http://localhost:3000](http://localhost:3000).

## Environment

Ensure the FastAPI backend is running on `http://localhost:8000` before starting the frontend. The chat interface communicates with the `/chat` and `/health` endpoints at that address.

## Project Structure

```bash
frontend/
├── app/              # Next.js App Router (layout, page, global styles)
├── components/       # Reusable UI components
│   └── ui/           # Core UI primitives (chat assistant, buttons)
└── lib/              # Utility functions
```
