UPDATE v2.8
------------
- Save Transaction saves the entry, clears its completed values, hides saved-record lists, and immediately returns to the Dashboard.
- When Income & Expenses is opened again from the top tab, bottom navigation, or Quick Add, the clean form automatically focuses the Amount field for the next entry.
- After creating a Debtor/Creditor record, the clean form remains ready for the next record and automatically focuses Person / Company.
- Previously entered transaction and debtor/creditor lists stay hidden during entry. They appear only when View Saved Transactions or View Saved Loans / Records is pressed.
- Unlocking always opens the Dashboard.
- Existing v2.7 data, multiple-loan-by-person features, and localStorage remain compatible.
- Service worker cache updated to v2.8.

MY MONEY MANAGER - ANDROID + iPHONE / iPAD INSTALLATION

VERSION v2.8 iOS COMPATIBLE

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


UPDATE v2.6
- Unlocking the app now always opens the Dashboard, regardless of which screen was open when it was locked.
- After saving an Income/Expense entry, the form stays ready for the next entry, clears the completed values, and focuses the Amount field.
- After creating a Debtor/Creditor record, the form stays ready for the next entry, clears the completed values, and focuses Person / Company.
- Saved transaction and ledger lists are hidden during data entry so the record just entered is not displayed again automatically.
- Use “View Saved Transactions” or “View Saved Loans / Records” when you intentionally want to review old entries.
- Existing v2.5 data and localStorage remain fully compatible.
- Service worker cache updated to v2.6.

UPDATE v2.5
- Added “Loans by Person” for Debtors and Creditors.
- Select one person to see all of their separate loans/records, original totals, paid totals and total outstanding.
- Added “All Loans” on each ledger record for quick access to that person’s full loan list.
- Existing names are suggested when creating another debtor/creditor record.
- Saving an Income/Expense transaction now returns to the Dashboard automatically.
- Saving a Debtor/Creditor payment now returns to the Dashboard automatically.
- Existing Current Balance, Debtor, Creditor and localStorage data remain compatible.
- Service worker cache updated to v2.5.

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
