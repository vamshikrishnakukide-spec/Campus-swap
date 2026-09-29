# CampusSwap — Frontend Only

This version is the backend-free conversion of CampusSwap. It preserves the major pages and UI while replacing Express/SQLite/session APIs with browser JavaScript + localStorage.

## Run
1. Extract the ZIP.
2. Open `index.html` in Chrome/Edge.
3. No Node.js, npm, Express or SQLite is required.

## Demo login
`aarav@cmr.edu` / `student123`

## Included
- 700 seeded demo listings (100 per category)
- 7 categories
- Search, filters and free-only filter
- Product details and related listings
- Local login/register
- Local wishlist
- Local sell-item flow with compressed image upload
- Local dashboard and sold/available status
- Local profiles
- Local chat and built-in CampusSwap AI helper
- Real photographic image URLs; no SVG/mock product graphics

## Frontend-only limitations
There is no central server/database. Accounts, listings, wishlist and messages are stored only in the current browser's localStorage. Chat is local/demo and does not send messages to another device. Clearing browser storage resets the demo data. Remote product photos require internet access.
