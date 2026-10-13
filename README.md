# Healthcare Web Starter

A minimal Next.js application prepared as a starting point for a healthcare-themed web project.

## Current status

The implemented home page displays a **Home** heading. Healthcare workflows, patient records, appointments, authentication, and clinical functionality are not implemented in the current repository.

This repository is useful for exploring the initial Next.js App Router structure and styling setup before adding domain features.

## Run locally

Download and extract the repository. From its root, with Node.js and npm installed:

```bash
npm install
npm run dev
```

Open `http://localhost:3000` to view the starter page.

```bash
npm run build
npm start
```

## Structure

| Path | Responsibility |
| --- | --- |
| [app/page.tsx](app/page.tsx) | Current Home page |
| [app/layout.tsx](app/layout.tsx) | Shared application layout |
| [app/globals.css](app/globals.css) | Global styles |
| [tailwind.config.ts](tailwind.config.ts) | Tailwind configuration |
| [package.json](package.json) | Next.js scripts and dependencies |

The current request flow is simply **browser → Next.js route → page component**. There is no application backend or database configuration to set up.

## Development

Edit `app/page.tsx` to change the page and use `app/layout.tsx` for shared structure. The stack is Next.js 14, React 18, TypeScript, and Tailwind CSS. Keep the README aligned with the features that are actually implemented as the project grows.
