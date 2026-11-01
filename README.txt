MNM Business Hub — Free Offline Accounting App

WHAT IS INCLUDED
- index.html: Bengali business accounting app
- manifest.webmanifest: home-screen app metadata
- sw.js: offline app-shell cache after HTTPS hosting

FEATURES
- Dashboard: total customer balances, payments, customer count
- Customer list, contact details, and customer search
- Transactions: credit sales, payments, adjustments/returns
- Customer ledger, date/month filter, transaction history filters
- Due reminders while the app is open
- JSON backup and restore, transaction CSV export, print/save as PDF
- Local-only storage; no account, server, or automatic sync

IMPORTANT DATA RULES
- Every phone/browser has its own separate data. Nadir's iPhone and Mohin's Android do not sync with each other.
- Export a JSON backup regularly and keep it somewhere safe.
- Restore replaces the data currently in that browser. Back up current data first.
- Clearing browser/site data may erase the app's saved records.
- Old versions' data do not automatically migrate. Use a compatible backup and verify totals after restoring.
- Adjustments: positive amount reduces the balance; negative amount increases it.
- Reminders appear inside the app while opened; no push notifications are sent when it is closed.

INSTALLATION (AFTER PUBLISHING)
1. Publish the contents of this folder to an HTTPS static host (upload the files, not the ZIP itself if the host asks for site files).
2. iPhone: open the HTTPS site in Safari > Share > Add to Home Screen.
3. Android: open the HTTPS site in Chrome > menu > Install app / Add to Home screen.
4. Add a test customer and test sale/payment, then confirm totals and backup/restore before entering real records.

STATUS / LIMITATIONS
This ZIP is a prepared website package, not an already-installed app. It has not been published from this workspace and has not been tested on physical iPhone/Android devices. HTTPS hosting is still required for installable/offline PWA behavior. This app is a simple record-keeping aid, not a substitute for keeping verified financial records.
