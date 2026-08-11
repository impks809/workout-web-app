# FitLock

A static, GitHub Pages-ready fitness tracker with:

- date-based automatic workout progression
- one-exercise-at-a-time locking; future exercise names are hidden
- automatic 45-second rest timer after each completion
- automatic day completion and next-day unlock
- streak + completed-day history
- localStorage persistence
- JSON export/import backup
- no backend and no external libraries

## GitHub Pages

1. Create a new GitHub repository.
2. Upload `index.html`, `styles.css`, `app.js`, and `README.md`.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, choose `main` and `/root`, then save.
5. GitHub will publish the site.

## Important data limitation

This app stores progress locally in the browser. A static website cannot guarantee permanent data if the browser/site data are manually cleared, the device is reset, or private browsing is used. Use **Backup / Export JSON** regularly and keep the backup file somewhere safe.

## Program design note

The exercise list is intentionally general and conservative because the intended user has mentioned scoliosis. It is not a substitute for an individualized scoliosis or physiotherapy plan.
