# Team 151 — Robonex Website

Single-page site for the National Robotics League social media challenges (Team Profile, Team Introduction, Season Plan). No build step — just open `index.html` or host the folder as-is (e.g. GitHub Pages, Netlify).

## Files
- `index.html` — page content and structure
- `css/styles.css` — theme and layout
- `js/script.js` — nav toggle, scroll reveal, stat counters, member card flip, season-plan tabs
- `assets/photos/` — put team/build photos here and reference them in `index.html`

## What to customize
Search `index.html` for `[Edit:` and `[Member Name]` / `[Photo]` / `[Date]` — every one marks a placeholder:

- **Header/Hero**: tagline under the team name
- **Team Profile**: mission statement, member count stat
- **Meet the Roster**: replace each member card's name, role, and responsibilities; swap the photo placeholder for `<img>` tags pointing to `assets/photos/`
- **What Makes Robonex Unique**: three highlight bullets
- **Season Plan tabs**: Game Brainstorm, Robot Build Plan, Skill-Building, Competition Goals
- **Development Timeline**: dates for Kickoff, Design Freeze, Build Phase, Testing, HYPERDRIVE competition
- **Progress / Season Updates**: add one card per week; duplicate the `<article class="update-card">` block
- **Footer**: real Instagram/YouTube links and contact email

## Tip for the weekly NRL challenges
Each week's Instagram/YouTube post should link back here, and each post should tag NRL and use `#NRL_BuildWhatsNext`.
