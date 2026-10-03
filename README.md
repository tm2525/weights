# APEX — Modular Coach × Scarci (offline-capable PWA)

Single-page training app: 20-block modular programming, three one-tap year presets (Hyrox · Climber/Runner · Recomp), live session + cardio logging with free-text extra exercises, 1RM tiles with % → kg, Extras (generators, fatigued runs, Invictus-style, 21-15-9), embedded Hyrox Forge, Fuel/Work/Tendon, searchable Index. Works fully offline once installed.

## Deploy (GitHub Pages) — upload ALL files
1. Create a repository (e.g. `apex`)
2. Add file → Upload files → drag in all of: index.html, sw.js, manifest.webmanifest, icon-180.png, icon-512.png → Commit
3. Settings → Pages → Deploy from a branch → main / (root) → Save
4. Open https://<your-username>.github.io/apex/ once while online
5. Safari → Share → Add to Home Screen

## Notes
- Offline: service worker caches the app on first online visit; data lives on-device regardless
- Updates: overwrite files in the repo; picked up next online open
- Data is per-device — use Export on the Plan tab regularly
