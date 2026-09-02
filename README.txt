MY MONEY MANAGER - ANDROID + iPHONE / iPAD INSTALLATION

VERSION v2.4 iOS COMPATIBLE

UPLOAD
1) Unzip this folder.
2) Upload the WHOLE folder to an HTTPS host such as GitHub Pages or Netlify.
3) Open the HTTPS link on the phone.

ANDROID (Chrome)
- Open the website.
- Tap Install App, or Chrome menu > Add to Home screen / Install app.

iPHONE / iPAD (Safari)
- Open the website in Safari.
- Tap the app's “Install on iPhone” button to see instructions, or directly tap Safari Share.
- Choose Add to Home Screen.
- Tap Add.

IMPORTANT FOR iOS
- Use Safari for installation. Browsers on iPhone may not offer Add to Home Screen in the same way.
- The app now includes Apple home-screen metadata and a 180x180 Apple touch icon.
- The bottom navigation respects the iPhone safe-area.
- Backup JSON and CSV exports use the iOS Share Sheet when supported, so you can Save to Files, AirDrop, email, etc.
- Restore JSON works through the iOS Files picker.

DATA
- Records remain stored locally on that phone/browser using localStorage.
- Back up JSON regularly.
- To move between Android and iPhone: Backup JSON on the old device and Restore JSON on the new device.
- Offline use works after the app has successfully loaded online at least once.

UPDATE v2.4
- Added iPhone/iPad PWA metadata.
- Added Apple touch icon.
- Added iOS-specific installation guidance.
- Improved backup/CSV saving on iOS using the Share Sheet when available.
- Kept all v2.2 Current Balance, Debtor and Creditor accounting behavior unchanged.
- Service worker cache updated to v2.4.

WHEN UPDATING GITHUB
Replace all files with this package, especially index.html, manifest.webmanifest, sw.js and apple-touch-icon.png.
After GitHub Pages deploys, open the website once in Safari/Chrome while online.
If an older installed shortcut is cached, close/reopen it. If needed, remove the old Home Screen shortcut and add it again.


v2.4 MOBILE INTERFACE UPDATE
- Mobile-first dashboard with Current Balance highlighted.
- One-tap Quick Add buttons for Income, Expense, Debtor and Creditor.
- Transaction, ledger and payment-history tables become readable card lists on phones.
- Larger 16px form controls to prevent iPhone Safari auto-zoom.
- Larger touch targets and simplified bottom navigation for Android/iOS.
- Existing transaction/current-account/debtor/creditor calculations are unchanged.
