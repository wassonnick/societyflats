# SocietyFlats v1.0 Frontend Prototype

Fresh prototype based on the locked blueprint:

- Product Strategy v1.0
- Information Architecture v1.0
- Database Architecture v1.0
- Design System v1.0
- UI Component Specification v1.0

## Included Screens

- Homepage
- Search results
- Listing detail
- Society detail
- Owner post-property form
- Tenant dashboard shell
- Admin dashboard shell

## How to Run Locally

Install Node.js first.

```bash
npm install
npm run dev
```

Open the local URL shown in terminal.

## How to Deploy

### Vercel

1. Upload this folder to GitHub.
2. Import repository in Vercel.
3. Framework: Vite.
4. Build command: `npm run build`.
5. Output directory: `dist`.

### cPanel/static hosting

```bash
npm install
npm run build
```

Upload the contents of the `dist` folder to your public HTML folder.

## Important

This is the first frontend prototype only. It uses mock data and does not include the Laravel/PostgreSQL backend yet.

Next build phase:

1. Convert mock data into API contracts.
2. Build Laravel backend modules.
3. Add PostgreSQL database migrations.
4. Add authentication and role-based dashboards.
5. Connect frontend to backend APIs.

## Sprint 2 Premium Real Estate Identity Upgrade

This package upgrades the V1 prototype with:

- Full-bleed image hero with overlay search
- Trust metrics strip
- Featured society marketplace cards
- Lifestyle discovery section
- Rental intelligence charts/progress cards
- Society-first property card hierarchy
- Premium society detail hero
- Why-this-society conversion block
- Expanded SEO footer
- Improved visual depth using warm/sand sections

Run locally:

```bash
npm install
npm run dev
```

Build for Vercel:

```bash
npm run build
```
