# Office Late Records

Simple HTML-based late attendance tracker. Hosted on GitHub Pages.

## Files
- `index.html` — Public read-only view (anyone can access via URL)
- `admin.html` — Password-protected admin panel (add/edit/delete + GitHub auto-commit)
- `data.json` — Records data store

## Admin Access
Open `admin.html` and enter password: `dev@123`

## Deploying to GitHub Pages
1. Push this folder to https://github.com/devendrakumar-max/Late-Records
2. In repo Settings → Pages → Source: `main` branch, root folder
3. Public URL will be: `https://devendrakumar-max.github.io/Late-Records/`
4. Admin URL: `https://devendrakumar-max.github.io/Late-Records/admin.html`

## Admin Workflow
1. Login to `admin.html` with password
2. Add/Edit/Delete records
3. Create a GitHub Personal Access Token at: https://github.com/settings/tokens/new?scopes=repo
4. Paste token into admin panel → Click **"Commit to GitHub"**
5. Public page auto-updates in ~1 minute (GitHub Pages cache)

## Fields
- Date, Employee Name, Arrive Time, Reason
- Penalty Paid (Yes/No)
- Penalty Mode (Cash / Party)
- Penalty Date
- Party Details (what was served, if party)
