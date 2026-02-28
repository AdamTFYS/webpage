# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Structure

The repository contains a single Next.js app at `subagent_inspo/`. All development work happens inside that subdirectory.

## Commands

Run from inside `subagent_inspo/`:

```bash
npm run dev      # Start development server at http://localhost:3000
npm run build    # Production build
npm run lint     # ESLint (Next.js core-web-vitals + TypeScript rules)
```

## Architecture

- **Framework**: Next.js 16 with the App Router (`app/` directory)
- **Language**: TypeScript (strict mode enabled)
- **Styling**: Tailwind CSS v4
- **Path alias**: `@/*` resolves to the project root (`subagent_inspo/`)

The entry point is `app/page.tsx`. The root layout (`app/layout.tsx`) applies Geist Sans and Geist Mono fonts globally via CSS variables and sets up metadata.
