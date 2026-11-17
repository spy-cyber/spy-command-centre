# SPY Command Centre 4.0

A mobile-first installable Progressive Web App for personal finance, debt repayment, career applications, daily tasks, savings goals, learning progress and reports.

## Deploy / upgrade on GitHub Pages

1. Download and extract this ZIP.
2. In your existing `spy-command-centre` GitHub repository, choose **Add file → Upload files**.
3. Upload all five files from this folder and replace the existing files with the same names.
4. Commit the changes to the `main` branch.
5. GitHub Pages should automatically rebuild from `main` and `/(root)`.
6. Open `https://spy-cyber.github.io/spy-command-centre/` in Chrome.

## Important data migration

Version 4.0 uses the same website origin and reads the existing `spy-command-centre-v3` browser storage key. It migrates existing Version 3 records into the Version 4 storage key without deleting the Version 3 key. Existing records include transactions, debt repayments, applications, tasks, learning goals and salary/debt settings. New fields receive safe defaults.

**Before upgrading:** In Version 3, open Reports / Settings and download a JSON backup if the export option is available in your build. Keep that file safe. The app stores data locally in the browser; it does not sync between devices.

After upload, reopen the installed app while online. If the old screen remains, fully close the app and reopen it, or open the site in Chrome and refresh. The updated service worker uses a new cache version.

## Privacy and limitations

- Data is stored locally in the browser on this device.
- There is no account login, server, cloud sync or app-level encryption.
- Do not store passwords, PINs or highly sensitive information.
- Export backups regularly. Clearing browser/site data can erase local records.
- This is a personal organiser, not a bank account or financial institution.
