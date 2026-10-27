# SAINDHAV ARENA

Free online games arcade with 59 fully playable browser games, no download, no sign-up.

## Deploy on Cloudflare Pages

- Connect this repository in Cloudflare Pages.
- Framework preset: None / Static.
- Build command: none.
- Build output directory: `/` (root, where `index.html` lives).

## Games

Arcade, Puzzle, Word, Board, Racing, Platform, Cards, Casual, Sports and Brain games, all in the single self-contained `index.html` with no external requests after the page loads.

## Notes

- Single-player games are in this page. Local multiplayer and online multiplayer via Cloudflare Workers / Durable Objects are planned separately and are not simulated in this page.
- True PWA manifest + service worker install is a separate deployment step on Cloudflare Pages, not included in this Muse static artifact export.
