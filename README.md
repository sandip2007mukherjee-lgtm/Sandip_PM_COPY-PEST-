# Sandip PMJ Copy Filter Tool

A mobile-first, responsive single-page tool for filtering Form Numbers from Excel/CSV files.

## Features
- English UI with a glassmorphism-inspired visual system
- Mobile-friendly touch targets and responsive layout
- Excel/CSV filtering: `Verification Status` is blank and `Digitization Done` is `Yes`
- Copy each Form Number once; copied numbers disappear from the pending list
- Total, Completed, Remaining, and completion progress
- Customizable accent/background colors, profile photo, and background photo
- Accessible focus states, live status announcements, and reduced-motion support
- Files are processed locally in the browser

## Deploy with GitHub Pages
1. Create a GitHub repository.
2. Upload the contents of this folder to the repository root (not the ZIP itself).
3. Open **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/(root)`, then save.
5. Open the URL shown in the Pages settings after deployment finishes.

The spreadsheet parser loads from a CDN, so Excel/CSV parsing requires an internet connection. Theme customizations are stored in the current browser and are not shared with other visitors.
