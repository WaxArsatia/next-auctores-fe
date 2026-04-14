# next-auctores-fe

Frontend web app for Auctores, built with Next.js (App Router). The current implementation is a single-page landing experience with multiple sections and reusable UI primitives.

## Features

- Single-page layout with sections: Hero, About, Our Work, Get Involved, and Contact.
- Reusable UI components in `src/components/ui` (`Button`, `Card`, `Input`, `Textarea`).
- Tailwind CSS styling with custom colors defined in `tailwind.config.ts`.
- SVG illustrations served from `public/`.
- `@vercel/speed-insights` integrated in the root layout.

## Tech Stack

- Next.js 14 (App Router)
- React 18 + TypeScript
- Tailwind CSS
- shadcn/ui-style component setup (`components.json`)
- Lucide React icons
- ESLint (`next/core-web-vitals`)

## Setup and Run

Install dependencies:

```bash
npm install
```

Run in development mode:

```bash
npm run dev
```

Build for production:

```bash
npm run build
```

Start production server:

```bash
npm run start
```

Run lint:

```bash
npm run lint
```

This project also includes `bun.lockb`, so you can use Bun if preferred.

## Project Structure

```text
next-auctores-fe/
├─ public/
│  ├─ undraw_about_us_page.svg
│  └─ undraw_programming.svg
├─ src/
│  ├─ app/
│  │  ├─ favicon.ico
│  │  ├─ globals.css
│  │  ├─ layout.tsx
│  │  └─ page.tsx
│  ├─ components/
│  │  └─ ui/
│  │     ├─ button.tsx
│  │     ├─ card.tsx
│  │     ├─ input.tsx
│  │     └─ textarea.tsx
│  └─ lib/
│     └─ utils.ts
├─ components.json
├─ tailwind.config.ts
└─ package.json
```

## License

No license file is currently present in this repository.
