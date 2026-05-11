# CLAUDE.md

## Project Overview

PortusAI Website — a React + Vite + Tailwind CSS web application using the Gemini API.

## Tech Stack

- React 19, TypeScript, Vite
- Tailwind CSS v4
- Lucide React (icons), Motion (animations)
- Google Gemini API (`@google/genai`)
- Express (server)

## Commands

- `npm run dev` — Start dev server on port 3000
- `npm run build` — Production build
- `npm run lint` — Type-check with tsc
- `npm run preview` — Preview production build

## UI/UX Design Intelligence

This project includes the **ui-ux-pro-max** skill for design assistance. Use the search tool for design decisions:

```bash
python3 src/ui-ux-pro-max/scripts/search.py "<query>" --domain <domain>
```

Domains: `product`, `style`, `typography`, `color`, `landing`, `chart`, `ux`

Stack search (default html-tailwind):
```bash
python3 src/ui-ux-pro-max/scripts/search.py "<query>" --stack react
```
