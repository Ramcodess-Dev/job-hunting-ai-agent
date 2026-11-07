# CareerPilot AI

Ramcodess Dev's job-search workspace. This is an independent browser app with live remote-role discovery, a persistent application tracker, and editable career writing tools.

## Run locally

Open `public/index.html` in a browser, or start a static server:

```bash
npx serve public
```

No build step, account, or API key is needed. Search listings require an internet connection. The tracker and drafts stay in browser storage on the device being used.

## Working features

- Search current remote job listings by keyword and location.
- Save real listings to an application tracker, update status, remove entries, or export CSV.
- Add applications manually.
- Generate editable cover-note, follow-up, and interview-practice drafts from supplied role context.
- Compare resume and job-description keywords locally in the browser.
- Responsive layout for desktop and mobile.

## Job data and privacy

Remote listings come from [Remotive's public API](https://remotive.com/remote-jobs/api), are cached in the browser for six hours, can be delayed by up to 24 hours, and link back to Remotive. Drafts, pasted resumes, and application records stay in local browser storage and are not sent to a server. Drafts use editable templates; an external AI model is not currently connected.

## Deployment

The repository is not currently deployed. Once the app is ready, GitHub Pages can publish the `public/` directory. Add a workflow under `.github/workflows/` or choose Pages deployment from repository settings.

## License

MIT. Copyright (c) 2026 Ramcodess Dev.
