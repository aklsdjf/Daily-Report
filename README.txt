TK Report (web) 1.1
====================
Files: index.html, sw.js, manifest.webmanifest, icon-192.png, icon-512.png, apple-touch-icon.png
Keep them all together in the same folder.

Host on GitHub Pages (free)
1. github.com > New repository (public), e.g. "tk-report".
2. Add file > Upload files: drag in the CONTENTS of this folder (not the folder itself). Commit.
3. Settings > Pages > Source: "Deploy from a branch", Branch: main, folder: / (root). Save.
4. After a minute the site is at https://<your-username>.github.io/tk-report/

Install on iPhone
1. Open that address in Safari.
2. Share button > Add to Home Screen > Add.
3. Open it from the Home Screen icon. It works offline after the first load.
4. Send: opens the iOS share sheet with "TK Report.xlsx" (choose Outlook/Mail). Falls back to a download if sharing isn't available.

Notes
- Data is stored on the phone only (localStorage). Clearing Safari website data erases it.
- To update, upload the new files over the old ones; the app picks up changes when online.
- Time links and the Setup screen are intentionally not included.
- The sent spreadsheet has the same merged cells and row heights as your report sheet, so copy A1:R208 and paste at A1.
