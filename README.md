# Chairside — Salon Studio

A responsive, local-first salon management prototype for demonstrating appointment scheduling, customer profiles, loyalty points, demo wallet credits, service pricing and salon analytics.

## Run it

No build tools, API keys, or package installation are required.

1. Clone or download this repository.
2. Open `index.html` in a modern browser, or serve the folder using a static server.
3. Try the seeded demo data, navigation, forms, booking status actions, customer profiles, reward tools, and CSV exports.

With Python installed, run `python -m http.server 8080` from the project folder, then open http://localhost:8080.

## Included features

- Responsive owner dashboard, schedule, customer summaries and illustrative revenue chart.
- Create/edit appointments, status changes, and completion flow that updates customer visits, spend and loyalty points.
- Customer records, search, visit history and CSV export.
- Editable salon service menu, pricing, durations, descriptions and visibility.
- Configurable loyalty points, reward redemption, demo wallet credits and referral tracking.
- Salon profile settings, browser-local persistence, CSV reports and JSON backup/reset.
- Responsive mobile navigation, accessible dialog labels, keyboard dismissal and form validation.

## Prototype limitations — read before real use

This is a front-end demonstration, not a production multi-user service. Data is stored in the current browser with `localStorage`; it does not sync across devices or accounts. Some preloaded records and the revenue trend are illustrative. Wallet balances and reward redemption are bookkeeping simulations only: no funds are collected or transferred. No authentication, real online booking from public customers, payments, automated WhatsApp/SMS/email reminders, server-side backups, or hosted database are configured.

Before handling real customer data, add a secure backend/database, staff authentication and authorization, server-side validation, privacy/consent handling and backups. Use vetted payment and messaging providers with credentials stored only on the server.

## Deploy

The project is static and can be hosted on GitHub Pages, Netlify or Vercel. On GitHub, enable Pages deployment from the `main` branch and repository root in Settings → Pages.

## Files

- `index.html` — app shell and navigation
- `styles.css` — responsive design system and UI
- `app.js` — rendering, local state, modal forms, demo workflows and exports
