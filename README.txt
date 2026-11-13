MYSPEND — iPhone browser app starter

WHAT THIS IS
A mobile-first personal expense tracker. It stores transactions in browser localStorage on this device, uses INR, supports expense/income entry, categories, monthly budget, history/search/edit/delete, simple reports, light/dark appearance, and CSV export. It includes a service worker for offline app-shell caching.

IMPORTANT
- This is a browser-based web app, not an App Store app or a signed native iOS app.
- Host these files on an HTTPS static website, then open the URL in Safari and add it to the Home Screen.
- Visit the hosted app once while online so the offline shell can be cached.
- Expense records stay in this browser on this iPhone. Do not clear Safari website data or remove site data if you need those records.
- Export CSV backups regularly. CSV export contains transactions, not settings/budget.
- Clearing browser/site data, switching browsers, or reinstalling/resetting may lose locally stored records.
- Test the app before relying on it for important financial records.

PUBLISH FROM IPHONE (GitHub Pages)
1. Sign in or create a free GitHub account in Safari.
2. Create a new public repository named myspend-app.
3. Use Add file > Upload files, select the extracted files in this folder, and commit.
4. In repository Settings > Pages, choose Deploy from a branch; select main and /(root), then Save.
5. Wait for GitHub Pages to publish. Open the displayed HTTPS URL in Safari.
6. In Safari tap Share > Add to Home Screen. Keep Open as Web App enabled if shown, then tap Add.
7. Open MySpend once while online. Then test airplane mode.

Do not upload personal expense exports to the repository. Only upload the app files in this package.
