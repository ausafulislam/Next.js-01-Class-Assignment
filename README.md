# Next.js Class Assignment

A small multi-page website built with **Next.js 14**, **React 18**, **TypeScript**, and **Tailwind CSS**. It demonstrates basic navigation between pages using the Next.js App Router.

## Pages

The home page includes links to these routes:

- `/` — Home
- `/About` — About
- `/Services` — Services
- `/Projects` — Projects
- `/Contact` — Contact

Each page is implemented in its matching directory under `app/` (for example, `app/About/page.tsx`).

## Requirements

- Node.js (LTS recommended)
- npm

## Run locally

```bash
npm install
npm run dev
```

Visit [http://localhost:3000](http://localhost:3000) in your browser. The development server reloads as you edit files.

## Available scripts

| Command | Description |
| --- | --- |
| `npm run dev` | Start the development server with Turbopack |
| `npm run build` | Create a production build |
| `npm run start` | Serve the production build (run `npm run build` first) |
| `npm run lint` | Run the configured Next.js lint command |

## Project structure

```text
app/
├── About/page.tsx
├── Contact/page.tsx
├── Projects/page.tsx
├── Services/page.tsx
├── globals.css
├── layout.tsx
└── page.tsx
```

Global styles and Tailwind setup live in `app/globals.css` and `tailwind.config.ts`. The root layout and page metadata are defined in `app/layout.tsx`.

## Author

Built by Ausaf Ul Islam.
