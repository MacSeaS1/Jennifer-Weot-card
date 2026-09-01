# Jennifer Weot — Macomb County Digital Business Card

Cloudflare Worker for Jennifer Weot's Macomb County Planning and Economic Development digital business card.

## Project structure

- `wrangler.toml` — Cloudflare Worker configuration
- `package.json` — Wrangler scripts and development dependency
- `src/index.js` — complete Worker application

## GitHub-to-Cloudflare deployment

1. Create a new GitHub repository.
2. Extract this ZIP and upload all project files while preserving the `src` folder.
3. In Cloudflare, open **Workers and Pages** and choose **Create application**.
4. Select **Import a repository** and connect the GitHub repository.
5. Use `npm install` as the build command if Cloudflare requests one.
6. Use `npx wrangler deploy` as the deploy command.
7. Deploy the Worker.

The QR code, page canonical URL and downloadable vCard automatically use the active Cloudflare Worker URL. No URL replacement is required after deployment.

## Local Wrangler deployment

```bash
npm install
npm run deploy
```

## Included contact information

- Jennifer Weot
- Senior Outreach Specialist
- Fueling the Talent Pipeline
- Cell: 586-524-2987
- Email: Jennifer.Weot@MacombGov.org
- Macomb Business, Planning and Economic Development, and LinkedIn links

