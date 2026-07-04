# Pulse — Clickable Prototype

Standalone, click-through UX prototype for Pulse (nightlife discovery app for Singapore). No backend, no build step — just open `index.html` in a browser.

This is a design/UX sandbox, separate from the real app (`pulse-app-main`, the Next.js + Supabase implementation). Once a flow is validated here, it gets built for real in that repo.

## Screens

**Consumer**
- `consumer-map.html` — live event pins on the map
- `consumer-explore.html` — search & filters
- `consumer-event-idle.html` — event card before requesting a perk
- `consumer-event-perk-revealed.html` — event card after perk is unlocked
- `consumer-perks-wallet.html` — active + used perks

**Venue**
- `venue-dashboard.html`
- `venue-events-new-step1.html` / `step2` / `step3` — new event creation flow
- `venue-monitor.html` — live claim queue
- `venue-claims.html` — claims history

## Running it

Just open `index.html` in a browser, or serve the folder locally:

```
npx serve .
```

## Collaborating

Both contributors can edit these files directly and push to this repo. Keep screens as flat, linked HTML files (no build tooling) so it's trivial to open and review changes.
