# Smart Cutz — Salon Manager (MVP demo)

Bilingual (English / العربية) salon management system for men's salons in Qatar.
Single-file web app — open `index.html` or host on GitHub Pages. No server, no install.

## What's in this MVP (Phase 1 of the proposal)
- **Dashboard** — today's takings, services, average ticket, queue, bookings, lapsed clients with one-click WhatsApp reminders
- **Bookings** — day view per barber, 30-minute slots, click to book, start → checkout
- **Walk-in queue** — ticket numbers, estimated wait, assign barber, start, checkout, no-show
- **Checkout (POS)** — Smart / Relax / Signature / Kids service lines, retail products, membership visit redemption, discount, cash/card, receipt, WhatsApp receipt
- **Clients** — visit history, spend, preferred barber, membership, active/lapsed status, "due back" flag, WhatsApp nudge
- **Services & products** — prices, durations, stock
- **Barbers** — commission %, monthly takings and commission due
- **Reports** — last 7 days, takings by barber, service mix, retail share, retention
- **Settings** — hours, slot length, membership plans, reset demo data

## Demo notes
- Data is stored in the browser (`localStorage`). "Reset demo data" in Settings restores the sample set.
- Phone numbers, C.R. and prices are sample/placeholder values from the proposal.
- Phase 2 (retention automation, memberships & loyalty, stock) and Phase 3 (dashboard, multi-branch, client app) are scoped in the proposal deck; a production version adds a cloud database, user logins and WhatsApp Business API sending.

## Run on GitHub Pages
Settings → Pages → Source: *Deploy from a branch* → `main` / root. The app is then live at `https://<user>.github.io/<repo>/`.
