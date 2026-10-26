# Sandip PMJ Copy Filter Tool

A mobile-friendly, English-language Glassmorphism web app for filtering Form Numbers from Excel/CSV exports.

## Features
- Filters rows where **Verification Status is blank** and **Digitization Done = Yes**.
- Shows each matching Form Number with an individual Copy button.
- Removes a number from the visible list after successful copy and keeps Total / Completed / Remaining counters.
- Saves copied-number locks in the current browser using local storage.
- Includes Sandip's profile photo in the site header, plus Settings to change the title, colors, and profile photo.
- Processes uploaded spreadsheets locally in the browser; the spreadsheet file is not uploaded to a server.

## Publish with GitHub Pages

1. Create a new repository on GitHub, for example `sandip-pmj-copy-filter-tool`.
2. Upload **all files and folders in this ZIP**. Keep `index.html` at the repository root and keep `assets/profile.jpg` inside the `assets` folder.
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/(root)**, then click **Save**.
6. Wait for GitHub Pages to finish publishing. The site URL will appear in Settings → Pages, usually in the form `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`.

## Notes
- Excel support loads SheetJS from a CDN, so the visitor needs an internet connection when using Excel files. CSV support currently uses the same library path.
- The site is static and does not require a backend or API key.
- The uploaded profile photo and theme customizations made in Settings are stored in that browser only. The default photo is bundled in `assets/profile.jpg` so it appears for every visitor on first load.
