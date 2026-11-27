# Parkwise · P07 Campus Parking Guidance (CP6 Updated Build)

## Artwork Setup
Save the three generated Gamma-style clay/paper-cut illustrations into `public/images/`:
1. `public/images/campus-pathway.jpg` — Curved campus parking pathway arch with scooter and car
2. `public/images/zone-tokens.jpg` — Connected terracotta and sage parking zone tokens
3. `public/images/attendant-keys.jpg` — Parking attendant keys and directional board badge

## CP6 Changes Implemented
- **P1 · Reset All Confirmation (`C-01`)**: Confirmation dialog asking *"Reset all four lot statuses to Available?"* with `Cancel` and `Confirm reset`.
- **P1 · Per-Lot Status Freshness (`C-02`)**: Displays exact `Updated HH:MM` timestamp per lot (`Building 34`, `Building 56`, `BH1`, `BH4`) plus a clear *"Manually updated by parking staff"* disclosure.
- **P2 · Single Role-Based Navigation (`C-03`, `C-04`)**: Eliminates duplicate top+bottom navigation bars on mobile; shows only the selected role's workspace (`I'm parking` vs `I'm updating a lot`).
- **P2 · Saved-At Timestamp & Local Note (`C-07`, `C-08`)**: Shows `Saved at HH:MM` distinct from lot update time, plus a local-device storage note.
- **P2 · Accurate QR Deep-Link Wording (`C-06`)**: Explains `?zone=A1..B2` prefill links accurately with manual `A1–B2` fallback.
