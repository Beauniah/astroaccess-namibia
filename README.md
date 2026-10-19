# AstroAccess Namibia — concept prototype

A responsive, frontend-only React + Vite demonstration of an astronomy travel-kit rental service for the AstroBizNet proposal.

## Run locally

```bash
npm install
npm run dev
```

Open the local URL shown by Vite (usually http://localhost:5173).

## Build

```bash
npm run build
```

The static build will appear in `dist/`.

## Deploy with HTTPS

Import this folder or its GitHub repository into Vercel or Netlify. Use the Vite defaults: build command `npm run build`, output directory `dist`. Hosting providers normally give a hosted HTTPS URL automatically. No custom domain needed for this demo. Check current free-tier terms before deploying.

## IMPORTANT — this is a prototype

- The three products, prices, deposits, and collection arrangements are **illustrative, not actual available rentals**.
- The date selection and rental estimate are calculated in your browser. Clicking Preview request **does not transmit, store, or submit a booking**.
- The kit instruction booklet is a mock preview; no downloadable videos or real customer support are implemented.
- The estimated rental charges assume the example two-night price is charged for every started two-night block.
- Prototype has no payment integration, real availability, database, authentication, backend or analytics.
- Before turning this into a real service, validate the customer need, confirm equipment / warranty / insurance / pricing, implement safety and real booking operations, and review relevant legal/privacy requirements.

All artwork is rendered using CSS, icons and emoji placeholders, rather than implying ownership of particular telescope product photos. External Google fonts are optional and fall back to Arial.
