# BOOKED — The 8-Module DJ Business System

8 modules. 8 products in one. The complete DJ business toolkit by **DJ Redlite**.
**Price: $4.99 one-time** via Cash App.

## How it's sold

- `index.html` — the public **sales page** (what's inside, how it works, FAQ, buy button → Cash App).
- `toolkit.html` — the full interactive toolkit, gated behind a personal **access code**.
- Buying flow: buyer pays $4.99 (note `BOOKED`) → buyer DMs the payment screenshot to @djredlite → Atoy mints a code in his private generator → buyer enters the code to unlock. Codes are validated in-page (checksum); it's a soft gate that keeps honest buyers honest, not DRM.

## What's inside the toolkit

| # | Module | Tools |
|---|--------|-------|
| 1 | **Booking Machine** | Venue pitch script generator + outreach tracker |
| 2 | **Pricing Shield** | 3-tier rate card (editable) + objection handling scripts |
| 3 | **Fail-Safe Rig** | Survival kit checklist + emergency setup playbook |
| 4 | **Crowd Code** | Functional crate system + 3-song rescue rule planner |
| 5 | **Content Engine** | 3-type content system + weekly content calendar |
| 6 | **Music Locker** | Sunday Dig Day ritual + tagging system + track log |
| 7 | **Client Lock** | One-page DJ service agreement (print-ready) + client intake form |
| 8 | **Longevity Protocol** | Burnout prevention rules + gear/money maintenance system |

## Run it

Single self-contained HTML files — no build step, no dependencies, no server.

- **Preview locally:** open `index.html` in any browser.
- **Publish free:** enable GitHub Pages on this repo (Settings → Pages → Deploy from branch → `main`).

## Privacy

Everything the user types (pitch details, tracker rows, checklists, calendar, track log) is saved in the browser's `localStorage` on their own device. Nothing is sent anywhere.

## Customizing

- The buy-button payment link lives in `index.html` (search `cash.app`) — swap in a $4.99 Cash App **payment link** (Cash App → payment tab → enter $4.99 → Request → Share link) so the amount prefills for buyers.
- Edit default rates in the toolkit's Module 2 to match your market.
- Colors live in the `:root` block at the top of the `<style>` section.
