# HASHTAGSX Admin Portal

Static page (no build step). Shows orders from `hashtagsx-api` and lets you change their status.

## Setup
1. Open `config.js` and set `window.API_URL` to your deployed API address.
2. Push this folder to its own GitHub repo.
3. Vercel > Add New Project > import the repo. Framework: Other. No build command, output directory `.`.
4. Open the site and sign in with the `ADMIN_PASSWORD` you set on the API.
5. Add the admin site address to `ALLOWED_ORIGINS` on the API, then redeploy the API.
