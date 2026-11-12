MY BUDGET — PRIVATE IPHONE HOME SCREEN APP

1. Unzip this folder.
2. Upload the CONTENTS of the my-budget-app folder to a static HTTPS host (for example Netlify Drop at https://app.netlify.com/drop). The host gives you a public URL; anyone who knows it can open the app, but your financial records are stored locally on your own device, not on that hosting service.
3. Open that HTTPS URL in Safari on your iPhone.
4. Tap Share -> Add to Home Screen -> Add.
5. Launch My Budget from the new icon.
6. Update values and tap Save Changes. Changes are stored locally on that phone.
7. Use Backup JSON and save the file in iCloud Drive regularly. Use Restore backup to recover or transfer records.
8. Use Export Excel-compatible CSV to open monthly and dated totals in Excel or Numbers. CSV export is NOT automatic Excel file synchronization.

IMPORTANT LIMITATIONS:
- This is a Progressive Web App, not an App Store native app.
- iOS Safari/PWA does not guarantee physical haptic feedback through navigator.vibrate().
- Local storage can be deleted when you clear website data, delete the app, or change devices. Keep backups.
- The app files are hosted at a public URL unless you choose a private hosting service. Financial records are local to your phone, but the app URL is not access-restricted.
- Monthly snapshots are separate from daily entries; weekly summaries use dated entries only, avoiding double-counting.
