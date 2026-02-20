# Intergalactic March Landing Page

Official landing page for Alexandr Misko's single **Intergalactic March** from the upcoming album **Final Boss**.

## Tech
- Single static file: `index.html`
- Static assets in `assets/`
- No build step required

## Public Repo Safety
This repository is public.  
Do **not** commit secrets (API keys, private tokens, passwords, private credentials).

Safe to keep in this repo:
- Public music links
- Public social links
- Public Google Apps Script Web App URL for form submission

## Local Preview
Run:

```bash
cd /Users/guy/codex-app/intergalactic-march-landing-page && python3 -m http.server 8080
```

Open:
- `http://localhost:8080`

## Deploy (GitHub Pages)
1. Push changes to `main`.
2. In GitHub: `Settings` -> `Pages`.
3. Source: `Deploy from a branch`.
4. Branch: `main`, folder: `/ (root)`.
5. Save and wait 1-3 minutes.

## Main Configuration
Edit the `PAGE_CONFIG` object near the bottom of `index.html`:
- `youtubeEmbedUrl`
- `albumReleaseISO`
- `streamingLinks`
- `tablatureBuyUrl`
- `umbrellaStreetUrl`
- `socialProfiles.tiktok`
- `assets.intergalacticCover`
- `assets.umbrellaCover`
- `subscribe.googleAppsScriptUrl`

If `subscribe.googleAppsScriptUrl` is empty, subscribe form stays local-only and does not store emails.

## Assets
Place image files in `assets/`:
- `assets/intergalactic-march.jpg`
- `assets/umbrella-street.jpg`
- `assets/tablature-preview.jpg`

