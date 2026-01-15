# React Next Workflow

A simple Next.js React application with TypeScript and Tailwind CSS.

## Tech Stack

- **Next.js 16.1.1** with **React 19.2.3**
- **TypeScript** configured with strict mode
- **App Router** (`src/app/` directory structure)
- **Path alias** `@/*` → `./src/*` for clean imports

## Styling

- **Tailwind CSS v4** with PostCSS
- **Geist fonts** (Sans & Mono) from Google Fonts
- Dark mode support via `prefers-color-scheme`
- CSS variables for theming (`--background`, `--foreground`)

## Development Tools

- **ESLint 9** with `eslint-config-next`
- TypeScript type definitions for Node, React, and React DOM

## Available Scripts

```bash
npm run dev      # Start development server
npm run build    # Build for production
npm run start    # Start production server
npm run lint     # Run ESLint
```

## Project Structure

```
src/
  app/
    layout.tsx    # Root layout with fonts
    page.tsx      # Home page
    globals.css   # Global styles + Tailwind
    favicon.ico
public/           # Static assets
```

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```

3. Open [http://localhost:3000](http://localhost:3000) in your browser.
