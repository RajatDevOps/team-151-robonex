# Team 151 — Robonex Website

Single-page site for the National Robotics League social media challenges (Team Profile, Team Introduction, Season Plan). No build step — just open `index.html` or host the folder as-is (e.g. GitHub Pages, Netlify).

## Files
- `index.html` — page content and structure
- `css/styles.css` — theme and layout
- `js/script.js` — nav toggle, scroll reveal, stat counters, member card flip, season-plan tabs
- `assets/photos/` — put team/build photos here and reference them in `index.html`

## Current roster
Mihikaa Srivastava (Team Captain), Jivansh Nangru (Lead Builder / Mechanical), Prayan Mittal (Software / Programming Lead), Arjun Aditya Gupta (Electrical / Wiring Lead), Neil Rao (Strategy / Drive Team), Parth Ojha (Media / Outreach Lead). Photos live in `assets/photos/`.

## Still worth double-checking
The season plan, timeline dates, and update copy were drafted to fit the team's real build photos — review and adjust if any detail (dates, who leads what, goals) doesn't match reality:

- **Development Timeline**: dates for Kickoff, Design Freeze, Build Phase, Testing, HYPERDRIVE competition (currently Sep–Nov 2026, competition date TBD)
- **Progress / Season Updates**: add a new card each week; duplicate the `<article class="update-card">` block
- **Gallery**: add more build/competition photos to `assets/photos/` and reference them in the `.gallery-grid`
- **Footer**: real Instagram/YouTube links and contact email (currently placeholders)

## Tip for the weekly NRL challenges
Each week's Instagram/YouTube post should link back here, and each post should tag NRL and use `#NRL_BuildWhatsNext`.
