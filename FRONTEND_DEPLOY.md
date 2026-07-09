# VANYAA Frontend - Vercel

Deploy this folder to Vercel as a static site.

## Before Deploying

After your Render backend is live, open `config.js` and set:

```js
window.VANYAA_API_BASE = "https://your-render-service.onrender.com";
```

Use the exact Render URL, without a trailing slash.

## Vercel Settings

- Framework preset: Other
- Build command: leave empty
- Output directory: leave empty

`vercel.json` already routes:

- `/` to the player site
- `/user` to the player site
- `/crm` to the admin CRM

## Admin Login

The admin code is controlled by the backend `CRM_LOGIN_CODE` environment variable on Render.

