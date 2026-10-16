PROPEDGE DAILY — ZERO-COST STARTER

FILES
- index.html: responsive sports picks dashboard
- manifest.webmanifest: installable web app metadata
- sw.js: basic offline shell cache
- icon.svg: app icon

FEATURES
- Add/edit-independent player prop entries
- Mark results Win/Loss/Push
- Record summary counts
- Local browser storage
- Export/import JSON backup
- PWA install metadata and service worker

IMPORTANT LIMITS
- This is a front-end prototype, not a deployed public app.
- No live sports data, user login, cloud sync, payment/subscription handling, or push notifications.
- Browser storage is local to that browser/device; export backups.
- PWA install/offline behavior generally requires HTTPS hosting or localhost. Opening the HTML file directly is useful for testing but won't enable all install features.
- Replace placeholder demo picks with sourced, current research before publishing.
- Review gambling/sports-data laws and provider terms before monetizing.

NO-CODE NEXT STEP
1. Test index.html locally.
2. Publish the folder to a static HTTPS host (for example, a free static hosting tier) by following that host's current upload instructions.
3. Open the HTTPS URL on Android Chrome and use Install app / Add to Home screen if available.
4. For public multi-user subscriptions, add a supported auth/database/payment service later; this cannot be safely simulated by localStorage.
