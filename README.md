# Sandip PMJ Copy Filter Tool

A mobile-first, glassmorphism-styled web tool for filtering Form Numbers from Excel/CSV files.

## Features
- Mobile-first responsive layout with large tap targets
- English interface with customizable title and accent/background colors
- Upload a profile photo and a custom background photo in Settings
- Filters rows where `Verification Status` is blank and `Digitization Done` is `Yes`
- Copy each Form Number individually; copied numbers disappear from the pending list
- Total, Completed, and Remaining counters
- File processing happens locally in the browser

## Run locally
Open `index.html` in a modern browser. An internet connection is required to load the SheetJS spreadsheet library from a CDN.

## Publish with GitHub Pages
1. Create a repository on GitHub.
2. Extract this ZIP and upload the **contents** (not the ZIP itself) to the repository root.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, branch `main`, folder `/(root)`, then Save.
5. Wait for the Pages URL to appear in Settings → Pages.

Settings including custom images are saved in the current browser's local storage. They are not automatically shared to other devices or browsers. If you want the custom background photo to appear for every visitor by default, add the image to the repository and customize the default setting in `index.html`.
