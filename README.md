# USTR SUITS — Interactive Clothing Rack

Next.js App Router + TypeScript + Tailwind CSS + Framer Motion starter.

## Run locally
- Install Node.js 20+
- Run `npm install`
- Run `npm run dev`
- Open http://localhost:3000

## Build
Run `npm run build`.

## Product images
Place transparent WebP files in `public/products/`. The photos must already contain the hanger:
- `<slug>-side.webp`
- `<slug>-front.webp`
- `<slug>-back.webp` (optional)

Edit `lib/products.ts` to add real products, colours and store URLs. The sample catalogue is placeholder data. No product photos are included.

## Push to GitHub
Create an empty GitHub repository, extract this ZIP, upload the contents of this folder to the repository root, then commit and push. Import the repository into Vercel for deployment.

## Important
This repository is the animated storefront frontend starter. It does not yet implement a real database, inventory, checkout, payments, customer accounts, orders or the private owner admin dashboard. Add a backend such as Supabase, server-side authorization and a payment gateway before accepting real orders. The current demo availability links are placeholders.
