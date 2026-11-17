# SPY Command Centre 3.0

A mobile-first installable web app (PWA) for personal finance, debt tracking, job applications, tasks and learning goals.

## What's included
- Local data persistence in the browser using localStorage
- Income and expense ledger
- Debt repayment history
- Job application pipeline and status updates
- Daily task checklist
- Learning goals and progress sliders
- Financial and career summaries
- JSON backup/restore and transaction CSV export
- Offline caching after first successful load
- Add-to-home-screen support

## Important privacy note
Data stays in the browser profile on the device where it is entered. It is not synced to an online account and is not encrypted by this app. Anyone with access to the unlocked browser profile may be able to view it. Export backups and keep them somewhere private. Do not store passwords, bank credentials or highly sensitive information.

## Install on Android
1. Publish the contents of this folder to a static HTTPS host (for example, a GitHub Pages site).
2. Open the published HTTPS address in Chrome on your Android phone.
3. Open Chrome's three-dot menu and choose **Install app** or **Add to Home screen**.
4. Confirm. The app will appear on your home screen and open in its own app-style window.

## Install on iPhone
Open the published HTTPS address in Safari → Share → Add to Home Screen.

## Publish with GitHub Pages
1. Sign in to GitHub and create a new public repository, e.g. `spy-command-centre`.
2. Upload all files from this folder to the repository root (not the ZIP itself).
3. In the repository, open Settings → Pages.
4. Under Build and deployment, select Deploy from a branch, choose `main` and `/ (root)`, then Save.
5. Wait for GitHub Pages to publish, then open the provided HTTPS address on your phone and install it.

You can also use another static HTTPS hosting service. Do not publish personal backup files or transaction exports in the hosting repository.

## Updating
Replace the app files on the host with the newer version. Reopen the app while online so the service worker can fetch the update.

## Technical notes
This is a static Progressive Web App. No server or paid backend is included. Data is local to one browser/device. Clearing browser site data may erase app records; export a backup regularly.
