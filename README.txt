THE CARD VAULT v1.0

DEPLOY TO GITHUB PAGES
1. Create a new GitHub repository named Card-Vault (or use an existing repository).
2. Upload index.html, app.js, sw.js, and manifest.webmanifest to the repository root (not the zip).
3. In repository Settings > Pages, choose Deploy from a branch, main, /(root), and Save.
4. Open the resulting GitHub Pages URL on iPhone Safari. Share > Add to Home Screen.

DATA AND SAFETY
- IndexedDB stores all cards and compressed photos in the current browser/device.
- GitHub Pages hosts the app code, NOT the card database.
- Backups > Download JSON regularly. Save the downloaded file in iCloud Drive or another safe location.
- Backups > Restore JSON replaces the full local inventory.
- CSV export/import is available for bulk entry, but CSV does not contain photos.
- CSV imports append records; there is no automatic duplicate detection.
- Different devices will have independent collections unless you manually transfer JSON backups.
- Photos are compressed; retain original photographs separately.
- App does not automatically recognize cards or fetch market prices.
- Do not use private browsing for permanent storage.
