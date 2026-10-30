# JK Score Live — Free starter website

A responsive starter website for Jammu & Kashmir cricket leagues and tournaments.

## Run it on your phone or computer
1. Download and extract `jk-score-live-website.zip`.
2. Open `index.html` in Chrome, Edge, Firefox, or another modern browser.
3. Tap **Admin Panel** to add matches, update scores, add teams and add players.
4. Use **Export backup** regularly to save your data. Import a previous JSON backup if needed.

## Included
- Match centre with live/upcoming/completed filters and search
- Manual match and score entry
- Fixtures and results
- Basic points table (win = 2 points; tie/no winner = 1 point)
- Teams and player directory
- JSON export/import backup
- Responsive mobile layout

## Important limitations
- Sample matches and scores are demonstration data, not verified real results.
- The app stores data in the browser's local storage. It is not a shared database.
- If you publish this exact static file, each visitor's browser has its own data. Admin edits will **not** automatically appear for all visitors.
- The Admin Panel is a prototype and has no secure login. Do not treat it as a production admin system.
- For a real public live-score service, add a shared backend (for example, Firebase or Supabase), secure administrator authentication, access rules, and backups. Only publish official/verified schedules and scores.
- JKCA/domestic fixtures are not automatically fetched. Add them manually only after checking official sources and permissions.

## Free hosting option
You can host the static demo for free using GitHub Pages:
1. Create/sign in to a GitHub account.
2. Create a new public repository, e.g. `jk-score-live`.
3. Upload `index.html` and `README.md`.
4. In repository **Settings → Pages**, choose deployment from the main branch and root folder.
5. Save and open the published URL shown by GitHub Pages.

This is suitable for showing the design/demo. It does **not** solve shared score updates; a shared backend is needed for that.
