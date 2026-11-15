# Masters Cove

A cozy planner for masters applications: a dashboard with a milestone countdown, a planner, a program shortlist (USA and Germany), a documents and attestation checklist, and a motivational note each time you open it.

## Profiles and privacy

Each person makes their own profile the first time they open the page. A profile's plan is saved only in that person's browser (`localStorage`). Nothing is sent to a server, so nobody else can see your plan, and your plan does not sync between devices.

Use **Profile → Download backup** now and then. To move your plan to another device, download a backup there and use **Profile → Restore from backup**.

## Run it

It's a single `index.html` with no build step. Open it in a browser, or host it on GitHub Pages.

## Change the theme

All colours and fonts are CSS variables at the top of `index.html` (the `:root` block, plus the dark-mode blocks under it).
