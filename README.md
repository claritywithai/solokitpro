# SoloKit Pro

**Invoice generator, time tracker, and tax tools for freelancers — all in one browser-based dashboard.**

🔗 Live site: [claritywithai.org](https://claritywithai.org)

SoloKit Pro is a lightweight productivity toolkit built for freelancers and solo founders. No install, no bloated software — everything runs in the browser, with optional cloud backup for your data.

## Features

- **📄 Invoice Generator** — Create professional, branded PDF invoices with your logo, accent color, multiple currencies, tax and discount fields, and saved clients.
- **🧾 Statement Analyzer** — Upload a bank/payment statement and get a quick breakdown of income, fees, and recurring subscriptions.
- **📊 Fee Calculator** — Compare payout fees across payment platforms (PayPal, Wise, Payoneer, etc.) before you choose how to get paid.
- **⏱️ Time Tracker** — Track billable hours per project and send tracked time straight to an invoice.
- **💰 Tax Set-Aside** — Estimate how much to set aside for taxes, including freelance/export income tax calculations.

## Tech stack

- Plain HTML/CSS/JS (no build step) + [Tailwind CSS](https://tailwindcss.com/) via CDN
- [Supabase](https://supabase.com/) for auth, storage, and cloud backup
- [jsPDF](https://github.com/parallax/jsPDF) for PDF generation
- [PapaParse](https://www.papaparse.com/) for CSV parsing
- [pdf.js](https://mozilla.github.io/pdf.js/) for reading uploaded statements
- [Lucide](https://lucide.dev/) icons

## Getting started (self-hosting)

1. Clone this repo.
2. Open `index.html` and follow the in-app setup screen to connect your own [Supabase](https://supabase.com/) project (needed for accounts, trial gating, and cloud backup).
3. Deploy the static files anywhere — Cloudflare Pages, GitHub Pages, Netlify, or Vercel all work since there's no build step.

## Pricing

Try every tool free with sample data — no signup required. Full access is a one-time payment, no subscription.

## License

All rights reserved. This code is provided for reference; redistribution or resale of this tool is not permitted without permission.
