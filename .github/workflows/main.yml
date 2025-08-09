# QuitBuddy Desktop Installer Repo

This repository packages the QuitBuddy frontend into an Electron app and includes a GitHub Actions workflow to build a Windows installer (.exe) using electron-builder (NSIS).

## How it works
- Push this repository to GitHub (to the `main` branch).
- The workflow `.github/workflows/build-windows.yml` runs on push or manual dispatch and builds the installer on `windows-latest` runner.
- Once the workflow completes, download the artifact named `QuitBuddy-Windows-Installer` from the workflow run (contains `dist/*` with installer).

## Customization
- Replace `app/` content with your finalized frontend (HTML/CSS/JS). This package already includes a working frontend from the FinalQuitBuddyRelease.
- Add your `build/icon.ico` for Windows icon.
- Update `package.json` metadata (publisherName, appId) if desired.

## Local testing
To test locally (development):
1. Install Node.js (v18+) and npm.
2. `npm install`
3. `npm start` to run Electron app locally.

To build locally (requires build tools):
1. `npm install`
2. `npm run dist` (generates installers in `dist/`)

